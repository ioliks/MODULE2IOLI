<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>module2</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }

        header {
            text-align: center;
            margin-bottom: 20px;
        }

        header h1 {
            font-size: 2rem;
            color: #333;
        }


        .section {
            border: 1px solid black;
            padding: 20px;
            margin: 10px;
            position: relative;
            background-color: #f4f4f4;
        }

        .section .title {
            position: absolute;
            top: 10px;
            right: 10px;
            background-color: #ffdd57;
            color: black;
            padding: 5px;
            border: 1px solid black;
        }


        .section-chicken {
            background-color: #ffefdb;
        }

        .section-beef {
            background-color: #fddede;
        }

        .section-sushi {
            background-color: #dff6ff;
        }

        /* Media Queries */


        @media (min-width: 992px) {
            main {
                display: flex;
                justify-content: space-between;
            }

            .section {
                flex: 1;
                margin: 10px;
            }
        }


        @media (min-width: 768px) and (max-width: 991px) {
            main {
                display: flex;
                flex-wrap: wrap;
            }

            .section {
                width: 48%;
                margin: 1%;
            }

            .section-sushi {
                width: 100%;
            }
        }

        @media (max-width: 767px) {
            .section {
                width: 100%;
                margin: 10px 0;
            }
        }

        @media (max-width: 767px) {
            .section {
                width: 100%;
                margin: 10px 0;
            }
        }
    </style>

<body>
    <header>
        <h1>MODEL 2</h1>
    </header>
    <main>
        <section class=" section section-chicken">
            <div class="title">TITLE 1</div>
            <p>Some explanation here.</p>
        </section>
        <section class=" section section-beef">
            <div class="title">TITLE 2</div>
            <p>Some explanation here.</p>
        </section>
        <section class="section section-sushi">
            <div class="title">TITLE 3</div>
            <p>LSome explanation here.</p>
        </section>
    </main>
</body>


</html>

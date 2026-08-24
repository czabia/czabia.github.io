<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>CZABIA | Coming Soon</title>

    <style>

        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;

            font-family: Arial, Helvetica, sans-serif;

            background: #faf9f7;
            color: #333;

            text-align: center;
        }

        .container {
            width: 90%;
            max-width: 700px;

            padding: 50px 20px;
        }

        /* LOGO */

        .logo {
            width: 300px;
            max-width: 75%;
            height: auto;

            margin-bottom: 45px;
        }

        /* MAIN TITLE */

        h1 {
            font-size: 32px;
            font-weight: 400;

            letter-spacing: 1px;

            margin: 0 0 30px 0;
        }

        /* DIVIDER */

        .divider {
            width: 160px;

            margin: 0 auto 30px auto;

            display: flex;
            align-items: center;
            justify-content: center;

            gap: 15px;
        }

        .divider::before,
        .divider::after {
            content: "";

            height: 1px;

            background: #bbb;

            flex: 1;
        }

        .divider span {
            font-size: 16px;
        }

        /* TEXT */

        p {
            font-size: 17px;

            line-height: 1.7;

            color: #666;

            margin: 8px 0;
        }

        /* EMAIL */

        .email {
            display: inline-block;

            margin-top: 15px;

            font-size: 17px;

            color: #333;

            text-decoration: none;

            font-weight: 600;
        }

        .email:hover {
            text-decoration: underline;
        }

        /* FOOTER */

        .footer {
            margin-top: 55px;

            font-size: 14px;

            color: #999;
        }

    </style>
</head>


<body>

    <div class="container">

        <!-- YOUR LOGO -->

        <img
            src="logo.png"
            alt="CZABIA logo"
            class="logo"
        >


        <!-- MAIN MESSAGE -->

        <h1>
            Our website is currently<br>
            under construction
        </h1>


        <!-- DIVIDER -->

        <div class="divider">
            <span>♥</span>
        </div>


        <!-- TEXT -->

        <p>
            We're working on something new and exciting.
        </p>

        <p>
            CZABIA is still here — we'll be back soon!
        </p>


        <!-- CONTACT -->

        <p style="margin-top: 30px;">
            In the meantime, for any questions or enquiries,<br>
            please contact us at:
        </p>


        <a
            class="email"
            href="mailto:info.czabia@gmail.com"
        >
            info.czabia@gmail.com
        </a>


        <!-- FOOTER -->

        <div class="footer">
            Thank you for your patience ♥
        </div>

    </div>

</body>
</html>

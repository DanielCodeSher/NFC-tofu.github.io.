<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TOFU POAP</title>
    <link rel="stylesheet" type="text/css" href="style.css">
    <link rel="shortcut icon" href="/favicon.png" type="image/x-icon">
</head>

<body>
    <nav>
        <img src="img/logo.png" alt="Logo">
    </nav>

    <main>
        <div class="box">
            <img src="/start.png" alt="star">

            <h1>NFC POAP
                <A> GENERATOR </A>
            </h1>
            <p>
                Is a service that t0fu.tech provide to the
                POAP for community as a way to generate random links
                to deliver mint links though NFC technology.
            </p>
            <div class="drag-Area">
                <img src="/upload.png" alt="uploadicon" href="#">
                <header id="dragText">Drag your file with poap links here</header>
                <h6> TXT file max 5MB </h6>
                <input type="file" id="upload" style="display: none;">
                <label class="upload-button" for="upload">SELECT FILE</label>
            </div>
            <div class="email">
                <p>Enter your email to save your links</p>
                <input type="email" name="email" id="email">
                <button class="getlink" id="btn"> GET LINK </button>
            </div>
        </div>
    </main>

    <footer>

    </footer>
</body>
<script src="script.js"></script>
</body>

</html>

<!DOCTYPE html>
<html>
<head>
    <title>W3.CSS</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-aFq/bzH65dt+w6FI2ooMVUpc+21e0SRygnTpmBvdBgSdnuTN7QbdgL+OapgHtvPp" crossorigin="anonymous">
    <style>
        .img1 {
            width: 900px;
            margin-right: 80%;
        }
        #divone {
            background-color: #3269a8;
            color: white;
        }
        #div2 {
            background-color: gray;
        }
        #h2 {
            color: white;
        }
        .dropdown {
            position: relative;
            display: inline-block;
        }
        .dropbtn {
            background-color: #3269a8;
            color: white;
            padding: 10px;
            font-size: 16px;
            border: none;
            cursor: pointer;
        }
        .dropdown-content {
            display: none;
            position: absolute;
            z-index: 1;
            background-color: #3269a8;
            color: #ffffff;
            text-decoration: none;
        }
        .dropdown-content a {
            color: white;
            padding: 12px 16px;
            text-decoration: none;
            display: block;
        }
        .dropdown-content a:hover {
            background-color: gray;
            color: black;
        }
        .dropdown:hover .dropdown-content {
            display: block;
        }
    </style>
</head>
<body id="body" class="body">
    <div id="div2">
        <img src="https://thumbs.dreamstime.com/b/design-code-logo-template-illustration-106362967.jpg" width="100px">
        <h2 id="h2">edCODE</h2>
    </div>
    <div id="divone">
        <a href="menu.html" class="w3-bar-item w3-button">Početna</a>
        <a href="convert.html" class="w3-bar-item w3-button">Konvertuj u HTML tag</a>
        <a href="clean.html" class="w3-bar-item w3-button">Očisti HTML kod</a>
        <a href="list.html" class="w3-bar-item w3-button">Napravi listu</a>
        <a href="change.html" class="w3-bar-item w3-button">Izmeni tabelu</a>
    </div>
    <br>
    <img src="https://play-lh.googleusercontent.com/xcl9ZcT0QDPx8Bnkr4Ct-VY4P5HjQ_iMxkwmRxmMqV3TfMNiHJyXs0ppjLp2XcyzA3w=w240-h480" class="img1">
</body>
</html>

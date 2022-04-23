
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <style>
        div.gallery {
            border: 1px solid #ccc;
        }
        
        div.gallery:hover {
            border: 1px solid #777;
        }
        
        div.gallery img {
            width: 100%;
            height: auto;
            border-right: #F90F13
        }
        
        div.desc {
            padding: 15px;
            text-align: center;
        }
        
        * {
            box-sizing: border-box;
        }
        
        .responsive {
            padding: 0 6px;
            float: left;
            width: 24.99999%;
            border-radius: 100pt;
        }
        
        @media only screen and (max-width: 700px) {
            .responsive {
                width: 49.99999%;
                margin: 6px 0;
            }
        }
        
        @media only screen and (max-width: 500px) {
            .responsive {
                width: 50%;
            }
        }
        
        .clearfix:after {
            content: "";
            display: table;
            clear: both;
        }
        
        .reponsive {
            border-style: solid;
            border-style: solid;
            border-color: red;
        }
    </style>
</head>

<body>

    <div class="responsive">
        <div class="gallery">
            <a target="_blank" href="https://pixabay.com/vi/photos/th%c3%ba-v%e1%ba%adt-linh-tr%c6%b0%e1%bb%9fng-6930449/">
                <img src="animal-ge14562f14_640.jpg" alt="Cinque Terre" width="600" height="400">
            </a>
            <div class="desc">Add a description of the image here</div>
        </div>
    </div>


    <div class="responsive">
        <div class="gallery">
            <a target="_blank" href="https://cdn.pixabay.com/photo/2022/04/16/16/42/black-shouldered-kite-7136585__340.jpg">
                <img src="black-shouldered-kite-g996a57ed0_640.jpg" alt="Forest" width="600" height="400">
            </a>
            <div class="desc">Add a description of the image here</div>
        </div>
    </div>

    <div class="responsive">
        <div class="gallery">
            <a target="_blank" href="https://cdn.pixabay.com/photo/2022/04/11/07/15/deer-7124972__340.jpg">
                <img src="deer-g10dab4bd1_640.jpg" alt="Northern Lights" width="600" height="400">
            </a>
            <div class="desc">Add a description of the image here</div>
        </div>
    </div>

    <div class="responsive">
        <div class="gallery">
            <a target="_blank" href="https://cdn.pixabay.com/photo/2021/12/02/18/38/seagulls-6841129__480.jpg">
                <img src= "seagulls-g8eb54db7d_640.jpg"Mountains" width="600" height="400">
            </a>
            <div class="desc">Add a description of the image here</div>
        </div>
    </div>





</body>

</html>


<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>APP download</title>
    <style>
        .out{
            text-align: center;
            margin-top: 15%;
        }
        .block{
            height: 250px; width: 250px;
            border-radius: 10px;
            margin: 30px;
        }
        button{
          background:#85B8Cb;
          color:#fff;
          border:none;
          position:relative;
          height:60px;
          font-size:1.6em;
          cursor:pointer;
          transition:800ms ease all;
          outline:none;
    
        }
        button:hover{
          background:#fff;
          color:#85B8Cb;
        }
        button:before,button:after{
          content:'';
          position:absolute;
          top:0;
          right:0;
          height:2px;
          width:0;
          background: #85B8Cb;
          transition:400ms ease all;
        }
        button:after{
          right:inherit;
          top:inherit;
          left:0;
          bottom:0;
        }
        button:hover:before,button:hover:after{
          width:100%;
          transition:800ms ease all;
        }
    </style>
</head>
<body>
    <div class="out">
        <button class="block" onclick="window.open('https://play.google.com/store/apps/details?id=appinventor.ai_minjuju0518.handwash_2');">
            <h4>손씻기 타이머</h4>
            <h6>Download</h6>
        </button>
        <button class="block" onclick="window.open('https://play.google.com/store/apps/details?id=appinventor.ai_minjuju0518.covid_19_3');">
            <h4>물끄기 어플</h4>
            <h6>Download</h6>
        </button>
    </div>
</body>
</html>

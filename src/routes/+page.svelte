<script>
    let images = [
        'logo.png',
        'shittop.png'
    ]

    let image = images[Math.floor(Math.random() * images.length)]
</script>

<head>
    <style>
        body, html {
            height: 100%;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            background-color: #fff;
            font-family: Arial, sans-serif;
        }

        img {
            max-width: 100%;
            height: auto;
        }

        .slogan {
            margin-top: 20px;
            font-size: 24px;
        }
    </style>
</head>
<body>
    <div class="content">
        <img src={image} alt="Logo" height=400px width=400px>
        <p class="slogan">Bird Shit Software LLC</p>
    </div>
</body>
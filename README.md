<html lang="vi">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thiệp 8/3</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
    <style>
        body {
            background: url("background-8-3-31.jpg") no-repeat center center fixed;
            background-size: cover;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            position: relative;
        }

        .openButton {
            padding: 12px 20px;
            background-color: #ff4d6d;
            color: white;
            font-size: 18px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            transition: 0.3s;
        }

        .openButton:hover {
            background-color: #e33b5d;
        }

        .wrapperLetterForm {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.7);
            display: none;
            justify-content: center;
            align-items: center;
        }

        .boxLetter {
            background-color: #ffebeb;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            text-align: center;
            width: 400px;
            position: relative;
        }

        .closeButton {
            position: absolute;
            top: 10px;
            right: 10px;
            font-size: 20px;
            cursor: pointer;
            color: #e33b5d;
        }

        .closeButton:hover {
            color: #ff1a40;
        }

        .image-gallery {
            position: absolute;
            top: 50%;
            left: 50%;
            width: 600px;
            height: 500px;
            transform: translate(-50%, -50%);
        }

        .image-gallery img {
            width: 130px;
            height: 215px;
            object-fit: contain;
            position: absolute;
            border-radius: 0;
            background-color: white;
        }



        .image-gallery img:nth-child(1) {
            top: -100px;
            left: 50%;
            transform: translateX(-50%);
        }

        .image-gallery img:nth-child(2) {
            top: 50%;
            left: -100px;
            transform: translateY(-50%);
        }

        .image-gallery img:nth-child(3) {
            bottom: -100px;
            left: 50%;
            transform: translateX(-50%);
        }

        .image-gallery img:nth-child(4) {
            top: 50%;
            right: -100px;
            transform: translateY(-50%);
        }

        .image-gallery img:nth-child(5) {
            top: -80px;
            left: -80px;
        }

        .image-gallery img:nth-child(6) {
            top: -80px;
            right: -80px;
        }

        .image-gallery img:nth-child(7) {
            bottom: -80px;
            left: -80px;
        }

        .image-gallery img:nth-child(8) {
            bottom: -80px;
            right: -80px;
        }
    </style>
</head>

<body>

    <button class="openButton" onclick="openLetter()">Chúc mừng 8/3</button>

    <div class="wrapperLetterForm" id="letterBox">
        <div class="image-gallery">
            <img src="0d8d4c5a-01e1-4728-b967-e8044b015611.jpg" alt="Friend 1">
            <img src="0dea7eb1-3d59-4517-ac14-10f3453002c2.jpg" alt="Friend 2">
            <img src="1cd43c06-bf85-4f9a-977f-5c3c91f3beea.jpg" alt="Friend 3">
            <img src="6d9f4c9c-d5a5-43b9-85d4-11bd19158b3f.jpg" alt="Friend 4">
            <img src="36558900-5bdf-401d-a5aa-ba4ba1ceb9d5.jpg" alt="Friend 5">
            <img src="481713420_1002606788495141_4717442931152258847_n.jpg" alt="Friend 6">
            <img src="bc08fe48-a591-4952-b96c-0b4cf9d39367.jpg" alt="Friend 7">
            <img src="f94a9a27-a3c9-4812-871c-ef15283271e1.jpg" alt="Friend 8">
        </div>

        <div class="boxLetter">
            <i class="fa-solid fa-xmark closeButton" onclick="closeLetter()"></i>
            <h2>Gửi các cậu!</h2>
            <p class="contentLetter">💖 Nhân dịp Quốc tế Phụ nữ 8/3, chúc các bạn nữ lớp 9A luôn vui vẻ, tự tin và ngày
                càng tỏa sáng. Cảm ơn các bạn vì đã luôn là một phần quan trọng của lớp mình! 💖...</p>
        </div>
    </div>

    <script>
        function openLetter() {
            document.getElementById("letterBox").style.display = "flex";
        }

        function closeLetter() {
            document.getElementById("letterBox").style.display = "none";
        }
    </script>

</body>

</html>

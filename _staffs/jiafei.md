---
short_name: jiafei
name: Shen Jiafei
position: 财务总监
---
<head>
    <meta charset="utf-8"> 
    <title>Bootstrap 实例 - 简单的轮播（Carousel）插件</title>
    <link rel="stylesheet" href="http://cdn.staticfile.net/twitter-bootstrap/3.3.7/css/bootstrap.min.css">
    <script src="http://cdn.staticfile.net/jquery/2.1.1/jquery.min.js"></script>
    <script src="http://cdn.staticfile.net/twitter-bootstrap/3.3.7/js/bootstrap.min.js"></script>
    <style>
            .carousel-inner {
                display: flex;
                justify-content: center; /* 水平居中 */
                align-items: center; /* 垂直居中 */
                height: 600px; /* 按需设置一个恰当的固定高度 */
        }

            .carousel-inner > .item {
                flex: 0 0 auto; /* 防止项目伸缩，保持原始大小 */
                width: 100%; /* 使.carousel-item的宽度充满父容器宽度 */
                height: 100%; /* 使.carousel-item的高度充满父容器高度 */
            }

            .carousel-inner > .item > img, 
            .carousel-inner > .item > a > img {
                max-width: 100%; /* 最大宽度100% */
                max-height: 100%; /* 最大高度100% */
                margin: auto; /* 自动外边距居中 */
                display: block; /* 设置为块级元素 */
            }

        /* 其他样式保持不变 */
            .product-features {
                list-style: none;
                padding: 0;
                text-align: center;
            }
            .product-features li {
                background: #f9f9f9;
                margin-bottom: 5px;
                padding: 10px;
                border-radius: 5px;
                display: inline-block;
                margin-right: 10px;
            }
    </style>
</head>

<body>
<div id="myCarousel" class="carousel slide">
    <!-- 轮播（Carousel）指标 -->
    <ol class="carousel-indicators">
        <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
        <li data-target="#myCarousel" data-slide-to="1"></li>
        <li data-target="#myCarousel" data-slide-to="2"></li>
    </ol>   
    <!-- 轮播（Carousel）项目 -->
    <div class="carousel-inner">
        <div class="item active">
            <img src="assets/images/花心1.jpg" alt="First slide">
        </div>
        <div class="item">
            <img src="assets/images/花心2.jpg" alt="Second slide">
        </div>
        <div class="item">
            <img src="assets/images/花心3.jpg" alt="Third slide">
        </div>
    </div>
    <!-- 轮播（Carousel）导航 -->
    <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
        <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
        <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
    </a>
</div>
作为一名财务专业人士，沈加菲对数字有着近乎痴迷的热爱。她坚信只有准确的财务数据才能为公司的决策提供可靠的依据，不仅拥有丰富的财务管理经验，还具有敏锐的商业洞察力和卓越的领导能力。在她的领导下，哥拉斯公司的财务状况稳步提升，即将实现市值百亿的小目标。
</body>


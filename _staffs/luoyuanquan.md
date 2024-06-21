---
short_name: yuanquan
name: Luo yuanquan
position: 人事总监
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
            <img src="https://img2.imgtp.com/2024/05/30/20uVK2jz.jpg" alt="First slide">
        </div>
        <div class="item">
            <img src="https://img2.imgtp.com/2024/05/30/sZ1ll97g.jpg" alt="Second slide">
        </div>
        <div class="item">
            <img src="https://img2.imgtp.com/2024/05/30/yBrf68vs.jpg" alt="Third slide">
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

在无数高楼林立的现代都市中，有那么一个角落，总是充满了欢声笑语，那就是罗源圈所执掌的人事部。这位人称“笑果制造机”的人事部长，不仅以其高超的人事管理技能赢得了同事们的尊敬，更以其独特的幽默感成为了公司里不可或缺的开心果。
</body>

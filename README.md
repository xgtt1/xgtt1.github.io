<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>峡谷天天</title>
    <link rel="stylesheet" href="./css/normalize.css">
    <link rel="stylesheet" href="./css/index.css">
    <link rel="stylesheet" href="./css/swiper.min.css">
</head>

<body>
    <section class="wrap">
        <div class="header">峡谷天天</div>
        <div class="nav">
            <a href="" class="item">
                <img src="./icons/icon1.png" alt="">
                <span>HR面试</span>
            </a>
            <a href="" class="item">
                <img src="./icons/icon2.png" alt="">
                <span>HR面试</span></a>
            <a href="" class="item">
                <img src="./icons/icon3.png" alt="">
                <span>HR面试</span></a>
            <a href="" class="item">
                <img src="./icons/icon4.png" alt="">
                <span>HR面试</span></a>
            <a href="" class="item">
                <img src="./icons/icon5.png" alt="">
                <span>HR面试</span></a>
            <a href="" class="item">
                <img src="./icons/icon6.png" alt="">
                <span>HR面试</span></a>
        </div>
        <!-- go模块 -->
        <section class='go'>
            <img src="./images/go.png" alt="">
        </section>
    </section>
    <!-- 主要内容 -->
    <section class="content">
        <div class="content-hd">
            <h4>
                <span class="icon"><img src="./icons/i2.png" alt=""></span>
                就业指导
            </h4>
            <a href="#" class="more">更多>></a>
        </div>
        <!-- 轮播图模块 -->
        <section class="swiper-focus">
            <div class="swiper-container get_job_fo">
                <div class="swiper-wrapper">
                    <div class="swiper-slide">
                        <a href="#"><img src="./images/pic.png" alt=""></a>
                        <p>老师教你应对面试技巧</p>
                    </div>
                    <div class="swiper-slide">
                        <a href="#"><img src="./images/ldh.jpg" alt=""></a>
                        <p>老师教你应对面试技巧</p>
                    </div>
                    <div class="swiper-slide">
                        <a href="#"><img src="./images/3.jpg" alt=""></a>
                        <p>老师教你应对面试技巧</p>
                    </div>
                </div>
            </div>
            <!-- Add Arrows -->
            <div class="swiper-button-next"></div>
            <div class="swiper-button-prev"></div>

            </div>
        </section>
    </section>


    <section class="content study_cont">
        <div class="content-hd">
            <h4>
                <span class="icon"><img src="./icons/i2.png" alt=""></span>
                充电学习
            </h4>
            <a href="#" class="more">更多>></a>
        </div>
        <!-- 轮播图模块 -->
        <section class="swiper-study">
            <div class="swiper-container study_fo">
                <div class="swiper-wrapper">
                    <div class="swiper-slide">
                        <img src="./images/pic1.png" alt="">
                        <h5>说地道英语，告别中式英语</h5>
                        <p>156人学习</p>
                    </div>
                    <div class="swiper-slide">
                        <img src="./images/pic2.png" alt="">
                        <h5>思维攻略金字塔思维提升写作能力</h5>
                        <p>125人学习</p>
                    </div>
                    <div class="swiper-slide">
                        <img src="./images/pic1.png" alt="">
                        <h5>说地道英语，告别中式英语</h5>
                        <p>86人学习</p>
                    </div>


                </div>

            </div>
        </section>
    </section>
    <footer class="footer">
        <a href="#" class="item">
            <img src="./icons/home.png" alt="">
            <p>首页</p>
        </a>
        <a href="#" class="item">
            <img src="./icons/net.png" alt="">
            <p>技术面试</p>
        </a>
        <a href="#" class="item">
            <img src="./icons/ms.png" alt="">
            <p>模拟面试</p>
        </a>
        <a href="#" class="item">
            <img src="./icons/user.png" alt="">
            <p>我的主页</p>
        </a>
       
    </footer>





    <script src="./js/flexible.js"></script>
    <script src="./js/swiper.min.js"></script>
    <script>
        (function () {
            var swiper = new Swiper('.get_job_fo', {
                slidesPerView: 2,
                spaceBetween: 30,
                centeredSlides: true,
                loop: true,
                navigation: {
                    nextEl: '.swiper-button-next',
                    prevEl: '.swiper-button-prev',
                },
            });
        })();
          
        (function () {
                var swiper = new Swiper('.study_fo', {
                    slidesPerView: 2.5,
                    spaceBetween: 20,
                  
                });
            })()
    </script>
</body>

</html>

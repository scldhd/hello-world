<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta content='width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no' name='viewport'>
    <title>苏苏1.0.0</title>
    <link rel="icon" type="image/png" sizes="32x32" href="images/favicon-32x32.png">
    <!----------------Global css------------------->
    <link rel="stylesheet" href="css/bootstrap.css">
    <link rel="stylesheet" href="css/font-awesome.min.css">
    <link rel="stylesheet" href="vendors/revolution-slider/css/layers.css">
    <link rel="stylesheet" href="vendors/revolution-slider/css/navigation.css">
    <link rel="stylesheet" href="vendors/revolution-slider/css/settings.css">
    <link rel="stylesheet" href="vendors/imagehover/css/imagehover.min.css">
    <link rel="stylesheet" href="vendors/animate/animate.min.css">
    <link rel="stylesheet" href="vendors/iCheck/css/all.css">
    <link rel="stylesheet" href="vendors/sweetalert2/css/sweetalert2.min.css">
    <!----------------custo css----------------->
    <link rel="stylesheet" href="css/custom.css">
</head>
<body>
<!-------------------Preloader---------------->
<div class="preloader" style="position:fixed;
    width:100%;
    height:100%;
    top:0;
    left:0;
    z-index:100000;
    backface-visibility: hidden;
    background: #ffffff;">
    <div style=" width: 50px;
    height: 50px;
    position: absolute;
    left: 50%;
    top: 50%;
    background-position: center;
    margin:-25px 0 0 -25px;">
        <img src="images/loader.gif" alt="loading...">
    </div>
</div>
<!----------------Preloader end----------------->
<!-------------Header--------->

<header>
    <div class="container">
        <nav class="navbar navbar-default">            
            <div class="navbar-header">
                
                <button class="navbar-toggle" type="button" data-toggle="collapse" data-target="#myMegamenu"><span
                        class="sr-only">Toggle navigation</span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
                
                <a class="navbar-brand" href="index.html">
                    <img src="images/g14.png" alt="company-logo" width="60" class="img-responsive">
                </a>
            </div>
            
            <div class="collapse navbar-collapse navbar-right" id="myMegamenu">
                <ul class="nav navbar-nav">
                    <li class="list2"><a href="index.html" class="hvr-underline-from-center">首页</a></li>
                    <li class="list2"><a href="about_us.html" class="hvr-underline-from-center">关于苏苏</a></li>
                  
                </ul>
            </div>
        </nav>
    </div>
</header>
<!-------------------------slider----------------------->
<div class="tp-banner-container rev_slider_wrapper fullwidthbanner-container" data-alias="news-hero72">
    <div class="home_slider">
        <ul>
            <li data-index="rs-10" data-transition="fade" data-slotamount="7" class="bg-light"
                data-easein="Power4.easeInOut" data-delay="5000" data-easeout="Power4.easeInOut" data-masterspeed="2000"
                data-rotate="0" data-saveperformance="off" data-title="Love it?" data-description="">
                <img src="images/timg.jpg" alt="systemimg" data-kenburns="off" data-bgposition="center center"
                     data-duration="10000" data-ease="Linear.easeNone" data-scalestart="100" data-scaleend="120"
                     data-rotatestart="0" data-rotateend="0" data-offsetstart="0 -500" data-bgfit="cover"
                     data-offsetend="0 500" data-bgparallax="10" class="rev-slidebg" data-no-retina>
                <div class="tp-caption  sfb tp-resizeme" data-x="center"
                     data-y="120" data-speed="700" data-start="1000" data-easing="Power0.easeInOut"
                     data-splitin="words"
                     data-splitout="none" data-elementdelay="0.1" data-endelementdelay="0.1"
                     style="z-index: 5; max-width: inherit; max-height: inherit; white-space: nowrap;color: #fff;font-size:60px;font-family: lato">
                    期末考试
                </div>
                <div class="tp-caption sft tp-resizeme" data-x="center"
                     data-y="200" data-speed="700" data-start="1000" data-easing="Power0.easeInOut"
                     data-splitin="words"
                     data-splitout="none" data-elementdelay="0.1" data-endelementdelay="0.1"
                     style="z-index: 5; max-width: inherit; max-height: inherit; white-space: nowrap;color: #fff;font-size:70px;font-family: lato">
                    会不会挂
                </div>

                <div class="hidden-xs tp-caption  sfl tp-resizeme" data-x="470"
                     data-y="340" data-speed="1000" data-start="2000" data-easing="Power3.easeInOut"
                     data-splitout="none" data-elementdelay="0.1" data-endelementdelay="0.1"
                     style="z-index: 5;font-size:40px";color: #007f00>
                    <a href="nofail.html" class="slider_btn hvr-shutter-out-horizontal">会</a>
                </div>
                <div class="hidden-xs tp-caption  sfr tp-resizeme" data-x="600"
                     data-y="340" data-speed="1000" data-start="2000" data-easing="Power3.easeInOut"
                     data-splitout="none" data-elementdelay="0.1" data-endelementdelay="0.1"
                     style="z-index: 5;font-size:40px;color: #ff0000">
                    <a href="pass.html" class="slider_btn">不会</a>
                </div>
                <!--
                <div class="visible-xs tp-caption  sfl tp-resizeme" data-x="350"
                     data-y="340" data-speed="1000" data-start="2000" data-easing="Power3.easeInOut"
                     data-splitout="none" data-elementdelay="0.1" data-endelementdelay="0.1"
                     style="z-index: 5;font-size: 30px">
                    <a href="contact_us.html" class="slider_btn slider_btn_res">1</a>
                </div>
                <div class="visible-xs tp-caption  sfr tp-resizeme" data-x="600"
                     data-y="340" data-speed="1000" data-start="2000" data-easing="Power3.easeInOut"
                     data-splitout="none" data-elementdelay="0.1" data-endelementdelay="0.1"
                     style="z-index: 5;font-size: 30px">
                    <a href="#" class="slider_btn slider_btn_res">1</a>
                </div>
                -->
            </li>
            <!--
            <li data-transition="Curtain from Middle" data-slotamount="7" data-delay="5000" data-masterspeed="600"
                class="bg-light">

                <img src="images/new_slider4.png" alt="girlimg" data-bgposition="right bottom"
                     data-duration="11000" data-ease="Linear.easeNone" data-bgfit="cover"
                     data-bgpositionend="left top">
                <div class="tp-caption grey_heavy_72 sfb tp-resizeme" data-x="center"
                     data-y="150" data-speed="700" data-start="700" data-easing="Power0.easeInOut"
                     data-splitin="lines"
                     data-splitout="none" data-elementdelay="0.1" data-endelementdelay="0.1"
                     style="z-index: 5; max-width: inherit; max-height: inherit; white-space: nowrap;color: #fff;font-size:55px;font-family: lato">
                    WELCOME TO
                </div>
                <div class="tp-caption grey_heavy_72 sft tp-resizeme" data-x="center"
                     data-y="250" data-speed="700" data-start="1000" data-easing="Power0.easeInOut"
                     data-splitin="lines"
                     data-splitout="none" data-elementdelay="0.1" data-endelementdelay="0.1"
                     style="z-index: 5; max-width: inherit; max-height: inherit;
                     white-space: nowrap;color: #fff;font-size:45px;font-family: lato">
                    ALL THE BLUES
                </div>
                <div class="hidden-xs tp-caption  sfl tp-resizeme" data-x="430"
                     data-y="350" data-speed="1000" data-start="2000" data-easing="Power3.easeInOut"
                     data-splitout="none" data-elementdelay="0.1" data-endelementdelay="0.1"
                     style="z-index: 5;">
                    <a href="contact_us.html" class="slider_btn">WELCOME</a>
                </div>
                <div class="hidden-xs tp-caption  sfr tp-resizeme" data-x="600"
                     data-y="350" data-speed="1000" data-start="2000" data-easing="Power3.easeInOut"
                     data-splitout="none" data-elementdelay="0.1" data-endelementdelay="0.1"
                     style="z-index: 5;">
                    <a href="#" class="slider_btn">VERY WELCOME</a>
                </div>
                <div class="visible-xs tp-caption  sfl tp-resizeme" data-x="350"
                     data-y="350" data-speed="1000" data-start="2000" data-easing="Power3.easeInOut"
                     data-splitout="none" data-elementdelay="0.1" data-endelementdelay="0.1"
                     style="z-index: 5;font-size: 30px">
                    <a href="contact_us.html" class="slider_btn slider_btn_res">CONTACT US</a>
                </div>
                <div class="visible-xs tp-caption  sfr tp-resizeme" data-x="600"
                     data-y="350" data-speed="1000" data-start="2000" data-easing="Power3.easeInOut"
                     data-splitout="none" data-elementdelay="0.1" data-endelementdelay="0.1"
                     style="z-index: 5;font-size: 30px">
                    <a href="#" class="slider_btn slider_btn_res">MEET OUR TEAM</a>
                </div>
            </li>            
            <li data-index="rs-82" data-transition="fade" data-slotamount="7" data-masterspeed="500" data-delay="5000"
                data-saveperformance="on"
                data-title="Intro Slide" data-bgfit="cover">
                <img src="images/new_slider3.png" alt="girlimg" data-bgposition="right bottom"
                     data-duration="11000" data-ease="Linear.easeNone" data-bgfit="cover"
                     data-bgpositionend="left top">

                <div class="tp-caption grey_heavy_72 sfl tp-resizeme" data-x="center"
                     data-y="150" data-speed="700" data-start="700" data-easing="Power0.easeInOut"
                     data-splitin="words"
                     data-splitout="none" data-elementdelay="0.1" data-endelementdelay="0.1"
                     style="z-index: 5; max-width: inherit; max-height: inherit; white-space: nowrap;color: #fff;font-size:70px;font-family: lato">
                    VEDHA CORPORATE
                </div>
                <div class="tp-caption grey_heavy_72 sfr tp-resizeme" data-x="center"
                     data-y="250" data-speed="700" data-start="1500" data-easing="Power0.easeInOut"
                     data-splitin="words"
                     data-splitout="none" data-elementdelay="0.1" data-endelementdelay="0.1"
                     style="z-index: 5; max-width: inherit; max-height: inherit; white-space: nowrap;color: #fff;font-size:45px;font-family: lato">
                    Best Corporate Company
                </div>
                <div class="hidden-xs tp-caption  sfb tp-resizeme" data-x="430"
                     data-y="350" data-speed="1000" data-start="2000" data-easing="Power3.easeInOut"
                     data-splitout="none" data-elementdelay="0.1" data-endelementdelay="0.1"
                     style="z-index: 5;">
                    <a href="contact_us.html" class="slider_btn">CONTACT US</a>
                </div>
                <div class="hidden-xs tp-caption  sfb tp-resizeme" data-x="600"
                     data-y="350" data-speed="1500" data-start="2000" data-easing="Power3.easeInOut"
                     data-splitout="none" data-elementdelay="0.1" data-endelementdelay="0.1"
                     style="z-index: 5;">
                    <a href="#" class="slider_btn">MEET OUR TEAM</a>
                </div>
                <div class="visible-xs tp-caption  sfl tp-resizeme" data-x="350"
                     data-y="350" data-speed="1000" data-start="2000" data-easing="Power3.easeInOut"
                     data-splitout="none" data-elementdelay="0.1" data-endelementdelay="0.1"
                     style="z-index: 5;font-size: 30px">
                    <a href="contact_us.html" class="slider_btn slider_btn_res">CONTACT US</a>
                </div>
                <div class="visible-xs tp-caption  sfr tp-resizeme" data-x="600"
                     data-y="350" data-speed="1000" data-start="2000" data-easing="Power3.easeInOut"
                     data-splitout="none" data-elementdelay="0.1" data-endelementdelay="0.1"
                     style="z-index: 5;font-size: 30px">
                    <a href="#" class="slider_btn slider_btn_res">MEET OUR TEAM</a>
                </div>
            </li>
            -->
        </ul>
    </div>
</div>



<!-------------------Slider end----------------->
<!--Login And Register Modal-->

<script src="js/jquery.min.js"></script>
<script src="js/bootstrap.min.js"></script>
<script src="vendors/revolution-slider/js/jquery.themepunch.revolution.min.js"></script>
<script src="vendors/revolution-slider/js/jquery.themepunch.tools.min.js"></script>
<script src="vendors/iCheck/js/icheck.js"></script>
<script src="vendors/countup/js/countUp.min.js"></script>
<script src="vendors/sweetalert2/js/sweetalert2.min.js"></script>
<script src="vendors/jribbble/js/jribbble.min.js"></script>
<!----------------------page Level Js-------------------------->
<script src="js/custom.js"></script>

</body>
</html>

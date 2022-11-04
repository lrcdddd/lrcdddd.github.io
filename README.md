                                                           

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    <meta name="viewport" content="initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
    <meta name="keywords" content="书法,字典,字帖,集字,以观书法">
    <link rel="icon" href="./image/favicon.ico" type="image/x-icon">
    <link rel="shortcut icon" href="./image/favicon.ico" type="image/x-icon">
    <link rel="apple-touch-icon" sizes="180x180" href="./image/icon.png">
    <title>以观书法</title>
    <link rel="stylesheet" href="./css/common.css"/>
    <link rel="stylesheet" href="./css/index.css"/>
</head>
<body>
    <div id="app">
        <div class="banner">
            <div class="content">
                <div class="icon">
                    <img src="./image/ygsf.png" alt="">
                </div>
                <div class="state">
                    <span>4.9 分</span>
                    <span class="app-info-delimter"></span>
                    <span>12 MB</span>
                    <span class="app-info-delimter"></span>
                    <span>987 万次安装</span>
                </div>
            </div>
        </div>

        <div class="download">
            <div class="button" onclick="window.open('ygsf.apk')">
                <img src="./image/android.png" alt="" />
                <span>安卓版</span>
            </div>
            <div class="button" onclick="window.open('https://itunes.apple.com/cn/app/id1351158526')">
                <img src="./image/apple.png" alt="" />
                <span>苹果版</span>
            </div>
            <div class="button" onclick="window.open('https://web.ygsf.com')">
                <img src="./image/web.png" alt="" />
                <span>网页版</span>
            </div>
        </div>

        <div class="sologan">以古为鉴<i class="dot">•</i>观复知常</div>
        <div class="scroll-x">
            <div class="screenshot">
                <img src="./image/app-01.jpg" alt="">
            </div>
            <div class="screenshot">
                <img src="./image/app-02.jpg" alt="">
            </div>
            <div class="screenshot">
                <img src="./image/app-03.jpg" alt="">
            </div>
            <div class="screenshot">
                <img src="./image/app-04.jpg" alt="">
            </div>
            <div class="screenshot">
                <img src="./image/app-05.jpg" alt="">
            </div>
        </div>

        <!-- 评分 -->
        <div class="resume">
            <h2 class="title">评分<i>(4.9分)</i></h2>
            <div class="comment">
                <img class="star" src="./image/star.png" alt="">
            </div>
        </div>

        <!-- 应用介绍 -->
        <div class="resume">
            <h2 class="title">应用介绍</h2>
            <div class="descrip">
                <p>『以观书法』与您一起欣赏汉字之美，学习书法之道。</p>
                <p>・这是一本中国书法大字典，可查询行、草、隶、篆、楷各种字体，收录书法字形数量超过400万（包含甲骨文、金文、简帛、篆刻等）；另收录硬笔字形数量超过130万。</p>
                <p>・这是一部中国历代书法名帖大全，包含大量高清字帖、拓本等，并配释文和注解。</p>
                <p>・这是一座汇集名师的书法学院，内涵大量书法课程及单字临摹视频，是书法爱好者的良师益友。</p>
                <p>・这是一款集字创作工具，集书法名家真迹字体，为书法创作寻找灵感源泉。</p>
                <p>・这是一部历代印谱大全，包含大量印谱和印章，并可根据印文查询。</p>
                <p>・这是一款古汉语字典，内含《康熙字典》、《说文解字》等大量古代字书，方便查询、考证。</p>
            </div>
        </div>

        <div id="contact">
            <span>© 2021 以观文化 </span><a href="https://beian.miit.gov.cn">皖ICP备18024832号-<span id="beian">2</span></a>
        </div>
        <script type="text/javascript">
            document.getElementById('beian').innerText = (location.href.indexOf('ygsf.com') > -1) ? '2' : '1';
        </script>
    </div>
</body>
</html>

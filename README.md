<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>hermes成果展示 </title>
    <style>
        h1 {
            color: rgb(240, 159, 8);
            font-size: 40px;
            text-align: center;
            font-family: Arial, Helvetica, sans-serif;
            text-shadow: 3px 3px 6px rgba(162, 126, 9, 0.6);

        }

        header {
            background-color: #333;
            color: #fff;
            padding: 10px;
            text-align: center;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }


        h2 {
            color: purple;
            font-size: 30px;
            font-family: 'Times New Roman', Times, serif;
            font-weight: 900;
            text-shadow: 3px 3px 6px rgba(187, 10, 131, 0.6);
            text-align: center;
        }

        h3 {
            color: rgb(184, 66, 214);
            font-size: 20px;
            text-align: center;
        }

        h4 {
            color: rgb(14, 103, 73);
            font-size: 22px;
            text-align: center;
        }

        p {
            color: rgb(12, 12, 12);
            font-size: 20px;
        }

        h5 {
            color: rgb(125, 96, 58);
            font-size: 18px;
        }

        span {
            color: rgb(242, 164, 177);
            font-size: 20px；
        }

        .mytype1 {
            color: rgb(142, 97, 184);
            font-size: 22px;

        }

        .box4 {
            margin: auto;
        }

        .mytype2 {
            color: rgb(201, 47, 47);
            font-size: 18px;
        }

        .mytype3 {
            color: rgb(20, 20, 177);
            font-size: 20px;
            text-shadow: 3px 3px 6px rgba(28, 10, 187, 0.6);

        }

        .mytype4 {
            color: black;
            font-size: 20px;

        }

        .back1 {
            width: 400px;
            height: 400px;
            background-color: rgb(25, 132, 96);
        }

        .back2 {
            width: 400px;
            height: 400px;
            background-image: url("照片1.jpg");
            background-repeat: no-repeat;

        }



        table,
        td {
            border: 5px solid rgb(210, 156, 75);
            box-shadow: 0px 10px 10px rgba(0, 0, 0, 0.5);
            border-radius: 10px;
            text-align: center;
        }

        table {
            border-collapse: collapse;
            width: 700px;
        }


        td {
            text-align: center;
            padding: 20px;


        }

        th {
            background-color: rgb(174, 173, 170);
        }

        .container {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 30vh;
        }

        .image-container {
            overflow: hidden;
            width: 300px;
            margin-right: 25px;
        }

        .animated-image {
            width: 100%;
            height: auto;
            transform: scale(1);
            transition: transform 0.5s ease;
        }

        .content {
            text-align: center;
        }

        .animated-title {
            font-size: 24px;
            margin-bottom: 10px;
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.5s ease, transform 0.5s ease;
        }

        .animated-description {
            font-size: 20px;
            opacity: 0;
            transform: translateY(10px);
            transition: opacity 0.5s ease, transform 0.5s ease;
        }

        .container:hover .animated-image {
            transform: scale(0.85);
        }

        .container:hover .animated-title,
        .container:hover .animated-description {
            opacity: 1;
            transform: translateY(0);
        }

        .box2 {

            animation: photo 3s linear 0s infinite normal;

        }

        .box2:hover {
            opacity: 1;
            transform: translateY(0);
            animation-play-state: running;

        }

        .animation:hover {
            animation-play-state: running;
        }

        @keyframes photo {
            from 0% {
                opacity: 0.2;
                box-shadow: 0 1px 2px rgba(225, 225, 225, 0.1)
            }

            50% {
                opacity: 0.5;
                box-shadow: 0 1px 2px rgba(197, 133, 21, 0.1)
            }

            100% {
                opacity: 1;
                box-shadow: 0 1px 5px rgba(23, 128, 209, 0.1)
            }
        }



        .box7 {
            width: 100px;
            height: 100px;
            background-color: rgb(237, 154, 65);
            position: fixed;
            right: 50px;
            bottom: 50px;
            box-shadow: 10px 10px 20px rgba(0, 0, 0, 0.5);
            border-radius: 20px;
        }

        .box1 {
            box-shadow: 10px 10px 20px rgba(0, 0, 0, 0.5);
            border-radius: 20px;

        }

        img {
            box-shadow: 0px 10px 10px rgba(0, 0, 0, 0.5);
            border-radius: 25px;
           
           
            height: auto;
         
            display: block;
           
            margin: 0 auto;
        }

        .box3 {
            display: block;
            width: 80px;
            height: 80px;
            background-image: url(童蒙养财.png);
            background-position: -300px -280px;
            position: fixed;
            right: 50px;
            bottom: 50px;
            box-shadow: 10px 10px 20px rgba(0, 0, 0, 0.5);
            border-radius: 20px 20px;
        }
    </style>
</head>

<body>
    <header>
        <h1>林灵-进度：</h1>
    </header>

    <div class="container">
        <div class="image-container">
            <img src="童蒙养财.png" alt="Your Image" class="animated-image">
        </div>
        <div class="content">

            <h1 class="animated-title">Hermes——青少年财商教育创新平台项目</h1>
            <a href="https://mp.weixin.qq.com/s/kFxbK6hvx3bwxCbi_-9jsA">
                <h1 class="animated-title">财商元宇宙</h1>
            </a>
            <p class="animated-description"></p>
        </div>
    </div>

    <h2>简介：</h2>
    <h3>项目背景：</h3>
    <img src="线上线下.png" width="700px" alt="线上+线下">
    <p>深大金融科技学院师生共同创办Hermes——青少年财商教育创新平台项目。
    </p>
    <h2>产品1：财商元宇宙</h2>
    <table class="box4">
        <tr>
            <td class="mytype3">简介：</td>
            <td class="mytype3">相关推文：</td>

        </tr>
        <tr>
            <td class="mytype4"><strong>深大金融科技学院</strong>师生共同创办<i>Hermes——青少年财商教育创新平台项目</i>
                <br>策划并计划开发出一款面向青少年的、基于虚拟经济平台的财商教育应用。
                致力于通过<strong>UE5引擎</strong>开发一款<strong>趣味性</strong>游戏，将财商知识融入游戏关卡、任务与剧情，寓教于乐。
                <br>助力青少年培养与时俱进的金钱观念，养成审慎严谨的<strong>风控</strong>习惯并学习<strong>金融</strong>知识，
                从而实现青少年财商素质的有效提升，逐步提高全民金融素养。
            </td>
            <td>


                <a href="https://mp.weixin.qq.com/s/w6Q9THfxr__y-vOwQXFk2A">
                    1.<img src="开发组招新.png" width="200px" alt="开发组招新推文">
                </a>
                <br>
                <a href="https://mp.weixin.qq.com/s/kFxbK6hvx3bwxCbi_-9jsA">
                    2.<img src="研投.png" width="200px" alt="DYOR开发组研投推文">
                </a>
                <br>
                <a href="https://mp.weixin.qq.com/s/C20Z-9Zj1zqt4eD1IeUA9A">
                    3.<img src="创LI.png" width="200px" alt="双创推文">
                </a>

                <br>
                <a href="https://mp.weixin.qq.com/s/Iu01kziBqjM88oo23me9tA">
                    4.<img src="p2p.png" width="200px" alt="对等网络推文">
                </a>

            </td>

        </tr>
    </table>
    <h3>成品展示：</h3>
    <a
        href="https://mp.weixin.qq.com/s?__biz=Mzk0MDQ0NzMwMg==&mid=2247484042&idx=1&sn=8bba7c24cf89197003a4b5f54d556c56&chksm=c3dfdc7a5edf2da3d8a2b64825b67242bd40e822ab114bead3a6600703e500ad8390ab5eb6fe&scene=126&sessionid=1703310705#rd">
        <img class="box1" src="hermes game.png" width="400px" alt="成品">
    </a>



    <h2>产品2：线下工作坊</h2>

    <table class="box4">
        <tr>
            <td class="mytype3">简介：</td>
            <td class="mytype3">相关推文：</td>

        </tr>
        <tr>
            <td class="mytype4">
                培养青少年正确<strong>价值观和消费观</strong>，树立正确的<strong>理财观和投资观</strong>。
                <br>良好的财商教育指导，引导孩子完成理财、金融决策。
                父母参与活动，<strong>提高财商教育意识</strong>。
            </td>
            <td>
                <a href="https://mp.weixin.qq.com/s/U6Dl-4QFGFxPeGt0WOq9SQ">
                    1.<img src="人才培养.png" width="200px" alt="人才培养推文">
                </a>
                <br>
                <a href="https://mp.weixin.qq.com/s/hhAhRTr7gzePYiGZc-hnng">
                    2.<img src="童蒙养财.png" width="200px" alt="童蒙养财推文">
                </a>
                <br>
                <a href="https://mp.weixin.qq.com/s/bUzqMXMEfsb_gShBWNW12g">
                    3.<img src="三下乡.png" width="200px" alt="三下乡推文">
                </a>

                <br>
                <a href="https://mp.weixin.qq.com/s/QlUAq2xSZfrJF98nyuZrAQ">
                    4.<img src="财商工作坊.png" width="200px" alt="财商工作坊推文">
                </a>

            </td>

        </tr>
    </table>






    <h2>项目组部门：</h2>
    <ol class="mytype1 box4">
        <li>商推组
            <ul class="mytype2">
                <li>负责：竞赛+商业策划</li>
            </ul>

        </li>
        <li>开发组
            <ul class="mytype2">
                <li>游戏开发：对游戏关卡运行等提供技术支持</li>
                <li>web2.0前端开发：前端网页(HTML、css、JavaScript)</li>
                <li>web2.0后端开发：数据库、数据存储</li>

            </ul>


        </li>
        <li>美工组
            <ul class="mytype2">
                <li>负责：根据需求建立、制作原画素材模型</li>
            </ul>
        </li>
        <li>策划组
            <ul class="mytype2">
                <li>经济系统策划：财商量表的优化，优化游戏内的题库</li>
                <li>游戏策划：设计游戏关卡、编写关卡设计文档，敌人布局、目标任务、游戏制作等详细说明</li>
            </ul>
        </li>
        <li>工作坊：
            <ul class="mytype2">
                <li>目的：青少年实践现实的财商生活场景、提高财商教育意识</li>
                <li>形式：线下在城乡社区、学校开展活动:
                    <ul>
                        <li>
                            工作坊活动
                        </li>
                        <li>第二课堂活动</li>
                        <li>支教活动</li>
                    </ul>
                </li>
            </ul>
        </li>
    </ol>



    <div>
        <a href="https://mp.weixin.qq.com/s/hhAhRTr7gzePYiGZc-hnng">
            <img class="box3" alt="">
        </a>

    </div>





    <h5>
        <ul>
            <li>感兴趣的同学请关注！</li>
        </ul>
    </h5>
    <img src="二维码.png" alt="HMS公众号" width="350px" height="300px">
    <footer>林灵-Hermes考核成果展示</footer>


</body>

</html>

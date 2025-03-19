<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>赵荣腾 - 个人网站</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Arial, sans-serif;
        }

        body {
            background-color: #f5f5f5;
            line-height: 1.6;
            color: #333;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            background: linear-gradient(135deg, #2c3e50, #3498db);
            color: white;
            padding: 60px 20px;
            text-align: center;
            border-radius: 0 0 20px 20px;
            margin-bottom: 30px;
        }

        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin: 20px auto;
            border: 3px solid white;
            display: block;
        }

        section {
            background: white;
            padding: 30px;
            margin: 20px 0;
            border-radius: 10px;
            box-shadow: 0 2px 15px rgba(0,0,0,0.1);
        }

        h2 {
            color: #3498db;
            border-left: 4px solid #3498db;
            padding-left: 15px;
            margin-bottom: 20px;
        }

        .contact-info {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }

        .contact-item {
            text-align: center;
            padding: 15px;
            background: #f8f9fa;
            border-radius: 8px;
        }

        .award-list li {
            margin-bottom: 15px;
            padding: 10px;
            background: #f8f9fa;
            border-radius: 5px;
        }

        footer {
            text-align: center;
            padding: 20px;
            color: #666;
        }

        /* 响应式设计 */
        @media (max-width: 768px) {
            .container {
                padding: 10px;
            }
            section {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>赵荣腾</h1>
        <p>华中农业大学 资源与环境</p>
    </header>

    <div class="container">
        <!-- 个人简介 -->
        <section>
            <h2>个人简介</h2>
            <p>出生年月：2002.04 | 籍贯：山东聊城</p>
            <p>毕业院校：青海大学 | 政治面貌：共青团员</p>
            <p>初试总分：320 | 专业排名：第9</p>
        </section>

        <!-- 教育经历 -->
        <section>
            <h2>教育背景</h2>
            <h3>青海大学 环境生态工程（2019.09-2023.06）</h3>
            <ul>
                <li>主修课程：高等数学Ⅱ、环境监测、环境化学、环境影响评价、土壤学、污染生态学等</li>
                <li>毕业设计：Fe₃O₄-RGO纳米复合催化剂去除亚甲基蓝效果分析</li>
            <h4>华中农业大学 资源与环境硕士在读
            <ul>
                <li>（2024-今）</li>
            </ul>
        </section>

        <!-- 曾获荣誉 -->
        <section>
            <h2>证书与荣誉</h2>
            <ul class="award-list">
                <li>大学英语四级证书</li>
                <li>青海大学优秀共青团员（2021）</li>
                <li>校级优秀学生干部（2020）</li>
                <li>舞台剧比赛三等奖（2019）</li>
            </ul>
        </section>

        <!-- 联系方式 -->
        <section>
            <h2>联系我</h2>
            <div class="contact-info">
                <div class="contact-item">
                    <h3>电话</h3>
                    <a href="tel:18986778037">189-8677-8037</a>
                </div>
                <div class="contact-item">
                    <h3>邮箱</h3>
                    <a href="mailto:zrt981578267@163.com">zrt981578267@163.com</a>
                </div>
            </div>
        </section>
    </div>

    <footer>
        <p>© 2025 赵荣腾 | 追求卓越，永不止步</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>NianJiu's GitHub Profile</title>
    <style>
        /* 动态欢迎动画 */
        .typewriter {
            font-family: 'Courier New', Courier, monospace;
            overflow: hidden;
            white-space: nowrap;
            margin: 0 auto;
            border-right: .15em solid orange;
            animation:
                typing 3.5s steps(30, end),
                blink-caret .75s step-end infinite;
        }

        @keyframes typing {
            from { width: 0 }
            to { width: 100% }
        }

        @keyframes blink-caret {
            from, to { border-color: transparent }
            50% { border-color: orange }
        }

        /* 整体样式 */
        body {
            font-family: Arial, sans-serif;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f0f0f0;
        }

        .profile {
            text-align: center;
            margin-bottom: 30px;
        }

        .avatar {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-bottom: 10px;
        }

        .section {
            background-color: white;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 8px;
        }

        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 5px;
            margin-top: 10px;
        }

        .skill {
            background-color: #e0e0e0;
            padding: 5px 10px;
            border-radius: 3px;
        }

        /* 媒体查询 */
        @media (max-width: 600px) {
            body {
                padding: 10px;
            }
        }
    </style>

</head>
<body>
    <div class="profile">
        <img src="https://avatars.githubusercontent.com/u/12345678?v=4" alt="NianJiu" class="avatar">
        <h1 class="typewriter">Hi, I'm NianJiu</h1>
        <p>大二学生 | 厦门大学计算机科学与技术专业 | 开源社区贡献者</p>
        <p>
            <a href="https://github.com/NianJiu" target="_blank">GitHub</a> |
            <a href="mailto:nianjiu@example.com" target="_blank">Email</a>
        </p>
    </div>

    <div class="section">
        <h2>About Me</h2>
        <p>
            我是厦门大学计算机科学与技术专业的大二学生。对开源社区充满热情，致力于通过技术创新解决实际问题。目前专注于Web开发领域，喜欢探索前沿技术并参与开源项目。
        </p>
    </div>

    <div class="section">
        <h2>Skills</h2>
        <div class="skills">
            <span class="skill">Python</span>
            <span class="skill">JavaScript</span>
            <span class="skill">Java</span>
            <span class="skill">React</span>
            <span class="skill">Git</span>
            <span class="skill">Machine Learning</span>
        </div>
    </div>

    <div class="section">
        <h2>Featured Projects</h2>
        <ul>
            <li>
                <a href="https://github.com/NianJiu/project1" target="_blank">Project 1</a> - 一个全栈Web应用，使用React和Node.js构建
            </li>
            <li>
                <a href="https://github.com/NianJiu/project2" target="_blank">Project 2</a> - 基于机器学习的图像分类系统
            </li>
        </ul>
    </div>

    <div class="section">
        <h2>GitHub Stats</h2>
        <div>
            <img src="https://github-readme-stats.vercel.app/api?username=NianJiu&show_icons=true&theme=radical" alt="GitHub Stats">
        </div>
    </div>

</body>
</html>

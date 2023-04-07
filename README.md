<!DOCTYPE html>
<html>

<head>
    <title>My Cool README File</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" />
    <style>
        body {
            font-family: 'Roboto', sans-serif;
        }

        h1 {
            font-size: 36px;
            font-weight: bold;
            color: #4CAF50;
            text-align: center;
            margin-top: 50px;
        }

        p {
            font-size: 24px;
            color: #666;
            text-align: center;
            margin-top: 30px;
        }

        hr {
            border: none;
            border-top: 2px solid #39FF14;
            margin: 50px 0px;
        }

        /* Animated ordered list numbering */
        ol {
            list-style: none;
            counter-reset: item;
            margin: 0;
            padding: 0;
        }

        li {
            margin-bottom: 10px;
            position: relative;
        }

        li::before {
            content: counter(item);
            counter-increment: item;
            display: inline-block;
            width: 20px;
            height: 20px;
            border-radius: 50%;
            margin-right: 10px;
            text-align: center;
            line-height: 20px;
            position: absolute;
            left: -30px;
            top: 0;
            background-color: #39FF14;
            animation: bounce 1s infinite;
        }

        @keyframes bounce {

            0%,
            20%,
            50%,
            80%,
            100% {
                transform: translateY(0);
            }

            40% {
                transform: translateY(-20px);
            }

            60% {
                transform: translateY(-10px);
            }
        }

        .icon {
            font-size: 50px;
            color: #4CAF50;
            margin: 20px;
            display: inline-block;
        }

        .currently-working {
            padding: 20px;
            margin: 50px auto;
            max-width: 800px;
        }

        .currently-working h2 {
            font-size: 30px;
            color: #4CAF50;
            margin-top: 0px;
        }

        .currently-working ul {
            list-style: none;
            padding-left: 0px;
        }

        .currently-working ul li {
            margin: 10px 0px;
            font-size: 20px;
            color: #666;
            line-height: 1.5;
        }

        .about-me {
            padding: 20px;
            margin: 50px auto;
            max-width: 800px;
        }

        .about-me h2 {
            font-size: 30px;
            color: #4CAF50;
            margin-top: 0px;
        }

        .about-me p {
            font-size: 20px;
            color: #666;
            line-height: 1.5;
            text-align: justify;
        }

        .my-interests {
            padding: 20px;
            margin: 50px auto;
            max-width: 800px;
        }

        .my-interests h2 {
            font-size: 30px;
            color: #4CAF50;
            margin-top: 0px;
        }

        .my-interests ul {
            list-style: none;
            padding-left: 0px;
        }

        .my-interests ul li {
            margin: 10px 0px;
            font-size: 20px;
            color: #666;
            line-height: 1.5;
        }
    </style>
</head>

<body>
    <h1>Hello, I'm [Your Name]!</h1>
    <p>I'm a Junior MERN Stack Developer.</p>
    <div style="text-align:center;">
        <i class="fab fa-html5 icon"></i>
        <i class="fab fa-css3-alt icon"></i>
        <i class="fab fa-js-square icon"></i>
        <i class="fab fa-react icon"></i>
        <i class="fab fa-node-js icon"></i>
    </div>
    <div class="currently-working">
        <h2>Currently Working On</h2>
        <ol class="animated-numbering">
            <li>Building a full-stack e-commerce website using MERN stack</li>
            <li>Learning advanced React concepts</li>
            <li>Practicing algorithms and data structures</li>
        </ul>
    </div>

    <hr class="section-divider">

    <div class="about-me">
        <h2>About Myself</h2>
        <p>Hi there! I'm a Junior MERN Stack Developer based in [Your Location]. I recently graduated from [Your
            University/Bootcamp] and have been working on building my skills and experience since then. I love working
            with the MERN stack and am constantly learning new things to improve my skills.</p>
        <p>Aside from coding, I enjoy spending time outdoors, playing video games, and learning about new technologies.
        </p>
    </div>

    <hr class="section-divider">

    <div class="my-interests">
        <h2>My Interests</h2>
        <ol class="animated-numbering">
            <li>Technology</li>
            <li>Gaming</li>
            <li>Hiking</li>
            <li>Reading</li>
            <li>Traveling</li>
        </ul>
    </div>

    <div style="text-align:center;">
        <img src="https://media.giphy.com/media/USV0ym3bVWQJJmNu3N/giphy.gif" alt="React Gif"
            style="width:200px;height:200px;">
        <img src="https://media.giphy.com/media/ln7z2eWriiQAllfVcn/giphy.gif" alt="MERN Stack Gif"
            style="width:200px;height:200px;">
    </div>
</body>

</html>

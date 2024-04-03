- 👋 Hi, I’m @harshitkowsik
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
harshitkowsik/harshitkowsik is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me Slider</title>
    <link rel="stylesheet" href="style.css">
    <link href='https://fonts.googleapis.com/css?family=Poppins' rel='stylesheet'>
    <style>
        body {
    background-color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    overflow: hidden;
    margin: 0px;
    transition: all ease 0.5s;
}

a {
    text-decoration: none;
    color: black;
}

.top {
    position: absolute;
    top: 0px;
    width: 100vw;
    display: flex;
    justify-content: space-around;
    align-items: center;
    box-shadow: 0px 1px 0px grey;
    height: 5vh;
    font-family: poppins;
    background-color: white;
    overflow: hidden;
}

img {
    width: 1em;
    margin-top: 5px;
}

#btn:hover {
    transform: scale(110%);
}

#btn:active {
    transform: scale(100%);
}


.bottom {
    position: absolute;
    bottom: 0px;
    width: 100vw;
    display: flex;
    justify-content: right;
    padding-right: 2em;
    align-items: center;
    box-shadow: 0px -1px 0px grey;
    height: 5vh;
    font-family: poppins;
    color: grey;
    background-color: white;
    overflow: hidden;
}

.container {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 2em;
    width: 80vw;
    overflow: hidden;
}

.div1 {
    color: #25D366;
    font-size: 1em;
    border: 1px solid #25D366;
    padding: 0.5em;
    width: 0.5em;
    border-radius: 1em;
    margin: 0.2em;
    animation: scale1 5s alternate infinite;
}

.div2 {
    color: #25D366;
    font-size: 1em;
    border: 1px solid #25D366;
    padding: 0.5em;
    width: 0.5em;
    border-radius: 1em;
    margin: 0.2em;
    animation: scale2 5s alternate infinite;
}

.div3 {
    color: #25D366;
    font-size: 1em;
    border: 1px solid #25D366;
    padding: 0.5em;
    width: 0.5em;
    border-radius: 1em;
    margin: 0.2em;
    animation: scale3 5s alternate infinite;
}

.div4 {
    color: #25D366;
    font-size: 1em;
    border: 1px solid #25D366;
    padding: 0.5em;
    width: 0.5em;
    border-radius: 1em;
    margin: 0.2em;
    animation: scale4 5s alternate infinite;
}

.div5 {
    color: #25D366;
    font-size: 1em;
    border: 1px solid #25D366;
    padding: 0.5em;
    width: 0.5em;
    border-radius: 1em;
    margin: 0.2em;
    animation: scale5 5s alternate infinite;
}

.div6 {
    color: #25D366;
    font-size: 1em;
    border: 1px solid #25D366;
    padding: 0.5em;
    width: 0.5em;
    border-radius: 1em;
    margin: 0.2em;
    animation: scale6 5s alternate infinite;
}

.div7 {
    color: #25D366;
    font-size: 1em;
    border: 1px solid #25D366;
    padding: 0.5em;
    width: 0.5em;
    border-radius: 1em;
    margin: 0.2em;
    animation: scale7 5s alternate infinite;
}

.div8 {
    color: #25D366;
    font-size: 1em;
    border: 1px solid #25D366;
    padding: 0.5em;
    width: 0.5em;
    border-radius: 1em;
    margin: 0.2em;
    animation: scale8 5s alternate infinite;
}

.div9 {
    color: #25D366;
    font-size: 1em;
    border: 1px solid #25D366;
    padding: 0.5em;
    width: 0.5em;
    border-radius: 1em;
    margin: 0.2em;
    animation: scale9 5s alternate infinite;
}

.bubble {
    height: 1em;
    width: 19em;
    background: transparent;
    border: 1px solid red;
    margin: 0.2em;
    z-index: 1;
    position: absolute;
}

@keyframes scale1 {
    from {
        transform: translateY(19px);
    }

    50% {
        transform: translateY(0px);
    }

    to {
        transform: translateY(-19px);
    }
}

@keyframes scale2 {
    from {
        transform: translateY(0px);
    }

    50% {
        transform: translateY(19px);
    }

    to {
        transform: translateY(-19px);
    }
}

@keyframes scale3 {
    from {
        transform: translateY(-19px);
    }

    50% {
        transform: translateY(0px);
    }

    to {
        transform: translateY(19px);
    }
}

@keyframes scale4 {
    from {
        transform: translateY(0px);
    }

    50% {
        transform: translateY(19px);
    }

    to {
        transform: translateY(-19px);
    }
}

@keyframes scale5 {
    from {
        transform: translateY(19px);
    }

    50% {
        transform: translateY(-19px);
    }

    to {
        transform: translateY(0px);
    }
}

@keyframes scale6 {
    from {
        transform: translateY(-19px);
    }

    50% {
        transform: translateY(0px);
    }

    to {
        transform: translateY(19px);
    }
}

@keyframes scale7 {
    from {
        transform: translateY(19px);
    }

    50% {
        transform: translateY(0px);
    }

    to {
        transform: translateY(-19px);
    }
}

@keyframes scale8 {
    from {
        transform: translateY(19px);
    }

    50% {
        transform: translateY(-19px);
    }

    to {
        transform: translateY(0px);
    }
}

@keyframes scale9 {
    from {
        transform: translateY(19px);
    }

    50% {
        transform: translateY(0px);
    }

    to {
        transform: translateY(-19px);
    }
}
    </style>
</head>

<body>
    <script> 
body = document.querySelector('body');
let check = false;

document.getElementById('btn').addEventListener('click', function() {
    if (check) {
        body.style.backgroundColor = 'white';
    }
    else {
        body.style.backgroundColor = 'black';
    }
    check = !check;
});
    </script>
    <nav class="top">
        <h3><a href="index.html"> About     Me </a></h3>
        <h3 id="btn"><img src="https://img.icons8.com/?size=100&id=104618&format=png"></h3>
        </a>
    </nav>
    <div class="container">
        <div class="div1">d<br>d<br>c</div>
        <div class="div2">e<br>e<br>r</div>
        <div class="div3">e<br>v<br>s</div>
        <div class="div4">e<br>i<br>a</div>
        <div class="div5">g<br>t<br>l</div>
        <div class="div6">i<br>o<br>n</div>
        <div class="div7">e<br>p<br>v</div>
        <div class="div8">r<br>e<br>e</div>
        <div class="div9">+<br>r<br>+</div>
        <div class="bubble"></div>
    </div>
    <nav class="bottom">
        <h6>By Harshit Kowsik </h6>
    </nav>
</body>

</html>

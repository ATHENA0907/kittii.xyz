<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>모기 잡기 게임</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    user-select:none;
}

body{
    overflow:hidden;
    background:#8fd3ff;
    font-family:Arial, sans-serif;
}

#score{
    position:fixed;
    top:20px;
    left:20px;
    font-size:32px;
    font-weight:bold;
    color:#fff;
    text-shadow:2px 2px 5px black;
}

#mosquito{
    position:absolute;
    font-size:70px;
    cursor:pointer;
    transition:0.12s;
}

#mosquito:hover{
    transform:scale(1.15);
}
</style>

</head>
<body>

<div id="score">점수 : 0</div>

<div id="mosquito">🦟</div>

<script>

const mosquito = document.getElementById("mosquito");
const scoreText = document.getElementById("score");

let score = 0;

function moveMosquito(){

    const size = 80;

    const x = Math.random() * (window.innerWidth - size);
    const y = Math.random() * (window.innerHeight - size);

    mosquito.style.left = x + "px";
    mosquito.style.top = y + "px";
}

mosquito.onclick = () =>{

    score++;
    scoreText.innerHTML = "점수 : " + score;

    moveMosquito();

}

window.onresize = moveMosquito;

moveMosquito();

</script>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GameSense</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:#111;
    color:#d6d6d6;
}

.wrapper{
    width:900px;
    margin:20px auto;
}

/* Header */

.header{
    background:#1c1c1c;
    border:1px solid #2b2b2b;
}

.logo{
    padding:18px 18px 10px;
    font-size:40px;
    font-weight:bold;
}

.logo .game{
    color:#ffffff;
}

.logo .sense{
    color:#8fd14f;
}

.nav{
    background:#2a2a2a;
    border-top:1px solid #343434;
    border-bottom:1px solid #343434;
    padding:12px 18px;
}

.nav a{
    color:#cfcfcf;
    text-decoration:none;
    margin-right:25px;
    font-size:14px;
}

.nav a:hover{
    color:#ffffff;
}

.notice{
    padding:18px;
    font-size:14px;
}

/* Panels */

.panel{
    margin-top:14px;
    border:1px solid #2c2c2c;
    background:#1c1c1c;
}

.panel-title{
    background:#2a2a2a;
    padding:10px 14px;
    font-weight:bold;
    border-bottom:1px solid #343434;
}

.panel-body{
    padding:20px 14px;
    line-height:28px;
}

.panel-body a{
    color:#4ea3ff;
    text-decoration:none;
}

.panel-body a:hover{
    text-decoration:underline;
}

/* Footer */

.footer{
    margin-top:14px;
    background:#1c1c1c;
    border:1px solid #2b2b2b;
    padding:12px 14px;
    color:#aaa;
    font-size:14px;
}
</style>
</head>

<body>

<div class="wrapper">

    <div class="header">

        <div class="logo">
            <span class="game">game</span><span class="sense">sense</span>
        </div>

        <div class="nav">
            <a href="#">🏠 Index</a>
            <a href="#">Register</a>
            <a href="#">Login</a>
        </div>

        <div class="notice">
            You are not logged in.
        </div>

    </div>

    <div class="panel">
        <div class="panel-title">
            Info
        </div>

        <div class="panel-body">
            You do not have permission to view these forums.<br>
            <a href="#">Go back</a>
        </div>
    </div>

    <div class="footer">
        GameSense 2026
    </div>

</div>

</body>
</html>

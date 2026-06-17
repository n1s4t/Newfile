<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GitHub Stats Card</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Segoe UI',sans-serif;
}

body{
    background:#f5f7fb;
    display:flex;
    justify-content:center;
    align-items:center;
    min-height:100vh;
}

.container{
    width:900px;
    max-width:95%;
}

.card{
    background:#fff;
    border-radius:18px;
    padding:30px;
    box-shadow:0 10px 30px rgba(0,0,0,.08);
}

.title{
    color:#3b82f6;
    font-size:32px;
    font-weight:700;
    margin-bottom:25px;
}

.progress{
    width:100%;
    height:18px;
    border-radius:20px;
    overflow:hidden;
    display:flex;
    margin-bottom:30px;
}

.ts{width:63%;background:#3b82f6;}
.py{width:16%;background:#2563eb;}
.html{width:12%;background:#f97316;}
.sh{width:5%;background:#84cc16;}
.css{width:3%;background:#7c3aed;}
.php{width:1%;background:#475569;}

.languages{
    display:grid;
    grid-template-columns:repeat(2,1fr);
    gap:15px;
    margin-bottom:35px;
}

.lang{
    display:flex;
    align-items:center;
    gap:10px;
    font-size:18px;
}

.dot{
    width:15px;
    height:15px;
    border-radius:50%;
}

.stats{
    display:flex;
    justify-content:space-between;
    align-items:center;
    flex-wrap:wrap;
}

.left p{
    font-size:18px;
    margin:12px 0;
    color:#374151;
}

.score{
    width:150px;
    height:150px;
    border-radius:50%;
    border:10px solid #dbeafe;
    border-top-color:#3b82f6;
    display:flex;
    justify-content:center;
    align-items:center;
    font-size:50px;
    font-weight:700;
    color:#374151;
}
</style>
</head>

<body>

<div class="container">
    <div class="card">

        <h2 class="title">Most Used Languages</h2>

        <div class="progress">
            <div class="ts"></div>
            <div class="py"></div>
            <div class="html"></div>
            <div class="sh"></div>
            <div class="css"></div>
            <div class="php"></div>
        </div>

        <div class="languages">
            <div class="lang">
                <span class="dot" style="background:#3b82f6"></span>
                TypeScript 63.19%
            </div>

            <div class="lang">
                <span class="dot" style="background:#84cc16"></span>
                Shell 4.65%
            </div>

            <div class="lang">
                <span class="dot" style="background:#2563eb"></span>
                Python 16.16%
            </div>

            <div class="lang">
                <span class="dot" style="background:#7c3aed"></span>
                CSS 3.16%
            </div>

            <div class="lang">
                <span class="dot" style="background:#f97316"></span>
                HTML 12.51%
            </div>

            <div class="lang">
                <span class="dot" style="background:#475569"></span>
                PHP 0.34%
            </div>
        </div>

        <div class="stats">
            <div class="left">
                <p>⭐ Total Stars Earned: 3</p>
                <p>🕒 Total Commits: 64</p>
                <p>🔀 Total PRs: 2</p>
                <p>❗ Total Issues: 3</p>
                <p>📦 Contributed To: 1</p>
            </div>

            <div class="score">C</div>
        </div>

    </div>
</div>

</body>
</html>

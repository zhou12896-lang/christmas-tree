<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>圣诞树</title>

<style>
body {
    margin: 0;
    height: 100vh;
    background: radial-gradient(circle at top, #1a2a3a, #0b0f16);
    color: #f5f5f5;
    font-family: "PingFang SC", "Microsoft YaHei", sans-serif;
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: hidden;
}

/* 飘雪 */
.snow {
    position: fixed;
    top: -10px;
    color: rgba(255,255,255,0.75);
    user-select: none;
    animation: fall linear infinite;
}

@keyframes fall {
    to { transform: translateY(110vh); }
}

.container {
    text-align: center;
    width: 90%;
    max-width: 420px;
    z-index: 2;
}

.text {
    font-size: 15px;
    line-height: 1.9;
    opacity: 0;
    animation: textFade 2.5s ease forwards;
}

.text.delay1 { animation-delay: 1.5s; }
.text.delay2 { animation-delay: 5s; }
.text.delay3 { animation-delay: 8.5s; }
.text.delay4 { animation-delay: 13s; }
.text.delay5 { animation-delay: 18s; font-size: 12px; opacity: 0.6; }

.tree {
    margin: 34px auto;
    width: 0;
    height: 0;
    border-left: 85px solid transparent;
    border-right: 85px solid transparent;
    border-bottom: 150px solid #1f7a4d;
    position: relative;
    opacity: 0;
    animation: treeFade 3.5s ease forwards;
    animation-delay: 6s;
}

.tree::before {
    content: "";
    position: absolute;
    top: 42px;
    left: -65px;
    border-left: 65px solid transparent;
    border-right: 65px solid transparent;
    border-bottom: 120px solid #1c6b45;
}

.tree::after {
    content: "";
    position: absolute;
    top: 78px;
    left: -45px;
    border-left: 45px solid transparent;
    border-right: 45px solid transparent;
    border-bottom: 90px solid #185c3b;
}

/* 星星 */
.star {
    position: absolute;
    top: -26px;
    left: -14px;
    font-size: 24px;
    color: #ffd36a;
    opacity: 0;
    animation: starBlink 2s ease forwards;
    animation-delay: 10.5s;
}

/* 小灯 */
.light {
    position: absolute;
    width: 6px;
    height: 6px;
    border-radius: 50%;
    background: #ffd36a;
    opacity: 0;
    animation: lightOn 1.5s ease forwards;
}

@keyframes lightOn {
    to { opacity: 1; box-shadow: 0 0 6px rgba(255,211,106,0.8); }
}

/* 音乐按钮 */
.music-btn {
    position: fixed;
    top: 18px;
    right: 18px;
    font-size: 13px;
    padding: 6px 10px;
    border-radius: 20px;
    background: rgba(255,255,255,0.15);
    border: 1px solid rgba(255,255,255,0.25);
    color: #fff;
    cursor: pointer;
    z-index: 3;
}

@keyframes textFade {
    from { opacity: 0; transform: translateY(12px); }
    to { opacity: 1; transform: translateY(0); }
}

@keyframes treeFade {
    from { opacity: 0; transform: scale(0.92); }
    to { opacity: 1; transform: scale(1); }
}

@keyframes starBlink {
    0% { opacity: 0; }
    50% { opacity: 1; }
    100% { opacity: 1; }
}
</style>
</head>

<body>

<audio id="bgm" loop>
    <source src="https://cdn.pixabay.com/audio/2022/10/25/audio_6f3c5e3b5a.mp3" type="audio/mpeg">
</audio>

<div class="music-btn" onclick="toggleMusic()">♪ 音乐</div>

<div class="container">

    <div class="text delay1">
        今年的冬天<br>
        好像比以前<br>
        更安静一些
    </div>

    <div class="tree" id="tree">
        <div class="star">★</div>
    </div>

    <div class="text delay2">
        想把一些温柔的东西<br>
        慢慢放进这个冬天<br><br>
        不需要理由<br>
        只是觉得<br>
        你值得
    </div>

    <div class="text delay3">
        给 <strong>亲爱的小李</strong> 的圣诞树
    </div>

    <div class="text delay4">
        希望这个冬天<br>
        你会被很多温柔的事情包围<br><br>
        如果有一天<br>
        你觉得有点冷<br><br>
        也希望这棵树<br>
        能让你想起<br>
        有人真心祝你快乐<br><br>
        —— 圣诞快乐
    </div>

    <div class="text delay5">
        制作于 2025 年圣诞前
    </div>

</div>

<script>
// 飘雪
for (let i = 0; i < 45; i++) {
    const snow = document.createElement("div");
    snow.className = "snow";
    snow.innerText = "❄";
    snow.style.left = Math.random() * 100 + "vw";
    snow.style.animationDuration = 6 + Math.random() * 6 + "s";
    snow.style.fontSize = 8 + Math.random() * 10 + "px";
    document.body.appendChild(snow);
}

// 小灯生成
const tree = document.getElementById("tree");
const lightPositions = [
    {top: 30, left: -10},
    {top: 55, left: -30},
    {top: 55, left: 15},
    {top: 80, left: -20},
    {top: 80, left: 20},
    {top: 105, left: -5}
];

lightPositions.forEach((pos, i) => {
    const light = document.createElement("div");
    light.className = "light";
    light.style.top = pos.top + "px";
    light.style.left = pos.left + "px";
    light.style.animationDelay = (11 + i * 0.8) + "s";
    tree.appendChild(light);
});

// 音乐
const bgm = document.getElementById("bgm");
let playing = false;
function toggleMusic() {
    playing ? bgm.pause() : bgm.play();
    playing = !playing;
}
</script>

</body>
</html>

<!-- rebuild -->

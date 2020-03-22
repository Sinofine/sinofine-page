---
title: Friends
date: 2020-02-19 23:48:12
layout: false
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Friends</title>
    <style>
:root{
    font-family:serif;
}
main {
    display: flex;
    flex-direction: column;
    align-items: center;
    align-self: center;
    margin: -15% 0 0 0;
}
a{
    color:#333;
    text-decoration:none;
}
article.friends {
    display: flex;
    margin: 0.5em;
    flex-direction: column;
}
img.avatar {border-radius: 100%;width: 5em;height: 5em;align-self: center;}
.friends-container {
    display: flex;
    width: fit-content;
    align-content: center;
    justify-content: center;
    flex-wrap: wrap;
}
.friends h3 {
    margin: 0.5em auto;
}
.friends figure {
    margin: 0.1em auto;
    color: #555;
}
h1 {
    width: fit-content;
}
body {
    display: flex;
    min-height: 100vh;
    margin: 0;
    justify-content: center;
}
.home-button {
    position: fixed;
    left: 1em;
    top: 1em;
}</style>
</head>
<body>
    <div class="home-button" onclick="location.href = '/'">HOME</div>
    <main>
        <h1>Friends</h1>
        <div class="friends-container">
            <a href="https://bokutake.com"><article class="friends">
                <img src="https://secure.gravatar.com/avatar/86ef10df2865daf36471371b8260e138?s=100" alt="Bokutake" class="avatar">
                <h3>bokutake的小栈</h3>
                <figure>Welt von Bokutake</figure>
            </article></a>
            <a href="https://haotown.cn/"><article class="friends">
                <img src="https://secure.gravatar.com/avatar/d0b3bc8c616d20b72ba5d59a7a1c6c79?s=100" alt="Haotown" class="avatar">
                <h3>HAOTOWN</h3>
                <figure>疯狂减肥带</figure>
            </article></a><a href="https://diygod.me/"><article class="friends">
                <img src="https://cdn.jsdelivr.net/gh/DIYgod/diygod.me@gh-pages/images/DIYgod.jpg" alt="DIYGOD " class="avatar" width="100" height="100">
                <h3>DIYGod</h3>
                <figure>网红</figure>
            </article></a><a href="https://yecl.net/"><article class="friends">
                <img src="https://i.loli.net/2020/03/18/OUNRqcV62gatu8M.png" alt="YECL" class="avatar" width="100" height="100">
                <h3>夜绫千裕</h3>
                <figure>认证用户（请使用代理）</figure>
            </article></a><a href="https://yuki.yuki233.com/"><article class="friends">
                <img src="https://i.loli.net/2020/03/20/AsjGK1p3XxNyDZk.png" alt="yuki" class="avatar" width="100" height="100">
                <h3>初雪</h3>
                <figure>雪次元</figure>
            </article></a><a href="https://woshixiaofu666.github.io/"><article class="friends">
                <img src="https://i.loli.net/2019/12/10/uqBgf2D3Hpzdr6x.jpg" alt="xiaofu" class="avatar" width="100" height="100">
                <h3>我是小福</h3>
                <figure>R3</figure>
            </article></a><a href="https://www.mokeyjay.com/"><article class="friends">
                <img src="https://www.mokeyjay.com/headimg.png" alt="mokeyjay" class="avatar" width="100" height="100">
                <h3>Mokeyjay</h3>
                <figure>超能小紫</figure>
            </article></a><a href="https://skk.moe/"><article class="friends">
                <img src="https://cdn.jsdelivr.net/npm/skx@0.0.1/avatar/128x128.png" alt="sukka" class="avatar" width="100" height="100">
                <h3>Sukka</h3>
                <figure>苏卡卡！</figure>
            </article></a>
        </div>
    </main> 
</body>
</html>
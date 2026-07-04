<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For Vidhu ❤️</title>

<style>
body{
    margin:0;
    padding:0;
    font-family:Arial,sans-serif;
    background:linear-gradient(135deg,#ffb6c1,#ffd6e8,#ffeef5);
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
}

.card{
    width:90%;
    max-width:700px;
    background:white;
    border-radius:20px;
    padding:25px;
    text-align:center;
    box-shadow:0 10px 30px rgba(0,0,0,.2);
}

h1{
    color:#ff4f8b;
}

p{
    font-size:18px;
}

button{
    padding:12px 28px;
    margin:15px;
    border:none;
    border-radius:50px;
    font-size:18px;
    cursor:pointer;
    transition:.3s;
}

#yes{
    background:#ff4f8b;
    color:white;
}

#no{
    background:#666;
    color:white;
    position:absolute;
}

#letter{
    display:none;
    margin-top:20px;
    text-align:left;
    background:#fff5fa;
    padding:20px;
    border-radius:15px;
    line-height:1.7;
}

footer{
    margin-top:20px;
    color:#888;
}
</style>
</head>

<body>

<div class="card">

<h1>🌸 Hey Vidhu 🌸</h1>

<p>
Can I tell you something special? ❤️
</p>

<button id="yes">Yes 💖</button>
<button id="no">No 🙈</button>

<div id="letter">

<h2>💌 A Letter For You</h2>

<p>

Dear Vidhu,

I just wanted to tell you that you're one of the sweetest people I've ever met.

You're caring, supportive, kind, and honestly... super cute too. 🌸

Whenever we talk, it makes my day a little brighter. I genuinely enjoy knowing more about you, listening to your thoughts, and seeing your smile.

You have a beautiful heart, and that's what makes you truly amazing.

Thank you for being such a wonderful person. Never change who you are because your kindness is something really special.

No matter what happens, I hope you always keep smiling and chasing your dreams.

You deserve lots of happiness, laughter, and love.

Stay cute...
Stay amazing...
Stay YOU. ❤️

— Someone who thinks you're really special 🌹

</p>

</div>

<footer>
Made with ❤️ just for Vidhu
</footer>

</div>

<script>

const yes=document.getElementById("yes");
const no=document.getElementById("no");
const letter=document.getElementById("letter");

yes.onclick=()=>{
letter.style.display="block";
window.scrollTo({
top:document.body.scrollHeight,
behavior:"smooth"
});
};

no.onmouseover=()=>{
let x=Math.random()*(window.innerWidth-120);
let y=Math.random()*(window.innerHeight-60);
no.style.left=x+"px";
no.style.top=y+"px";
};

no.onclick=()=>{
alert("Nice try 😜... 'No' button doesn't work!");
};

</script>

</body>
</html>

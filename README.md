<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <title>seu jogos</title>
    <!DOCTYPE html>
<html lang="pt-BR">
<head>
    <title>seu jogos</title>
    <style>
        body{
    background-color: rgb(199, 171, 112);
    color: white;
    }

header{
    font: normal 25pt arial;
    text-align: center;
}

section{
    background-color: white;
    color: black;
    padding: 20px;
    width: 650px;
    margin: auto;
    border-radius: 15px;
    box-shadow: 5px 5px 10px black;
    }

footer{
    text-align: center;
    color: rgb(240, 242, 247)
}

img{
    box-shadow: 5px 5px 10px black;
    border-radius: 10px;
    width: 100px;
    height: 150px;
    cursor: pointer;
}

div{
    padding: 25px;
}
    </style>
</head>
<body>
    <header>
        <div id="title">
            SEUS JOGOS
        </div>
    </header>
    <section>
        <img src="https://bdjogos.com.br/capas/3778-the-legend-of-zelda-twilight-princess-wii-capa-1.jpg" id="img1" onmouseenter="enter1()" onmouseout="out1()">
        <img src="https://www.ultimagame.es/god-war-ascension/imagen-i7638-pge.jpg" alt="" id="img2" onmouseenter="enter2()" onmouseout="out2()">
        <img src="http://www.mobygames.com/images/covers/l/310953-assassin-s-creed-brotherhood-xbox-360-front-cover.jpg" alt="" id="img3" onmouseenter="enter3()" onmouseout="out3()">
        <img src="https://now.estarland.com/images/products/18/71118/Legend-of-Zelda-Tears-of-The-Kingdom-large-image.jpg" alt="" id="img4" onmouseenter="enter4()" onmouseout="out4()">
        <img src="https://www.movegame.co.il/uploads/images/big58405.jpg" alt="" id="img5" onmouseenter="enter5()" onmouseout="out5()">
        <img src="https://images-na.ssl-images-amazon.com/images/I/919sAiaL72L._SL1500_.jpg" alt="" id="img6" onmouseenter="enter6()" onmouseout="out6()">
    </section>
    <footer>
        <div id="nome">
            JOGO:
        </div>
    </footer>
    <script src="jogos.js"></script>
</body>
</html>
style>
</head>
<body>
    <header>
        <div id="title">
            SEUS JOGOS
        </div>
    </header>
    <section>
        <img src="https://bdjogos.com.br/capas/3778-the-legend-of-zelda-twilight-princess-wii-capa-1.jpg" id="img1" onmouseenter="enter1()" onmouseout="out1()">
        <img src="https://www.ultimagame.es/god-war-ascension/imagen-i7638-pge.jpg" alt="" id="img2" onmouseenter="enter2()" onmouseout="out2()">
        <img src="http://www.mobygames.com/images/covers/l/310953-assassin-s-creed-brotherhood-xbox-360-front-cover.jpg" alt="" id="img3" onmouseenter="enter3()" onmouseout="out3()">
        <img src="https://now.estarland.com/images/products/18/71118/Legend-of-Zelda-Tears-of-The-Kingdom-large-image.jpg" alt="" id="img4" onmouseenter="enter4()" onmouseout="out4()">
        <img src="https://www.movegame.co.il/uploads/images/big58405.jpg" alt="" id="img5" onmouseenter="enter5()" onmouseout="out5()">
        <img src="https://images-na.ssl-images-amazon.com/images/I/919sAiaL72L._SL1500_.jpg" alt="" id="img6" onmouseenter="enter6()" onmouseout="out6()">
    </section>
    <footer>
        <div id="nome">
            JOGO:
        </div>
    </footer>
    <script>
        function enter1(){
    document.getElementById('nome').style.transition = '2s'
    document.getElementById('nome').style.color = 'green'
    document.getElementById('img1').style.transition = '1s'
    document.getElementById('img1').style.width = '125px' 
    document.getElementById('img1').style.height = '190px'
    document.getElementById('nome').innerHTML = 'JOGO: The Legends of Zelda Twilight Princess'
}

function out1(){
    document.getElementById('nome').style.transition = '2s'
    document.getElementById('nome').style.color = 'white'
    document.getElementById('img1').style.width = '100px' 
    document.getElementById('img1').style.height = '150px'
    document.getElementById('nome').innerHTML = 'JOGO:'
}

function enter2(){
    document.getElementById('nome').style.transition = '2s'
    document.getElementById('nome').style.color = 'green'
    document.getElementById('img2').style.transition = '1s'
    document.getElementById('img2').style.width = '125px' 
    document.getElementById('img2').style.height = '190px'
    document.getElementById('nome').innerHTML = 'JOGO: God of War Acesion'
}

function out2(){
    document.getElementById('nome').style.transition = '2s'
    document.getElementById('nome').style.color = 'white'
    document.getElementById('img2').style.width = '100px' 
    document.getElementById('img2').style.height = '150px'
    document.getElementById('nome').innerHTML = 'JOGO:'
}

function enter3(){
    document.getElementById('nome').style.transition = '2s'
    document.getElementById('nome').style.color = 'green'
    document.getElementById('img3').style.transition = '1s'
    document.getElementById('img3').style.width = '125px' 
    document.getElementById('img3').style.height = '190px'
    document.getElementById('nome').innerHTML = "JOGO: Assassin's Creed BrotherHood"
}

function out3(){
    document.getElementById('nome').style.transition = '2s'
    document.getElementById('nome').style.color = 'white'
    document.getElementById('img3').style.width = '100px' 
    document.getElementById('img3').style.height = '150px'
    document.getElementById('nome').innerHTML = 'JOGO:'
}

function enter4(){
    document.getElementById('nome').style.transition = '2s'
    document.getElementById('nome').style.color = 'green'
    document.getElementById('img4').style.transition = '1s'
    document.getElementById('img4').style.width = '125px' 
    document.getElementById('img4').style.height = '190px'
    document.getElementById('nome').innerHTML = "JOGO: The Legends of Zelda Tears of the kingdom"
}

function out4(){
    document.getElementById('nome').style.transition = '2s'
    document.getElementById('nome').style.color = 'white'
    document.getElementById('img4').style.width = '100px' 
    document.getElementById('img4').style.height = '150px'
    document.getElementById('nome').innerHTML = 'JOGO:'
}

function enter5(){
    document.getElementById('nome').style.transition = '2s'
    document.getElementById('nome').style.color = 'green'
    document.getElementById('img5').style.transition = '1s'
    document.getElementById('img5').style.width = '125px' 
    document.getElementById('img5').style.height = '190px'
    document.getElementById('nome').innerHTML = "JOGO: Ghost of Tsushima"
}

function out5(){
    document.getElementById('nome').style.transition = '2s'
    document.getElementById('nome').style.color = 'white'
    document.getElementById('img5').style.width = '100px' 
    document.getElementById('img5').style.height = '150px'
    document.getElementById('nome').innerHTML = 'JOGO:' 
}

function enter6(){
    document.getElementById('nome').style.transition = '2s'
    document.getElementById('nome').style.color = 'green'
    document.getElementById('img6').style.transition = '1s'
    document.getElementById('img6').style.width = '125px' 
    document.getElementById('img6').style.height = '190px'
    document.getElementById('nome').innerHTML = "JOGO: X-Men Origins Wolverine"
}

function out6(){
    document.getElementById('nome').style.transition = '2s'
    document.getElementById('nome').style.color = 'white'
    document.getElementById('img6').style.width = '100px' 
    document.getElementById('img6').style.height = '150px'
    document.getElementById('nome').innerHTML = 'JOGO:' 
}
    </script>
</body>
</html>

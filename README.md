<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <title>seu jogos</title>
    <style>
        div#jogo{
            color: white;
        }
        h1{
            color: white;
            font: x-small 15pt arial;
        }
        img#img1{
            border-radius: 10px;
            cursor: pointer;
        }

        img#img2{
            border-radius: 10px;
            cursor: pointer;
        }

        img#img3{
            cursor: pointer;
            border-radius: 10px;
        }

        img#img4{
            cursor: pointer;
            border-radius: 10px;
        }

        img#img5{
            cursor: pointer;
            border-radius: 10px;            
        }

        img#img6{
            cursor: pointer;
            border-radius: 10px;            
        }

        body{
            background-color: rgb(88, 82, 82);
        }
    </style>
</head>
<body>
    <h1>Venha Jogar</h1>
    <img src="https://bdjogos.com.br/capas/3778-the-legend-of-zelda-twilight-princess-wii-capa-1.jpg" id="img6" style="width: 100px; height: 150px;" onmouseenter="enter6()" onmouseout="out6()">
    <img src="https://www.ultimagame.es/god-war-ascension/imagen-i7638-pge.jpg" id="img5" style="width: 100px; height: 150px;" onmouseenter="enter5()" onmouseout="out5()">
    <img src="http://www.mobygames.com/images/covers/l/310953-assassin-s-creed-brotherhood-xbox-360-front-cover.jpg" id="img4" style="width: 100px; height: 150px;" onmouseenter="enter4()" onmouseout="out4()">
    <img src="https://now.estarland.com/images/products/18/71118/Legend-of-Zelda-Tears-of-The-Kingdom-large-image.jpg" id="img3" style="width: 100px; height: 150px;" onmouseenter="enter3()" onmouseout="out3()">
    <img src="https://www.movegame.co.il/uploads/images/big58405.jpg" id="img1" style="width: 100px; height: 150px;" onmouseenter="enter2()" onmouseout="out2()">
    <img src="https://images-na.ssl-images-amazon.com/images/I/919sAiaL72L._SL1500_.jpg" id="img2" style="width: 100px; height: 150px;" onmouseenter="enter1()" onmouseout="out1()">
    <div id="jogo">Jogo:</div>
    <script>
        function enter6(){
            document.getElementById('img6').style.width = '125px';
            document.getElementById('img6').style.height = '200px';
            document.getElementById('jogo').innerText = 'Jogo: zelda Twilight Princess'          
        }

        function enter5(){
            document.getElementById('img5').style.width = '125px';
            document.getElementById('img5').style.height = '200px';
            document.getElementById('jogo').innerText = 'Jogo: God of War Ascension'            
        }

        function enter4(){
            document.getElementById('img4').style.width = '125px';
            document.getElementById('img4').style.height = '200px';
            document.getElementById('jogo').innerText = "Jogo: Assassins's Creed BrotherHood"            
        }

        function enter3(){
            document.getElementById('img3').style.width = '125px';
            document.getElementById('img3').style.height = '200px'; 
            document.getElementById('jogo').innerText = 'Jogo: Zelda Tears of the Kingdon'
        }

        function enter2(){
                document.getElementById('img1').style.width = '125px';
                document.getElementById('img1').style.height = '200px';
                document.getElementById('jogo').innerText = "Jogo: Ghost of Tsushima"
    }

        function enter1(){
            document.getElementById('img2').style.width = '125px';
            document.getElementById('img2').style.height = '200px'; 
            document.getElementById('jogo').innerText = "Jogo: X-Men Origins Wolverine"      
    }

        function out2(){
            document.getElementById('img1').style.width = '100px';
            document.getElementById('img1').style.height = '150px';
            document.getElementById('jogo').innerText = "Jogo:"
        }

        function out1(){
            document.getElementById('img2').style.width = '100px';
            document.getElementById('img2').style.height = '150px';
            document.getElementById('jogo').innerText = "Jogo:"
        }

        function out3(){
            document.getElementById('img3').style.width = '100px';
            document.getElementById('img3').style.height = '150px';
            document.getElementById('jogo').innerText = "Jogo:"
        }

        function out4(){
            document.getElementById('img4').style.width = '100px';
            document.getElementById('img4').style.height = '150px';
            document.getElementById('jogo').innerText = "Jogo:"
        }

        function out5(){
            document.getElementById('img5').style.width = '100px';
            document.getElementById('img5').style.height = '150px';
            document.getElementById('jogo').innerText = "Jogo:"
        }

        function out6(){
            document.getElementById('img6').style.width = '100px';
            document.getElementById('img6').style.height = '150px';
            document.getElementById('jogo').innerText = "Jogo:"
        }        
    </script>
</body>
</html>

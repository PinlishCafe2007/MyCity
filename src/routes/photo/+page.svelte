<svelte:head>
<title>Фотографии</title>
</svelte:head>
<h1>Фотогалерея</h1>
<div class="photo">
    <a class="a1" href="https://kartinkin.net/pics/uploads/posts/2022-08/thumbs/1660369767_16-kartinkin-net-p-respublika-khakasiya-stolitsa-abakan-krasi-16.jpg"><img src="https://kartinkin.net/pics/uploads/posts/2022-08/thumbs/1660369767_16-kartinkin-net-p-respublika-khakasiya-stolitsa-abakan-krasi-16.jpg" alt="one_small"></a>
    <a class="a2" href="https://cloud.pulse19.ru/uploads/2019/10/vid-na-vechernij-abakan.jpg"><img src="https://cloud.pulse19.ru/uploads/2019/10/vid-na-vechernij-abakan.jpg"></a>
    <a class="a3" href="https://krot.info/uploads/posts/2021-12/1640788740_2-krot-info-p-abakan-stolitsa-krasivo-foto-2.jpg"><img src="https://krot.info/uploads/posts/2021-12/1640788740_2-krot-info-p-abakan-stolitsa-krasivo-foto-2.jpg" alt="three_small"></a>
    <a class="a4" href="https://kartinkin.net/pics/uploads/posts/2022-08/1660347947_11-kartinkin-net-p-abakan-stolitsa-krasivo-foto-11.jpg"><img src="https://kartinkin.net/pics/uploads/posts/2022-08/1660347947_11-kartinkin-net-p-abakan-stolitsa-krasivo-foto-11.jpg" alt="four_small"></a>
    <a class="a5" href="https://img.pac.ru/resorts/213151/409141/big/49F4E6A57F0001011A89BE6AF42F1AD7.jpg"><img src="https://img.pac.ru/resorts/213151/409141/big/49F4E6A57F0001011A89BE6AF42F1AD7.jpg" alt="five_small"></a>
    <a class="a6" href="https://upload.wikimedia.org/wikipedia/commons/thumb/2/27/Abakan-.jpg/1200px-Abakan-.jpg"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/27/Abakan-.jpg/1200px-Abakan-.jpg" alt="six_small"></a>
</div>
<style>
    h1{
    text-align: center;
    text-shadow: 3px 2px 1px rgba(0,0,0,0.2);
    }
    .photo{
    margin: 0 auto;
    width: 530px;
    height: 480px;
    position: relative;
    }
    .photo a{
    background-color: white;
    padding: 10px;
    border: 1px solid black;
    position: absolute;
    text-shadow: 5px 5px 1px rgba(0,0,0,0.4);
    border-radius: 10px;
    }
    img{
    border-radius: 10px;
    width: 430px;
    height: 300px;
    }
    .photo a:hover{
    z-index: 1;
    }
    .a1{
    left: 10px;
    top: 10px;
    }
    .a2{
    left: 50px;
    top: 50px;
    }
    .a3{
    left: 90px;
    top: 90px;
    }
    .a4{
    left: 130px;
    top: 130px;
    }
    .a5{
    left: 170px;
    top: 170px;
    }
    .a6{
    left: 210px;
    top: 210px;
    }
</style>
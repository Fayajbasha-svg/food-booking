<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Zomato Banner</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    background:#111;
    display:flex;
    justify-content:center;
    align-items:center;
    min-height:100vh;
    font-family:Arial,sans-serif;
}

.banner{
    width:1000px;
    height:500px;
    display:flex;
    overflow:hidden;
    border-radius:10px;
}

.left{
    flex:2;
    background:url('food.jpg') center/cover;
    position:relative;
}

.right{
    flex:1;
    background:linear-gradient(
        180deg,
        #0d2b7e 0%,
        #1e2f88 40%,
        #c71947 100%
    );
    position:relative;
}

.logo{
    position:absolute;
    top:30px;
    right:30px;
    color:white;
    font-size:40px;
    font-weight:bold;
}

.phone{
    position:absolute;
    top:50%;
    left:65%;
    transform:translate(-50%,-50%) rotate(5deg);
    width:250px;
    height:450px;
    background:#ff4040;
    border:10px solid #fff;
    border-radius:40px;
    box-shadow:0 10px 30px rgba(0,0,0,.5);
}

.notch{
    width:120px;
    height:25px;
    background:black;
    border-radius:0 0 15px 15px;
    margin:auto;
}

.screen{
    text-align:center;
    margin-top:140px;
    color:white;
}

.screen h1{
    font-size:55px;
}

.pizza{
    font-size:70px;
}

.food-text{
    position:absolute;
    bottom:30px;
    left:30px;
    color:white;
    font-size:40px;
    font-weight:bold;
}
</style>
</head>
<body>

<div class="banner">

    <div class="left">
        <div class="food-text">Delicious Food</div>
    </div>

    <div class="right">
        <div class="logo">equentis</div>
    </div>

    <div class="phone">

        <div class="notch"></div>

        <div class="screen">
            <div class="pizza">🍕</div>
            <h1>Zomato</h1>
        </div>

    </div>

</div>

</body>
</html>

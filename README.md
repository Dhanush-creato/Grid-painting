Source Code 👇🏼👇🏼
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    *{
        background-color: rgb(190, 180, 180);
       

    }
    .container{
        display: grid;
        grid-template-columns: 20px 50px 100px 30px 90px 40px 50px;
        grid-template-rows: 100px 100px 50px 80px;
        background-color: black;
        gap: 6px;
        width: 425px;
        height: 360px;

    }
    .white1{
        background-color: white;
    }
    .yellow{
        background-color: yellow;
    }
    .red{
        background-color: red;
    }
    .blue{
        background-color: blue;
        grid-column: span 2;
    }
    .yellow2{
        background-color: yellow;

    }
    .white2{
        background-color: white;
    }
    .white3{
        background-color: brown;
        grid-column:span 2 ;
    }
    .white4{
        background-color: white;
    }
    .white5{
        background-color: green;
        grid-row: span 2;
    }
    .red2{
        background-color: red;
        grid-area: 2/5/2/7;
    }
    .white6{
        background-color: white;
        grid-row: span 2;
    }
    .blue2{
        background-color: blue;
        grid-row: span 2;
    }
    .white7{
        background-color: white;
    }
    .white8{
        background-color:yellow;
        grid-area:3/2/3/4 ;
    }
    .white9{
        background-color: yellow;
    }
    .blue3{
        background-color: red;
    }
    .white10{
        background-color: blue;
        grid-column: span 2;
    }
    .yellow3{
        background-color: white;
        grid-column: span 2;
        
    }
    .red3{
        background-color: rgb(118, 27, 27);
    }
    

</style>
<body>
    <div class="container">
        <div class="white1 item"></div>
        <div class="yellow item"></div>
        <div class="red iteam"></div>
        <div class="blue iteam"></div>
        <div class="yellow2 iteam"></div>
        <div class="white2 iteam"></div>
        <div class="white3 iteam"></div>
        <div class="white4 iteam"></div>
        <div class="white5 iteam"></div>
        <div class="white6 iteam"></div>
        <div class="red2 iteam"></div>
        <div class="blue2 iteam"></div>
        <div class="white7 iteam"></div>
        <div class="white8 iteam"></div>
        <div class="white9 iteam"></div>
        <div class="blue3 iteam"></div>
        <div class="white10 iteam"></div>
        <div class="yellow3 iteam"></div>
        <div class="red3 iteam"></div>
        
    
</body>
</html>

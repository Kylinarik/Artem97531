<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<title>Kylinarik</title>
<link rel="icon" href="/Praktika/Laba/img/favicon.ico" type="image/x-icon" />
<link rel="shortcut icon" href="/Praktika/Laba/img/favicon.ico" type="image/x-icon" />
<link rel="stylesheet" href="/Praktika/Laba/fonts/appetite.css">  

	   
<style>

V{font-family: "Appetite";}


html { overflow:  hidden; }

p{ position:absolute;
   left:600px; 
   top:180px;
   /*text-align: right;/**/
  }
  
  
  p1{ position:absolute;
     left:600px; 
     top:25px;
    }



img {
    border: 30px solid transparent; /* Прозрачная рамка */
   }
   img:hover {
    border: 0px solid #00af64; /* Цветная рамка */
	box-shadow: 7px 7px 5px rgba(0,0,0,0.6); /* Тень */
	border-radius: 10px; /* Радиус скругления */
   }
   

    #sidebar {    
    top: 100px; /* Расстояние от верхнего края */ 
    bottom: 0; /* Расстояние снизу  */
   }
    
  

  
      .rectangle{
    height: 50px;
    width: 600px;    
    background: #FFFFFF;
    border-radius:  7px  ;
    margin-left: auto;
    margin-right: auto;
    
    
    }


   
.main-menu {
    list-style: none;
    margin: 0;
    padding: 0;
   
    margin-top: 30px;
    font-family: 'Montserrat', sans-serif;   
    /* Для выравнивания меню по центру */
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
   
}
.main-menu > li {
    display: inline-flex;
}
.main-menu > li + li {
    margin-left: 20px;
}
.main-menu > li > a {
    padding: 0 0 20px 0;
    position: relative;
    text-transform: uppercase;   
    color: #000;
    font-weight: bold;
    letter-spacing: 0.2px;
    font-size: 15px;
    text-decoration: none;   
}
.main-menu > li > a:hover {
    text-decoration: none;   
    color: #000080;
}
.main-menu > li > a:after {
    width: 0;
    height: 3px;
    background-color: #0000FF;
    content: '';
    left: 0;
    bottom: 10px;
    position: absolute;
    transition: all .3s;
}
.main-menu > li > a:hover::after {
    width: 100%;
}
.main-menu > li.active a:after {
    width: 100%;
}
.main-menu li {
    margin: 0;
    white-space: nowrap;
}
.main-menu li.menu-children {
    position: relative;
    margin-right: 12px;
}
.main-menu li.menu-children:after {
    position: absolute;
    content: "\2039";
    color: #0000FF;
    font-size: 20px;
    font-weight: bold;
    right: -12px;
    top: -2px;
    transform: rotate(-90deg);
}
.main-menu li li.menu-children:after {
    position: absolute;
    content: "\2039";
    color:#0000FF;
    font-size: 20px;
    font-weight: bold;
    right: 10px;
    top: 12px;
    transform: rotate(180deg);
}
.main-menu li.menu-children:hover > ul {
    opacity: 1;
    visibility: visible;
    transform: translateY(0);
}
.main-menu ul {
    padding: 10px 0;
    margin: 0;
    list-style: none;
    background-color: #0000FF;
    position: absolute;
    z-index: 20;
    min-width: 220px;
    top: 100%;
    left: -30px;
    opacity: 0;
    visibility: hidden;
    transform: translateY(5px);
    transition: all 200ms cubic-bezier(0.43, 0.59, 0.16, 1.25);
}
.main-menu ul li {
    display: block;
    padding: 0 10px;
    line-height: 1.1;
}
.main-menu ul li:last-child {
    margin-bottom: 0;
}
.main-menu ul li a {
    display: block;
    color: #fff;
    padding: 10px;
    transition: all .3s;
    text-decoration: none;   
}
.main-menu ul li a:hover {
    color: #0000FF;
    background: #FFF;
    text-decoration: none;   
}
.main-menu ul ul {
    top: 0;
    left: 100%;
}
</style>
</head>

<body>


<div class="rectangle"><ul class="main-menu">
    <li class="active"><a href="/Praktika/Laba/Kulinarik.html">Рецепты</a></li>
    <li class="menu-children">
        <a href="#url">Питание</a>
        <ul>
            <li><a href="/Praktika/Laba/FoodP.html">Правильное</a></li>
            <li><a href="#url">Неправильное</a></li>
            <li class="menu-children">
                <a href="#url">Напитки</a>
                <ul>
                    <li><a href="#url">Холодные</a></li>
                    <li><a href="#url">Горячие</a></li>           
                </ul>
            </li>           
        </ul>
    </li>
    <li><a href="/Praktika/Laba/News.html">Новости</a></li>
    <li><a href="#url">Фотогалерея</a></li>
    <li><a href="/Praktika/Laba/Me.html">Обо мне</a></li>       
</ul></div>

<div style="position:absolute;left:80px; top:150px "><img src="/Praktika/Laba/img/S.JPG" width="450" height="300"></div>





<V>
<div style="position:absolute;left:800px; top:170px"><font size="4">
<table bordercolor="000000" border="0" width="160%" align="right" rules="groups">
   
   
    <tr><strong>ИНГРЕДИЕНТЫ:</strong></tr>
   
   <tr><td>Куриные ножки</td><td>600 г </td></tr>
   <tr><td>Растительное масло</td><td>60 мл</td></tr>
   <tr><td>Бальзамика</td><td>1 ст.л.</td></tr>
   <tr><td>Соевый соус</td><td>2 ст.л.</td></tr>   
   <tr><td>Зернистая горчица</td><td>1 ст.л. </td></tr>   
   <tr><td>Чеснок</td><td></td></tr>
   <tr><td>Специи</td><td></td></tr> 
  </table></font></div>

<div style="position:absolute;left:500px; top:570px"><font size="4">
<strong>Приготовление</strong>: Смешай все ингредиенты для маринада и добавь специи по вкусу. </br>
Сложи куриные ножки в рукав, залей маринадом, завяжи и хорошо перемешай.</br> 
Оставь их на столе на час, а потом запекай 30 минут в духовке при 180 градусах.
</font></div></V>


</body>
</html>

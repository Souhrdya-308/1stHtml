<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personalized Gift</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    
    <style>

nav {
            background-color: rgb(245,245,245);
            color: red;
            padding: 10px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav ul {
            list-style-type: none;
            display: flex;
        }

        nav li {
            margin-right: 20px;
        }

        

        nav a:hover {
            color: orangered;
        }
        .nav-link {
            text-decoration: none;
            color: red;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        .nav-link:hover {
            color: #a3c6c9;
        }

body{
    background-color: rgb(255,249,249);
}
#loginRegistor {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #e67676;
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }

        .container {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 300px;
            text-align: center;
        }

        label {
            display: block;
            margin-bottom: 8px;
            font-weight: bold;
        }

        input {
            width: 100%;
            padding: 8px;
            margin-bottom: 16px;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }

        button {
            background-color: #333;
            color: #fff;
            padding: 10px 15px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }








.card-content{
   display:flex;
    flex-wrap:wrap;
    width:100%;
    height:auto;
    justify-content:center;
    padding: 20px;
    flex-direction: row;
    background-color: antiquewhite; 
    align-items: center;
    gap: 40px;
    border:0;
    

}
.item{
    width:350px;
    height:400px;
    border:3px rgb(163, 32, 32) solid;
    margin:40px 0px;
    border-radius: 5px;
    text-align:center;
    background-color: white;
    cursor: pointer;
    

    
}

.item2{
    width:350px;
    height: auto;
    border:3px rgb(186, 31, 31) solid;
    margin: 40px 0px;
    border-radius: 5px;
    text-align:center;
    background-color: white;
    cursor: pointer;

}
.add{
    color:white;
    background-color: red;
    height:35px;
    width:348px;
    margin:0;
    font-size: 25px;
    border-radius: 5px;
    
}
.item > p{
    text-align: center;
    font-size: 24px;
    color: red;
    font-weight:bold;

}

img{
    width:100%;
    height:325px;

}
.pic{
    width:100%;
    height:760px;
    background-color: aliceblue ;


}
.big{
    width: 100%;
    height:650px;
    
}
.pic > p{
    text-align: center;
    font-size: 40px;
    color:red;
}
.item2 > img{
    width:100%;
    height:330px;
}
.item2 > p{
    font-size:18px;
    font-weight: bold;
    text-align: left;
}
.add:hover{
    background-color: darkred;
}
a:hover{
    border-color: darkred;
}
.n:hover, .m:hover{
   color:  darkred ;
}
.m{
    font-size:25px;
    font-weight:bold;
    color:red;

}
.n{
    font-size:20px;
}
.hh{
    width:100%;
    height:300px;
    text-align: left;
}
.ppp{
    width:100%;
    height:300px;
}
.homepage{
    width:96%;
    height:auto;
    display :flex;
    flex-wrap: wrap;
    justify-content: space-around;
    border:0;
    margin: 0;
    background-color: #c2e4e7;
    padding :40px;

    


}
.circle{
    margin: 0;
    border:1px black solid;
    border-radius: 50%;
    width:150px;
    height:150px;
   
    

}
.circle > img{
    width:150px;
    height:150px;
    border-radius: 50%;
}
.box {
    width:150px;
    height: 200px;
    align-items: center;
    cursor: pointer;
    

}
.box > p{
    font-size: 16px;
    color: black;
    text-align: center;

}
h1{
    font-size: 30;
    color: red;
    text-align: center;
}
header > p{
    
    color:red;
    text-align:left;
    font-size: 45px;
    font-weight:bold;
    font-family: Arial, Helvetica, sans-serif;
    text-align:center;
    display:inline;
    cursor: pointer;
    
}
.forgot-password {
            margin-top: 10px;
            font-size: 14px;
            color: #0c6462;
            text-decoration: underline;
            
}
.header {
    width:100%;
    height:100px;
    background-color: rgb(255, 232, 243);
    display :flex;
    flex-wrap:wrap;
    }

#search{
  display : inline ;
   align-self: center;  
   font-size: 30px;
   border-radius: 15px;
}
.hea{
    width:40%;
    height:100%;
    display: inline;
}
.hea > img{
    width:300px;
    height:100px;
}
.h11{
    padding: 30px;
    width: 700px;;

}
.sea{
    width:32px;
    height:32px;
    border-radius: 50%;
   
}
.icons{
    width:100px;
    padding: 30px;
}
.track{
    width:35px;
    height:35px;
    border-radius: 10px;
}
.con{
    font-size:28px;
}
.v{
    align-self: center;
    font-size: 16px;
    font-weight: bold;
    text-align: center;
}
a > p{
    text-align: center;
}
.headd{
    width: 100%;
    height:80px;
    background-color: lightgoldenrodyellow;
    text-align: center;
    color: red;
    font-size: 40px;
    margin: 0;
}
.textto{
    width: 9.5%;
    align-items: center;
    padding:70px;
    display: flex;
    flex-wrap:wrap ;
    align-items: center;
}
#addto{
     font-size: 30px;
    border-radius: 10px;
    border:5px black dashed;

}

    </style>

</head>
<body>
    
    <header >
        <div class="header">
       <div class="hea"><img src="forever.jpg"></div>
       <div class="h11"><input name="search" id= "search" placeholder="Search...." type="text">
        <label for="search"></label></div>
        <div class="icons"><img class="track" src="track.jpg">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img class="track" src="addto.jpg"></div>
        </div>

    </header>
    <nav>
        <a onclick="showPage('home')"><p class="n">Home</p></a>
        <a onclick="showPage('cake')"><p class="n">Cake</p></a>
        <a onclick="showPage('card')"><p class="n">Greeting Card</p></a>
        <a onclick="showPage('flowers')"><p class="n">Flowers</p></a>
        <a onclick="showPage('perso')"><p class="n">Personalized Gifts</p></a>
        <a onclick ="showPage('loginRegistor')"><P class="n">Register/login</P></a>
    </nav>
    <section id="home">
        <div class="pic">
            <img class="big" src="homepic.jpg"><p>Welecome To Forever 21</p>
        </div>
       
        <div class="homepage">

            
            <div class="box"><a onclick="showPage('frame')"><div class="circle"><img src="frame.jpg"></div><p class="v">Photo Frame</p></a></div>
            <div class="box"><a onclick="showPage('white')"><div class="circle"><img src="whiteflr3.jpg"></div><p class="v">Flower</p></a></div>
            <div class="box"><a onclick="showPage('birthday')"><div class="circle"><img src="birthday.jpg"></div><p class="v">Birthday Card</p></a></div>
            <div class="box"><a onclick="showPage('red')"><div class="circle"><img src="redflr4.jpg"> </div><p class="v">Roses</p></a></div>
            <div class="box"><a onclick="showPage('pillow')"><div class="circle"><img src="pillow.jpg"></div><p class="v">Pillow </p></a></div>
            <div class="box"><a onclick="showPage('Black Forest')"><div class="circle"><img src="Cake images\black forestt.png"></div><p class="v">Black Froest</p></a></div>
            <div class="box"><a onclick="showPage('chris')"><div class="circle"><img src="chistmas.jpg"></div><p class="v">Greeting Cards</p></a></div>
            <div class="box"><a onclick="showPage('Butterscotch')"><div class="circle"><img src="Cake images\Butterscotch cream cake.png"></div><p class="v">Butter Scoch</p></a></div>
            <div class="box"><a onclick="showPage('exotic')"><div class="circle"><img src="exoticflowers.jpg"></div><p  class="v">Exotic Flowers</p></a></div>

        </div>
        <div class ="headd"><h1>OFFERS OF THE DAY DELICOUSE CAKES</h1></div>
        
        <div class="card-content">
            <div class="item2"><a onclick ="showPage('Chocolate')"><img src="Cake images\ccake.png"><p>0.5 Kg Chocolate Truffle Cake</p></a><p class="rupee">&nbsp;&#8377;500<br></p><div class="add">Add to Cart</div></div>
            <div class="item2"><a onclick ="showPage('Chocolate')"><img src="Cake images\choco cake.png"><p>Chocolate Dropping Cake 500 Gm</p></a><p class="rupee">&nbsp;&#8377;699<br></p><div class="add">Add to Cart</div></div>
            <div class="item2"><a onclick ="showPage('Chocolate')"><img src="Cake images\choco gems cake.png"><p>Chocolate Gems Cream Cake</p></a><p class="rupee">&nbsp;&#8377;599<br></p><div class="add">Add to Cart</div></div>
            <div class="item2"><a onclick ="showPage('Chocolate')"><img src="Cake images\chocolate cake .png"><p>Kitkat Gems Designer Cakes</p></a><p class="rupee">&nbsp;&#8377;800<br></p><div class="add">Add to Cart</div></div>
            </div>
            <div class="headd"><h1>OFFERS OF THE DAY PERSONAL CARDS</h1></div>
            <div class="card-content">
                <div class="item2"><img src="perso11.jpg"><p class="con">Special Wishes For You On Christmas Personalised Card</p><p class="rupee">&nbsp;&#8377;375</p><div class="add">Add to Cart</div></div>
                <div class="item2"><img src="perso12.jpg"><p class="con">Merry Christmas With Best Wishes and Love Personalised Card</p><p class="rupee">&nbsp;&#8377;375</p><div class="add">View Details</div></div>
                <div class="item2"><img src="perso13.jpg"><p class="con">It Is Christmastime Personalised Card for your loved ones</p><p class="rupee">&nbsp;&#8377;375</p><div class="add">View Details</div></div>
                <div class="item2"><img src="perso14.jpg"><p class="con">Warm Wishes At Christmas Personalised Card for your friends</p><p class="rupee">&nbsp;&#8377;375</p><div class="add">View Details</div></div>
        </div>    



    </section>

    <section id="cake">
        <div class="pic">
            <img class="big" src="https://archiesonline.com/uploads/category/banner/category_632da423e9aa92-21079386-36158965.jpg"><p>Cake</p>
        </div>
        <div class ="card-content">
            <div class="item"><a onclick="showPage('Chocolate')"><img src="Cake images\chocolate.png"></a><p class="m">Chocolate Cakes</p></div>
            <div class="item"><a onclick ="showPage('Red velvet')"><img src="Cake images\red velvet.png"></a><p class="m">Red Velvet</p></div>
            <div class="item"><a onclick="showPage('Butterscotch')"><img src="Cake images\butterscotch .png"></a><p class="m">Butterscotch Cakes</p></div>
            <div class="item"><a onclick="showPage('Black Forest')"><img src="Cake images\blck forest.png"></a><p class="m">Blackforest Cakes</p></div>
            <div class="item"><a onclick="showPage('Pineapple')"><img src="Cake images\pineapple.png"></a><p class="m">Pineapple Cakes</div>
            
        </div>
    </section>


    <section id="loginRegistor">
        <div class="container">
            <h2>Login</h2>
            <form action="/login" method="post">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
    
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" required>
    
                <button type="submit">Login</button>
            </form>
    
            <p class="forgot-password" onclick="showForgotPassword()">Forgot Password?</p>
    
            <hr>
    
            <h2>Register</h2>
            <form action="/register" method="post">
                <label for="registerEmail">Email:</label>
                <input type="email" id="registerEmail" name="registerEmail" required>
    
                <label for="registerPassword">Password:</label>
                <input type="password" id="registerPassword" name="registerPassword" required>
    
                <button type="submit">Register</button>
            </form>
        </div>

    </section>
    
    <section id="Chocolate">
        <div class="pic">
            <img class="big" src="https://archiesonline.com/uploads/category/banner/category_632da423e9aa92-21079386-36158965.jpg"><p>Chocolate Cake</p>
        </div>
        <div class="card-content">
            <div class="item2"><img src="Cake images\ccake.png"><p>0.5 Kg Chocolate Truffle Cake</p><p class="rupee">&nbsp;&#8377;500<br></p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="Cake images\choco cake.png"><p>Chocolate Dropping Cake 500 Gm</p><p class="rupee">&nbsp;&#8377;699<br></p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="Cake images\choco gems cake.png"><p>Chocolate Gems Cream Cake</p><p class="rupee">&nbsp;&#8377;599<br></p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="Cake images\chocolate cake .png"><p>Kitkat Gems Designer Cakes</p><p class="rupee">&nbsp;&#8377;800<br></p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="Cake images\heart shaped.png"><p>0.5 Kg Heart Shaped Chocolate Cream Cake</p><p class="rupee">&nbsp;&#8377;600<br></p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="Cake images\truffle cake.png"><p>Round Choco 500Gm</p><p class="rupee">&nbsp;&#8377;1000<br></p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="Cake images\choco truffle.png"><p>Chocolate Sprinkle Cake 1 Kg</p><p class="rupee">&nbsp;&#8377;700<br></p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="Cake images\cup cake.png"><p>Set Of 4 Chocolate Gems Cupcakes</p><p class="rupee">&nbsp;&#8377;900<br></p><div class="add">Add to Cart</div></div>
    
    
        </div>
    </section>
    
    <section id="Butterscotch">
        <div class="pic">
        <img class="big" src="Cake images\big butterscotch.png"><p>Butterscotch Cakes</p></div>
        <div class="card-content">
            <div class="item2"><img src="Cake images\Butterscotch cream cake.png"><p> Butterscotch Cream Cake</p><p class="rupee">&nbsp;&#8377;1034<br></p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="Cake images\Butterscotch cream.png"><p>Walnut With Butterscotch Cake 500 Gm</p><p class="rupee">&nbsp;&#8377;1200<br></p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="Cake images\butterscotch.png"><p>0.5 Kg Butterscotch Cream Cake</p><p class="rupee">&nbsp;&#8377;900<br></p><div class="add">Add to Cart</div></div>
            </div>
    
    </section>
    
    <section id ="Red velvet">
        <div class="pic">
            <img class="big" src="Cake images\Red velvet big.png"><p>Red Velvet Cakes</p>
                </div>
                <div class="card-content">
                    <div class="item2"><img src="Cake images\red velvet cream.png"><p>Red Velvet Heart Cake </p><p class="rupee">&nbsp;&#8377;899<br></p><div class="add">Add to Cart</div></div>
                    <div class="item2"><img src="Cake images\red velvet fruits.png"><p>Red Velvet Cream Fruit Cake</p><p class="rupee">&nbsp;&#8377;1230<br></p><div class="add">Add to Cart</div></div>
                    <div class="item2"><img src="Cake images\red velvets.png"><p>0.5 Kg Red Velvet Cream Cake</p><p class="rupee">&nbsp;&#8377;1168<br></p><div class="add">Add to Cart</div></div>
                    <div class="item2"><img src="Cake images\red verlvet cake.png"><p>Red Velvet With Fresh Fruits Cream Cake</p><p class="rupee">&nbsp;&#8377;999<br></p><div class="add">Add to Cart</div></div>
                    
    
    
                </div>
    </section>
    
    <section id="Black Forest">
        <div class="pic">
            <img src ="Cake images\black forest big.png" class="big"><p>Black Forest Cakes</p>
        </div>
        <div class="card-content">
            <div class="item2"><img src="Cake images\black forestt.png"><p>Black Forest Heaven</p><p class="rupee">&nbsp;&#8377;959</p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="Cake images\black.png"><p>Black Forest Onway 500 Gm</p><p class="rupee">&nbsp;&#8377;1249</p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="Cake images\black forest.png"><p>Gems Black Forest</p><p class="rupee">&nbsp;&#8377;969</p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="Cake images\red cherry.png"><p>Red N Yellow Cream Black Forest</p><p class="rupee">&nbsp;&#8377;1550</p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="Cake images\forest black.png"><p>Black Forest Fruit And Oreo Cake</p><p class="rupee">&nbsp;&#8377;999</p><div class="add">Add to Cart</div></div>
        
            
            
    
    
        </div>
    </section>
    
    <section id ="Pineapple">
        <div class="pic">
            <img src = "Cake images\pineaplle cake big.png" class="big"><p>Pineapple cakes</p>
        </div>
        <div  class="card-content">
            
            <div class="item2"><img src ="Cake images\p cake.png"><p>0.5 Kg Pineapple Cream Cake</p><p class="rupee">&nbsp;&#8377;959</p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src ="Cake images\pine cake.png"><p>Pineapple Cake with Crunch</p><p class="rupee">&nbsp;&#8377;839</p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src ="Cake images\pineapple cherry.png"><p>0.5 Kg Pineapple Cream Cake</p><p class="rupee">&nbsp;&#8377;679</p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src ="Cake images\designer.png"><p>Little Princes Pineapple Shape Cake</p><p class="rupee">&nbsp;&#8377;1219</p><div class="add">Add to Cart</div></div>
            
    
    
        </div>
       </section>
    
    <section id="card">
        <div class="pic">
            <img class="big" src="cards.jpg"><p>Greeting Cards</p>
        </div>
        </div>
        <div class ="card-content">
            <div class="item"><a onclick="showPage('birthday')"><img src="C:\Users\DELL\Documents\html project\birthday.jpg"></a><a onclick="showPage('birthday')"><p class="m">Birthday Card</p></a></div>
            <div class="item"><a onclick ="showPage('holi')"><img src="C:\Users\DELL\Documents\html project\holi.jpg"><p class="m">Holi Card</p></a></div>
            <div class="item"><a onclick="showPage('chris')"><img src="C:\Users\DELL\Documents\html project\chistmas.jpg"><p class="m">Christmas Card</p></a></div>
            <div class="item"><a onclick="showPage('diwali')"><img src="C:\Users\DELL\Documents\html project\diwali.jpg"><p class="m">Diwali</p></a></div>
            
        </div>
    </section>
    <section id="perso">
        <div class="pic">
            <img class="big" src="personal.jpg"><p>Personal Card</p>
        </div>
        <div class="card-content">
            <div class="item"><a onclick="showPage('personal')"><img src="personalcard.jpg"><p class="m">Personalized Cards</p></a></div>
            <div class="item"><a onclick="showPage('mug')"><img src="mug.jpg"><p class="m">Personalized Mug</p></a></div>
            <div class="item"><a onclick="showPage('frame')"><img src="frame.jpg"><p class="m">Personalized Photo Frame</p></a></div>
            
        </div>
    </section>
    <section id="personal">
        <div class="pic">
            <img class="big" src="persobig.jpg"><p>Personal Card</p>
        </div>
        <div class="card-content">
            <div class="item2"><img src="perso11.jpg"><p class="con">Special Wishes For You On Christmas Personalised Card</p><p class="rupee">&nbsp;&#8377;375</p><a onclick="showPage('viewdetails')"><div class="add">View Details</div></a></div>
            <div class="item2"><img src="perso12.jpg"><p class="con">Merry Christmas With Best Wishes and Love Personalised Card</p><p class="rupee">&nbsp;&#8377;375</p><a onclick="showPage('viewdetails')"><div class="add">View Details</div></a></div>
            <div class="item2"><img src="perso13.jpg"><p class="con">It Is Christmastime Personalised Card for your loved ones</p><p class="rupee">&nbsp;&#8377;375</p><a onclick="showPage('viewdetails')"><div class="add">View Details</div></a></div>
            <div class="item2"><img src="perso14.jpg"><p class="con">Warm Wishes At Christmas Personalised Card for your friends</p><p class="rupee">&nbsp;&#8377;375</p><a onclick="showPage('viewdetails')"><div class="add">View Details</div></a></div>
            <div class="item2"><img src="perso21.jpg"><p class="con">Merry Christmas Personalised Card &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;375</p><div class="add">View Details</div></div>
            <div class="item2"><img src="perso22.jpg"><p class="con">Beautiful Moments and Sweet Memories Womans Day Greeting Card</p><p class="rupee">&nbsp;&#8377;375</p><a onclick="showPage('viewdetails')"><div class="add">View Details</div></a></div>
            <div class="item2"><img src="perso23.jpg"><p class="con">Celebrate The Beautiful Brother-Sister Bond With Personalised Rakhi Card</p><p class="rupee">&nbsp;&#8377;375</p><div class="add">View Details</div></div>
            <div class="item2"><img src="perso24.jpg"><p class="con">Holi Hai Multicolor Greeting Card&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;375</p><div class="add">View Details</div></div>

        </div>
    </section>


    <section id="mug">
        <div class="pic">
            <img class="big" src="mugbig.jpg"><p>Personal Card</p>
        </div>
        <div class="card-content">
            <div class="item2"><img src="mug11.jpg"><p class= "con">Black Elegant Personalized Coffee Mug</p><p class="rupee">&nbsp;&#8377;975</p><a onclick="showPage('viewdetails')"><div class="add">View Details</div></a></div>
            <div class="item2"><img src="mug12.jpg"><p class= "con">Hello Sweetheart Personalized Coffee Mug</p><p class="rupee">&nbsp;&#8377;1375</p><a onclick="showPage('viewdetails')"><div class="add">View Details</div></a></div>
            <div class="item2"><img src="mug13.jpg"><p class= "con">All Yours Personalized Coffee Mug</p><p class="rupee">&nbsp;&#8377;575</p><a onclick="showPage('viewdetails')"><div class="add">View Details</div></a></div>
            <div class="item2"><img src="mug14.jpg"><p class= "con">Personalised Mug For An Enthusiastic Holi</p><p class="rupee">&nbsp;&#8377;675</p><a onclick="showPage('viewdetails')"><div class="add">View Details</div></a></div>
            <div class="item2"><img src="mug21.jpg"><p class= "con">Happy Rakshabandhan Personalized White Mug</p><p class="rupee">&nbsp;&#8377;475</p><a onclick="showPage('viewdetails')"><div class="add">View Details</div></a></div>
            <div class="item2"><img src="mug22.jpg"><p class= "con">Quirky Personalized Ceramic Coffee Mug</p><p class="rupee">&nbsp;&#8377;1075</p><a onclick="showPage('viewdetails')"><div class="add">View Details</div></a></div>
            <div class="item2"><img src="mug23.jpg"><p class= "con">Personalized Coffee Mug With Romantic Text</p><p class="rupee">&nbsp;&#8377;975</p><a onclick="showPage('viewdetails')"><div class="add">View Details</div></a></div>
            <div class="item2"><img src="mug24.jpg"><p class= "con">Bee Mine Personalized Coffee Mug</p><p class="rupee">&nbsp;&#8377;775</p><div class="add">View Details</div></div>

        </div>
    </section>

    <section id="frame">
        <div class="pic">
            <img class="big" src="framebig.jpg"><p>Personal Card</p>
        </div>
        <div class="card-content">
            <div class="item2"><img src="frame11.jpg"><p class="con">White and Brown Dog Personalised Photoframe</p><p class="rupee">&nbsp;&#8377;375</p><a onclick="showPage('viewdetails')"><div class="add">View Details</div></a></div>
            <div class="item2"><img src="frame12.jpg"><p class="con">Best Friends Personalised Photoframe</p><p class="rupee">&nbsp;&#8377;375</p><a onclick="showPage('viewdetails')"><div class="add">View Details</div></a></div>
            <div class="item2"><img src="frame13.jpg"><p class="con">The Gangster Teddy Bear Personalised Photoframe</p><p class="rupee">&nbsp;&#8377;375</p><a onclick="showPage('viewdetails')"><div class="add">View Details</div></a></div>
            <div class="item2"><img src="frame14.jpg"><p class="con">Love me everyday Personalised Photoframe</p><p class="rupee">&nbsp;&#8377;375</p><a onclick="showPage('viewdetails')"><div class="add">View Details</div></a></div>
            <div class="item2"><img src="frame21.jpg"><p class="con">Colorful Parrot Personalised Photoframe</p><p class="rupee">&nbsp;&#8377;375</p><a onclick="showPage('viewdetails')"><div class="add">View Details</div></a></div>
            <div class="item2"><img src="frame22.jpg"><p class="con">White Cycling Rabbit Personalised Photoframe</p><p class="rupee">&nbsp;&#8377;375</p><a onclick="showPage('viewdetails')"><div class="add">View Details</div></a></div>
            <div class="item2"><img src="frame23.jpg"><p class="con">Rose and Dog Personalised Photoframe</p><p class="rupee">&nbsp;&#8377;375</p><a onclick="showPage('viewdetails')"><div class="add">View Details</div></a></div>
            <div class="item2"><img src="frame24.jpg"><p class="con">White Rabbit With Flowers Personalised Photoframe</p><p class="rupee">&nbsp;&#8377;375</p><a onclick="showPage('viewdetails')"><div class="add">View Details</div></a></div>

        </div>

    </section>


    
    <section id="holi">
        <div class="pic">
            <img class="big" src="C:\Users\DELL\Documents\html project\holibig.jpg"><p>Holi Cards</p>
        </div>
        <div class="card-content">
            <div class="item2"><img src="holi11.jpg"><p>Multicolor Happy Holi Card with The Delish Co - Bites Mini Chocolate Bar</p><p class="rupee">&nbsp;&#8377;375</p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="holi12.jpg"><p>Magnificent Design Happy Holi Card with Delish Lovly Chocolate Box</p><p class="rupee">&nbsp;&#8377;375</p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="holi13.jpg"><p>Purple Beautiful Design Happy Holi Card with The Delish Mini Chocolate Bar</p><p class="rupee">&nbsp;&#8377;395</p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="holi14.jpg"><p>Magnificent Design Happy Holi Card with The Delish Mini Chocolate Bar</p><p class="rupee">&nbsp;&#8377;395</p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="holi21.jpg"><p>Colour Your Life With The Joys of Holi Card with The Delish Mini Chocolate Bar</p><p class="rupee">&nbsp;&#8377;395</p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="holi22.jpg"><p>Magnificent Design Happy Holi Card with Ferrero Rocher 24pc </p><p class="rupee">&nbsp;&#8377;395</p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="holi23.jpg"><p>Attractive Design Happy Holi Card with Ferrero Rocher T4 Chocolate</p><p class="rupee">&nbsp;&#8377;395</p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="holi24.jpg"><p>Attractive Design Happy Holi Card with Ferrero Rocher 24</p><p class="rupee">&nbsp;&#8377;395</p><div class="add">Add to Cart</div></div>


        </div>
    </section>
    <section id="birthday">
        <div class="pic">
        <img class="big" src="C:\Users\DELL\Documents\html project\bidbirthday.jpg"><p>Birthday Card</p></div>
        <div class="card-content">
            <div class="item2"><img src="birthday11.jpg"><p>Its Your Day Today Happy Birthday Greeting Card&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;395</p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="birthday12.jpg"><p>Chocolate Muffin Design Birthday Greeting Card&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;395</p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="birth13.jpg"><p>Blue Flowers And Butterflies Birthday Greeting Card&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;895</p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="bith14.jpg"><p>Orange Birthday Cake Design Greeting Card&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;395</p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="bithday21.jpg"><p>Purple Flower Design Birthday Greeting Card&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;1395</p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="birthday22.jpg"><p>Pink Birthday Greeting Hanging Card&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;795</p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="birthday23.jpg"><p>Green Birthday Greeting Hanging Card&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;695</p><div class="add">Add to Cart</div></div>
        </div>

    </section>
    <section id ="diwali">
        <div class="pic">
            <img class="big" src="C:\Users\DELL\Documents\html project\diwalibig.jpg"><p>Diwali</p>
                </div>
                <div class="card-content">
                    <div class="item2"><img src="C:\Users\DELL\Documents\html project\diwali11.jpg"><p>The Amazing Gift Set Combo&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;599<br></p><div class="add">Add to Cart</div></div>
                    <div class="item2"><img src="C:\Users\DELL\Documents\html project\diwali12.jpg"><p>The Best Design Gift Set Combo&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;599<br></p><div class="add">Add to Cart</div></div>
                    <div class="item2"><img src="C:\Users\DELL\Documents\html project\diwali13.jpg"><p>The Elephant Design Gift Set Combo&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<p class="rupee">&nbsp;&#8377;599<br></p><div class="add">Add to Cart</div></div>
                    <div class="item2"><img src="C:\Users\DELL\Documents\html project\diwali14.jpg"><p>The Amazing Design Gift Set Combo&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<p class="rupee">&nbsp;&#8377;599<br></p><div class="add">Add to Cart</div></div>
                    <div class="item2"><img src="C:\Users\DELL\Documents\html project\diwali21.jpg"><p>Archies Glittering Diyas Diwali Blank Seasons Greetings Card Pack Of 50</p><p class="rupee">&nbsp;&#8377;3750<br></p><div class="add">Add to Cart</div></div>
                    <div class="item2"><img src="C:\Users\DELL\Documents\html project\diwali22.jpg"><p>Archies Grey And Golden Diwali Seasons Greetings Card Pack Of 10</p><p class="rupee">&nbsp;&#8377;600<br></p><div class="add">Add to Cart</div></div>
                    <div class="item2"><img src="C:\Users\DELL\Documents\html project\diwali23.jpg"><p>Wishing You Much Happiness Diwali Cards With Envelope Pack Of 6</p><p class="rupee">&nbsp;&#8377;420<br></p><div class="add">Add to Cart</div></div>
                    <div class="item2"><img src="diwali24.jpg"><p>Special Wishes On Diwali Cards With Envelope Pack Of 6</p><p class="rupee">&nbsp;&#8377;420<br></p><div class="add">Add to Cart</div></div>


  
                </div>
    </section>
    
    <section id="chris">
        <div class="pic">
            <img src ="C:\Users\DELL\Documents\html project\chrisbig.jpg" class="big"><p>Christmas Cards</p>
        </div>
        <div class="card-content">
            <div class="item2"><img src="chris11.jpg"><p>Archies White And Green Christmas Seasons Greetings Card Pack Of 10</p><p class="rupee">&nbsp;&#8377;600</p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="chris12.jpg"><p>Archies White And Green Christmas Blank Seasons Greetings Card Pack Of 50</p><p class="rupee">&nbsp;&#8377;3000</p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="chris13.jpg"><p>Archies Shiny Christmas Tree Blank Seasons Greetings Card Pack Of 50</p><p class="rupee">&nbsp;&#8377;2500</p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="chris14.jpg"><p>Archies Marry Christmas and New Year Wish Seasons Greeting Card Pack Of 10</p><p class="rupee">&nbsp;&#8377;550</p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="chris21.jpg"><p>Attractive Merry Christmas Image Card(Pack of 1 Card)</p><p class="rupee">&nbsp;&#8377;70</p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="chris22.jpg"><p>Silver Reindeer Christmas Season's Greeting Card ( Pack of 50 )</p><p>&nbsp;&#8377;2000</p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="chris23.jpg"><p>Snow Man Season's Christmas Greeting Card ( Pack of 50 )</p><p>&nbsp;&#8377;2750</p><div class="add">Add to Cart</div></div>
            <div class="item2"><img src="chris24.jpg"><p>Merry Christmas and Happy New Year Multicolor Greeting Card ( Pack of 50 )</p><p>&nbsp;&#8377;3000</p><div class="add">Add to Cart</div></div>
            


        </div>
    </section>



    </div>
   </section>

   <section id="flowers">
    <div class="pic">
        <img class="big" src="flowers.jpg"><p>Flowers</p>
    </div>
    <div class ="card-content">
        <div class="item"><a onclick="showPage('pink')"><img src="https://archiesonline.com/uploads/category/category_62b6c49bb36c50-63765667-73565901.jpg"></a><p class="m">Pink Flowers</p></div>
        <div class="item"><a onclick ="showPage('red')"><img src="https://archiesonline.com/uploads/category/category_62b6c6442d1595-04649890-94379361.jpg"></a><p class="m">Red Flowers</p></div>
        <div class="item"><a onclick="showPage('white')"><img src="whiteflowers.jpg"></a><p class="m">White Flowers</p></div>
        <div class="item"><a onclick="showPage('yellow')"><img src="yellowflowers.jpg"></a><p class="m">Yellow Flowers</p></div>
        <div class="item"><a onclick="showPage('exotic')"><img src="exoticflowers.jpg"></a><p class="m">Exotic Flowers</p></div>
        
    </div>
</section>
<section id="pink">
    <div class="pic">
        <img class="big" src="pinkflowers.jpg"><p>Pink Flowers</p>
    </div>
    <div class="card-content">
        <div class="item2"><img src="pinkflr1.jpg"><p>40 Pink Roses Bouquet&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;3589<br></p><div class="add">Add to Cart</div></div>
        <div class="item2"><img src="pinkflr2.jpg"><p>8 Pink Roses Bouquet&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;899<br></p><div class="add">Add to Cart</div></div>
        <div class="item2"><img src="pinkflr3.jpg"><p>Pink Gerbera Bouquet&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;989<br></p><div class="add">Add to Cart</div></div>
        <div class="item2"><img src="pinkflr4.jpg"><p>100 Red And Pink Rose Bouquet&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;6900<br></p><div class="add">Add to Cart</div></div>
        <div class="item2"><img src="pinkflr5.jpg"><p>White Gerbera and Pink Roses Glass Vase&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;2159<br></p><div class="add">Add to Cart</div></div>
        <div class="item2"><img src="pinkflr6.jpg"><p>Jute Bouquet of 10 Pink Roses&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;1049<br></p><div class="add">Add to Cart</div></div>
        <div class="item2"><img src="pinkflr7.jpg"><p>25 Pink Gerbera One Side Bouquet&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;1599<br></p><div class="add">Add to Cart</div></div>
        <div class="item2"><img src="pinkflr8.jpg"><p>30 Premium Pink Roses Bouquet&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;3549<br></p><div class="add">Add to Cart</div></div>


    </div>
</section>
<section id="red">
    <div class="pic">
    <img class="big" src="redflowers.jpg"><p>Red Flowers</p></div>
    <div class="card-content">
        <div class="item2"><img src="redflr1.jpg"><p>12 Pink Carnations Bouquet&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;1164<br></p><div class="add">Add to Cart</div></div>
        <div class="item2"><img src="redflr2.jpg"><p>Rose Ferrero Roche And Cake Hamper 500Gm&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;4599<br></p><div class="add">Add to Cart</div></div>
        <div class="item2"><img src="redflr3.jpg"><p>40 Red Roses with Bow&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;2639<br></p><div class="add">Add to Cart</div></div>
        <div class="item2"><img src="redflr4.jpg"><p> Bouquet Of 6 Red Roses And 16 Ferrero Rocher Chocolates&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;2650<br></p><div class="add">Add to Cart</div></div>
        <div class="item2"><img src="redflr5.jpg"><p>20 Red Roses With A Basket&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;2500<br></p><div class="add">Add to Cart</div></div>
        <div class="item2"><img src="redflr6.jpg"><p>20 Red Roses and 3 Asiatic Pink Lilies- 500 gm Heart Shape Chocolate Cake<p class="rupee">&nbsp;&#8377;3579<br></p><div class="add">Add to Cart</div></div>
        <div class="item2"><img src="redflr7.jpg"><p>12 Red Roses with Butterscotch Cake 500 gm&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;2159<br></p><div class="add">Add to Cart</div></div>
    </div>

</section>
<section id ="white">
    <div class="pic">
        <img class="big" src="whiteflowers.jpg"><p>White Flowers</p>
            </div>
            <div class="card-content">
                <div class="item2"><img src="whiteflr1.jpg"><p>6 White Orchids Bouquet&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;1599<br></p><div class="add">Add to Cart</div></div>
                <div class="item2"><img src="whiteflr2.jpg"><p>12 Red and White Roses- Cadbury's Celebrations (131.3 gms)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;1230<br></p><div class="add">Add to Cart</div></div>
                <div class="item2"><img src="whiteflr3.jpg"><p>12 Roses (Red and Pink) Bouquet&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;1468<br></p><div class="add">Add to Cart</div></div>
                <div class="item2"><img src="whiteflr4.jpg"><p>Premium Quality Bridal Bouquet&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;5499<br></p><div class="add">Add to Cart</div></div>
                


            </div>
</section>

<section id="yellow">
    <div class="pic">
        <img src ="yellowflowers.jpg" class="big"><p>Yellow Flowers</p>
    </div>
    <div class="card-content">
        <div class="item2"><img src="yellowflr1.jpg"><p>Yellow Gerbera Bouquet&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;959</p><div class="add">Add to Cart</div></div>
        <div class="item2"><img src="yellowflr2.jpg"><p>12 Yellow Roses Bouquet&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;1249</p><div class="add">Add to Cart</div></div>
        <div class="item2"><img src="yellowflr3.jpg"><p>Yellow and White Roses with White Paper Wrapped Bouquet&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;969</p><div class="add">Add to Cart</div></div>
        <div class="item2"><img src="yellowflr4.jpg"><p>Glass Vase Arrangement of 18 Mixed Roses (Red,Light Pink,Yellow,Orange)</p><p class="rupee">&nbsp;&#8377;1550</p><div class="add">Add to Cart</div></div>
        <div class="item2"><img src="yellowflr5.jpg"><p>100 Yellow Roses Bouquet Premium&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;9989</p><div class="add">Add to Cart</div></div>
        <div class="item2"><img src="yellowflr6.jpg"><p>5 Yellow Asiatic Lilies- 8 Red Roses- 8 Pink Carnations- Pink and Yellow Paper (Half Kg)</p><p>&nbsp;&#8377;3899</p><div class="add">Add to Cart</div></div>
        
        


    </div>
</section>

<section id ="exotic">
<div class="pic">
    <img src = "exoticflr.jpg" class="big"><p>Exotic Flowers</p>
</div>
<div  class="card-content">
    <div class="item2"><img src ="exoflr1.jpg"><p>10 Red Roses with Minimal White Flowers&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;959</p><div class="add">Add to Cart</div></div>
    <div class="item2"><img src ="exoflr2.jpg"><p>Red Roses with Brown Paper wrapping&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;4959</p><div class="add">Add to Cart</div></div>
    <div class="item2"><img src ="exoflr3.jpg"><p>Red Roses with Paper wrapping and Orchid decorated&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;6839</p><div class="add">Add to Cart</div></div>
    <div class="item2"><img src ="exoflr4.jpg"><p>40 Pink Roses Bouquet&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;3679</p><div class="add">Add to Cart</div></div>
    <div class="item2"><img src ="exoflr5.jpg"><p>Pink Roses with Paper wrapping&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;2219</p><div class="add">Add to Cart</div></div>
    <div class="item2"><img src ="exoflr6.jpg"><p>Yellow Roses Basket Arrangement&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;1439</p><div class="add">Add to Cart</div></div>
    <div class="item2"><img src ="exoflr7.jpg"><p>6 White Orchids Bouquet&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;1469</p><div class="add">Add to Cart</div></div>
    <div class="item2"><img src ="exoflr8.jpg"><p>40 Mixed Flowers Bouquet&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;4779</p><div class="add">Add to Cart</div></div>
    <div class="item2"><img src ="exoflr9.jpg"><p>25 Mixed Flowers Basket Arrangement&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p><p class="rupee">&nbsp;&#8377;2159</p><div class="add">Add to Cart</div></div>

</div>



</section>
<section id ="viewdetails">
    <div class="textto">
        <div class="view">
        <form action="/form/submit" method="post">
        <textarea  name="textarea" id ="addto"  rows="16" cols ="85" placeholder="ADD YOUR SPECIFICTION"></textarea>
        <br>
      <input type="submit"  name="submitInfo" value="Submit">
      </form>
    </div>
    <br>
      <br>
      <br>
      <div class="view">
        <form action="/form/submit" method="post">
        <textarea  name="textarea" id="addto" rows="16" cols ="85">ADD YOUR YOUR IMAGE </textarea>
        <br>
      <input type="submit" name="submitInfo" value="Submit">
    </form>
    </div>
   

    </div>
</section>
 
 
    


    <script>
        function showForgotPassword() {
            alert("Forgot Password functionality will be implemented separately.");
             }
        
    
        function showPage(pageId) {
            
            const sections = document.querySelectorAll('section');
            sections.forEach(section => {
                section.style.display = 'none';
            });
    
           
            const selectedSection = document.getElementById(pageId);
            if (selectedSection) {


                selectedSection.style.display = 'block';
            }
        }
        function myFunction(divClass) {
      alert("Item Added to Cart");
        }
    
        showPage('home');
    </script>
    
    
</body>
</html>

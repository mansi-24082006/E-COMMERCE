

<!DOCTYPE html>

<html lang="en">

<head>



    <title>shop website</title>

    <style>

        .home {

            width: 100%;

            height: 1100px;

            border: 5px solid rgb(109, 83, 0);

            box-shadow: 2px 3px 100px rgb(236, 155, 3);

            border-radius: 20px;

            margin-top: 20px;

            margin-bottom: 100px;

            background: linear-gradient(to right, #f3a068, #adacaa);

            text-align: center;

        }

        .home img{

            width: 90%;

            height: 800px;

            margin-left: 10px;

            margin-bottom: 20px;



        }

        ul {

            list-style-type: none;

            margin: 0;

            padding: 0;

            overflow: hidden;

        }

        

        li {

            float: left;

        }

        

        .nav {

            position: sticky;

            top: 0;

            left: 0;

            margin-top: 20px;

        }

        

        li a {

            display: inline-block;

            color: black;

            text-align: center;

            padding: 15px 16px;

            text-decoration: none;

            text-transform: uppercase;

            text-shadow: 1px 1px 1px black;

            font-family: serif;

        }

        

        .box {

            display: flex;

            

        

        }

        

        .box1 {

            display: relative;

            border: 2px solid black;

            border-radius: 20px;

            box-shadow: 2px 2px 10px rgb(97, 165, 204);

            width: 500px;

            height: 600px;

            background-repeat: no-repeat;

            margin-left: 100px;

            margin-top: 10px;

            border: 2px solid rgb(79, 79, 175);

            

        

        }

        

        .box1 footer {

            font-size: 25px;

            margin-top: 50px;

            margin-left: 10px;

            font-size: 20px;

        }

        

        .box1 button {

            display: flex;

            background-color: rgb(139, 134, 134);

            margin-top: 20px;

            margin-left: 190px;

            width: 120px;

            height: 20px;

            justify-content: center;

        }

        

        .box1 img {

            margin-top: 15px;

            margin-left: 10px;

            object-fit: fill;

            width: 450px;

            height: 400px;

        }

        

        .box2 {

            width: 400px;

            height: 500px;

            background-repeat: no-repeat;

            border: 2px solid black;

            border-radius: 20px;

            box-shadow: 2px 2px 10px rgb(78, 76, 76);

            margin-right: 200px;

        }

        

        .watches {

            width: 100%;

            height: 700px;

            border: 2px solid black;

            border-radius: 30px 70px;

            margin-top: 200px;

            margin-bottom: 100px;

            box-shadow: 2px 3px 100px rgb(24, 4, 201);

            

        }

        

        .eyewear {

            width: 100%;

            height: 750px;

            border: 2px solid black;

            border-radius: 30px 70px;

            margin-top: -50px;

            margin-bottom: 100px;

            box-shadow: 2px 3px 100px rgb(243, 4, 4);

             }

        

        .Box {

            display: flex;

        }

        

        .Box1 {

            display: relative;

            border: 2px solid black;

            border-radius: 20px;

            box-shadow: 2px 2px 20px rgb(255, 5, 5);

            width: 500px;

            height: 650px;

            background-repeat: no-repeat;

            margin-left: 150px;

            margin-top: 50px;

            border: 2px solid rgb(48, 48, 53);

        }

        

        

        

        .Box1 footer {

            font-size: 15px;

            margin-top: 50px;

            margin-left: 10px;

            font-size: 20px;

        }



        .Box button {

            display: flex;

            background-color: rgb(139, 134, 134);

            margin-top: 20px;

            margin-left: 190px;

            width: 120px;

            height: 20px;

            justify-content: center;

        }

        

        .Box1 img {

            margin-top: 15px;

            margin-left: 10px;

            object-fit: fill;

            width: 400px;

            height: 450px;

        }

        .Hat{

            display: flex;

        

        }



        .Hats1{

            display: relative;

            border: 2px solid black;

            border-radius: 20px;

            box-shadow: 2px 2px 10px rgb(180, 9, 214);

            width: 500px;

            height: 650px;

            background-repeat: no-repeat;

            margin-left: 150px;

            margin-top: 70px;

            border: 2px solid rgb(48, 48, 53);

        }

        .Hats1 footer{

            font-size: 30px;

            margin-top: 50px;

            margin-left: 10px;

            font-size: 20px;

        }

        .Hats1 button{

            display: flex;

            background-color: rgb(139, 134, 134);

            margin-top: 30px;

            margin-left: 180px;

            width: 120px;

            height: 20px;

            justify-content: center;

        }

        .Hats1 img{

            margin-top: 15px;

            margin-left:20px;

            object-fit: fill;

            width: 450px;

            height: 460px;

        }

        .Brands {

            width: 100%;

            height: 500px;

            border: 2px solid rgb(3, 3, 3);

            border-radius: 30px 70px;

            margin-top: -50px;

            margin-bottom: 150px;

            box-shadow: 2px 3px 100px rgb(148, 238, 3);

        }

        .Hats{

            width: 100%;

            height: 800px;

            border: 2px solid black;

            border-radius: 30px 70px;

            margin-top: -30px;

            margin-bottom: 100px;

            box-shadow: 2px 3px 100px rgb(238, 3, 226);

        }

        .text h1{

            display: flex;

            justify-content:space-around;

            align-items: center;

            text-align: center;

            font-size: 50px;

            margin-top: -30px;;

            font-family: monospace;

            font-weight: bold;

        }

        .text p{

            font-size: 20px;

            font-family:fantasy

        }

        .footer a {

    font-size: 14px;

    color:rgb(241, 227, 227);

    

    text-decoration: none;

    cursor: pointer;

}



.footer-item {

    display: flex;

    flex-direction: column;

    gap: 20px;

    position: relative;

    justify-content: center;

    

}

        .footer {

    background-color: #333230;

    color: rgb(122, 166, 196);

    width: 70%;

    margin: auto;

    padding: 100px;

    display: flex;

    justify-content: space-evenly;

   flex-wrap:no-wrap;

}

    </style>

</head>



<body>

    <div class="main">

        <div class="home">

            

            <div class="nav">

                <ul>

                    <li>

                        <a href="#">home</a>

                        <a href="#">watches</a>

                        <a href="#">eyewear</a>



                        <a href="#">Hats</a>

                        <a href="#">Brands</a>

                       

                        

                    </li>

                </ul>

                <div class="text">

                    <h1>Online shopping</h1>

                    <p>Everything 50% discount</p>

                </div>

            

            <img src="https://img.freepik.com/premium-photo/online-fashion-shopping-with-computer_23-2150400628.jpg" alt="">

           

            </div>

        <div class="watches">



            <div class="box">



                <div class=" box1">w

                    <img src="https://5.imimg.com/data5/AY/XB/RW/SELLER-104356294/2-removebg-preview.png" alt="">

                    <footer>Mens Watches</footer>

                    <button>shop now</button>

                </div>

                <div class=" box1">

                    <img src="https://mansi-24082006.github.io/watch/Watch.jpg" alt="">

                    <footer>Womens watches</footer>

                    <button>shop now</button>

                </div>

            </div>

        </div>

        <div class="eyewear">

            <div class="Box">

                <div class=" Box1">

                    <img src="https://s.yimg.com/lo/api/res/1.2/h34xT0bX41fcLRiGkOJ_FQ--/YXBwaWQ9ZWNfaG9yaXpvbnRhbDtoPTQwMDtzcz0xO3c9NDAw/https://m.media-amazon.com/images/I/41aCXv626ML._SL500_.jpg" width="400px" height="400px" alt="">

                    <footer> Mens eyewears</footer>

                    <button>shop now</button>

                </div>

                <div class=" Box1">

                    <img src="https://i.ebayimg.com/images/g/C0gAAOSwSkllW8fA/s-l400.jpg" width="400px" height="400px" alt="">

                    <footer>Womens eyewears </footer>

                    <button>shop now</button>

                </div>

            </div>

        </div>



        <div class="Hats">

            <div class="Hat">

                <div class=" Hats1">

                    <img src="https://images-cdn.ubuy.co.in/6583b36ae0c88513cd5bcf6f-meinicy-3-pack-washed-plain-baseball.jpg"alt="">

                    <footer> Mens Hats</footer>

                    <button>shop now</button>

                </div>

                <div class=" Hats1">

                    <img class="girls "src="https://www.miabellebaby.com/cdn/shop/products/girls-pearl-and-bow-embellished-straw-hat-19-99-under-beach-beige-dropified-dropshipping-hats-mia-belle-overseas-fulfillment-baby_872_1024x1024.jpg?v=1645560963" alt="">

                    <footer>Womens Hats</footer>

                    <button>shop now</button>

                </div>

            </div>

        </div>

        



        

        <div class="footer">

            <div class="footer-item"> 

                <h1>SHOP</h1>

                <a href="faq">watches</a>

                <a href="faq">Eyewear</a>

                <a href="faq">Hats</a>

                

                </div>



            

            <div class="footer-item">

                <h2>ABOUT</h2>

                <a href="faq">Our story</a>

                <a href="faq">wholesale </a>

                <a href="faq">press</a> 

                <a href="faq">careers</a>

            </div>

           



            <div class="footer-item">

                <h3>HELP</h3>

                <a href="faq">FAqs</a>

                <a href="faq">contact us</a> 

                <a href="faq">Terms</a> 

                <a href="faq">Privacy</a>

            </div>



          </div>

    </div>-









</body>



</html>

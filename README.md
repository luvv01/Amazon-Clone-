# Amazon-Clone-
I created the little bit similar amazon clone home page using HTML &amp; CSS
{HTML}
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Amazon.clone</title>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css"
      integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <header>
      <div class="navbar">
        <div class="nav-logo">
          <div class="logo"></div>
        </div>

        <div class="nav-address">
          <p class="add-first">deliverd to</p>
          <div class="add-icon">
            <i class="fa-solid fa-location-dot"></i>
            <p class="add-sec">India</p>
          </div>
        </div>
        <!-- 3rd box -->
        <div class="nav-search">
          <select class="search-select">
            <option>All</option>
          </select>
          <input placeholder="Search Amazon" class="search-input" />
          <div class="search-icon">
            <i class="fa-solid fa-magnifying-glass"></i>
          </div>
        </div>
        <!-- box 4 -->
        <div class="fourthbox">
          <p><span class="sign-in">Hello,sign in</span></p>
          <p class="nav-sec">
            Account & List <i class="fa-solid fa-caret-down"></i>
          </p>
        </div>

        <!-- box 5 -->
        <div class="fifthbox">
          <p><span class="Return">Return</span></p>
          <p class="Orders">&Orders</p>
        </div>

        <!-- box 6 -->
        <div class="cart">
          <i class="fa-solid fa-cart-shopping"></i>
          <span>cart</span>
        </div>
      </div>

      <!-- panel -->
      <div class="panel">
        <div class="panel-all">
          <i class="fa-solid fa-bars"></i>
          All
        </div>

        <div class="panel-options">
          <p>Today's Deals</p>
          <p>Customer Service</p>
          <p>Registry</p>
          <p>Gift Cards</p>
          <p>Sell</p>
        </div>
        <div class="panel-deal">Shop deals in Electronics</div>
      </div>
    </header>
    <!-- hero section -->
    <div class="hero-section">
      <div class="hero-msg">
        <p>
          You are on amazon.com. You can also shop on Amazon India for millions
          of products with fast local delivery.
          <a>Click here to go to amazon.in</a>
        </p>
      </div>
    </div>

    <!-- shop-section -->
    <div class="shop-section">
      <div class="box">
        <div class="box1-content">
          <h2>Deals in PCs</h2>
          <div class="pc-img" style="background-image: url('pc.jpg')"></div>
          <b><p>Shop know</p></b>
        </div>
      </div>
      <div class="box">
        <div class="box1-content">
          <h2>Toys under 25$</h2>
          <div class="pc-img" style="background-image: url('bear.jpg')"></div>
          <b><p>Shop know</p></b>
        </div>
      </div>
      <div class="box">
        <div class="box1-content">
          <h2>Creating business solution</h2>
          <div class="pc-img" style="background-image: url('lappy.jpg')"></div>
          <b><p>See more business product</p></b>
        </div>
      </div>
      <div class="box">
        <div class="box1-content">
          <h2>Look your best this season</h2>
          <div class="pc-img" style="background-image: url(fashion.jpg)"></div>
          <b><p>Shop know</p></b>
        </div>
      </div>
      <div class="box">
        <div class="box1-content">
          <h2>Shop activity trackers and smartwatches</h2>
          <div class="pc-img" style="background-image: url(watch.jpg)"></div>
          <b><p>Shop know</p></b>
        </div>
      </div>
      <div class="box">
        <div class="box1-content">
          <h2>Try some footwears</h2>
          <div class="pc-img" style="background-image: url(shoe.jpg)"></div>
          <b><p>See more</p></b>
        </div>
      </div>
      <div class="box">
        <div class="box1-content">
          <h2>Personal Care under $25</h2>
          <div class="pc-img" style="background-image: url(brush.jpg)"></div>
          <b><p>See more</p></b>
        </div>
      </div>
      <div class="box">
        <div class="box1-content">
          <h2>Study material</h2>
          <div class="pc-img" style="background-image: url(study.jpg)"></div>
          <b><p>Shop know</p></b>
        </div>
      </div>
    </div>
    <footer>
      <div class="foot-panel1">Back to top</div>
      <div class="foot-panel2">
        <ul>
          <p>Get to Know Us</p>
          <a>Careers</a>
          <a>Blog</a>
          <a>About Amazon</a>
          <a>Investor Relations</a>
          <a>Amazon Devices</a>
          <a>Amazon Science</a>
        </ul>
        <ul>
          <p>Make Money with Us</p>
          <a> Sell products on Amazon</a>
          <a>Blog</a>
          <a> Sell on Amazon Business</a>
          <a> Sell apps on Amazon</a>
          <a> Become an Affiliate</a>
          <a> Advertise Your Products </a>
          <a> Self-Publish with Us</a>
          <a>Host an Amazon Hub</a>
          <a>›See More Make Money with Us</a>
        </ul>
        <ul>
          <p>Amazon Payment Products</p>
          <a> Amazon Payment Products </a>
          <a> Shop with Points</a>
          <a>Reload Your Balance </a>
          <a>Amazon Currency Converter</a>
        </ul>
        <ul>
          <p>Let Us Help You</p>
          <a> Amazon and COVID-19</a>
          <a>Your Account </a>
          <a>Your Orders </a>
          <a> Shipping Rates & Policies </a>
          <a>Returns & Replacements </a>
          <a>Manage Your Content and Devices </a>
          <a>Help</a>
        </ul>
      </div>
      <div class="foot-panel3">
        <div class="logo2">
          <a class="amalogo"> <i class="fa-brands fa-amazon"></i></a>
        </div>
      </div>
      <!-- lastfootpanerl -->
       <div class="foot-panel4">
        <div class="pages">
          <a>Conditions of Use</a>
          <a> Privacy Notice</a>
          <a> Consumer Health Data Privacy Disclouser </a>
          <a> Your Ads Privacy Choices </a>
         </div>
         
         <div class="copyright">
          © 1996-2024, Amazon.com, Inc. or its affiliates
         </div>
       </div>

    </footer>
  </body>
</html>


----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

{CSS}


* {
  margin: 0px;
  font-family: Arial;
  border: border-box;
}

.navbar {
  height: 70px;
  background-color: #0f1111;
  color: white;
  display: flex;
  align-items: center;
  justify-content: space-evenly;
}

.nav-logo {
  height: 60px;
  width: 120px;
  display: flex;
  justify-content: center;
}

.logo {
  background-image: url(amazon-logo-editorial-icon-isolated-260nw-2333488123.webp);
  background-size: cover;
  height: 60px;
  width: 120px;
}

.logo:hover {
  border: 1.5px solid white;
}

.nav-address:hover {
  border: 1.5px solid white;
}

/* box 2 */

.add-first {
  color: #cccccc;
  font-size: 0.85rem;
  margin: 10px;
}

.add-sec {
  font-size: 1rem;

}

.add-icon {
  display: flex;
  align-items: center;
}

/* box 3rd */
.nav-search {
  display: flex;
  justify-content: space-evenly;
  background-color: pink;
  width: 620px;
  height: 40px;
  border-radius: 4px;
}

.nav-search :hover {
  border: 2px solid orange;
}

.search-select {
  background-color: #f3f3f3;
  width: 50px;
  text-align: center;
  border-top-left-radius: 4px;
  border-bottom-left-radius: 4px;
  border: none;
}

.search-input {
  width: 100%;
  font: 1rem;
  border: none;
}

.search-icon {
  width: 45px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 1.2rem;
  border-top-right-radius: 4px;
  border-bottom-right-radius: 4px;
  background-color: #febd68;
  color: #0f1111;
}

/* 4th box */

.sign-in {
  font-size: 0.7rem;

}

.nav-sec {
  font: 0.85rem;
  font-weight: 700px;
}

.fourthbox:hover {
  border: 2px solid white;
}

/* fifthbox */

.Return {
  font-size: 0.7rem;
}

.orders {
  font: 0.85rem;
  font-weight: 700px;
  padding-left: 13.5px;
}

.fifthbox:hover {
  border: 2px solid white;
}


/* box-6 */

.cart i {
  font-size: 30px;
}

.cart:hover {
  border: 2px solid white;
}

.cart {
  font-size: 0.85rem;
  font-weight: 700;
}

/* panel */
.panel {
  background-color: #222f3d;
  height: 40px;
  display: flex;
  color: white;
  align-items: center;
  justify-content: space-evenly;
}

.panel-options p {
  display: inline;
  margin-left: 15px;
}

.panel-options {
  width: 70%;
  font-size: 0.85rem;
}

.panel-deal {
  font-size: 0.9rem;
  font-weight: 700;
}

/* hero-section */

.hero-section {
  background-image: url(hero.jpg);
  height: 350px;
  background-size: cover;
  display: flex;
  justify-content: center;
  align-items: flex-end;

}

.hero-msg {
  background-color: #f5f6f6;
  color: #0f1111;
  height: 40px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 0.85rem;
  width: 80%;
  margin-bottom: 25px;
}

.hero-msg a {
  color: #007185;
}

/* shop-section */
.shop-section {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-evenly;
  background-color: #e2e7e6;

}

.box {
  /* border: 2px solid black; */
  width: 23%;
  height: 400px;
  background-color: white;
  padding: 20px 0px 15px;

}

.pc-img {
  height: 300px;
  background-size: cover;
  background-repeat: none;
  margin-bottom: 1rem;
  margin-top: 1rem;

}

.box1-content {
  margin-left: 1rem;
  margin-right: 1rem;

}

.box1-content p {
  color: #007185;
}

.shop-section p {
  font-size: large;
}

/**FOOTER**/
footer{
  margin-top: 15px;

}
.foot-panel1 {
  background-color: #37475a;
  color: white;
  height: 50px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 0.85rem;
}
/**foot-panel 2**/
.foot-panel2{
   background-color: #222f3d;
   color: white;
   height: 300px;
   display: flex;
   justify-content: space-evenly;
}

ul{
  margin-top: 23px;
}

ul a{
  display: block;
  font-size: 0.85rem;
  margin: 10px;
  color: #dddddd;
}
/**foot panel **/

.foot-panel3{
  background-color: #222f3d;
  color: white;
  border-top: 0.5px solid white;
  height: 100px;
  display: flex;
  justify-content: center;
  align-items: center;
}
 .amalogo{
   font-size: 40px;
}
.foot-panel4{
  background-color:#131a22 ;
  color: white;
  height: 80px;

}    

.pages{
  font-size: 0.8rem;
  text-align: center;
  padding: 10px;

}
.copyright{
   font-size:0.8rem;
   text-align: center;
}


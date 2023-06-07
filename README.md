# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
### home.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./layout.css">
    <link rel="icon" href="Ferrari-Logo-1931.png" type="image/x-icon">
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          
          <div class="contenttext">
            At Edusoft, we understand the importance of technology in enhancing business efficiency and empowering 
            entrepreneurs. That's why we design our products to be user-friendly and adaptable to your specific needs.
            Our latest offering, Edusoft Prime, takes this to the next level by making the 
            transition to automation and our platform simpler than ever before.
            With an intuitive interface and customizable features, you can easily discover the 
            full potential of the product without needing to learn any new skills.
            Edusoft Prime adapts to your unique business and working style,
            providing greater flexibility and a transformed look and feel
            that will make you love it even more.

            Our new product takes this to a new level, making your
            start to automation, or your switch to Tally simpler than ever
            before. You can now discover the product much more easily and make
            the product do more for you, without learning anything new. There is
            greater flexibility as the product adapts to your business and your
            way of working. And the transformed look and feel will only make you
            love the product even more.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 EduSoft Private Limited, Developed by Aakash P.
      </div>
    </div>
  </body>
</html>
```
### products.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="../html/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>

    <div class="total">
      <img src="../images/pexels-irina-iriser-1647976.jpg" class="leftimg">
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="../images/12 pro.jpg" alt="product image">
                  </div>
                  <div class="itemname">i phone</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="../images/air pods.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Air Pods</div>
                  <div class="itemprice">Price: Rs.13,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="../images/mac book.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Mac Book</div>
                  <div class="itemprice">Price: Rs.200,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="../images/apple airtag.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Air Tag</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="../images/drone.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Drone</div>
                  <div class="itemprice">Price: Rs.100000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="../images/apple headphone.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Headphones</div>
                  <div class="itemprice">Price: Rs.60000 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by Aakash P.
      </div>
    </div>
    </div>
  </body>
</html>
```
### people.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    
     <link rel="stylesheet" href="./layout1.css">
    <link rel="icon" href="w0.jpg" type="image/x-icon">
    
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>PEOPLE AT EDUSOFT</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./people/p1.jpg" alt="product image">
                  </div>
                  <div class="itemname">Mickel</div>
                  <div class="itemprice">Managing Director</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./people/p2.png"  alt="product image">
                  </div>
                  <div class="itemname">Franklin</div>
                  <div class="itemprice">Co-founder and Chairman of the Board </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./people/p3.png" alt="product image">
                  </div>
                  <div class="itemname">Trevor</div>
                  <div class="itemprice">Lead Independent Director </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./people/p4.jpg" alt="product image">
                  </div>
                  <div class="itemname">TOM</div>
                  <div class="itemprice">Independent Director India </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./people/p5.jpg" alt="product image">
                  </div>
                  <div class="itemname">Walker</div>
                  <div class="itemprice">Independent Director </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./people/p6.webp" alt="product image">
                  </div>
                  <div class="itemname">Musk</div>
                  <div class="itemprice">Independent Director</div>
              </div>
             
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 EduSoft Private Limited, Developed by Aakash P.
      </div>
    </div>
  </body>
</html>
```
### contacts.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
   <link rel="stylesheet" href="./layout1.css">
    <link rel="icon" href="/static/icon.png" type="image/x-icon">
     
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
          
            <h1>Contact Us</h1>
  <p>If you have any questions or feedback, please don't hesitate to reach out to us.</p>
  <ul>
    <li>Address: 123,Mr John Smith. 132, My Street, Kingston, New York 12401.</li>
    <li>Phone: +91 8765432109</li>
    <li>Email: contact@edusoft.com</li></ul>
  
<h2> Sales Inquiries</h2>

<ul><li>UK 1800 103 11231800 572 3535</li></ul>
    <h2>Press Inquiries</h2> 
<ul><li>press@edusoft.com</li>

<li>Trevor</li>
<li>Trevor@edusoft.com</li></ul>
    <h2>Analyst Relations</h2> 

    <ul><li>Franklin</li>
    <li>+1-925-924-9500</li>
    <li>Franklin@edosoft.com</li></ul>
        <h2>Customer Relations</h2> 

    <ul><li>Mickel</li>
    <li>Director of Sales & Customer Service</li>
    <li>Mickel@edusoft.com</li>
    </ul>
    
  </div>
   <div class="footer">
        Copyright &#169; 2023 EduSoft Private Limited, Developed by Aakash P.
      </div>
      </div>
</body>
</html>
```
### layout.css
```
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: #17421d;
  margin-left: 80%;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px gray;
  background-color: black;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/img/banner1.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #16d1ae;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #5bb045;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #16d1ae;
}

.menuitem a {
  text-decoration: none;
  color: #9c1018;
}

.content {
  display: block;
  width: 100%;
  background-color: #cffffd;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #5bb045;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}


.leftimg{
    position: absolute;
    height: 130%;
    width: 40%;
    margin-left: -600px;
}
```
## OUTPUT:
### Home Page:
![home](https://github.com/Aakash0407/productcompanywebsite/assets/118799103/96ba9863-74e7-4810-9b9a-8c71b42d4831)

### Products Page:
![products](https://github.com/Aakash0407/productcompanywebsite/assets/118799103/9dab3800-08e7-4cd2-859f-12f9daa84aeb)

### People Page:
![people](https://github.com/Aakash0407/productcompanywebsite/assets/118799103/2acffa5b-e78a-4d60-91c0-2a1aa304c8b8)

### Contacts Page:
![contacts](https://github.com/Aakash0407/productcompanywebsite/assets/118799103/20d50557-784d-495e-91d9-ffd1595a922b)

## Result:
Thus a website is designed for the software product company and the HTML,CSS code are validated.

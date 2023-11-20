# Ex.07 Software Product Company Website
## Date:

## AIM:
To develop a static company website to display the softwares and services provided by the company.

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

### Step 7:
Publish the website in the given URL.

## PROGRAM:
## index
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Ethical Hacking</title>

    <!-- font awesome cdn link -->
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css"
    />

    <!-- custom css link -->
    <link rel="stylesheet" type="text/css" href="css/style.css" />
  </head>
  <body>
    <!-- header section start -->
    <header class="header" id="nav">
      <div class="logo"><h1>CHOCOLATE</h1></div>

      <div class="links">
        <a href="#home">home</a>
        <a href="#team">team</a>
        <a href="#project">Products</a>
        <a href="#contact">contact</a>
      </div>

      <div class="icons">
        <div class="fa-solid fa-right-to-bracket"></div>
        <div class="fa-solid fa-user"></div>
        <div class="fas fa-bars" id="menu-btn"></div>
      </div>
    </header>
    <!-- header section ends -->

    <!-- home section start -->

    <section class="home" id="home">
      <div class="content">
        <h1>Join to buy the best chocolate in the world</h1>
        <p>Want to buy</p>
        <a href="#" class="btn"><span>click -></span></a>
      </div>
    </section>
    <!-- home section ends -->

    <!-- team section start -->

    <section class="team" id="team">
      <h1 class="heading">meet our team</h1>
      <p class="paragraph">
      </p>

      <div class="box-container">
        <div class="box">
          <img src="images/Boobesh.jfif" />

          <div class="content">
            <div>
              <h3>Boobesh</h3>
              <span>software engineer</span>

              <div class="icon">
                <a href="#" class="fab fa-facebook-f"></a>
                <a href="#" class="fab fa-instagram"></a>
                <a href="#" class="fab fa-twitter"></a>
              </div>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/Harish.jfif" />

          <div class="content">
            <div>
              <h3>Harish</h3>
              <span>software engineer</span>

              <div class="icon">
                <a href="#" class="fab fa-facebook-f"></a>
                <a href="#" class="fab fa-instagram"></a>
                <a href="#" class="fab fa-twitter"></a>
              </div>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/Abinash.jfif" />

          <div class="content">
            <div>
              <h3>Abinash</h3>
              <span>software engineer</span>

              <div class="icon">
                <a href="#" class="fab fa-facebook-f"></a>
                <a href="#" class="fab fa-instagram"></a>
                <a href="#" class="fab fa-twitter"></a>
              </div>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/Amar.jfif" />

          <div class="content">
            <div>
              <h3>Amar</h3>
              <span>software engineer</span>

              <div class="icon">
                <a href="#" class="fab fa-facebook-f"></a>
                <a href="#" class="fab fa-instagram"></a>
                <a href="#" class="fab fa-twitter"></a>
              </div>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/Boobathi.jfif" />

          <div class="content">
            <div>
              <h3>Boobathi</h3>
              <span>software engineer</span>

              <div class="icon">
                <a href="#" class="fab fa-facebook-f"></a>
                <a href="#" class="fab fa-instagram"></a>
                <a href="#" class="fab fa-twitter"></a>
              </div>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/Srinivasan.jpeg" />

          <div class="content">
            <div>
              <h3>Srinivasan</h3>
              <span>software engineer</span>

              <div class="icon">
                <a href="#" class="fab fa-facebook-f"></a>
                <a href="#" class="fab fa-instagram"></a>
                <a href="#" class="fab fa-twitter"></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- team section ends -->

    <!-- project section start -->

    <section class="project" id="project">
      <h1 class="heading">Products</h1>
      <p class="paragraph">
      </p>

      <div class="box-container">
        <div class="box">
          <img src="images/download (1).jfif" />

          <div class="content">
            <div>
              <h3>Dairy Milk Silk</h3>
              <span>design / product</span>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/download (2).jfif" />

          <div class="content">
            <div>
              <h3>Diry Milk Oreo</h3>
              <span>design / product</span>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/images (1).jfif" />

          <div class="content">
            <div>
              <h3>Dairy Milk Red</h3>
              <span>design / product</span>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/images (2).jfif" />

          <div class="content">
            <div>
              <h3>All In One</h3>
              <span>design / product</span>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/images (3).jfif" />

          <div class="content">
            <div>
              <h3>Dairy Milk Heart</h3>
              <span>design / product</span>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/images (4).jfif" />

          <div class="content">
            <div>
              <h3>Special Diry Milk</h3>
              <span>design / product</span>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/images (5).jfif" />

          <div class="content">
            <div>
              <h3>Dairy Milk Green</h3>
              <span>design / product</span>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/images.jfif" />

          <div class="content">
            <div>
              <h3>Special Edition</h3>
              <span>design / product</span>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/images (6).jfif" />

          <div class="content">
            <div>
              <h3>Heart</h3>
              <span>design / Product</span>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/images (7).jfif" />

          <div class="content">
            <div>
              <h3>Silk Gold</h3>
              <span>design / product</span>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/images (8).jfif" />

          <div class="content">
            <div>
              <h3>3 in 1</h3>
              <span>design / product</span>
            </div>
          </div>
        </div>

        <div class="box">
          <img src="images/images (9).jfif" />

          <div class="content">
            <div>
              <h3>Special Edition 3 in 1</h3>
              <span>design / product</span>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- project section ends -->

    <!-- contact section start -->

    <section class="contact" id="contact">
      <h1 class="heading">contact us</h1>
      <p class="paragraph">feel free to contact us</p>

      <div class="row">
        <div class="content">
          <h1>let's talk</h1>
          <h3>bookesh@gmail.com</h3>
          <p>
			ALso Social Media Available For Further Information
          </p>

          <div class="icons">
            <a href="#" class="fab fa-facebook-f"></a>
            <a href="#" class="fab fa-instagram"></a>
            <a href="#" class="fa-solid fa-phone"></a>
			<a href="#" class="fa fa-at"></a>
          </div>
        </div>

        <div class="form">
          <form>
            <input type="text" name="" placeholder="your name" />
            <input type="email" name="" placeholder="your email" />
            <input type="text" name="" placeholder="subject" class="subject" />

            <textarea placeholder="your message"></textarea>

            <a href="#" class="btn"><span>send message</span></a>
          </form>
        </div>
      </div>
    </section>

    <!-- contact section ends -->

    <!-- footer section start -->
    <section class="footer">
      <div class="credit">
        created by <span>Boobesh networks</span> | all rights reserved.
      </div>

      <div class="links">
        <a href="#">teams of use</a>
        <a href="#">privacy policy</a>
        <a href="#">cookie policy</a>
      </div>
    </section>
    <!-- footer section ends -->

    <!-- custom js link -->
    <script src="js/scripts.js"></script>
  </body>
</html>
```
## style.css
```
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700&display=swap');
/*font-family: 'Roboto', sans-serif;*/

:root
{
	--main-color: #e9204f;
	--black: #191919;
	--bg: #101010;
	--font: #fff;
	--border: .1rem solid rgba(255,255,255,.3);
}
*
{
	font-family: 'Roboto', sans-serif;
	margin: 0;padding: 0;
	box-sizing: border-box;
	outline: none;border: none;
	text-decoration: none;
	text-transform: capitalize;
	transition: .3s linear;
}
html
{
	font-size: 62.5%;
	overflow-x: hidden;
	scroll-padding-top: 9rem;
	scroll-behavior: smooth;
}
html::-webkit-scrollbar
{
	width: .8rem;
}
html::-webkit-scrollbar-track
{
	background: transparent;
}
html::-webkit-scrollbar-thumb
{
	background: #eee;
	border-radius: 4rem;
}
body
{
	background: var(--bg);
}
section
{
	padding: 4rem 7%;
}
.btn
{
	margin-top: 1rem;
	display: inline-block;
	padding: 2rem 4rem;
	font-size: 1.7rem;
	color: var(--font);
	cursor: pointer;
	position: relative;
	overflow: hidden;
	background: #fff;
}
.btn span 
{
	position: relative;
	z-index: 3;
}
.btn:after
{
	content: '';
	display: block;
	width: 100%;height: 100%;
	position: absolute;
	right: 0%;top: 0%;
	background: var(--main-color);
	transition: .5s;
	z-index: 1;
}
.btn:hover:after
{
	right: -100%;
}
.btn:hover
{
	color: var(--main-color);
}
.heading
{
	text-align: center;
	color: var(--font);
	padding: 2.5rem 0;
	font-size: 4.5rem;
}
.paragraph
{
	text-align: center;
	font-size: 1.5rem;
	color: #747474;
	padding: 1rem 0;
	line-height: 1.8;
}




.header
{
	background: transparent;
	display: flex;
	color: var(--font);
	align-items: center;
	justify-content: space-between;
	padding: 1.5rem 7%;
	position: fixed;
	top: 0;left: 0;right: 0;
	z-index: 5000;
}
.header .logo h1
{
	font-size: 3rem;
	letter-spacing: .1rem;
}
.header .links a 
{
	margin: 0 1rem;
	color: var(--font);
	font-size: 1.5rem;
	letter-spacing: .1rem;
}
.header .links a:hover
{
	border-bottom: .1rem solid var(--main-color);
	padding-bottom: .5rem;
}
.header .icons div
{
	color: var(--font);
	cursor: pointer;
	font-size: 1.8rem;
	margin-left: 2rem;
}
.header .icons div:hover
{
	color: var(--main-color);
}
#menu-btn
{
	display: none;
}

/*on scroll effect*/

.nav-change
{
	background: var(--black);
}

/*home section style*/

.home
{
	min-height: 100vh;
	display: flex;
	align-items: center;
	justify-content: center;
	background: linear-gradient(rgba(0, 0, 0, .2),rgba(0, 0, 0, .2)),url(../images/download.jfif);
	background-repeat: no-repeat;
	background-size: cover;
	text-align: center;
}
.home .content h1
{
	font-size: 6rem;
	text-transform: uppercase;
	color: var(--font);
}
.home .content p 
{
	font-size: 2rem;
	font-weight: lighter;
	color: #eee;
	line-height: 1.8;
	padding: 1rem 0;
}


/*service section style*/
.service .box-container
{
	display: grid;
	grid-template-columns: repeat(auto-fit, minmax(30rem,1fr));
	gap: 2rem;
	padding: 2.5rem 0;
}
.service .box-container .box
{
	padding: 5rem;
	background: var(--black);
	cursor: pointer;
}
.service .box-container .box i 
{
	color: var(--font);
	font-size: 5rem;
	padding: 2.5rem 0;
}
.service .box-container .box h3
{
	color: var(--font);
	font-size: 2.5rem;
	padding: .3rem 0;
}
.service .box-container .box p 
{
	font-size: 1.5rem;
	color: #747474;
	padding: 2rem 0;
	line-height: 1.8;
}
.service .box-container .box span 
{
	font-size: 3rem;
	color: #ccc;
	line-height: 1.8;
}
.service .box-container .box:hover i
{
	color: var(--main-color);
} 
.service .box-container .box:hover
{
	box-shadow: 3px 3px 15px rgba(214, 215, 215, .2);
	transform: scale(1.01);
}


/*project style*/

.project .box-container
{
	display: grid;
	grid-template-columns: repeat(auto-fit, minmax(30rem,1fr));
	gap: 2rem;
	padding: 2.5rem 0;
}
.project .box-container .box  
{
	position: relative;
	cursor: pointer;
	overflow: hidden;
}
.project .box-container .box img
{
	width: 100%;
	height: 100%;
	object-fit: cover;
	transform-origin: center;
}
.project .box-container .box:hover img
{
	transform: scale(1.1);
}
.project .box-container .box .content
{
	position: absolute;
	top: 0;left: 0;right: 0;bottom: 0;
	display: flex;
	align-items: center;
	justify-content: center;
	color: var(--font);
	background: rgba(0, 0, 0, .4);
	text-align: center;
	opacity: 0;
}
.project .box-container .box .content h3
{
	font-size: 3rem;
}
.project .box-container .box .content span 
{
	font-size: 1.2rem;
}
.project .box-container .box:hover .content
{
	opacity: 1;
}

/*team style*/

.team .box-container
{
	display: grid;
	grid-template-columns: repeat(auto-fit, minmax(30rem,1fr));
	gap: 2rem;
	padding: 2.5rem 0;
}
.team .box-container .box
{
	position: relative;
	cursor: pointer;
	overflow: hidden;
	border-radius: 50%;
}
.team .box-container .box img 
{
	width: 100%;
	height: 100%;
	object-fit: cover;
	transform-origin: center;
}
.team .box-container .box:hover img 
{
	transform: scale(1.1);
}
.team .box-container .box .content
{
	position: absolute;
	top: 0;left: 0;right: 0;bottom: 0;
	color: var(--font);
	display: flex;
	align-items: center;
	justify-content: center;
	text-align: center;
	opacity: 0;
}
.team .box-container .box .content h3
{
	font-size: 3rem;
	padding: .3rem 0;
}
.team .box-container .box .content span 
{
	font-size: 1.2rem;
}
.team .box-container .box .content .icon a 
{
	width: 3rem;
	height: 3rem;
	line-height: 3rem;
	display: inline-block;
	color: #ddd;
	margin: 1rem .2rem;
	background: rgba(0, 0, 0, .8);
}
.team .box-container .box .content .icon a:hover
{
	border-radius: 50%;
}
.team .box-container .box:hover .content
{
	opacity: 1;
	background: rgba(233, 32, 79, .6);
}

/*blog style*/
.blog .box-container
{
	display: grid;
	grid-template-columns: repeat(auto-fit, minmax(30rem,1fr));
	gap: 1.5rem;
	padding: 3rem 0;
}
.blog .box-container .box .image
{
	height: 25rem;
	overflow: hidden;
	width: 100%;
}
.blog .box-container .box .image img
{
	height: 100%;
	object-fit: cover;
	width: 100%;
}
.blog .box-container .box:hover .image img
{
	transform: scale(1.2);
}
.blog .box-container .box .content
{
	padding: 2rem 0rem;
}
.blog .box-container .box .content .cate
{
	font-size: 1.5rem;
	line-height: 1.5;
	color: var(--font);
}
.blog .box-container .box .content span 
{
	color: var(--main-color);
	display: block;
	padding-top: 1rem;
	font-size: 2.2rem;
}
.blog .box-container .box .content p 
{
	font-size: 1.3rem;
	line-height: 1.8;
	color: #ddd;
	padding: 1rem 0;
}
.blog .box-container .box .content a 
{
	font-size: 1.5rem;
	color: var(--font);
}

/*contact style*/
.contact .row 
{
	display: flex;
	align-items: center;
	flex-wrap: wrap;
	padding: 3rem 0;
}
.contact .row .content
{
	flex: 1 1 35rem;
	padding: 2rem;
}
.contact .row .content h1
{
	font-size: 5rem;
	color: var(--font);
	padding: 3rem 0;
}
.contact .row .content h3
{
	font-size: 2rem;
	color: var(--main-color);
	font-weight: 300;
	padding: 2rem 0;
}
.contact .row .content p 
{
	font-size: 1.6rem;
	color: #ccc;
	line-height: 1.8;
	padding: 1rem 0;
}
.contact .row .content .icons a 
{
	width: 5rem;
	height: 5rem;
	line-height: 5rem;
	text-align: center;
	color: var(--font);
	margin: .3rem .3rem;
	border: .1rem solid var(--main-color);
	font-size: 1.3rem;
	border-radius: 50%;
}
.contact .row .content .icons a:hover
{
	transform: translateY(-1rem);
}
.contact .row .form 
{
	flex: 1 1 55rem;
	padding: 2rem;
}
.contact .row .form input[type="text"],
.contact .row .form input[type="email"]
{
	width: 27rem;
	background: transparent;
	border-bottom: .1rem solid #ddd;
	padding-bottom: 2rem;
	margin: 2.5rem 0;
	color: #ddd;
}
.contact .row .form .subject
{
	width: 55rem!important;
}
.contact .row .form textarea
{
	width: 55rem;
	background: transparent;
	border-bottom: .1rem solid #ddd;
	padding-bottom: 2rem;
	color: #ddd;
	margin: 1rem 0;
}

/*footer style*/

.footer
{
	background: var(--black);
	display: flex;
	justify-content: space-between;
	flex-wrap: wrap;
}
.footer .credit
{
	font-size: 2rem;
	flex: 1 1 45rem;
	color: var(--font);
	font-weight: lighter;
	padding: 1rem 0;
}
.footer .credit span 
{
	color: var(--main-color);
}
.footer .links
{
	display: flex;
	flex: 1 1 35rem;
	justify-content: center;
	flex-wrap: wrap;
	gap: 1rem;
	align-items: center;
	padding: 1rem 0;

}
.footer .links a 
{
	color: var(--font);
	font-size: 1.5rem;
}
.footer .links a:hover
{
	color: var(--main-color);
}





/*media query start*/
@media (max-width: 991px)
{
	html
	{
		font-size: 55%;
	}
	section
	{
		padding: 2rem;
	}
	.btn
	{
		padding: 1.5rem 3rem;
	}
	.header
	{
		padding: 1.5rem 2rem;
	}
}
@media (max-width: 768px)
{
	#menu-btn
	{
		display: inline-block;
	}
	.header .links
	{
		position: absolute;
		top: 100%;right: -100%;
		background: var(--bg);
		width: 100%;
		height: calc(100vh - 9.5rem);
		text-align: left;
	}
	.header .links a 
	{
		color: #ccc;
		display: block;
		margin: 1.5rem;
		padding: 1rem;
		border-bottom: var(--border);
	}
	.header .links a:hover
	{
		padding-bottom: 1.5rem;
	}
	.header.active
	{
		background: var(--black);
	}
	.header .links.active
	{
		right: 0;
	}
	.contact .row .content
	{
		text-align: center;
	}
}
@media (max-width: 450px)
{
	html
	{
		font-size: 50%;
	}
}
```
## script.js
```
let navbar = document.querySelector('.links');

let header = document.querySelector('header');

document.querySelector('#menu-btn').onclick = () =>{
	navbar.classList.toggle('active');
	header.classList.toggle('active');
}

function change() {
	var nav = document.getElementById('nav');

	var value=window.scrollY;

	if (value>80) 
	{
		nav.classList.add('nav-change');
	}
	else
	{
		nav.classList.remove('nav-change');
	}
}

window.addEventListener('scroll',change);
```





## OUTPUT:
![image](https://github.com/Harishragav123/softweb/assets/135584731/ae2db868-3a56-4f03-badc-a068c47b31ea)
![image-1](https://github.com/Harishragav123/softweb/assets/135584731/0fd23453-51f8-444f-8290-bdf501a8f445)
![image-2](https://github.com/Harishragav123/softweb/assets/135584731/a29f5121-fe16-4388-bd31-8dcf05091c55)
![image-3](https://github.com/Harishragav123/softweb/assets/135584731/b43d5e09-05a4-4947-af57-a434fbf46f9f)
![image-4](https://github.com/Harishragav123/softweb/assets/135584731/078e234c-f300-49ea-872b-9e578919f46c)
![image-5](https://github.com/Harishragav123/softweb/assets/135584731/655f9477-9d88-4e9a-af30-d22c27d0e0ed)





## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

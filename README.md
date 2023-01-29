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
```

* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}

body {
  background-color: whitesmoke;
}

#home-h{
  width: 50%;
  margin-left: 20px;
}

h1{
  font-size:100px;
  letter-spacing: 1px;
  width: fit-content;
}

.container {
  width: 1080px;
  margin: auto;
  margin-top: 25px;
  box-shadow: rgba(0, 0, 0, 0.1) 0px 10px 50px;
  border-radius: 10px;
}

.banner {
  display: block;
  width: 100%;
  height: 10px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/img/applelogo.png");
  background-size:25%;
  background-repeat: no-repeat;
  background-position: center;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  border-radius: 5px;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #000000;
  text-align: center;
  margin: 0px 0px 0px 0px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  height: 100%;
  padding: 10px;
  padding-top: 15px;
}

.menuitem a {
  text-decoration: none;
  color: #fff;
}

.content {
  display: block;
  width: 100%;
  background-color: #ffffff;
  min-height: 500px;
  border-width: 0.1px;
  border-color: white white black white;
  border-style: solid;
  background-image: url('/static/img/iPhone.jpg');
  background-position: right bottom;
  background-size: 45%;
  background-repeat: no-repeat;
}

#home-p{
  font-size: larger;
  width: 50%;
  margin-left: 30px;
  margin-top: -50px;
  color: rgb(73, 73, 73);
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

a
{
    text-decoration: none;
}
.p-page{
  display: grid;
  grid-template-columns: auto auto;
  padding: 70px;
}
.product-card {
    width: 400px;
    position: relative;
    box-shadow: 0 2px 7px #dfdfdf;
    background: #fafafa;
    margin: auto;
    margin-bottom: 50px;
}

.badge {
    position: absolute;
    left: 0;
    top: 20px;
    text-transform: uppercase;
    font-size: 13px;
    font-weight: 700;
    background: red;
    color: #fff;
    padding: 3px 10px;
}

.p-con{
  background: none;
}

.product-tumb {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 300px;
    padding: 50px;
    background: #fff;
}

.product-tumb img {
    max-width: 100%;
    max-height: 100%;
}

.product-details {
    padding: 30px;
    background-color: rgb(250, 250, 250);
}

.product-catagory {
    display: block;
    font-size: 12px;
    font-weight: 700;
    text-transform: uppercase;
    color: rgb(108, 108, 108);
    margin-bottom: 18px;
}

.product-details h4 a {
    font-weight: 500;
    display: block;
    margin-bottom: 18px;
    text-transform: uppercase;
    color: #363636;
    text-decoration: none;
    transition: 0.3s;
}

.product-details h4 a:hover {
    color: #fbb72c;
}

.product-details p {
    font-size: 15px;
    line-height: 22px;
    margin-bottom: 18px;
    color: #999;
}

.product-bottom-details {
    overflow: hidden;
    border-top: 1px solid #eee;
    padding-top: 20px;
}

.product-bottom-details div {
    float: left;
    width: 50%;
}

.product-price {
    font-size: 18px;
    color: #fbb72c;
    font-weight: 600;
}

.product-price small {
    font-size: 80%;
    font-weight: 400;
    text-decoration: line-through;
    display: inline-block;
    margin-right: 5px;
}

.product-links {
    text-align: right;
}

.product-links a {
    display: inline-block;
    margin-left: 5px;
    color: #e1e1e1;
    transition: 0.3s;
    font-size: 17px;
}

.product-links a:hover {
    color: #fbb72c;
}

.profile-card {
	width: 300px;
  margin: auto;
  margin-bottom: 80px;
	display: flex;
	flex-direction: column;
	align-items: center;
	padding: 2rem;
	background-color: white;
	border-radius: 1rem;
  box-shadow: rgba(0, 0, 0, 0.1) 0px 10px 50px;
}

.profile-image {
	position: relative;
	top: -60px;
	border-radius: 100px;
	width: 11rem;
	height: 11rem;
  background-image: url('/static/img/shakthi.png');
	background-position: center;
	background-size: cover;
  border:rgb(0, 0, 0) 3px solid; 
	box-shadow: rgba(0, 0, 0, 0.1) 0px 10px 50px;
}

.profile-info {
	text-align: center;
	margin-top: -3rem;
	margin-bottom: 1rem;
}

.profile-info > .profile-name {
	color: #212121;
}

.profile-info > .profile-desc {
	color: #666666;
	font-size: 0.9rem;
}

.status {
	list-style: none;
	display: flex;
	justify-content: space-between;
	text-align: center;
	line-height: 1rem;
	margin-bottom: 1.3rem;
  padding: 10px;
}

.status-value {
	color: #212121;
	font-weight: 700;
}

.status-text {
	font-size: 0.8rem;
	color: #7c7c7d;
}

.action {
	display: flex;
	justify-content: space-between;
}

.btn {
	border: none;
	padding: 0.8em 1.9em;
	border-radius: 0.35rem;
	cursor: pointer;
	font-weight: 600;
}

.btn-pink {
	background: #000000;
	color: white;
}

.btn-gray-outline {
	border: 1px solid;
	background: transparent;
	color: #000000;
}

#about-p{
  padding:0px 70px;
  line-height: 25px;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #000;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #ffffff;
  border-radius: 0px 0px 10px 10px ;
}

.fill{
  transition: all 0.3s ease-in-out;
}

.fill:hover{
  background-color: #fff;
  cursor: pointer;
}

.fill:hover a{
  color: black;
}
```
```
{% load static %}

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Apple</title>
    <link rel="stylesheet" href="{% static 'css/layout.css' %}" />
    <link rel="icon" href="https://alchemyimmersive.com/wp-content/uploads/sites/4/2020/04/apple-logo-transparent.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem fill"><a href="/home">Home</a></div>
        <div class="menuitem fill"><a href="/about">About</a></div>
        <div class="menuitem fill"><a href="/products">Products</a></div>
        <div class="menuitem fill"><a href="/people">People</a></div>
        <div class="menuitem fill"><a href="/contact">Contact Us</a></div>
      </div>
      <div class="content">
        <h1 id="home-h" >THINK DIFFERENT.</h1>
        <p id="home-p">Everything is designed. Few things are designed well. And those are designed by us.</p>
      </div>
      <div class="footer">
        &#169; 2021 Apple Lt., Developed by jagadeesh
      </div>
    </div>
  </body>
</html>

```
```
{% load static %}

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Apple</title>
    <link rel="stylesheet" href="{% static 'css/layout.css' %}" />
    <link rel="icon" href="https://alchemyimmersive.com/wp-content/uploads/sites/4/2020/04/apple-logo-transparent.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
        <div class="menu">
        <div class="menuitem fill"><a href="/home">Home</a></div>
        <div class="menuitem fill"><a href="/about">About</a></div>
        <div class="menuitem fill"><a href="/products">Products</a></div>
        <div class="menuitem fill"><a href="/people">People</a></div>
        <div class="menuitem fill"><a href="/contact">Contact Us</a></div>
      </div>
      <div class="content p-con">
        <h1 style="margin:auto;margin-top:50px;font-size:50px;">People</h1>
        <div class="p-page">
            <div class="profile-card">
                <div class="profile-card-header">
                    <div class="profile-image" style="background-image: url(https://pm1.narvii.com/7721/6550eae21d1637c54ac4f4ff15bea4010f728cc5r1-554-554v2_hq.jpg);"></div>
            
                    <div class="profile-info">
                        <h3 class="profile-name">Jonny Sins</h3>
                        <p class="profile-desc">All Rounder</p>
                    </div>
                </div>
                <div class="profile-card-body">
                    <ul class="status">
                        <li>
                            <span class="status-value">751</span>
                            <span class="status-text">Posts</span>
                        </li>
            
                        <li>
                            <span class="status-value">1.8m</span>
                            <span class="status-text">Followers</span>
                        </li>
            
                        <li>
                            <span class="status-value">4</span>
                            <span class="status-text">Following</span>
                        </li>
                    </ul>
            
                    <div class="action">
                        <button class="btn btn-pink">Follow</button>
                        <button class="btn btn-gray-outline">Message</button>
                    </div>
                </div>
            </div>
            <div class="profile-card">
                <div class="profile-card-header">
                    <div class="profile-image" ></div>
                    <div class="profile-info">
                        <h3 class="profile-name">Powervel</h3>
                        <p class="profile-desc">Developer/Conent Creator</p>
                    </div>
                </div>
                <div class="profile-card-body">
                    <ul class="status">
                        <li>
                            <span class="status-value">532</span>
                            <span class="status-text">Posts</span>
                        </li>
            
                        <li>
                            <span class="status-value">1.5m</span>
                            <span class="status-text">Followers</span>
                        </li>
            
                        <li>
                            <span class="status-value">423</span>
                            <span class="status-text">Following</span>
                        </li>
                    </ul>
            
                    <div class="action">
                        <button class="btn btn-pink">Follow</button>
                        <button class="btn btn-gray-outline">Message</button>
                    </div>
                </div>
            </div>
            <div class="profile-card">
                <div class="profile-card-header">
                    <div class="profile-image" style="background-image: url('https://m.media-amazon.com/images/M/MV5BNzg1MTUyNDYxOF5BMl5BanBnXkFtZTgwNTQ4MTE2MjE@._V1_.jpg');"></div>
            
                    <div class="profile-info">
                        <h3 class="profile-name">RDJ</h3>
                        <p class="profile-desc">Genius, billionaire,philanthropist.</p>
                    </div>
                </div>
                <div class="profile-card-body">
                    <ul class="status">
                        <li>
                            <span class="status-value">532</span>
                            <span class="status-text">Posts</span>
                        </li>
            
                        <li>
                            <span class="status-value">1.5m</span>
                            <span class="status-text">Followers</span>
                        </li>
            
                        <li>
                            <span class="status-value">423</span>
                            <span class="status-text">Following</span>
                        </li>
                    </ul>
            
                    <div class="action">
                        <button class="btn btn-pink">Follow</button>
                        <button class="btn btn-gray-outline">Message</button>
                    </div>
                </div>
            </div>
            <div class="profile-card">
                <div class="profile-card-header">
                    <div class="profile-image" style="background-image: url('https://file1.telestar.fr/var/telestar/storage/images/3/3/2/3/3323904/chris-evans-comment-failli-refuser-role-vie.jpg?alias=exact1024x768_l');"></div>
            
                    <div class="profile-info">
                        <h3 class="profile-name">Cris Evans</h3>
                        <p class="profile-desc">Conent Creator</p>
                    </div>
                </div>
                <div class="profile-card-body">
                    <ul class="status">
                        <li>
                            <span class="status-value">532</span>
                            <span class="status-text">Posts</span>
                        </li>
            
                        <li>
                            <span class="status-value">1.5m</span>
                            <span class="status-text">Followers</span>
                        </li>
            
                        <li>
                            <span class="status-value">423</span>
                            <span class="status-text">Following</span>
                        </li>
                    </ul>
            
                    <div class="action">
                        <button class="btn btn-pink">Follow</button>
                        <button class="btn btn-gray-outline">Message</button>
                    </div>
                </div>
            </div>
            <div class="profile-card">
                <div class="profile-card-header">
                    <div class="profile-image" style="background-image: url('https://image.gala.de/21743318/t/N_/v12/w960/r0.6667/-/elizabeth-olsen.jpg');"></div>
            
                    <div class="profile-info">
                        <h3 class="profile-name">Elizabeth Olsen</h3>
                        <p class="profile-desc">Developer</p>
                    </div>
                </div>
                <div class="profile-card-body">
                    <ul class="status">
                        <li>
                            <span class="status-value">532</span>
                            <span class="status-text">Posts</span>
                        </li>
            
                        <li>
                            <span class="status-value">1.5m</span>
                            <span class="status-text">Followers</span>
                        </li>
            
                        <li>
                            <span class="status-value">423</span>
                            <span class="status-text">Following</span>
                        </li>
                    </ul>
            
                    <div class="action">
                        <button class="btn btn-pink">Follow</button>
                        <button class="btn btn-gray-outline">Message</button>
                    </div>
                </div>
            </div>
            <div class="profile-card">
                <div class="profile-card-header">
                    <div class="profile-image" style="background-image: url('https://a1cf74336522e87f135f-2f21ace9a6cf0052456644b80fa06d4f.ssl.cf2.rackcdn.com/images/characters/large/800/Bruce-Banner.The-Incredible-Hulk.webp');"></div>
                    <div class="profile-info">
                        <h3 class="profile-name">Bruce Banner</h3>
                        <p class="profile-desc">Scientist</p>
                    </div>
                </div>
                <div class="profile-card-body">
                    <ul class="status">
                        <li>
                            <span class="status-value">532</span>
                            <span class="status-text">Posts</span>
                        </li>
            
                        <li>
                            <span class="status-value">1.5m</span>
                            <span class="status-text">Followers</span>
                        </li>
            
                        <li>
                            <span class="status-value">423</span>
                            <span class="status-text">Following</span>
                        </li>
                    </ul>
            
                    <div class="action">
                        <button class="btn btn-pink">Follow</button>
                        <button class="btn btn-gray-outline">Message</button>
                    </div>
                </div>
            </div>
        </div>
      </div>
      <div class="footer">
        &#169; 2021 Apple Lt., Developed by  jagadeesh
      </div>
    </div>
  </body>
</html>

```
```
{% load static %}

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Apple</title>
    <link rel="stylesheet" href="{% static 'css/layout.css' %}" />
    <link rel="icon" href="https://alchemyimmersive.com/wp-content/uploads/sites/4/2020/04/apple-logo-transparent.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem fill"><a href="/home">Home</a></div>
        <div class="menuitem fill"><a href="/about">About</a></div>
        <div class="menuitem fill"><a href="/products">Products</a></div>
        <div class="menuitem fill"><a href="/people">People</a></div>
        <div class="menuitem fill"><a href="/contact">Contact Us</a></div>
      </div>
      <div class="content p-con">
        <h1 style="margin:auto;margin-top:50px;font-size:50px;">Contact Us</h1><br><br>
          <p id="about-p" style="font-size:19px;line-height:33px;"><b>Email: </b>applestore@inc.com<br>
            <b>Contact Number: </b>+44 467 467 23<br>
            <b>Facebook: </b>Apple Inc.<br>
            <b>Instagram: </b>Apple Inc.<br>
            <b>Linkedin: </b>Apple Inc.<br>
            <b>Address: </b>One Apple Park Way; Cupertino, CA 95014, U.S.A.<br></p>
      </div>
      <div class="footer">
        &#169; 2021 Apple Lt., Developed by jagadeesh.
      </div>
    </div>
  </body>
</html>

```

## OUTPUT:

### Home Page:
![home](https://user-images.githubusercontent.com/120623104/215328767-0c5fad7a-1f69-41ed-a2ac-fc6136cb4069.png)
![products](https://user-images.githubusercontent.com/120623104/215328787-13cec3d5-88b6-45b8-a4fc-fd047bc60b9d.png)

![people](https://user-images.githubusercontent.com/120623104/215328791-cac5995f-b63b-454f-9c14-93e66af34e55.png)
![contact](https://user-images.githubusercontent.com/120623104/215328792-91009521-3c60-41d0-a568-d405a1e520ed.png)


## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.

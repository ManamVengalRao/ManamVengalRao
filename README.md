<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Creating a Landing Page Website</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <section>
      <div class="container">
        <nav>
          <h1>Logo</h1>
          <ul>
            <li><a href="" class="active">Home</a></li>
            <li><a href="">About</a></li>
            <li><a href="">Services</a></li>
            <li><a href="">Contact</a></li>
          </ul>
        </nav>
        <div class="article">
          <h1>Creative Digital Agency</h1>
          <p>
            Offer services such as online and print copywriting, logo design,
            color schemes, ad creation, and more.<br />
            Their primary role is to create visual elements and content for
            businesses. Digital Agencies: Responsible for all things related to
            digital marketing.
          </p>
          <a href="" class="btn">Download Now</a>
        </div>
      </div>
    </section>
  </body>
</html>




* {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  font-family: "roboto", sans-serif;
}
section {
  min-height: 100vh;
  background-image: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)),
    url("../image/img.jpg");
  background-repeat: no-repeat;
  background-size: cover;
}
.container {
  width: 85%;
  margin: auto;
}
nav {
  height: 80px;
}
nav h1 {
  float: left;
  line-height: 80px;
  font-size: 35px;
  font-size: inline;
  color: #eb7620;
}
nav ul {
  float: right;
  line-height: 80px;
}
nav ul li {
  display: inline-block;
  list-style: none;
  padding: 0px 5px;
}
nav ul li a {
  color: #fff;
  text-decoration: none;
  text-transform: uppercase;
  border-radius: 5px;
  padding: 7px 8px;
}
nav ul li a:hover {
  background-color: #eb7620;
  transition: 0.5s ease;
}
nav ul li .active {
  background-color: #eb7620;
}
.article {
  width: 50%;
  margin: auto;
  text-align: center;
  transform: translateY(25vh);
}
.article h1 {
  font-size: 36px;
  color: #fff;
  letter-spacing: 1.5px;
  font-weight: 800;
  margin-bottom: 25px;
}
.article p {
  font-size: 18px;
  color: #7e7e7e;
  line-height: 1.5;
  margin-bottom: 50px;
}
.article .btn {
  color: #fff;
  padding: 12px 25px;
  letter-spacing: 1.5px;
  text-transform: uppercase;
  text-decoration: none;
  background-color: #f15048;
}
.article .btn:hover {
  background-color: hsl(213, 10%, 21%);
  transition: 0.5s ease;
}

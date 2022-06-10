<!-- add link -->
<link
      rel="stylesheet"
      href="https://cdn.rawgit.com/2noScript/font-awesome/main/fontawesome-pro-5.13.0-web/css/all.min.css"
    />
<style>
 @import url("https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,300;0,400;0,500;0,700;0,900;1,400&display=swap");
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
  font-family: "Roboto", sans-serif;
}
html {
font-size: 62.5%;
}
body {
font-size: 1.6rem;
}
a {
text-decoration: none;
}
:root {
--btn-border-radius: 12px;
}
</style>

![Top banner](image/banner.jpg)

<html lang="en">
  <head>
   
<style>

.contact {
display: flex;
align-items: center;
justify-content: center;

padding: 32px 0;
}
.contact-item {
display: flex;
justify-content: center;
align-items: center;
color: #ffffff;
background-color: antiquewhite;
border: 1px solid black;
border-radius: var(--btn-border-radius);
padding: 8px 8px;
font-size: 1.4rem;
font-weight: 600;
}
.contact-item:hover {
cursor: pointer;
}
.contact-item + .contact-item {
margin-left: 4px;
}
.contact-item .contact-name {
text-transform: uppercase;
display: none;
}
.contact-item .contact-icon {
display: flex;
justify-content: center;
align-items: center;
width: 36px;
height: 36px;
font-size: 3.2rem;

}
.contact-item.facebook {

color: #1877f2;
}
.contact-item.instagram {

color: #c535a3;
}
.contact-item.youtube {

color: #c91211;
}
.contact-item.github {
color: #000000;
}
</style>

  </head>
  <body>
    <div class="contact">
      <a
        class="contact-item facebook"
        href="https://www.facebook.com/profile.php?id=100024072759238"
        target="_blank"
      >
        <div class="contact-icon"><i class="fab fa-facebook-square"></i></div>
        <span class="contact-name"> facebook </span>
      </a>
      <a
        class="contact-item instagram"
        href="https://www.instagram.com/2noscript/"
        target="_blank"
      >
        <div class="contact-icon"><i class="fab fa-instagram"></i></div>
        <span class="contact-name"> instagram </span>
      </a>
      <a
        class="contact-item youtube"
        href="https://www.youtube.com/channel/UCBoON30jZ100O8m9DGUHWqQ"
        target="_blank"
      >
        <div class="contact-icon"><i class="fab fa-youtube-square"></i></div>
        <span class="contact-name"> youtube </span>
      </a>
      <a
        class="contact-item github"
        href="https://github.com/2noScript"
        target="_blank"
      >
        <div class="contact-icon"><i class="fab fa-github-square"></i></div>
        <span class="contact-name"> github </span>
      </a>
    </div>
  </body>
</html>

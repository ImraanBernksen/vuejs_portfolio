<template>
  <router-view/>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Gemunu+Libre:wght@600&family=Nanum+Pen+Script&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Alkalami&display=swap');

*,
*::before,
*::after {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root {
    --primaryColor: blue;
    --secondaryColor: blue;
    --alternativeColor: white;
    --mainBoxShadow: .5vw .5vw .5vw var(--alternativeColor);
    --landingPage : .5vw 1vw .5vw var(--gray);
    --activeLink: lime;
}

a:link {
    color: var(--primaryColor);
}
a:visited {
    color: var(--alternativeColor);
    border-radius: 5px;
}
a:hover {
    font-size: 30px;
    color: var(--secondaryColor);
    background-color: white;
    border-radius: 10px;
}
a:active {
    color: var(--primaryColor);
    background-color: var(--activeLink);
}

h2 {
    font-family: 'Gemunu Libre', sans-serif;
}

h4, p, .project-tile, #fill, #social-media, #projects {
    font-family: 'Alkalami', serif;
}

header, main, footer {
    min-width: 100%;
}

header {
    background-color: black;
    padding-bottom: 10px;
}

.logo {
    width: 2em;
    border-radius: 50%;
}

.menu {
    margin-left: auto;
    align-self: center;
}
.menu-list li {
  padding: 0 5px;
}
  
.menu-list {
    font-family: 'Gemunu Libre', sans-serif;
    list-style: none;
    font-size: 25px;
}

h1, h2, h3, h5, h6 {
    text-align: center;
    padding-bottom: 20px;
    padding: 20px;
    color: white;
}

h4 {
    text-align: center;
    padding-bottom: 20px;
    padding: 20px;
    color: gold;
}

#about {
    text-align: center;
    padding-bottom: 10px;
}

#projects {
    text-align: center;
    padding-bottom: 20px;
}

#projectlinks li {
    list-style: none;
}

#viewprojects li {
    list-style: none;
    padding: 0 5px;
    display: inline;
}

#viewprojects {
    padding-top: 50px;
}

#skills {
    padding-bottom: 30px;
    text-align: center;
}

#testimonial {
    padding-bottom: 20px;
}

.wrapper {
    min-height: 90vh;
}
.wrapper img{
    display: block;
    margin: 15px auto;
    width: 30em;
}
.wrapper p {
    text-align: center;
}

#projects a {
    padding: 0 5px;
}

.project-tile {
    text-shadow: 0 0 8px black;
}

.about-par{
    text-align: start;
}
#social-media a {
    padding: 0 5px;
}

#contact {
    padding-bottom:20px;
}

.info {
    text-align: center;
}

#social-media {
    text-align: center;
    padding-bottom: 20px;
}

.img {
    border-radius: 50%;
}

.flip-box {
    background-color: transparent;
    width: 500px;
    height:500px;
    perspective: 1000px;
    border-radius: 50%;
    margin: auto;
}
  
.flip-box-inner {
    position: relative;
    width: 100%;
    height: 100%;
    transition: transform 0.8s;
    transform-style: preserve-3d;
}
  
.flip-box:hover .flip-box-inner {
    transform: rotateY(180deg);
}
  
.flip-box-front, .flip-box-back {
    position: absolute;
    width: 100%;
    height: 100%;
    -webkit-backface-visibility: hidden;
    backface-visibility: hidden;
}

.flip-box-back {
    background-color: gold;
    color: black;
    transform: rotateY(180deg);
    border-radius: 50%;
    padding-top: 225px;
    text-align: center;
}

#picture {
    background-attachment: fixed;
    background-repeat: no-repeat;
    background-size:cover;
}

#M1I0B_ {
    padding: 0 5px;
    text-decoration: none;
}

#imo {
    display: block;
    padding-top: 10px;
}

#myName {
    padding-top: 30px;
    font-size: 50px;
}

.home_extra {
    text-align: center;
    padding-top: 50px;
}

.form-label {
    padding-top: 15px;
}

#cards_ {
    border: 1px solid;
    padding: 10px;
    box-shadow: 5px 10px;
}

#btn_ {
    border: 1px solid;
    padding: 10px;
    box-shadow: 1px 5px;
}

#about1_ {
    border: 1px solid;
    box-shadow: 5px 10px;
    padding: 20px;
}

main {
    background: url(https://i.postimg.cc/DzDVmKRH/wallpaper4.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
    width: 100%;
}

label {
    color: gold;
}

@media screen and (max-width:300px) {
    body {
    width: 100%;
    }
}

.waviy {
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
    font-family: 'Gemunu Libre', sans-serif;
  }
  .waviy span {
    position: relative;
    display: inline-block;
    font-size: 80px;
    color: gold;
    text-transform: uppercase;
    animation: flip 2s infinite;
    animation-delay: calc(.2s * var(--i))
  }
  @keyframes flip {
    0%,80% {
      transform: rotateY(360deg) 
    }
  }
</style>

<template>
    <div class="footer  footer-Color">
        <div class="font textDecoRemover">
            <div class="footer-Color">
                <div class="">
                    <img class="align-center fadeIn" src="../assets/Skull.png" height="35px">
                </div>
                <div class="hrTitle1 align-center">
                    <span class="hrTitle">Footer Stuff</span>
                </div>
                <div class="icon-container2">
                    <div class="icon-Space click-Icons" id ="youtube"></div>
                    <div class="icon-Space click-Icons" id ="twitter"></div>
                    <div class="icon-Space click-Icons" id ="facebook"></div>
                    <div class="icon-Space click-Icons" id ="instagram"></div>
                </div>
            </div>
            <div>
                <div class="container">
                    <div class="align-center">
                        <ul>
                            <li><p class="header">* About *</p></li>
                            <li><a class="smallText" href="https://rsbuddy.com/exchange">Another Link</a></li>
                            <li><a class="smallText" href="https://www.reddit.com/r/2007scape/">Another link</a></li>
                        </ul> 
                    </div>
                    <div class="align-center">
                        <ul>
                            <li><p class="header">* Locations *</p></li>
                            <li><a class="smallText" href="https://rsbuddy.com/exchange">Another Link</a></li>
                            <li><a class="smallText" href="https://www.reddit.com/r/2007scape/">Another link</a></li>
                        </ul> 
                    </div>
                    <div class="align-center">
                        <ul>
                            <li><p class="header">* News and updates *</p></li>
                            <li><a class="smallText" href="https://rsbuddy.com/exchange">Another Link</a></li>
                            <li><a class="smallText" href="https://www.reddit.com/r/2007scape/">Another link</a></li>
                        </ul> 
                    </div>                
                    <div class="align-center">
                        <ul>
                            <li><p class="header">* Information *</p></li>
                            <li><a class="smallText" href="https://rsbuddy.com/exchange">Another Link</a></li>
                            <li><a class="smallText" href="https://www.reddit.com/r/2007scape/">Another link</a></li>
                        </ul> 
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css?family=Titillium+Web');

.icon-container2 {
    display: flex; 
    flex-direction: row; 
    flex: 1; 
    align-items: center; 
    justify-content: center;   
    background-color: #25272b;
}

.icon-Space {
    margin: 10px;
}

.footer {
  width: 100%;
  left: 0; 
  position: absolute;
  bottom: 0;
  width: 100%;
  height: 20px;
  margin-bottom: -500px;
}


.font {
    line-height: 18px;
    letter-spacing: normal !important;
    font-family: "Titillium Web", Circular, -apple-system, BlinkMacSystemFont, Roboto,
    "Helvetica Neue", sans-serif;
    color: #ffff;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}

.container {
    border: 2px solid #73AD21;
    display: flex; 
    flex-direction: row; 
    flex: 1; 
    background-color: #25272b;
}

a {
  color: silver;
  text-decoration: none;
}

a:hover {
border-bottom: 2px solid red;
}

ul a { display: block;}

ul { list-style-type: none;}

li { cursor: pointer;}

.textDecoRemover {text-decoration: none;}

.click-Icons { cursor: pointer;}

.align-center {
    display: block;
    margin: 1.0em auto;
    text-align: center;
}

.smallText {
    font-size: 11px;
}

.footer-Color {
    background-color: #25272b;
}

.header {
    font-weight: bold;
    font-size: 17px;
    line-height: 30px;
}

.topText {
    font-size: 22px;
}

.hrTitle {
    font-size: 28px;
    background-color: #25272b; padding: 0 50px;
}

.hrTitle1 {
    width: 90%;
    height: 10px;
    border-bottom: 1px solid white;
    text-align: center;
}


.fadeIn {
    -webkit-animation-duration: 1500ms;
    animation-name: fadeIn;
    -webkit-animation-name: fadeIn;
    animation-duration: 1500ms;
    animation-iteration-count: infinite;
}

@keyframes fadeIn {
    0%,100% {opacity: 0;}
    30%, 80% {opacity: 1;}
}

@-webkit-keyframes fadeIn {
    0%,100% {opacity: 0;}
    30%, 80% {opacity: 1;}
}

#youtube {
    background-image: url('../assets/youtube dark.png');
    background-repeat: no-repeat;
    height: 64px;
    width: 64px;
}

#youtube:hover {
    background-image: url('../assets/youtube white.png');
    background-repeat: no-repeat;
    height: 64px;
    width: 64px;  
}

#facebook {
    background-image: url('../assets/facebook dark.png');
    background-repeat: no-repeat;
    height: 64px;
    width: 64px;
}

#facebook:hover {
    background-image: url('../assets/facebook white.png');
    background-repeat: no-repeat;
    height: 64px;
    width: 64px;  
}

#twitter {
    background-image: url('../assets/twitter dark.png');
    background-repeat: no-repeat;
    height: 64px;
    width: 64px;
}

#twitter:hover {
    background-image: url('../assets/twitter white.png');
    background-repeat: no-repeat;
    height: 64px;
    width: 64px;  
}

#instagram {
    background-image: url('../assets/instagram dark.png');
    background-repeat: no-repeat;
    height: 64px;
    width: 64px;
}

#instagram:hover {
    background-image: url('../assets/instagram white.png');
    background-repeat: no-repeat;
    height: 64px;
    width: 64px;  
}
</style>

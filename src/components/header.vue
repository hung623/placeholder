<template>
    <div class="">
        <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.1/css/all.css" integrity="sha384-50oBUHEmvpQ+1lW4y57PTFmhCaXp0ML5d60M1M7uH2+nqUivzIebhndOJK28anvf" crossorigin="anonymous">
        <div class="">
            <div class="font">
                <ul>
                    <a href="/"><img class="logo" src="../assets/logo.png">WTB</a>
                    <li class="links link-Float"><a href="#page">Shop <i class="fas fa-gift"></i></a></li>
                    <button class="links link-Float" @click="scrollBottom">Social medias</button>
                    <li class="links link-Float"><a href="#page">placeholder</a></li>
                    <li class="links link-Float"><a href="#page">placeholder</a></li>
                </ul>            
            </div>
            <hr/>
            <div class="content">  
            </div>
        </div>
    </div>
</template>


<style scoped>
.links {
    padding: 20px;    
    display: inline-block;
}

.link-Float{
    float: right;
}

a {
  color: black;
  text-decoration: none;
}

ul { list-style-type: none;}

li { 
    cursor: pointer;
}

.font {
    line-height: 20px;
    letter-spacing: normal;
    font-family: "Titillium Web", Circular, -apple-system, BlinkMacSystemFont, Roboto,
    "Helvetica Neue", sans-serif;
    color: #ffff;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}

.logo {
    height: 45px;   
}

button {
    border-style: none;
    background: none;
	border: none;
	padding: 0;
	font: inherit;
	cursor: pointer;
	outline: inherit;
}

</style>

<script>
export default {
    methods: {
        scrollBottom: function(){
            window.scrollTo(0,280);
        },
    }
}   
</script>


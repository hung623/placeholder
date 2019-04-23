<template>
    <div class="other">
        <div class="content wrapper">
            <div id="content" class="sections font">
                <button class="float" v-on:click="nightMode"><i class="far fa-moon"></i></button>
                <div>
                    <p>Html begreper</p>
                    <h1 v-if="begrep == 'html'">Im HTML begreper</h1>
                </div>
                <button v-on:click="begreper('html')">Show Html begreper</button>
                <p>ASDASDDASDAD</p>
                <p>ASDASDDASDAD</p>
                <p>ASDASDDASDAD</p>
                <p>ASDASDDASDAD</p>
            </div>
        </div>
    </div>  
</template>

<script>
export default {
    data: function() {
        return {
            begrep: "",
            };
        },
    methods: {
        nightMode: function(){
            window.scrollTo(0,880);
        },
        begreper: function(begrep) {
            this.begrep = begrep;
        }
    }
}   
</script>



<style scoped>



.sections{
    padding: 1rem;
    border-radius: 5px;
    border: 1px solid black;
    padding-bottom: 50px;
}

p:hover {
    text-decoration: none !important;
    color: #90ee90;
    background: white;
}

.float {
    position: relative;
}

.border {
    background: #eee;
    padding: 1rem;
    height: 780px;
    -webkit-box-shadow: 1px 2px 10px 1px rgba(0,0,0,0.54);
    -moz-box-shadow: 1px 2px 10px 1px rgba(0,0,0,0.54);
    box-shadow: 1px 1px 10px 1px rgba(0,0,0,0.54);
    flex: row;
}

div.content {
  width: 800px;
  margin: 0 auto;
} 

.font {
    font-size: 20px;
    letter-spacing: normal;
    font-family: "Titillium Web", Circular, -apple-system, BlinkMacSystemFont, Roboto,
    "Helvetica Neue", sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    
}

.wrapper {
  align-items: center;
  justify-content: center;
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
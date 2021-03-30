<template>
  <div class="HeaderAll">
    <header class="MenuSelection flex ">

      <div class="Cabecalho flex ">

            <div class="LogoHim flex">
              <a class="LogoBusiness flex" href="">
                    <div class="Logo"></div>
                  <div class="CenterLogo">
                    <h1 class="LogoWhrite">fitnessgym</h1>
                    <h2 class="TagLine">Your Tagline here</h2>
                </div>
              </a>
            </div>

            <nav class="SideBar flex">
              <ul class="ListNav flex">
                <li><a href="">HOME</a></li>
                <li><a href="">ABOUT</a></li>
                <li><a href="">SHOP</a></li>
                <li><a href="">CONTACT</a></li>
              </ul>
            </nav>

      </div>
    </header>

    <section class="SectionBuy flex flex-direction-column">

      <div class="TextCenter flex flex-direction-column">
        <h2 class="neon"> SPORT</h2>
        <p class="TextPress">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eaque, earum quidem ab, obcaecati sapiente optio dolorem nemo commodi qui doloribus quaerat, vitae nihil. Rem culpa nobis, eum numquam laboriosam et.</p>
      </div>

      <div class="ButtonHead flex">
         <a href="">READ MORE</a> 
      </div>
    </section>

  </div>
</template>

<script>
export default {
  name: 'Header',
}
</script>


<style scoped>

.HeaderAll {
  background-image: url("../assets/backgroundHeader.png");
  background-repeat:no-repeat ;
  background-size:cover; 
  height: 100vh;
}

.Cabecalho{
  justify-content: space-between;
  background-color: black;
  margin-top: 20px; 
  height: 55px;
  width: 100%;  
}
.LogoBusiness{
  justify-content: center;
  align-items: center;

}
.LogoHim{
  justify-content: center;
  flex: 1;
}
.Logo{
  background-image: url('../assets/LogoGym.png');
  background-repeat:no-repeat; 
  margin-top: 8px;
  height: 56px;
  width: 56px;  
}
h1, h2{
  padding: 0;
  margin: 0;
}
.LogoWhrite{
  background: linear-gradient(to right, white 65%, #00c0ff 50%);
  font-family: Raleway, 'Open Sans';
  -webkit-background-clip: text;
  text-transform: uppercase;
  background-clip: text;
  display: inline-block;
  color: transparent;
  font-weight: 700;
  font-size: 1.6em;	
	
}
.TagLine{
  font-family: Raleway, 'Open Sans';
  text-transform: uppercase;
  text-align: center;
  font-size: 0.6em;
  font-weight: 400;
  color: white;
}
.SideBar {
  flex: 2;
}

ul{
  justify-content: space-evenly;
  align-items: center;
  list-style: none;
  height: 100%;
  width: 100%;
  padding: 0;
  margin: 0;
}
.ListNav > li > a{
  font-family: Raleway, 'Open Sans';
  text-transform: uppercase;
  color: #00c0ff;
  font-weight: 500;
  font-size: 1.0em; 
}
.SectionBuy{
  height: 80%;
  justify-content: center;
  align-items: center;
  justify-content: space-evenly;

}
.TextCenter{
  justify-content: center;
  align-items: center;
}
.neon{
  font-family: Raleway, 'Open Sans';
  font-weight: 700;
  font-size: 9.0rem;
  color: transparent;
  text-shadow: 0 0 10px rgba(192, 185, 185, 0.164);
  -webkit-text-stroke-width: 2px;
  -webkit-text-stroke-color: white;
}
.TextPress{
  font-family: Raleway, 'Open Sans';
  font-weight: 400;
  color: white;
  margin:0 auto ;
  width: 33%;
  text-align: center;
}

.ButtonHead{
  background-color: rgba(255, 255, 255, 0.911);
  width: 15%;
  height: 8%;
  align-items: center;
  justify-content: center;
  border-radius: 15px;

}
.ButtonHead> a{
  color: #00c0ff;
  font-family: Raleway, 'Open Sans';
  font-weight: 700;
  font-size: 1.0em;
  text-align: center;
}
</style>

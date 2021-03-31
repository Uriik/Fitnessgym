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


<style >





.HeaderAll {
  background-image: url("../assets/backgroundHeader.png");
  background-repeat:no-repeat ;
  background-size:cover; 
  background-position:center top;
  height: 100vh;
  
}
.SideBarListaMob, .ListNavListaMob{
  display: none;
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
  justify-content: space-evenly;
  align-items: center;
  height: 80%;
}
.TextCenter{
  justify-content: center;
  align-items: center;
}
.neon{
  text-shadow: 0 0 10px rgba(192, 185, 185, 0.164);
  -webkit-text-stroke-color: white;
  font-family: Raleway, 'Open Sans';
  -webkit-text-stroke-width: 2px;
  color: transparent;
  font-size: 9.0rem;
  font-weight: 700; 
}
.TextPress{
  font-family: Raleway, 'Open Sans';
  text-align: center;
  font-weight: 400;
  color: white;
  margin:0 auto ;
  width: 33%;  
}

.ButtonHead{
  background-color: rgba(255, 255, 255, 0.911);
  justify-content: center;
  border-radius: 15px;
  align-items: center;
  height: 8%;
  width: 15%;
}
.ButtonHead> a{
  font-family: Raleway, 'Open Sans';
  text-align: center;
  color: #00c0ff;
  font-weight: 700;
  font-size: 1.0em;
}

/* ================================= MEDIA QUERY========================================== */


@media (max-width: 1024px){

  .HeaderAll{
    background: rgb(0, 0, 0);
    height: auto;
    padding: 5%;
  }
  .neon{
    font-size:4.5rem ;
  }
  .CenterLogo{
    display: none;
  }
  .TextPress{
    width: auto;
    margin-bottom:5% ;
  }
  .LogoHim{
    justify-content: flex-start;
  }
  .SideBar{
    flex: 3;
  }
  .ButtonHead{
    height: 50px;
    width: 50%;
  }
.SectionBuy{
  justify-content: space-evenly;
}
.neon{
  margin-bottom:3% ;
}
.TextCenter{
  margin: 5% 0 5% 0;
}

}












/* ================================= MEDIA QUERY========================================== */
</style>

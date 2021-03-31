<template>
    <div class="SectionExactly">

        <div class="SectionExacHand flex flex-flow-column">
            <div class="TitleExac flex flex1">

                <h3 class="TitleEx">what exactly do we do</h3>
                <p class="TextEx">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt perspiciatis culpa consectetur ratione beatae? Maiores ea inventore quasi numquam obcaecati. Consequuntur minus consectetur necessitatibus magni pariatur a, temporibus veritatis eveniet.</p>

                <ul class="ListCheck flex">
                    <a href=""><li>Projects</li></a>
                    <a href=""><li>Travel</li></a>
                    <a href=""><li>Mission</li></a>
                    <a href=""><li>Photos</li></a>
                </ul>

            </div>


            <div class="IconsExact flex flex2">

            <div class="CardComp flex flex-direction-column">
                <span class="CellPhone"></span>
                <h4 class="TitleCardComp">COMPANY</h4>
                <p class="TextCardComp">"Lorem ipsum dolor sit amet consectetur adipisicing elit., tempora quaerat consequuntur."</p>
                <h5 class="NameComp">ADAM JOHNS <span class="CompManager flex">acount manager</span></h5>
            </div>

            <div class="CardComp flex flex-direction-column">
                <span class="SupinoHard"></span>
                <h4 class="TitleCardComp">COMPANY</h4>
                <p class="TextCardComp">"Lorem ipsum dolor sit amet consectetur adipisicing elit., tempora quaerat consequuntur."</p>
                <h5 class="NameComp">ADAM JOHNS <span class="CompManager flex">acount manager</span></h5>
            </div>

            <div class="CardComp flex flex-direction-column">
                <span class="PesoHero"></span>
                <h4 class="TitleCardComp">COMPANY</h4>
                <p class="TextCardComp">"Lorem ipsum dolor sit amet consectetur adipisicing elit., tempora quaerat consequuntur."</p>
                <h5 class="NameComp">ADAM JOHNS <span class="CompManager flex">acount manager</span></h5>
            </div>

            </div>
        </div>



        <div class="SectionExacBot flex flex-direction-column">
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nisi ad perferendis minus distinctio quaerat ullam doloribus aut laudantium inventore. Atque sed accusantium ipsa quod molestiae minima asperiores laboriosam fuga dolor?</p>
            <p>David Johnson</p>
        </div>
    </div>
</template>

<script>
export default {
  name: 'SectionExac',
}
</script>
<style scoped>

h1, h2, h3, h4, h5, p {
    padding: 0;
}

.SectionExactly{
    height: 100vh;
    box-sizing: border-box;
}
.SectionExacHand{
    background-color: black;
    height: 85vh;
    
}

.SectionExacBot{
    background-color: #222222;
    height: 15vh;
    
}
.TitleExac{
    flex-flow: column;
    justify-content: space-evenly;
}
.TitleEx{
    color: #00c0ff;
    font-size: 1.0rem;
    font-family: Raleway, 'Open Sans'; 
    font-weight: 700; 
    text-transform: uppercase;
    text-align: center;

}
.TextEx{
    color: #00c0ff;
    font-size: 1.0rem;
    font-family: Raleway, 'Open Sans'; 
    font-weight: 300;
    text-align: center;
    padding:0px 8.0em 0 8.0em ;
}
a{
    color: #00c0ff;
    font-size: 1.0rem;
    font-family: Raleway, 'Open Sans'; 
    font-weight: 300;    
}

.ListCheck {
    justify-content: space-around;
    align-items: center;
    flex-flow: row;
    list-style: none;
    padding: 0;
    margin: 0;
}

.IconsExact{
    align-items: flex-end;
    justify-content: center;
    justify-content: space-evenly;
}


.CellPhone{
    align-self: center;
    width: 3.8em;
    height: 6.6em;
    background-image: url('../assets/CellPhone.png');
    background-repeat: no-repeat;
}
.SupinoHard{
        align-self: center;
    width: 4.9em;
    height: 6.7em;
    background-image: url('../assets/SupinoHard.png');
    background-repeat: no-repeat;
}
.PesoHero{
    align-self: center;
    width: 4.9em;
    height: 6.7em;
    background-image: url('../assets/PesoHero.png');
    background-repeat: no-repeat;
}

.CardComp{
    width: 15vw;
    height: 50vh;
    margin: 5px;
    padding: 5px;
    text-align: center;
    justify-content: space-around;
    box-sizing: border-box; 
}
.CardsCompanyTwo {
    height: 35vh;
    box-sizing: border-box;
    justify-content: center;
    padding: 5px;
}
h4  p h5{
    box-sizing: border-box; 
        font-family: Raleway, 'Open Sans'; 
}
h5{
    margin: 25px 0 0 0;
    text-align: bottom;
}
.TitleCardComp{
    color: white;
    font-size: 1.0rem;
    font-weight: 600; 
    font-family: Raleway, 'Open Sans'; 
}
.TextCardComp{
    color: white;
    font-size: 0.7rem;
    font-weight: 300; 
    font-family: Raleway, 'Open Sans'; 
}
.CompManager{
    justify-content: center;
    color:white ;
    font-weight: 300; 
    font-family: Raleway, 'Open Sans';
}
.NameComp{
    color:white ;
    font-weight: 600; 
    font-family: Raleway, 'Open Sans';
}

.SectionExacBot{
    color:#00c0ff;
    font-size: 0.8em;
    font-weight: 300; 
    font-family: Raleway, 'Open Sans';
    justify-content: space-evenly;
    text-align: center;
    padding:0px 8.0em 0 8.0em ;
}
@media (max-width: 1024px){
    .SectionExactly{
        height: auto;

    }
    .TextEx{
        padding: 0 0 0 0;
         margin: 5% 0 5% 0;
    }
    .TitleEx{
        margin: 5% 0 5% 0;
    }
    .TitleExac{
        margin: 5% 0 5% 0;
        padding: 5%;
    }
    .IconsExact{
        flex-direction: column;
        height: auto;
        align-items: center;
    }
    .SectionExacHand{
        height: auto;
    }
    .SectionExacBot{
        height: auto;
        padding: 5%;
    }

    .CardComp{
        width: auto;
        height: auto;
    }
    .CellPhone{
        height: 8.5rem;
    }
}
</style>
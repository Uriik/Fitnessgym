<template>
    <div class="SectionThreeAll">

        <div class="TextOne flex flex-direction-column">
            <h3 class="TextWho">priorities go first</h3>
            <p class="TextInst">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Suscipit voluptates accusamus assumenda doloremque dicta consectetur porro earum error labore? Enim iusto a accusamus ut doloremque ipsa optio cupiditate mollitia perspiciatis?</p>
        </div>

        <div class="CardsCompany flex ">

            <div class="CardComp flex flex-direction-column">
                <h4 class="TitleCardComp">COMPANY</h4>
                <p class="TextCardComp">"Lorem ipsum dolor sit amet consectetur adipisicing elit., tempora quaerat consequuntur."</p>
                <h5 class="NameComp">ADAM JOHNS <span class="CompManager flex">acount manager</span></h5>
            </div>
            <div class="CardComp flex flex-direction-column">
                <h4 class="TitleCardComp">COMPANY</h4>
                <p class="TextCardComp">"Lorem ipsum dolor sit amet consectetur adipisicing elit., tempora quaerat consequuntur."</p>
                <h5 class="NameComp">ADAM JOHNS <span class="CompManager flex">acount manager</span></h5>
            </div>           
            <div class="CardComp flex flex-direction-column">
                <h4 class="TitleCardComp">COMPANY</h4>
                <p class="TextCardComp">"Lorem ipsum dolor sit amet consectetur adipisicing elit., tempora quaerat consequuntur."</p>
                <h5 class="NameComp">ADAM JOHNS <span class="CompManager flex">acount manager</span></h5>
            </div>            
            <div class="CardComp flex flex-direction-column">
                <h4 class="TitleCardComp">COMPANY</h4>
                <p class="TextCardComp">"Lorem ipsum dolor sit amet consectetur adipisicing elit., tempora quaerat consequuntur."</p>
                <h5 class="NameComp">ADAM JOHNS <span class="CompManager flex">acount manager</span></h5>
            </div>           
             <div class="CardComp flex flex-direction-column">
                <h4 class="TitleCardComp">COMPANY</h4>
                <p class="TextCardComp">"Lorem ipsum dolor sit amet consectetur adipisicing elit., tempora quaerat consequuntur."</p>
                <h5 class="NameComp">ADAM JOHNS <span class="CompManager flex">acount manager</span></h5>
            </div>            
            <div class="CardComp flex flex-direction-column">
                <h4 class="TitleCardComp">COMPANY</h4>
                <p class="TextCardComp">"Lorem ipsum dolor sit amet consectetur adipisicing elit., tempora quaerat consequuntur."</p>
                <h5 class="NameComp">ADAM JOHNS <span class="CompManager flex">acount manager</span></h5>
            </div>
        </div>

    </div>
</template>

<script>
export default {
  name: 'SectionThree',
}
</script>

<style scoped>
h3, p{
    margin: 0;
}
.SectionThreeAll{
    background-image: url('../assets/BackgroundAside.png');
    height: 100vh;
    background-repeat:no-repeat ;
    background-size:cover; 
    box-sizing: border-box;
}
.TextOne{
    min-height: 20vh;
    text-align: center;
    align-items: center;
    justify-content: space-evenly;
}
.TextWho{
    color: #00c0ff;
    font-size: 1.5rem;
    font-family: Raleway, 'Open Sans';
    font-weight: 700;
    text-transform: uppercase;
    box-sizing: border-box;
}
.TextInst{
    color: #00c0ff;
    font-size: 1.0rem;
    font-family: Raleway, 'Open Sans'; 
    font-weight: 300;  
    width: 70%; 
}

.CardsCompany{
    max-width: 50vw;
    min-height: 75vh;
    margin: auto;
    flex-wrap: wrap;
    justify-content: center;
}
.CardComp{
    background-color: rgba(0, 0, 0, 0.486);
    width: 15vw;
    height: 35vh;
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

@media (max-width: 1024px){
    .SectionThreeAll{
        background: black;
        height: auto;
        padding: 2%;
        box-sizing: border-box;
    }
    .CardComp{
        background-color:rgb(59, 56, 56) ;
        height: auto;
        width: 100%;
    }
    .CardsCompany{
        max-width: none;
        width: auto;
        height: auto;
        margin:0;
    }
    .TextOne{
        margin: 5% 0 5% 0;
    }
}


</style>
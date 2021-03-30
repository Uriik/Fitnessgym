<template>
    <div class="FooterHero flex flex-direction-column">

        <div class="TextHeroLor flex">
            <div><p class="HeroLorem">Lorem Ipsuim Dolor Sit</p><p class="Trips">Trips / 16th March, 2019</p></div>
            <div><p class="HeroLorem">Lorem Ipsuim Dolor Sit</p><p class="Trips">Trips / 16th March, 2019</p></div>
            <div><p class="HeroLorem">Lorem Ipsuim Dolor Sit</p><p class="Trips">Trips / 16th March, 2019</p></div>
        </div>

        <div class="TextDavid flex flex-direction-column">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Exercitationem sequi veritatis, voluptate molestias nulla, itaque placeat accusantium quis architecto consequuntur nesciunt dolor nemo id? Officia accusantium qui ipsa nesciunt at, consequuntur nesciunt dolor nemo id? Officia accusantium qui ipsa nesciunt at.consequuntur nesciunt dolor nemo id? Officia accusantium qui ipsa nesciunt atconsequuntur nesciunt dolor nemo id? Officia accusantium qui ipsa nesciunt at</p>
            <p> David Johnson</p>
        </div>

        <div class="FooterBar flex">
            <div class="BotLeft flex1 flex flex-direction-column">
                <p class="Abt">About</p>
                <p class="TextBot">Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure adipisci rerum ad autem commodi.consectetur adipisicing elit. Iure adipisci rerum ad autem commodi.</p>
                <ul class="MediaList flex">
                    <a href=""><li><i class="fab fa-facebook"></i></li></a>
                    <a href=""><li><i class="fab fa-instagram-square"></i></li></a>
                    <a href=""><li><i class="fab fa-twitter-square"></i></li></a>
                    <a href=""><li><i class="fab fa-youtube-square"></i></li></a>
                    <a href=""><li><i class="fab fa-snapchat"></i></li></a>
                </ul>
            </div>
                



            <div class="BotAll flex flex2">
                <div class="FooterList flex flex-direction-column">
                    <p class="Abt">About</p>
                    <ul>
                        <a href=""><li>Team</li></a>
                        <a href=""><li>Join us</li></a>
                        <a href=""><li>Ethic</li></a>
                        <a href=""><li>Goals</li></a>
                    </ul>
                </div>
                <div class="FooterList flex flex-direction-column">
                    <p class="Abt">About</p>
                    <ul>
                        <a href=""><li>Team</li></a>
                        <a href=""><li>Join us</li></a>
                        <a href=""><li>Ethic</li></a>
                        <a href=""><li>Goals</li></a>
                    </ul>
                </div>

                <div class="FooterList flex flex-direction-column">
                    <p class="Abt">About</p>
                    <ul>
                        <a href=""><li>Team</li></a>
                        <a href=""><li>Join us</li></a>
                        <a href=""><li>Ethic</li></a>
                        <a href=""><li>Goals</li></a>
                    </ul>
                </div>
            </div>
        </div>
        <div class="ColorFootHero"></div>
    </div>
</template>

<script>
export default {
  name: 'Article',
}
</script>

<style scoped>
    .FooterHero{
        height: 100vh;
    }
    .TextHeroLor{
        background-color: #222222;
        height: 30vh;
        justify-content: space-evenly;
        align-items: center;
    }
    .TextHeroLor p{
        margin: 0;
        padding: 0;
    }
    .Trips{
    color: white;
    font-family: Raleway, 'Open Sans';
    font-weight: 300;
    font-size: 0.7rem;
    text-align: center;
    }
    .HeroLorem{
    color: white;
    font-family: Raleway, 'Open Sans';
    font-weight: 500;
    font-size: 0.9rem;
    text-align: center;        
    }
    .TextDavid p{
        margin: 0;
        padding: 0;
        color: #00c0ff;
        font-family: Raleway, 'Open Sans';
        font-weight: 500;
        font-size: 0.9rem;
        text-align: center;
    }
    .TextDavid{
        background-color: black;
        height: 35vh;
        align-items: center;
        justify-content: center;
        padding: 0 8rem 0 8rem;
        justify-content: space-evenly;
    }
    .FooterBar{
        background-color: #222222;
        height: 36vh; 
    }
    .BotLeft{
        box-sizing: border-box;
        margin-left: 5rem;
    }
    .TextBot{
        box-sizing: border-box;
        width: 20rem;
        color: white;
        font-size: 0.9rem;
        font-weight: 300; 
        font-family: Raleway, 'Open Sans';
    }
    .fab{
        font-size: 1.5rem;
        margin-right:2rem ;
    }
    .MediaList{

        align-items: flex-start;
    }
    .fa-instagram-square .fa-twitter-square .fa-youtube-square{
        border-radius:5px ;
    }

    .ColorFootHero{
        background-color: #00c0ff;
        height: 1vh;
    }
    .BotAll{
        justify-content: space-evenly;
        align-items: center;
        box-sizing: border-box;
        padding: 2rem;
        margin-right: 5rem;
    }
    ul{
        list-style: none;
        padding: 0;
    }
    .list-style{
        list-style: none;
        justify-content: center;
        text-align: center;
    }
    .FooterList, a{
    color: white;
    font-size: 0.9rem;
    font-weight: 300; 
    font-family: Raleway, 'Open Sans'; 
    }
    .Abt{
    color: white;
    font-size: 1.0rem;
    font-weight: 600; 
    font-family: Raleway, 'Open Sans';         
    }
</style>
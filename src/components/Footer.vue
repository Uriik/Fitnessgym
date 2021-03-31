<template>
    <div class="FooterHero flex flex-direction-column">

        <div class="TextHeroLor flex">
            <div class="FootCardLor"><p class="HeroLorem">Lorem Ipsuim Dolor Sit</p><p class="Trips">Trips / 16th March, 2019</p></div>
            <div class="FootCardLor"><p class="HeroLorem">Lorem Ipsuim Dolor Sit</p><p class="Trips">Trips / 16th March, 2019</p></div>
            <div class="FootCardLor"><p class="HeroLorem">Lorem Ipsuim Dolor Sit</p><p class="Trips">Trips / 16th March, 2019</p></div>
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
        justify-content: space-evenly;
        background-color: #222222;
        align-items: center;
        height: 30vh;    
    }
    .TextHeroLor p{
        padding: 0;
        margin: 0;       
    }
    .Trips{
        font-family: Raleway, 'Open Sans';
        text-align: center;  
        font-size: 0.7rem;  
        font-weight: 300;
        color: white;        
    }
    .HeroLorem{
        font-family: Raleway, 'Open Sans';
        text-align: center;
        font-size: 0.9rem;
        font-weight: 500;
        color: white;      
    }
    .TextDavid p{
        font-family: Raleway, 'Open Sans';
        text-align: center;
        font-size: 0.9rem;
        color: #00c0ff;
        font-weight: 500;
        padding: 0;
        margin: 0;  
    }
    .TextDavid{
        justify-content: space-evenly;
        background-color: black;
        justify-content: center;
        padding: 0 8rem 0 8rem;
        align-items: center;
        height: 35vh;   
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
        font-family: Raleway, 'Open Sans';
        box-sizing: border-box;
        font-size: 0.9rem;
        font-weight: 300; 
        color: white;
        width: 20rem;  
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
        box-sizing: border-box;
        align-items: center;

    }
    ul{
        list-style: none;
        padding: 0;
    }
    .list-style{
        justify-content: center;
        text-align: center;
        list-style: none;   
    }
    .FooterList, a{
        font-family: Raleway, 'Open Sans'; 
        font-size: 0.9rem;
        font-weight: 300; 
        color: white;
    }
    .Abt{
        font-family: Raleway, 'Open Sans'; 
        font-size: 1.0rem;
        font-weight: 600; 
        color: white;                
    }
    @media (max-width: 1024px){
        .FooterHero{
            height: auto;
        }
        .TextHeroLor{
            height: auto;
            padding: 5%;
        }
        .FootCardLor{
            margin: 2% 0 2% 0;
        }
        .Trips{
            margin: 5%;
        }
        .TextHeroLor p{
            margin:10% 0 10% 0;
        }
        .TextDavid{
            height: auto;
            padding: 5%;
        }
        .TextDavid p{
            margin: 3% 0 3% 0;
        }
        .FooterBar{
            height: auto;
            flex-direction: column;
            padding: 5%;
        }
        .BotLeft{
            height: auto;
            flex-direction: column;
            margin: 0;
            padding: 5%;
        }
        .BotAll{
            justify-content: space-around;
        }
        .MediaList{
            padding: 1%;
            margin: 0;
            display: flex;
            justify-content: space-around;
        }
        .TextBot{
            width: auto;
            text-align: center;
        }
        .fab{
            margin: 0;
        }
        .Abt{
            text-align: center;
        }
    }
</style>
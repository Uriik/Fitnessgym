<template>
    <div class="ArticleHero flex flex-direction-column">

        <div class="Something flex flex1">
            <div class="TextArticle flex flex1 flex-direction-column">
                <span class="flex flex-direction-column">
                <p class="TitleTxArt">Projects / 20th August</p>
                <h5 class="TitleLorem">Something new has just arrived</h5>
                </span>
                <p class="TextLorem">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim v architecto beatae vitae dicta sunt es. omne essentiale dolor liquam.</p>
            </div>
            <div class="FromPhoto flex flex1">
                <span class="PhotoHasOne flex"></span>
            </div>
        </div>

        <div class="Arrived  flex flex1">
            <div class="TextArticle flex flex1 flex-direction-column">
                <span class="flex flex-direction-column">
                <p class="TitleTxArt">Projects / 20th August</p>
                <h5 class="TitleLorem">Something new has just arrived</h5>
                </span>
                <p class="TextLorem">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim v architecto beatae vitae dicta sunt es. omne essentiale dolor liquam.</p>
            </div>
            <div class="FromPhoto flex flex1">
                <span class="PhotoHasTwo flex"></span>
            </div>
        </div>



        <div class="NewHas  flex flex1">
            <div class="TextArticle flex flex1 flex-direction-column">
                <span class="flex flex-direction-column">
                <p class="TitleTxArt">Projects / 20th August</p>
                <h5 class="TitleLorem">Something new has just arrived</h5>
                </span>
                <p class="TextLorem">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim v architecto beatae vitae dicta sunt es. omne essentiale dolor liquam.</p>
            </div>
            <div class="FromPhoto flex flex1">
                <span class="PhotoHasThree flex"></span>
            </div>
        </div>



    </div>
</template>

<script>
export default {
  name: 'Article',
}
</script>

<style scoped>
    p, h5{
        margin: 0;
        padding: 0;
    }
    .ArticleHero{
        padding: 0 15rem 0 15rem;
        background-color:black;
        box-sizing: border-box;
        height: 100vh;   
    }
    .Something{
        justify-content: center;
    }
    .Arrived {
        flex-direction: row-reverse;
    }
    .TextArticle {
        justify-content: space-evenly;
        align-items: center;
    }
    .TextLorem{
        box-sizing: border-box;
        width: 25rem;
    }
    .PhotoHasOne{
        background-image: url('../assets/PhotoHero1.png') ;
        background-repeat: no-repeat;
        height: 6rem;
        width: 6rem;        
    }
    .PhotoHasTwo{
        background-image: url('../assets/PhotoHero2.png') ;
        background-repeat: no-repeat;
        height: 6rem;
        width: 6rem;
    }
     .PhotoHasThree{
        background-image: url('../assets/PhotoHero3.png') ;
        background-repeat: no-repeat;
        height: 6rem;
        width: 6rem;       
    }
    .FromPhoto{
        justify-content: center;
        align-items: center;        
    }
    .TitleTxArt{
        font-family: Raleway, 'Open Sans';
        text-align: center;
        color: #00c0ff;       
        font-weight: 500;
        font-size: 0.7em;       
    }
    .TitleLorem{
        font-family: Raleway, 'Open Sans';
        text-transform: uppercase;   
        color: #00c0ff;        
        font-weight: 700;
        font-size: 1.1em;            
    }
    .TextLorem{
        font-family: Raleway, 'Open Sans';
        text-align: center; 
        color: #00c0ff;        
        font-weight: 400;
        font-size: 0.8em;               
    }
    @media (max-width: 1024px){
        .ArticleHero{
            height: auto;
            padding: 5%;
            
        }
        .Something, .Arrived, .NewHas{
            height: auto;
            padding: 5% 0 5% 0;
            flex-direction: column;

        }
        .TextLorem{
            text-align: center;
            width: auto;
            margin: 5% 0 5% 0;
        }
        .TitleTxArt{
             margin: 5% 0 5% 0;
        }
      

    }
</style>
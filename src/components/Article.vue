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
        background-color:black;
        height: 100vh;
        box-sizing: border-box;
        padding: 0 15rem 0 15rem ;
    }
    .Something{

        justify-content: center;
    }
    .Arrived {

        flex-direction: row-reverse;
    }
    .TextArticle {
        align-items: center;
        justify-content: space-evenly;
    }
    .TextLorem{
        box-sizing: border-box;
        width: 25rem;
    }
    .PhotoHasOne{
        background-image: url('../assets/PhotoHero1.png') ;
        background-repeat: no-repeat;
        width: 6rem;
        height: 6rem;
    }
    .PhotoHasTwo{
        background-image: url('../assets/PhotoHero2.png') ;
        background-repeat: no-repeat;
        width: 6rem;
        height: 6rem;
    }
     .PhotoHasThree{
        background-image: url('../assets/PhotoHero3.png') ;
        background-repeat: no-repeat;
        width: 6rem;
        height: 6rem;
    }
    .FromPhoto{
        align-items: center;
        justify-content: center;
    }
    .TitleTxArt{
        color: #00c0ff;
        font-family: Raleway, 'Open Sans';
        font-weight: 500;
        font-size: 0.7em;
        text-align: center;
    }
    .TitleLorem{
        color: #00c0ff;
        font-family: Raleway, 'Open Sans';
        font-weight: 700;
        font-size: 1.1em; 
        text-transform: uppercase;       
    }
    .TextLorem{
        color: #00c0ff;
        font-family: Raleway, 'Open Sans';
        font-weight: 400;
        font-size: 0.8em; 
        text-align: center;       
    }
</style>
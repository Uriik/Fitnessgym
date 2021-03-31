<template>
    <div class="SectionHeroArt flex flex-flow-column">

        <div class="SecPhotoText flex">
            <div class="BackBlack flex1">
                <h3 class="TitleAbove">nature is abose all</h3>
                <p class="TextAbove">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Error dolor dolorum quisquam maiores quos beatae doloribus iure dignissimos labore. Cupiditate eos odit ex voluptates nisi tempore laborum saepe ducimus quos.</p>
            </div>
            <div class="BackPhoto flex1">

            </div>
        </div>

        <div class="PhotoAbsArt flex flex-end">
            <h3 class="BuyTk">buy your <span class="flow flex">tickets</span></h3>
            <p class="TextTooBot">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Totam et sit magnam? Vel, explicabo libero. </p>
            <div class="ButtonHead flex">
                    <a href="">HERE</a> 
            </div>
        </div>

    </div>
</template>

<script>
export default {
  name: 'SectionArtc',
}
</script>

<style scoped>
    .SectionHeroArt{
        height: 100vh;
    }

    .BackBlack{
        height: 50vh;
        background-color: black;
        box-sizing: border-box;
        padding: 2em;
    }
    .BackPhoto{
        height: 50vh;
        background-image: url('../assets/PhotoSecFlex.png');
        background-repeat:no-repeat;
        background-size:cover; 
    }
    .PhotoAbsArt {
        height: 50vh;
        background-image: url('../assets/PhotoAbdsArtc.png');
        background-repeat:no-repeat;
        background-size:cover; 
        flex-direction: column;
        box-sizing: border-box;
        padding: 0 4rem 0 4rem;
        justify-content: space-evenly;
    }
    .TitleAbove{
        color:#00c0ff;
        font-size: 2.0em;
        font-weight: 700; 
        font-family: Raleway, 'Open Sans';
        text-transform: uppercase;
        text-align: left;
    }
    .TextAbove{
        color:#00c0ff;
        font-size: 1.0em;
        font-weight: 300; 
        font-family: Raleway, 'Open Sans';    
        text-align: left;
    }
    .BuyTk{
        text-align: end;
        align-items: center;
        font-weight: 700; 
        font-family: Raleway, 'Open Sans';
        text-transform: uppercase;
        color: white;
        font-size: 2.0em;
        margin:0 0 0 0 ;
    }
    .flow{
        justify-content: flex-end;
    }
    .TextTooBot{  
        font-family: Raleway, 'Open Sans';
        text-align: right;
        font-weight: 400; 
        width: 15rem;
        margin: 0;
        box-sizing: border-box;
        color: white;
    }

    .ButtonHead{
        background-color: rgba(255, 255, 255, 0.911);
        width: 10%;
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

@media (max-width: 1024px){

    .SectionHeroArt{
        height: auto;
        
    }
    .BackBlack{
        height: auto;
    }
    .SecPhotoText{
        flex-direction: column;
    }
    .BackPhoto{
    background-image: none;
    }
    .PhotoAbsArt{
        height: auto;
        padding: 5% ;
        background: #222222;
        align-items: center;
    }
    .ButtonHead{
        height:50px ;
        width: 50%;
    }
    .BuyTk{
        text-align: center;
        margin: 5% 0 5% 0;
    }
    .flow{
        justify-content: center;
        text-align: center;
    }
    .TextTooBot{
          margin: 5% 0 5% 0;
          text-align: center;
    }
    .BackBlack{
        padding: 5%;
    }
}
</style>
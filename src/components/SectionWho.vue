<template>
    <div class="SectionWho flex flex-direction-column">

       <div class="TextOne flex flex-direction-column">
            <h2 class="TextWho">who are we</h2>
            <p class="TextInst">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Porro cupiditate excepturi sequi iure. Est commodi, modi id, quisquam odio distinctio nisi atque sequi doloremque tempora dignissimos consectetur vitae. Fugiat, eveniet.Lorem ipsum dolor sit, amet consectetur adipisicing elit. Porro cupiditate excepturi sequi iure. Est commodi, modi id, quisquam odio distinctio nisi atque sequi doloremque tempora dignissimos consectetur vitae. Fugiat, eveniet.Lorem ipsum dolor sit, amet consectetur adipisicing elit. Porro cupiditate excepturi sequi iure. Est commodi, modi id, quisquam odio distinctio nisi atque sequi doloremque tempora dignissimos consectetur vitae. Fugiat, eveniet.</p>
       </div>

        <div class="TextTwo flex">
            <span class="CardsWho">
            <h3 class="TextCard">LOREM IPSUM DOLOR</h3>
            <p class="TextOfCards">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Dolorem sequi illo suscipit incidunt quibusdam necessitatibus at similique velit reprehenderit esse fuga repellat saepe eaque temporibus, exercitationem doloremque dolores architecto commodi.</p>
            </span>

            <span class="CardsWho">
            <h3 class="TextCard">LOREM IPSUM DOLOR</h3>
            <p class="TextOfCards">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Dolorem sequi illo suscipit incidunt quibusdam necessitatibus at similique velit reprehenderit esse fuga repellat saepe eaque temporibus, exercitationem doloremque dolores architecto commodi.</p>
            </span>

            <span class="CardsWho">
            <h3 class="TextCard">LOREM IPSUM DOLOR</h3>
            <p class="TextOfCards">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Dolorem sequi illo suscipit incidunt quibusdam necessitatibus at similique velit reprehenderit esse fuga repellat saepe eaque temporibus, exercitationem doloremque dolores architecto commodi.</p>
            </span>
            

        </div>
    </div>
</template>


<script>
export default {
  name: 'SectionWho',
}
</script>

<style scoped>
h2, p{
    margin: 0;
}

.SectionWho{
    height: 100vh;
}
.TextOne{
    height: 50vh;
    background-color: black;
    text-align: center;
    align-items: center;
    justify-content: center;
    justify-content: space-evenly;
}
.TextWho{
    color: #00c0ff;
    font-size: 2.0rem;
    font-family: Raleway, 'Open Sans';
    font-weight: 700;
    text-transform: uppercase;
}
.TextInst{
    color: #00c0ff;
    font-size: 1.0rem;
    font-family: Raleway, 'Open Sans'; 
    font-weight: 300;  
    width: 90%; 
}

.TextTwo {
    background-color: #222222;
    height: 50vh;
    align-items: center;
    padding: 50px;
}
.CardsWho{
    padding: 20px;
}

.TextCard, .TextOfCards{
    color: white;
    font-family: Raleway, 'Open Sans'; 
}
.TextOfCards{
    font-size: 0.9rem;
}

</style>
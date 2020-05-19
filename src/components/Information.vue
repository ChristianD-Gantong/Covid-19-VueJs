<template>
    <div class="Information-div">
        <h1> {{Title}} </h1>
        <p class="p1">{{prag1}}</p>
        <p class="p2">{{prag2}}</p>
        <p class="p3">{{prag3}}</p>
        <p class="p4">{{prag4}}</p>
    </div>
</template>

<script>
export default {
    data(){
        return{
            Title: "What is COVID-19?",
            prag1: "The coronavirus disease (COVID-19) is an infectious disease caused by a new strain of coronavirus. This new virus and disease are unknown before the outbreak began in Wuhan, China, in December 2019.\n",
            prag2: "Most people infected with the COVID-19 virus will experience mild to moderate respiratory illness and recover without requiring special treatment. Older people, and those with underlying medical problems are more likely to develop serious illness.",
            prag3: "On 30 January 2020, the Philippine Department of Health reported the firstcase of COVID-19. On 7 March, the first local transmission of COVID-19 was confirmed. ",
            prag4: "At this time, there are no specific vaccines or treatments or COVID-19. However, there are many ongoing clinical trials evaluating potential treatments."
        }
    }   
}
</script>

<style>
@media only screen and (min-width: 1024px){
    h1{
        position: relative;
        text-align: center;
        margin-bottom: 3.5%;
        font-family: Roboto;
        font-style: normal;
        font-weight: normal;
        font-size: 5em;
        line-height: 1em;
        color: #146A97;
    }
    .p1, .p2, .p3{
        position: relative;
        float:left;
        width: 40%;
        margin-left: 8%;
        font-family: Roboto;
        font-style: normal;
        font-weight: lighter;
        font-size: 1.5em;
        line-height: 2em;
        color: #FCFCFC;
    }
    .p4{
        position: relative;
        float: left;
        margin-top: 3%;
        width: 40%;
        margin-left: 8%;
        font-family: Roboto;
        font-style: normal;
        font-weight: 300;
        font-size: 1.5em;
        line-height: 2em;
        color: #FCFCFC;
    }
}
</style>
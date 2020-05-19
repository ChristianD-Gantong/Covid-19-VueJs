<template>
    <div class="Prevention-Div">
        <p class="title">{{PreventionTitle}}</p>
        <p class="subtitle">{{Subtitle}}</p>

        <img src="../assets/Rectangle-Prevent-Des.png" alt="rectangle" class="recDesign">
        <img src="../assets/Design Rectangle.png" alt="anotha rectangle" class="inner-Rec">
        <img src="../assets/Rectangle 2.png" alt="anotha rectangle here" class="Rect-Left">
        <ol>
            <li> STAY<span class="descript"> At home as much as you can</span></li>
            <li> KEEP<span class="descript"> a safe distance</span></li>
            <p class="subtitle2">{{Subtitle2}}</p>
            <li> WASH<span class="descript"> hands often</span></li>
            <li> COVER<span class="descript"> your cough</span></li>
            <li> SICK?<span class="descript"> call ahead</span></li>
            
        </ol>

    </div>
</template>

<script>
export default {
    data(){
        return{
            PreventionTitle: "C O V I D - 1 9 Prevention",
            Subtitle: "Help stop Coronavirus",
            Subtitle2: "The best way to prevent and slow down transmission is be well informed about the COVID-19 virus" 
        }
    }
}
</script>

<style>
@media only screen and (min-width: 1024px){
    .Prevention-Div{
        margin-top: 15%;
        float:left;
    }
    .title{
        position: relative;
        float: left;
        width:60%;
        left: 4%;
        margin-bottom: 0;
        font-family: Roboto;
        font-style: normal;
        font-weight: 100;
        font-size: 6.5em;
        line-height: 1.2em;
        color: #146A97;
    }
    .subtitle{
        float: left;
        position: relative;
        margin-top: 0%;
        width: 53%;
        left:4%;
        font-family: Roboto;
        font-style: normal;
        font-weight: 200;
        font-size: 3.8em;
        line-height: 1.5em;
        color: #FFFFFF;
    }
    .recDesign{
        z-index: -2;
        position: absolute;
        right: 0;
        margin-top: 5%;
        width: 55%;
        height: 1000px;
    }
    .inner-Rec{
        z-index: -1;
        margin-top: 15%;
        position: absolute;
        right:0;
        width:  50%;
    }
    .Rect-Left{
        position: relative;
        float: left;
        width: 48%;
        height: 400px;
        margin-top: 0%;
    }
    ol{
        display:inline-block;
        width: 40%;
        margin-top: 0;
    }
    li{
    font-family: Roboto;
    font-style: normal;
    font-weight: 300;
    font-size: 3em;
    line-height: 1.5em;
    color: #FFFFFF;
    }
    .descript{
        color: #146A97;
    }
    .subtitle2{
        position: absolute;
        margin-top: 0;
        left: 1.5%;
        font-family: Roboto;
        font-style: normal;
        width: 45%;
        font-weight: 300;
        font-size: 3em;
        line-height: 1.5em;
        color: #FFFFFF;
    }
}
</style>

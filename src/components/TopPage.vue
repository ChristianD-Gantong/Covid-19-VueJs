<template>
    <div class="top">
        <img src="../assets/WhoLogo.png" alt="WHO-Logo" class="ImgLogo">
        <img src="../assets/Ellipse.png" alt="Circle" class="Circle">
         <pre><p class="slogan">{{TopSlogan}} </p></pre>
         <p class="quote">{{parag}}</p>
    </div>
</template>

<script>
export default {
    data(){
        return{
            TopSlogan: "STAY HOME.\nSAVE LIVES.",
            parag: "We need to learn the lessons that are being shown from this virus"
        }
    }   
}
</script>


<style>
@media only screen and (min-width: 1024px){
    .top{
        margin-bottom: 35%;
    }
    .ImgLogo{
        position: relative;
        width: 25%;
        left: 1%;
        margin-top: 1%;
    }
    .slogan{
        left: 4%;
        margin-bottom: 2%;
        margin-top: 3%;
        position: relative;
        width: 50%;
        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 8em;
        line-height: 1em;
        color: #FBF2F2;
    }
    .quote{
        width: 50%;
        margin-left: 4%;
        position: relative;
        font-family: Roboto;
        font-style: normal;
        font-weight: normal;
        font-size: 3em;
        line-height: 1.5em;
        color: #146A97;
    }
    .Circle{
        position: relative;
        float: right;
        margin-top: 2%;
        width: 42%;
    }
}
/* @media only screen and (max-width: 1023px){
.slogan{
    font-size: 250%;
    color: red;
    position: relative;
    width: 180px;
    height: 91px;
    left: 28px;
    top: 57px;
    }
    } */
</style>
<template>
    <div class="searchbox">
        <div class="search-input">

            <img src="https://uploads-ssl.webflow.com/5f127ac8860f158e650f06b5/5f13618db066ca1a332318d1_home%403x.png"
                 alt="" class="pin">


            <input type="text" id="search-input-box" ref="autocomplete" onfocus="value = ''" maxlength="256"
                   name="field" data-name="Field" placeholder="Enter Your Address" 
                    v-bind:class="{'white': !clicked, 'lightblue': clicked}"
    v-on:click ="clicked = !clicked" required="" autocomplete="on">

        </div>
        <input type="submit" value="Get Inspection" data-wait="Please wait..." class="submit-button">
    </div>
</template>

<script>
    
    export default {
        name: 'Search',

        mounted: function(){
                let gpaInput = document.getElementById("search-input-box");
                this.autocomplete = new window.google.maps.places.Autocomplete(gpaInput);
                this.autocomplete.addListener('place_changed', this.onPlaceChanged);
            },

        methods:{
            onPlaceChanged : function(){
            
            }
        }
   
    }


</script>

<style scoped>

    .searchbox {

        display: flex;
        height: 60px;
        max-width: 500px;
        margin-top: 30px;
        margin-bottom: 100px;
        justify-content: space-between;
        align-items: center;
        border-radius: 50px;
        background-color: #fff;

    }

    .search-input {
        display: flex;
        justify-content: flex-start;
        align-items: center;
        background-color: #fff;
        margin-left: 20px;
        width: 100%;


    }

    .pin {
        background-color: #fff;
        margin-left: 5px;
        height: auto;
        width: 25px;


        vertical-align: middle;

    }

    #search-input-box {


        background-color: #fff;
        margin-left: 10px;
        width: 100%;
        padding: 10px;
        height: 100%;
        border: 0;
        /* border-color:lightblue; */



    }

    .submit-button {
        max-width: 190px;
        min-width: auto;
        padding-right: 20px;
        padding-left: 10px;
        font-size: 14px;
        height: 45px;
        margin-right: 10px;
        border-radius: 22px;
        background-color: #017afe;
        font-family: sans-serif;
        font-size: 16px;
        color: #fff;
        border: none;
    }


    .text-search-input-box {
        cursor: not-allowed;
        background-color: #eeeeee;

    }

    .image {
        border: 0;
        max-width: 60%;
        margin-left: 0px;
        background-color: #fff;


    }

</style>

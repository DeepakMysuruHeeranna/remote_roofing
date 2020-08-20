<template>
    <div class="head">
    <h1 id="heading-1">{{ msg1 }}</h1>
    <h2 id="heading-2">{{ msg2 }}</h2>

    </div>
</template>

<script>
export default {
    name: 'Headingtext',
    props: {
        msg1 : String,
        msg2 : String
    
  }
    
}
</script>

<style scoped>
.head{
  padding: 0;
}
#heading-2{
  color: #ffffff;
  font-family: AirbnbCerealBold, sans-serif;
  font-size: 20px;
  font-weight: 400;
  margin: 0;
  
  }
  #heading-1{
    font-family: AirbnbCerealLight, sans-serif;
    font-size: 40px;
    color: #fff;
    font-weight: 700;
  }
</style>>

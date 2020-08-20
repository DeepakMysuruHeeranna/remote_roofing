<template>
    <!--Menu with 3 options-->
        <div class="navbar">

            <div class="menu-item">

                <div class="menu-text">
                Home
                </div>

            </div>

            <div class="menu-item">

                <div class="menu-text">
                FAQ
                </div>

            </div>
            
            <div class="menu-item">

                <div class="menu-text">
                Services
                </div> 
                
            </div>
        
        </div>
</template>

<script>
export default {
    name:'Navbar'
    
}
</script>

<style scoped>
.navbar {
  display: flex;
  align-items: center;
  margin-top: 10px;
  height: 60px;
}
.header-logo {
    display: flex;

}
.menu-item {
  
  text-align: center;
  display: flex;
  justify-content: flex-start;
  margin-right: 5%;
  
}
.menu-text{
  font-size: 20px;
  color: #ffffff;
  cursor: pointer;
  font-weight: 400;
  font-family: AirbnbCerealLight, sans-serif;
  width: fit-content;


  
}
.menu-text:hover {
  border-bottom: 2px solid #ffffff;
}
.menu-center {
  font-size: 36px;
  color: #474343bb;
}
</style>
<template>
    <div class="header">
        
        <img src="../assets/logo.png" class="header-logo" alt="LOGO">
        

        <div class="phone-container">

                
        <img src="https://uploads-ssl.webflow.com/5f127ac8860f158e650f06b5/5f1297d1c3fecf36271c10a2_483947%403x.png" alt="" id="phone-icon">
              

                <div class="phone-num-container">
                    <a href="tel:1800-401-7716" id ="num">
                        
                            <strong id="phone-number">1800-401-7716</strong>
                        
                    </a>
                </div>
        </div>

    </div>
</template>

<script>

export default {
    name: 'Header'
    
}
</script>

<style scoped>
.header{
    display: flex;
    justify-content: space-between;
    flex: 1;
    font-weight: 700;
    
}
#num{
    color:#fff;
    text-decoration: none;
    
}
#phone-number{
    max-height: 15px;
    align-self: center;
    font-size: 15px;

    

}
.phone-container{
    display: flex;
    justify-content: space-between;
    margin-right: 20px;
}
#phone-icon{
    max-height: 15px;
    max-width: 15px;
    margin-right: 10px;
    align-self: center;
}
.header-logo{
    height: 30px;
    width: 82px;
}
</style>
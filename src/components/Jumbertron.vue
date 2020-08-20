<template>
    <div class="blue-box">
        <div class="inspect-box">
            <div class="image-container">
                <img src="https://uploads-ssl.webflow.com/5f127ac8860f158e650f06b5/5f1290e8860f155c380f1c02_3039041%403x.png" width="59" alt="" class="image-6">
            </div>

            <div>
                <div class="text-box">Free Inspection</div>
            </div>
        </div>

        <div class="file-box">   
            <div class="image-container">
                <img src="https://uploads-ssl.webflow.com/5f127ac8860f158e650f06b5/5f1293b423e1bd4b2b89c278_2921571%403x.png" width="58" alt="" class="image-7">
            </div>
            <div>
                <div class="text-box">File a Claim</div>
            </div>
        </div>
        <div class="claim-box">
            <div class="image-container">
                <img src="https://uploads-ssl.webflow.com/5f127ac8860f158e650f06b5/5f12939072c6226dbd635684_69886%403x.png" width="57" alt="" class="image-8">
            </div>
        <div>
            <div class="text-box">Replace or Repair a Roof</div>
        </div>
        </div>
    </div>
</template>

<script>
export default {
    name:'Jumbertron'
}
</script>

<style scoped>
.blue-box {
    position: relative;
    display: flex;
    height: 154px;
    padding-right: 40px;
    padding-left: 40px;
    justify-content: space-around;
    align-items: center;
    border-radius: 11px;
    background-color: #0059bf;
    margin-top: 20px;
}
.inspect-box {
    position: relative;
    top: 0px;
    display: flex;
    width: 30%;
    height: 130px;
    padding-right: 20px;
    padding-left: 20px;
    justify-content: center;
    align-items: center;
    border-radius: 11px;
    background-color: #0059bf;
}
.image-container {
    
    display: flex;
    width: 100px;
    margin-right: 0px;
    padding-right: 20px;
    justify-content: flex-end;
    background-color: #0059bf;
}
.image-6 {
    max-height: 60px;
    background-color: #0059bf;
}
.text-box {
    font-family: AirbnbCerealBook, sans-serif;
    color: #fff;
    font-size: 18px;
    font-weight: 400;
    background-color: #0059bf;
}
.file-box {
    position: relative;
    top: 0px;
    display: flex;
    width: 33%;
    height: 130px;
    padding-right: 20px;
    padding-left: 20px;
    justify-content: center;
    align-items: center;
    border-radius: 11px;
    background-color: #0059bf;
}
.image-container {
    display: flex;
    width: 100px;
    margin-right: 0px;
    padding-right: 20px;
    justify-content: flex-end;
}
.image-7 {
    max-height: 62px;
    background-color: #0059bf;
}
.text-box {
    font-family:sans-serif;
    color: #fff;
    font-size: 18px;
    font-weight: 400;
}
.claim-box {
    position: relative;
    top: 0px;
    display: flex;
    width: 33%;
    height: 130px;
    padding-right: 20px;
    padding-left: 20px;
    justify-content: center;
    align-items: center;
    border-radius: 11px;
    background-color: #0059bf;

}
.image-container {
    display: flex;
    width: 100px;
    margin-right: 0px;
    padding-right: 20px;
    justify-content: flex-end;
}
.image-8 {
    max-height: 62px;
    background-color: #0059bf;
}
* {
    box-sizing: border-box;
}

</style>
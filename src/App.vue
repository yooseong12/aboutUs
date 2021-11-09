<template>
  <div class="app">
    <div class="header">
      <h1>팀원 발표</h1>
    </div>
      <div class="mainBox">
        <div class="mainLogo">
          <img src="@/assets/javascriptImage1.png" width="500px"/>
        </div>

      <div class="mainImage1">
      <img src="https://lh3.googleusercontent.com/proxy/QwJOqL3xzk2r7RZIFqSs7lg8m3_TZ9FMNVvIvZwj1rzk2Fpd1fMDLSL3Jikmsow6tG7OdLn8j4yewL0f8M63cUsTGhnGmnyGGWkETahfPWwJci09VnKA25eeTXYLuT7peY75sOpGX6ZbibVSKR-4uat87ZG3tuIIbw" class="img1"/>
      <h2>김유성</h2>
      <p>안녕하세요 저는 IT소프트웨어과 18학번<br>김유성입니다.</p>
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSwweEo7T_CjjdRSV5koIvroo8gtNaI1_E9iQ&usqp=CAU" class="img2"/>
      <h2>고진혁</h2>
      <p>안녕하세요 저는 IT소프트웨어과 18학번<br>고진혁입니다.</p>
      </div>

      <div class="mainImage2">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSCTBt3IdD6fo2-sNraGURr0GlUvNOTVywZOQ&usqp=CAU" class="img1"/>
      <h2>신성철</h2>
      <p>안녕하세요 저는 IT소프트웨어과 18학번<br>신성철입니다.</p>
      <img src="https://scontent-ssn1-1.xx.fbcdn.net/v/t1.6435-9/131335717_3828397587199389_4155341957141734026_n.jpg?_nc_cat=106&ccb=1-5&_nc_sid=973b4a&_nc_ohc=S147VM8Nq7AAX_Q8inl&_nc_oc=AQnwYSwO-Iv0WlTTEWtBWAhkPucyoYsW_qXClFfXr-Dwnn-qy1Et50CAjniMixA2Fp4&_nc_ht=scontent-ssn1-1.xx&oh=97cc1ff2885ca66567143822976c61ed&oe=61AE4C56" class="img2"/>
      <h2>남정훈</h2>
      <p>안녕하세요 저는 IT소프트웨어과 18학번<br>남정훈입니다.</p>
      
      
      </div>

      
      

    </div>
    
    
 
  </div>
  
</template>

<script>

export default {
  
}
</script>

<style scoped>
  .header{
    padding-top:30px;
    text-align: center;
  }

  .mainBox{
    display: flex;
  }
  .mainLogo{
    padding-top:130px; 
  }
  
  .img1{
    width: 300px;
    height: 200px;
    border-radius: 70%;
  }
  .img2{
    width: 300px;
    height: 200px;
    border-radius: 70%;
    margin-top:60px;
  }
  
  .mainImage1{
    padding : 50px;
    
  }
  .mainImage2{
    padding : 50px;
  }
  
  
</style>

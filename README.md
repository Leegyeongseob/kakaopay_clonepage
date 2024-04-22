# 1. kakopay Clone Page

[카카오페이 마음 놓고 금융하다](https://www.kakaopay.com/)

## 최소화면

https://github.com/Leegyeongseob/kakaopay_clonepage/assets/67867076/c8c0390b-e9e4-4d5d-a64a-77debdc8a2f9

## 최소크기 화면

https://github.com/Leegyeongseob/kakaopay_clonepage/assets/67867076/dae00bb6-0cf9-4953-896b-ec3521aae271

# 2. 메인페이지 레이아웃

## 전체화면 레이아웃

![kakopay_layout](https://github.com/Leegyeongseob/kakaopay_clonepage/assets/67867076/8837f058-762d-4151-95cf-ba3d204935e3)

## 최소화면 레이아웃

![kakao_layout_mobile](https://github.com/Leegyeongseob/kakaopay_clonepage/assets/67867076/5102f0d5-5ee2-42ae-9650-ae846c1b3026)

# 3. 코드

### HTML

```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <!-- html기존값을 전부 초기화 -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/reset-css@5.0.1/reset.min.css">
  <!-- 버튼 스타일을 위한 CDN -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@alphardex/aqua.css/dist/aqua.min.css">
  <link rel="stylesheet" href="../CloneCss/pc1.css" />
  <link rel="stylesheet" media="screen and (max-width: 1268px)" href="../CloneCss/pc2.css" />
  <link rel="stylesheet" media="screen and (max-width: 770px)" href="../CloneCss/mobile.css" />
  <!-- 애니매이션 CDN -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css">
  <title>Document</title>

  <!-- 모바일 배경 이미지 자동 변경을 위한 자바 스크립트 -->
   <script type="text/javascript">
    var imgArray=new Array();
    imgArray[0]="../이미지 데이터/img1.webp";
    imgArray[1]="../이미지 데이터/img2.webp";
    imgArray[2]="../이미지 데이터/img3.webp";
  
    function showImage(){
     var imgNum=Math.round(Math.random()*3);
     var objImg=document.getElementById("introimg");
     objImg.src=imgArray[imgNum];
     setTimeout(showImage,2500);
    }
  
   </script>
</head>
<body onload="showImage()">
  <div class="container">
    <video id="back_video" src="../영상 데이터/main_vidio.mp4" autoplay loop muted></video>
    <img id="introimg" border="0">
    <div class="headfirst">
      <header>
        <section class="boxa"><a href="#">kakao<b>pay</b></a></section>
        <nav>
          <div class="box1"></div>
          <a href="https://www.kakaopay.com/brand">카카오페이</a>
          <a href="#">서비스</a>
          <a href="#">소식</a>
          <a href="#">ESG</a>
          <a href="#">투자정보</a>
          <a href="#">문의</a>
          <a href="https://kakaopay.career.greetinghr.com/">채용</a>
          <div class="box1"></div>
        </nav>
        <section class="boxb">
          <div class="lang">KOR | ENG</div>&nbsp;三
        </section>
      </header>
    </div>
    <div class="div_section">
      <div class="half_radius1">
        <section class="sect1">
        </section>
        <section class="sect2">
          <div class="payment">
            <p>마음놓고 금융하다</p>
            <button type="button" class="Appdawnload">
              <a href="https://pay-home.kakao.com/pay/scheme/open?t_src=kakaopay&t_ch=brand&t_obj=install">
                <p>앱 다운로드</p>
              </a>
            </button>
          </div>
          
          <div class="logo">
            <button type="button" class="btn btn-primary btn-round">
              <a href="https://apps.apple.com/kr/app/%EC%B9%B4%EC%B9%B4%EC%98%A4%ED%8E%98%EC%9D%B4/id1464496236"><img src="../이미지 데이터/애플로고.png">&nbsp;<p>App Store</p></a>
            </button>
            <button type="button" class="btn btn-primary btn-round">
              <a href="https://pay-home.kakao.com/pay/scheme/open?t_src=kakaopay&t_ch=brand&t_obj=install"><img src="../이미지 데이터/플레이 스토어 로고.png">&nbsp;<p>Google Play</p></a>
            </button>
          </div>
        </section>
      </div>
      <div class="half_radius2">
        <section class="sect3">

        </section>
        <section class="sect4">

        </section>
      </div>
    </div>
    <div class="div2_section">
      <section class="sect5">

      </section>
      <section class="sect6">

      </section>
      <section class="sect7">

      </section>
      <section class="sect8">

      </section>
      </div>
    <div class="back_main">
      <div class="main1">
        <section class="sect9">

        </section>
        <section class="sect10">

        </section>
        <aside class="aside1">
          <div class="div_aside1_1 animate__fadeInUp">
            <img src="../이미지 데이터/ic-pfm.png">
            <pre>일상의 모든 금융
<span>한 번에 관리</span>해요</pre>
          </div>
          <div class="div_aside1_2 animate__fadeInUp">
            <pre>조회부터 실행까지
대출도 <span>톡하듯 쉽게</span></pre>
          </div>
          <div class="div_aside1_3 animate__fadeInUp">
            <a href="https://www.kakaopay.com/services/finance/loan">
              <img src="../이미지 데이터/img_pc_3.png">
            </a>
          </div>
        </aside>
        <aside class="aside2">

        </aside>
        <div class="video2">
          <a href="https://www.kakaopay.com/services/management/pfm">
          <video src="../영상 데이터/상품설명_vidio.mp4" autoplay loop muted></video>
        </a>
        </div>
        <div class="aside_box">
          <aside class="aside3">

          </aside>
          <aside class="aside4">
            <div class="div_aside4_1 animate__fadeInUp">
              <pre>내 친구의 보험은?
<span>궁금했던 정보</span>가 여기에
            </pre>
            </div>
            <div class="div_aside4_2 animate__fadeInUp">
              <a href="https://www.kakaopay.com/services/finance/insurance">
                <img src="../이미지 데이터/img_pc_2.png">
              </a>
            </div>
          </aside>
        </div>
      </div>
      <section class="sec_img">
        <div class="pc_img">
          <img src="../이미지 데이터/stock_PC_kor.png"></img>
        </div>
        <div class="mo_img">
          <img src="../이미지 데이터/stock_mo_kor.png"><img>
        </div>
        <h1>
          <p>카카오페이 주식, 아직 안 써보셨어요?</p>
        </h1>
      </section>
      <div class="main2">
        <section class="sect11">
        </section>
        <section class="sect12">
        </section>
        <aside class="aside5">
          <div class="div_aside5_1 animate__fadeInUp">
            <img src="../이미지 데이터/ic-payment.png">
            <pre>가까운 결제 해택도
놓칠 수 없죠!</pre>
          </div>
        </aside>
        <aside class="aside6">

        </aside>
        <div class="video3">
          <video src="../영상 데이터/GPS_vidio.mp4" autoplay loop muted></video>
        </div>
        <div class="aside_box2">
          <aside class="aside7">
          </aside>
          <aside class="aside8">
            <div class="div_aside8_1 animate__fadeInUp">
              <img src="../이미지 데이터/ic-ryan.png">
              <pre>내가 만든 금융을
모두가 쓰는 특별한 경험</pre>
            </div>
          </aside>
        </div>
        <div class="sec_img2 animate__fadeInUp">
          <img src="../이미지 데이터/img_pc_6.jpg">
        </div>
        <section class="sect13">

        </section>
      </div>
      <footer>
        <div class="kakaocrop">
          <p>© Kakao Pay Corp.</p>
        </div>
        <div class="kakao_footer">
          <div class="footer1">
          <a href="https://www.kakaopay.com/terms/code_of_ethics"><span>카카오페이 윤리강령&nbsp;&nbsp; <span>|</span>&nbsp;&nbsp;&nbsp;</span></a>
          <a href="https://www.kakaopay.com/terms/service"><span>카카오페이 이용악관&nbsp;&nbsp; <span>|</span>&nbsp;&nbsp;&nbsp; </span></a>
        </div>
        <div class="footer2">
          <a href="https://www.kakaopay.com/terms/financial"><span>전자금융거래 이용약관&nbsp;&nbsp; <span>|</span>&nbsp;&nbsp;&nbsp;</span></a>
          <a href="https://www.kakaopay.com/terms/privacy"><span>개인정보 처리방침&nbsp;&nbsp; <span>|</span>&nbsp;&nbsp;&nbsp;</span></a>
        </div>
        <div class="footer3">
          <a href="https://www.kakaopay.com/terms/location"><span>위치기반 서비스 이용약관&nbsp;</span></a>
        </div>
        </div>
        <div class="foot_site">
          <select class=footsite onchange="window.open(value,'_blank');">
            <option selected hidden>관련사이트</option>
            <option value="https://kakaopaysec.com/">카카오페이 증권</option>
            <option value="https://developers.kakaopay.com/">카카오페이 개발자센터</option>
            <option value="https://tech.kakaopay.com/">카카오페이 기술 블로그</option>
          </select>
        </div>
      </footer>
    </div>
  </div>
</body>

</html>
```

### pc1.css

```css
.container {
  width: 100%;
  height: 4595px;
}
header {
  display: flex;
  flex-wrap: wrap;
  width: 100%;
  height: 80px;
  box-sizing: border-box;
  backdrop-filter: brightness(80%);
  justify-content: space-between;
}

.headfirst {
  z-index: 5;
  position: sticky;
  top: 0;
}

.boxa>a {
  font-size: 1.2rem;
}

.boxa>a>b {
  font-weight: bolder;
}

nav {
  width: 63.8%;
  height: 80px;
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  box-sizing: border-box;
}

nav a {
  padding: 0 auto;
  text-decoration: none;
  color: #fff;
  box-sizing: border-box;
  font-size: 1rem;
}

.boxa {
  padding: 0 auto;
  width: 18.1%;
  height: 80px;
  text-decoration: none;
  box-sizing: border-box;
  font-size: 1.2rem;
  display: flex;
  justify-content: center;
  align-items: center;

  color: #fff;
}

.boxb {
  padding: 0 auto;
  width: 18.1%;
  height: 80px;
  color: #fff;
  box-sizing: border-box;
  font-size: 1.2rem;
  display: flex;
  justify-content: center;
  align-items: center;
}
#introimg{
  display: none;
}
#back_video {
  width: 100%;
  height: auto;
  background-size: cover;
  object-fit: fill;
  box-sizing: border-box;
  z-index: -1;
  position: fixed;
  filter: brightness(47%)
}

.div_section {
  width: 100%;
  height: 625px;
  position: absolute;
  display: flex;
  box-sizing: border-box;
}

img {
  float: left;
  width: 25px;
  height: 25px;
}

a {
  text-decoration: none;
}

a:link {
  color: #fff;
}

a:visited {
  color: #fff;
}

.half_radius1 {
  width: 50.2%;
  height: 625px;
  border-left: 0.01px solid #fff;
  box-sizing: border-box;
  display: flex;
  border-radius: 330px 0 0 330px;
  border-collapse: collapse;

}

.half_radius2 {
  width: 50%;
  height: 625px;
  border-right: 0.01px solid #fff;
  box-sizing: border-box;
  display: flex;
  border-radius: 0 330px 330px 0;
}

.sect1 {
  width: 36.2%;
  height: 625px;
  border-right: 0.01px solid #fff;
  border-top: 0.01px solid #fff;
  border-bottom: 0.01px solid #fff;
  box-sizing: border-box;

}

.sect2 {
  width: 63.8%;
  height: 625px;
  box-sizing: border-box;
  flex-direction: column;
  align-items: end;
  border-right: 0.01px solid #fff;
  border-top: 0.01px solid #fff;
  border-bottom: 0.01px solid #fff;
}

.payment {
  width: 200%;
  margin-top: 400px;
  box-sizing: border-box;

}

.payment>p {
  font-size: 3.7rem;
  color: #fff;
}

.logo {
  width: 200%;
  height: 50px;
  box-sizing: border-box;
  margin-top: 20px;
}

.sect3 {
  width: 63.7%;
  height: 625px;
  box-sizing: border-box;
  border-top: 0.01px solid #fff;
  border-bottom: 0.01px solid #fff;
}

.sect4 {
  width: 36.2%;
  height: 625px;
  border-left: 0.01px solid #fff;
  border-top: 0.01px solid #fff;
  border-bottom: 0.01px solid #fff;
  box-sizing: border-box;

}

.div2_section {
  width: 100%;
  height: 175px;
  position: absolute;
  margin-top: 625px;
  display: flex;
  box-sizing: border-box;
}

.sect5,
.sect8 {
  width: 18.1%;
  height: 175px;
}

.sect5 {
  border-right: 0.01px solid #fff;
}

.sect6,
.sect7 {
  width: 31.9%;
  height: 175px;
  box-sizing: border-box;
}

.sect6 {
  width: 32%;
  border-right: 0.01px solid #fff;
}

.sect7 {

  border-right: 0.01px solid #fff;
}

.main1 {
  width: 100%;
  height: 1759px;
  position: absolute;
  display: flex;
  flex-wrap: wrap;
  box-sizing: border-box;

}

.sect9 {
  width: 18.1%;
  height: 175px;
  border-right: 0.01px solid lightgray;
  box-sizing: border-box;
}

.sect10 {
  width: 32%;
  height: 175px;
  border-right: 0.01px solid lightgray;
  box-sizing: border-box;

}

.aside1 {
  width: 31.6%;
  height: 1650px;
  border-right: 0.01px solid lightgray;
  box-sizing: border-box;

}

.aside2 {
  width: 18.1%;
  height: 1650px;
  box-sizing: border-box;

}

.video2 {
  width: 100%;
  height: 270px;
  box-sizing: border-box;
  position: absolute;
  justify-content: left;
  margin-top: 175px;
  z-index: 1;
}
.video2 a > video{
  width:49.6vw;
}

.aside_box {
  width: 50.2%;
  height: 1230px;
  box-sizing: border-box;
  position: absolute;
  display: flex;
  margin-top: 175px;
}

.aside3 {
  width: 36.2%;
  height: 1475px;
  border: 0.01px solid #fff;
  box-sizing: border-box;
  border-right: 0.01px solid lightgray;
}

.aside4 {
  width: 64.5%;
  height: 1475px;
  border-right: 0.01px solid lightgray;
  box-sizing: border-box;
}

.div_aside1_1 {
  width: 31.8%;
  height: 353px;
  box-sizing: border-box;
  position: absolute;
  display: flex;
  flex-direction: column;
  margin-top: 175px;
  animation-duration: 4s;
}

.div_aside1_1>img {
  width: 100px;
  height: 70px;
  margin-left: 30px;
}

.div_aside1_2 {
  width: 31.8%;
  height: 353px;
  box-sizing: border-box;
  position: absolute;
  margin-top: 528px;
  animation-duration: 4.7s;
}

.div_aside1_2>pre {
  font-size: 30px;
  line-height: 45px;
  margin-top: 30px;
  margin-left: 30px;
}

.div_aside1_2>pre>span {
  text-decoration-line: underline;
  text-decoration-thickness: 10px;
  text-decoration-color: yellow;
  text-underline-position: above
}

.div_aside1_3 {
  width: 31.9%;
  height: 500px;
  border: 0.01px solid #fff;
  box-sizing: border-box;
  position: absolute;
  margin-top: 881px;
  animation-duration: 4.7s;
}

.div_aside1_3>a>img {
  width: 100%;
  height: 540px;
}

.div_aside4_1 {
  width: 63.8%;
  height: 353px;
  box-sizing: border-box;
  position: absolute;
  animation-duration: 5s;
  margin-top: 250px;
}

.div_aside4_1>pre {
  font-size: 30px;
  line-height: 45px;
  margin-top: 230px;
  margin-left: 30px;
}

.div_aside4_1>pre>span {
  text-decoration-line: underline;
  text-decoration-thickness: 10px;
  text-decoration-color: yellow;
  text-underline-position: above
}

.div_aside4_2 {
  animation-duration: 5s;
  margin-top: 300px;
}

.div_aside4_2>a>img {
  margin-top: 400px;
  width: 100%;
  height: 540px;
}

.sec_img {
  width: 100%;
  height: 750px;
  background-color: rgb(46, 51, 56);
  box-sizing: border-box;
  position: absolute;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin-top: 1650px;
}

.sec_img>.pc_img {
  width: 100%;
  display: flex;
  justify-content: center;
}

.sec_img>.pc_img>img {
  width: 80%;
  height: 550px;

}

.sec_img>h1 {
  color: #fff;
  font-size: 40px;
  font-weight: bold;
}

.main2 {
  width: 100%;
  height: 1200px;
  position: absolute;
  margin-top: 2400px;
  display: flex;
  flex-wrap: wrap;
  box-sizing: border-box;
}

.sect11 {
  width: 18.1%;
  height: 525px;
  border-right: 0.01px solid lightgray;
  box-sizing: border-box;
}

.sect12 {
  width: 31.9%;
  height: 525px;
  box-sizing: border-box;
}

.aside5 {
  width: 31.9%;
  height: 1164px;
  box-sizing: border-box;
  border-left: 0.01px solid lightgray;
}

.aside6 {
  width: 18.1%;
  height: 1165px;
  box-sizing: border-box;
  border-left: 0.01px solid lightgray;
}

.video3 {
  width: 100%;
  height: 250px;
  box-sizing: border-box;
  position: absolute;
  margin-top: 175px;
}
.video3 > video{
  width:49.6vw; 
}

.aside_box2 {
  width: 50%;
  height: 640px;
  box-sizing: border-box;
  position: absolute;
  display: flex;
  margin-top: 527px;
  border-right: 0.01px solid lightgray;
}

.aside7 {
  width: 36.2%;
  height: 639px;
  border-right: 0.01px solid lightgray;
  box-sizing: border-box;
}

.aside8 {
  width: 63.8%;
  height: 639px;
  box-sizing: border-box;
}

.sec_img2 {
  width: 100%;
  height: 350px;
  box-sizing: border-box;
  position: absolute;
  margin-top: 650px;
  left: 50%;
  animation-duration: 6.5s;
}

.sec_img2>img {
  width:49.6vw;
  height: 350px;
  box-sizing: border-box;
  position: absolute;
  display: flex;
}

.div_aside5_1 {
  width: 31.9%;
  height: 353px;
  box-sizing: border-box;
  position: absolute;
  margin-top: 175px;
  display: flex;
  flex-direction: column;
  animation-duration: 6s;
}

.div_aside5_1>img {
  width: 100px;
  height: 70px;
  margin-left: 30px;
}

.div_aside5_1>pre {
  font-size: 30px;
  line-height: 45px;
  margin-top: 30px;
  margin-left: 30px;
}

.div_aside8_1 {
  width: 63.8%;
  height: 553px;
  box-sizing: border-box;
  position: absolute;
  display: flex;
  flex-direction: column;
  animation-duration: 6.5s;
}

.div_aside8_1>img {
  width: 100px;
  height: 70px;
  margin-left: 30px;
  margin-top: 150px;
}

.div_aside8_1>pre {
  font-size: 30px;
  line-height: 45px;
  margin-top: 30px;
  margin-left: 30px;
}

.sect13 {
  width: 50%;
  height: 145px;
  box-sizing: border-box;
  position: absolute;
  display: flex;
  margin-top: 1021px;
  left: 50%;
}

footer {
  width: 100%;
  height: 145px;
  box-sizing: border-box;
  position: absolute;
  display: flex;
  margin-top: 3565px;
  background-color: #f8f9fa;
}

.kakaocrop {
  width: 17%;
  height: 150px;
  display: flex;
  padding-left: 40px;
  justify-content: left;
  align-items: center;
  box-sizing: border-box;
  background-color: #f8f9fa;
}

.kakaocrop>p {
  font-size: 17px;
  color: rgba(6, 11, 17, 0.48)
}

.kakao_footer {
  width: 68%;
  height: 150px;
  display: flex;
  justify-content: right;
  align-items: center;
  box-sizing: border-box;
  background-color: #f8f9fa;
}

.foot_site {
  width: 17%;
  height: 150px;
  display: flex;
  align-items: center;
  justify-content: left;
}

.foot_site>select {
  width: 180px;
  height: 40px;
  background-color: #f8f9fa;
  color: rgba(6, 11, 17, 0.48);
}

.btn {
  width: 160px;
  background-color: rgba(85, 84, 84, 0.247);
  border: #87929c;

  &-round {
    transition: 0.3s;

    &::before {
      position: absolute;
      content: "";
      top: 0;
      left: 0;
      z-index: -1;
      width: 100%;
      height: 100%;
      background: var(--btn-bg);
      transform: scaleX(0);
      transition: 0.3s;
    }

    &:hover {
      background: transparent;

      &::before {
        transform: scaleX(1);
      }
    }
  }
}

.logo>.btn>a {
  display: flex;
  justify-content: center;
  align-items: center;
}

.btn>a>p {
  font-size: 18px;
  margin-bottom: 4px;
}

.div_aside1_1>pre {
  font-size: 30px;
  line-height: 45px;
  margin-top: 30px;
  margin-left: 30px;
}

.div_aside1_1>pre>span {
  text-decoration-line: underline;
  text-decoration-thickness: 10px;
  text-decoration-color: yellow;
  text-underline-position: above
}

.animate__fadeInUp {
  animation-iteration-count: infinite;
}

.animate__fadeInUp {
  animation-iteration-count: infinite;
}

.kakao_footer>.footer1>a>span {
  font-size: 14px;
  color: rgba(6, 11, 17, 0.48)
}
.kakao_footer>.footer2>a>span {
  font-size: 14px;
  color: rgba(6, 11, 17, 0.48)
}
.kakao_footer>.footer3>a>span {
  font-size: 14px;
  color: rgba(6, 11, 17, 0.48)
}

.kakao_footer>select {
  width: 150px;
  height: 40px;
  font-size: 14px;
  color: rgba(6, 11, 17, 0.48)
}

.back_main {
  width: 100%;
  height: 3716px;
  margin-top: 800px;
  background-color: #fff;
}
.Appdawnload{
  display: none;
}
.Appdawnload>a>p {
  color: black;
}

.sec_img>.mo_img {
  display: none;
}
```

### pc2.css(max-width: 1268px)

```css
footer {
  display: flex;
  flex-direction: column-reverse;
  width: 100%;
  height: 350px;
  margin-top: 3550px;
}
.foot_site{
  width:100%;
  height: 80px;
  display: flex;
  justify-content: center;
  align-items: first baseline;
  margin-top: 25px;
}
.foot_site > select{
  width:95%;
}
.kakao_footer{
  width:100%;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
.kakao_footer > .footer1> a > span {
  font-size: 13px;
}
.kakao_footer > .footer2> a > span {
  font-size: 13px;
}
.kakao_footer > .footer3> a > span {
  font-size: 13px;
}
.kakao_footer > .footer1> a > span > span{
  display: none;
}
.kakao_footer > .footer2> a > span > span{
  display: none;
}
.kakao_footer > .footer3> a > span > span{
  display: none;
}
.kakaocrop > p{
  font-size: 11px;
}
```

### mobile.css(max-width: 770px)

```css
#back_video{
  display: none;
}
#introimg{
  display: block;
  width: 100%;
  height: 800px;
  background-size: cover;
  object-fit: fill;
  position: absolute;
  box-sizing: border-box;
  z-index: -1;
  position: fixed;
  filter: brightness(47%);
}
.back_main {
  width: 100%;
  margin-top: 950px;
  height: 4500px;
}

.boxa>a {
  margin-left: 40px;
  font-size: 1.2rem;
}

.div2_section,
.half_radius2 {
  z-index: -2;
}

nav,
.boxb>.lang,
.sect1,
.logo {
  display: none;
}

.half_radius1,
.sect2 {
  border: none;
}

.sect2 {
  width: 180px;
  height: 800px;
}

.payment {
  width: 180px;
  height: 800px;
  margin-top: 220;
  animation-duration: 7s;
  animation-iteration-count: unset;
}

.payment>p {
  margin-top: 300px;
  display: flex;
  justify-content: center;
  font-size: 45px;
  font-weight: bolder;
}

.Appdawnload {
display: block;
width: 125px;
height: 50px;
text-align: center;
border-radius: 20px;
border: 0;
background-color: yellow;
margin-left: 500px;   
z-index: 99;
position: sticky;   
top:600px
}

.sect9,
.sect10,
.aside3,
.aside2 {
  display: none;
}

.main1 {
  display: flex;
  flex-direction: column;
}

.video2 {
  margin-top: 295px;
  width: 100%;
}

.video2>a>video {
  width: 100%;
  height: auto;
  height: 55vw;
}

.div_aside1_1 {
  width: 100%;
  margin-top: 80px;
}

.div_aside1_2 {
  width: 100px;
  margin-top: 1410px;
}

.div_aside1_3 {
  width: 100%;
  margin-top: 1550px;
}

.aside_box {
  width: 100%;
}

.aside4 {
  width: 100%;
}

.aside1 {
  width: 100%;
}

.div_aside4_1 {
  width: 100%;
  margin-top: 280px;
}

.div_aside4_2 {
  width: 100%;
  margin-top: 225px;
}

.sec_img {
  margin-top: 2190px;
  height: 116vw;
  display: flex;
  justify-content: center;
  flex-direction: column;
}

.sec_img>.pc_img {
  display: none;
}

.sec_img>.mo_img {
  display: block;
  justify-content: center;
  width: 100%;
  height: auto;
}

.sec_img>.mo_img>img {
  width: 90%;
  margin-left: 5%;
  height: auto;
}

.sec_img>h1 {
  margin-top: 20px;
  font-size: 28px;
  text-align: center;
  font-weight: bold;
}

.main2 {
  width: 100%;
  display: flex;
  flex-direction: column;
}

.sect11,
.sect12,
.aside7,
.sect13 {
  display: none;
}

.video3 {
  width: 100%;
}

.video3>video {
  margin-top: 525px;
  width: 100%;
  height: 60vw;
}

.aside5 {
  width: 100%;
}

.div_aside5_1 {
  margin-top: 515px;
  width: 100%;
}

.aside8 {
  width: 100%;
}

.div_aside8_1 {
  width: 100%;
  margin-top: 460px;
}

.aside_box2 {
  width: 100%;
  border: none;
}

.sec_img2 {
  width: 100%;
  left: 0%;
  margin-left: 5%;
  margin-top: 1350px;
}

.sec_img2>img {
  width: 100%;
  height: 58vw;
}
footer {
  display: flex;
  flex-direction: column-reverse;
  width: 100%;
  height: 350px;
  margin-top: 4170px;
}
.kakaocrop{
  width:100%;
}
```

# 4. Copy Version

[kakaopage_clone.mp4](https://prod-files-secure.s3.us-west-2.amazonaws.com/bdf8d538-0573-4e53-8871-08828a72d8e6/28e7afa4-7108-446d-b518-e8d4c96ed371/kakaopage_clone.mp4)

# 5. 결과 링크

[GitHub - Leegyeongseob/kakaopay_clonepage](https://github.com/Leegyeongseob/kakaopay_clonepage)

# 6. 활용 이미지/영상

### 활용 이미지

[ic-payment.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/bdf8d538-0573-4e53-8871-08828a72d8e6/70b197a6-6d7a-4b92-b198-fbf73ac8e742/ic-payment.png)

[ic-pfm.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/bdf8d538-0573-4e53-8871-08828a72d8e6/712b2c9f-615f-425a-ab70-ee206099edf6/ic-pfm.png)

[ic-ryan.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/bdf8d538-0573-4e53-8871-08828a72d8e6/3dd3ac8e-2465-432f-bafb-6b2133014f29/ic-ryan.png)

[img_pc_2.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/bdf8d538-0573-4e53-8871-08828a72d8e6/dd4928ea-c36a-42ae-ae83-a089e58bf3a7/img_pc_2.png)

[img_pc_3.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/bdf8d538-0573-4e53-8871-08828a72d8e6/44c169b6-7679-4e5e-8488-c853809ffc03/img_pc_3.png)

[img_pc_6.jpg](https://prod-files-secure.s3.us-west-2.amazonaws.com/bdf8d538-0573-4e53-8871-08828a72d8e6/e37c20d8-9407-42e6-a8dc-84745a1e7ad9/img_pc_6.jpg)

[img1.webp](https://prod-files-secure.s3.us-west-2.amazonaws.com/bdf8d538-0573-4e53-8871-08828a72d8e6/afac42ef-d790-43ad-b562-2f6248cbd878/img1.webp)

[img2.webp](https://prod-files-secure.s3.us-west-2.amazonaws.com/bdf8d538-0573-4e53-8871-08828a72d8e6/6fc6fd83-5981-4e2a-824b-b50f8798d4b0/img2.webp)

[img3.webp](https://prod-files-secure.s3.us-west-2.amazonaws.com/bdf8d538-0573-4e53-8871-08828a72d8e6/0c3f767e-8ce7-4340-aba4-da0238ab27cb/img3.webp)

[stock_mo_kor.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/bdf8d538-0573-4e53-8871-08828a72d8e6/00ea70b5-3e0d-49d4-9adf-7539ce77130e/stock_mo_kor.png)

[stock_PC_kor.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/bdf8d538-0573-4e53-8871-08828a72d8e6/1a6b8d39-f47e-4518-bc73-ef2b35f2c39b/stock_PC_kor.png)

[애플로고.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/bdf8d538-0573-4e53-8871-08828a72d8e6/71f2a682-cc1c-40a6-b9d3-c47ef18b8307/%EC%95%A0%ED%94%8C%EB%A1%9C%EA%B3%A0.png)

[플레이 스토어 로고.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/bdf8d538-0573-4e53-8871-08828a72d8e6/329856bb-62f0-4141-bbb8-c57836f3ce9d/%ED%94%8C%EB%A0%88%EC%9D%B4_%EC%8A%A4%ED%86%A0%EC%96%B4_%EB%A1%9C%EA%B3%A0.png)

### 활용 영상

[GPS_vidio.mp4](https://prod-files-secure.s3.us-west-2.amazonaws.com/bdf8d538-0573-4e53-8871-08828a72d8e6/7510b345-de86-44fa-8eb0-ac9b14e931ad/GPS_vidio.mp4)

[main_vidio.mp4](https://prod-files-secure.s3.us-west-2.amazonaws.com/bdf8d538-0573-4e53-8871-08828a72d8e6/cb53b92c-131b-44ad-8f64-300ce7a65047/main_vidio.mp4)

[상품설명_vidio.mp4](https://prod-files-secure.s3.us-west-2.amazonaws.com/bdf8d538-0573-4e53-8871-08828a72d8e6/144adb9d-0fc9-4c31-9c20-39a16169b3f5/%EC%83%81%ED%92%88%EC%84%A4%EB%AA%85_vidio.mp4)

# 8. 느낀점

### 1. 처음에 만들 때 레이아웃을 더 깊게 생각하지 못해서 나중에 margin으로 전부 따로 움직여서 배치해야 하는 일을 겪고 어떻게 레이아웃을 잡아야 하는지 깨달을 수 있었습니다.

### 2. display flex를 자유자재로 사용할 수 있게 되었습니다.

### 3. java script를 사용하지 않아서 스크롤 이벤트를 비슷한 애니매이션으로 대체했습니다.

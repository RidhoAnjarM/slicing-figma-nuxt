<template>
    <header>
        <nav class="navbar">
            <div class="icon">
                <img src="asset/Icon.png" alt="logo">
                <img src="asset/Positivus.png" alt="logo">
            </div>
            <ul class="navigasi">
                <li><a href="#">About us</a> </li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Use Cases</a> </li>
                <li><a href="#">Pricing</a></li>
                <li><a href="#">Blog</a></li>
                <section class="button"><a href="#">Reques a quote</a></section>
            </ul>
        </nav>

        <section class="hiro">
            <div class="text">
                <h1>Navigating the digital landscape for success</h1>
                <p>Our digital marketing agency helps businesses grow and succeed online through a range of services
                    including
                    SEO, PPC, social media marketing, and content creation.</p>
                <div class="buttonn">
                    <a href="#">Book a consultation</a>
                </div>
            </div>
            <div class="ilustration">
                <img src="asset/ilustration.svg" alt="">
            </div>
        </section>
    </header>
</template>

<style>
:root {
  --Green: #B9FF66;
  --Dark: #191A23;
  --Grey: #F3F3F3;
}

header {
  padding-inline: 100px;
  margin-bottom: 70px;
  width: 1443px;
}

.navbar {
  margin-top: 40px;
  margin-bottom: 70px;
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.icon {
  /*logo positivus*/
  display: flex;
  width: 219.537px;
  height: 36px;
  justify-content: center;
  align-items: center;
  gap: 12.92px;
}

.navigasi {
  display: flex;
  justify-content: center;
  align-items: center;
}

.navigasi li {
  list-style: none;
  margin-right: 40px;
}

.navigasi li a {
  text-decoration: none;
  color: #000;
  font-family: "Space Grotesk";
  font-size: 20px;
  font-style: normal;
  font-weight: 400;
  line-height: 28px;
}

.button {
  /*button reques a quote*/
  border: 1px solid #000;
  border-radius: 14px;
}

.button a {
  text-decoration: none;
  color: var(--Dark);
  font-family: "Space Grotesk";
  font-size: 20px;
  font-style: normal;
  font-weight: 400;
  line-height: 28px;
  display: flex;
  padding: 20px 35px;
  align-items: flex-start;
}

.text{
  width: 531px;
  height: 481px;
}

.hiro{
  width: 100%;
  display: flex;
  justify-content: space-between;
}

header h1 {
  width: 531px;
  color: #000;
  font-family: "Space Grotesk";
  font-size: 60px;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
  float: left;
  margin: 0px 0px 35px 0px;
}

header p {
  width: 498px;
  color: #000;
  font-family: "Space Grotesk";
  font-size: 20px;
  font-style: normal;
  font-weight: 400;
  line-height: 28px;
  margin: 35px 0px 35px 0px;
}

.buttonn {
  display: block;
  padding: 20px 35px;
  align-items: flex-start;
  gap: 10px;
  border-radius: 14px;
  background: var(--Dark, #191A23);
  float: left;
  margin-bottom: 70px;
}

.buttonn a {
  color: #FFF;
  text-align: center;
  font-family: "Space Grotesk";
  font-size: 20px;
  font-style: normal;
  font-weight: 400;
  line-height: 28px;
  text-decoration: none;
}
</style>
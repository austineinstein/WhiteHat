# WhiteHat 
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>WhiteHat: provides real-time visibility into your security status and allows you to understand the risks and vulnerabilities in your environment. This means you can take appropriate steps to fix them before any malicious actors get in! </title>
    <link href="styles.css" rel="stylesheet">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Detect & Protect against vulnerabilities ">
    <meta name="keywords" content="WhiteHat, Detect & Protect against vulnerabilities ">
    <meta name="author" content="WhiteHat">

    <link rel="icon" type="image/png" sizes="32x32" href="favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="favicon-16x16.png">
  </head>
  <style>
  @import url("https://rsms.me/inter/inter-ui.css");

body {
  position: relative;
  margin: 0;
  padding: 0;
  font-family: "Inter UI", sans-serif;
  text-align: center;
  color: white;
}

.titan-background {
  position: absolute;
  width: 100%;
  background-image: linear-gradient(-180deg, #000000 0%, #200835 100%);
  overflow: hidden;
  z-index: 1;
  /* Make the rubber band scroll not show empty white space */
  top: -10%;
  height: 120%;
  min-height: 120vh;
  margin-bottom: -20%;
}

.stars {
  position: absolute;
  top: 0;
  width: 300vw;
  height: 100vh;
  transform: translate(0%, 0%);
  background-size: contain;
  background-repeat: repeat;
  transform-origin: top left;
}

.stars-L {
  background-image: url("assets/stars-L.svg");
  background-size: 890px;
  height: 750px;
  animation: panning-stars 200s linear infinite alternate;
}

.stars-M {
  background-image: url("assets/stars-M.svg");
  height: 530px;
  animation: panning-stars 300s linear infinite alternate;
}

.stars-S {
  background-image: url("assets/stars-S.svg");
  height: 370px;
  animation: panning-stars 400s linear infinite alternate;
}

@keyframes panning-stars {
  from {
    transform: translate(-20%, 0%);
  }
  to {
    transform: translate(-80%, -40%);
  }
}

.marvellous-container {
  position: relative;
  z-index: 2;
  padding: 104px 0 24px 0;
  width: 95%;
  max-width: 600px;
  margin: auto;
}

h1 {
  display: block;
  font-size: 80px;
  margin: 0 0 24px 0;
}

@media (max-width: 500px) {
  h1 {
    font-size: 16vw;
  }
}

h2 {
  font-weight: 500;
  font-size: 24px;
}

h3 {
  font-weight: 300;
  font-size: 24px;
}

a {
  color: inherit;
  text-decoration: underline;
}

.title-marvel {
  font-weight: bolder;
  color: #020103;
  letter-spacing: -6.7px;
  text-transform: uppercase;
  padding: 0 16px;
  background: #9b00f5;
}

.title-studios {
  position: relative;
  display: inline-block;
  font-weight: bold;
  color: #9b00f5;
  letter-spacing: -4.5px;
  text-transform: uppercase;
  padding: 0 16px;
  border-color: #9b00f5;
  border-top: 8px solid;
  border-bottom: 8px solid;
  line-height: 1;
}

code {
  display: block;
  box-sizing: border-box;
  text-align: left;
  font-size: 18px;
  width: 100%;
  padding: 16px 24px;
  background: rgba(44, 37, 44, 0.8);
  border: 1px solid #7f797f;
  border-radius: 8px;
  margin-bottom: 16px;
}

.header {
  margin-bottom: 104px;
}

.installation-instructions,
.usage-instructions {
  margin-top: 64px;
}

.footer {
  margin-top: 224px;
}

.footer img {
  height: 104px;
  width: auto;
}

  </style>
  <body>
    <div class="titan-background">
      <span class="stars stars-L"></span>
      <span class="stars stars-M"></span>
      <span class="stars stars-S"></span>
    </div>
    <div class="marvellous-container">
      <div class="header">
        <h1><span class="title-marvel">White </span> <span class="title-studios">Hat</span></h1>
        <h2>
          Offers a web vulnerability solution for securing your websites, web applications, and APIs. Our automated web security testing platform detects and protects against new vulnerabilities before they become an attacker’s weapon of choice.
        </h2>
      </div>
      <div class="installation-instructions">
        <h3>Detect & Protect against vulnerabilities including </h3>
       

        <code>- SQL injections</code>
        <code>- XSS</code>
        <code>- misconfigurations</code>
        <code>- weak passwords</code>
        <code>- exposed databases and </code>
        <code>- out-of-band vulnerabilities</code>
      </div>
      <div class="usage-instructions">
        <h3>Basic Usage</h3>
        <code>$ WhiteHat snap-fingers --with-glove</code>
      </div>
      <div class="footer">
        <img src="glove.png" alt="whitehat"/>
        <p>
          Contact our trusted partner, <br />
          sales@procomeurope.co.uk for more details 
        </p>
      </div>
    </div>
  </body>
</html>


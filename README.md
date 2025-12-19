# Ex08 Event Registration Web Application
## Date:19.12.2025

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
```
frame1
 <!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <img class="sing" src="img/sing-1.png" />
      <div class="text-wrapper">TALENTS DAY EVENTS</div>
      <div class="rectangle"></div>
      <div class="div"></div>
      <div class="text-wrapper-2">Login</div>
      <div class="div-wrapper"><div class="text-wrapper-3">Register</div></div>
      <img class="logo" src="img/logo2-1.png" />
    </div>
  </body>
</html>

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}


.frame {
  background-color: #ffffff;
  width: 100%;
  min-width: 292px;
  min-height: 498px;
  position: relative;
}

.frame .sing {
  position: absolute;
  top: 226px;
  left: 69px;
  width: 223px;
  height: 272px;
  aspect-ratio: 0.75;
  object-fit: cover;
}

.frame .text-wrapper {
  position: absolute;
  top: 200px;
  left: 27px;
  width: 265px;
  font-family: "Jersey 10-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .rectangle {
  top: 194px;
  left: 13px;
  width: 265px;
  height: 40px;
  mix-blend-mode: multiply;
  position: absolute;
  background-color: #ff4460d4;
  border: 1px solid;
  border-color: #000000;
}

.frame .div {
  top: 249px;
  left: 77px;
  width: 125px;
  height: 30px;
  position: absolute;
  background-color: #ff4460d4;
  border: 1px solid;
  border-color: #000000;
}

.frame .text-wrapper-2 {
  position: absolute;
  top: 249px;
  left: 112px;
  width: 83px;
  font-family: "Jaro-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .div-wrapper {
  position: absolute;
  top: 305px;
  left: 77px;
  width: 123px;
  height: 27px;
  display: flex;
  background-color: #ff4460d4;
  overflow: hidden;
  border: 1px solid;
  border-color: #000000;
}

.frame .text-wrapper-3 {
  margin-top: -1px;
  width: 80px;
  height: 30px;
  margin-left: 27px;
  font-family: "Jaro-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .logo {
  position: absolute;
  top: 69px;
  left: 89px;
  width: 110px;
  height: 110px;
  aspect-ratio: 1;
  object-fit: cover;
}




frame2

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <img class="arrow" src="img/arrow-1.svg" />
      <img class="img" src="img/arrow-3.svg" />
      <img class="arrow-2" src="img/arrow-4.svg" />
      <div class="rectangle"></div>
      <div class="text-wrapper">TALENTS DAY EVENTS</div>
      <div class="div">Singing(Solo/Group)</div>
      <div class="text-wrapper-2">Live Drawing</div>
      <div class="text-wrapper-3">Dance(Solo/Group)</div>
      <img class="arrow-3" src="img/arrow-2.svg" />
      <div class="text-wrapper-4">Speech/Mono Act</div>
      <img class="speech" src="img/speech-1.png" />
      <img class="dance" src="img/dance2-1.png" />
      <div class="ellipse"></div>
      <div class="ellipse-2"></div>
      <div class="ellipse-3"></div>
      <div class="ellipse-4"></div>
    </div>
  </body>
</html>


@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}


.frame {
  background-color: #ffffff;
  border: 1px solid;
  border-color: transparent;
  border-image: linear-gradient(
      180deg,
      rgba(102, 102, 102, 1) 0%,
      rgba(81, 81, 81, 1) 0%,
      rgba(0, 0, 0, 1) 26%
    )
    1;
  width: 100%;
  min-width: 292px;
  min-height: 498px;
  position: relative;
}

.frame .arrow {
  top: 123px;
  position: absolute;
  left: 27px;
  width: 30px;
  height: 15px;
}

.frame .img {
  top: 216px;
  position: absolute;
  left: 27px;
  width: 30px;
  height: 15px;
}

.frame .arrow-2 {
  top: 264px;
  position: absolute;
  left: 27px;
  width: 30px;
  height: 15px;
}

.frame .rectangle {
  position: absolute;
  top: 30px;
  left: 7px;
  width: 275px;
  height: 45px;
  background-color: #ff4460d4;
  border: 1px solid;
  border-color: #000000;
}

.frame .text-wrapper {
  position: absolute;
  top: 34px;
  left: 32px;
  width: 259px;
  -webkit-text-stroke: 1px #000000;
  font-family: "Jersey 10-Regular", Helvetica;
  font-weight: 400;
  color: transparent;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .div {
  position: absolute;
  top: 113px;
  left: 75px;
  width: 207px;
  font-family: "Jomhuria-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .text-wrapper-2 {
  position: absolute;
  top: 207px;
  left: 95px;
  width: 101px;
  font-family: "Jomhuria-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .text-wrapper-3 {
  position: absolute;
  top: 160px;
  left: 75px;
  width: 207px;
  font-family: "Jomhuria-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .arrow-3 {
  top: 167px;
  position: absolute;
  left: 27px;
  width: 30px;
  height: 15px;
}

.frame .text-wrapper-4 {
  position: absolute;
  top: 254px;
  left: 85px;
  width: 138px;
  font-family: "Jomhuria-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .speech {
  position: absolute;
  top: 233px;
  left: 76px;
  width: 216px;
  height: 265px;
  aspect-ratio: 1;
  object-fit: cover;
}

.frame .dance {
  position: absolute;
  top: 271px;
  left: 0;
  width: 207px;
  height: 227px;
  object-fit: cover;
}

.frame .ellipse {
  position: absolute;
  top: 105px;
  left: 63px;
  width: 181px;
  height: 42px;
  background-color: #ff3572a6;
  border-radius: 90.5px / 21px;
  border: 1px solid;
  border-color: #000000;
  box-shadow: 0px 4px 4px #00000040;
  mix-blend-mode: darken;
}

.frame .ellipse-2 {
  top: 152px;
  height: 41px;
  border-radius: 90.5px / 20.5px;
  border-color: #1e1e1e;
  position: absolute;
  left: 63px;
  width: 181px;
  background-color: #ff3572a6;
  border: 1px solid;
  box-shadow: 0px 4px 4px #00000040;
  mix-blend-mode: darken;
}

.frame .ellipse-3 {
  top: 196px;
  height: 41px;
  border-radius: 90.5px / 20.5px;
  border-color: #151313;
  position: absolute;
  left: 63px;
  width: 181px;
  background-color: #ff3572a6;
  border: 1px solid;
  box-shadow: 0px 4px 4px #00000040;
  mix-blend-mode: darken;
}

.frame .ellipse-4 {
  top: 246px;
  height: 42px;
  border-radius: 90.5px / 21px;
  border-color: #000000;
  position: absolute;
  left: 63px;
  width: 181px;
  background-color: #ff3572a6;
  border: 1px solid;
  box-shadow: 0px 4px 4px #00000040;
  mix-blend-mode: darken;
}


frame3

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <div class="text-wrapper">EVENT REGISTRATION FORM</div>
      <div class="rectangle"></div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="text-wrapper-2">GENDER:</div>
      <img class="FULL-NAME" src="img/FULL-NAME.svg" />
      <div class="text-wrapper-3">DEPT:</div>
      <div class="text-wrapper-4">REG NO:</div>
      <div class="text-wrapper-5">MOBILE NO:</div>
      <div class="rectangle-6"></div>
      <div class="text-wrapper-6">SUBMIT</div>
    </div>
  </body>
</html>


@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}


.android-medium {
  background-color: #ffffff;
  width: 100%;
  min-width: 289px;
  min-height: 498px;
  position: relative;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 37px;
  left: 15px;
  font-family: "Jaro-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle {
  position: absolute;
  top: 30px;
  left: 7px;
  width: 275px;
  height: 44px;
  background-color: #ff4460d4;
  border: 1px solid;
  border-color: #000000;
  mix-blend-mode: multiply;
}

.android-medium .div {
  position: absolute;
  top: 143px;
  left: 16px;
  width: 224px;
  height: 30px;
  background-color: #d9d9d9;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 189px;
  left: 16px;
  width: 224px;
  height: 30px;
  background-color: #d9d9d9;
}

.android-medium .rectangle-3 {
  position: absolute;
  top: 235px;
  left: 17px;
  width: 223px;
  height: 30px;
  background-color: #d9d9d9;
}

.android-medium .rectangle-4 {
  position: absolute;
  top: 284px;
  left: 17px;
  width: 225px;
  height: 31px;
  background-color: #d9d9d9;
}

.android-medium .rectangle-5 {
  position: absolute;
  top: 99px;
  left: 17px;
  width: 225px;
  height: 30px;
  background-color: #d9d9d9;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 142px;
  left: 17px;
  font-family: "Jaldi-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .FULL-NAME {
  position: absolute;
  top: 111px;
  left: 23px;
  width: 90px;
  height: 12px;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 237px;
  left: 18px;
  font-family: "Jaldi-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 189px;
  left: 18px;
  font-family: "Jaldi-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-5 {
  position: absolute;
  top: 285px;
  left: 18px;
  font-family: "Jaldi-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-6 {
  position: absolute;
  top: 341px;
  left: 41px;
  width: 100px;
  height: 22px;
  background-color: #ff4460fa;
  border: 1px solid;
  border-color: #000000;
  box-shadow: 0px 4px 4px #00000040;
}

.android-medium .text-wrapper-6 {
  position: absolute;
  top: 335px;
  right: 165px;
  font-family: "Jaldi-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}


```



## OUTPUT:

![alt text](<Screenshot (36).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.

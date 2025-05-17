# Ex09 Event Registration Web Application
## Date:17-05-2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:

### Page1

HTML

```
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max" data-model-id="1:3">
      <div class="div">
        <div class="EVENT-REGISTRATION">
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;EVENT<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;REGISTRATION
        </div>
        <div class="text-wrapper">Create an account</div>
        <div class="group">
          <div class="overlap-group">
            <div class="group-2"></div>
            <div class="text-wrapper-2">Sign in</div>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>

```

CSS

```
.iphone-pro-max {
  background-color: transparent;
  display: flex;
  flex-direction: row;
  justify-content: center;
  width: 100%;
}

.iphone-pro-max .div {
  overflow: hidden;
  background-image: url(https://c.animaapp.com/706CYhDu/img/iphone-16-pro-max---2.svg);
  background-size: cover;
  background-position: 50% 50%;
  width: 440px;
  height: 956px;
  position: relative;
}

.iphone-pro-max .EVENT-REGISTRATION {
  position: absolute;
  width: 526px;
  top: 342px;
  left: -63px;
  background: linear-gradient(
    90deg,
    rgba(66, 127, 249, 1) 0%,
    rgba(0, 0, 0, 1) 100%
  );
  -webkit-background-clip: text !important;
  background-clip: text;
  -webkit-text-fill-color: transparent;
  text-fill-color: transparent;
  font-family: "Segoe UI-Semibold", Helvetica;
  font-weight: 400;
  color: transparent;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  width: 260px;
  top: 567px;
  left: 90px;
  font-family: "Roboto", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .group {
  width: 358px;
  top: 494px;
  left: 42px;
  position: absolute;
  height: 60px;
}

.iphone-pro-max .overlap-group {
  position: relative;
  width: 356px;
  height: 60px;
  border-radius: 30px;
}

.iphone-pro-max .group-2 {
  width: 356px;
  top: 0;
  left: 0;
  background-color: #ffffff;
  border-radius: 30px;
  opacity: 0.7;
  position: absolute;
  height: 60px;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 10px;
  left: 139px;
  font-family: "Caveat", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

```

```
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
@import url("https://fonts.googleapis.com/css?family=Roboto:400|Caveat:400");
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
@font-face {
  font-family: "Segoe UI-Semibold";
  src: url("https://anima-uploads.s3.amazonaws.com/projects/654d154fc35917c129244240/fonts/seguisb.ttf")
    format("truetype");
}

```

### Page2

HTML

```
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <div class="div">
        <div class="overlap">
          <div class="group"><img class="rectangle" src="img/rectangle.png" /></div>
          <div class="text-wrapper">WELCOM BACK</div>
          <div class="text-wrapper-2">Login to your account</div>
        </div>
        <div class="overlap-group-wrapper">
          <div class="overlap-group"><div class="text-wrapper-3">LOGIN</div></div>
        </div>
        <div class="group-2">
          <div class="div-wrapper"><div class="text-wrapper-4">Username</div></div>
          <div class="group-3">
            <div class="overlap-group"><div class="text-wrapper-4">Password</div></div>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>
```

CSS

```
.iphone-pro-max {
  background-color: transparent;
  display: flex;
  flex-direction: row;
  justify-content: center;
  width: 100%;
}

.iphone-pro-max .div {
  overflow: hidden;
  background: linear-gradient(
    0deg,
    rgba(255, 255, 255, 1) 0%,
    rgba(255, 255, 255, 1) 100%
  );
  width: 440px;
  height: 956px;
  position: relative;
}

.iphone-pro-max .overlap {
  position: absolute;
  width: 1435px;
  height: 673px;
  top: -217px;
  left: -540px;
}

.iphone-pro-max .group {
  position: absolute;
  width: 1435px;
  height: 673px;
  top: 0;
  left: 0;
}

.iphone-pro-max .rectangle {
  position: absolute;
  width: 440px;
  height: 455px;
  top: 217px;
  left: 540px;
  object-fit: cover;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  width: 283px;
  top: 561px;
  left: 642px;
  background: linear-gradient(
    90deg,
    rgba(66, 127, 249, 1) 0%,
    rgba(0, 0, 0, 1) 100%
  );
  -webkit-background-clip: text !important;
  background-clip: text;
  -webkit-text-fill-color: transparent;
  text-fill-color: transparent;
  font-family: "Roboto-Regular", Helvetica;
  font-weight: 400;
  color: transparent;
  font-size: 40px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  width: 208px;
  top: 607px;
  left: 717px;
  background: linear-gradient(
    90deg,
    rgba(66, 127, 249, 1) 0%,
    rgba(0, 0, 0, 1) 100%
  );
  -webkit-background-clip: text !important;
  background-clip: text;
  -webkit-text-fill-color: transparent;
  text-fill-color: transparent;
  opacity: 0.7;
  font-family: "Roboto-Regular", Helvetica;
  font-weight: 400;
  color: transparent;
  font-size: 20px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .overlap-group-wrapper {
  position: absolute;
  width: 375px;
  height: 50px;
  top: 832px;
  left: 33px;
}

.iphone-pro-max .overlap-group {
  position: relative;
  width: 373px;
  height: 50px;
  background-color: #ffffff;
  border-radius: 30px;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  width: 194px;
  top: 18px;
  left: 85px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .group-2 {
  position: absolute;
  width: 375px;
  height: 127px;
  top: 478px;
  left: 33px;
}

.iphone-pro-max .div-wrapper {
  position: absolute;
  width: 373px;
  height: 50px;
  top: 0;
  left: 0;
  background-color: #ffffff;
  border-radius: 30px;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  width: 194px;
  top: 14px;
  left: 45px;
  opacity: 0.5;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .group-3 {
  position: absolute;
  width: 375px;
  height: 50px;
  top: 77px;
  left: 0;
}
```

```
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

```

### Profile Page

HTML

```
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <div class="overlap-wrapper">
        <div class="overlap">
          <div class="overlap-group">
            <div class="rectangle"></div>
            <div class="text-wrapper">User Name</div>
          </div>
          <div class="div">
            <div class="rectangle"></div>
            <div class="text-wrapper">Register Number</div>
          </div>
          <div class="overlap-2">
            <div class="rectangle"></div>
            <div class="text-wrapper">Department</div>
          </div>
          <div class="overlap-3">
            <div class="rectangle"></div>
            <div class="text-wrapper">Year</div>
          </div>
          <div class="overlap-4">
            <div class="rectangle"></div>
            <div class="text-wrapper">Phone Number</div>
          </div>
          <img class="user" src="img/user.png" />
          <div class="group">
            <div class="div-wrapper"><div class="text-wrapper-2">Back</div></div>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>

```

CSS

```
.iphone-pro-max {
  background-color: transparent;
  display: flex;
  flex-direction: row;
  justify-content: center;
  width: 100%;
}

.iphone-pro-max .overlap-wrapper {
  background-image: url(./img/iphone-16-pro-max-7.png);
  background-size: cover;
  background-position: 50% 50%;
  width: 440px;
  height: 956px;
}

.iphone-pro-max .overlap {
  position: relative;
  width: 381px;
  height: 845px;
  top: 55px;
  left: 29px;
  border-radius: 40px;
}

.iphone-pro-max .overlap-group {
  position: absolute;
  width: 335px;
  height: 62px;
  top: 352px;
  left: 23px;
}

.iphone-pro-max .rectangle {
  position: absolute;
  width: 335px;
  height: 61px;
  top: 1px;
  left: 0;
  background-color: #f5f5f5;
  border-radius: 30px;
  border: 2px solid;
  border-color: #000000;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  width: 284px;
  height: 61px;
  top: 0;
  left: 26px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #00000099;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  position: absolute;
  width: 335px;
  height: 62px;
  top: 442px;
  left: 23px;
}

.iphone-pro-max .overlap-2 {
  position: absolute;
  width: 335px;
  height: 62px;
  top: 532px;
  left: 23px;
}

.iphone-pro-max .overlap-3 {
  position: absolute;
  width: 335px;
  height: 62px;
  top: 622px;
  left: 23px;
}

.iphone-pro-max .overlap-4 {
  position: absolute;
  width: 335px;
  height: 62px;
  top: 712px;
  left: 23px;
}

.iphone-pro-max .user {
  position: absolute;
  width: 335px;
  height: 239px;
  top: 85px;
  left: 23px;
}

.iphone-pro-max .group {
  position: absolute;
  width: 77px;
  height: 29px;
  top: 27px;
  left: 30px;
}

.iphone-pro-max .div-wrapper {
  position: relative;
  width: 75px;
  height: 29px;
  background-color: #417ef9;
  border-radius: 30px;
  border: 2px solid;
  border-color: #1e1e1e;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  width: 53px;
  top: 3px;
  left: 17px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

```

```
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

```
## OUTPUT:

Name: Arunsamy D

Register Number: 212224240016

![alt text](<Screenshot (88).png>)

![alt text](<Screenshot (89).png>)

![alt text](<Screenshot (90).png>)

![alt text](<Screenshot (91).png>)

![alt text](<Screenshot (92).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.

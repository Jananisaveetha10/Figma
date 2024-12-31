# Ex09 Event Registration Web Application
## Date:30/12/2024

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
```  
html
<div class="container--0-">
  <div class="text-0-1-0">MUSIC EVENT</div>
  <svg
    width="297"
    height="62"
    viewBox="0 0 297 62"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g filter="url(#filter0_i_601_18)">
      <rect width="297" height="62" fill="#D9D9D9"></rect>
    </g>
    <rect x="0.5" y="0.5" width="296" height="61" stroke="black"></rect>
    <defs>
      <filter
        id="filter0_i_601_18"
        x="0"
        y="0"
        width="297"
        height="66"
        filterUnits="userSpaceOnUse"
        color-interpolation-filters="sRGB"
      >
        <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
        <feBlend
          mode="normal"
          in="SourceGraphic"
          in2="BackgroundImageFix"
          result="shape"
        ></feBlend>
        <feColorMatrix
          in="SourceAlpha"
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
          result="hardAlpha"
        ></feColorMatrix>
        <feOffset dy="4"></feOffset>
        <feGaussianBlur stdDeviation="2"></feGaussianBlur>
        <feComposite
          in2="hardAlpha"
          operator="arithmetic"
          k2="-1"
          k3="1"
        ></feComposite>
        <feColorMatrix
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"
        ></feColorMatrix>
        <feBlend
          mode="normal"
          in2="shape"
          result="effect1_innerShadow_601_18"
        ></feBlend>
      </filter>
    </defs></svg
  >
<div class="text-0-1-3">LOGIN</div>
  <svg
    width="297"
    height="62"
    viewBox="0 0 297 62"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g filter="url(#filter0_i_601_23)">
      <rect width="297" height="62" fill="#D9D9D9"></rect>
    </g>
    <rect x="0.5" y="0.5" width="296" height="61" stroke="black"></rect>
    <defs>
      <filter
        id="filter0_i_601_23"
        x="0"
        y="0"
        width="297"
        height="66"
        filterUnits="userSpaceOnUse"
        color-interpolation-filters="sRGB"
      >
        <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
        <feBlend
          mode="normal"
          in="SourceGraphic"
          in2="BackgroundImageFix"
          result="shape"
        ></feBlend>
        <feColorMatrix
          in="SourceAlpha"
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
          result="hardAlpha"
        ></feColorMatrix>
        <feOffset dy="4"></feOffset>
        <feGaussianBlur stdDeviation="2"></feGaussianBlur>
        <feComposite
          in2="hardAlpha"
          operator="arithmetic"
          k2="-1"
          k3="1"
        ></feComposite>
        <feColorMatrix
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"
        ></feColorMatrix>
        <feBlend
          mode="normal"
          in2="shape"
          result="effect1_innerShadow_601_23"
        ></feBlend>
      </filter>
    </defs>
  </svg>
  <div class="text-0-1-6">REGISTER</div>
</div>


CSS
.container--0- {
  position: absolute;
  left: -220px;
  top: -478px;
  width: 434px;
  height: 928px;
  background-color: #870709;
  justify-content: start;
  align-items: start;
}
.text-0-1-0 {
  width: 292px;
  height: 40px;
  color: #000000;
  font-size: 40px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-3 {
  width: 125px;
  height: 48px;
  color: #000000;
  font-size: 40px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-6 {
  width: 198px;
  height: 48px;
  color: #000000;
  font-size: 40px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}


HTML
<div class="container--0-">
  <div class="text-0-1-0">MUSIC EVENT</div>
  <div class="text-0-1-1">
    Raise Your Mic.<br />Beyond The Voice.<br />Breaking Records.<br />Bring
    music to life.<br />Face the music.<br />Let the Music Speak.<br />Music =
    Life.<br />
  </div>
</div>
.container--0- {
  position: absolute;
  left: 260px;
  top: -433px;
  width: 440px;
  height: 956px;
  background-color: #ee7a05;
  justify-content: start;
  align-items: start;
}
.text-0-1-0 {
  width: 324px;
  height: 61px;
  color: #d9d9d9;
  font-size: 40px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: center;
  vertical-align: top;
}
.text-0-1-1 {
  width: 452px;
  height: 798px;
  color: #000000;
  font-size: 40px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}

HTML
<div class="container--0-">
  <div class="text-0-1-0">REGISTARTION FORM</div>
  <svg
    width="326"
    height="47"
    viewBox="0 0 326 47"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="326" height="47" fill="white"></rect></svg
  ><svg
    width="326"
    height="47"
    viewBox="0 0 326 47"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="326" height="47" fill="white"></rect></svg
  ><svg
    width="326"
    height="47"
    viewBox="0 0 326 47"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="326" height="47" fill="white"></rect></svg
  ><svg
    width="326"
    height="47"
    viewBox="0 0 326 47"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="326" height="47" fill="white"></rect></svg
  ><svg
    width="326"
    height="47"
    viewBox="0 0 326 47"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="326" height="47" fill="white"></rect></svg
  ><svg
    width="326"
    height="47"
    viewBox="0 0 326 47"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="326" height="47" fill="white"></rect></svg
  ><svg
    width="326"
    height="47"
    viewBox="0 0 326 47"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="326" height="47" fill="white"></rect>
  </svg>
  <div class="text-0-1-8">EMAIL ID</div>
  <div class="text-0-1-9">MOBILE NO</div>
  <div class="text-0-1-10">DEPARTMENT</div>
  <div class="text-0-1-11">REGISTER NO</div>
  <div class="text-0-1-12">AGE</div>
  <div class="text-0-1-13">GENDER</div>
  <div class="text-0-1-14">NAME</div>
</div>

CSS
.container--0- {
  position: absolute;
  left: 740px;
  top: -404px;
  width: 440px;
  height: 956px;
  background-color: #148e9c;
  justify-content: start;
  align-items: start;
}
.text-0-1-0 {
  width: 354px;
  height: 22px;
  color: #ffffff;
  font-size: 32px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: center;
  vertical-align: top;
}
.text-0-1-8 {
  width: 141px;
  height: 39px;
  color: #000000;
  font-size: 32px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: center;
  vertical-align: top;
}
.text-0-1-9 {
  width: 179px;
  height: 39px;
  color: #000000;
  font-size: 32px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: center;
  vertical-align: top;
}
.text-0-1-10 {
  width: 223px;
  height: 39px;
  color: #000000;
  font-size: 32px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: center;
  vertical-align: top;
}
.text-0-1-11 {
  width: 214px;
  height: 39px;
  color: #000000;
  font-size: 32px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: center;
  vertical-align: top;
}
.text-0-1-12 {
  width: 68px;
  height: 39px;
  color: #000000;
  font-size: 32px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: center;
  vertical-align: top;
}
.text-0-1-13 {
  width: 132px;
  height: 39px;
  color: #000000;
  font-size: 32px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: center;
  vertical-align: top;
}
.text-0-1-14 {
  width: 98px;
  height: 39px;
  color: #000000;
  font-size: 32px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: center;
  vertical-align: top;
}

HTML
<div class="container--0-">
  <svg
    width="378"
    height="137"
    viewBox="0 0 378 137"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g filter="url(#filter0_i_602_30)">
      <rect x="1" y="1" width="376" height="135" fill="white"></rect>
    </g>
    <rect x="0.5" y="0.5" width="377" height="136" stroke="black"></rect>
    <defs>
      <filter
        id="filter0_i_602_30"
        x="0"
        y="0"
        width="378"
        height="141"
        filterUnits="userSpaceOnUse"
        color-interpolation-filters="sRGB"
      >
        <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
        <feBlend
          mode="normal"
          in="SourceGraphic"
          in2="BackgroundImageFix"
          result="shape"
        ></feBlend>
        <feColorMatrix
          in="SourceAlpha"
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
          result="hardAlpha"
        ></feColorMatrix>
        <feOffset dy="4"></feOffset>
        <feGaussianBlur stdDeviation="2"></feGaussianBlur>
        <feComposite
          in2="hardAlpha"
          operator="arithmetic"
          k2="-1"
          k3="1"
        ></feComposite>
        <feColorMatrix
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"
        ></feColorMatrix>
        <feBlend
          mode="normal"
          in2="shape"
          result="effect1_innerShadow_602_30"
        ></feBlend>
      </filter>
    </defs>
  </svg>
  <div class="text-0-1-1">
    We wish every student to participate and enjoy the event ....!!!!
  </div>
  <div class="text-0-1-2">THANK YOU</div>
  <div class="text-0-1-3">
    Contact Us<br />Email<br />saveetha@gmail.com<br />phone<br />9856357852<br />8765478557<br />
  </div>
</div>


CSS
.container--0- {
  position: absolute;
  left: 1220px;
  top: -377px;
  width: 440px;
  height: 956px;
  background-color: #18c543;
  justify-content: start;
  align-items: start;
}
.text-0-1-1 {
  width: 340px;
  height: 120px;
  color: #000000;
  font-size: 24px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: center;
  vertical-align: top;
}
.text-0-1-2 {
  width: 291px;
  height: 58px;
  color: #ffffff;
  font-size: 48px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: center;
  vertical-align: top;
}
.text-0-1-3 {
  width: 353px;
  height: 239px;
  color: #000000;
  font-size: 32px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: center;
  vertical-align: top;
}
```

## OUTPUT:
![alt text](<Screenshot 2024-12-30 232035.png>) 
![alt text](<Screenshot 2024-12-30 232046.png>) 
![alt text](<Screenshot 2024-12-30 232058.png>) 
![alt text](<Screenshot 2024-12-30 232106.png>)
## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.

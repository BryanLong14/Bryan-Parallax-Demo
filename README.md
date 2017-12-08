# Bryan's Parallax Demonstration

## What is it?
This code adds basic parallax to a site. Specifically, it slides a colored overlay on top of two static background images which change as the user scrolls.

See the live version at my <a href="https://bryan-paralla.firebaseapp.com/">hosted website.</a>

## How The Code Works in the HTML
In the HTML document, add two DIVs which will hold background images and a DIV that will hold the colored overlay. It is important to place the DIVS in your HTML in the following order:
<ul>
  <li>FirstBackgroundImage</li>
  <li>colorOverlay</li>
  <li>SecondBackgroundImage</li>
</ul>

## How The Code Works in the CSS
Set your background image URLs and give them the following attributes:
<ul>
  <li>background-size: cover</li>
  <li>height: 100vh</li>
  <li>background-attachment: fixed</li>
  <li>background-position: center;</li>
  <li>background-repeat: no-repeat;</li>
</ul>


On your colored overlay set the height to 100vh and then style it as you see fit.

Feel free to look at my code! All images copyright Bryan Long.


The game has been deployed on Netlify 🔗 --> https://etsi.netlify.app/




![Capture](https://user-images.githubusercontent.com/43856395/115306729-e7a9b500-a170-11eb-9df9-611aed9528b1.JPG)



![](README.jpg)

# JAVASCRIPT | ETCH-A-SKETCH


#### INSTRUCTIONS

1. Create a webpage with a 16x16 grid of square divs
   1. Create the divs using JavaScript... don't try making them by hand with copy and pasting in your html file!
   2. Best to put your grid squares inside another "container" div (that one can go directly in your html)
   3. There are several different ways to make the divs appear as a grid (versus just one on each line) feel free to use any or play with each of them:
      1. float/clear
      2. inline-block
      3. flexbox
      4. CSS Grid
   4. Be careful with borders and margins, they can adjust the size of the squares!
   5. "OMG, Why isn't my grid being created???"
      1. Open your browser's developer tools
      2. Check if there are any errors in the JavaScript console
      3. Check your "elements" pane to see if the elements have actually shown up but are somehow hidden.
      4. Go willy-nilly and add  `console.log` statements in your JavaScript to see if it's actually being loaded.

2. Set up a "hover" effect so that the grid divs change color when your mouse passes over them, leaving a (pixelated) trail through your grid like a pen would.
   1. Hint: "hovering" is what happens when your mouse enters a div and ends when your mouse leaves it.. you can set up event listeners for either of those events as a starting point.
   2. There are multiple ways to change the color of the divs, including:
      1. adding a new class to the div
      2. changing the div's background color using JavaScript.

3. Add a button to the top of the screen which will clear the current grid and send the user a popup asking for how many squares per side to make the new grid.  Once entered the new grid should be generated _in the same total space as before_ (e.g. 960px wide) and now you've got a new sketch pad.
   1. Research `button` tags in HTML and how you can make a JavaScript function run when one is clicked.
   2. Also check out `prompt`s
   3. You should be able to enter `64` and have a brand new 64x64 grid pop up without changing the total amount of pixels used

4. (Optional): Instead of just changing the color of your grid from black to white (for example) have each pass through it with the mouse change to a completely random RGB value.   Then try having each pass just add another 10% of black to it so that only after 10 passes is the square completely black.


[Project page](https://athena.socialhackersacademy.org/topic/project-etch-a-sketch/)

---

_Photo by lizzieerwood on Flickr_

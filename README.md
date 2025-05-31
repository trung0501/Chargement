🏷️ Program name: Loading Animation

🎯 Program Purpose: Create a dynamic effect to display "loading" notifications to provide a visual and vivid user experience while waiting for the website content to be downloaded or processed.

🧩 The main component of the program:

    📄 HTML: 
     . <div class="wrapper"> tag: Wraps the entire animation.
     . Three <div class="circle"> tags: Represents three balls jumping up and down.
     . Three <div class="shadow"> tags: Creates a shadow effect under the balls.
     . <span> tag: Displays the word “Loading”.

    🎨 CSS:
     . Specifies the display style, positioning, color, and animation effects for HTML elements.
     . Two main animations: @keyframes circle: Controls the jumping effect of the balls.
                            @keyframes shadow: Creates a shadow effect that scales with the movement of the ball.

⚙️ Principle of operation:

  1. As the page loads, the white balls (.circle elements) start bouncing up and down with varying time delays, creating a smooth and continuous motion.

  2. The shadows below (.shadow elements) stretch and stretch in sync with the ball’s movement to create a three-dimensional feel.

  3. The “Loading” text stays fixed at the bottom to notify the user of the status.

  4. The infinite loop animation effect at .5s intervals keeps the animation running throughout the waiting time.

✅ Advantages:

  1. The interface is vivid, modern, creating a professional feeling for the website.

  2. Smooth effect thanks to the use of CSS Animation, no javascript.

  3. Easy to customize (glossy, color, motion speed).

  4. Good compatibility with most modern browsers.

❌ Limit:

  1. There is no logic function or actual state processing - just a display effect, not linked to the actual data download process.

  2. Do not support users when JavaScript or CSS is disabled.

  3. Do not respond to real time: Do not know when the content is actually completed (unless combined with JS to hide the effect when completing the load).

<h1> Pong-game </h1>

This is a basic implementation of the Atari Pong game, but it's missing a few things intentionally and they're left as further exploration for the reader.

<h1>Web Creator J5.JS

I used their library to build the game Pong

![image](https://user-images.githubusercontent.com/89170789/221024443-c0b3dc90-5f3b-425c-8eab-516f505b273b.png)

The p5.js is a JavaScript library for creative coding. A collection of pre-written code, it provides us with tools that simplify the process of creating interactive visuals with code in the web browser.


---------------------------------------------------------------------------------------------------------------
![image](https://user-images.githubusercontent.com/89170789/221023348-41e9af6b-1d81-462e-9118-792aef77447f.png)

<h1>Further Exploration</h1>

<h2>Score</h2>

- When a ball goes past a paddle, the other player should score a point. Use [context.fillText()](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/fillText) to display the score to the screen
- Mobile and touchscreen support
  - Allow the game to be scaled down to a phone size. See https://codepen.io/straker/pen/VazMaL
  - Support [touch controls](https://developer.mozilla.org/en-US/docs/Web/API/Touch_events)


- Ball trajectory
  - The ball should change trajectory based on where it hit the paddle. For example, if it hit the topmost part of the paddle it should have a sharp angle upward, whereas if it hit the direct middle of the paddle it should move completely flat towards the other payer.



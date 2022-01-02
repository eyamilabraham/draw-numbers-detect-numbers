# draw-numbers-detect-numbers
- This is a classifier of written numbers, where you can draw in the browser a number between 0 and 9.
- When you click on predict it will try to tell what number it is, using Tensorflow.js, based on a model trained in Python with Tensorflow.

Starts a server in the folder

- This project uses a Tensorflow.js model, which to load requires access via http/https. For that you can use any server, but here is a way to do it:

  1. Download Python to your computer
  2. Open a command line or terminal
  3. Navigate to the folder where you downloaded the repository
  4. Run the command python -m http.server 8000
  5. Open a browser and go to http://localhost:8000

# APP

- Draw with the mouse or your finger (only smarthpones) on the square canvas a number from 0 to 9, and click on "Predict". To clear the canvas click on "Clear".

DiceAid 

In the Fall of 2024, I competed in HackUmass and I was on a team with fellow students Artem Plotkin and David Lowden and we designed DiceAid
We had 36 hours to design and build a project of our choice

We all started thinking about dungeons and dragons and how physical dice are really important to the overall style of the game
You can't replace them with an online dice roller
So in turn we came up with DiceAid - it mimics an online dice roller and is able to effectively count/pronouce/show on screen the dice data
but you use real dice

What is it?
  DiceAid is a machine based around a Raspberry Pi 4B with an attached camera module that overlooks a dice game arena
  The dice arena has a lever arm powered by a stepper motor that simulates the rolling of dice
  Then, there is a sweeper that sweeps the dice off the area and back into the level arm for the next roll

  Before the Dice are swept away, an image is taken of the dice, from there, that image is hyper colorized and put
  into black and white to get high contrast of any light and dark areas
  Then a method takes in the image pixels and according to the calibration finds dots in the image of the size expected
  Any dots found are marked with a dot

  The Pi then outputs the image with the marked dots as well as the count of the number of dots on the dice AKA the score

Further Ideas
  Since again this project had Dungeons and Dragons in mind, we were hoping to turn our DiceAid into more of an artistic set piece 
  That would integrate well into the game itself
  Where you can use your custom dice and send it down say a magical tower for the score to be said alooud to the group 

This project worked fairly well, there were few errors in marking wrong areas as dots, there is a larger error in
not marking enough dots - I do not have the exact statistics on accuracy 

I learned a lot from this project and I happy to have all of our work stored here - minus our physical machine!

In the end we WON BEST HARDWARE HACK which was a great reward for our hard work

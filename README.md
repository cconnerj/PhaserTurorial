PHASER GAME

1. Why did you choose this subject?
  - I chose this subject simply because it is something i've always wanted to learn.  Creating a game is something i would be passionate about making so i will stay motivated

2. How were you first made aware of it?
  - I was first made aware of Phaser through suggestions in the GA lesson plan

3. What problem does it solve?

  - It solves the problem of having to write really complex code for lets say the physics of a player.  There is a file (phaser.min.js) that holds all of the conventions for this by simply calling, for example, body.physics.

4. Why does one use it?
  - They use it to create 2D browser games at ease.

5. What are the alternatives?
  - Unity, Godot Engine, and Construct to name a few

6. What is it similar to, if anything?
  - Godot Engine, because it is open source and also have compatibility with mobile devices.  Also has an easy to use library for ease of coding.

7. What is the history of this technology?
  - Created by Richard Davey, in order to create a easy way for people to create 2d games without having a ridiculous background in coding in order to create them.
  - It is open source, so PhotonStorm (Created by Richard Davey) is maintaining it while anyone can help update the library with their own code.

8. What is your opinion on the technology after having built something with it?
  - I really like it because it makes something really difficult to code from scratch really easy by having a library of code to reference so making calls to something like collision is very easy, and you wont have to write out the complex code for it.

9. What are the biggest conceptual hurdles (if any) you encountered when researching this?
  - Hosting it on a server provided a bit of a problem, it said to run it through a "webroot" directory on your computer in the tutorial, so on mac its in the library directory, but couldn't get it to work.  I ended up just using node.js from what we learned in class and it worked out well.

10. What resources do you recommend for interested students?
  - https://phaser.io/learn, https://phaser.io/community
    - 2 great resources for learning the basics and help with complications you may come across in Phaser.

11. What article or forum was most helpful to you in learning this?
  - https://phaser.io/community/forum
    - (You have to register for the forum)

12. What are 3 interview questions one might be asked about this technology?
  - How does the animation of sprites work when writing out the code for moving left and right?
  - How do you implement keyboard strokes to your game?
  - What should you preload into your game before it starts? (what goes into the preload function)


Insructions to run:
  - Have a script tag where your phaser.min.js file is located (found it in the tutorial used for this specific game, located in the repository under phaser tutorial directory)
      - I moved the js file from the tutorial directory to the gameapp directory
  - Have node.js installed on computer
  - Run hs in the cli in the directory where your game is located
  - Can be deployed to Heroku

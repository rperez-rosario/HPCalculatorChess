# HPCalculatorChess
A chess game implemented on/for the HP Prime Graphing Calculator using its api and programming language (HP PPL.)

See it in action:
[https://www.youtube.com/shorts/HLDzqyRd3_Y](https://www.youtube.com/shorts/My8YHUkvzI4)

<img width="300" alt="image" src="https://github.com/rperez-rosario/HPCalculatorChess/assets/24212098/9a273ddf-95f5-40d1-b06f-a3f7d99c292e">


<pre>The program is structured around the con-
cept of processing user or intelligent a-
gent (i.a.) input affecting the game's 
state, and updating the user interface ba-
sed on said state as the user or i.a. in-
put loop is consumed by the program. This
concept is commonly known as the model, 
view, controller (MVC) software design pa-
ttern.</pre>

The main four (4) program functions are:

<pre>a_chess: Main program/entry point. Calls
         the other main functions, and 
         implements and executes the pla-
         yer's and/or i.a.'s input loop. 
a_igst:  Initializes and stores the game's
         current state (model.)
a_pui:   Prints the game's user interface
         based on the game's current sta-
         te (view.)
a_ppi:   Processes user or i.a. input and
         affects the game's current state 
         accordingly (controller.)</pre>

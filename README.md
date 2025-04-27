# info1113-comp9003-p0-assignment-solved
**TO GET THIS SOLUTION VISIT:** [INFO1113-COMP9003 P0 Assignment Solved](https://www.ankitcodinghub.com/product/info1113-comp9003-p0-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;124376&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;INFO1113-COMP9003 P0 Assignment Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
INFO1113 / COMP9003 Assignment

Task Description

In this assignment, you will create a game in the Java programming language using the Processing library for graphics and gradle as a dependency manager. In the game, players control tanks which can aim and

fire at each other. Players gain score for hitting another player’s tank, causing them to lose health. After Assignment Project Exam Help

all levels are completed, the player with the highest score wins.

Working on your assignment

You have been given a scaffold which will help you get started with this assignment. You can download the scaffold onto your own computer and invoke gradle build to compile and resolve dependencies. You will be using the Processing library within your project to allow you to create a window and draw graphics. You can access the documentation from here.

Gameplay

The game contains a number of entities that will need to be implemented within your application.

Level

Each level is read from a text file of characters 28×20. The size of the window should be 864×640, meaning each character in the file corresponds to 32×32 pixels.

• X – denotes the terrain height. This can change during gameplay when hit by projectiles. To smooth out the terrain, see the section on page 3.

• Letters (A,B,C,D,E, etc.) – starting position of human players. The order of player turns, and the order in the scoreboard, is alphabetical order.

• Numbers (0,1,2,3,4,5,6,7,8,9) – starting position of AI players (optional for extension, otherwise they can just be normal human players as well)

• T – location of trees. They are always present on top of the terrain – so if the terrain changes, so do any trees on top of it. The initial position of trees is randomised up to 30 pixels around its starting point.

• Spaces – empty space, just ignore it.

The level layouts are defined in files provided in the “layout” attribute of the JSON configuration file described below. Each level must have an associated layout file.

How to smooth the level terrain:

below:

Config

The config file is in located in config.json in the root directory of the project (the same directory as build.gradle and the src folder). Use the simple json library to read it. Sample config and level files are provided in the scaffold.

The map layout files will also be located in the root directory of the project. However, sprites or images such as the background, and trees will be located in the resources folder (src/main/resources/Tanks/) or (build/resources/main/Tanks/).

In addition to providing the filenames of these files, the configuration file also provides the colours that should be used for the foreground of each level, and players.

The format is “R,G,B” containing the red,

Assignment Project Exam Helpgreen and blue components of the colour (0-

• layout: the level file containing the characters determining the initial terrain, player positions, and trees (see pages 2 and 3 above).

• background: the image which should be displayed in the background, behind the terrain and everything else.

• foreground-colour: the colour to render the terrain in for this level.

• trees (optional): The sprite image to use for trees in this level. If not specified, your program should not crash (either assume the level contains no trees so don’t render any, or use a default sprite such as tree1.png).

Tanks

Initial positions of tanks are provided in each level’s layout file. Each player can control the tank’s turret movement, move it across the terrain, or increase and decrease the power level (the key must be held for these actions). Once they fire a shot (pressing the spacebar), their turn ends. A summary of the player input actions are in the table below:

Keyboard input Action Rate of change

UP arrow Tank turret moves left +3 radians per second

DOWN arrow Tank turret moves right -3 radians per second

LEFT arrow Tank moves left across terrain -60 pixels per second

RIGHT arrow Tank moves right across terrain +60 pixels per second

W Turret power increases +36 units per second

S Turret power decreases -36 units per second

SPACEBAR Fire a projectile (ends turn)

Note: the rate of change should be continuous (ie. per frame) and does not have to be exact, but is an indication to guide you in optimising user experience.

Tanks can only move across the terrain as long as they have fuel ( denoted in the top right corner). Movement consumes 1 unit of fuel per horizontal pixel moved. Tanks start with 250 initial fuel in each

level. Assignment Project Exam Help

How to change the turret’s position using the angle from the vertical:

Projectiles

The player’s turn ends after they fire a projectile (press spacebar).

Explosions

When a projectile makes contact with the terrain, it causes an explosion. The default explosion radius is 30 pixels. Any tanks within the radius will sustain up to 60 hp lost depending on how close they are to the impact site, reducing linearly the further the distance away. For example, with radius=30, a tank which is distance 15 pixels away (half the radius) from the impact will sustain only 30hp damage. A tank which is 10 pixels away will sustain 40hp damage, and a tank which is 20 pixels away will sustain 20hp damage. A tank which is 31 pixels away will sustain no damage since it’s outside the radius.

Assignment Project Exam Help

0.2 seconds. During this time:

• Red circle expands from radius 0 to explosion radius (in this case 30px)

• Yellow circle expands from 0 to 20% of the explosion radius (in this case 6px)

The terrain will also be destroyed in a radius of 30 pixels around the impact site. Note that terrain cannot be floating, so if the impact is on the side of a hill, terrain above falls to fill the crater. Any trees on the terrain also fall to remain on top of the terrain. Trees are not destroyed by impacts.

Wind

Wind is a force that acts on projectiles in the air, in the horizontal (x) direction. It can blow either left or right, denoted by the different icons (shown above) and has a magnitude. The force imparted by wind is an acceleration of approximately w*0.03 pixels per second.

Wind is initially a random value between -35 and 35 (where negative values represent wind blowing to the left, and positives values are blowing to the right). After each turn, it changes by a random value from between -5 to 5 (inclusive of both).

Wind is displayed in the top right corner of the screen.

Powerups

During their turn, players can purchase powerups by using their score as currency. Powerups can only be purchased when the player can afford it, otherwise the action does nothing.

INFO1113 students must implement the following powerups:

• Repair kit (key: r, cost: 20) – repairs the player’s tank by increasing health by 20 (maximum health is 100).

• Additional fuel (key: f, cost: 10) – increase the player’s remaining fuel by 200.

COMP9003 students must implement the following powerups:

• Additional parachute (key: p, cost: 15) – increase the player’s remaining parachutes by 1.

• Larger projectile (key: x, cost: 20) – the next shot fired by this player will have double the radius (60 instead of 30). Projectile damage is not increased, but will affect tanks within the radius according to the previous rules (proximity distance). A visual indication needs to be shown in the GUI / HUD that the next projectile to be fired will be a larger one.

Scoreboard

The scoreboard is persistent across levels. When a projectile fired by a player

damages another player’s tank, the player who fired that projectile gains Assignment Project Exam Help

score equal to the hp damage caused. A player does not gain score when a projectile they fire damages their own tank.

displayed in the top right corner. The text colour for each player is the same as their tank colour.

A level ends when there is only one tank remaining in play. The next level is loaded after 1 second, or whenever this tank fires a shot. The sequence of levels is the order they are provided in the configuration file.

When the last level ends, the game ends – display the player with the highest score as the winner (eg. “Player A wins!”) and then in the centre of the screen, display the final scores in a box filled with a colour corresponding to the player’s colour, and slightly lighter and transparent. The scores (and the corresponding players who achieved them) should be displayed in descending order (highest to lowest score), with a delay of 0.7s between when each one appears.

Application

Your application will need to adhere to the following specifications:

• The window must have dimensions 864×640

• The game must maintain a frame rate of 30 frames per second.

• Your program must not exhibit any memory leaks.

• You must use the processing library (specifically processing.core and processing.data), you cannot use any other framework for graphics such as javafx, awt or jogl

Extension

• Additional powerups (eg, if you are doing INFO1113, you can implement the COMP9003 powerups as an extension, and vice versa). Or powerups of your own choosing, such as:

o Shield (key: h, cost: 20) – protect your tank from taking damage the next time it’s hit.

Assignment Project Exam HelpAfter it is gets hit, the shield is destroyed (absorbed to sustain the blast). This must be

indicated in the GUI (like with a blue transparent bubble around the tank).

• Computer-controlled players. A targeting AI which can compute the trajectory of a projectile and adjust its aim to focus on hitting a player.

• Sound effects

Please ensure you submit a config and level layout file with the features of your extension (if the extension required changes to the level or config files), and ensure the extension doesn’t break any of the default behaviour. Also, describe your extension functionality in the report.

Marking Criteria (20%)

Final Code Submission and Demo (12%)

You will need to have implemented and satisfied requirements listed in this assignment. Make sure you have addressed the following and any other requirements outlined previously.

• Window launches and shows map layout correctly.

• Terrain display is correct – smooth curve, and matches level layout file

• Player starting positions and tree positions are correct, and correct tree type is rendered

• Configuration file is correctly read in – initial values for game state are used from config (player colours, level backgrounds and foregrounds)

• Multiple players take turns at controlling their own tank – turns are processed in alphabetical order according to config file

• Tank turret can be controlled with up/down arrow keys and angle changes (3 rad/s)

• Tank can move across terrain with left/right arrow keys (speed is 60px/s)

• Tank turret power can increase/decrease with ‘w’ and ‘s’ keys

• Tank fires a projectile according to the turret’s trajectory when the user pressed spacebar

• Projectile moves through the air and is affected by gravity and wind

• When a projectile collides with terrain, it explodes with a radius of 30 pixels

• Explosion is animated correctly

• Explosion causes damage to nearby tanks in a linearly decreasing proportion based on distance

• Tanks deploy parachute if available to fall slowly if the terrain underneath is destroyed, otherwise Assignment Project Exam Help

they fall faster (2x speed) and incur damage.

o For COMP9003: Additional parachute, and larger projectile

• When tank reaches 0 health it is destroyed with an explosion, and that player’s turn is skipped for the current level.

o Health bar which displays changes to tank’s health o Fuel indicator shows how much fuel is remaining o Parachutes indicator shows parachutes remaining o Power as a proportion of remaining health bar

o Wind indicator that changes icon depending on direction of wind

o Text for current player’s turn, and arrow that appears at the beginning of the player’s turn and lasts for 2 seconds, pointing to their tank

• Scoreboard tracks scores correctly

• Scoreboard is rendered with correct player colours

• The current level ends, and the next level is loaded when only 1 tank remains in play (after 1 second, or as soon as the player fires a shot).

• When all levels are complete, the player with the highest score is declared to be the winner and the final scores are displayed larger in the centre of the screen in a box whose background colour matches that of the winning player and is slightly transparent

• Final scores are displayed in descending order with a delay of 0.7s between each subsequent player

• Once the game has ended, a player can restart the game by pressing ‘r’

• Ensure that your application does not repeat large sections of logic

• Ensure that your application is bug-free

Testcases (3%)

During development of your code, add testcases to your project and test as much functionality as possible. You will need to construct unit test cases within the src/test folder using JUnit. To test the state of your entities without drawing, implement a simple loop that will update the state of each object but not draw the entity.

Ensure your test cases cover over 90% of execution paths (Use jacoco in your gradle build) – average of branches and instructions. Ensure your test cases cover common cases. Ensure your test cases cover edge cases. Each test case must contain a brief comment explaining what it is testing. To generate the testing code coverage report with gradle using jacoco, run “gradle test jacocoTestReport”.

Design, Report, UML and Javadoc (3%)

You will need to submit a report that elaborates on your design. This will include an explanation of any object-oriented design decisions made (such as reasons for interfaces, class hierarchy, etc) and an explanation of how the extension has been implemented. This should be no longer than 500 words. This report will be submitted through Canvas.

use this to determine whether you have appropriately used those principles to aid you in your design, as Assignment Project Exam Help

Style Guide. As part of your comments, you will need to create a Javadoc for your program. This will be properly covered in week 11 but the relevant Oracle documentation can be found here.

Report, UML and OO design: 2% Javadoc, comments, style and readability: 1%

Extension (2%)

Suggested Timeline

Page

Week 8: Begin writing the actual code for the program. Start small, for example by initially creating the map layouts and terrain, then gradually add more like player tanks. At the end of the week, you should have loading in the map and tank movement finished, as well as some sprite management. If confident, use Test Driven Development (writing test cases at same time as writing the code). Conduct a large amount of user testing to ensure the initial mechanics work as expected.

Weeks 9-10: Develop more gameplay features, such as the projectile movement, wind, collisions with terrain and tanks, powerups and scoreboard. Sprite management should be streamlined at this point. You

should have a fairly high code coverage for your test cases at this stage. If you are noticing any questionable design decisions, such as God classes or classes that are doing things they logically should not be doing, this is the time to refactor your code. Think about what extension you want to make and start to implement it.

Week 11: Finish developing the remaining features for your program, notably the configuration file, GUI enhancements, timers and level progression. Additionally, finish writing your testing suite. Create the UML and Javadoc for the program. Fix any remaining bugs that your code exhibits. Submit your code to Ed (by uploading the entire project and pressing MARK) and submit your UML to Canvas in PDF form.

Assignment Project Exam Help

By submitting this assignment you declare the following:

Page

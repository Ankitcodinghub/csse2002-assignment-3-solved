# csse2002-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [CSSE2002 Assignment 3 Solved](https://www.ankitcodinghub.com/product/csse2002-assignment-3-15-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116089&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSSE2002  Assignment 3  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
Abstract

In this assignment, you will take supplied code and create graphical user interfaces to use it. You should not modify the supplied code at all. Copying the supplied code and modifying the copy is not allowed either.

Do not use anything outside of the java or javafx package hierarchies.

Preamble

If you have questions about what is acceptable, please ask.

For this assignment you are expected to produce a graphical user interface which has the same appearance as shown in this task sheet (there are a number of ways to do this). However, there are some aspects which are determined by your computer’s graphical environment rather than your Java program (the window title bar is the main example). See Figure 1. The only thing you need to fix in your title bar is the title text.

Supplied material

• This task sheet

• A .zip file containing supplied source code for you to build on. Do not modify the supplied files except to add required methods.

Required classes

CrawlGui

CrawlGui is to extend javafx.application.Application. When run, it expects a single command line argument which is the name of a map file to load. If this argument is missing the message “Usage: java CrawlGui mapname” is to be printed to standard error and the program will exit with status 1. If the argument is present but the map can not be loaded for some reason, “Unable to load file” is to be printed to standard error and the program will exit with status 2. (Any output to standard error should be followed by a newline).

There are three main parts at the top level.

• Button area: The area to the right, it should keep a fixed width when the window is resized.

• Message area: The area at the bottom displays text messages (It should occupy the full width of the window and resize with the window).

Figure 1: Window title bar.

Figure 2: CrawlGUI window immediately after startup.

• Map area: displays the map. It should resize as the window is resized.

Cartographer

Cartographer is to extend javafx.scene.canvas.Canvas. This class will be responsible for rendering the “map” in the GUI. It will draw all reachable rooms starting from a “start room”. (Pay particular attention to the update() method).

The player is to be indicated with a @ in the top left quadrant (ie the top left corner) of the room. If any treasure is present in the room, a $ is drawn in the top right quadrant. If any live critters are present in the room, a M is drawn in the bottom left quadrant. Any dead critters are indicated with a m in the bottom right quadrant.

Your cartographer must be large enough to show the entire loaded map. That is, your initial window size will vary depending on the map being loaded.

Functionality

In all of the following “displayed” means add to the message area. Whenever a list of things is to be displayed, each item is to be on a separate line. Where dialog boxes are required they will all use the same layout. Suggestion: Look at the TextInputDialog class and its showAndWait method.

Once the map has loaded successfully, it will display “You find yourself in ” followed by the description of the start room.

Figure 3: CrawlGUI window after being resized (to illustrate resize behaviour).

North/South/East/West buttons

If there is no exit in the specified direction, display “No door that way”. If there is an exit in that direction but you can’t leave, display “Something prevents you from leaving”. Otherwise, move to the specified room and display “you enter ” followed by the description of the room.

Look button

Display the following information: description_of_room – you see: followed by the short descriptions of each Thing in the room (add a leading space for each item). Then

You are carrying:

followed by the short descriptions of each Thing (add a leading space for each item) you are carrying. Then

“worth total_worth_of_carried_items in total”

(without the quotes and with the italics text replaced). Formatted for one decimal place. See Figure 4 for an example.

Examine button

Show a dialog box (see Figure 5) to get the short description of the Thing to examine. The first matching item will have its long description displayed. Check the player’s inventory first, then if no match is found, the contents of the current room. If no match is found, display “Nothing found with that name”.

Figure 4: Output having just clicked Look

Figure 5: Dialog box to use when the Examine button is clicked (and main window)

Figure 6: Dialog box to use when the Drop button is clicked

Drop button

Show a dialog box (See Figure 6) to get the short description of the item to remove from the player’s inventory and add to the current room. If the player is not carrying a matching item, display “Nothing found with that name”

Take button

Similar to Drop but the dialog box is to be titled “Take what?”. Objects of type Player should be skipped when looking for short description matches. There are additional cases where the operation will fail (silently):

• If an attempt is made to pick up a live Mob

• If the leave call to remove the item returns false. [Remember that, to remove an item from a room, you will need to call leave on the room].

Fight button

Show a dialog box (titled “Fight what?”) to get the short description of a Critter in the current room to fight. If the fight occurs, display either “You won” or “Game over” as appropriate. (If you lose the fight, all of the buttons on the GUI should be disabled). Silent failures will occur if:

• There is no matching Critter.

• There is a matching Critter but it is not alive.

Save button

Show a dialog box (titled “Save filename?”) for a file name to use with MapIO.saveMap. Display either “Saved” or “Unable to save” as appropriate.

Marking

F 65 Human Implementation and functionality:

Does the submission conform to this task sheet?

S 35 Human Style and clarity.

The overall assignment mark will be A2 = F + S with the following adjustments:

1. If F &lt; 5, then S = 0 “style” will not be marked.

2. If S &gt; F, then S = F.

Functionality marking

Style marking

As a style guide, we are adopting the Google Java Style Guide https://google.github.io/styleguide/javaguide.html with some modifications:

4.2 Indenting is to be +4 chars not +2.

4.4 Column limit for us will be 80 columns.

4.5.2 First continuation is to be +8 chars.

• Java source files must be encoded as either ASCII or UTF-8.

Naming 5

Commenting 11

Readability and layout 8 Implementation practices (including OO) 11

Note that this category does involve some aesthetic judgement (and the marker’s aesthetic judgement is final).

Submission

Submission is via the course blackboard area Assessment/Ass3/Ass3 Submission.

Your submission is to consist of a single .zip file containing a src/ directory with all of your java files directly inside it.

Note: you must submit supplied classes as well.

Your classes must not declare themselves to be members of any package.

Remember that java filenames are case sensitive even when your filesystem isn’t.

Revisions

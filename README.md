We won 3rd place in this hackathon.
Written in Processing / Java


## Bakeoff Prompt:
You will be given source code for a simple application that displays a 4x4 grid of square buttons. These light up one at a time; users must click the lit buttons as accurately and quickly as they can. Currently the application simply lets you click with the mouse. You mission is to devise a technique that facilitates clicking these buttons (every button must be clickable at any instant). Accuracy must be above 90% to be feasible. Time is the important measure. Open design challenge, so email me ideas you think might break the rules.

## Our Narrative/instructions:
Idea 1
Our goal is to decrease the time the user takes to go through all the boxes. In order to accomplish this task, we provide the user with helpful information. If you see in this screen, the numbers on the boxes will guide the user through the random sequence. The numbers allow the user to know ahead of time where the next lit box will come up and in result will decrease the amount of time the user takes to click all the random boxes.

## Idea 2
Our goal is to decrease time and increase the accuracy of the user when he/she clicks all the boxes. In order to accomplish this task, we decided to implement four changes. First, we decided to highlight the box purple once the cursor is inside the box. This will improve accuracy since users will be aware when the cursor is inside the box in order for it to be considered a hit. Second, we decided to increase the size of the boxes and decrease the gap between the boxes. This will improve accuracy since the bigger boxes increase the area in which a cursor can click the box for it to be considered a hit. In addition, by decreasing the gap between the boxes users will take less time to get to one box from another. However, we still found it valuable to keep some gap between the boxes in order for the user to have enough space to move from one box to the other without being confused. Third, we added in the option to use the space key or any other key to ‘click’ the box. After several trials where we had the user using the trackpad to both move and click, we realized that users could be hitting buttons faster if they used both of their hands. This will encourage the user to use both hands and will decrease the time it takes for the user to click all the boxes. However, clicking on the trackpad is still enabled so users can still click to hit a button if they choose. Lastly, we decided to change the color of the box to red instead of blue if a certain button is the target button for more than once consecutively. This will increase the accuracy and decrease the time it takes users to hit the button since users will be aware that the box will be the target button twice in a row.

## Changes/additions:
* highlighting the box when the cursor is inside the box
* make the boxes slightly bigger and decrease the gap of the boxes
* the mouse is to move, and the space key is to click
* light up the box red if it is double hit… preferencing the box?

# Scratch Project

**This is bolded** <br>
*This is italicized* <br>
~~Strikenthrough~~

numbered list
1. item one
2. item two

bulleted list
* item one
* item two

**Bat Code** <br>
When flag is clicked <br>
  Go to (-160,25) <br>
  Rotate Upright <br>
  Show <br>
  
When Spacebar is pressed <br>
  Loop forever <br>
    Wait .1 seconds <br>
    Change y by -5 units <br>
    
When Up Arrow is pressed <br>
  Change y by 20 units <br>
  
When Up Arrow is pressed <br>
  Change to Flapping Costume <br>
  Wait .1 second <br>
  Return to Normal Costume <br>

When I receive "Game Over" <br>
  Rotate Downward <br>
  Wait 5 seconds <br>
  Hide <br>
  
**Start Screen Code** <br>
When flag is clicked <br>
  Show <br>
  
When Spacebar is pressed <br>
  Hide <br>
  
**Game Over Screen Code** <br>
When flag is clicked <br>
  Hide <br>
  
When I receive "Game Over" <br>
  Show <br>
  Print "You got SCORE points!" <br>
  
**Top Pipe Code** <br>
When flag is clicked <br>
  Set SCORE to 0 <br>
  Go to (300, -34) <br>
  Hide <br>
  
When flag is clicked or When Starting as clone <br>
  Loop forever <br>
    If pipe touches Bat <br>
      Broadcast "Game Over" <br>

When I receive "Game Over" <br>
  Hide <br>
  Delete Clones <br>
  
When Spacebar is pressed <br>
  Wait 1 second <br>
  Show <br>
  Glide to (-300,-34) <br>
  Wait 1 second <br>
  Broadcast "Make Copy" <br>
  Hide <br>
  
When I receive "Make Copy" <br>
  Create Clone of Myself <br>
  
When I start as Clone <br>
  Show <br>
  Set x to 300 <br>
  Set y value to random number between -75 and 100 <br>
  Set Pipe Heights equal to y value <br>
  Loop 55 times <br>
    Wait .1 seconds <br>
    Change x by -10 units <br>
  Broadcast "Make Copy" <br>
  Delete Self <br>
  
 **Bottom Pipe Code**
When flag is clicked <br>
  Show Variable SCORE <br>
  Set SCORE to 0 <br>
  Go to (300, -34) <br>
  Hide <br>
  
When flag is clicked or When Starting as clone <br>
  Loop forever <br>
    If pipe touches Bat <br>
      Broadcast "Game Over" <br>
      
When I receive "Game Over" <br>
  Stop Sounds <br>
  Hide SCORE <br>
  Hide <br>
  Delete Clones <br>
  
When Spacebar is pressed <br>
  Wait 1 second <br>
  Show <br>
  Glide to (-300,-34) <br>
  Wait 1 second <br>
  Change SCORE by 1 unit <br>
  Broadcast "Make Copy" and "Score Ding" <br>
  Hide <br>
  
When I receive "Make Copy" <br>
  Create Clone of Myself <br>
  
When I start as Clone <br>
  Show <br>
  Set x to 300 <br>
  Set y value to Pipe Height <br>
  Loop 55 times <br>
    Wait .1 seconds <br>
    Change x by -10 units <br>
  Change SCORE by 1 unit <br>
  Broadcast "Make Copy" and "Score Ding" <br>
  Delete Self <br>
  
When I receive "Score Ding" <br>
  Start sound "SQUEAK" <br>
  Wait .5 seconds <br>
  Stop all sounds <br>

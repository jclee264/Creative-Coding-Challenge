# Creative-Coding-Challenge
<body>
  
 ## Coding Challenge Information
  * [Coding Challenge #166: Lissajous Curve Table](https://thecodingtrain.com/CodingChallenges/116-lissajous.html) 
  * After watching the video, I visited [this link](https://happycoding.io/tutorials/processing/) 
    to brush up on my processing information before beggining to refactor the code.
  * I then opened up processing on my computer, and coded along with Dan to make sure I fully understood what I was
    coding (as opposed to just copy and pasting the code)
  * After coding with Dan and documenting the code so I could remember what each part of the code did, I had to decide
    what creative things I was going to add to the code. 
  * Note: In Dan's code, he had lines being drawn where the points were going, which helped visually while coding. 
          But to clean it up afterwards, I took out that part of code so the output was just focused on the curves
          themselves. 
 
 ## Creative Add-ins
  1) Changing the colours of the curves as time progresses
        * I used [this link](https://processing.org/reference/frameCount.html) to figure out what frameCount and frameRate 
          was and then used it to make the colour change (with if statements) as the frameCount got higher. Remembering that
          when the curve drawing reset, the frameCount also had to be reset. 
  2) Adding words behind the curves 
        * I used [this link](https://processing.org/reference/text_.html) to brush up on text output in processing. 
        * Then I started by adding a title to my table, this was easy because it didn't require any looping.
        * Then I started to figure out how to output text behind the curves in the outside row and column. To do this, 
          I added a text output statement after each elipse drawn in the first row and column. I adjusted the x and y
          values of the text string so it would output in the middle of each elipse and voila. 
        * Then the tricky part, firguring out how to output text in each other row and column on the inside. The most 
          confusing part of doing this was trying to figure out which x and y values to put in the text statement.
</body>

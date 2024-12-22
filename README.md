# CSS-Grid

     flex-one dimensional layout change

Grid: two dimensional layout change


grid-template-column: It is used to mention the width of the columns.

grid-template-row: It is used to mention the height of the row.


## Line-base-placement
 -to target a box
     -row start/ column start/ row end/ column end

grid-area: Position (1/2/3/2)/ identifier
(string / number)

grid-template-areas: "identifier"

## units
    -pixels
       -grid-template-column: 100px 100px
       or repeat(2,100px);

   percentages
        grid-template-columns: 50% 50% or
        repeat(2,50%);
         //each column will take 50% width in reference to its parent.

         grid-template-columns: 1fr 1fr or
         repeat(2,1fr);
         //each column will take 1 fraction width in reference to its parent.

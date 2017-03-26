G score is basically how many tiles it takes to get to the destination from
the start tile. Each tile is weighted 1 point. So for every tile moved, the number
increases by 1. In this image, it takes 18 tiles to get to the destination tile.


![G Score][http:url/to/g_score.png]


H score is the estimated cost of tiles it should take to get to the destination
tile/cake. This number is updated every time the character moves a tile. In this
image, the H score goes up 18.

![H Score][http:url/to/h_score.png]

F score is basically the total of the two scores, G and H. This number is used
to generate the shortest path to the destination tile. This score is updated
every time the character moves. In this image, the final F score is 18. This
matches the score it should have if the G and H scores were added together.

![F Score](http:url/to/f_score.png)

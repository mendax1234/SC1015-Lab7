# SC1015 Lab7

## Graph Generator

## PseudoCode
Contributed by Yingjie
```
The environment is a m*n matrix

main:

Initially, the agent locate at the middle of first row, (x,y) == (n/2, 0)
for each loop
    The agent will move forward by 1 grip( y += 1 )
    The agent will execute search() func
    if no enemy : continue
    else:
        search() nearest enymy(nearest means smallest difference in x, but ensure y difference > x difference, the agent can only move 1 grip towards left/right for each loop )
        move towards enemy, shoot() if y diffrence > x diffrence, otherwise do not move
    
     end the game if collide with enemy(when they at same location)
    
shoot():
    bullet is initialised at position of agent, y axis increase 5 each loop
    if y of bullet >= y of target: delete target and bullet, score += 1;


search():
```

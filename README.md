# My-First-Game
An attractive 2D Snake game made using Unity3D

#How I made this
I created my first snake game in c++ when I was in my secondary school. But that used the old discontinued Borland turbo c++ for the MSDOS. 
It was a console application without any graphics. When I came to  Unity game engine, know aboutjust after doing a simple roll-a-ball tutorial
I created this game. Thanks to stackoverflow, unity docs and my determination that I created this game in just 4 days.


# Two different ways for creating the snake game
I divided the snake body into an array of small blocks. I found different logics for controlling those blocks:
1. Using a time bound approach to make a block shown at a paritcular point for a time proportional to the length of the snake. As soon
as it goes out of time its position is readjusted to a place where the head of the snake is to be.
2. Make each block shifted to the position of the next block and hence following it with the exception of the head of the snake that will
be controlled by the user.

# My approach
In unity it is very easy to create a game Object and attach a property to it. I started with the time bound approach. 
But I also wanted to add two categories of snakes to add some choices for the user.
![alt text](https://drive.google.com/open?id=15b84hrOkCfPAGEMSahVc0mOrSEwWxfdq)
I found problems in applying the time bound approach for creating the two different types of snakes. 
I tried using the second approach and with a very small adjustment I was able to create the two different snakes.



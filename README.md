# Introduction
This a simple 2D Snake game created using Unity3D. You will enjoy playing it with the Pacman music as its background song and simple yet attractive UI. 

![Main Menu](https://github.com/ShubhamK2799/My-First-Game-In-Unity/blob/master/Images/Main%20Menu.png?raw=true "Main Menu")

# Inspiration 
I created my first snake game in c++ when I was in my secondary school. But that used the old discontinued Borland turbo c++. It was a console application and that too without any graphics. When I came to know about the Unity game engine, just after doing a  simple Roll-a-Ball @ https://unity3d.com/learn/tutorials/s/roll-ball-tutorial, I was able to create this game. Thanks to stackoverflow, unity docs and its outstanding tutorials and my determination that helped me completing this game in just 4 days!

# Different ways of creating the snake game
I divided the snake body into an array of small blocks. I found different logics for controlling those blocks:
1. Using a time bound approach to make a block shown at a paritcular point for a time proportional to the length of the snake. As soon as it goes out of time its position is readjusted to a place where the head of the snake is to be.
2. Make each block shifted to the position of the next block and hence following it with the exception of the head of the snake that will be controlled by the user.

# My approach
In unity it is very easy to create a game Object and attach a property to it. I started with the time bound approach. 
But I also wanted to add two categories of snakes to add some choices for the user.
I found problems in applying the time bound approach for creating the two different types of snakes. 
I tried using the second approach and with a very small adjustment I was able to create the two different snakes.

# ScreenShots
![Screen Shot 1](https://github.com/ShubhamK2799/My-First-Game-In-Unity/blob/master/Images/Screenshot1.png?raw=true "Screen Shot 1")
![Snake Type 1](https://github.com/ShubhamK2799/My-First-Game-In-Unity/blob/master/Images/Snake%20Type%201.png?raw=true "Snake Type 1")
![Snake Type 2](https://github.com/ShubhamK2799/My-First-Game-In-Unity/blob/master/Images/Snake%20Type%202.png?raw=true "Snake Type 2")


---
layout: post
title: Design a game with strong AI equipped with reinforced learning
subtitle: Evolution Game Day1
---

![image1](https://github.com/andy-qiu1/andy-qiu1.github.io/raw/master/img/spore_1.jpg)
I love playing Spore when I was kid.  It is a game about the evolution of a species from unicellular organism to multi-planetary civilization.  You start out as a cell wandering around in the ocean.  You consume other animal and plant to get evolution point which can use to purchase traits and become more powerful. 


![image2](https://github.com/andy-qiu1/andy-qiu1.github.io/raw/master/img/spore_2.jpg)

As you become more powerful, other organism around you become more powerful.  You try to survive under increasing harsh competition, until you reach a threshold and move to land and become a animal.  As a animal, you have more options and can evolve in many different ways.  

![image3](https://github.com/andy-qiu1/andy-qiu1.github.io/raw/master/img/spore_3.jpg)

I very interested in this type of game but Spore 2 never come out, and there not other game like this in the market.  I decide to recreate the cellular stage of it with my own twist.  I felt the increasing competitiveness was a scripted behaviour and it would be much better if it is a spontaneous process, i.e. the increasing competitiveness is a result of natural selection.  I felt it would be too long to generate complex behaviour and traits from natural selection, so I have to limit the possible trait space.  I can parametric the trait and train a reinforce learning agent to adjust those parameter.  I will create a reward function as the amount of food it can obtain.  

setup:

-ocean background

-agent: sensor from 8 direction and movement to 8 direction.
        Behaviour level optimization:
        sensor input -> neural network -> movement output
        
-gene of agent: size(dependent variable), weight(dependent variable),force, energy efficiency, life, damage.

I will start working on this game now (March 17 2018).  Hopefully, first version of it can be finished by May.  I will keep posting progress on this project.  

Thank you for reading!!!

Andy Qiu





---

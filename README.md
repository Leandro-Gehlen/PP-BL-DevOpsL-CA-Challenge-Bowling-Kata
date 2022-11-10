# Bowling Challenge - Personal Project  

### Domain Rules

![image 1 (1)](https://user-images.githubusercontent.com/114420790/201217071-4fac7d68-ed54-4b41-a32e-857052025324.png)
----

## Repo Notation:   

+ **PP** - Personal Project  
  
+ **BL** - Backend Learning  
  
+ **DevOpsL** - DevOps Learning  
  
+ **CA** - Clean Architecture  
----

# Let´s Start!  

## Why CI first?    

What I´m trying to do is to hands-on every thing that I´ve learned so far.
So, **it must be a CI/CD working enviroment.**  

If I just code the app and them put it on this CI/CD pipeline, I´ll not achieve the objective because I´ll not going to keep deploying after the app is ready for deploy.
**So, I´ve decided to build the CI first.**  

## Continuous Integration - CI  

### + At CI I must check the lint and run the unit tests on every commit to dev branch.  

+  For that, I´ll be creating a Github Action that does that.
 + Runs the lint 
 + Runs the tests  
 


## Clean Architecture - Entities  

+ Mach
+ player
+ frames
+ pins  
+ frameScore 
+ PlayersRanking

## Clean Architecture - Use Cases  

+ Player gives his name and start a mach
+ Player can abandon the mach
+ A player can only play one match.
+ A mach has 10 frames
+ A player has two shots on every frame.
+ The result of a frame can be :  
 + Spare: all 10 pins in two tries.
    + Bonus: Number of pins knocked down on the next roll  
 + Strike: all 10 pins in the first try
    + Bonus: Number of pins knocked down on the next two rolls



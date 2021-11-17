# Optimal-flight-with-a-glider
A project where we use dynamic optimization to find a flight path of a glider which maximizes the distance traveled.

## Introduction (from the paper)   

   
Finding the optimal trajectory of a gliding flight with no additional thrust seems like a simple task. However, when trying to model the physical aspects of the flight, using flight mechanics, dynamic optimization and simulation, we can see that it becomes quite a complex system. Fortunately, it is known that the dynamics of rotation are significantly more rapid than those of movement, and therefore we can simplify the aircraft as a point mass and ignore the rotations of the glider. The forces that affect the glider, the dynamics of the glider and the surrounding environment can all be taken into account by starting from the basic free body diagrams of a moving body in the air. By creating the state equations of such a point mass body, we can simulate and more importantly determine the optimal controls in different scenarios. The scenarios that we are going to go over in this project are gliding flight with and without thermal upward air flow.
  
## Authors
  - Johannes Mäkinen [GitHub](https://github.com/johmakinen)
  - Viljami Uusihärkälä [GitHub](https://github.com/uusiharkala)

### Disclaimer

The code used to simulate the project is done in Matlab, but we are not releasing it to the public. This is because the project is a course project which will probably be repeated in the next course offering.

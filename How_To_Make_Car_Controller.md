# How to make Carcontroller
---
### Importing the car model and necessary setup
- First we have to import our car model to the unity project window then.drag it into the scene.
- A car model typically looks like this.
  - it will have a body , that is the actual body of the car 
  - then it will have 4 tires (visual ).
  - some model will have spoilers also.

  #### Steps to properly setup the car
  - first add rigidbody to the carmodel. 
  - then add a collider to the carmodel if it doesnot have
  > [!NOTE]
  > Make sure that it will always be above the wheel otherwise the wheelcollider will collide and cause unexpected outcomes.
  - then create an copy of the wheels and add wheelcolliders for each of the wheels and 

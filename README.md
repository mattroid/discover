## Discover finds paths through your application and records them for regression tests

## Features

  * Don't have to maintain automated UI tests
  * Don't have to fix xpath queries for selenium 
  * Regression tests can be more than what's in a user story
  * Uncover unintended uses of your system
  
## Framework

  * Tensorflow classifiers
  * OpenCV for computer vision 
  * Selenium test runner for automation
  * NeDb for storing data on goal states in the application
  * Akka system for live reinforcement training on the classifiers
  
  
## Getting Started

  * docker-compose up the docker file to get tensorflow and akka framework
  * Need to generate training data. For example we used our existing UI test framework to generate screenshots for every click event our selnium test run and record the xy of the click.
  * Train the button classifier and the cascading classifier for finding "clickable" things. Note: I'll add more information on how to do this when I get further into it. 

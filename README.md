# Rocket Project

This project is based on the Rockect Landing Simulator Project developed by Adrian A. de Freitas and Troy Weingart at the US Air Force Academy in Colorado Springs, CO and shared at SIGCSE 2021.

## Overview
In this project, you will create a rocket landing simulator that allows you to launch a rocket and land it on a moving boat. 

If time permits, you will also develop an artificial intelligence agent that can land the rocket on the boat without user input. You will start by writing a rules-based AI agent, and tune its performance characteristics using a genetic algorithm.

## Steps to take
Complete instructions are in the Canvas module. The project is broken down into sections ("Gate Checks") to manage the complexity.

* Gate Check 1: Setup
  * In this gate check, you will set up the game's starting state. You will randomly generate the rocket and landing boat's starting (x, y) coordinates, and create a random landscape (land & water). You will then implement the basic drawing functions in order to show the game within the graphics window.
  * When you have completed this gate check, you will be able to see the initial game (although it will not be animated).
  
* Gate Check 2: Animation
  * In this gate check, you will animate the game. You will write the code to make the boat move, and animate the rocket during the Boost and Landing phases.
  * When you have completed this gate check, you will see the rocket boost from the launch pad, travel upwards, and begin moving towards the landing boat. Since we have not yet implemented thrusters or player controls, the rocket will end up crashing into the ground or flying of the screen). This is fine! We will tackle this problem in the following gate check.

* Gate Check 3: Player Controls
  * In this gate check, you will implement player controls. Your code will allow the user to move the rocket by pressing the arrow keys. You will also implement a basic heads up display (HUD) in order to track basic performance stats (e.g., fuel consumed, time in flight, etc.). Finally, your code will detect when the rocket 1) hits the ground, 2) goes off the horizontal edges of the screen, or 3) lands on the boat. It will then display a simple "success" or "failure" message before resetting the simulation for the next round.
  * When you have completed this gate check, you should have a fully playable rocket landing simulator.
 
* Gate Check 4: Artificial Intelligence
  * In this gate check, you will develop a (simple) Artificial Intelligence that can land the rocket on the boat without human assistance. Your code will track the rocket's location in relation to the boat, and fire the appropriate thrusters.
  * To receive full credit, you must be able to write a set of rules (i.e., an expert system) that can get the rocket to land on the boat "most of the time." Alternatively, you can write an AI that can "learn" how to land on the rocket by trying different (i.e., random) strategies.







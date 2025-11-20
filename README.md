This is the creature simulation game.

There are 4 creatures sucha as: 
  Base Creature
  SwimmingCreature
  FlyingCreature
  FireCreature

This project models different types of creatures in a simple combat-style simulation.
Each creature has:
  Name
  HP (Health Points)
  Attack Power

And there are 3 special attributes such as:
  Depth, Altitude and Fire Level

Class Structure
Creature
│
├── SwimmingCreature
│     └── depth
│
├── FlyingCreature
│     └── altitude
│
└── FireCreature
      └── fire_level
      
Features
Base Creature
Tracks HP
Performs attacks
Checks if alive
Clean display using __str__

SwimmingCreature
Can dive to increasing depth
Underwater-style attack with modified output

FlyingCreature
Can fly to any altitude
Performs aerial attacks

FireCreature
Stores a fire level
Can emit fire
Has override fire attacks
Custom attack text

Automated Test Suite
When run, the script performs:
Initialization tests
Attack calculations
Overkill (HP cannot go below zero)
Death checks
Inheritance method overrides
Flying & swimming behavior tests

How to run the program?
Type this command in the CMD or the TERMINAL on MAC
            |
            |
            |
            V
python creature_system.py

Tanisorn Pisittanphat 6810545671

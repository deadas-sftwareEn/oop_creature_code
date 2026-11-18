Creature Battle Project (OOP + Git Branching Practice)

This project is designed to help me learn object-oriented programming in Python — especially inheritance — while also practicing key Git concepts like branching, merging, conflict resolution, and version history.

I will begin with a base class (Creature) and create additional subclasses on separate Git branches to simulate a real development workflow.

Learning Objectives

Python / OOP

Understand and implement classes

Use inheritance to extend behaviors

Override and extend methods (e.g., attack())

Practice writing simple test code in main

Git / Version Control

Create and switch branches

Merge branches into main

Resolve merge conflicts

View commit history (git log --graph --all)

Project Structure

oop_creature_code/
│
├── creature_simulation.py  # Base class (Creature) + subclasses (SwimmingCreature, FlyingCreature, FireCreature)
└── README.md               # Project documentation


How to Test and Run

Open your terminal and navigate to the project folder (oop_creature_code/).

Run the Python simulation script:

python creature_simulation.py


Check the console output to verify all test suites pass:

Creature Tests: Basic initialization, attacks, HP boundaries (never dropping below 0), is_alive() status, and defeated creature attack prevention.

SwimmingCreature Tests: Updating depth with dive_to() and underwater attacks.

FlyingCreature Tests: Updating altitude with fly_to() and aerial attacks.

FireCreature Tests: Setting fire_level (0–100) with emit_fire() and dealing bonus fire damage with the overridden attack() method.
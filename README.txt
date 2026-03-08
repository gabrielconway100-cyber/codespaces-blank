Virtual Blob Pet
Interactive Virtual Pet Simulation

This project is an interactive virtual pet game where users care for a customizable blob creature by managing its needs, exploring different environments, and making decisions that affect its well-being.

The goal of the application is to combine game design, user interaction, and adaptive logic into a simple but engaging digital experience.

How the App Works

The player takes care of a virtual blob by managing several key needs:

• Hunger
• Energy
• Cleanliness
• Health
• Mood

These values change over time and influence the blob's behavior and appearance.

If the blob becomes hungry, tired, dirty, or unhealthy, its mood will change and it will react with different animations.

Environments

The application includes multiple interactive rooms. Each room allows the user to perform different actions that affect the pet.

Home
Main hub where the blob lives and the player can monitor its condition.

Restaurant
Allows the user to feed the blob and restore hunger.

Bedroom
Allows the blob to rest and restore energy.

Bathroom
Allows the blob to clean itself and improve cleanliness.

Vet Clinic
Allows the blob to receive medical treatment to restore health.

Shop
Allows the player to purchase items that affect gameplay and track expenses.

Interactive Features

Swipe Navigation
Users can swipe or use arrows to move between environments.

Mini Game
Players can earn money by completing a quick reaction game.

Shop and Inventory
Items can be purchased and stored, influencing stats and gameplay.

Vet Treatments
Different levels of treatment restore health at different costs.

Adaptive Q&A Assistant
A smart helper analyzes the blob's condition and provides advice based on its current needs.

Example:

User: "Why is my blob sad?"
Assistant: "Your blob is hungry. Go to the restaurant to feed it."

Technical Overview

The application was built using:

HTML
JavaScript
Phaser.js game framework

All gameplay logic, UI systems, and scene management are contained within a single HTML file for portability and simplicity.

Assets such as backgrounds, sprites, and icons are stored in the assets folder.

File Structure
virtual-pet-single
│
│ index.html
│ README.txt
│
└── assets
     bg_main.png
     bg_bedroom.png
     bg_restaurant.png
     bg_bathroom.png
     bg_vet.png
     bg_shop.png
     pet_idle.png
     pet_happy.png
     pet_sad.png
     pet_mad.png
     icon_money.png
     icon_food.png
     icon_sleep.png
     icon_clean.png
     ui_play.png
     ui_shop.png
Purpose

This project demonstrates how interactive software can combine logic, user interface design, and adaptive decision systems to create a dynamic user experience.

The goal was to create a virtual pet simulation that is simple to run, visually engaging, and responsive to user actions.

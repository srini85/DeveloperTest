# DeveloperTest

Your task is to implement a car inventory. You have been given the task to lead the development and now is your chance to shine. 

You can use this project to show case as much or as little as you want. This is your place to shine so the more you showcase, the better you will be ranked.

Some of the things we will be looking for in your development

1. Attention to detail
2. Coding Structure
3. Design Patterns
4. SOLID principles
5. Quality and maintainable code
6. Testable code
7. Deployability
8. Documentation

## Task at hand

You are to build a car inventory SaaS solution in C# (.NET 6 or above). The car inventory solution allows users/businesses who manage a fleet of vehicles to be able to securely store and get details about their vehicles. This software is used for many use cases but one common use case is car rental companies which owns numerous cars. They can easily see which cars are available and which ones have been taken out of their garage.

Some of the requirements of this software

1. We need this to be a multitennanted SaaS solution whereby we can have multiple users who manage their own fleet of cars
2. There needs to be a user interface where one can add their car into an inventory (see car specs)
3. User interface should have the ability to update details of a vehicle
4. User interface should have the ability to remove vehicles from the inventory
5. User interface should have the ability to see a listing of vehicles
6. User interface should have the ability to filter the vehicles by status
7. Current Value of the vehicle should depreciate by 5% each year from when it was made. I.e. if it was made in 2022, and the cost was 100,000, in 2023, the current value should be $95,000
8. We should have the ability to log in as different users/businesses on the solution and see their own fleet

Anything not mentioned above, or if you are unsure, you can make assumptions and note them down in the readme.

Things you must provide

1. Your working solution in a github link
2. Readme instructions on how to build and run the code and see it in action
3. If you have deployed it somewhere, details or scripts on how you did the deployment

### car specs

The minimium details you need to store about the car includes
- Model
- Make
- Year
- Registration Number
- Colour
- Current Value
- Status (Available, Unavailable, Stolen, Disposed)
- Notes

There maybe other properties you wish to add which you are more than welcome to if it seems appropriate

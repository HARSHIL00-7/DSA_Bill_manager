# RESTAURANT MANAGEMENT SYSTEM

## _What this does_

This is a program to display the menu for a restaurant based on the quantity of dishes sold in the past week and sort them accordingly using [Merge Sort].

Welcome to my restaurant menu optimizer repository! This project, developed solely by me, utilizes the powerful [Merge Sort](https://www.javatpoint.com/merge-sort) algorithm to generate optimized bills based on past week's dish sales. With a focus on user preferences (Veg/Non-Veg) and budget, this program enhances the dining experience. Feel free to explore the codebase, contribute, and revolutionize the way we optimize menus. Your feedback is highly appreciated!
## _How it does it_

![Employee data](/Restaurant.png "Employee Data title")

The program segregates the menu which was taken into a linked list from a `.csv` file into another list depending upon whether the customer chose vegetarian or non-vegetarian preference.

The optimised bill is generated using the [Knapsack Algorithm](https://www.geeksforgeeks.org/0-1-knapsack-problem-dp-10/)

## _Challenges_

The first challenge we faced was taking the input from an `Excel`(first choice) file into a linked list. As we could not find any external library or discover any clever method to perform this task, we decided to use a `csv` file.

The second challenge was of implementing the Knapsack Algorithm and displaying the optimized bill.

## _Future of this project_
A proper Frontend can be built and using the concepts of this project it can be used by restaurants. 

# Algorithm Name

Bubble Sort 

Reason : The reason why I choose bubble sort is due to it being incredibly simple to understand and conceptualize. It is also a very easy algorithm I find to easily visualize. This algorithm is an algorithm I indeed find enjoyable to implement. When implementing the algorithm in the GUI, I would want each step of the algorithm to be shown clearly. This can be easily done with bubble sort as it makes comparisons and swaps between different adjacent elements. Due to all these reasons and bubble sort being my personal favourite, I do think it is a good choice to use inside of this assignment. And to show how a sorting algorithm works. 

## Demo video/gif/screenshot of test

https://github.com/user-attachments/assets/a56dc5c4-bc0f-4aca-9cc7-bb2c3ba546fa

## Problem Breakdown & Computational Thinking 

Decomposition : 

Starts off with taking the user’s list of numbers 
Comparing each pair of numbers, with its adjacent element 
If the left one is indeed larger, then it swaps them 
It keeps repeating the passes until no more swaps are needed 
As it outputs the sorted list in the end, it also shows every single step 

Pattern recognition ; 

Bubble Sort 
The algorithm (bubble sort) keeps repeating the same action over and over again until the condition is met 
Compares, possibly swaps, and then moves onto the next pair 
The larger value gets pushed to the end every single time when there is a pass 
The unsorted part, becomes smaller and smaller after every swap 

Abstraction : 

Shown to the user : 
After every single swap, the list 
Which of the 2 elements are being compared to each other 
The step number 
Not shown : 
The loop variables 
Internal Counters 
As well as the memory operations 

Algorithm Design : 

Input : Inside of the Gradio textbox, a list of numbers which are separated by commas 
Processing :  Bubble Sort is run, it then records every comparison as well as swap 
Output : Inside of GUI, it shows every step that the algorithm (bubble sort) takes. And in the end it shows the finalized sorted list 
The user in the end can end up choosing if they want to step through it, or see the full run of it

<img width="519" height="1797" alt="image" src="https://github.com/user-attachments/assets/71ccf163-7fe6-4723-beec-f42b802eeb59" />

## Steps to Run

1. Vist the hugging face link, listed under "Hugging Face Link". This is where the application is depolyed
2. Enter the numbers you want to be sorted. These numbers should be seperated by commas. (Example : 1,2,5,-1)
3. Click the "Start" button to begin the sorting.
4. Click next to step through each comparison and swap.
5. Continue pressing stop (repeat step 4) until the list is sorted.
6. Click reset after the list is sorted, if the user wants to input another list. 

## Hugging Face Link

https://huggingface.co/spaces/IkeaHarish/BubbleSort

## Author & Acknowledgment

Karikaran Harish Kandavell 
harish.kandavell@queensu.ca 

AI Level 4 (Claude AI) was used inside of this project 

Python Version: 3.12.11
UI Framework: Gradio

Course information : CISC 121 

#[AI Disclaimer: Used Claude with prompt “Implement the Algorithm Develop a working version of your chosen algorithm in Python. • Comment key steps so the logic is easy to follow. • Ensure the code is readable and correct, not just functional. • The code structure does not have to be OOP • Handle user input and output to the GUI carefully (e.g., incorrect entries). Bubble sort is the algorithm of choice in this case. Decomposition : Starts off with taking the user’s list of numbers Comparing each pair of numbers, with its adjacent element If the left one is indeed larger, then it swaps them It keeps repeating the passes until no more swaps are needed As it outputs the sorted list in the end, it also shows every single step Pattern recognition ; Bubble Sort The algorithm (bubble sort) keeps repeating the same action over and over again until the condition is met Compares, possibly swaps, and then moves onto the next pair The larger value gets pushed to the end every single time when there is a pass The unsorted part, becomes smaller and smaller after every swap Abstraction : Shown to the user : After every single swap, the list Which of the 2 elements are being compared to each other The step number Not shown : The loop variables Internal Counters As well as the memory operations Algorithm Design : Input : Inside of the Gradio textbox, a list of numbers which are separated by commas Processing :  Bubble Sort is run, it then records every comparison as well as swap Output : Inside of GUI, it shows every step that the algorithm (bubble sort) takes. And in the end it shows the finalized sorted list The user in the end can end up choosing if they want to step through it, or see the full run of it. These are the steps needed, please implement the steps. This again is done through Python. Step 4 — Add Interactivity with a Python UI Library, Use a beginner friendly UI library such as Gradio. Another option is Tkinter, but that is for desktop Python apps only and cannot be deployed on Hugging Face. So, please use Gradio. • Create input boxes, e.g., for target value/s and search array, and result displays. • Show each step or the final result clearly. • Keep the interface simple enough that anyone can understand it. Ensure that it is truly interactiv, there are boxes that can be moved around to truly show the full implementation of the bubble sorting algorithm. The version of Python I am using is 3.12.11. Please use all the correct syntax and gradio implementation. There should not be any errors. Ensure that it doesn't just get stuck at one step, that it is able to visually go through every single one of the necessary steps. It is also actually show the swapping, not just be stuck. Ensure that all the buttons work. Especailly the next button. Ensure that the next button actually does it's job. And ensure that the sorting and swapping is actually shown. Not just the first step, but every step must be shown. It is still stuck, as the next button isn't working after the first step”]


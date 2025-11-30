# CISC121-final-project
#Algorithm name: Bubble Sort 

#Screenshot of test 
<img width="1463" height="761" alt="Screenshot 2025-11-30 at 9 50 57 AM" src="https://github.com/user-attachments/assets/09d6b9f6-f9f0-4c83-ba4f-41d2a973fabe" />

#Problem breakdown and computational thinking 
1. Decomposition
   - Input: list of numbers
   - Output:
     - Visual step-by-step animation of Bubble Sort
     - Slider to adjust the length of array; button to start; button to generate array
     - Highlighted comparisons of the swaps
     - Display of the different sorting steps

Development process:
- Create code for bubble sort logic
- Record the array at each step of the sorting process
  - Save the current array
  - Mark the two positions being compared
  - Keep track of comparisons and swaps (displayed for visualization)
- Create visuals (bar chart, buttons, slider)
- Review Draft Code
- Put code on Hugging Face to generate app

3. Pattern Recognition
- The algorithm always compares pairs of adjacent elements in the loop

5. Abstraction
- Visualization removes numeric values and presents them as bar graphs
  
7. Algorithms
- Bubble sort:
  - Loop through the list multiple times
  - Compare adjacent elements
  - Swap if the left element is greater than the right
  - Repeat until no more swaps required 

#Steps to run
1. Use the Array size slider to change the default array size of 5 (optional step)
2. Click the Generate Random Array Button
3. Click the Run Button (found at the bottom)
4. The visualization will display on the screen 

#Draft Code
Colab link: https://colab.research.google.com/drive/1W_gU5tDFHsHNfqgYE2ql39LPaLCvnjTN?usp=sharing 

#Hugging Face App Link 
https://huggingface.co/spaces/trishaanoop/CISC121-project

#Author and Acknowledegement 
Author: Trisha Anoop
Sources used:
- Creating graphs for visualization:
  - https://matplotlib.org/stable/tutorials/pyplot.html
  - https://www.dataquest.io/blog/how-to-plot-a-bar-graph-matplotlib/
  - https://www.gradio.app/docs/gradio/barplot (used to learn functions)
- Yield function in Python https://stackoverflow.com/questions/231767/what-does-the-yield-keyword-do-in-python
AI disclaimer: ChatGPT was used during the debugging process by prompting, "What is causing an error in the function get_steps?" When running the code through the Hugging Face Aoo tab, the first arror message pointed to this function, so ChatGPT was used to identify the issue and guide the fixes. For this prompt, the AI tool also identified other errors, including variable-name spelling mistakes, missing final lines (such as the one that makes the Gradio app run only when the file is executed directly), missing import statements for required libraries (Gradio, Matplotlib (creating charts), NumPy (handling data and timing), PIL (working with images)), and other lines that needed to be added for the program to run properly. Overall, I found AI extemely helpful in the debugging process, as it explained each error clearly and in simple terms, which made it much easier for me to understand the issues and learn from there. 

# Pre-trained-Image-Classifier-to-Identify-Dog-BreedAIPND
 Mini Project from Udacity's AI Programming with Python Nano Degree
 
 To execute the project, run ``` sh run_models_batch.sh``` in terminal, on all three given architectures and compare the performance for **best** model with respect to the project goals.
 
```#TODO: 0```: Timing Code - Implement the start_time to measure total program runtime. Coding within the ```check_images.py```
```#TODO: 1```: Command Line Arguments - Code for ```def get_input_args():``` to create & retrieve the command line arguments with in ***get_input_args.py***</br>
```#TODO: 2```: Creating Pet Image Labels - Code for ```def get_pet_labels():``` to create pet image labels by creating a dictionary with key=filename and value=file label within ***get_pet_labels.py*** and code within the ```main()``` function, ***check_images.py***. Specify the appropriate directory within the function call with *in_arg.dir*</br>
```#TODO: 3```: Classifying Images - In ***classify_images.py***, implement ```def classify_images()``` to create the classifier labels with the classifier function using in_arg.arch. Compare the labels, and create a dictionary of results. Change corresponding ***check_images.py*** code. </br>
```#TODO: 4```: **Classifying Labels as Dogs** - Implement the ```def adjust_results4_isadog():``` function to adjust the results of dictionary to determine if the classifier correctly classified images as 'a dog' or 'not a dog'.Change corresponding ***check_images.py*** code. </br>
```#TODO: 5```: **Calculating Results** - Implement the ```def calculates_results_stats():``` function to calculate the results of run and put statistics in a results statistics dictionary (results_stats_dic). Change corresponding ***check_images.py*** code. </br>
```#TODO: 6```: **Printing The Results** Implement the ```def print_results():``` function to print a summary of the results (as well as incorrect classifications of dogs and breeds if requested). Change corresponding ***check_images.py*** code. </br>

# Image Classification for a City Dog Show
## Description:</br>
Your city is hosting a citywide dog show and you have volunteered to help the organizing committee with contestant registration. Every participant that registers must submit an image of their dog along with biographical information about their dog. The registration system tags the images based upon the biographical information.</br>
Some people are planning on registering pets that **aren’t actual dogs**.</br>
You need to use an already developed ```Python``` *classifier* to make sure the participants are dogs.<br>

## Principal Objectives:
1. Correctly identify which pet images are of dogs (even if breed is misclassified) and which pet images aren't of dogs.</br>
2. Correctly classify the breed of dog, for the images that are of dogs.</br>
3. Determine which CNN model architecture (ResNet, AlexNet, or VGG), "best" achieve the objectives 1 and 2.</br>
4. Consider the time resources required to best achieve objectives 1 and 2, and determine if an alternative solution would have given a "good enough" result, given the amount of time each of the algorithms take to run.</br>

## Program Outline
- Time your program
  - Use Time Module to compute program runtime
- Get program Inputs from the user
  - Use command line arguments to get user inputs
- Create Pet Images Labels
  - Use the pet images filenames to create labels
  - Store the pet image labels in a data structure (e.g. dictionary)
- Create Classifier Labels and Compare Labels
  - Use the *Classifier* function to classify the images and create the classifier labels
  - Compare Classifier Labels to Pet Image Labels
  - Store Pet Labels, Classifier Labels, and their comparison in a complex data structure (e.g. dictionary of lists)
- Classifying Labels as "Dogs" or "Not Dogs"
  - Classify all Labels as "Dogs" or "Not Dogs" using dognames.txt file
  - Store new classifications in the complex data structure (e.g. dictionary of lists)
- Calculate the Results
  - Use Labels and their classifications to determine how well the algorithm worked on classifying images
- Print the Results


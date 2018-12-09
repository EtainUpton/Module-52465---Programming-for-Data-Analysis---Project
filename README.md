# Module-52465---Programming-for-Data-Analysis---Project
10 Credit Module Project 2018 – 50% of overall mark for this module 

Deadline: December 14th (Friday)

## To do:	
- 12.11.2018 – 18.11.2018: Review project video and instructions. Create repository and submit link. COMPLETED.

- 19.11.2018 – 25.11.2018: Finish reviewing all videos. Review and adhere to marking scheme.

- 26.11.2018 – 02.12.2018: Commence project. Pick a phenomenon and research it. Create the dataset.

- 03.12.2018 – 09.12.2018: Complete project

- 10.12.2018 – 13.12.2018: Submit project

## References
-	https://www.aspca.org

-	MADRA Website - http://www.madra.ie/

-	ISPCA Website - https://www.ispca.ie

-	Department of Environment, Community and Local Government Website – 

-	https://www.thejournal.ie

-	https://www.irishtimes.com

-	Dog control report 2017

-	https://drcd.gov.ie

## Brainstorming 27/11/2018:

-	Performance of students studying a 10 credit module = successfully rehomed dogs in a shelter

-	Variables;

  - Grade = Successful rehoming/ non-successful rehoming
  
	    - Hours = Breed of dog/puppy

	    - Logins = amount of previous owners the dog has had / age of the dog/puppy

	    - Qualifications = how well trained the dog is

The 3 above variables should be closely related to the successful/non-successful rehoming of the dog. 

After brainstorming the variables I realised some of the ideas I had come up with were not numbers (e.g. breed of dog/puppy). I decided to try allocating a figure to approximately 5 breeds, something like;

1 – German Shepherd

2 – Labrador 

3 – Collie

4 – Greyhound

5 – Mixed breed

I will try this approach and see if it works.

The same scenario occurs for another variable I had chosen – how well trained the dog is. I decided to allocate levels of training from 1 to 3;

1 – Well trained

2 – Somewhat trained

3 – Not trained at all

These are all non-negative real numbers.

I fabricated the below;

o	Breed of dog/puppy

o	Amount of previous owners the dog has had / age of the dog/puppy

o	The dog’s level of training

German Shepherds out of 20;

-	Breed of dog/puppy - German Shepherds

-	Age of the dog/puppy – 

    5 below 6 months
    
    10 below 5 years
    
    5 over 5 years old
    
-	The dog’s level of training – 

    1 – Not trained (3)
    
    17 – Somewhat trained (2)
    
    2 – Well trained (1)
    
I will try to complete the same type of fabrication for each of the 5 breeds of dog I have chosen, and work from there. 

#### To do tomorrow 28/11/2018: 
Now that I have a fair idea what real-world phenomenon I would like to simulate data for, I need to become more familiar with the numpy.random package which I will use to model and synthesise the data using Python.


![Screenshot](Tyson.jpg)

02/12/2018

At this point I have decided what I would like my data set to represent.

To do: Model & synthesise the data using Python – numpy.random package.

There should be at least one-hundred data points across four different variables.

Create a synthesised data set.

Devise an algorithm (or method) to generate my data set. 

Detail this work in my notebook.

Add some code to generate a data set with those properties.

Review the numpy.random package videos on Moodle.

The the numpy.random package is used for generating random data in Python, which is exactly what I want to do.

I reviewed the following videos;
1.	Introduction to numpy.random
2.	Introduction to numpy. I also checked out http://www.numpy.org/.
3.	Setting up the numpy.random repo
4.	

Reference;
http://www.numpy.org/
https://jupyter.readthedocs.io/en/latest/running.html#running


I initially thought realised that I would need to compile my synthesised data somewhere. I then realised that numpy.random will do this for me – it will generate arrays of numbers for me, so I don’t need to compose them myself.

To launch jupyter notebook; CMD > Anaconda Prompt > jupyter notebook

03.12.2018
I reviewed the following videos;
4.	Setting up the numpy.random repo
5.	Numpy.random docs
6.	Rand function video
7.	Distributions video
8.	

Reference:
Docs.scipy.org/doc/numpy

np.random.rand(3,2) 

To generate the random numbers for my dataset;

![Screenshot](ToGenerateRandomNumbersInJupyterNotebook.JPG)

I received the results of my assignment which I had completed for this module in November by email from Dr Ian McLoughlin on 04th December. I reviewed the constructive feedback carefully and will try to apply it to this project.

### Ian’s feedback;

#### -	Research:

Your submission was of a reasonable standard in this category.

You might consider further developing the following in future submissions:

- Make sure to inform yourself of other people's approaches to problems like the one set out in the assignment brief. In your submission, you might summarise your findings and then make an informed decision as to your approach to the problem. You can provide evidence that you carried out this research by documenting it within your submission.

- Try to break the overall assignment into smaller components. Research each of these components, and then consider how they might fit together to provide an overall solution.

#### -	Development

Your submission was of a reasonable standard in this category.

You might consider further developing the following in future submissions:

- Make sure you demonstrate your competence in programming, including an ability to search, read and understand documentation.

- You code must work and files should be named appropriately with correct filename extensions.

#### -	Consistency

Your submission was of a reasonable standard in this category.

You might consider further developing the following in future submissions:

- Make sure you manage your own learning and development, including time management and organisational skills, and make this evident in your submissions.

- You should reflect on previous projects you have completed and have the foresight to see common potential issues coming down the tracks during your project.

#### -	Documentation

Your submission was of a reasonable standard in this category.

You might consider further developing the following in future submissions:

- Your documentation should provide descriptions and instructions for understanding your submission.

- All code should be commented. Usually each statement requires a comment and a preamble is required at the beginning of every file.


I was unsure which simple random data code to use for this purpose, so I researched some different options from https://docs.scipy.org/doc/numpy-1.15.1/reference/routines.random.html and decided that for my purposes and the dataset I wish to create, the following would be the most suitable; numpy.random.shuffle

numpy.random.shuffle can be used to modify a sequence in-place by shuffling its contents.

This function only shuffles the array along the first axis of a multi-dimensional array. The order of sub-arrays is changed but their contents remains the same (Reference: https://docs.scipy.org/doc/numpy-1.15.1/reference/generated/numpy.random.shuffle.html#numpy.random.shuffle)

I tested this in my Jupyter notebook;

![Screenshot](ToGenerateRandomNumbersInJupyterNotebook.JPG)
 
I wondered – does this actually generate random numbers, or does it just shuffle numbers between 1 and 10 and display them in random order?

Perhaps I need to explore further.

I tried to use the same code but replaced the figure 10 with 100;

![Screenshot](JupyterNotebookErrorMessage.JPG)
 
The above error was displayed.

Now that I have decided to use 

To do: Work out what types of figures I need in terms of the subject I have closen and the variables.

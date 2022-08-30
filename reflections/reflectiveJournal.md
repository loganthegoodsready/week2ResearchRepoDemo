# Reflective Journal

## Week 1:

### What is Scratch?
It is a fun visual programming language that is used to create interactive games and stories. The concept of stacking blocks makes it intuitive and helps the user understanding progamming principles.

### What is visual programming?
A visual programming language is any programming language that lets users create programs by manipulating program elements graphically rather than by specifying them textually.

### What are some programming principles that you have discovered?
"Programming is simply a set of instructions to tell a computer how to perform a particular task". Programming languges are used as the "set of instructions", and there are many languages that have their own "syntax", but they all share the same purpose. There are 'low level' and 'high level' languages, the former being closer "machine code"  which the computer for can process directly (Computers understand 0's and 1's - binary - exclusively), and the latter being closer to noraml "human" language. Programming languages are 'compiled' and/or 'interpreted' in order to be translated into machine code.
Programming conventions - common rules, guidelines and approaches for programming languages - are the begining of the "programming principles" I'm becoming familiar with. 'Standard libraries' which defines the built-in functions and modules for a particular language are an important aspect of high level languages. "Style guides", seem to be synonymous with "syntax" so I may need to follow up on that if it's important. Variables are place holders for information, and each varibale stores just one piece of information. They store data types which can be numeric, text (strings) or booleans (True or False values). 
 "A flowchart is a simple diagram that illustrates the stages or steps the computer must complete to solve the problem". These visual representations of code are easier to grasp than normal written code. Scratch is similar to a flow chart in many ways. seeing the visual elements of flow charts such as sequence, condition and itteration, make 'control flow' concepts like "while loops" in 'Python'(or any other language) easier to understand. 
 K.I.S.S - Short, concise and coherent code is optimal as it's quicker to write and read. "code is read more than it's written"- Said many people.


### Can you share your favourite Scratch project that you have made or remixed?
Yes i can.
### Click [Here](https://scratch.mit.edu/projects/718450845) to a play a game about a crab on drugs.

## Week 2:

### What is git?
A dictionary defines a 'git' as "an unpleasant or contemptible person".
or "Git is software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development."

### What is GitHub?
GitHub is a website and cloud-based service that helps developers store and manage their code, as well as track and control changes to their code. A developer can duplicate part of the source code (called the repository). The developer can then safely make changes to that part of the code without affecting the rest of the project.

# Hello, Markdown
**this should be in bold**, _and this should be in italics?._ **_And this in bold italics_** ~~Cross this out~~
* Unordered sublist
+ Using any symbol 
- then press enter to continue another. 
- like this

1. But how do you get a middle dot???

## Week 3:

# Lab task 1:
age = float(input("How old is your dog in human years? "))
if age == 2:
    print("Your dog is", 10.5, "years old")
elif age > 2:
    print("Your dog is", (age-2)*4 + 21, "years old")
elif age <= 1:
    print("your dog is a puppy")
elif age >1 and age <2:
    print("your dog is an adolescent")

### else statement N/A
~~I'd like to figure out a differnt way to write this code if possible~~

**_This seems like the best way to write this code_**

# Lab task 2:
month_31 =['January','March', 'May', 'July', 'August', 'October', 'December']
month_30 =['April', 'June', 'September', 'November']
month_28_29 =['February']
birth_month= input("What is your birth month? ")
if birth_month in month_31:
    print("There are 31 days in",birth_month)
elif birth_month in month_30:
    print("There are 30 days in",birth_month)
elif birth_month in month_28_29:
    print("There are 28 days in",birth_month+", or 29 days on leap year")

### originally I wrote this code using the 'or' operater but it looked far too long and messy. After some research I discovered i could use a 'list' function and the 'in' operator to make it shorter and more comprehensive. 

# Lab task 3:
cat = input("What is your name \n")
print("your name is a", type(cat))

### I'm not entirely sure how to do this one, but outputting the class type of the input seemed to be the closest option I could think of. 

# Lab task 4:
num_1= int(input("Enter first number: "))
num_2= int(input("Enter second number "))
if num_1 % 2 ==0 or num_1 % 3 == 0 and num_2 % 2 == 0 or num_2 % 3 ==0:
    print(num_1 * num_2 )

### Nice and easy :)

# Lab task 5:
temp = input("Enter '1' to convert celsius to fahrenheit\nEnter '2' to convert fahrenheit to celsius ")
if "1" in temp:
    celsius = float(input("Enter temp in celsius: "))
    fahrenheit = celsius*1.8+32
    print(celsius, "celsius is equivalent to", fahrenheit, "fahrenheit")
elif "2" in temp:
    fahrenheit = float(input("Enter temp in fahrenheit: "))
    celsius = ((fahrenheit - 32) *5 / 9)
    print(fahrenheit, "fahrenheit is equivalent to", celsius, "celsius")

### This one im stuck on. "enter 1 for, enter 2 for, and enter 3 for" HOW? 

# Lab task 6:
### I'll get back to this one. too many convervsions. maybe there's a built in module to do it.

# Lab task 7:
x = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
print(sum(x))
print(sum(x) / 10)

### seems easy enough, although i will forget it if I don't practice.

# Lab task 8:
num = 1
for y in range(1,13):
    print(num,"x", y, "=", num*y)

### How to print them in a grid like:

1 x tables   2 x tables   3 x tables   4 x tables

5 x tables   6 x tables   7 x tables   8 x tables

9 x tables   10 x tables   11 x tables   12 x tables

### ??? Need to find out how to do this. Hopefully the answer will come apparent to me as I learn more python. 

## Week 4

** What is a graph?
Nodes with lines connecting them...

Reflective questions: How did you feel as a subject of a video? Did you notice your ego? How are we evolving with this device? How could we draw this activity? Did you feel more attachment to the phone than to your image?
** 

## week 5
Agile. We aregoing to experience it in order to learn what it is.


Reflective Questions: What is an MVP? 
MVP stands for minimum viable product. It's an approach for testing and getting feedback on your product and its features. It doesn't have to be the product itself, it could even be a crowd funding campaign to showcase your product to gain maximum feedback with minimal time and expenses.  
Reflect on the exercise of building he tower and how it relates to Agile.



#### Promptsto use...

### Did you remember to take regular breaks away from your screen during this week? How often? Did you stretch your body?
I've been try to maake sure I take a break atleast every hour, even if im confused about something and I know i'll likely spend my break time ruminating about my confusion. I have to make sure I take breaks so my mind stays clear and my body doesn't turn to stone. 

### What is Timeboxing? Have you heard of it before? Will you use it?

### On a a 0-5 scale, how confident are you with each of the assignments?

### What are of you proud of up to this point in the course?

### Do you have a personal learning strategy? If so, what parts of your learning strategy worked? What problems did you face? If you don't have a personal strategy yet, what do you think might work? Invent a describe a strategy for yourself. 


### If you could send a time traveling text message back to yourself at the start of this course, what would it say?

### What is Python?

### Have you developed a habit of exploring?

### Have you meditated before?

### Is there something over which you have gained a degree of mastery before in your life? Gymnastics, Rubik's Cubes, A Video Game? What did it take?

### Do you consider yourself a developer yet?

### Do you value creativity? As a value itself? What about as a tool for learning to think logically?

### How many tabs do you have open in your web browser right now? What is the ratio of study related tabs to distraction related tabs?

### Have you had a fight response to technology? What does it feel like? How did you overcome this?

### What is an IDE?

### What did you learn out of the Marshmallow Challenge?

### Did you have any blocks during this challenge? How did you overcome them?

### So far, what was the hardest moment of this course for you?

### What is OOP?

### Are you using the canvas content? Do you find it helpful or tedious?

### Which parts of the work did you find tedious?

### What is polymorphism?

### Did you hear a self critical voice in your head throughout the process of learning during this last few weeks? What did it say to you? Do you believe what it said?

### What is an MVP? How would you describe it to a group of 6 year olds?

### What is the hardest problem you have solved so far?

### What is pair programming?

### What are you looking forward to learning about programming?

### What is conscious listening?


### What programming languages are you interested in learning? Why?

### What is something kind that someone has done for you?

### If you were describing programming to someone who knows nothing about it, what would you say?

### Which parts of this course made you feel doubtful of your own innate ability?

### What is a fixed mindset?

### What is something kind you have done for someone else?

### Have you done mindfulness or attention training before?

### Have you developed a habit of persevering?


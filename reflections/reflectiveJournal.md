# Reflective Journal

## Week 1:

### What is Scratch?
It is a fun visual programming language that is used to create interactive games and stories. The concept of stacking blocks makes it intuitive and helps the user understanding progamming principles.

### What is visual programming?
A visual programming language is any programming language that lets users create programs by manipulating program elements graphically rather than by specifying them textually.

### What are some programming principles that you have discovered?
"Programming is simply a set of instructions to tell a computer how to perform a particular task". Programming languges are used as the "set of instructions", and there are many languages that have their own "syntax", but they all share the same purpose. There are 'low level' and 'high level' languages, the former being closer "machine code"  which the computer for can process directly (Computers understand 0's and 1's - binary - exclusively), and the latter being closer to noraml "human" language. Programming languages are 'compiled' and/or 'interpreted' in order to be translated into machine code.
Programming conventions - common rules, guidelines and approaches for programming languages - are the begining of the "programming principles" I'm becoming familiar with. 'Standard libraries' which defines the built-in functions and modules for a particular language are an important aspect of high level languages. "Style guides", seem to be synonymous with "syntax" so I may need to follow up on that if it's important. Variables are place holders for information, and each varibale stores just one piece of information. They store data types which can be numeric, text (strings) or booleans (True or False values). 
 "A flowchart is a simple diagram that illustrates the stages or steps the computer must complete to solve the problem". These visual representations of code are easier to grasp than normal written code (pseudo code). Scratch is similar to a flow chart in many ways. seeing the visual elements of flow charts such as sequence, condition and itteration, make 'control flow' concepts like "while loops" in 'Python'(or any other language) easier to understand. 


### Can you share your favourite Scratch project that you have made or remixed?
Yes i can.

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

1. But how do you get a middle dot????

## Week 3:

#Lab task 1:
age = float(input("How old is your dog in human years? "))
if age == 2:
    print("Your dog is", 10.5, "years old")
elif age > 2:
    print("Your dog is", (age-2)*4 + 21, "years old")
elif age <= 1:
    print("your dog is a puppy")
elif age >1 and age <2:
    print("your dog is an adolescent")
**#else statement N/A**
**I'd like to figure out a differnt way to write this code if possible**

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
**#originally I wrote this code using the 'or' operater but it looked far too long and messy. After some research I discovered i could use a 'list' function and the 'in' operator to make it shorter and more comprehensive. 

# Lab task 3:
cat = input("What is your name \n")
print("your name is a", type(cat))
**# I'm not entirely sure how to do this one. 

# Lab task 4:
num_1= int(input("Enter first number: "))
num_2= int(input("Enter second number "))
if num_1 % 2 ==0 or num_1 % 3 == 0 and num_2 % 2 == 0 or num_2 % 3 ==0:
    print(num_1 * num_2 )
**# writes thoughts here.

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
**# This one im stuck on. "enter 1 for, enter 2 for, and enter 3 for" HOW? 

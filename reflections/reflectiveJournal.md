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

Nodes with lines connecting them. Nodes contain the data and the lines are what connects that data. Graphs can be directed (one way connection) or undirected (two way connection) or both. The simplest example I have found of an undirected grapgh in a real world scenario is the Faceebook (social graph) "friend" system. Users with all their information attached represent the nodes, and if two people are friends on facebook that will mean there is a two way connection between them (undirected). Additionally, Facebook can use this grapgh to implement features such as the 'friend request system'. It's a simple system that suggests to you mutual frinds of your current friends. An example of a directed grapgh is the world wide web (which can also be undirected). A webisite may have a link on their site to another website, but if that website doesn't have a link back to them, it's just a one way connection. 

In class today we made a video graph. There was a lack of cooperation from the class but I did get the jist of the exercise. Each person represented a node and the video feed of another person reresented the edge.  It was mostly a directed graph because the person you were filming would not also film you. Normally I dont like having the spotlight on me so being filmed makes me anxious, but because everyone else was also being filmed it lessened that anxiety a lot and I joined the hive mind of the group. People - especially gen z and millienials - have become very attached to their phones and it has become an extention of themselves. This became very noticiable for myself and probably many others in the class when we had to put our phones on the ground to be filmed. Photo galleries contain the most private parts of our lives, and that's exactly where my video was playing from. 

Reflective questions: How did you feel as a subject of a video? Did you notice your ego? How are we evolving with this device? How could we draw this activity? Did you feel more attachment to the phone than to your image?
** 

# week 5
Agile. We are going to experience it in order to learn what it is.
The Agile model is the most widely used devopment methodology in the tech space. It's a set of principles and guidlines used to execute a project.

Them main for values of Agile are:
- Individuals and interactions over processes and tools
- Working software over comprehensive documentation
- Customer collaboration over contract negotiation
- Responding to change above following a plan

These four principles are pretty cool imo. I like how focused it is on people and the product itself. The entire process is so dynamic that it forses the developers to let go of their egos and be more open minded. 

### Click [here](https://i0.wp.com/availagility.co.uk/wp-content/uploads/2015/12/Screen-Shot-2015-12-16-at-10.43.01.png) to see the Agile Manifesto. 


Reflective Questions: What is an MVP? 
MVP stands for minimum viable product. It's an approach for testing and getting feedback on your product and its features. It doesn't have to be the product itself, it could be a wesite, an app, a video, or even be a crowd funding campaign to showcase your product to gain quality feedback with minimal time and expenses.  

Our task of creating teams and trying to build the tallest tower over three iterations, using raw spaghetti, tape, string and a marshmellow, was a good exercise to demonstrate why the agile model works well. Our first attemt failed, our second attempt also failed, and our third attempt was successful. During our first attempt, we made a plan together and allocated tasks, but we spent too much time on small details and were unable to make a finished tower. On our second attempt we didnt fuss over the small details and we made a finished tower but it didnt stand on its own. We found a bug at the end our second attempt that was making the taower topple over, and we were able to fix that bug and make the only free standing tower. Although we won and we had good teamwork, we still somewhat followed a more traditional approch to building the tower. A key element we were missing was an MVP. We were so focused on making the tallest people tower that we could and that which almost led to there being no tower at all. Our MVP would have been to make a free standing tower as fast as possible with minimal planning and time wasted, and from there we could have continued to make it taller with each itteration. 

### Reflection on the last five weeks

During week four and five I started to feel quite lost and confused abouth the direction of the course. Infact, I was so lost that stopped doing any study at all. I was trying to collect my thoughts in that time instead. My confusion was due to a misunderstanding about the course material and also the unorthodox teaching style that I wasn't used to. My expectation was that the class would be learning Python progressively each week during lectures, along with other things ofcourse, and that would ultimately lead to making projects with python. This confusion was due to the the older course outline I was given when I signed up for the course. After reaching out to you (Roman) regarding my concerns, The final thing you said to me was "trust the process". I've been doing so since that interaction and I've felt my confident with the direction of the course. I'm a bit behind schedule due to my 2 week break from study, but I have a rough idea of my plans. During that interaction you also sent me a link to a video about developing a growth mindset by Carol Dweck. That video made me better understand your teaching style and the course structure. You're trying to encourage a growth mindset with this course, and help students break free from the fixed mindset they might have. By choosing our own projects we are faced with challenge of aiming for a high goal, and you're encouraging us to explore that route and to not be afraid failure, and learn from it instead. I hope that if I do fail this assignment, I'm given the grade "Not yet".


#### Promptsto use...

### Did you remember to take regular breaks away from your screen during this week? How often? Did you stretch your body?
I've been trying to make sure I take a break atleast every hour, even if Im confused about something and I know I'll likely spend my break time ruminating about my confusion. I have to make sure I take breaks so my mind stays clear and my body doesn't turn to stone. 

### What is Timeboxing? Have you heard of it before? Will you use it?

"In Agile principles, timeboxing allocates a fixed and maximum unit of time to an activity, called a timebox, within which planned activity takes place. It is used by Agile principles-based project management approaches and for personal time management."

Up until googling "time boxing" right now, I had not heard of it. I do tend to ponder on unimportant matters so this would be a good tool to use in my own own life to help prioritise tasks. I dont work well under pressure generally, so introducing timeboxing should be good preparation for real world work environments. 

### On a a 0-5 scale, how confident are you with each of the assignments?

A 3/5

Software development is a bit overwhelming but I know once I'm more familiar with the process of making a project I'll feel more confident.

### What are of you proud of up to this point in the course?

Starting this course is the thing I'm most proud of so far. My last formal educational experience was in 2014 at university and that didn't pan out as I'd hoped, so signing up to this course was scary. 

### Do you have a personal learning strategy? If so, what parts of your learning strategy worked? What problems did you face? If you don't have a personal strategy yet, what do you think might work? Invent a describe a strategy for yourself. 

Learning for me is similar to reading a book. I need to be by myself in a quiet place with no distractions. My biggest hinderance is procrastination. I'll generally delay doing something if I find it boring or if I'm confused which makes beginning the task daunting. One strategy I've used in the past which has worked, is to set very small easily attainable goals. In this instance, the goal would be to 'study every day for 15 minutes'. Small goals like this work because it's not overwhelming. 15 minutes might not sound like much but that's not the part that matters, what matters is that once you've reached the 15 min mark, you've achieved the goal and you feel a little bit accomplished and proud of yourself. This creates a positive association with the activity which is easier for building a lasting habit. Even though the goal is only 15 minutes of study, you'll find that you'll usually study for a lot longer because it's only the 'starting' that's the hard part. Setting the goal to do it every day is another good hack because if you miss a day then you have the oppertunity to study again the next day and you're less likely to make excuses to 'start fresh the following week' for example. 

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


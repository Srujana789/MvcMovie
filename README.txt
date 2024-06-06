2024-05-09 
Sai Naga Srujana Vanarasi
1324
Web app created w/ Visual Studio2022 .Net 7
No auth,...
SSL cert SH-1
0305
Tested and modified the app..
All good

Let's start on part2, add a controller

tested 2 different controller methods
url : /HelloWorld/welcome/
webpage loaded successfully

2024-05-16

Part3 1420

created a new folder in views
name:helloworld
add item razor view empty and open the index html file
all good, I tried commenting few lines of code and then uncommented them and tested the webpage
0300
its successfully running
urls tested:
https://localhost:7119/
https://localhost:7119/helloworld
https://localhost:7119/helloworld/welcome
https://localhost:7119/helloworld/haveaniceday

2024-05-23

Part 3 1350
welcome.cshtml created

Part 3 tested with URL

https://localhost:7119/helloWorld/welcome?name=Srujana&numtimes=5
result successful

Part 4 1412

Adding a model
movie.cs is modified

scaffold item was disabled and I could identify that the process is running and so I couldnt add the scaffolding
Application stopped and added the scaffold item
added details like model class dbcontext class

see the moviescontroller.cs created
data/mvcmoviecontext.cs is the database class

1504

Initial Migration

commands run in PMC
added migration and the database is updated

completed successfully

Test the app

test successful

examine the generated database class and registration
created files
Data/MvcMovieContext.cs
dependency injection-program.cs
appsettings.json-- 2 lines of code is added after scaffolding

examine initial create class file

initial create file created with timestamp 
20240530161712_InitialCreate

part 5 1605
opened the DB by SQL server object explorer

examined the dbo.movie
designer and view data options
Completed sucessfully

2024-05-30
part 6 1405
controller methods
Release Date should be displayed with a space in between.
result success
tested the url  https://localhost:7058/Movies

part 7 1443

having difficulty in adding the filter to genre :(
I was able to troubleshoot the issue
index in moviecontroller is modified and it worked :)
tested url https://localhost:7058/Movies?MovieGenre=Action&SearchString=

part 8 1518

Build started at 3:20 PM...
========== Build: 0 succeeded, 0 failed, 1 up-to-date, 0 skipped ==========
========== Build completed at 3:20 PM and took 00.151 seconds ==========

tried adding the rating field
added it to the index, seed data and controller codes
updated the database with the rating field, without updating it the page doesnt show up the result

rating field is displayed but not getting to edit it :(

1921

I got itttttttt :)
added rating field to create,edit files and moviescontroller code as well..it worked
Rating field is now editable

part 9 1922

validation rules for movie model
validation in UI for all the possibilities for data types configured
test successful


2024-06-06 1415

part 10 1420

examined movie controller, program.cs files


1430

Created Github account 
cloned it 
pushed project MvcMovie to github
Made my github repository private to public
checked with my peer to access my github link..its working





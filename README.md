# Nikol
Draw figures with your favourite singer or actor!
Now available: 
* Igor Nikolaev
* Nicolas Cage

# Installation

Just upload this project on any hosting or server. It does not need any additional setups. 

# How to add a new person?

It is easy! Create a few photos of the new person in png format.

Call them like this: 1.png, 2png, 3.png, etc.

There is an array on the 9th line in index.html, called "people". Just add a new object to that array,

with the following format:

{

 folder: "%SOME FOLDER NAME%",

 name: "%PERSON's FULL NAME%",

 photos_num: %NUMBER OF PHOTOS%

}

Where:

%SOME FOLDER NAME% - the folder, in which images of the new person are located

%PERSON's FULL NAME% - full name of the new person. (Nicolas Cage, ex)

%NUMBER OF PHOTOS% - the number of photos of the person


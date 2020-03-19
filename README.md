GenerationSTEM Website
Created by: Stephanie Carpintero-Flores
Part of a senior project at CAL POLY SLO
March 13,2020

# generationSTEM.github.io
A website to digitize the content of the education program called GenerationSTEM. For easier access to teachers and students. The program GenerationSTEM's goal is to help underrepresented and more diverse communities to have equal opportunity to STEM education. This website it meant to display the current teaching program (the handbook) on the web. It's meant for future purpose of when teachers would like to run the program on their own, they will have this website to reference the content. The website offers material and resources to the students and teachers. Such as pdf forms to print and animations for the students. The animations were built of Unity and used WebGL to include it into the web.

The code come from an online template that was transformed to have a design created on Figma. The website design process can be read in the file called: Website Implementation Overview.

Main information about each File/Folder:

HTML files:
1. index.html - home page
2. index-1.html - teachers page that acts as a teachers handbook
3. StudentsPage.html - students page with unity projects in them (intro animation and cue tutorial)
4. index-2.html - materials page 
5. index-3.html - about us page
6. Tutorial.html - has the unity project of Cue Robot Tutorial
 
Folders:

-Build: contains all the files from the built Introduction Animation project in Unity. 
-js: contains all the javascript files used (however, the main javascript code used is within the index.html file for the slide pictures)
-css: all the css code 
-files: has all the pdf files that are used in the materials page for the teachers
-images: images used for the website
-bat: part of the previous template a mail handler with php code

Extra Details:

The Cue Robot Tutorial Unity Project does not want to show up in the Student Page for some reason (the code is inserted in the StudentPage.html though). This is probably due to that  both projects have the "unity container" name.
There is a link in the text of the title in the Student Page "Cue Tutorial" that has a link to the Tutorial.html that contains the project. The current build of the tutorial has some things look out of place (for example the back button). 


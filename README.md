Download Link: https://assignmentchef.com/product/solved-lab-10-cmput-398
<br>
<h1>Objective</h1>

The purpose of this lab is to introduce you to the OpenCL API by implementing vector addition. You will implement vector addition by writing the GPU kernel code as well as the associated host code.

All parts of this lab will be submitted as one zipped file through eclass. Details for submission are at the end of the lab.

<h1>Instructions</h1>

Edit the code where the TODOs are specified. There are many tutorials on

OpenCL online and in the slides. It can be helpful to get the build log of the OpenCL program to see what issues you might have with your kernel. Check out:

<a href="http://dhruba.name/2012/08/16/opencl-cookbook-building-a-program-and-debugging-failures/">http://dhruba.name/2012/08/16/opencl-cookbook-building-a-program-and</a><a href="http://dhruba.name/2012/08/16/opencl-cookbook-building-a-program-and-debugging-failures/">debugging-failures/</a>

<h1>Local Setup Instructions</h1>

Steps:

<ol>

 <li>Download “Lab10.zip”.</li>

 <li>Unzip the file.</li>

 <li>Open the Visual Studios Solution in Visual Studios 2013.</li>

 <li>Build the project. Note the project has two configurations.

  <ol>

   <li>Debug</li>

   <li>Submission</li>

  </ol></li>

</ol>

But make sure you have the “Submission” configuration selected when you finally submit.

<ol start="5">

 <li>Run the program by pressing the following button:</li>

</ol>

Make sure the “Debug” configuration is selected. Running the program in Visual Studios will run one of the tests located in “Dataset /Test”.

<h1>Testing</h1>

To run all tests located in “Dataset/ Test”, first build the project with the “Submission” configuration selected. Make sure you see the “Submission” folder and the folder contains the executables.

To run the tests, click on “Testing_Script.bat”. This will take a couple of seconds to run and the terminal should close when finished. The output is saved in “Marks.js”, but to view the calculated grade open “Grade.html” in a browser. If you make changes and rerun the tests, then make sure you reload “Grade.html”. You can double check with the timestamp at the top of the page.



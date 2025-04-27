# cmpen-ee-454-project-1-solved
**TO GET THIS SOLUTION VISIT:** [CMPEN/EE 454, Project 1, Solved](https://www.ankitcodinghub.com/product/cmpen-ee-454-project-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;11516&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMPEN\/EE 454, Project 1, Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (4 votes)    </div>
    </div>
<h1>1 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Motivation</h1>
The goal of this project is to implement template matching for the detection of objects in images. One of the most common tasks in computer vision is object detection; be it cars, faces, motion capture markers, or in this case airplanes.

Specifically, the goal is to detect airplanes from a satellite view. In this project you will be provided Google Earth images of airplane depots, with the goal of implementing a template matching based algorithm to detect and count the airplanes in each image.

While this appears to be a simple task at first, you will discover that practical applications have hurdles to overcome. Specifically, in each picture there are multiple different models of airplanes, and these planes are in different orientations in the image.

The specific project goals include:

<ul>
<li>Gain experience in Matlab programming to implement computer vision algorithms</li>
<li>Successfully import, manipulate, and convert images/matrices in Matlab</li>
<li>Establish a method to select the templates used for matching</li>
<li>Use correlation to score the similarity of the template to the image</li>
<li>Use non-maximal suppression to locate and enumerate template matches</li>
<li>Overlay graphics to show location/identification of each detection</li>
<li>Successfully explain and visualize each step of the final algorithm</li>
</ul>
<h1>2 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The Basic Operations</h1>
The following steps will be essential to the successful completion of the project:

<ol>
<li>Image input and conversion for manipulation: Each image needs to be read into Matlab and converted from a standard color image (MxNx3) to a grayscale image (MxNx1).</li>
<li>Selection of a template to use in the correlation: to detect airplanes using template matching the image must be correlated with an airplane template. To generate a template, there needs to be some automatic / manual template identification / selection / computation.</li>
<li>Localizing peaks from the template match: the output of template correlation will be a matrix with multiple peaks where the peaks are higher when the content in the image</li>
</ol>
has increased similarity to the template.&nbsp; Use non-maximum suppression to provide single pixel locations of each peak.

<ol start="4">
<li>Use graphic overlays to enumerate each detection: the final locations need to be counted with a marker showing the detected airplane and a count added as a graphical overlay to the original image.</li>
</ol>
<h1>3 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Evaluation</h1>
<h2>Quantitative</h2>
For this project, quantifying the accuracy of your algorithm’s implementation is easy for you as a human. There are 3 values you should use:

<ul>
<li>True positives: airplanes that the algorithm detects that do exist in the picture based on human perception.</li>
<li>False positives: airplanes that the algorithm detects that do not exist in the picture based on human perception.</li>
<li>False negatives: airplanes that the algorithm does not detect that do exist in the picture based on human perception.</li>
</ul>
&nbsp;

It is essential to show specific examples of the successful detections and failure cases. It is important to identify, enumerate, and evaluate failure cases as part of a process of cyclical improvement to the algorithm’s implementation.

&nbsp;

<h2>Qualitative</h2>
As part of the report, each intermediate step of the process should be visualized to demonstrate the proper functionality of the algorithms implemented for the project.&nbsp; This will include visualizing the input image, the template(s) utilized, the correlation score matrix, the results of non-maximum suppression, and the final graphic overlay results. Figure 1 shows an example input and output image (this is a small sample from the provided test images.

The final report should provide results for each of the input files provided in the assignment. There are two (2) files (dma.jpg and vcv.jpg) provided for testing and evaluation which are both to be included in the report. Additionally, the example1.jpg input image shown in Figure 1 is provided for initial testing. It is recommended that during the initial development of the project code that only a portion of the full resolution test images be used as processing and testing the full images can be time consuming depending on the efficiency of the algorithms implementation. Each of the evaluation images is approximately 14MP with a resolution of 4800×2935.

&nbsp;

&nbsp;

<table width="624">
<tbody>
<tr>
<td width="312"><strong>Input Image (example1.jpg) </strong></td>
<td width="312"><strong>Output Image (example1_output.jpg) </strong></td>
</tr>
<tr>
<td width="312"></td>
<td width="312"><strong>&nbsp;</strong></td>
</tr>
<tr>
<td colspan="2" width="624">Figure 1 – Input (left) and output (right) example images.&nbsp; The output image presents an acceptable graphical overlay to indicate the locations and enumerations of each airplane.

This example is a small sample of one of the images provided.
</td>
</tr>
</tbody>
</table>
&nbsp;

4 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; What Libraries Can I Use?

The intent is that you will implement the various computational modules described using general processing functions <a href="https://www.mathworks.com/help/matlab/functionlist.html">(</a><u><a href="https://www.mathworks.com/help/matlab/functionlist.html">https://www.mathworks.com/help/matlab/functionlist.html</a></u><a href="https://www.mathworks.com/help/matlab/functionlist.html">)</a> in Matlab. The single notable exception is that you MAY use the image processing toolbox <a href="https://www.mathworks.com/help/images/index.html">(</a><u><a href="https://www.mathworks.com/help/images/index.html">https://www.mathworks.com/help/images/index.html</a></u><a href="https://www.mathworks.com/help/images/index.html">)</a>. Specifically, you MAY NOT use anything from the computer vision toolbox, or any third-party libraries/packages. Don’t plagiarize any code from anywhere or anyone else. It saddens us to even have to say that, but you’d be surprised what we discover each and every semester.

<h1>5 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Project Reporting and Evaluation</h1>
Half of your grade will be based on submitting a fully operation program, and the other half will be based on a written report discussing your program, design decisions, and experimental observations. The following components will be submitted:

<ul>
<li>Submit a written report in which you discuss at least the following:
<ol>
<li>Summarize <em>in your own words </em>what you think the project was about. What were the tasks you performed; what did you expect to achieve?</li>
<li>Present an outline of the procedural approach along with a flowchart showing the flow of control and subroutine structure of your Matlab code. Explain any design decisions you had to make. For example, how did you choose or extract airplane templates? If you used raw cross-correlation, did you subtract off the mean of the template first?&nbsp; Did you use normalized cross-correlation instead?&nbsp; How did you implement non-maximum suppression?&nbsp; Basically, explain at each step why you chose to do whatever you did. Be sure to document any deviations you made from the above project descriptions (and why), or any additional functionality you added to increase robustness or generality of the approach. This project is a little open-ended, so detailed explanation of everything you did is necessary for us to fully appreciate your approach to solving this project.</li>
<li>Experimental observations. What do you observe about the behavior of your program when you run it? Does it seem to work the way you think it should? Run the different portions of your code and show pictures of intermediate and final results that convince us that the program does what you think it does.</li>
<li>Extensions and Explorations. If you are in an exploratory mood, find some images of your own on the web and input them to your code. Try an airport like Pittsburgh International (PIT), or Los Angeles International (LAX). Can your implementation find some or all of the airplanes?</li>
<li>Document what each team member did to contribute to the project. It is OK if you divide up the labor into different tasks (it is expected), and it is OK if not everyone contributes precisely equal amounts of time/effort on each project. However, if two people did all the work because the third team member could not be contacted until the day before the project was due, this is where you get to tell us about it, so the grading can reflect the inequity.</li>
</ol>
</li>
<li>Turn in a running version of your main program and all subroutines in a single zip or tar archive file (e.g. put all code, subroutines, etc in a single directory, then make a zip file of that directory for submission via Canvas). We can then unzip/untar everything and go from there.
<ol>
<li>Include one or more demo routines that can be invoked with no arguments and that load any input needed from the local directory and display intermediate <strong>and</strong> final results that show the different portions of your program are working as intended.</li>
<li>We might be running the code ourselves on other input, so include a routine that takes as input a single image and that outputs the matching location results.</li>
<li>Include enough comments in your functions so that we have a good idea what each section of code does. The more thought and effort you put in to demonstrating / illustrating in your written report that your code works correctly, the less likely we feel the need to poke around in your code, but in case we do, make your code and comments readable.</li>
</ol>
</li>
</ul>
FAQ: How long should your report be? We don’t have a strict number of pages in mind, but as a general rule-of-thumb, if the length of your report (excluding figures) is less than the length of this project description document, you probably haven’t included enough detail about what you did/observed.

FAQ: Will the submitted code be evaluated for functionality and coding quality? Yes. Your code and all subsequent functions you write and submit can be reviewed and tested. Please make sure the code is your own unique work and no one else’s, and that each function and what it does is easy for graders to identify.

&nbsp;

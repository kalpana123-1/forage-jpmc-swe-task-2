# JPMC Task 2

Starter repo for task 2 of JPMC's Forage program

<h1> Introduction</h1> 
<b> Experience Technology at JP Morgan Chase </b>
<p>Try out what real work is like in the technology team JP Morgan Chase. Fast track to the tech team with your work.</p>

<h2 id="task"> Module 2 Task Overview </h2>
<p>Use JP Morgan Chase's frameworks and tools
Implement JP Morgan Chase’s Perspective open source code in preparation for data visualization</p>
<p> <b>Aim:</b>Take an incomplete setup of Perspective, i.e. a graph that updates manually, and make it work with the code from Task 1 such that it now updates automatically by continuously requesting from the server application</p>

<ol>
	<li>Please clone this repository to start the task</li>
	<li>[goal-a] In the client application, observe that when new data feed is retrieved whenever you click the 'Start Streaming Data' button, the previous entry is re-entered into the table. Update the application so that the table does not have duplicated entries</li>
	<li>[goal-b] We also want the react app to keep continuosly requesting data from the python server. Currently, the data feed is called only once every time the 'Start Streaming' button is clicked. Change the application to continuously query the datafeed every 100ms when the 'Start Streaming' is clicked.</li>
	<li>[goal-c] Currently, the Perspective element only shows the data in table view after the data loads. Add Perspective configurations so that when the data is loaded, it shows the historical data of ask_price ABC in the Y line chart.</li>
	<li>Upload a git patch file as the submission to this task</li>	
</ol>

<h2 id="installation" >Set up / Installation</h2>
<p>In order to get the server and client application code working on your machine, <a href="https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/setup_devenv_m2_v8.pdf">follow the setup here</a></p>

<h2>How to Run</h2>

<p>Similar to Task 1, start the data feed server by running the python server.</p> 
<p>Make sure your terminal / command line is in the repository first before doing any of this.</p>
<p>If you are using Windows, make sure to run your terminal/command prompt as administrator.</p>

<code> python datafeed/server.py </code>

If you encounter an issue with `datautil.parser`, run this command:

    pip install python-dateutil

If you don't have pip, you can install it from: https://pip.pypa.io/en/stable/installing/

Run <code>npm install && npm start</code> to start the React application.

It's okay to have audit warnings when installing/running the app.

If you don't have `npm` (although you should if you followed the set up / installation part), you can install the recommended version alongside NodeJS from: https://nodejs.org/en/

The recommended version are node v11.0.0 and npm v6.4.1

Open http://localhost:3000 to view the app in the browser. The page will reload if you make edits.

<h2>How to fix the code to meet the objectives</h2>
<p>Ideally you should have some background into programming and possibly some knowledge about web applications/frameworks to reach the objectives of this task.</p>
<p> If you're up to the challenge, please attempt to do this task without using the guide below.</p>
<p>If you have absolutely no clue where to start, you can <a href="https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/making_changes_m2_v2.pdf">follow this guide</a>.</p>

<h2>How to submit your work</h2>
<p>A patch file is what is required from you to submit. To create a patch file, <a href="https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/create_patch_file_v3a.pdf">follow this guide</a>. Then submit the patch file in the <a href="https://www.insidesherpa.com/modules/R5iK7HMxJGBgaSbvk/88AisH7iuw3L5N5ig">JPM Module 2 Page</a>.</p>

Download Link: https://assignmentchef.com/product/solved-ensf592-assignment-6
<br>
5/5 - (1 vote)

<header></header>



 <main></main>



<h2 id="learningoutcomes">&#x1f4da; Learning Outcomes</h2>

<ul>

 <li>Create a simple Flask application with multiple routes</li>

 <li>Scrape and parse data from a single web page</li>

 <li>Store and manipulate data within a DataFrame</li>

 <li>Print a DataFrame object to a webpage</li>

</ul>

<h2 id="programspecifications">&#x1f4bb; Program Specifications</h2>

Follow along with the Lab 12 demonstration. The demo program is a collaborative effort between Garth Johnson and Emily Marasco, and is used with permission. Before submitting your files, you must complete the following tasks:

<ul>

 <li>Change “STUDENT NAME” to your own name in the code.</li>

 <li>Follow the “/hello/” route by entering your own name. Take a screenshot of the display.</li>

 <li>Modify the book table to display a new column with the sale price (reduced by 25%). Submit a screenshot of the modified table being displayed.</li>

 <li>Create a new route “/learn” that displays one thing that you learned in ENSF 592. Submit a screenshot of your answer being displayed.</li>

 <li>Your submitted code must match your provided screenshots.</li>

 <li>Your code will be run by the instructor/TAs as your end user.</li>

 <li>FAQs about the assignment will be answered in Lab 12 and on the D2L discussion boards. Please check the boards for any clarifications before submitting.</li>

 <li>The grading rubric will be posted to D2L.</li>

</ul>

To run your web application: MAC/Linux

<ul>

 <li>Make sure you are working in the correct directory</li>

 <li><code>export FLASK_ENV=development</code></li>

 <li><code>export FLASK_APP=web_data_app.py</code></li>

 <li><code>flask run</code></li>

</ul>

Windows

<ul>

 <li>Make sure you are working in the correct directory</li>

 <li><code>set FLASK_ENV=development</code></li>

 <li><code>set FLASK_APP=web_data_app.py</code></li>

 <li><code>flask run</code></li>

</ul>

Exporting the <code>FLASK_ENV</code> as <code>development</code> enables some nice features that you can explore later on (see Visual Studio’s <a href="https://code.visualstudio.com/docs/python/tutorial-flask#_run-the-app-in-the-debugger" target="_blank" rel="noopener">Run the App Debugger</a> page for more info on how to setup/use it from within VS), and disables some anoying reminders to NOT use this in ‘production’ without a proper WSGI (or similar interface).

Once the application is running, browse the local system on port <code>5000</code> (typically http://localhost:5000/). When you do, you should see the friendly message “Hello World!” in your browser and the following in the terminal where the application is running: ❯ flask run * Serving Flask app “web<em>data</em>app.py” (lazy loading) * Environment: development * Debug mode: on * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit) * Restarting with stat * Debugger is active! * Debugger PIN: 290-425-530 127.0.0.1 – – [25/Apr/2021 12:04:00] “GET / HTTP/1.1” 200 – 127.0.0.1 – – [25/Apr/2021 12:04:01] “GET /favicon.ico HTTP/1.1” 404 –

If you followed the ENSF 592 installation guidelines, you should have all the necessary modules ready to go. If you encounter issues, run the requirements file using <code>pip install -r requirements.txt</code> to ensure you have the correct versions necessary. Make sure you are in your assignment working directory and your ENSF 592 virtual environment.

<h2 id="assignmenttasks">&#x1f4dd; Assignment Tasks</h2>

<ul>

 <li>If you weren’t able to attend the June 15th lab, be sure to watch the recording and follow along.</li>

 <li>Clone this repository to your local computer.</li>

 <li>Open VSCode and start a new terminal. Make sure that your <code>ensf592</code> environment is activated.</li>

 <li><code>web_data_app.py</code> is provided as a starting point. Add your name to the header.</li>

 <li>Remember to test your program execution via the terminal: <code>run flask</code></li>

 <li>Fulfill the tasks above and upload the successful execution screenshots to your assignment repository.</li>

 <li>Commit your screenshots and code.</li>

 <li>Push your local git history to github: <code>git push origin main</code></li>

 <li>Submit your repository HTTPS link to the Assignment 6 D2L dropbox.</li>

 <li>Tip: If you want to learn more about a specific aspect of Python or Flask, remember to take a look at the official documentation!</li>

</ul>

<h2 id="developercomments">&#x1f4da; Developer Comments</h2>
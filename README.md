Internet Speed Test
This project is a simple web application that measures and displays your internet download speed using a gauge chart from Google Charts.

Features
Tests internet download speed using a sample file.
Displays real-time speed on a Google Charts gauge.
Shows the average download speed at the end of the test.
Technologies Used
HTML: Structure of the web page.
CSS: Styling for the application.
JavaScript: Core logic to perform the speed test and render results.
Google Charts: Visualization for download speed.
How It Works
File Download: The app downloads a sample file to measure the speed.
Speed Calculation:
Measures the amount of data downloaded over a specific time period.
Calculates speed in Mbps (megabits per second).
Gauge Display: Updates the gauge chart in real-time to show current download speed.
Final Speed: Displays the average download speed after the test.

Setup and Usage
1. Prerequisites
A modern web browser with JavaScript enabled.
Internet connection to test download speed.
2. Running the Application
Clone the repository or download the source files.
Ensure the following files are in the same directory:
index.html (HTML structure).
styles.css (CSS for styling).
script.js (JavaScript logic).
Open index.html in a browser to run the application.
3. Start the Speed Test
Click the "Start Test" button.
Watch the gauge update in real-time.
View the average download speed displayed after the test.
Project Structure
bash
   
**/internet-speed-test**
│
├── index.html   # Main HTML file
├── styles.css   # Styles for the web page
├── script.js    # JavaScript logic for the speed test

Customization
Sample File URL: Change the fileUrl variable in script.js to use a different sample file for testing.
Test Duration: Adjust the testTime variable in script.js to modify the duration of the test.

Limitations
Results may vary based on:
Network conditions.
Size of the sample file.
Browser limitations (e.g., caching, download speed caps).

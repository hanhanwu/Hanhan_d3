# Hanhan_d3
data visualization

* Using D3 to create animated visualization
  1. I was coding in JSBin which is very convenient to add libraries like D3, and will see the results immediately. (You's better uncheck auto run with JS, otherwise the webpage will froze for no reason)
  2. static.html - Base static html, and my other HTML code makes changes based on it to create different animations.
  3. transition.html - At the beginning, the text is on the left side and it is in black color. After waiting for 1 sec, it moves from left to right by 100px, where the duration time is 1 sec. Once it arrives at the right side, the color of each character is changed from black to its rainbow color.
  4. selection_exit.html - At the beginning, there is no text. Every 0.5 sec, there is a new character (including space) showing up from left to right. Once all the characters show up, each character will disappear one by one from right to left (every 0.5sec).
  5. selection_on.html - At the beginning, all characters are in black color. Once you move the mouse over each character, the color of the character changes from black to its original color. Once you move the mouse out the character, the color changes to black after waiting for 1 sec.

*************************************************************************************************

Time to practice more in d3 and Javascript. Somtimes, you still need to write Javascript as a data scientist, either for data visualization purpose, or to do more experiments when developers are busy with other work.

<b>IDE & Server</b>
* Now I use <b>Visual Studio Code</b>. With this tool, I even no need to install or run any server
  * Use the method [here][1], so that when you press `Cmd+Shift+B`, the website will be launched to chrome directly
  * BTW, I don't like Sublime Text, I tried 1 hour, guidance on its manual never worked for me.
* But!! When you are loading local data, you may only get this error, "Cross origin requests are only supported for HTTP". The solution is to start your local server and run the website
  * `cd` to the directory where you are writing your .html page
  * Python2.*: type `python -m SimpleHTTPServer 8000` in your terminal
  * Python3.*: type `python -m http.server` in your terminal
  * Then just go to http://0.0.0.0:8000/ to open your .html page


*************************************************************************************************

RESOURCES

* D3 for Beginners: https://www.analyticsvidhya.com/blog/2017/07/beginner-guide-build-data-visualisations-web-d3-js/
  * If you want to use Python to launch server (with Visual Studio Code, no need this)
    * `cd` to the directory where you are writing your .html page
    * Python2.*: type `python -m SimpleHTTPServer` in your terminal
    * Python3.*: type `python -m http.server` in your terminal
    * Then just go to http://0.0.0.0:8000/ to open your .html page
  * Author's original code: https://github.com/hanhanwu/d3js/tree/master/AV_D3_Intro
  * SVG or Scalable Vector Graphics is a format used to draw xml based graphics and animations. <b>SVG graphics do NOT lose any quality if they are zoomed or resized.</b>
    * The origin(0,0) in SVG is at the <b>“top-left”</b>
  * `d3` is a global object that we can use it to select web elements, such as `d3.select("body").append("p").text("Baby Emmanuel!")`
    
* <b>D3 Original GitHub</b>: https://github.com/d3/d3
  
  
* Jaw drop D3: https://www.analyticsvidhya.com/blog/2017/08/visualizations-with-d3-js/?utm_source=feedburner&utm_medium=email&utm_campaign=Feed%3A+AnalyticsVidhya+%28Analytics+Vidhya%29
  * Jaw didn't drop, but it's am amazing tutorial
  * .tsv is a tab seperated data file

*************************************************************************************************

PRACTICE

* Beginner Code: https://github.com/hanhanwu/Hanhan_d3/tree/master/beginner


*************************************************************************************************
  
  
[1]:https://www.webucator.com/blog/2016/06/launch-files-browser-visual-studio-code/

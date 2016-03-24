# Hanhan_Data_Visualization
data visualization

* Using D3 to create animated visualization
  1. I was coding in JSBin which is very convenient to add libraries like D3, and will see the results immediately. (You's better uncheck auto run with JS, otherwise the webpage will froze for no reason)
  2. static.html - Base static html, and my other HTML code makes changes based on it to create different animations.
  3. transition.html - At the beginning, the text is on the left side and it is in black color. After waiting for 1 sec, it moves from left to right by 100px, where the duration time is 1 sec. Once it arrives at the right side, the color of each character is changed from black to its rainbow color.
  4. selection_exit.html - At the beginning, there is no text. Every 0.5 sec, there is a new character (including space) showing up from left to right. Once all the characters show up, each character will disappear one by one from right to left (every 0.5sec).
  5. selection_on.html - At the beginning, all characters are in black color. Once you move the mouse over each character, the color of the character changes from black to its original color. Once you move the mouse out the character, the color changes to black after waiting for 1 sec.

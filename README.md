## <\NAME>=<\VALUE> V1.2!
### Extremely Simplistic HTML page
with basic functionality of accepting "`<name>=<value>`" input and storing it as pairs of names and values in a neat output.
V1.2
- Now with improved mobile css!
- Press enter instead of "Add" button!
- And a brand new checkbox that gives you a new feature! <- (it's not that exciting, but it is qol feature)
#### Controls
You are able to **select the output pairs** using your **mouse cursor or touchscreen**. The script is able to detect selected pairs through containsNode() function with output pairs. This implementation is the fastest and easiest to code way, that works with pure js (and doesn't involve nodejs)

You are also presented with minimalistic UI, for basic operations, like buttons to:
- Add a new pair from input to output
- Remove the First pair in output
- Remove Selected pair(s) in output
- Remove the Last pair in output
- Clear all pairs in output

as well as dropdown menus that allow you to choose between multiple option of sorting your pairs and presenting them. The options are

**Sorting Options**
 - No sort (all new pairs appear at the bottom)
 - Key A > B (sort all pairs by first value in alphabetical order)
 - Key A < B (sort all pairs by first value in reverse order)
 - Value A > B (sort all pairs by second value in alphabetical order)
 - Value A < B (sort all pairs by second value in reverse order)

**Output Presentation Options**
 - Default (Presents pairs as `Key=Value`)
 - Raw (Presents pairs as `[{Key: Value}]`)
 - JSON-ish (Presents pairs as `Key: Value`)

and now (since V1.2) you are also able tick a checkbox:

**Add "=" on Enter**
- A qol (quality of life) feature that was requested by testers. This feature is enabled by default, and it will check if what you're entering has an equal sign (=), and if it doesn't, it will be placed automatically (if the input query is selected)
 
You are also able to use your keyboard (doesn't trigger mobile or gaming console virtual keyboard features) to use special keybinds such as:<br/>**Enter**: Acts the same as the on-screen "Add" button; (V1.2+)<br/>**Backspace**: Acts the same as the on-screen "Remove Selected" button;<br/>**F8**: Generates a pair with random key and value. (usefull for testing);<br/>**F9**: Switches between Day(White) and Night(Dark Blue) themes;<br/>**F10**: Enable and disables *Debug Mode*. Only changes the color a few elements and how console logging acts (usefull for testing);

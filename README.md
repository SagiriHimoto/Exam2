## <\NAME>=<\VALUE>
### Extremely Simplistic HTML page
with basic functionality of accepting "`<name>=<value>`" input and storing it as pairs of names and values in a neat output.
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
 
You are also able to use your keyboard (doesn't trigger mobile or gaming console virtual keyboard features) to use special keybinds such as:
**Backspace**: Acts the same as the on-screen "Remove Selected" button;
**F8**: Generates a pair with random key and value. (usefull for testing);
**F9**: Switches between Day(White) and Night(Dark Blue) themes;
**F10**: Enable and disables *Debug Mode*. Only changes the color a few elements and how console logging acts (usefull for testing);

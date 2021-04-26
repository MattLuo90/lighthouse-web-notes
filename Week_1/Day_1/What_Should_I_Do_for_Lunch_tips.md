 ### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry === true) {
    if (availableTime <= 20) {
      console.log("i should eat my sandwich in the kitchen.");
    } else if (availableTime > 20 && availableTime < 30) {
      console.log("i could have a break and try the Ramen Restaurant in Gastown");
    } else if (availableTime >= 30) {
      console.log("this is a intense course I shouldn't take a lunch break more than 30 minutes.");
    }
  } else {
    console.log("I should get back to the work.");
  }
};
```

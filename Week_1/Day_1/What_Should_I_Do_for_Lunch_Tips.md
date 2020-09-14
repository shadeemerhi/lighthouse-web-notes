### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry === true) {
    if (availableTime <= 20) {
      return 'Pick something up and eat it in the lab';
    } else if (availableTime > 20 && availableTime <= 30) {
      return 'Try a place nearby!';
    } else if (availableTime > 30) {
      return 'Remember, we are at Bootcamp! Be mindful of your time spent away from work! Grab something, but be back quick!';
    } else {
      return "I don't know what to do!";
    }
  } else {
    return "I will eat later when I am hungry";
  }
};
```
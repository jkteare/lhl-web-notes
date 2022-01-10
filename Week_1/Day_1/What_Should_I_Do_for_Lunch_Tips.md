### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry === false) {
    console.log('You are not hungry, hunker down!');
  } else {
    if (availableTime < 20) {
      console.log('Pick something up, and eat in the lab');
    } else if (availableTime >= 20 && availableTime < 30) {
      console.log('Check out something in Gastown, maybe sushi?');
    } else (console.log('Do you really? You are in bootcamp!'));
  }
};
```
### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (!hungry) {
    console.log(' Please get back to work. Wait until you are hungry');
  } else if (availableTime < 20) {
    console.log('Please pick somthing up and eat it in the lab');
  } else if (availableTime >= 20 && availableTime < 30) {
    console.log('Try a place nearby');
  } else {
    console.log('Please reconsider. You are in a bootcamp. You dont have that much time');
  }
};
```
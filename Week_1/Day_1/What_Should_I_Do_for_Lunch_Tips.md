### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces.

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.


```javascript

function whatToDoForLunch(hungry, availableTime) {
  if (hungry === false) {
    console.log("Keep Coding");
  }
  else if (availableTime < 20 ) {
    console.log("Grab a bite in the Kitchen");
  }
  else if (availableTime >= 20 && availableTime <=30 ) {
    console.log("Check out Gastown");
  }
  else {
    console.log("Check yourself, before you wreck yourself");
  }
}

```
---
layout: post
title: Stacks and Trees
--- 

## Factor

Get acquainted [Factor](http://factorcode.org/). Download it, and experiment with the examples [on the site](http://concatenative.org/wiki/view/Factor/Examples) and on [Rosetta Code](http://rosettacode.org/wiki/Category:Factor). I tested and confirmed that the graphics examples are working, you just have to pay attention to the **Running the examples** part of the page. Start with the simpler ones, then get more complex. As always, be mindful of the feeling of writing code in Factor. How is it different from what you already have seen? How is it the same? Better? Worse?

## Solved Homework

[This is as far as we got in class.](https://gist.github.com/nasser/b4aa988a1ffa5cee08ab)

## Homework for Next Week

Next week's [homework]({{ site.url }}/lanuages/jisp-trees.html) has you building out the example from class. As a recap: we're parsing everything that looks `(something like this)` into a JavaScript object that looks like this

<pre><code>
{parens: {symbol: "something"}
 arguments: [
      {symbol: "like"},
      {symbol: "this"}
   ]
}</code></pre>
 
And that object is being passed into a function called `JispEval` to actually evaluate. You will have to edit the `JispEval` function to complete the assignment.

Work in groups if that's helpful!

## Final Projects

Have some idea as to your final project by next class! I will go around and talk to you about what you want to accomplish and we can figure out how to best approach it. The constraints for this class are loose, anything language-like or tool-like is acceptable.
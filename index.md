# On the Edit file tab, add a '#', followed by a space, before any content you like to make it an H1 Header. You can add more headers, using one to six '#' characters followed by a space

Here I used one # in the above line of this markdown file. Becasue as `<#>` This is an `<h1>` header, which is the largest.

# Let's add an image. Including descriptive text in the square brackets. This text can be read aloud for people using screen readers. It's also shown at times when image doesn't display, such as when there's a poor connection.

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

# Time to add some code blocks. Code blocks can render differently depending on the languages on github. let's take a look at this verilog coding from http://www.nandland.com:

``` verilog
module example_and_gate 
  ( 
    input_1,
    input_2,
    and_result);
   
  input  input_1;
  input  input_2;
  output and_result;
 
  wire   and_temp;  
 
  assign and_temp = input_1 & input_2;
   
  assign and_result = and_temp;
 
endmodule
```

# Adding a list (Remember, a task list starts with the syntax - [ ] and then the task list item. The formatting is specific!)

- [ ] Turn on GitHub Pages
- [ ] Outline my portfolio
- [ ] Introduce myself to the world



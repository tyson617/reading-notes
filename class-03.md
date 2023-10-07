# Class-03 Reading Notes

# HTML

- When should you use an unordered list in your HTML document?<br>
  - When listing something that doesn’t have a specific numbered order and when you     want to use bullet points.<br>

- How do you change the bullet style of unordered list items?<br>
  - You would use CSS property list-style-type.<br>

- When should you use an ordered list vs an unorder list in your HTML document?<br>
  - You would use an ordered list when the items require a set sequence and an          unordered list for anything else.<br>

- Describe two ways you can change the numbers on list items provided by an ordered list?<br>
  - You can use <ol start=” “> or <ol type=” “> <br>

# CSS

- Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?<br>
  - The margin box is the space surrounding the padding box, being the outermost border. The padding box surround the content.<br>

- List and describe the four parts of an HTML elements box as referred to by the box model.<br>
  - The four parts of an HTML box model are box-sizing, *, , *::before, *::after, and followed by box-sizing: inherit.<br>

# JavaScript

- What data types can you store inside of an Array?<br>
  - Strings, numbers, objects, or other arrays.<br>

- Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?<br>

`const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];`<br>
  - Yes, it is valid. Each subarray would be accessed by the following<br>
    - `const petesInfo = people[0]`<br>
    - `const smithsInfo = people[1]`<br>
    - `const billsInfo = people[2]`<br>
 
- List five shorthand operators for assignment in javascript and describe what they do.<br>
  - Addition: `x += f()` is used to add numbers or concatenate a string<br>
  - Division: `/= f()` is used to divide numbers<br>
  - Exponentiation: `x= **= f()` is used to perform exponentiation of numbers<br>
  - Left Shift: `x = <<= f()` will assign the result to the left of the operands<br>
  - Logical AND Assignment: `x &&= f()` will evaluate to the right and only assigns to the left of the operand if it is truthy<br>

- Read the code below and evaluate the last expression and explain what the result would be and why.<br>
  - let a = 10;<br>
  - let b = 'dog';<br>
  - let c = false;<br>
 `// evaluate this (a + c) + b;` <br>

  - The result would be 10dog because a false boolean has a value of 0 and JavaScript will then convert the numerical 10 into a string and      add it to dog.<br>
    
- Describe a real world example of when a conditional statement should be used in a JavaScript program.<br>
  - A real world example would be making the decision to do a coding bootcamp. If I do the bootcamp, then I increase the chances of getting     a job, or if I don’t then I’d have to teach myself and potentially decrease my odds.<br>

- Give an example of when a Loop is useful in JavaScript.<br>
  - Loops are useful when needing to perform a repetitive task over data structures.<br>


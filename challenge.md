## General Requirements
- Use either Ruby or Javascript. If you feel more comfortable with another language, please let us know and we can discuss. 
- Do not use any external libraries or frameworks, such as Rails, to solve this problem. You may only use external libraries or tools for building or testing purposes (e.g., Rspec, Jest, Mocha, etc.).
- Include detailed instructions on how to run the application and an explanation of assumptions you make (if any)


**IMPORTANT:**  

Please limit the amount of time you spend on the problem to **4 hours**. If you haven't completed the challenge within the allotted time, please submit the work you have completed. Focus on implementing the requirements with the best code you can produce within the given timeframe. 

Submit your solution either as a zip file via email or upload to a public repository (GitHub, Bitbucket, etc.) and share the url with us.


## Problem Statement 

This problem requires some kind of input. You are free to implement any mechanism for feeding the input into your solution. You should provide sufficient evidence that your solution is complete by, as a minimum, indicating that it works correctly against the supplied test data.

**Basic sales tax** is applicable at a rate of **10%** on all goods, **except** books, food, and medical products that are exempt. **Import duty** is an additional sales tax applicable on all imported goods at a rate of 5%, with no exemptions.

When I purchase items I receive a receipt which lists the name of all the items and their price (including tax), finishing with the total cost of the items, and the total amounts of sales taxes paid. The rounding rules for sales tax are that for a tax rate of n%, a shelf price of p contains (np/100 rounded up to the nearest 0.05) amount of sales tax.


Write an application that prints out the receipt details for these shopping baskets:

### Input

#### Input 1:
```
2 book at 12.49
1 music CD at 14.99
1 chocolate bar at 0.85
```

#### Input 2:
```
1 imported box of chocolates at 10.00
1 imported bottle of perfume at 47.50
```

#### Input 3:
```
1 imported bottle of perfume at 27.99
1 bottle of perfume at 18.99
1 packet of headache pills at 9.75
3 imported boxes of chocolates at 11.25
```

### Output

#### Output 1:
```
2 book: 24.98
1 music CD: 16.49
1 chocolate bar: 0.85
Sales Taxes: 1.50
Total: 42.32
```

#### Output 2:
```
1 imported box of chocolates: 10.50
1 imported bottle of perfume: 54.65
Sales Taxes: 7.65
Total: 65.15
```

#### Output 3:
```
1 imported bottle of perfume: 32.19
1 bottle of perfume: 20.89
1 packet of headache pills: 9.75
3 imported boxes of chocolates: 35.55
Sales Taxes: 7.90
Total: 98.38
```


# Important
The coding exercise is not designed to be difficult and should only take you a maximum of 4hrs to complete (this isn't a rule however). It is not timed so you are able to come back to and from the exercise. 

To help you pass the technical test, here are some tips:
Please make sure you use the latest versions of Ruby (don't use Rails).
Ensure you fully understand the coding exercise instructions before starting the exercise.
Please follow Object-Oriented Programming Structures and use familiar Ruby Paradigms.
Make sure your code is well tested and provide lots of documentation (README files) to show what you are doing and why.
Ensure your code is well-organized.
Make sure your code is thread-safe and production ready.
DON'T OVER ENGINEER YOUR CODE. SUBSCRIBE have often failed engineers for over-engineering the simple exercise. Make sure you complete the full exercise and exactly to what they have asked.
Make sure you're happy with your code and it reflects your best work. 
Here is some negative feedback from SUBSCRIBE regarding the technical assignment stage that I have received:

- Code challenge utilized one class that did almost everything - calculate tax, total price, and output. Used inheritance instead of composition
- Failed to show Object-Oriented Structures and the code was poorly organised. 
- Code wasn't tested and had no signs of standard Ruby paradigms.
- procedural approach rather than a scalable design. Overall, it lacks the flexibility and abstraction we expect at a senior level.

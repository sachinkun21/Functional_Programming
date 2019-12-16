For loops are a Swiss army knife for problem-solving, but, when it comes to scanning code to get a quick read of what you’ve done, they can be overwhelming.

Three techniques — map, filter, and reduce — help remedy the for loop mania by offering functional alternatives that describe why you’re iterating.

In this Repo, I will cover each of the three techniques, highlighting the syntactic differences between them in Python, and then give examples of how to convert common for loop syntaxes into one of these.


Infact 95% of the time when looping through strings or arrays we do one of the following: 
- map a sequence of statements to each value
- filter values that meet specific criteria
- reduce the data set to a single aggregate value.

With that insight, these three methods are recognition and implementation:— that the reason you loop through an iterable often falls into one of these three functional categories:

- **Map**: Apply the same set of steps to each item, storing the result.
- **Filter:** Apply validation criteria, storing items that evaluate True.
- **Reduce:** Return a value that is passed from element to element.

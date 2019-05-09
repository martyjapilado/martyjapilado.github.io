---
layout: essay
type: essay
title: Red Means Bad and Green Means Good So It’s a Good Thing I’m Not Colorblind
published: false

# All dates must be YYYY-MM-DD format!
date: 2019-02-07
labels:
  - Software Engineering
  - JavaScript
  - Learning
  - Coding Standards
---

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I recall a specific question that psyched me out in a quiz. The code looked something similarly this:
```C
int ezpz(int x) {
    int y = x;
    int i;
    for(i = 0; i < 100; i++) {
        y += i;

    return y;
    }
}
```
The question was how many iterations will the for loop go through. This is how I got baited out of a single point, because someone like me would think “oh the result is at the same line as the for loop, therefore it returns out of the for loop”. My answer: 100 iterations. The real answer was one. This was a lesson by the professor on coding style, because the return statement is positioned in a way that looks to be out of the for loop. 
	<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The code is formatted and readable in a way that it’s easy to follow for the reader. My old code from ICS 111, my first computer science class, contains violations of coding standards I’ve followed. In my old code, there are multiple occurrences of empty lines in between code, which looks jarring with unnecessary comments. Even worse, there are empty lines in between unnecessary comments. The idea behind coding standards is that you could comment a whole lot less, for someone to follow a narrative behind the code with little effort. This becomes real important in group projects.</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Up until the Wednesday of the week, the complete absence of ESLint in my IntelliJ IDE escaped me. The reason for this is the thought of “Oh yes,.eslintric is in the directory, ESLint is enabled and a green check mark is on the top right of my IDE” convinced me ESLint was installed to my projects. It wasn’t until the practice WOD with Branden, the class teaching assistant, that I managed to figure out that ESLint wasn’t installed (for the duration of the whole week) into any of my projects. This was because one crucial command was missed while installing ESLint. Which command that is, cannot be recalled as of now. But that Wednesday led me to reinstall ESLint with Branden, which left me with half of a day’s experience by the time of that week’s WOD.<p>
	<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Everything you read from here forward is what I’ve gathered from half and experience of ESLint with IntelliJ. During the WOD, everything was going well, until I saw that ESLint highlighted something, because I thought I could add to string using the infamous ‘string + otherString’ method to join the strings. I worked around this using ‘string.concat(otherString)’ instead. This was a nice work around, as ESLint didn’t return any errors. The code worked, so then I proceeded to spend the next twelve minutes attempting to push the project to GitHub. I didn’t fail too hard so that’s what I’d like to call a success. Anyway, ESLint, like many other plugins for IDEs that work as a coding standard ‘Grammarly’ plugin, provide nice instant feedback to the coder that makes it my code more readable to both the author and viewers. All I had to know was that if there's red on the left, just adjust it to make it green so the code satisfied the standards.<p>

---
layout: essay
type: essay
title : Structure and Design for Precautions and Big Mistakes
published: false

# All dates must be YYYY-MM-DD format!
date: 2019-04-28
labels:
  - Design Patterns
  - Software Engineering
---
	
There are things that I start to notice the more I move up within Computer Science. There are things in the code that we always run into such as bugs, errors, etc. I noticed that coding styles is a given in all courses, each one with their own differences and similarities (getting some déjà vu vibes just typing that). In terms of a design pattern, it gets a bit broader as there are common occurrences, inconveniences, and things that give me heart palpitations within the code that I often experience. Some instances of this are minor, such as a missing bracket at the end of the code. 

However, there are much broader cases such as a recent case I experienced with my Software Engineering project. Originally, my team and I decided to work with a single schema to represent a singular object: a recipe. Now, in a recipe, there are things such as ingredients or the type of diet of the recipe. It turned out that incorporating these elements turned out more complicated than usual. We then decided to use a less complicated (as told to me) using a pattern similar to that of a composite design pattern, where the team decided to make four different schemas. These schemas were one for ingredients, one for diet types for the recipes, other elements such as the name and serving size, and a last one where we piece together all the schemas together. It appeared easier and organized in this way.

The effect of organization and structure from design patterns are quite eye-opening. It's like finding not just faster, but more convenient ways to just go about things. Say I had a task such as buying groceries. Say I could just walk in and buy everything and walk out with full confidence that whatever I have purchased can sustain me until my next visit. Alternatively, I could take a more organized approach, such as picking a list based on ingredients to recipes that looked appealing to me. Then I picked a date based off a sale of some of my items. This is what appeals to me with [Structural Patterns]( https://sourcemaking.com/design_patterns/behavioral_patterns). I imagine I would correlate all these things such as ingredients, recipes, packages, and purchases so that my grocery visit ends up being “optimal”.




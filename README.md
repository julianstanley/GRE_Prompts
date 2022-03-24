# GRE_Prompts
A quick notebook investigating GRE writing prompts

This repository contains a day-project where I wanted to figure out how to best prepare for the GRE writing prompts. It's not very clean, but maybe you'll find it helpful. 

In `GRE Sentences.ipynb`, you'll see that I scrape GRE the offical GRE prompts from the ETS website.

Then, I clean and tokenize the prompts. 

I cluster the prompts and find that, for the issue prompt, many (24) of the prompts are nearly identical, with 95%+ similarity. 
For the argument prompt, even more (33) pass this threshold.

Therefore, you can study just a subset of the issue and argument prompts to effectively prepare for the GRE writing section.

I sorted the prompts by similarity (sorted_prompts_argument.txt and sorted_prompts_issue.txt) and used that sorted list to study, picking one prompt to practice and then skimming prompts until I found a different-enough prompt for the next study session.

This is my first refactor so I had a hard time initially finding an approach, after reorganizing the code in a way that was a bit easier
to read I started to find a lot of errors in redundancy.

I started by renaming the title from "website" to the name of the company.

I then reorganized the code by their div classes just for my own easier readability.

Looking through the css file, a lot of the classes and id's seemed out of order so I moved them in the order of their appearance in the code

The ls and ul had longer names that I condensed only because they were the only instances of those names.

I noticed a lot of repetition, such as the part containing "Search-Engine-Opimization", "Online-Reputation-Management", etc. I regrouped those
    into a single class called sub-groups and grouped them that way.

Same process went into changing the benefits section since there were so many classes doing the exact same thing.

The footer seems okay in only being two different parts.

I also went through and changed headers like h2 to be more uniform despite being in different areas.
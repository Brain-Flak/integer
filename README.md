# [Brain-flak Integer Metagolfer](https://brain-flak.github.io/integer/)

[Brain-flak](https://github.com/DJMcMayhem/Brain-Flak) is a stack-based esoteric programming language, where the only valid characters are balanced pairs of brackets. Because this language is so minimalistic, sometimes expressing large numbers can be a pain. For example, the number "100" can be expressed in brain-flak as:

    (()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()()())
    
But this *clearly* not the best way to write it. A more optimal way of expressing 100 in brain-flak is

    ((((((()()()){}){}){}()){}){})
    
Coming up with these can be hard. This program allows you to enter a number, and it attempts to find the most optimal way of writing that number in brain-flak. Although it's still a work in progress, so sometimes the outputs will be suboptimal.

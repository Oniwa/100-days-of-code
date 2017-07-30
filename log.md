# 100 Days Of Code - Log

### Day 3: July 30th, 2017

**Today's Progress:** Got program to work correctly.  The model is verified by math as shown [here](https://www.reddit.com/r/spikes/comments/5eaf7r/standard_what_is_the_chance_to_hit_delirium_off/).  Also reduced program runtime from 5+ hours to about 30 seconds.

**Thoughts:** Program runs good enough but there are still some issues I could tackle as shown in the todo list.  These issues would improve the quality of the code for future use and make it easier to work on it while also teaching me a bit more about unittests.  I will consider this project done for now.

**Link to work:** [mtg_tools](https://github.com/Oniwa/mtg_tools)

### Day 2: July 29th, 2017

**Today's Progress:** Redesigned the deck list importer and refactored code to accommodate these changes.  Still need to get my user story to pass but have all other unittests passing.

**Thoughts:** Working with 3rd party APIs can be tough.  I can't figure out why one of my queries isn't returning correctly when everything else is.  Also had some super weird issues with namespaces in my unittests that caused a bunch of problems.

**Link to work:** [mtg_tools](https://github.com/Oniwa/mtg_tools)

### Day 1: July 28, 2017

**Today's Progress**: Finished the model for delirium checker in MTG_Tools.

**Thoughts:** There are some efficiency problems.  It is making an HTTP API call way too often.  Solution is to do the calls once and store the card objects and then use those in the model.

**Link to work:** [mtg_tools](https://github.com/Oniwa/mtg_tools)

### Day 0: July 27, 2017

**Today's Progress**: Edited the project files to align the scope of this challenge with what I want to be doing.

**Thoughts:** I am looking forward to beginning this challenge.

**Link to work:** [100 Days Of Code](https://github.com/Oniwa/100-days-of-code)

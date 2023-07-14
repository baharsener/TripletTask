# TripletTask
A task exploring the relationship between the mental timeline and spatiotemporal memory. This is task is adapted from Pathman et al., (2018).
A triplet of objects is presented in either a left-to-right linear, right-to-left linear or a nonlinear order (this is determined by where on the screen the first, second and third images appear).
After 25 encoding trials, participants are shown some these objects one by one and asked the temporal order of the object ("when did you see this object, first, second or third?")
Each triplet is shown twice with a mask in between, and about 20% of the trials show a different order during these two viewing portions to act as an attention checker ("were the two triplets same or different?") Only the objects from encoding trials that showed the same order twice are used in the retrieval phase. 
We ran a behavioral version of this task before and saw a significant memory boost for triplets that were presented from left-to-right for temporal memory, and we now want to include pupil and other eye movement methods to get a better insight into the process of temporal memory encoding using the mental timeline. Changes we implemented in this version:
We have a 2 second fixation cross to base a baseline pupil dilation off of.
we have a delay between retrieval question and appearance of answer options to check for eye movements.
Answer options are vertical rather than horizontal. 
We think that pupil dilation will track with memory accuracy. 

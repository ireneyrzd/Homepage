+++
date = "2021-07-25T12:00:00-00:00"
title = "Music and Machine Learning Brainstorm"
tags = [ "Machine Learning Brainstorms" ]
comments = true
share = true
+++

My favorite hobbies revolve around music as I enjoy playing the piano, the flute, and dancing. Additionally, I enjoy building both tangible and virtual projects. In the future, I would like to major in Computer Science, and currently am most appealed in the field of machine learning. Thus, I would like to combine my interests to create a machine learning project that would benefit music education.
 
Below are some of my project brainstorm ideas as well as how they can fulfill the needs for people from a variety of backgrounds.
 
 
# Beat Detection:
## Current technologies:
Currently, there are already research papers written about beat detection in a piece using neural networks. I would like to explore how we can apply it in daily music playing and how it can benefit people from different types of music backgrounds.
 
## Problem
1. During the COVID-19 pandemic shelter in place, my flute ensemble was forced to put together performances by recording our parts separated and combining them through an editing tool. However, a big dilemma we faced while rehearsing is how to make sure everyone is syncing together. While we rehearsed over Zoom, the lag in the internet meant that we could never hear everyone while we rehearsed as we will always sound ahead of others and it's an infinite cycle of waiting for each other.
2. In addition, recording is also a problem. For songs with fixed tempo, we could agree on metronome tempo and record having everyone follow the tempo strictly. However, for songs with more flexibility in the rythme (e.g. have tempo changes, *ritardando*, *accelerando*), we could not prepare because everyone would have different timing at the tempo changes. Thus, when the audio files are combined, the beats and notes do not match up, and the final result sounds messy.
 
## Beat Detection as Solution
In a TED Talk by a Stanford professor, I had the chance of learning about beat detection using machine learning. If we can process every audio file by labeling the main beats within a measure, then when we combine everyone's recording together, we could easily edit the audio files to sync by aligning the main beats. The result is a fully matched combined recording. This can benefit online forms of music ensembles and bands in helping to create synchronized recordings and virtual performances.
 
Another idea is an auto-generated conductor using beat detection and machine learning. The jobs of a conductor in an ensemble are, according to Wikipedia, "to unify performers, set the tempo, execute clear preparations and beats, listen critically and shape the sound of the ensemble, and to control the interpretation and pacing of the music" by giving visual cues. While tasks such as pointing out dynamic change and steady tempo can easily be assessed by reading the music score, others, like deciding the interpretation, the expression of the music is more abstract.
 
In an ensemble of students without a conductor, a computer-generated conductor would greatly increase the efficiency and quality of rehearsal. The virtual conductor would train using existing recordings of other bands playing the same song, other songs in the same style of music or ones written by the same composers, and most importantly, a part played by the lead player. Using these inputs, the computer created conductor would have an understanding on how the song should be interpreted and expressed, then giving vision cues of tempo and dynamic to the player. This would benefit players practicing, but more importantly those who are unable to come together for in-person rehearsal and need seperate, virtual practice sessions. This would fix the dilemma of synchronizing during online rehearsal by providing a virtual conductor to practice with. It opens up the possibility of more virtual, long-distance ensembles involving members from all over the world, to perform songs together.
 
Finally, this can be expanded to create online duet partners. Observed by my piano teacher, I found that beginner players are much attracted to playing duet music. Not only does the sense that someone is accompanying you solves the common grudge against practicing piano being lonely, it also decorates an original simple piece to sound more sophisticated and give the player a sense of accomplishment.
 
# Music Generation:
## Uses:
Analyzing Google Magenta's project (https://magenta.tensorflow.org/piano-transformer), there are three main categories that a machine generated music can be useful:
 
1. Creation*
  - Creating background music for commercial purposes
2. Continuation
  - Helping a composer create new raw materials to work on by extending any short phrases they have written into a longer, more complete phrase
  - Continuation of a song in the same style to create an elongated version of a piece
  - Continuation in the sense of extending the work repertoire of a deceased composer in a matching style
3. Accompaniment
  - Creating an accompaniment of a pop song given a level of difficulty imputed based on the desire of a player
  - Creating corresponding duet parts to be played by a computer along with a beginner piano player
 
* In these three categories, I found the unconditional idea to be more achievable for me in the current phase and the easiest one to improve. As a result, I have created a similar project during my time in the Summer Research Academies program. I will follow up on my findings and opinions in the following post, as well as how the topic can be extended to fit a variety of different usages.
 
 


+++
date = "2021-07-24T12:00:00-00:00"
title = "Music and Machine Learning Brainstorm"
tags = [ "Machine Learning Brainstorms" ]
comments = true
share = true
+++

If you look at my other post (SRA Experience Recap 7/26), the current music generation models can be improved to become more customizable if a dataset with specific labels is created. Then, when a user prompts for a certain characteristic as input, only songs with corresponding tags would be fed into the training model, and the output result would follow the desire of the user.
 
##### Possible Labels to the MusicNet datasets
* Composer
* Musical period (eg. Baroque, Classical, Romantic, Contemporary)
* Genre/style (eg. dance, sonata, nocturne, jazz, blues, pop)
* Speed
* Difficulty (ranked based on standards of different exams, eg. Certificate of Merit, Associated Board of the Royal Schools of Music)
* Mood that it evokes
 
I looked at three papers that explore how music can evoke senses of emotion in audiences from different backgrounds.
#### "Ooh là là! Music evokes at least 13 emotions. Scientists have mapped them"
by Anwar, Yasmin (2020)
https://news.berkeley.edu/2020/01/06/music-evokes-13-emotions/
 
In the study, the Berkeley doctoral students found that the emotions evoked by music can be categorized into 13 feelings: "Amusement, joy, eroticism, beauty, relaxation, sadness, dreaminess, triumph, anxiety, scariness, annoyance, defiance, and feeling pumped up. "
 
In addition, the study found that while people from different regions experience similar emotions while listening to the same music, they classified these emotions differently. However, the Chinese and U.S. study participants differed in opinion on whether the emotions, for example, "fear", evokes a positive or negative feeling.
 
Finally, the study proves that the emotion evoked by the music is not influenced whether the person associates it with a certain movie, as similar research conducted using Chinese traditional music reflects similar results.
 
#### “What music makes us feel: At least 13 dimensions organize subjective experiences associated with music across different cultures”
by Cowen et al. (2020)
https://www.pnas.org/content/117/4/1924
 
In the study, researchers from UC Berkeley investigated how different people from various cultures reported on specific feelings and broad affective features in response to listening to music. The research is done with 1591 Americans and 1258 Chinese each listening to about 2168 music samples and differs from previous studies by analyzing a significantly larger number of emotions, as well as the impact that cultures have on music perceptions
 
The result is that 13 distinctive types of subjective experience “amusing, annoying, anxious/tense, beautiful, calm/relaxing/serene, dreamy, energizing/pump-up, erotic/desirous, indignant/defiant, joyful/cheerful, sad/depressing, scary/fearful, and triumphant/heroic” can be identified from listening to music. In the observation, specific feelings were more preserved between the 2 cultures than broad, which is in contrast to previous beliefs that they both correlate. In addition, separate emotion theories are also rejected as feelings are found to occupy continuous gradients.
https://www.ocf.berkeley.edu/~acowen/music.html# shows a visual of how the music is categorized into 13 emotions on an interactive map, as well the percentage of emotion reported with each sample of the music.
Due to the complexity involved in music, the researchers utilized semantic space and a logical approach that structures subjective experiences with 3 properties: conceptualization, dimensionality, and distribution. Conceptualization is the nature of the concepts that most precisely characterize our feelings. It is concerned with affective science, or scientific study of emotion and affects (feeling, mood, decision-making, etc.) as well as underlying physiology and neuroscience of emotions
* particular feelings or general effective features like valence from music
* answering this can also give insight into how the brain represents feelings, how infants can recognize feelings, and how universal across cultures subjective experiences can be
* dimensionality
    * range of feelings that people experience
    * how many distinct feelings
    * how much does culture impact feelings associated with music and which are consistent among cultural groups (this particular study focused on participants from China and the US)
- distribution
    - how are the feelings that music evokes distributed
    - are the feelings distinct or can they to be blended?
    - boundaries between specific feelings
 
#### "Music and emotion"
https://en.wikipedia.org/wiki/Music_and_emotion
 
The field of music and emotion is a branch of music psychology that studies the relationship between music and emotion in the human brain. The end target is to discover how music therapy can be efficiently applied to people from a variety of backgrounds.
 
The subject seeks how the influence of music changes with the age of the audience. How different aspects of music, such as tempo, mode, loudness, melody, and rhythm, can evoke different reactions. The Juslin & Västfjäll's BRECVEM model found that music can elicit emotion through seven ways: brain stem reflex, rhythmic entrainment, evaluative conditioning, emotional contagion, episodic memory, and musical expectancy.
 
Researchers are able to study the changes in emotion through self-reports or outsider's observation of listeners' physiological responses and expressive behavior both conveyed and elicited.
 
Finally, a better understanding of the relationship between music and relationships can help create more effective therapeutic tools using music. Music therapy already shows promising outputs in treating patients with autism, the hope is that in the future, it would help more people, such as those with other mental illnesses, or others trying to break alcohol or drug addiction.
 
With a better understanding of how music can be used as therapeutic tools and classification of what type of music is the most effective, the hope is that we can then utilize computer-generated music to create a variety of playlists with specific attributes targeting a group of people with a specific therapeutic need.
 
 


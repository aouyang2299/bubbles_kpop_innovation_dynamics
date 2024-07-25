# bubbles_kpop_innovation_dynamics

This final project for 88-275 (Bubbles: Data Science for Human Minds) takes on a personal interest in K-pop and combines it with an established methodology mentioned in class. The example shows the analysis of poetry by tracking the similarity scores of a poem released in time (x) and a poem released in time (x-1) and creating a time series visualization to show the changes over time.

<img width="546" alt="Screenshot 2024-07-25 at 12 21 44 AM" src="https://github.com/user-attachments/assets/42d0225a-5679-4926-90c6-5f4c8159fed3">

Additionally, producers and composers in the music industry use information cascades and market signals to guide their creative decisions, influencing artists to adapt their musical styles and stay relevant in an ever-changing industry, providing another layer of complexity to this.

With this project, I aim to understand the innovation dynamics and patterns of fame framework that shows the evolution of the group's musical sound and how that impacts people: in the end, are people interested in innovation or similarity? 

The working hypothesis is that groups get more and more similar from the start to a certain point where their sound diverges from the original one and changes.
My project focuses on GFRIEND, a group I am familiar with in terms of their music and history.

This project highlights
- using the Spotify API to gather all of the necessary audio data 
- using ChatGPT as a tool to classify lyrical data in an unbiased way
- transforming a class example into a technical project that highlights data wrangling (feature vectors, data normalization, similarity scores) and data visualization

Sample Visualizations
<img width="546" src="https://github.com/user-attachments/assets/5cd0e1ce-5e56-49ba-8bcc-d755227bc2f7">

<img width="546" src="https://github.com/user-attachments/assets/7d4e4b27-ab75-46bf-a7f6-6874e2e8b9a8">

<img width="546" src="https://github.com/user-attachments/assets/5336a041-f9df-45c0-a652-73b4ef9442eb">

Key Results
- The overall data was very noisy and even after seeing only key data, there was much more sound deviance than expected (especially at the start of music journey)
- The general trends of sound shifts can still be identified and explained (greatest change in sound in 6th mini album, changes from company acquisition)
- Lyrical and audio data provide different perspectives on the music
- Linear regressions shows a not significant relationship between popularity and similarity to past (p=0.0876), people's interests in music may not only lie within similarity or innovation

Final Comments
- A group's sound evolves through time, and as shown in the graphs, that evolution is not very consistent with the human perception of music
- GFRIEND has been through a lot more musical variation than what is commonly and publicly perceived by Reddit and humans in general
- We cannot say for certain how people react to similarity or innovation from this data
- Within the larger scheme of things, this project may prove the point that there are too many outside factors to consider when using this type of methodology to examine the medium of music
- These results and interpretations may also potentially downplay the importance and impact of information cascades, as insider info is key in the music industry

- Future work can be done with more extensive review of music from multiple social media sites for general consensus and with other groups as well, which will be considered


GENIE: Media Recommendation System

**Genesis of the Idea**
   In the era where the pursuit of goals is paramount, many are battling stress and occasional 
   despondency. Decisions sometimes made in haste are regretted later. Here's where Moodify 
   steps in, a beacon for those seeking solace through tailored movie and song recommendations.

**Key Features**
   GENIE isn't just another recommendation engine; it's a blend of intuitive facial 
   recognition combined with mood-tailored media suggestions:
1. Detects user's emotional state spanning 7 categories: Angry, Sad, Fear, Happy, Disgust, 
   Surprise, and Neutral.
2. Post emotion recognition, users can choose their preferred mode of relaxation: movies or 
   songs.
3. Users are then presented with a handpicked list of movies or songs, mirroring their current 
   emotions, each accompanied by its poster or album art.
4. A single click navigates movie buffs to IMDB while music aficionados are transported to 
   Spotify.

**Behind the Scenes**
  GENIE is a symphony of Python and its diverse libraries. Our emotion detection algorithm 
  rides on the power of the MobileNet model via transfer learning. We honed our model using the 
  FER-2013 dataset, abundant with 35,000 images. The user interface is a simple yet effective 
  meld of HTML and CSS, and Flask brings it all together, allowing seamless web integration. To 
  further enhance the user experience, we curated mood-based media lists for bespoke 
  recommendations.

**Obstacles we faced**
1. Curating emotion-specific movie and song databases was a true needle-in-a-haystack challenge.
2. Designing templates for each emotion-centric movie and song recommendation tested our 
   patience.
3. Serving the right set of recommendations dynamically, based on user emotions, was a maze we 
   navigated using dynamic linking.

**Points of Pride**
1. Realizing a tool that resonates with contemporary challenges.
2. Our collaboration was distant in miles but close in spirit and purpose.
3. Tackling each obstacle head-on and innovating within tight timelines.
4. Broadening our horizons in technologies like Python, Flask, and a suite of other tools.
   
**Lessons and Growth**
   With GENIE, we delved deep into:
1. The nuances of transfer learning, a cornerstone for our facial recognition system.
2. Crafting elegant web pages using HTML and CSS.
   The art and science of deploying models via Flask.
   
**Envisioning GENIE's Horizon**
   We're not stopping here:
1. We aim to fine-tune our model for even sharper emotion detection.
2. A planned addition is an AI conversationalist: A chatbot that not only listens but suggests 
   therapeutic content, further accentuated by mood-reflective movie or song choices.




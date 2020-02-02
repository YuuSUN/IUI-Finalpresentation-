# IUI_Final_Presentation
  * [Overallintroduction](#Overallintroduction)
  * [Motivation](#Motivation)
  * [标题3](#标题3)
        * [标题3.1](#标题3.1)
        * [标题3.2](#标题3.2)
  * [标题4](#标题4)
## Overall introduction
German Helper is a voice assistant that is supposed to teach you the German language in a “smart” way. The first idea that makes it “smart”, is that it is based on Voice User Interface, which is a human computer interaction mode centered on human intention and conversation. So you can learn German in a most natural way. The second would be emotional intelligence, which gives you relevant feedback that provides a long term learn incentive. The assistant will become your “personal” assistant, by gradually learning your preferences. 
## Motivation 
- Why VUI  
Dialog based interaction makes the learn process more natural in compare to GUI 
- Why is it used to learn   
  - Ubiquitous Learning  
  German helper provides learners with information and interaction anytime and anywhere. There are two advantages. Firstly, in the era of lifelong learning you do not need a motivation to open it. On the contrary, you will open google map only when you have a motivation of finding the route. Secondly, you can take good use of small fragment of time to perform short productive activities. The main scenarios for voice use in the US are home (43%), car (30%), and road (19%)
## What did we do
1. we have designed a basic concept of features
2. we have designed the dialog model 
3. Then we evaluated the technical feasibility in Alexa
4. after that we implemented the features 
5. then concepts for emotional intelligence were designed
6. see 4.
7. then concepts for context awareness were designed
8. see 4.
## Basic Functions
1. Active learning
  - Asking for a word if you don’t know it.
  - Listening to radio/podcasts
2. Test learning effect
  - Tests that aim to push your knowledge
  - Test skill level (which is stored in user profile)
3. Emotional recognition
  - Short term impact: 
    - Positive emotion: Congratulate the user
    - Negative emotion: encourage the user
4. Customize study plan
  - Preferred time to learn
## Core Techs 
## Exercise task  ( complete concept for emotional recognition )
Recognize if the person likes the thing that is currently presented by the assistant. Store that in the user profile.
- Long term impact: Change the recommendations, actions and difficulty for tests based on emotion. 
  - Positive emotion: keep your current learning style
  - Negative emotion: change learning method. Also try to change the learning method every now and then and see what happens
- Short term impact: Change your responses based on the emotion of the user.
## Special cases 
- User Profile 
  - Stores the current and past estimated skill levels based on test results.
  - Stores average emotions 
  - Based on the trajectory of the skill levels and average emotions, the learning method will be changed.
    - Skill goes up: increase difficulty of tests
    - Skill goes down: decrease difficulty of tests
- Customize study plan
  - set minimum time that you should learn per session
  - set interval of learning sessions (e.g. daily, on Monday and Friday, weekly...)
## Vision 
Environmental sensors and devices
- Attention detection (via camera)
- Buzzer for alarm (according to study plan, or if you don’t pay attention)
- Preferred learning location detection
- Reward mystery cookie box. (Destroys cookie in front of you if you don’t deserve it.）
## Reference
[1] 语音交互的基本概念和设计实践  
http://www.woshipm.com/pd/1039577.html  
[2] 网易用研：超全面的语音交互知识科普  
https://www.uisdc.com/vui-knowledge-science  
[3] Ubiquitous Learning  
https://link.springer.com/referenceworkentry/10.1007%2F978-1-4419-1428-6_224

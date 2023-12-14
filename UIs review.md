# top
toc:
- [top](#top)
- [Listed Topics](#listed-topics)
  - [Design Principles](#design-principles)
  - [Usability Components/aspects](#usability-componentsaspects)
  - [Human-Centred Design Methodology](#human-centred-design-methodology)
  - [Double Diamond of Design](#double-diamond-of-design)
  - [Data Collection Methods](#data-collection-methods)
  - [Personas](#personas)
  - [Prototyping](#prototyping)
  - [Evaluation](#evaluation)
    - [Usability Testing](#usability-testing)
    - [SUS](#sus)
    - [Inspection](#inspection)
      - [Heuristic Evaluations](#heuristic-evaluations)
      - [Walkthroughs](#walkthroughs)
      - [Web Analytics and A/B Testing](#web-analytics-and-ab-testing)
      - [Predictive Models](#predictive-models)
  - [Principles of Visual Design](#principles-of-visual-design)
    - [Interface Metaphors](#interface-metaphors)
    - [Graphical Devices for Grouping](#graphical-devices-for-grouping)
  - [Interaction Design Framework](#interaction-design-framework)
    - [Models](#models)
    - [Framworks](#framworks)
  - [Aspects of Interaction](#aspects-of-interaction)
- [Rest of Course](#rest-of-course)
  - [Affordances](#affordances)
  - [Accessibility](#accessibility)
  - [Interaction Types](#interaction-types)
  - [Data Privacy](#data-privacy)
  - [Society](#society)
    - [Social Proof](#social-proof)
    - [Biases](#biases)
  - [Emotional Design](#emotional-design)
  - [random small shit](#random-small-shit)
    - [Front-End Dev vs UX Designer](#front-end-dev-vs-ux-designer)
    - [Recognition vs Recall](#recognition-vs-recall)
    - [conceptual design vs physical/concrete design](#conceptual-design-vs-physicalconcrete-design)
    - [hierarchy of user needs](#hierarchy-of-user-needs)
    - [types of interfaces](#types-of-interfaces)

# Listed Topics
Prof gave the following topics as being the most important topics discussed in the course:
1. Design Principles
2. Usability components/aspects
3. human-centred design methodology
4. double diamond of design process model
5. data collection methods (contextual inquiry,...)
6. personas
7. prototyping
8. evaluation (methods, tools, techniques,...)
9. principles of visual design
10. interaction design framework (conceptual models of user and designer, system image)
11. cognitive, social, and emotional aspects of interaction

[return to top](#top)
## Design Principles
Dos and Don'ts

- visibility
- feedback
- constraints
- consistency
- affordance

Visibility:
- show the user what they want to see
- key functions visible
- non-applicable functions invisible

Feedback:
- know whether interaction with system was successful
- what action has been done and what this has accomplished
- immmediate and synched to action
- ex
  - vibration
  - audio cue
  - loading screen
  - read receipt in messaging apps

Consistency:
- have similar operations and similar elements for achieving similar tasks
- support learning
- good for multiplatform applications

Constraint:
- limit what's possible for the user
- simplify things to guide them to the next appropriate action
- reduces chances of errors from user sellecting wrong options

Affordance:
- make it easy for people to know how to use your thing

[return to top](#top)
## Usability Components/aspects

There are different goals to be achieved for something to be usable:
- effictiveness
- efficiency
- safety
- utility
- learnability
- memorability

Something needs to effectively do what it sets out to help with or accomplish in order to be usable.
Can we get the outcome we want.

It needs to be efficient with time and resoures consumed.

If the system is unreasonably unsafe then the cost of use is too great compared to using a different safer system.

Can we get to the outcome we want in the way we want.
Does this have all the functions we want it to have.

How easily can a user figure out how to use the system.
Can a user use their own strategies or are they meant to follow a specific way of learning.
Is there documentation or other learning resources in the form of tutorials or videos.
Is the user just meant to explore until they understand what is happening.
In general, the more complex the system the harder it is to learn.

Can users remember how to use the system once they've already learned how.
Are all the items in their right places consistently.
Are there good visual cues and ways to navigate the system.
Make names descriptive.

---

Useful, useable, and used.

Some stupid shitty distinction that we made in class.

Something is useful if it can serve a use.

Something is useable if it can be used.

But something can be useful and useable but not be used.

A good design is one that is used.

[return to top](#top)
## Human-Centred Design Methodology
Focus on people, on users and their experience.

User Experience:
- all aspects of the end user's experience and what affects them
- is the interface functional
- how does the user interface with it
- how does the user feel
  - satisfaction
  - frustration
- appearances
  - vibes
    - professional
    - safe
  - clean vs cluttered

This is a general approach rather than a process.

Mainly about the double diamond of design.

[return to top](#top)
## Double Diamond of Design

Double diamond refers to the shape of the scope of our project.

We start at one point,
expand out,
narrow down to another point,
expand out,
then narrow down to one last point.

1. discover
2. define
3. develop
4. deliver

we discover what the problem is

define what areas we need to focus on

develop potential solutions

deliver the best one we can.

This process let's us iterate as well since we can go between 1&2, 3&4, or even between both diamonds of 1&2 and 3&4.

   - start with the problem
   - discover - find insight into the problem
   - define - find an area to focus on
   - converge onto a point
   - develop - expand out and find solutions
   - deliver - narrow down to solutions that work

[return to top](#top)
## Data Collection Methods
need to collect data to understand users
 - where:
   - users
     - know what they're expecting or what they're gonna do
     - gain access to the user's mental model instead of just our own mental model
   - other products
   - field research
   - documentation, manuals, logs, ... to know more about the steps involved in an activity...
 - should be iterative
   - do this more than once
   - do this regularly
   - continue to do this after release
 - use different techniques
   - surveys, questionnaires
   - telemetry
   - observe users in action
   - focus groups
   - probes
     - designed to prompt and elicit information from peopel about their lives and local culture
     - diary maintained by a user over several day sor weeks
       - diary study
       - media diary
       - photo
       - scrapbooks
       - google docs
     - similar to journaling in order to better understand yourself
       - ask for the users' general experiences with how they use the program and other related things
     - tell the users how to do the probe in the probe briefing session
       - how to take screenshot
       - how to describe shit
     - you can have a debriefing session
       - see how they feel about the probing process
         - improve for later
       - insights on the program
         - they've been using it for a while so they've become a skilled user (hopefully)
   - contextual inquiry
     - used often in other fields
     - interviewer records what user does and why user does what they do...
     - one-on-one interview - contextual interview
       - at place of work, no lab environment
       - just blending in and observing in the background
     - the focus is on the matters of daily life
     - uses a model of master (user) / apprentice (interviewer)
     - the interviewer is immersed in the world of the user
     - principles (4) :
        1. context principle
            - going to the user wherever they are
            - see what they do as they do it
        2. partership
            - user and interviewer explore the user's life together, on an equal footing
            - no one has the upper hand
        3. interpretation
            - make sure the interpretations from the observations are sound
            - make sure the information is correct
            - run through the notes with the user
        4. focus
            - make sure to just grab what you need and not unnecessary shit
     - think aloud protocol - use in conjunction with the above
       - users talk as they "do"
         - have users think out loud
       - they think loudly so that the interviewer would be able to record their trail of thoughts
       - "please think aloud. verbalize your thought process. What are you looking for? What are you doing? What are you trying to do? What's the goal? What are you cooking?"
       - not very natural for most people so need to prompt
       - this is just gameplay commentary and vod review
         - stabby videos
   - brainstorming
     - a generic technique used to generate, refine, and develop ideas
     - participants are the users
       - invite the users to something like a focus group
       - have them discuss issues and features
     - key factors:
       - know the user by the end
       - no ideas are criticized or discarded
         - may be useful later on
       - wide range of participants
         - levels of experience
         - levels of expertise
         - stupid motherfuckers
         - smart motherfuckers

Remember to try to stay within the scope of what we're looking for.

[return to top](#top)
## Personas

We pieces of data that we can correlate to one another.

With that we can create a user profile.

ex:
- bus commuter
  - reports ~1 hr commute times
  - reports unreliable transport time
- car commuter
  - reports ~30 min commute times
  - reports reliable transport time

Then we bring it to life by creating a character based off of it that we call a persona.

This way we have some fictional person that can represent a ton of our users.

making too many is a waste of time if your scope is too small or if it would divide the userbase too finely.

We put these personas into scenarios to see what a prospective user would do/feel in a situation.

There are also use cases where we show commonly performed actions.

[return to top](#top)
## Prototyping

prototyping
 - users don't have a clear idea what they want
 - you can't perfectly communicate what you are going to make
 - prototypes are an easy way for us to communicate to users
   - give them something they can use and understand
 - txtbk:
   - one manifestation of a design that allows stakeholders to interact with it and to explore its suitability
 - let's us experiment with what the final product or parts of the final product might look like
 - typically only represents some specific aspect
   - shape
   - look and feel
   - 1 function
   - structure
 - low-fidelity - less details, less complicated
   - simple
   - cheap
   - fast
   - use crude materials like pencil, paper, and cardboard
   - easily dismissable
   - not so robust
   - not great for testing towards the end
   - good for beginning of design process
 - high-fidelity - high detail, more complicated
   - complex
   - expensive
   - slow
   - interactive
   - similar to functional product
   - very robust
   - good for nearing the end of the design process
 - tested functionality need not be fully implemented
   - implementation may be faked
   - wizard of oz
     - get someone else (the wizard) to do it
     - humans are fallible and inconsistent
       - unlike the system we're making

prototypes are different from minimal viable product as an mvp can be put to market as a finished product.

Focus on a specific idea with prototypes.

Storyboarding:
 - evolved version of a user scenario
 - depict the context in which the user experiences a problem or pain point
   - see how the system can help the user in that context

The slides have a lot of examples for prototypes.

Remember to try and prototype the interaction.

Moodboards:
 - help with interactive design
 - decide what will make sense to include for the visual feel or look and feel

plus/minus scenarios
 - attempt to caputre the most positive and most negative consequences of a particular proposed design solution
 - reflections on imagined benefits, consequences, and ramifications
 - example: at the bank we use a faster less precise algo to send information
   - on bigger transactions that we have the time to process then the lack of precision isn't a factor and we don't want to lose their information even for a second even though we can correct later
   - on smaller transactions we just want speed and are able to correct later

The fidelity level we refer to when we talk about lo-fi and hi-fi prototypes is moreso refering to the visual, functional, and content fidelity rather than other aspects of the quality.

There are no true clear line dividing the different types of prototypes.

There are wireframes, mockups, interactive prototypes, simple html/css representations, and other types of prototypes that fall under the category of hi-fi prototypes but still run the gambit when it comes to different levels of fidelity.

Wireframes are a visual mockup that outlines the basic structure of your website, app, or landing page.
SHow of the structure and content controls.
Basic shapes and elements are used to block out where each piece of content and UI element will go.

It's all about visuals and layout. We're not necessarily concerned with the function or content.
High visual fidelity.
We're still concerned with the type of details in terms of content and structure but less so with the real content itself.

A wireframe mockup of a videosharing website will show where the main videoplayer goes, where the playlist goes, and where ads go.
We may not decide the colours or fonts.

Mockups are static pages that show off the visuals and content.
What a screenshot of the final product would look like.
Low functionality (multiple pages but they don't link or anything) fidelity but high visual and content fidelity (as close as we can to final product at that point in time).

[return to top](#top)
## Evaluation

We evaluate our designs all the time throughout the process of designing.

Formative evaluation:
- done during design phase
- often only checks one or a few parts of a system
- verify an idea works before throwing it in with the rest of the design

summative:
- done after finished product is created
- tests the whole system
- make sure everything works together in the end

[return to top](#top)
### Usability Testing

A session where a researcher called the facilitator or moderator asks a participant to perform tasks, usually using one or more specific user interfaces. While the participant completes each task, the researcher observes the participant's behavior and listens for feedback.

Testing needs to be 1 on 1.

We only need 5 participants

Surveys are like interviews,
one on one question sequences.

Questions are premade and static whereas in an interview we can change it up a lot

[return to top](#top)
### SUS

System usability scale - provides a reliable tool for measuring usability quickly
 - quick and dirty method
 - 10 item questionnaire with 5 response options from strongly agree to strongly disagree
 - limitations:
   - many questions might have to ask the same thing in order to get useful/specific information
   - questions are very vague
   - questions are often framed in positives and negatives
     - these are effectively yes or no questions
   - prone to bias
     - people might want to just easily agree or disagree
 - we can get a good mean/average score at the end though and that can be pretty good to quantifiably say we did a good job

[return to top](#top)
### Inspection
Evaluation without direct access to users
- suppose we cannot access the users
  - they are difficult to find
  - they are far away
  - they are spread out
  - we don't have the resources
    - time
    - money
  - the users are otherwise not available
- but we still want to do some testing
- inspection is how we do studies/tests w/o users
- 2 main subtypes
  - heurisitc evaluations
  - walkthroughs

[return to top](#top)
#### Heuristic Evaluations

Heurisitc Evaluations:
- evauluate based on some heuristics based in the principles and rules of design
- heuristics
  - rules of thumbs
  - very general
- see if the design stands up to what we know about design
- not as effective as evaluation with real users
- prone to bias
- Jacok Bielsen's 10 general principles for interaction design
  - visilibity of the system's status
    - what is the current sttae of the system
    - what is going on?
    - can we tell that we're done what we're trying to do
    - do we know what the next required step is?
  - match between system and the real world
    - use of perfect metaphors
    - take advantage of users' experience with real life things
    - does the design do the above
  - user control and freedom
    - based in usability and allat
  - consistency and standards
    - using guidelines
    - consistency with branding
  - error prevention
    - where could things go wrong and what can I do about it?
    - Am I doing anything about it?
    - have an undo/cancel
  - recognition rather than recall
    - providing the user with the means to recognize what they want to do as opposed to completely recall what they want to do
    - don't force them to memorize a process
    - intuitive process
    - they can recognize what they want to do as opposed to memorize what they want to do
    - give them a search bar so that they don't need to dig around in menus and subcategories
      - the suggestions would be really good
    - example used: IDE
      - we don't remember the names of the functions, we type out most of it and then we can just autocomplete it
    - examples
      - autofill and suggestions
      - filters and categories
      - good icons and labels
      - feedback and confirmation to prompt users' memory
      - defaults and presets so users don't have to tweak settings a ton
  - flexibility and efficiency of use
    - connected to the usability aspects of efficiency and learnability
    - are there different ways for different users of different levels of knowledge/expertise to use the system
    - prompts and confirmations for newer users that can be disabled by experienced users
    - flexible enough that the inexperienced can get things done and learn
    - efficient enough that an experienced user can go very fast
  - aesthetics and minimalistic design
    - functionality comes first
      - safety security and reliability
        - then usability
          - then finally aesthetics
          - as long as we don't compromise any of the previous
    - it's still important but we don't talk about it rn
  - help users recognize, diagnose, and recover from errors
  - help and documentation
    - clues aren't enough all of the time
    - more information is often required

[return to top](#top)
#### Walkthroughs
- the designers and ux researchers walk through the action sequences of each task from a sample task list
  - will the user know what to do to achieve the task?
  - will the user notice that an action is available?
  - try to find what a normal user might run into and see as a problem
  - act as the user working with the product
- record and document results
- best to ask for other entites (designers, researches, firms, etc.)
  - tester needs to have the background knowledge of the prospective user

[return to top](#top)
#### Web Analytics and A/B Testing

Web analytics and A/B testing
- users's loggings can be used to monitor user behavior
- user is not present
- ethical concerns
  - consent is not continued and cannot be easily withdrawn

web analytics:
- where users came from
- which pages they visited in what order
- other user stats
- not very reliable or specific but it's information

A/B testing:
- 2 versions of the system (A and B) to 2 groups of users belonging to the same demographic (user profile or persona)
- users are not present (online)
- in large scales
- randomly selected users

[return to top](#top)
#### Predictive Models

Predictive models
- formulas to estimate the measures of user performance
- not a method of testing
- not based on user satisfaction
- not based
  - cringe
- not very accurate but pretty okay predictive models

Fitt's law - predictive model:
- if you put things closer to each other then the user will take less time to use that function
  - aligning the next button for each step in an installation wizard
- it's an actual fucking formula lmfao
  - mod

---

There was a shit ton more bonus crap but I'm going to ignore that

[return to top](#top)
## Principles of Visual Design

1. scale
2. visual hierarchy
3. balance
4. contrast
5. gestalt

scale:
- relative size of pieces of a design
- signal
  - importance
  - rank

visual hierarchy:
- the principle of visual
hierarchy refers to
guiding the eye on the
page so that it attends
to design elements in
the order of their
importance
- some things are more important than others
- convey this visually somehow

balance:
- equally distribtued amount of visual signal on both sides of an imaginary axis
- split the design some way and see if it feels balanced

contrast:
- juxtaposition of visually dissimilar elemnts in order to convey the fact that these elements are different
- make things look different to show that they are different

gestalt:
- multiple principles in a trench coat
- principles regarding our tendency to view the whole design as opposed to just the individual components
- missing the trees for the forest
- ex
  - principle of similarity
  - principle of proximity
    - things that are visually closer together are perceived as a part of some group
  - principle of common region
    - same as the above
  - principle of continuity
  - principle of focal point
  - principle of closure
    - what the fuck did she mean by this
    - when we look at a complex arrangement of visual elements, we tend to look for a single, recognizable pattern.

[return to top](#top)
### Interface Metaphors

Use a user's existing understanding of something in order to help them to understand your interface/system

[return to top](#top)
### Graphical Devices for Grouping

Vertical alignment

negative space

grouping helps support visual searching tasks

[return to top](#top)
## Interaction Design Framework

Interaction design is concerned with designing interactive products to support the way people communicate and interact in their everyday and working lives.

Interaction design is interdisciplinary.
A good team has tons of disciplines involved in addition to designers and those who are able to realize the designs using tools.
Professionals that have knowledge regarding the products, its users, and its uses.

[return to top](#top)
### Models

model - a simplification of some aspect of the human computer interaction

conceptual model:
- an explanation, usually highly simpolified, of how something works

mental model:
- someone's understanding
- the conceptual model within someone's mind
- user's understanding of the system before them
  - user's mental model
- designer and/or coder's understanding of the system they've created
  - designer/coder's mental model

framework:
- set of interrelated concepts

system image:
- info available to the system's users
- affordances & cues
- perceivable action possibilities
- users' experience and knowledge
  - trained vs untrained
  - familiar w/ system or similar systems vs unfamiliar
- sum of everyone's understanding and what the system provides for understanding

Norman's conceptual framework:
- 3 components
  - designer's conceptual model
  - system image
  - users's conceptual model
- the three components influence one another and should be considered both together and separately

[return to top](#top)
### Framworks

Internal:
- mental models
  - internalized understanding of the system in their head
  - more generally; how someone understands the world around them (simplified for their use, emphasizing what's important to them)
  - knowledge and experiences inform the expectation which in turn informs
    - reaction
    - next course of action
  - users' mental models can be
    - erroneous
    - incomplete
    - error-filled
    - easily confused
  - we can work to improve the users' mental models through our design and other actions
    - better instructions
    - online help
      - tutorials
      - videos
      - 1to1 support
    - following design principles to make our communication more effectively
      - visibility
      - affordances
    - know the user better to target problems more closely
- gulfs of execution
  - gaps that exist between the user and the interface
  - lack of understanding about
    - how to interact with the system
    - what is the current state of the system
      - informs next actions
      - changes experience
  - gap b/w what the user knows and what the system offers
  - gap b/w what the user knows is happening with the system and what's really happening with the system
- information processing
  - assume the brain functions like any other info processing unit
  - encoding --> comparison --> response selection --> response execution

external:
- distributed cognition:
  - when a task is hard (cognitively) we can distribute the cognitive load to others
  - pilots don't fly alone
  - students don't work alone
- external cognition
  - annotation
    - anything we find out we can write down so we don't need to find it again
    - highlighting
  - cognitive tracing
    - externally manipulating items into different orders or structures
    - examples
      - todo pile vs done pile for grading papers
      - playing cards
      - sorted and unsorted laundry piles
    - organization presents useful answers to questions we may have when presented with the system
- embodied interaction
  - how people interact with the world using their bodies
    - not only their minds

[return to top](#top)
## Aspects of Interaction
A focus on the cognitive, social, and emotional.

Users have 3 different kinds of goals connected to different levels of thought processes and emotions
 - experience goals - attached to visceral processing
   - we want to feel a certain way
     - smart, cool, in control, safe, etc.
     - banking software should make people safe and secure
   - you want some kind of stimulation from the process
   - how overwhelmed should the user be
     - a video game will be more overwhelming and stimulating than professional lookig banking software
 - end goals - behavioral
   - user's motivation for performing the tasks
   - ex submitting assignment on school software, setting up direct deposit
 - life goals
   - deep drives and motivations
   - why is the user using this
     - what is the longer term goal
     - ex graduating and getting a job, starting a retirement plan

[return to top](#top)
# Rest of Course
not repeating anything from above down here.

[return to top](#top)
## Affordances

An affordance is a possible action in an interactive system.
Made perceivable by clues left by the designer(s).

false affordance:
- something that seems possible but actually isn't
- the user thinks something is possible when it is impossible

Placebo:
- something that seems to do something but does nothing in reality

hidden affordance:
- something that is possible but is unknown to the user
- the user is able to do an action but they don't know it

In order to make affordances known to the user the designer has to take into account all different kinds of information about the user:
- culture
  - reading direction
  - known symbols
- experience
- age (physical and mental condition)
- working conditions
- education
- possible disabilities

Without well designed affordances,
the user will most likely leave and stop using the system.

[return to top](#top)
## Accessibility

We have to account for those with disabilities.

There are different categories:
- permanent
  - long-term weelchair users
- temporary
  - crutch users with expected recovery
- situational
  - it's really loud and I can't hear you aaaaaaaaaaaaaaaaaaaaaaaaa

Curb-Cut Effect:
- some kind of concession or feature is made to help a specific group
  - disabled
  - minorities
- that concession or feature benefits more than just that specific group

[return to top](#top)
## Interaction Types
1. instructing
2. conversing
3. manipulating
4. exploring
5. responding

not mutually exclusive

1. instructing
   - users issue instructions to a system; tell it what to do
     - typing commands
     - selecting options
     - abstract button combos
       - `ctrl+c` to copy
       - emacs chords
     - speaking aloud
     - gestures
     - pressing physical buttons with dedicated functions
2. conversing
   - users have a dialog with a system
   - 2 way communication with user
   - interface via speach or typing
   - give command, get presented with options, repeat
   - e.g. siri, amazon, chatbot, google giving responses after you give query, installation wizard dialog
3. manipulating
   - users interact with objects in a virtual or physical space by manipulating them
     - closing/opening a container or door
     - holding an object
     - placing an object
   - users use familiar knowledge of how to interact with objects
   - stands in contrast to indirect interaction
     - line editors, latex, editing raw html, markdown editing
4. exploring
   - users move through a virtual environment or physical space
     - vr
     - 3d worlds
     - augmented reality
   - physical spaces that use sensor-based tech
     - smart rooms
     - ambient environments
   - use familiar knowledge of bodlily movements
     - walking around
     - turning around
     - enter in and out of rooms
   - give additional (unnatural) movements
     - fly over
     - zoom in/out (pinching)
     - climb inside of tiny things
5. Responding
   - system takes initiative and acts on its own
   - ex
     - notifications
     - automated heating system
     - alerting or communicating the user
     - fire alarm
     - smart home turning up the lights when it detects you're in the room or the night has come

Most systems have a combination of these interactions as opposed to only a single type of interaction

[return to top](#top)
## Data Privacy

Always get informed consent.

There's lots of laws to sort through and certs to get in order to do data collection.

[return to top](#top)
## Society

I stopped paying attention to lecture atp b/c it all went online

There are implicit and explicit social cues.

It's harder to convey the social cues that we are used to in-person in an online setting.

We seemingly resort to more explicit social cues like emojis, stickers, gifs, memes, songs, or tone indicators but there are also implicit social cues in the online realm.

[return to top](#top)
### Social Proof
- people reference the behavior of others to guide their own behavior
- other people are doing it so I can/should do it
- we can leverage this to increase our
  - credibility
  - adoption rate
  - acceptance
- risky as
  - interface can get too busy
  - people might just not like it and it won't take off
- can test usability testing and A/B testing
- mob mentality

[return to top](#top)
### Biases

acquiescence bias:
- people's tendency to agree to survey questions
- people want to be agreeable i guess
- avoid being disapproved of

negativity bias:
- tendency for people to pay more attention or importance to negative experiences, over neutral or positive ones

courtesy bias:
- tendency to underreport unhappiness with a system or service
- want to be polite

demand characteristics:
- tendency to figure out the purpose of something
- tendency to adopt certain behaviors they believe belong in an experimental setting

extreme responding:
- tendency to select the most extreme options or answers available

question order bias:
- participants can react differently based on the order of the questions ina questionnaire or survey
- questions contextualize other questions

social desirability bias:
- tendency to project the best self
- want to be desired
- overreport socially desirable behaviors and characteristics
- underreport socially desirable behaviors and characteristics

recency bias:
- people's tendency to lean towards recent events

overconfidence effect:
- tendency to overestimate your knowledge and abilities
- make sure design decisions are rooted in research and data

framing bias:
- drawing different conclusions from the same information
- different contexts given resulting in differen conclusions
- ask the same question 3 different times in different ways and get different answers

status quo bias:
- tendency to resist change
- maintaining current state

[return to top](#top)
## Emotional Design

appeals to people's emotions in order to improve the user experience

emotional interaction is concerned with what
makes people feel happy, sad, annoyed,
anxious, frustrated, motivated, delirious,
and so on, and then using this knowledge to
inform the design of different aspects of the
user experience.

emotional design is design that anticipates
and accommodates users’ needs and
responses

visceral design
- making products look, feel, and sound good

behavioral design
- use and equates to the traditional values of usability

reflective design
- considering the meaning and personal value of a product in a particular
culture

[return to top](#top)
## random small shit

[return to top](#top)
### Front-End Dev vs UX Designer

Implementing the design vs creating the design

~~We barely learn either in this course lmfao~~ The course is mainly focused on being the UX Designer

[return to top](#top)
### Recognition vs Recall

It's easier for us to recognize things instead of straight up recalling them so design in such.

Instead of making the user remmeber everything in a process,
we can prompt them with what might make sense for what they want to do.

Think of autocomplete in search engines or IDEs.

[return to top](#top)
### conceptual design vs physical/concrete design

Conceptual:
- nothing about creation or implementation
- describing and deciding on the concepts that we're including in the design

Physical/Concrete Design:
- all about implmentation
- making the chosen concepts actually work.

[return to top](#top)
### hierarchy of user needs

functional --> reliable --> usable --> pleasurable

[return to top](#top)
### types of interfaces

- Command
- Graphical
- Multimedia
- Virtual Reality
- Web
- Mobile
- Appliance
- Voice
- Pen
- Touch
- Gesture
- Haptic
- Multimodal
- Sharable
- Tangible
- Augmented reality
- Wearable
- Robots and drones
- Brain Computer Interaction
- Smart
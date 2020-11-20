# Learn Unreal
This repo aims to assist in the discoverability of Unreal Engine learning resources, covering everything from art to coding. Learning Unreal Engine alone as an indie or aspiring game developer can be extremely difficult and thus I hope this helps ease your journey somewhat.

TODO: Emphasize this is based on my journey and what I've run into. There are tons of resources out there so there's a lot missing here as well. However, focus here is to list out key channels and otherwise resources that would help the greatest on a category-by-category basis

TODO: Perhaps a section on how to find resources? Eg, search on Youtube then google (lotta text stuff out there)?

**Table of Contents**

- [FAQs](#faqs)
    - [Broad Questions](#broad-questions)
    - [Unreal Getting Started Questions](#unreal-getting-started-questions)
- [Unreal Learning Resources](#unreal-learning-resources)
    - [General](#general)
        - [Official Resources](#official-resources)
        - [Quality Youtube Channels w/ Broad Scope](#general-quality-youtube)
        - [Other](#general-other)
    - [Animation](#animation)
    - [Level Design](#level-design)
    - [Sound](#sound)
    - [VFX & Materials/Shaders](#vfx)
        - [Where to Start](#where-to-start-vfx)
- [Notable Game Dev Resources](#notable-game-dev-resources)
    - [Game Design](#game-design)
    - [General Audio and Visuals](#general-audio-and-visuals)
    - [Narrative Design](#narrative-design)
- [Communities](#communities)
    - [Unreal Specific Communities](#unreal-specific-communities)
    - [General Game Development Communities](#general-game-development-communities)
    - [Art Communities](#art-communities)
- [Other Unreal Resource Compilations](#other-unreal-resource-compilations)

## FAQs

### Broad Questions
1. <details>
    <summary>What does this repo actually contain?</summary>

    At the moment, nothing too much. The goal is to be pretty thorough, but for now, this will be a place to add in various resources I run into over time as well as larger suggestions I end up running into.

    **tl;dr:** I need to come back and rewrite this question in the future

  </details>

2. <details>
    <summary>I want to get into game development but have never done game dev before. Am I at the right place?</summary>

    I - Jawad - have two very very strong recommendations:
    
    1. Make the simplest game possible, all the way from scratch to full release. It's alright if you have a dream game, but there are so many complexities and aspects to a large game that you definitely want to start as small as possible then work your way up to larger projects. Start with a sample tutorial project, slap on a couple levels, add menus and such, and release it! You'll be very glad you did
    2. If you have 0 prior game dev experience, then I suggest starting out with Unity instead of Unreal. For Unity, there's an extremely diverse set of learning resources for Unity development- massive depth and breadth of community resources. In contrast, Unreal has a very high learning curve with a far more sparse set of learning resources (hence why this repo is being created). Thus, Unity is a great place to first cut your teeth in reducing the pain on creating games and then you can later switch to Unreal once you have at least some basic experience.
    
    &nbsp;
    
    *Disclaimer:*
    I started out with Unity years ago during my college freshman year before I had done any programming or the like at all (Software Engineer background) and thus I'm heavily biased towards starting out with Unity  first. Unreal has become both easier to use and easier to learn since then, but the learning curve is still pretty darn strict. However, perhaps this repo will grow to the point where it'll provide you with what you need to journey forth with Unreal immediately =)
  </details>


### Unreal Getting Started Questions
1. <details>
    <summary>TODO: I want to learn Unreal. Where should I start? <i>(Recommended before following questions!)</i></summary>

    TODO: Suggest grabbing a course off of Udemy to start off with (and when it's on sale). Also mention course I used
    
  </details>

2.  [I have no background in VFX, including particles and materials. How do I get started?](#where-to-start-vfx)

3. <details>
    <summary>TODO: How do I get started with animations in Unreal?</summary>

    TODO: Suggest wiiiidie variety of vids. Disclaimer that not fully confident here and SHOULD be an easy way, but only way known so far as a solo dev (without learning directly from others)

  </details>

## Unreal Learning Resources
This section covers resources specific to learning how to  use Unreal

### General

#### Official Resources
- <details>
  <summary><a href="https://www.unrealengine.com/en-US/onlinelearning-courses">Unreal Official Free "Courses"</a> - TODO, sparse in some ways but many hidden gems here for both beginners and advanced devs</summary>

    TODO (only have been looking at this recently), but makes it easy to find some nice gems for advanced concepts such as [Dynamic Audio](https://www.unrealengine.com/en-US/onlinelearning-courses/dynamic-audio). Worth quickly looking through what's available here

  </details>
- <details>
  <summary><a href="https://www.youtube.com/user/UnrealDevelopmentKit">Unreal Official Youtube</a> - Large but messy gem of resources</summary>

    The official Unreal Engine channel has a *ton* of resources. If you're trying to learn a new component of Unreal - or just trying to get perspective on how professionals work with Unreal - then drop on by to this channel. Recommended to check out playlists as well as use the search bar.
    
    As a quick disclaimer, these vids do have various quality and utility. Thus, YMMV (your mileage may vary)

  </details>
  
<h4 id="general-quality-youtube">
Quality Youtube Channels w/ Broad Scope
</h4>

- <details>
  <summary><a href="https://www.youtube.com/c/CodeLikeMe/videos">CodeLikeMe</a> - Massive variety of tutorials, useful as a starting base for new concepts such as IK</summary>

    This is a begrudgingly given recommendation, as the channel's quality of videos isn't the greatest- often they're 30-40+ minutes long involving the dev figuring things out as he goes. However, this channel is a *massive* treasure trove diving into all sorts of concepts. In addition, once you're aware ahead of time that the dev doesn't always have the "best" (most efficient) approaches as well as that the vids often are so long due to following the dev's natural development process, then this channel becomes extremely valuable and understandable for why you'd want to dive in.
    
    In short, don't go to this channel if you're looking for high quality tutorials with best practices but *definitely* check out this channel for various overviews on how to implement various extremely diverse concepts.
    
    Thank you for the channel creator for doing this for so many years and for creating so many vids so often, this channel is a really damn good treasure trove to get an idea on how to start out.

  </details>
  
- <details>
  <summary><a href="https://www.youtube.com/c/NitrogenDev">Nitrogen</a> - TODO (wide variety of very high quality tutorials)</summary>

    TODO

  </details>

<h4 id="general-other">
Other
</h4>

- <details>
  <summary><a href="https://www.udemy.com/">Udemy</a> - Various paid courses and a highly recommended starting point for beginners</summary>

    Udemy is an extremely useful resource for beginners, with courses ranging on how to create your first games to [Tom Looman's Multiplayer Games with C++ course](https://www.udemy.com/course/unrealengine-cpp/). 
    
    **Key note regarding price:** Unless you're extremely impatient (or want to support the creators more with expensive purchases), I highly recommend *never* buying a course at full price. Udemy has a sale practically every month for courses and - especially towards the end of the year, including Black Friday until New Year's - every course across the site even drops down to around $5-11. Highly recommend to wait and check frequently until a course is around $5-20 before buying.

  </details>

### Animation
TODO: Add various links from that one reddit post regarding journey

### Level Design
TODO

### Sound
- <details>
  <summary><a href="https://www.youtube.com/channel/UC_fUOKtkDh4sXao49dn0bNQ">Valkyrie Sound</a> - Sound-related YT tutorials</summary>

    This YouTube channel provides a wide variety of Unreal-specific tutorials on creating sound effects, ranging from what specific sound cue nodes do to how to bullet flybys to adaptive audio. If you're interested in how to create various SFX in Unreal, then this is the channel for you.

  </details>


<h3 id="vfx">
VFX & Materials/Shaders
</h3>

- <details>
  <summary><a href="https://www.youtube.com/c/UnrealCG">UnrealCG</a> - Popular channel with a wide variety of quality visual effect tutorials (TODO)</summary>

    TODO

  </details>
- <details>
  <summary><a href="https://www.youtube.com/user/asif786ali1">CGHow</a> - Extremely diverse set of VFX (particle system) tutorials</summary>

    This channel contains a whoooole lot of VFX tutorials, with all recent ones using Niagara. Note that tutorials qualities can differ quite a bit from video to video but the effects are consistently amazing

  </details>
- <details>
  <summary><a href="https://www.youtube.com/channel/UCAaWnOJ4iFSQluBVNS2d-Ew">Dean Ashford</a> - Wide variety of visaul effect tutorials, ranging from solid particle systems to special shaders (TODO after more usage)</summary>

    TODO

  </details>
- <details>
  <summary><a href="https://www.youtube.com/user/bcloward/playlists">Ben Cloward</a> - Collections of detailed visual effect tutorials (TODO)</summary>

    TODO as haven't personally used any of these tutorials and also includes a bit more than just visual effects
    
    Notable collections:
    
    1. [UE4 Material Editor - Shader Creation](https://www.youtube.com/watch?v=uQG0SWv5lbw&list=PL78XDi0TS4lFlOVKsNC6LR4sCQhetKJqs).  This playlist includes 46 videos but note that's due to this large playlist also including the videos from the following playlists as well
    2. [Rain Materials in Unreal Engine 4](https://www.youtube.com/watch?v=fYGOZYST-oQ&list=PL78XDi0TS4lHpIHseomZCPRm_NkyUMkPs)
    3. [Procedural Noise Materials in Unreal Engine 4](https://www.youtube.com/watch?v=QIlxWkfZK-8&list=PL78XDi0TS4lE7kpna273_SUl2e0PXYZRY)
    4. [UE4 Water Material Tutorial](https://www.youtube.com/watch?v=r68DnTMeFFQ&list=PL78XDi0TS4lGXKflD2Z5aY2sLuIln6-sD)
    5. [UE4 Foliage and Vegetation](https://www.youtube.com/watch?v=5FxaVC5w97w&list=PL78XDi0TS4lEbQu-02qku02hR2QUKfDPR)
    6. [UE4 Ray Tracing](https://www.youtube.com/watch?v=WH1bwspb_Js&list=PL78XDi0TS4lFECjPpC3ClUIqNApHmdrPt)

  </details>

<h4 id="where-to-start-vfx">
Where to Start
</h4>

TODO: Answer, what's the difference between Cascade and Niagara?

- <details>
  <summary>Useful Starting Guides</summary>

  Listed in personal recommendation order to go through:
  1. [Excellent Single Vid Material Intro Vid w/ Realtime 3D NowYoshi](https://youtu.be/-B9k7WwHexQ). Sooo good, excellent efficient introduction for beginners which teaches a wide variety of common techniques as well
  2. [Unreal's Official Intro to Materials Series](https://www.youtube.com/watch?v=lngF4VVNER4&list=PLZlv_N0_O1gbQjgY0nDwZNYe_N8IcYWS-&index=1). A bit old but not outraded and goes through all key aspects of materials rather thoroughly
  3. [Particle Systems Intro Vid w/ Realtime 3D NowYoshi](https://youtu.be/WAnAZcMHt9w). Another pretty solid succinct intro tutorial, this time on particle systems and several common techniques related to them. Note that this is with the older Cascade particle systems so may not be entirely relevant for you.
  4. [Unreal's Official Intro to Cascade Series](https://www.youtube.com/watch?v=OXK2Xbd7D9w&list=PLZlv_N0_O1gYDLyB3LVfjYIcbBe8NqR8t). Again this tutorial series is about the older Cascade tool for creating particles, but it should again give you a pretty good foundation before moving onto the more powerful Niagara. Feel free to quickly skim through these vids to see how valuable they'd be to you
  5. [Udemy Niagara VFX Course by Gabriel Aguiar](https://www.udemy.com/course/ue4-vfx-for-games-beginner-to-intermediate/). 
  6. TODO: More solid Niagara guides!
  
  Note that you can skip all Cascade related tutorials if you feel that understanding and modifying older particle systems is not relevant for you.
  
  </details>


## Notable Game Dev Resources
This section aims to provide a non-exhaustive list of very notable game dev resources to help you on your journey. Personal recommendation is to subscribe to these channels and frequently watch various game design Youtube videos that interest you in your casual free time.

### Game Design

- <details>
  <summary><a href="https://www.gdcvault.com/">GDC (YT)</a> - Collection of various professional talks given for Game Developers Conferences</summary>

    An extremely valuable resource to keep in your back pocket. Not much else to say, other than you should take an immediate peak at their catalog of YT videos to get an idea of what game changers you may be missing.
    
    As an aside, do note that the [GDC Vault](https://www.gdcvault.com/) itself exists as well, which is the official collection of recorded GDC talks. Not all recorded GDC talks are free and the Youtube channel doesn't contain all free recorded talks either.

  </details>
- <details>
  <summary><a href="https://www.youtube.com/user/McBacon1337">Game Maker's Toolkit</a> - Extremely popular general game design YT channel</summary>

    If you haven't seen GMTK yet, you really really should. Extremely valuable YouTube channel covering a very wide variety of game design topics.

  </details>
- <details>
  <summary><a href="https://www.youtube.com/c/Thefearalcarrot">Adam Millard - The Architect of Games</a> - Very popular general game design YT channel with his own spin and approach</summary>

    Similar to GMTK, Adam goes into a wide variety of game design topics using various games as examples. A large number of videos also try to boil down the lessons into a few key takeaways or even acronym to use in your game design journey

  </details>
- <details>
  <summary><a href="https://www.youtube.com/channel/UCmY2tPu6TZMqHHNPj2QPwUQ">Snoman Gaming</a> - TODO (Broad game design channel w/ focus on good game design  BUT what's their key differentiating factor?)</summary>

    TODO

  </details>

- <details>
  <summary><a href="https://www.youtube.com/user/Warbot40">Design Doc</a> - Specializes in graphic design as well as comparing and contrasting good + bad examples from various games for wide variety of game design topics</summary>

    This channel often touches on its unique topics that isn't covered in other popular channels, while often using both strong good and bad examples to hone in on the primary points at hand. In addition, this channel also covers graphic + UI design in the very popular [Good Design, Bad Design series](https://www.youtube.com/playlist?list=PL8K0_g1wdQeoxta9RyvTK-DnhU4jI2QJN).

  </details>

### General Audio and Visuals
- <details>
  <summary><a href="https://www.youtube.com/c/NewFramePlus">New Frame Plus</a> - TODO (Animation in games)</summary>

    TODO

  </details>
  
- <details>
  <summary><a href="https://www.youtube.com/channel/UC8P_raHQ4EoWTSH2GMESMQA">Game Score Fanfare</a> - TODO (Music w/ focus on games and relevant analyses)</summary>

    TODO

  </details>
  
- <details>
  <summary><a href="https://www.youtube.com/channel/UCi7l9chXMljpUft67vw78qw">Sideways</a> - TODO (Music, not a focus on games but - as a non-musician - this is really good and much easier to watch than straightforward music theory vids)</summary>

    TODO

  </details>
  

### Narrative Design
There are various compilations on writing for video game and fiction in general ([like this one](https://medium.com/@farrtom/the-book-to-read-if-you-want-to-get-into-video-game-writing-4ca9442ec713)), but this section lists resources that I've personally used and loved. Note that I don't have a storytelling background of any sort, so these may be overly geared towards beginnings

- <details>
  <summary><a href="https://www.amazon.com/Video-Game-Storytelling-Developer-Techniques/dp/0385345828">Video Game Storytelling: What Every Developer Needs to Know about Narrative Techniques (Book)</a> - TODO (Currently reading, goes into basics and key elements really well at least)</summary>

    TODO

  </details>

## Communities
TODO

### Unreal Specific Communities
TODO

### General Game Development Communities
TODO

### Art Communities
- <details>
  <summary><a href="https://www.artstation.com">ArtStation</a> - TODO (Need to use this place more myself too)</summary>

    TODO

  </details>
- <details>
  <summary><a href="https://realtimevfx.com/">Real Time VFX</a> - TODO (Great community of VFX artists but haven't delved in at all yet really)</summary>

    TODO

  </details>

## Other Unreal Resource Compilations
TODO: I haven't really used  any of these, so need to go over these -> understand why they're valuable and unique -> turn into spoiler/expandable format with more details

- [Tom Looman's Unreal Engine Resource Collection](https://www.tomlooman.com/unreal-engine-resources/)
- [BusinessOfApp's Big List of Unreal Engine Development Resources](https://www.businessofapps.com/news/big-list-unreal-engine-development-resources/)
- [cindustries/unreal-directory](https://github.com/cindustries/unreal-directory)
- [terrehbyte/awesome-ue4](https://github.com/terrehbyte/awesome-ue4)

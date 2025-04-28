# Development Commentary Template

## Project Outline

```markdown
- Provide a concise description of the project, including its core concept and purpose.  
- Outline the initial goals or objectives you aim to achieve.  
- Identify any anticipated challenges or potential issues that may arise during development.
```

```
- Sci-Fi first person shooter where you play as a humanoid slime creature.
- I've been influenced by my playing habits, and I wanted to move away from my usual genre which was 3D platformers.
- I wish to include multiplayer but that's new to me.
- I wish to publish this game professionally, working with professional pipelines (detail these later) (uploading builds to platforms, working with version control, etc.) 
```



## Research

### Methodology  

```markdown
- Identify relevant sources for the project, including articles, documentation, talks, and games.  
- Detail how these sources have informed your practical work and influenced your approach.
```
- Story Driven FPS
- I feel that both playing story driven games as well as reading articles about them will give me an understanding of how they are designed, as well as seeing how other people think about the game.

---

- How to deal with multiplayer in Unreal
- I feel like YouTube videos could be a quicker solution than looking at Documentation when it comes to adding Multiplayer. 

---
- Publishing for Steam. Working with the Steamworks API
- I need to make sure I am compliant with Valve's Terms and Conditions and Service Agreements as a publishing platform. So I need to be strict with how I follow the API guidelines.

### Game Sources  
```markdown
- Conduct research on games that are relevant to your project. Provide a brief description of each game and the insights it offers.  
- Analyse the game's approach, cross-referencing it with other sources such as articles or talks to support your analysis.  
- Explain how these insights apply to your project and influence your decision-making process.
```
#### Metroid Prime
- Metroid Prime is a Sci-Fi first person shooter developed by Retro Studios Metroid Prime (2002).
- *Metroid Prime* is considered one of the best video game experiences of all time and the top GameCube game according to IGN(The 25 Best GameCube Games of All Time - IGN, s.d.).
- The level design in Metroid Prime features large environments comprised of multiple interconnected rooms. (The World Design of Metroid Prime | Boss Keys - YouTube, s.d.)
- The level design is largely non-linear, there are a lot of paths the player can follow, some take them to other areas of the map, and some areas feature small challenges that the player can complete to get extra items.
- The gameplay of Metroid Prime consists of combat, puzzle solving and exploration. The combat is divided into both shooting enemies as well as moving to avoid their attacks. This makes the combat unique as it makes every encounter more engaging than other first person shooters that typically feature quite stationary combat based around hiding behind cover and shooting when you get the opportunity.


(this is what i'm saying, this is what i've got to prove what i'm saying)


```


```


#### Bioshock
- Bioshock is a story driven first person shooter developed by 2K Boston
- The gameplay of Bioshock is a mix of exploring the environment, solving small puzzles and learning about the game's world, and fast-paced first person gunplay, featuring combining several different guns, and also magic powers such as blasts of electricity or grabbing objects with telekenesis. The player is encouraged to experiment with different weapon/power combos to approach different scenarios.
- The level design is fairly open, with a mix of large, open areas to explore, more open areas where the player has to fight numerous enemies, and optional side areas that pose challenges the player must overcome, that then reward them with rewards such as extra ammo, or money to spend on upgrades.
- The progression of Bioshock involves travelling to different areas with a set objective the player must reach. Though how they reach that goal is up to them, as there is usually multiple ways the player can reach the destination, such as different routes to take, or different approaches to exploration that affect what enemies they may or may not encounter. 
- Each area usually has a new weapon that the player can unlock, making each area fresh as the player always has a new weapon to try out, and see what upgrades they can get for it.


### Academic Sources  
```
- Research academic papers, books, or articles that provide theoretical guidance for your project. Include a brief summary of each source.  
- Describe how the academic research applies to your project and shapes your design and development decisions.
```
- For an academic source, I chose to look at Flow and Immersion in First-Person shooters (Flow and immersion in first-person shooters | Proceedings of the 2008 Conference on Future Play: Research, Play, Share, s.d.).
- The article reports the results of a psychological study about how different aspects of Half-Life 2 affects player's gameplay experience.
- The paper reports that players were more engaged when playing through levels that were designed for combat-oriented flow.
- The paper also reports boredom and how different aspects of the level design can lead to players getting bored, such as linear level deisgn, weak opponents with little visual vareity, repeating textures and models, limited choices of weapons, or high amounts of rewards such as health, and ammo supplies.
- I chose to analyse this source as the level design is a large factor in my game, and I want to avoid having the player be constantly bored when playing my game. Which means there should be a focus on making the level design interesting to explore, and also balancing the game's challenge, such as enemy vareity and difficulty, and also the frequency of health pickups, checkpoints and weapon unlocks.

### Documentation Sources  
```
- Investigate relevant documentation, tutorials, or instructional videos that provide technical insights into your tasks. Summarise the content and its relevance to your project.  
- Explain how this technical knowledge supports your project work and guides your decision-making process.
```
- To learn how to create Multiplayer, I started by looking at unreal documentation.
- Looking at Documentation for Testing Multiplayer (Testing Multiplayer in Unreal Engine | Unreal Engine 5.5 Documentation | Epic Developer Community, s.d.) showed me the basics of how to create a basic multiplayer mode, including adding other players to the level, and splitting the screen so the second player has a view.
- I watched a few YouTube videos as well since I was having difficulty actually assigning input to the second player.
I looked at a video about the basics of multiplayer in unreal (How to set up local/split-screen Multiplayer in Unreal Engine 5!, 2023), as well as a seperate video on creating multiple players and then assigning different player input to both of them (UE5 Fighting Game Tutorial: Local Multiplayer Game With 2 Gamepads | TrueFGE & Unreal Engine 5, 2023).
- After watching these videos, I managed to figure out how to control both players.

## Implementation

<iframe src="https://blueprintue.com/render/krpxksl9/" height= 512px width=100% scrolling="no" allowfullscreen></iframe>
Figure 1. gdngdsngsdngiods gfs


### Process
- Provide a step-by-step breakdown of your development process, including key milestones and decisions made throughout the project.  
- Highlight any tools, frameworks, or techniques used, and explain how they contributed to the implementation.  
- Include screenshots, diagrams, or code snippets where relevant to showcase your progress.

### New Approaches  
- Detail any innovative or new approaches you explored during the project.  
- Explain why these approaches were chosen and how they differ from standard practices.  
- Evaluate the success of these approaches, including any challenges faced and lessons learned.

### Testing
``` - Document the user testing conducted, specifying the type of tests used (e.g., automated testing, guided user testing, blind testing).  
- Present feedback or issues identified during testing, using graphs, tables, or visual aids to summarise results.  
- Describe how these issues were addressed. If any issues were not resolved, provide a clear justification for leaving them unaddressed.
```


### Technical Difficulties
- Identify any technical difficulties encountered during the implementation phase.  
- Provide details on how these issues were diagnosed and resolved.  
- If any difficulties remain unresolved, explain the impact on the project and any mitigation strategies used to minimise their effect.  
- Reflect on what you would do differently in future projects to avoid similar issues.

## Outcomes

### Source Code/Project Files
- Provide a link to your complete source code or project files.  
- Ensure the link is publicly accessible or shared with the appropriate permissions.  
- Include a brief description of the files provided, highlighting key components or any instructions required to run the project.

### Build Link
- Share a link to a playable or executable build of your project.  
- Ensure the build is accessible across relevant platforms and is publicly accessible.  
- Include any necessary instructions for running the build, such as system requirements or installation steps.

### Video Demonstration
- Embed a video or provide a link to a recorded demonstration of your project in action.  
- The video should showcase key features, functionality, and any unique elements of your project.  
- Include a brief commentary or text overlay in the video to explain the different aspects of your project as they are shown.

## Reflection

### Research Effectiveness  
- Assess the usefulness of the research conducted during the project.  
- Highlight which sources (games, academic, documentation) had the most significant impact on your work and explain why.  
- Identify any research gaps or areas where additional information could have improved your project outcomes.

### Positive Analysis 
- Reflect on the successful aspects of the project.  
- Highlight specific elements that worked well, such as technical solutions, creative decisions, or user feedback.  
- Provide evidence to support your analysis, such as test results, screenshots, or user comments.

### Negative Analysis  
- Identify the areas of the project that did not go as planned or could have been improved.  
- Discuss challenges you faced, whether technical, creative, or time-related, and evaluate their impact on the final product.  
- Reflect on any mistakes or missteps and what you learned from them.

### Next Time
- Outline what you would do differently if you were to undertake a similar project again.  
- Suggest improvements to your workflow, research methods, or implementation process based on your reflections.  
- Consider any new tools, techniques, or approaches you would explore in future projects to achieve better results.

## Bibliography  
```markdown
- Compile a complete list of all sources referenced throughout your project. This may include articles, journals, videos, games, software, documentation, or any other materials.  
- Ensure all references are formatted according to the [university's citation method](https://mylibrary.uca.ac.uk/referencing).  
- Organise your references in alphabetical order. Alternatively, you may separate them by type (e.g., academic sources, games, videos), but consistency is key.
```

‘Metroid Prime’ (2002). Retro Studios.

The 25 Best GameCube Games of All Time - IGN (s.d.) At: https://www.ign.com/articles/the-best-gamecube-games-of-all-time (Accessed  10/02/2025).

The World Design of Metroid Prime | Boss Keys - YouTube (s.d.) At: https://www.youtube.com/watch?v=zyoGD6uwCmk (Accessed  10/02/2025).

Pinchbeck, D. (2008) 'Story and recall in first person shooters' In: International Journal of Computer Games Technology pp.1–7.

Flow and immersion in first-person shooters | Proceedings of the 2008 Conference on Future Play: Research, Play, Share (s.d.) At: https://dl.acm.org/doi/10.1145/1496984.1496998 (Accessed  10/03/2025).


## Declared Assets
- Provide a detailed list of any third-party assets used in the project.  
- This includes asset packs, music, sound effects, 3D models, textures, scripts, or code from external sources.  
- Declare any use of AI tools (e.g., ChatGPT, GitHub Copilot, Meshy) or pre-existing code. Specify the purpose of these assets/tools and how they were integrated into your work.  
- Ensure you clearly distinguish between your original work and any external contributions to maintain academic integrity.
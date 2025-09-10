# 🃇 🂡 Mesmorized-Card-Game 🂽 🃞
###### - Andy Ruzicka
## Project Overview:
For this project, I designed and deployed a single-page application (SPA) developed using the Claude genAI tool.
#### Purpose:
To see the development differences between doing code myself and comparing it to the process of just utilizing a genAI tool to do the construction process for me, from start to finish.

## Description / Functionality
A simple application that allows the user to play a Memory Card Puzzle Game. A user will choose their difficulty and then start a game, where they will be selecting cards and trying to find matches in order to win!
- Users can choose between different difficulty levels: Easy (4x4 Card Layout), Medium (6x6 Card Layout), Hard (8x8 Card Layout), and EXTREME (12x12 Card Layout)
- After a successfully won game, a user will have the option to enter a 6-character name to add to a leaderboard for each specific game difficulty level

### How To Play (Detailed Instructions)
- A user will begin by selecting the difficulty level they want to play with.
- The user will then begin the game by clicking on the "Click to Begin" button
- Once a game is started, the user will have all the cards on display for about 3 to 5 seconds, so the user can try to quickly memorize the placement of the different icons.
- After the initial 3 to 5 seconds are up. All the cards will then flip over, hiding all the icons from the user.
- The user will then have the timer begin, and they can start to select two different cards to see if they can match cards together
- (if the cards match, they will be greyed out and highlighted)
- (if the cards do not match, then the cards will flip back over and allow the user to choose another set of cards)
- After a user has successfully matched all the cards with one another, they have WON the game!
- A pop-up will display the user's time they achieved and allow them to enter a 6-character name to add to the leaderboard tied to the specific game difficulty the user was playing on.
- After the pop-up is closed out, it will bring the user back to the main menu screen, where they can repeat the entire process again if they choose to.

## ACCESS to the Game Application 🟩>> PLAY GAME HERE <<🟩
##### Github Repository:
- https://github.com/AndyRuz/Mesmorized-Card-Game.git
##### Github IO:
- https://andyruz.github.io/Mesmorized-Card-Game/

## Known Issues:
- Users are able to switch the difficulty setting while playing a game, which will allow users to enter leaderboard scores for different difficulties, without truly playing the game at that specified difficulty, which they initially selected at the starting Main Menu screen.

## Future Enhancements/Adjustments:
- Make it so when cards are successfully matched/paired, instead of the cards flipping back over to their backend card face and becoming greyed out and highlighted. I would prefer to make the cards stay front-facing. So the icons will still display, while keeping the same features of greying out the cards and having them highlighted.
- Make the "Difficulty" button not visible/clickable once a game has been started.
- Add music in the background, and sound effects
- Create a settings menu to control audio levels, allow customization of the card icons, and be able to change the amount of time given to a user at the beginning of the game before all the cards get flipped over.
- Possibly allow for more GUI/Interface color scheme customization

## Process & Reflection:
#### Development Process

I began this project by outlining my vision in a Google Doc, where I wrote both a broad overview and a detailed set of instructions for how I wanted the memory card game to look and function. This helped me think through the design, transitions between views, and how the SPA would maintain state.

With this plan in place, I copied the document into the Claude.ai genAI tool and asked it to generate the full code. The first version was already close to what I envisioned, with the layout, grid system, and card-flipping mechanics in place. From there, I worked iteratively, refining the code by adjusting my Google Doc instructions whenever issues came up. For example, the cards were initially too small, but after specifying clearer details about sizing and layout, the AI regenerated a version that worked as intended.

This cycle of refining instructions and prompting the AI became my main strategy. Each time I hit a snag, whether in layout, accessibility, or styling, the key was being more specific. Over time, the work shifted from fixing functionality to making small visual improvements like colors, spacing, and transitions.

Overall, the genAI tool made development much faster than coding from scratch. It let me skip the tedious setup of file structure and base logic, so I could focus on design and refinement. This workflow gave me a strong foundation quickly and allowed me to build upward in a more efficient and motivating way.

#### Personal Reflection

Working with the Claude.ai tool, I was amazed at how effectively the tool could generate large portions of functional code from my written instructions. It wasn’t just producing small snippets—it was able to deliver entire working versions of my application that included HTML, CSS, and JavaScript, all stitched together in a way that actually ran in the browser. This gave me a sense of confidence, because I realized I didn’t need to have every piece of syntax memorized in order to create something functional and interactive.

Another insight I gained was the importance of being clear and precise when communicating with the AI. At first, I underestimated how much my phrasing would matter, but I quickly realized that vague or incomplete instructions led to incomplete results. For example, when I simply asked for a “grid of cards,” the tool generated something, but it wasn’t the size or design I had in mind. When I rewrote my instructions to specify exact dimensions, spacing, and layout, the AI’s output was far better. This reinforced for me that using genAI effectively is less about giving short commands and more about treating it like a collaboration where I provide detailed requirements.

That being said, there are limitations. One limitation is that the AI doesn’t always anticipate potential user issues the way a human developer might. For instance, it created a system where players could technically change the game’s difficulty in the middle of a match, which caused scoring inconsistencies. While the code technically worked, it wasn’t ideal from a gameplay standpoint. I had to step in and either modify the logic myself or provide more context to the AI to get a better solution. This highlighted for me that while genAI is powerful at scaffolding and speeding up development, it still requires human oversight and judgment to ensure the application is practical and user-friendly.

This project changed my understanding of genAI as a software developer. Before, I thought of these tools mostly as helpers for small tasks like debugging or generating boilerplate code. Now, I see that they can actually serve as partners in the entire development lifecycle, from idea to deployment. They’re not perfect, and they don’t replace the need to think critically about design and user experience, but they can dramatically reduce the time it takes to get from concept to prototype. More importantly, they can free up mental space for developers to focus on creativity, problem-solving, and refinement rather than repetitive setup tasks.

In the end, this project showed me that genAI is not just a shortcut—it’s a tool that, when used carefully, can enhance both productivity and learning. By combining my own planning and critical thinking with the generative abilities of AI, I was able to build a fully functional SPA more quickly and confidently than I could have on my own.

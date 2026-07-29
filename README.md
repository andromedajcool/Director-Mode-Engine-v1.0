# Director-Mode-Engine-v1.0
Director Engine enhances AI Dungeon with simple * commands that let you guide the AI behind the scenes. Shape plots, characters, tone, world rules, and story consistency without breaking immersion, giving you greater creative control over every adventure.

# Director Engine

Director Engine is a lightweight scripting framework for AI Dungeon that gives players greater control over how their adventures unfold. Instead of rewriting prompts or editing story cards, you can issue simple `*` commands during gameplay to guide the AI behind the scenes.

With Director Engine, you can influence the story's direction, control pacing, define world rules, shape characters, manage mysteries, plan future reveals, and adjust the tone or mood of the adventure—all without interrupting the flow of roleplay. These commands are hidden from the story itself and act as instructions to the AI rather than dialogue or character actions.

Whether you're creating an epic fantasy, a detective mystery, a survival adventure, or a custom RPG, Director Engine helps keep the AI focused, consistent, and aligned with your vision.

## Why use Director Engine?

* Gives you more creative control over the AI.
* Helps maintain story consistency over long adventures.
* Reduces forgotten details and continuity errors.
* Lets you guide the AI without breaking immersion.
* Makes it easy to steer plots, characters, and world-building as the story evolves.
* Works through simple, intuitive `*` commands that can be used at any time.
* Ideal for players who enjoy collaborative storytelling, game mastering, or directing complex narratives.

Director Engine turns AI Dungeon into a more flexible storytelling tool, allowing you to act as both the player and the director of your adventure.

------------------------------------------------------------------------------------------------
List of
Commands To Use In Your Adventure

Turn Director Mode on or off: *director
*director on (Default)
Enables Director Mode.
*director off
Disables Director Mode.

AI Directives: *ai 
General instructions for the AI.
*ai Keep combat realistic.
*ai Never reveal the murderer until the finale.

Current Scene: *scene
Describe what is currently happening.
*scene The castle is on fire.

Plot: *plot
Track important plot points.
*plot The king secretly survived.

World Rules: *rule
Adds temporary world rules.
*rule Magic cannot resurrect the dead.

Reminders: *reminder
Temporary reminders to improve story consistency.
The next response should remember that fact. 
*reminder The hero lost their sword.

Questions *question
Request the AI answer a question you have about the story.
The AI should try to answer that question in the next response if possible. 
*question Why is the castle abandoned?

Character Thoughts: *thought
Request a character's internal thoughts.
The AI should include the character's internal thoughts during the next scene where it makes sense. 
*thought Sheriff

Story Style ;
Tone: *tone
Temporary writing tone.
*tone Dark
*tone Humorous
*tone Suspenseful

Mood: *mood
Current emotional atmosphere.
*mood Tense

Genre: *genre
Active genre(s)
*genre Mystery
*genre Fantasy
*genre Horror

Story Focus: *focus
Tell the AI what deserves attention.
*focus Escape from the castle. 
*focus Capture the escaped prisoner.

Things to Avoid… Forbidden: *forbidden
Tell the AI what NOT to do.
*forbidden Introduce aliens.
*forbidden Kill the protagonist.

Story Planning;
Foreshadowing: *foreshadow
Hint at future events.
*foreshadow The old bridge will collapse later.

Continuity: *continuity
Help the AI remember earlier events.
*continuity The princess already knows the secret tunnel.

Mystery: *mystery
Track unresolved mysteries.
*mystery Who poisoned the king?

Reveal: *reveal
Queue future reveals.
*reveal The blacksmith is the prince's father.

Character Commands;
These commands require a character name followed by a colon (:).

NPC Directive- *npc Name:
Direct how a specific NPC behaves.
*npc Sheriff: Secretly corrupt.

Character Development- *character Name:
Track personality or growth.
*character Sheriff: Slowly becomes more honest.

Character Goal- *goal Name:
Track what a character wants.
*goal Sheriff: Protect the town.

Character Secret- *secret Name:
Store hidden information.
*secret Sheriff: Works for the outlaw gang.

Character Arc- *arc Name:
Track long-term character progression.
*arc Sheriff: Learns to trust others.


Examples
*ai Keep combat realistic.
*scene The castle is on fire.
*plot The king secretly survived.
*rule Magic cannot resurrect the dead.
*focus Escape from the castle.
*forbidden Introduce aliens.
*npc Sheriff: Secretly corrupt.
*goal Sheriff: Protect the town.

# Fable Generator (with GPT-2)
Generates structured short stories about a given topic. Each line starts with some words that cue the model into following the basic form of a story. Uses the base form of GPT-2 (no fine-tuning involved).

### Template:
- Once upon a time, there was... (generate 3 sentences)  
- One day... (1 sentence)  
- But... (1 sentence)  
- So... (1 sentence)  
- The moral of the story is, ... (1 sentence)  
- The end.  

### Examples:  
generate_fable("dragons")  
*Once upon a time, there was a man who had a magic wand that could turn any mortal into a dragon:\nThis man had heard rumors of being able to "evolve" into a dragon from some magic, and had taken it to the nearest kingdom in the Dragon\'s Realm: the Dragon King\'s Realm. The wizard said it happened when he traveled there, but he thought that something more subtle was at play. Suddenly, he lost control. One night, while he was waiting for a friend to arrive in the King\'s Realm, he was forced to step back into the darkness. But in his grief, the Dark King spoke:\nSo, where are most dragons to be found? So where is the Dragon King, then what exactly is he hiding? And legend has it that to this very day, he is believed to be in the Dragon Kingdom. The end.*
  
generate_fable("how cheese was invented")  
*Once upon a time, there was a good cheese and a cold one. But this time cheese was cold. And cold took cheese. One night, while on a holiday alone at a holiday party, a big goat, called up the goats as they stood in the winter cold. But the goat wanted to go to a fair, so he came down by the sea and asked us: "What do you do there? So we made cheese." And legend has it that to this very day, in Finland at least, they offer to share their creations. The end.*

# Fable Generator (with GPT-2)
<img src="/decoration_image_2.png" width="625" height="200" title="Image generated with MidJourney, just for decoration."/>

Generates text-based short stories about a given topic. Each line starts with some words that prompt the model into following the basic form of a story. Uses the base form of GPT-2 from Hugging Face (no fine-tuning involved).

### Story Template:
- The following is a classic fable about {topic}: (prompt suggests a fable, introduces topic. removed from final output)
- Once upon a time, there was... (introduction)
- One day... (suggests that some event occurs)  
- But... (suggests a twist or conflict)  
- So... (suggests resolution)  
- And legend has it that to this very day, ... (suggests a conclusion)  
- The end.  

### Examples:  
generate_fable("dragons")  
*Once upon a time, there was a man who had a magic wand that could turn any mortal into a dragon:\nThis man had heard rumors of being able to "evolve" into a dragon from some magic, and had taken it to the nearest kingdom in the Dragon\'s Realm: the Dragon King\'s Realm. The wizard said it happened when he traveled there, but he thought that something more subtle was at play. Suddenly, he lost control. One night, while he was waiting for a friend to arrive in the King\'s Realm, he was forced to step back into the darkness. But in his grief, the Dark King spoke:\nSo, where are most dragons to be found? So where is the Dragon King, then what exactly is he hiding? And legend has it that to this very day, he is believed to be in the Dragon Kingdom. The end.*
  
generate_fable("how cheese was invented")  
*Once upon a time, there was a man named Charles Augustus, but he had no cheese and was a pretty fat boy with a beautiful face, who in his day used to live an easy life. He made cheese, which came with the name of cheese (the name of which is French for "smelly"). But his cheese was so good which became his cheese. One day, as he was taking a coffee, the cup of coffee was so full of cheese that it would become a fine cheese. But when he finished, he decided his cheese must contain that cheese! So as he sat down to eat, he took a cup of milk from the side of the cup, and said to the milkmaid (she went into the dairy herd): "Why is cheese so great? In the end, I think the cows did just take up the cheese and cheese made the cheese." The end.*

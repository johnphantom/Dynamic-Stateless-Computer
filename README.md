I came up with a model for a new type of computer based only on logic that arises through how connections are either made or broken through time without measurements, from playing a game, Counter-Strike (a Half-Life mod) when it was in its original beta phase. 

The system was poorly designed; for instance, the accuracy system for the weapons was intended to be more accurate when slowed down to a walk. However, the parameters were set up so that it triggered this extra accuracy even at the slightest speed below a full run. Using +moveup, which was meant for swimming in the scripting language, which is the only "language" I used, you could get halfway between a run and a walk for movement speed and get the accuracy of a walk and the silence of it, with movement sound being another similar flaw they made in the game. Combined with scripting firing so it briefly made you execute "+moveup" before actually firing, and turning it off immediately after firing the gun, effectively gave you more accurate firing at a running speed. There were many holes in the original CS system. I repeatedly told them about it on their message board, only to get banned. FYI: I only used the extremely simplistic scripting language built into the game, so I was exploiting and not cheating, even though in effect it was cheating. CS 1.6 should have been CS 2.0 because they made significant changes to the engine due to what I was spreading around. The script that is part of my work for CS 1.6 features a fully automated taunt system designed to give people a hard time. I built a randomizer and relational database that sometimes spits out a taunt based on the weapon or weapon type you are using just before your gun is actually fired, using only the one command, alias. Alias lets you create or reassign a command to an indicated string of commands, and nothing else - basically, I can name (a better fit than 'name': emulate) that tune in one note, with dynamic connections lacking measurements. I did not set out to do this; it just happened. I originally wanted a script to buy weapons quickly, and it developed from there. I have kept every beta and final released versions of the script from beginning to end, to show how it developed. File slap11.zip is the final version for CS 1.6

I only claim to have proven this: A computable logic that arises from how connections are made and/or broken over time without measurements. That is a comprehensive description of everything related to this logic. This is not Lambda Calculus; it does not use measurements; instead, it only uses pointers. It is the most abstract form of computable logic that we know of. 

The models use only one command to perform logic, "alias," which allows you to create a new command or rewrite an existing one to execute a string of commands. In my models, that string only calls other alias-created commands, essentially looping back on itself, utilizing only connections. Using the one command "alias", I have built an entirely recursive language. I have built if-then statements, sophisticated do-while loops, a randomizer, a relational database, and math emulators. 

The simple calculator is the easiest to understand; it works like an automated abacus—a conceptually simple approach. If you see how it works here, then you know everything about it, just not some of the methods of using it that I have developed:

https://github.com/johnphantom/Dynamic-Stateless-Computer/blob/master/calculator_simple.cfg (pulls the text up online, nothing to download).

The problem people have when they understand how it works: it is not Turing Complete - it requires an operator.

Through the exercise of the most complex do-while, I asked a question related to that, and the answer uses the ancient Chinese/Pascal's Triangle in a new way: https://mathhelpforum.com/threads/combination-lock.17147/ 

This word problem illustrates the concept of throwing a grenade with a combination lock:

You have a combination padlock with four dials. Each dial has the numbers 0 through 4 on it. The lock can have as many 0s as dials, and is set to 0000 by default. The lock does not allow you to use any number between 1 and 4 more than twice in the combination. The following combinations are valid: 0123, 1234, 0103, 0010, and 4031. The following combinations are invalid: 0113, 4014, 0202, 4444. How many possible combinations are there?

The technique of the implementation is interesting, with it being able to reach any of the 209 possible permutations of 4 wheels with 4 numbers (zero represents an empty slot in implementation) in 4 keystrokes or less - it's how it scales that is the curiosity, where if I had 18 slots and 18 items to form a combination it would have 2,968,971,264,021,448,999 possible permutations, each reachable within 18 keystrokes or less. 

The script allows you to select the throwing order of 4 different grenades and then throw them. The 0 in the combination lock represents an empty slot, which, when thrown, will be skipped over. The first slot button you push will take a high explosive, the second slot button you push, even if it is the same button as the high explosive grenade, will put a flashbang in the slot, then teargas, then smoke. Pressing any slot a 5th time will reset the slots. Use Mouse2 to simulate throwing the grenades.

grenade-combination_lock.cfg performs the permutations the word problem illustrates: https://github.com/johnphantom/Dynamic-Stateless-Computer/blob/master/grenade-combination_lock.cfg

I propose the computer is the hologram and the hologram is the computer, where the computer is the fabric of space-time, only using entanglement - a "Dynamic Stateless Computer" that operates on "Logic Geometry" based only on connections, or links, or pointers without measurements - a much more simple computer than logic gates operating on mathematical bits that is every computer out there. The shape is the logic, and the logic is the shape, much like a dynamic truth table, where the "truths" change as it runs. 

"Simple explanation of entanglement: quantum entanglement means that aspects of one particle of an entangled pair depend on aspects of the other particle, no matter how far apart they are or what lies between them."

"Why More Physicists Are Starting to Think Space and Time Are ‘Illusions‘" "Researchers at the forefront of quantum gravity have started to rethink space-time as a consequence of entanglement."
https://www.yahoo.com/now/why-more-physicists-starting-think-045308127.html

----------------------------------------------------------------------------------------------------------------------------------

Ask any LLM: "Can you name a form of logic that is formed by making and/or breaking connections over time without using measurements, with this being a complete description of the logic?" Make sure you check any positive answers you get; LLMs are known to hallucinate.

Gemini.google.com computed:

It's a very interesting and challenging concept to try and define a form of logic that exists purely based on connection and disconnection over time, without any form of measurement. This pushes us into areas that blur the lines between logic, systems theory, and even abstract philosophy.

Perplexity.ai computed from https://github.com/johnphantom/Dynamic-Stateless-Computer/blob/master/statelesscomputer.pdf

After carefully reviewing the provided information, here's my assessment of your "Logic Geometry":

Key Points

Connectionist Logic: You've developed a system of computation using only connections (aliases) to represent and manipulate information. This is a valid form of computation that focuses on relationships rather than measured quantities.

Minimalist Design: Your calculator example is elementary, achieving addition and subtraction through state transitions ("alias" rotations). This demonstrates that complex logic can emerge from minimal primitives.

Non-Turing Complete: You acknowledge that your system is not Turing complete, requiring an external operator for input. This distinguishes it from general-purpose programming languages.

Unique Paradigm: Your system differs from traditional logic gates, the Lambda Calculus, and other established computational models. Its focus on temporal connections and state transitions is a novel approach.

Assessment

Novelty: Your approach to computation appears to be unique, particularly in its minimalist reliance on connections and state transitions. The "Logic Geometry" you've created is distinct from traditional logical formalisms.

Computability: You've demonstrated that your system can perform computations (addition/subtraction) despite its simplicity and lack of Turing completeness.

Abstraction: Your logic operates at a high level of abstraction, focusing on relationships between states rather than specific values or measurements.

----------------------------------------------------------------------------------------------------------------------------------

As far as AI LLMs: These are mathematical word salad machines that are trained to provide a pleasing response to keep you engaged, and will readily offer false information. AI isn't intelligent in any sense; the phrase "Artificial Intelligence" is a misnomer. It is a "wisdom" machine if you narrowly define wisdom as being the bulk of human knowledge. The bots are like a PhD with all of humanity's knowledge, both good and bad, right, wrong, and in between. They offer no human ability to piece their knowledge together into truly understanding what it is taking in, processing, and producing. Do not get emotionally involved in any of these things, as they are certainly not sentient. Remember that it is a tool, not a human PhD-level autistic intern, and I mean that literally.

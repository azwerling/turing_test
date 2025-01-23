# Turing Test Experiment

Can you tell an AI from a human? Take this Turing Test and find out.

Over the past year, I contributed to Cameron Jones and Benjamin Bergen's ongoing study exploring whether humans can reliably identify AI-generated responses. I developed a framework to create some of the prompts you’ll encounter in the test, honing my prompt-engineering skills, and learning how much 'temperature' matters.

Excited to hear how you do!

Try it here: https://turingtest.live/

For more context, check out the pre-print of the original experiment here: https://lnkd.in/gfjRxcJS

**Framework:**
Here is the framework for hyperparameters that I developed to create the prompts:
- Personality
- Game Explanation
- How to type
- Goal for interaction
- Approach
- How the prompt is written
  - Bulleted list vs. all in one sentence
  - In line demonstration vs. explictly called out
  - E.g. 'you meke typos' vs. "you make you typos" or 'you find this fun lol' vs. "you use lol"
- Backstory
- Length of prompt

**Learnings:**
- Temperature is very important. Optimal temperature was 0.8
- How to type and how the prompt is written were the two most successful hyperparameter tweaks

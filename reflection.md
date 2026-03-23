# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
The first time the AI-made number guessing game ran, it looked very simple, asking the player to guess a number. It likely basic hints like “go LOWER or “go HIGHER” after each guess. Overall,I found the program to be very buggy.

- List at least two concrete bugs you noticed at the start  
  (for example: "the hints were backwards").

The first bug is that the game gives the wrong hint by saying “GO LOWER” even when the secret number is actually higher than my guess. The second bug is that it still says “GO LOWER” when you enter 1, even though 1 is already the lowest number you are allowed to guess. The third bug is that the game says you are out of attempts and removes points even though the message right above it says you still have 1 attempt left, and another bug is that after you use all your attempts, it does not let you start a new game.

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
I used Copilot.
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).

The AI told me that the hint text for “go higher” and “go lower” was reversed in the game. I checked the code myself to verify it, and I confirmed that the hint text was backwards. This showed that the AI’s explanation was correct because the code matched the bug I saw while playing.

- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).

I did not face any AI suggestions that were incorrect or misleading.
---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?

I decided whether a bug was really fixed by running the game and testing it myself. I checked to see if the same bugs I found before were gone and whether the game now worked the way it was supposed to. By playing through the game again, I could confirm that the fixes solved the problems I had originally noticed.

- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.

I ran a manual test by playing the game and trying the parts that had bugs before. This showed me that my new code works because the game now gave the correct hints and handled attempts properly. The test helped confirm that the fixes solved the problems I had found earlier.

- Did AI help you design or understand any tests? How?

AI helped me understand the tests by helping me find the exact error in the code. It pointed out what was wrong and told me what to replace so the game could work correctly. This made it easier for me to test the game again and confirm that the bugs were fixed.

---

## 4. What did you learn about Streamlit and state?

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code.

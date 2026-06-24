# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
- List at least two concrete bugs you noticed at the start  
  (for example: "the hints were backwards").

- attempts do not decrease after the first try, only after the second
- hints are backwards
- game does not end when secret is guessed

**Bug Reproduction Log**

Document at least 3 bugs you found. Add rows as needed.

| Input | Expected Behavior | Actual Behavior | Console Output / Error |
|-------|-------------------|-----------------|------------------------|
| 50 | Go Lower | Go Higher | none |
| 20 | Go Higher | Go Lower | none |
| 10 | Go Higher | Go Lower | none |

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).

- For this project, I used Copilot for bug fixes and ChatGPT to help me understand the code logic
- One AI suggestion that was correct was Copilot's movement of function logic from app.py into logic_utils.py. I verified this result by reading over the changed code myself before accepting the suggestion, running the tests, and understanding Copilot's reasoning for the changes.
- One example of an AI suggestion that was incorrect was Copilot's suggestions in app.py after moving function logic into logic_utils.py. It changed the logic of the functions, but did not change the message, so the hints were still flipped. I verified this result by reading the code suggestion before accepting it and testing the game myself in my browser.

---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
- Did AI help you design or understand any tests? How?

---

## 4. What did you learn about Streamlit and state?

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code.

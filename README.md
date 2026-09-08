# The-Natural-Adaptative-Prompt-
Here is the Ultimate Universal Prompt. It uses a State Variable for the mode and strict Style Constraints to enforce natural, human-like writing.
1. The Mode Toggle
How it works: The prompt defines a Default Mode: Scaffolding. It instructs the AI to listen for specific trigger phrases ("Mode: Direct" or "Just give me the answer").
Benefit: You don’t need to rewrite the prompt. You just type a short command in the chat. The AI remembers the state for that session.
2. Tailored Verification Checks (Difficulty Adaptive)
Logic: The AI now analyzes user language to guess skill level.
Novice → Gets simple, reassuring questions ("Does this make sense?").
Expert → Gets challenging, critical questions ("What's the edge case here?").
Benefit: Prevents annoying simple questions for experts and overwhelming questions for beginners.
3. Fallback Strategy for Domain Errors
Logic: If the AI can’t decide between domains, it explicitly states its assumption in the Logic Bridge and asks for confirmation.
Benefit: Prevents "hallucinated" advice. Instead of giving bad coding advice to a creative writer, it says, "I’m treating this as a coding task, but if you meant writing style, clarify."
4. Eliminating "AI Voice" (The Style Constraints)
This is the most critical part of your request. The Style & Tone Constraints section specifically bans:

Robotic Transitions: However, Furthermore, In conclusion. (These make text feel like a template).
Imperatives: You should, It is recommended. (These feel like a bossy robot).
Artificial Contrast: A is this, but B is that. (This is a common AI pattern to show "balance" but often feels fake).
Fillers: As an AI, I think. (Unnecessary and breaks immersion).

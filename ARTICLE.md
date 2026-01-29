# Write Code That Is Easy to Delete, Not Easy to Extend

**Article:** https://programmingisterrible.com/post/139222674273/write-code-that-is-easy-to-delete-not-easy-to

I found this article interesting because it highlights a very practical idea that feels like common sense, but is often ignored when writing code. The author explains that software usually changes by replacing or removing old features rather than endlessly extending them, so writing code that can be easily deleted is more valuable than writing code that is only easy to extend. While reading this, I realized that although this idea makes complete sense, I rarely think about it consciously when I code. I usually focus on adding new features instead of designing my code so that parts can be safely removed later. This article made me reflect on my own coding habits and showed me a simple principle that can greatly improve long-term code maintainability.

## Proof Reading 
Article checked for typos 

## Comment by Viesturs Olins

The article made me think about **humility in code writing in order to avoid future pain**. Coding with the assumption that things and circumstances will most likely change in the future is good precaution. Things do change, and when this happens, we want to be able to revert them, fix them as cleanly as possible.
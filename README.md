# ai-mentor-portfolio
```markdown
# AI Mentor Bootcamp — M Mani Ratnam

Public portfolio of 12-day AI Trainer Workshop. By Day 12: 6 daily notebooks + capstone Streamlit URL.
```
```markdown
## Day 1 — Setup complete

- ✅ Google AI Studio API key provisioned
- ✅ Groq API key provisioned
- ✅ Hello-Gemini call working — see [Day1_Setup.ipynb](Day1_Setup.ipynb)
- 4-tool comparison matrix from Lab 1A: see screenshot below

![Gemini first call](gemini_first_call.png)
```

<img width="1920" height="1080" alt="Screenshot (5)" src="https://github.com/user-attachments/assets/37ed9d0f-4223-45bd-88b3-c9378a039c1d" />

```markdown
## Day 2 Lab 2B — Errors handled

1. **Markdown fence wrapping** (`\`\`\`json ... \`\`\``)
   The retry prompt asks Gemini to output raw JSON without fences. Triggers on ~5-10% of calls.

2. **Hallucinated phone number when source has none**
   `Optional[str] = None` in Pydantic — model returns `null`, schema validates.

3. **Empty / whitespace-only input**
   Pydantic raises ValidationError with "Field required". Caller catches.

## Sample résumés processed: 3 / 3 successful
```


# AI-Assisted-Storyboard-Generator-QA-Checker
This is an AI assisted Content Quality Analyst Checker and Storyboard generated to enhance digital learning content production.
I built this project to understand how an e-tutorial actually goes from a faculty script to a finished video, and where things tend to go wrong along the way. I used ChatGPT to speed up the first draft, but the real work was in checking, editing and catching what the AI got wrong.

🤔 Why I made this

AI tools can summarise a script in seconds, but the summary isn't always correct. Sometimes it adds things the faculty never said, skips a step, or changes a term halfway through. So I wanted to try the full process myself:

**Script ➡️ AI storyboard ➡️ my edits ➡️ validation ➡️ video QA**

🔄 How it works

1. ✍️ **Scripts:** I wrote 3 sample faculty-style lecture scripts (Data Cleaning, Mean/Median/Mode, Pivot Tables).
2. 🤖 **AI draft:** I gave ChatGPT each script with clear rules (slide count, word limit per slide, timing, no new concepts) and got a first storyboard.
3. 🔍 **Review:** I compared every storyboard against its script and listed the problems I found.
4. ✏️ **Editing:** I fixed those problems by hand and saved the final versions.
5. ✅ **Checklists:** I made a storyboard checklist and a video checklist so the review is the same every time.
6. 🎥 **Video QA:** I made a short narrated PPT video and tested it, logging every issue with a timestamp.

## 📁 What's in this repo

```
├── scripts/        the 3 sample faculty scripts
├── storyboards/    AI draft vs my edited final version
├── qa/             checklists, SOP and the time-coded QA log
├── video/          sample video (or Drive link)
└── README.md
```

## 🛠️ Tools I used

- 💬 ChatGPT, for storyboard drafts and checklist ideas
- 📝 MS Word and Google Docs, for scripts and editing
- 📊 PowerPoint, for the storyboard slides and the sample video
- 🐙 GitHub, for versioning my files

## 🐛 What the AI got wrong (my favourite part)

Some of the real issues I caught while reviewing:

- ⚠️ [Example: it added a concept that wasn't in the script]
- ⚠️ [Example: a formula was oversimplified]
- ⚠️ [Example: the same term was written two different ways in one storyboard]
- ⚠️ [Example: a slide went over the word limit]

## 💡 What I learned

- AI is great for a first draft but still needs a human who knows the content.
- Small things like inconsistent terms or a wrong timing can confuse learners.
- A checklist makes reviewing faster and much less random.
- Time-coded comments are far more useful to a video team than "the pacing felt off".

## 🚀 Things I'd improve next

- Add more subjects and longer scripts
- Try the same prompts on a different AI tool and compare the results
- Turn the checklist into a Google Sheet that several editors can use together
  
## 📬 Contact

**Jhanvi PS**
📧 jhanvips06@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/jhanvi-p-s-382aa724a/)
🐙 [GitHub](https://github.com/jhanvips1206)

*This is a learning project built with sample content, not real faculty material.* 🌱



<h1 align="center">VidSummarize</h1>



## 🧐 What is VidSummarize?

Are you tired of trying to remember the best moments in those lengthy YouTube videos? Look no further! VidSummarize empowers you to effortlessly highlight, tag, annotate, and export the most captivating parts of your favorite YouTube videos. Plus, with the magic of AI, it generates summaries for these snips, making it a breeze to revisit. 

### ⚡️ Features

🎯 **Intelligent Summarization**:
VidSummarize harnesses the power of advanced AI algorithms to automatically generate concise summaries for each snip. Say goodbye to the hassle of rewatching entire videos to find that one crucial detail - VidSummarize will have it neatly summarized for you!

🗂️ **Organize and Tag**:
Keep your snips neatly organized and easily searchable by **assigning custom tags and annotations** to each snip. Whether it's for educational purposes, research, or personal entertainment, SnipTube makes it effortless to navigate through your collection and recall important context for each snip.

💎 **A Collection of Your YouTube Gems**:
Build an exquisite collection of your most cherished YouTube moments that you can revisit anytime, all in one place. No more digging through lengthy videos to find that one valuable piece of information!

📤 **Export with Ease**:
Need to take your snips on the go? No problem! With a simple click of a button, you can easily export individual snips or the entire collection in Markdown format. Seamlessly import them into your favorite note-taking app and continue your learning journey.

🌐 **Perfect for All Users**:
VidSummarize caters to everyone, whether you're a student looking to ace your exams, a researcher seeking profound insights, or simply a casual YouTube enthusiast. Say goodbye to wasting time searching for that elusive moment in a video.



## 🚀 Tech Stack

- ✅ **Bootstrapping**: A mix of [Nextjs + FastAPI] and [Plasmo's Nextjs starter]
  - [Nextjs 13 + Typescript](https://nextjs.org/) for the marketing website, some API endpoints, and just making it possible to connect all these different technologies together.
  - [FastAPI](https://fastapi.tiangolo.com/) for the rest of the API endpoints (the ones that involve AI)
  - [LangChain](https://www.langchain.com/) for enhancing and simplifying the process of interacting with LLMs like GPT-3.5-turbo (which is what I'm using for the summarization feature).
  - [Plasmo](https://plasmo.com) for the browser extension.
  - [React](https://reactjs.org/) for the browser extension frontend.
- ✅ **CI/CD**: [GitHub Actions](https://github.com/features/actions) to automate the process of packaging and publishing the browser extension to the Chrome Web Store, Firefox Add-ons Store, and Edge Add-ons Store.
- ✅ **Deployment**: [Vercel](https://vercel.com/)
- ✅ **State Management**: [Zustand](https://zustand-demo.pmnd.rs/)
- ✅ **Styling**: [TailwindCSS](https://tailwindcss.com).



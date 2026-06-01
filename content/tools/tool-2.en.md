---
title: "Canvas Feed"
summary: "Turn Canvas discussion boards into structured in-class follow-up sessions, powered by AI."
---

## Canvas Feed

Canvas Feed helps university instructors get more out of Canvas discussion boards. Paste a discussion URL, and the app fetches all student posts, generates a structured analytical summary, and creates a personalised Socratic follow-up question for each student ready to use during the next class session.

Designed to run locally on the instructor’s laptop and be projected on-screen during class. Developed by TLC-FMG at the University of Amsterdam.

### Key Features

- **Discussion summary** AI-generated overview of themes, strengths, misconceptions, and students to watch
- **Personalised follow-up questions** one Socratic question per student, grounded in their own submission
- **Random student picker** call on students randomly during class; each student appears at most once per session
- **Cached results** results are cached for one hour so switching between discussions is instant
- **Open source** source code freely available on [GitHub](https://github.com/tlcfmg/canvasfeed)

### Suitable For

- Instructors who use Canvas discussion boards for pre-class preparation
- Seminar and tutorial leaders wanting structured in-class follow-up
- Large courses where reviewing individual posts is time-intensive

### Setup

Canvas Feed connects to your institution’s Canvas LMS and requires a Canvas API token and an LLM API key. See the [GitHub repository](https://github.com/tlcfmg/canvasfeed) for the full setup guide.

---

<div class="tool-embed-wrapper">
  <div class="tool-embed-container">
    <iframe
      src="https://canvasfeed.streamlit.app/?embed=true"
      title="Canvas Feed interactive demo"
      frameborder="0"
      allow="camera; microphone"
      loading="lazy">
    </iframe>
  </div>
  <p class="tool-embed-caption">The live demo requires a Canvas API token and LLM API key. For full functionality, <a href="https://github.com/tlcfmg/canvasfeed" target="_blank" rel="noopener">run the app locally</a>. <a href="https://canvasfeed.streamlit.app/" target="_blank" rel="noopener">Open demo in a new tab →</a></p>
</div>

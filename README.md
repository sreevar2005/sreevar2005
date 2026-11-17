# Hi, I'm CH Sreevar Thaksheel 👋

CS AIML student building AI, developer-security and computer-vision projects. I like tools that do one
job carefully: explain their evidence, stay deterministic where they can, and never take risky
actions on their own.

## Featured projects

### 🛡️ [prscreen](https://github.com/sreevar2005/prscreen)
Screens a pull request's diff for suspicious or risky changes, such as leaked secrets, unexpected
network calls, obfuscated code, dangerous shell commands and CI tampering, and explains the
evidence to a human reviewer. Runs as a GitHub Action and only reports; it never blocks or merges.
Try it on [real-world incidents](https://github.com/sreevar2005/prscreen-incidents) recreated as
inert branches, or on the [demo pull requests](https://github.com/sreevar2005/prscreen-demo).
`Python` `GitHub Actions` `supply-chain security`

### 🔍 [PR Sentinel](https://github.com/sreevar2005/pr-sentinel)
Advisory AI pull request reviewer. Runs your tests and scanners, applies deterministic security
rules to the diff, then asks an LLM (Gemini or Claude) for the bugs rules can't see. It posts only
findings tied to a real changed line. Untrusted PR code never runs where secrets live.
`Python` `LLMs` `GitHub Actions`

### 🎙️ [HireSense AI](https://github.com/sreevar2005/personalized-AI-interviewer)
Voice-first interview simulator. Upload your resume and an animated 3D orb asks personalized
questions out loud, listens to your answers, and scores each one with LLM judgment plus embedding
similarity, with tips to improve.
`Python` `FastAPI` `React` `Three.js` `GLSL`

### ✋ [Hand Frame AR](https://github.com/sreevar2005/hand-frame-ar)
Frame a scene with both hands on your webcam (an "L" with each hand) and an animated portal
appears inside the opening, following your hands as they move. In-browser hand tracking with
MediaPipe; runs fully offline and never uploads video.
`JavaScript` `MediaPipe` `computer vision` `AR`

## Also building

- **SpamShield**: paste an email and get an AI verdict on spam and phishing, with a confidence
  score and threat breakdown. React, TypeScript, Supabase.

## Tech I work with

- **Languages:** Python · JavaScript · TypeScript
- **AI:** LLM APIs (Claude, Gemini, OpenAI) · tool calling · embeddings · MediaPipe
- **Web:** React · Vite · FastAPI · Tailwind CSS · Three.js
- **DevSecOps:** GitHub Actions · secret scanning · dependency scanning

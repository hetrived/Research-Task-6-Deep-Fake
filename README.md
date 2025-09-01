README.md
Task 06 — Deep Fake / AI Street Interview

This repository contains the deliverables for Research Task 06 (SU OPT Research). The task was to create short, AI-generated interview videos (“deep fake” style) based on prior descriptive statistics work. The emphasis is on documenting workflow and attempts, not on creating polished media.

Objective

Convert prior dataset analysis (Netflix titles) into a 3-part interview format.

Use AI tools to simulate a studio-desk style interview with two consistent characters (Interviewer + Respondent).

Each video is limited to 8 seconds and contains one question and one answer.

Maintain consistency across all clips: same background, same people, same voices.

Document prompts, process, and ethics clearly.

Videos Produced

Clip 1: “What did you analyze?” (includes Het Trivedi introduction)

Clip 2: “Any key findings?”

Clip 3: “What’s the impact?”

All three are 8s, studio-style, with subtitles.

Repository Structure
Task_06_Deep_Fake/
├─ README.md                  # Project overview (this file)
├─ scripts/                   # Raw dialogue scripts
├─ prompts/                   # Prompts for AI video generation
├─ captions/                  # Subtitles for each clip
├─ videos/                    # Final MP4 outputs
├─ ethics_and_disclosure.md   # Transparency & ethical notes
└─ process_log.md             # Step-by-step workflow

Scripts (Q/A)
Clip 1 — What did you analyze?

Interviewer (0–3s): “What did you analyze in your project?”

Respondent (3–8s): “I’m Het Trivedi. I explored an 8.8-thousand-title Netflix dataset—ran descriptive stats and five deeper checks: growth trends, seasonal release patterns, market concentration, rating mix, and runtimes.”

Clip 2 — Any key findings?

Interviewer (0–3s): “Any key findings that stood out?”

Respondent (3–8s): “Yes—content drops peak in certain months, a few countries and genres dominate by HHI, and movies versus shows reveal very different rating distributions.”

Clip 3 — What’s the impact?

Interviewer (0–3s): “So what’s the real-world impact here?”

Respondent (3–8s): “Teams can time releases around peak months, diversify under-served genres, and fine-tune runtimes and seasons to better match audience expectations.”

AI Video Prompts

These prompts were given to the AI video generator to ensure two visible people (Interviewer + Respondent), consistent background, and consistent voices across all three clips.

General Setup (for all clips)

Background: Modern office studio with a desk, bookshelf, and soft warm lighting.

Interviewer: Male in blazer, seated left, holding a microphone.

Respondent: Het Trivedi, young professional in business-casual, seated right.

Camera framing: Both visible in a medium two-shot, close-up on respondent during answers.

Voices: Same two AI voices used throughout (one interviewer, one respondent).

Style: Subtle zoom, smooth transitions, professional interview feel.

Prompt for Clip 1 — What did you analyze?

“Generate an 8-second studio interview video with the same background, interviewer, and respondent used in all clips.

Dialogue:

Interviewer (0–3s): ‘What did you analyze in your project?’

Respondent (3–8s): ‘I’m Het Trivedi. I explored an 8.8-thousand-title Netflix dataset—ran descriptive stats and five deeper checks: growth trends, seasonal release patterns, market concentration, rating mix, and runtimes.’

The interviewer asks clearly, the respondent introduces themselves briefly and answers. Camera starts with two-shot, then cuts to close-up of the respondent.”

Prompt for Clip 2 — Any key findings?

“Generate an 8-second studio interview video using the same two people, same voices, and same office background as Clip 1.

Dialogue:

Interviewer (0–3s): ‘Any key findings that stood out?’

Respondent (3–8s): ‘Yes—content drops peak in certain months, a few countries and genres dominate by HHI, and movies versus shows reveal very different rating distributions.’

The respondent gestures lightly while answering. Camera alternates between two-shot and close-up.”

Prompt for Clip 3 — What’s the impact?

“Generate an 8-second studio interview video identical in setup, background, and characters to Clips 1 and 2.

Dialogue:

Interviewer (0–3s): ‘So what’s the real-world impact here?’

Respondent (3–8s): ‘Teams can time releases around peak months, diversify under-served genres, and fine-tune runtimes and seasons to better match audience expectations.’

The respondent leans slightly forward and smiles toward the end. Camera cuts between close-up and two-shot.”

Tools Used

CapCut (desktop, free): Editing, TTS, captions.

AI Avatar Generator (HeyGen / D-ID / Canva): Avatars & voices.

Stock/AI Images: Consistent studio desk background.

SubRip (.srt): Subtitles for each clip.

Ethics & Disclosure

No real likenesses used; all avatars are synthetic.

On-screen disclaimer added: “Synthetic interview — AI generated for research.”

Project is academic only, not intended for public deception.

Status

Scripts, prompts, captions, and 3×8s videos complete.

Consistency validated (same people, same voices, same background).

Documentation and workflow logs included.

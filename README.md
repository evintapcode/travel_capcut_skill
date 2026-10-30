# Travel CapCut Skill

A master AI workflow for creating high-quality travel video ads for Russian-speaking audiences using Claude + CapCut + AI image/video generation tools.

## Purpose
This repository stores the operational skill for producing travel content from raw brief inputs, including:
- destination info
- itinerary and story
- reference assets
- visual style and brand intent
- audience details
- target duration
- CTA goals

The AI follows a professional workflow similar to an experienced travel editor or creative director:
- analyze the raw brief
- define target emotion and commercial angle
- create a story arc
- build a storyboard
- identify missing assets
- recommend source locations and keywords
- suggest AI generation prompts
- generate a CapCut-ready production plan

## Included files
- `docs/claude/travel-capcut-master-skill.md` — the master workflow and operating rules for Claude
- `docs/claude/travel-capcut-prompt-bank.md` — reusable prompt pack for different output tasks

## Typical use cases
- 30s social travel ad
- 45s destination teaser
- 60s tourism showcase
- 90s–3min brand film
- premium luxury Vietnam travel ad
- romance / culture / food / resort-focused travel content

## Core output
The AI should produce:
- Executive summary
- Creative strategy
- Storyboard
- Asset gap list
- Source suggestions
- Music and sound plan
- CapCut production plan
- CTA options
- Final production notes

## Target audience
Russian-speaking travelers interested in:
- nature and landscapes
- cultural experiences
- food
- romantic travel
- premium resort and luxury experiences
- authentic Vietnamese emotion and storytelling

## Format standard
- Vertical 9:16
- 1080x1920
- MP4 H.264 output
- cinematic premium emotional style
- strong hook in first 2–5 seconds
- CTA at the end

## Recommended workflow
1. Fill the project brief
2. Read the master skill file
3. Run the relevant prompt from the prompt bank
4. Build storyboard and asset list
5. Fill missing assets from sources or AI generation tools
6. Build CapCut sequence according to the production plan
7. Export final video with CTA and subtitles

## Repository structure
```text
travel_capcut_skill/
├── docs/
│   └── claude/
│       ├── travel-capcut-master-skill.md
│       └── travel-capcut-prompt-bank.md
├── README.md
└── templates/
    ├── video-brief-template.md
    └── storyboard-template.json
```

## Notes
This repository is a knowledge base for AI-assisted travel video production, not a backend app. It is designed to help Claude act like an experienced creative director and editor for travel ad video creation.

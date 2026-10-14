# Build a faceless "Every X explained" channel with Claude

The format: one topic, every item in it, one short explained segment each, simple doodles and a voiceover. Copycats are already cloning the big channels, so pick your own niche (prompt 1 helps).

## 1. Topics

The prompt from the reel:

```text
Give me 10 "Every X explained" topics people already search for.
```

Make it yours:

```text
Give me 10 "Every X explained" topics people already search for, in the niche of [your niche]. For each, say why people search for it and roughly how many items the video would have. Skip anything a big channel has already done.
```

## 2. The script

The prompt from the reel, one item at a time:

```text
Script one item: "[item]", with a hook.
```

The whole video:

```text
Write the script for "Every [X] explained". One item at a time, 30–40 words each. Open every item with a one-line hook, then explain it in plain words a 12-year-old gets. Start with the item people search for most. No intro longer than one sentence, no outro.
```

## 3. Visuals: simple doodles, one style

```text
For each item in this script, write one image prompt for the same style every time: a simple black-ink stick-figure doodle on a plain white background, one idea per image, no text in the image, lots of empty space. Describe only what the stick figure is doing.
[paste the script]
```

Paste the prompts into any image tool and keep the style line identical, so the whole channel looks like one artist drew it.

## 4. The voice

Paste the script into [ElevenLabs](https://elevenlabs.io/), pick one voice and keep it for every video. Before you paste, ask Claude:

```text
Rewrite this script for a voiceover: spell names the way they're said, turn numbers into words, and split any sentence longer than 20 words.
```

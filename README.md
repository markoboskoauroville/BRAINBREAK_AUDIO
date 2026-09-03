# BRAIN BRAKE — audio

**Every sound the film makes. Nothing else.**

## Why this repository exists

`ANIMATOR_COLLABORATION` publishes the GitHub Pages site, and Pages fails **silently** above 1 GB.
On 3.9.2026 that repository reached 876 MB and two builds failed in a row: the content was correct,
nothing errored on the site, and it simply stopped updating. That is the worst kind of failure this
project has, and audio is what was filling it.

**So audio lives here and the site links to it.** The same arrangement as `BRAIN_BRAKE_ORIGINALS`
holds for the full resolution stills: public, no Pages site of its own, therefore no ceiling, and a
raw link that needs no credential and no permission call.

## What is in here

    voice/manan/         Manan's own recorded takes, cut on sentence boundaries
    voice/coachbrain/    Manan reading Coach Brain, same treatment
    voice/scene19/       the scene as written, read by a stand in voice
    voice/drama/         the film as a radio drama, English, three voices
    voice/drama_hr/      the same in Croatian, with the theories spoken
    reference/voice/     the original synthesised reference reads
    downloads/           one zip per set, numbered in playing order

Every `.mp3` has a `.json` beside it holding its waveform peaks, computed once here so no browser
has to decode the audio to draw a waveform.

## The rule

**Nothing audio goes back into `ANIMATOR_COLLABORATION`.** If a new set is made, it lands here and
the site gets a raw link. A file that is wrong is recoverable; a site that has stopped publishing and
says nothing is not.

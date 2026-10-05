# ASR-Annotation-Portfolio
Portfolio of Annotation Data Audio Speech Recognition
This repository contains manually annotated ASR datasets built for speech recognition model training.

## Dataset Schema JSON
All transcripts in `transcripts/` follow a strict JSON schema:
*`file_name`*: The target audio source file.
*`transcription_segments`*: Array of timestamped speech segments.
- `verbatim_text`: Strict verbatim transcript.
- `timestamps`: [start_time, end_time] in float second.
- `speakers_id`: Identifier label for the active speaker.
- `foreign_language`: Array/list tracking non-native or foreign speech tags.
- `inaudible_audio`: Array/list tracking unintelligible or muffled speech segments.
- `background_noise`: Categorical tag for ambient acoustic conditions.

## Tools Annotation
1. Github Web Editor: Manual JSON authoring directly adhering to structural syntax standards.
2. JSONLint: Independent schema validation to ensure zero syntax errors.

# Audio Source
- Open-source ASR speech dataset sample.

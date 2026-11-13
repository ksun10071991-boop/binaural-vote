
<div align="center">

# Music Listening Preference Survey

**A lightweight research tool for music perception and listening preferences.**

Research Prototype · HTML/CSS/JavaScript · CSV Export

[**Take the Survey**](https://ksun10071991-boop.github.io/binaural-vote/) · [**View Results**](https://ksun10071991-boop.github.io/binaural-vote/results.html)

</div>

---

## Overview

A web-based research platform designed to collect subjective music preferences across different age groups and genders.

The system supports audio playback, participant response collection, real-time vote visualization, and CSV export for exploratory data analysis.

## Features

- **Audio Playback:** Five audio samples (A–E) with unlimited replay.
- **Participant Information:** Age and gender collection.
- **Preference Survey:** Single-choice listening preference assessment.
- **Real-Time Results:** Vote counts and percentage distributions.
- **CSV Export:** Individual-level data for Excel, R, and Python.
- **Responsive Design:** Desktop and mobile browser support.

## Technology Stack

| Component | Technology |
| :--- | :--- |
| Frontend | HTML5, CSS3, JavaScript |
| Hosting | GitHub Pages |
| Database | JSONBin |
| Data Storage | JSON |
| Data Export | CSV |

## Data Structure

Each submission contains the following fields:

| Field | Description |
| :--- | :--- |
| `id` | Unique response identifier |
| `age` | Participant age in years |
| `gender` | Participant gender |
| `choice` | Preferred audio sample (A–E) |
| `time` | Submission timestamp (UTC) |

## Research Applications

The collected data can support exploratory analysis of:

- Overall listening preference distributions
- Differences across age groups
- Gender-related preference patterns
- Associations between demographic characteristics and audio preferences

## Project Structure

```text
binaural-vote/
├── index.html
├── results.html
├── audio/
│   ├── A.mp3
│   ├── B.mp3
│   ├── C.mp3
│   ├── D.mp3
│   └── E.mp3
└── README.md
```

## Limitations

This project is intended for small-scale exploratory research.

The current client-side JSONBin integration has limitations related to API credential exposure and concurrent data updates. Additional backend security and data-integrity safeguards are recommended before broader deployment.

## Project Status

**Research Prototype — Core Features Tested**

Audio playback, response submission, vote visualization, and CSV export have undergone basic functional testing.

---

<div align="center">

*Music Perception · Listening Preferences · Exploratory Research*

</div>

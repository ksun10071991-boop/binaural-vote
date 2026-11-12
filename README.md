# Binaural Beats Listening & Voting Survey

A lightweight web-based research tool for collecting subjective listening preferences across five binaural beat audio samples.

**[Launch Listening Survey](https://ksun10071991-boop.github.io/binaural-vote/)**

## Overview

This project provides a simple, browser-based interface for comparing five short binaural beat audio samples. Participants listen using stereo headphones and select the sample they prefer based on subjective listening experience.

The application supports audio playback, preference voting, persistent data storage, and an access-controlled results dashboard.

## Features

- **Audio comparison:** Five 5-second MP3 samples with replay controls.
- **Preference voting:** Participants select one preferred sample from options A–E.
- **Duplicate-vote handling:** Browser-based submission tracking and a persistent participant identifier.
- **Persistent storage:** Responses are stored in a Cloudflare D1 SQLite database.
- **Results dashboard:** Authorized researchers can view vote counts and percentages, with automatic refresh every five seconds.

## Audio Stimuli

| Sample | Binaural Beat Frequency |
|---|---|
| A | 10 Hz |
| B | 0.25 Hz |
| C | 40 Hz |
| D | 6 Hz |
| E | 12 Hz |

## Technology Stack

| Component | Technology |
|---|---|
| Frontend | HTML, CSS, JavaScript |
| Static Hosting | GitHub Pages |
| Backend API | Cloudflare Workers |
| Database | Cloudflare D1 (SQLite) |

## Research Scope

This tool is intended for exploratory listening-preference assessment and audio stimulus evaluation.

The survey measures **subjective preference**, not physiological entrainment, clinical efficacy, or therapeutic outcomes.

## Project Status

Functional prototype deployed for preliminary testing and exploratory data collection.

## Future Development

Potential improvements include expanded subjective rating scales, randomized audio presentation order, and structured data export.

## Research Context

Developed as part of exploratory work on auditory stimulation, binaural beats, and subjective listening experience.

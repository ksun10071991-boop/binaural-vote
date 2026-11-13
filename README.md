Bianural Beats Preference Survey
A lightweight, web-based research tool designed to collect subjective music preferences across different age groups and genders.

The platform supports audio playback, participant response collection, real-time vote visualization, and CSV data export. It is intended for exploratory research on music perception and preference, with potential applications in sleep-related audio design and product development.

Features

Audio Playback — Listen to five audio samples (A–E), with unlimited replay.

Participant Information — Collect age and gender information.

Preference Survey — Allow participants to select their preferred audio sample.

Data Storage — Store individual responses using JSONBin.

Real-Time Results — Display vote counts and percentage distributions.

CSV Export — Export individual responses for further analysis in Excel, R, or Python.

Responsive Interface — Support desktop and mobile browsers.

Live Demo

Take the Survey

View Results

The results page is intended for research personnel.

Technology Stack

Component

Technology

Frontend

HTML5, CSS3, JavaScript

Hosting

GitHub Pages

Data Storage

JSONBin

Data Format

JSON

Data Export

CSV

Data Structure

Each survey submission is stored as an individual record.

{
  "id": "unique-response-id",
  "age": 35,
  "gender": "Female",
  "choice": "A",
  "time": "2026-11-13T05:30:00.000Z"
}

The gender field is stored using the Chinese values 男 and 女 in the current implementation.

Field

Description

id

Unique response identifier

age

Participant age in years

gender

Participant gender

choice

Preferred audio sample (A–E)

time

Submission timestamp (UTC)

Research Applications

The collected data can support exploratory analyses of:

Overall preference distributions across audio samples.

Music preferences across age groups.

Gender-related differences in listening preferences.

Potential associations between demographic characteristics and audio preferences.

The survey is designed for descriptive and exploratory analysis rather than clinical assessment.

Project Structure

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

Limitations

This project is a research prototype intended for small-scale exploratory surveys.

The current implementation uses client-side JSONBin API requests. Concurrent submissions may result in overwritten records, and client-side API credentials do not provide secure access control.

The platform should not be used for sensitive data collection or large-scale public deployment without additional backend security and data-integrity improvements.

Project Status

Research Prototype — Functional Testing Completed

Core features, including audio playback, response submission, vote visualization, and CSV export, have undergone basic functional testing.

Further improvements may include enhanced data security, concurrent submission handling, and additional statistical visualization.

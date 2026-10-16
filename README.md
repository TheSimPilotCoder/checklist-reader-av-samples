# Checklist Reader - samples for antivirus vendors

This repository exists only to give antivirus laboratories a **direct download** of builds that a
scanner reported, so they can review a suspected false positive. It contains no source code.

Checklist Reader is free software for Microsoft Flight Simulator 2024 by "SimFlightChris":
a voice-controlled checklist tool. Regular users download it from FlightSim.to:

- Checklist Reader: https://flightsim.to/addon/96054/checklist-reader-voice-controlled-checklist-tool-beta-v1-0-0
- Checklist Library Extensions: https://flightsim.to/addon/114714/checklist-reader-library-extensions

## How the samples are stored

- One [release](../../releases) per reported version, tagged `v<Checklist Reader version>`.
- Every file is a ZIP archive protected with the password **`infected`**, as laboratories expect.
- The release notes list the file inside each archive with its SHA-256 and its VirusTotal report,
  so you can verify that you are looking at exactly the file that was reported.

Direct download links have the form

    https://github.com/TheSimPilotCoder/checklist-reader-av-samples/releases/download/<tag>/<file>.zip

## Contact

Please reply to the false-positive report you received from us, or open an issue in this repository.

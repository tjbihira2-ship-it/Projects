# Malicious Process Analyzer

This report documents a defensive Windows process-triage workflow that hashes running executables and checks their SHA-256 hashes against VirusTotal for analyst review.

## Workflow described

1. A PowerShell script collects process details and calculates executable hashes.
2. A Python script checks the hashes against VirusTotal and formats the results as JSON.

The report discusses CSV and JSON outputs, API rate limits, and handling processes that cannot be accessed. The scripts themselves are not included in this repository.

## Report

See [Malicious Process Analyzer.docx](Malicious%20Process%20Analyzer.docx) for the design, implementation discussion, and reflection.

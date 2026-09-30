# Retell AI Topic 3 — Voices, Speech Synthesis & Pronunciation

## Overview

This repository documents the Retell AI Topic 3 assessment for an AI Customer Support Voice Agent, focused on speech synthesis, voice settings, pronunciation, expressive delivery, multilingual configuration, live testing, and call/latency evidence.

## Agent Configuration

| Setting | Value |
|---|---|
| Workspace | my-project |
| Agent | AI Customer Support Agent |
| Agent Type | Single-Prompt Agent |
| Model | GPT 5.6 Terra |
| Voice | Cimo |
| Voice ID | retell-Cimo |
| Speech Speed | 1.00 |
| Expressive Mode | Enabled |
| Volume | Normal / Middle |
| Background Sound | None |
| Languages | English (US), English (India), Hindi (India) |

## Pronunciation Dictionary

The brand name **Retell AI** is configured with a custom IPA pronunciation:

- **Word:** Retell AI
- **Alphabet:** IPA
- **Phoneme:** `riːˈtɛl eɪ aɪ`

The saved pronunciation value uses the IPA text without leading or trailing slash delimiters.

## Multilingual Configuration

The agent is configured with:

- English (US) — `en-US`
- English (India) — `en-IN`
- Hindi (India) — `hi-IN`

The submitted live recording did not separately validate spoken output in every configured locale.

## Live Test & Loom Evidence

A live Retell interaction was recorded through Loom. The test covered the greeting, a request about Retell AI, a request to repeat the company name, a password-reset support question, an interruption attempt, and call closing.

### Important Test Note

During the recorded test, the agent did **not** repeat the phrase “Retell AI” when asked for the company name. Therefore, the pronunciation rule is documented as configured, but spoken pronunciation was **not conclusively validated** by the submitted recording.

## Latency & Call Logs

Existing Retell call-log evidence was reviewed as baseline data. These figures predate some final Topic 3 configuration changes and are therefore treated as baseline evidence.

| Metric | Observed |
|---|---:|
| LLM latency p50 | 827 ms |
| LLM latency p95 | 1555 ms |
| TTS latency p50 | 162 ms |
| TTS latency p95/p99 | 204 ms |
| ASR latency p50 | 223 ms |
| ASR latency p95 | 437 ms |
| E2E latency p50 | 1566 ms |
| E2E latency p95 | 2435 ms |
| E2E latency p99 | 2485 ms |
| Existing call duration | ~117 seconds |
| Existing call status | Successful |

## Evidence

This repository contains the Topic 3 assessment PDF and Retell configuration screenshots submitted for the LMS assessment.

## Assessment Checklist

| Requirement | Status |
|---|---|
| Speech synthesis provider selected | PASS |
| Cimo voice configured | PASS |
| Speech rate configured | PASS |
| Pitch tuned | NOT AVAILABLE — not exposed |
| Pronunciation dictionary created | PASS |
| Custom IPA pronunciation configured | PASS |
| Expressive Mode enabled | PASS |
| English (US) configured | PASS |
| English (India) configured | PASS |
| Hindi (India) configured | PASS |
| Live test recorded | PASS |
| Brand pronunciation validated by live speech | NOT CONCLUSIVELY VALIDATED |
| Natural voice quality verified | PARTIAL |
| Multilingual speech live-tested | NOT TESTED |
| Call/latency evidence reviewed | PASS / baseline |

## Deliverables

- `Retell_AI_Topic_3_Assessment_Documentation.pdf`
- Retell configuration screenshots
- Loom live-test evidence

This repository is the technical evidence and documentation package for the Retell AI Topic 3 LMS assessment.

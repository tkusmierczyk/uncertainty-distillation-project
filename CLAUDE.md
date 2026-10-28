# Project notes

Weekly research meetings (Tomasz, Srijith) with students Sajid (EnD² ensemble distillation on CIFAR-10 with auxiliary/noisy data) and Anushta (uncertainty distillation for LLM summarization).

- `meetings/`: transcripts (`.txt`), audio (raw `.flac` are in `raw_recordings/`), and AI-generated summaries. Transcript speaker labels are unreliable; attribute statements by content. Common garbles: "Samsung" = SAMSum, "delicia"/"deletion"/"dish" = Dirichlet, "C410"/"C4100" = CIFAR-10/100, "E and D square" = EnD².
- `meetings/Screenshots/`: slides shown in meetings, named by date; the result tables are there. meetings usually start about full hour so based on that the Screenshots can be roughly matched with the transcripts.
- `meetings/meetings 2025-01 - 2026-09.html` / `meetings/meetings 2025-01 - 2026-09.pdf` - notes from older meetings.

## The previous paper is only a starting point

`previous_paper.pdf` (Harsha's ECML 2026 paper on evidential knowledge distillation for LLM classification) is where the project started, not a reference for the current work. Its setup and explanations may not apply. For example, it explains students beating the teacher by early stopping, but Anushta's setup has no early stopping. Do not use the paper to explain current results; reason from the current experiments.

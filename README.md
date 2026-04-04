# NLP Project: Aphasia Severity Classification

This project uses AphasiaBank CHAT transcripts to model aphasia severity (WAB-AQ) using NLP features.

## Preprocessing steps
- Loaded CHAT (.cha) files using pylangacq
- Extracted participant speech (*PAR only)
- Isolated the "Cat" picture description task using @G markers
- Computed features:
  - Mean Length of Utterance (MLU)
  - Type-Token Ratio (TTR)
  - Function-word ratio
- Extracted AQ scores from transcript headers
- Created binary severity labels

## Notes
Raw AphasiaBank data is not included due to access restrictions.

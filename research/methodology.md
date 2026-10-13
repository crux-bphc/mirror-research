# MIRROR Anonymization Methodology

## Purpose
MIRROR prepares survey records for research use by removing direct identifiers and publishing a reduced dataset.

## Data handling
- Replace direct identifiers with stable record tokens.
- Retain selected attributes needed for analysis.
- Restrict identity-linked records to the research archive.
- Publish only the reduced survey dataset.

## Re-identification risk
Removing names does not guarantee anonymity. Combinations of attributes such as year, department, hostel, club, and project may identify a person when joined with another dataset. Stable tokens can also enable linkage across surveys.

## Validation requirements
1. Check that tokens are not reused across unrelated survey records.
2. Test whether combinations of quasi-identifiers uniquely distinguish records.
3. Confirm that timestamps and location-related fields do not expose identities unnecessarily.
4. Document residual risks before publication.

## Supervisor review
Review note recorded 13 October 2026, 15:20 IST (+05:30): “The reduced dataset appears anonymous, but the quasi-identifier combinations need explicit testing before publication.”

Review outcome: publication remains on hold until the quasi-identifier risks are tested.

## Limitations
Synthetic tests can demonstrate potential weaknesses but do not establish that a real-world dataset is safe. Publication should be withheld until identified risks are reviewed.

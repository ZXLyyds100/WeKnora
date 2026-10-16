# PR review evidence — October 17, 2026

Screenshots for Tencent/WeKnora#4392 at 648ae67edec6cff64af6d4ceff85981dc37ce588.
Actual production Vue/TDesign frontend and Go backend, real auth and SQLite, isolated local fixture accounts.
A local fixed-response model supplies chat and embeddings; no paid or external model calls.
Before-clear means before performing the cleanup action in the updated application, not the pre-feature revision.
The confirmation shows that indexing will pause, original conversations/messages remain, and old messages are not automatically reindexed.
After-clear shows the detached index and unlocked model selector; persisted message equality and other-workspace/ordinary-KB isolation were separately verified.
All displayed accounts, model labels, and conversations are disposable local test fixtures.

This isolated evidence branch is not included in the upstream feature PR diff.
Images are linked from immutable commit URLs so later branch changes cannot alter the evidence.

| Image | SHA-256 |
| --- | --- |
| weknora/before-clear.png | 00c0df11970dca0b01113cb797e595ff9e6416b9acfa6caeaf17273e1c2f7860 |
| weknora/confirmation.png | 666a504763e7cff0e4db77281e223d1bc14eb1dc910bfe5ad121870c06c6741a |
| weknora/after-clear.png | 5c489db10f402414707ba0e67e1ce017d3e1888fb6eb6b300e35e70358a8861c |
| weknora/preserved-messages.png | 79935861fcd2f7cd975f33e97221952c9cc657fcdceb4943e129b62940034ca8 |

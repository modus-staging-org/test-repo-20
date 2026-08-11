# Drop the unused legacy adapter

Requests could previously hang forever when the upstream stopped responding. This adds an explicit timeout and surfaces it as a typed error.

Change #1 of 3 on branch `pr/20260811-121032-1-drop-the-unused-legacy-adapter`.

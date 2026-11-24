# poster-judge-images

Rendered academic-poster images (generated from papers in the Paper2Poster benchmark) used as inputs to LLM-judge
experiments. `j2400q80/` holds 2400 px (long side) JPEGs at quality 80; each file is named by the first 24 hex digits
of its SHA-256, so a URL pinned to a commit always serves the exact bytes that were judged.

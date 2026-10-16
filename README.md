## Hi, I'm Jarod

Data Science senior at UCF (graduating Spring 2027). I sit with the people who will use what I build, find the step that's costing them time, and ship the AI tool that fixes it.

Open to forward-deployed, applied AI and data roles.
[jarodferkin.com](https://jarodferkin.com) · [LinkedIn](https://www.linkedin.com/in/jarod-ferkin-740189201/) · jtferkin@gmail.com

### What I've built

**[barnManager](https://barnmanager.fly.dev)**: operations platform for a working horse barn, live in production
In plain terms: the barn forwards a vet invoice or snaps a photo of paperwork, and Claude turns it into the right horse's record. Nothing posts until a person approves it in a review queue.
- Claude Haiku runs server-side, so API keys never reach the browser
- "Ask the barn": plain-language questions answered only from that barn's own records
- Wrote an attack script that tries to cross between barns as every type of user, found and fixed 9 issues, and the code passes all 53 checks
- React 19, TypeScript, PocketBase, Fly.io · try the public demo, no sign-up

**[pigeon](https://herodthegreater.github.io/pigeon/)**: model-compression research tool and teaching site
In plain terms: it shrinks a general AI vision model into the smallest version that can still spot birds, and measures exactly what each step costs.
- Cut a YOLOv8n detector's parameters 43% and compute 35%; a ~12% prune plus fine-tuning restored 91% of its original accuracy (mAP@50)
- The live site lets anyone shrink a real model in their browser, with 43 runnable method pages and 10 coding lessons
- PyTorch, FastAPI, ONNX Runtime Web, Astro

**[predicting-song-failure](https://github.com/herodthegreater/predicting-song-failure)**: which song features predict a flop, genre by genre
- 114K Spotify tracks, one model per genre: Random Forest reached a cross-validated ROC-AUC of 0.63 to 0.88 (0.88 for Latin), against a Naive Bayes baseline of 0.58 to 0.62
- Python, scikit-learn, pandas

### Tools

Python · TypeScript · SQL · Claude API · PyTorch · scikit-learn · pandas · React · FastAPI · PocketBase · SQLite · DuckDB · Docker · Fly.io

***********************************************************************************************************************************************
***********************************************************************************************************************************************

# Status: Concept sketch

pylon doesn't do anything yet! I'm hosting this README to talk about it with friends, and as a code-generation target for LLMs.

***********************************************************************************************************************************************
***********************************************************************************************************************************************


# pylon

Pylon is a framework for rapid semi-consensus group decision-making.

Pylon features a slapdash attempt at an agent which can do the following:

* Identify decisions to make using end-of-day and end-of-week surveys / direct conversations with team members;
* Facilitate rapid consensus using NLP (collect everyone's thoughts, see if they agree);
* Autonomously schedule meetings to work through areas of contention;
* Share out narrative history which summarizes the evolution of group thinking;
* Maintain living documents representing consensus opinion / current working practices ("Thesis");
* Maintain ongoing Bayesian estimates ("Estimates").
* Work cooperatively with human facilitators (referring issues to them / taking instructions from them).

Pylon follows Principle 6 and is down to merge into other frameworks. This repo is a vibe-coded early prototype example, specifically not designed for scale or generalizability. It's an R&D spike — a brief targeted exploration to see what's possible. The goal is to host a Pylon for my friends and I to make decisions with, and you can too! and then if it works we try to scale it.

Business decisions are obviously made by a Pylon team; if it works, our starting Thesis is to ICO (raise requirement currently Estimated at $500K), build an MVP, and offer an open pricing plan of $1/participant/month to for-profit companies, $0.10/participant/month to non-profits, and $0.001/participant/month to Principle 6 cooperatives. Target revenue is $2M/year; expected revenue is not Estimated yet (will depend entirely on how well it works, obvi!).

Pylon is designed with data sovereignty in mind, geared primarily toward local models on NVIDIA CUDA (so the data is never shared with anyone). PRs welcome to add API integration or we'll add it if/when enough people ask for it! Pylon is testing using DeepSeek R1, which will run on the new Mac Studio for about $10K (easy choice). Otherwise we intend to support NVIDIA CUDA down to a minimum 24 GB VRAM, which is commonly available on gaming-grade graphics controllers and Apple Silicon laptops (our dev/build rig runs R1 Distill Qwen 32B in 24 GB VRAM and cost $2K in parts (custom eBay build)).

Pylon will eventually support blockchain in some capacity; for now we depend on small group size and high trust metrics to feel safe running a local database.

Pylon is being incubated by the [Enspiral network](https://www.enspiral.com/).

Pull requests are welcome, say hi!

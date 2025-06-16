# pylon

Pylon is a framework for rapid semi-consensus group decision-making.

Pylon features a slapdash attempt at an agent which can do the following:
* Identify decisions to make using end-of-day and end-of-week surveys / direct conversations with team members;
* Facilitate rapid consensus using NLP (collect everyone's thoughts, see if they agree);
* Autonomously schedule meetings to work through areas of contention.

Pylon is currently pre-alpha / not ready for public use.

Pylon follows Principle 6 and is down to merge into other frameworks. It's really more of a conversation piece and an early prototype. I'm hosting a Pylon for my friends and I to make decisions with, and you can too!

For-profit companies will be able to subscribe to Pylon as a service; we currently follow a simple open pricing plan of $1/participant/month to for-profit companies, $0.10/participant/month to non-profits, and $0.001/participant/month to Principle 6 cooperatives.

Pylon is with data sovereignty in mind, targeted primarily for usage with local models; PRs welcome to add API integration or we'll add it if enough people ask for it. Pylon is best run with DeepSeek R1, which will run on the new Mac Studio for about $10K (easy choice). Otherwise we intend to support NVIDIA CUDA down to a minimum 24 GB VRAM, which is commonly available on gaming-grade graphics controllers and Apple Silicon laptops.

Pylon will eventually support blockchain in some capacity; for now we use high trust metrics and a local database.

Pylon is being incubated by the [Enspiral network](https://www.enspiral.com/).

Pull requests are welcome, say hi!

# Arcueil

**We are Bayesians. We come from a long lineage — Laplace, Gauss, Jaynes — and we are building its next instrument.**

In 1807, on Berthollet's estate in the village of Arcueil outside Paris, a small society began meeting on weekends: Laplace and Berthollet presiding, and around them the young scientists they mentored — Gay-Lussac, Biot, Arago, Malus, Poisson. The Société d'Arcueil had no charter beyond doing science carefully and together, and it published what it learned as the *Mémoires de la Société d'Arcueil*. This organization is named for that society, and works the same way: curate what the community actually knows, grade the evidence, publish the memoirs.

## The lineage

Bayes left a theorem; **Laplace** made it a method. He rediscovered inverse probability independently in 1774 and spent four decades applying it — to the mass of Saturn, the stability of the solar system, the ratio of births, the credibility of witnesses — insisting all along that probability theory is "nothing but common sense reduced to calculation."

**Gauss** made it a tool. His 1809 derivation of least squares is, read plainly, a Bayesian argument: a normal law for the errors, a uniform prior over the unknowns, and the estimate taken at the posterior's peak. Every regression since is downstream of that page.

Then came a long winter, when inverse probability fell from fashion — and the flame passed through hands that refused to let it gutter: **Jeffreys**, who rebuilt it as a working scientist's theory of inference; **Cox**, who proved that any consistent calculus of plausibility *must* be probability; **de Finetti**, who rooted it in exchangeability and coherence; **Savage**, who gave it decision-theoretic teeth.

**Jaynes** made it a logic. Probability as the extension of deductive reasoning to incomplete information — and he opened *Probability Theory: The Logic of Science* not with axioms but with a design brief: build a **robot** that reasons plausibly and consistently from its prior information.

Then computation made it a practice: Metropolis and Hastings, the Gibbs sampler, Gelfand and Smith; Hamiltonian Monte Carlo, born in lattice field theory and brought home to statistics; NUTS, Stan, PyMC, BlackJAX. And with practice came something the textbooks never fully captured — *craft*. Which parameterization funnels and which doesn't. What a divergence is trying to tell you. When a prior is load-bearing. Two centuries after Laplace, the theory is written down, but the craft lives scattered across forum threads, case studies, and the memories of practitioners.

## What we build

**[memoires](https://github.com/arcueil/memoires)** — the craft, written down. A curated, evidence-graded, contradiction-aware catalog of Bayesian modeling knowledge, distilled from tens of thousands of practitioner discussions and expert case studies, reviewed adversarially, and organized the way Laplace's society organized its science: a small set of principles you can actually read, over a deep, searchable record of what works — and what doesn't, and under which conditions.

**[jaynes-robot](https://github.com/arcueil/jaynes-robot)** — the reasoner that reads them. Jaynes asked for a robot that reasons from organized prior information; large language models finally make the design brief buildable. The Mémoires are its priors.

---

*« La théorie des probabilités n'est, au fond, que le bon sens réduit au calcul. »* — Laplace

**Common sense, reduced to calculation.**

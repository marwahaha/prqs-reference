# Pseudorandom quantum states (PRQS)


## All the papers
Let me start by collecting papers that define PRQS, since there are so many definitions!

* The original paper by [JLS18](https://eprint.iacr.org/2018/544.pdf). 
* [Kretschmer21](https://arxiv.org/abs/2103.09320)'s quantum oracle that shows PRU (pseudorandom unitaries, and thus PRQS) exist even when $$BQP = QMA$$. Also shows that $$BQP = PP$$ implies PRQS do not exist.
* [AQY21](https://arxiv.org/abs/2112.10020), then [AGQY22](https://arxiv.org/abs/2211.01444) talk about pseudorandom function-like states. There is also some related work in [MY22a](https://arxiv.org/pdf/2112.06369.pdf) but I can't parse all the differences.
* [KQST22](https://arxiv.org/abs/2212.00879) surprisingly improves this to a classical oracle (even a random oracle) where $$P = NP$$ but 1-PRQS exist. This uses Forrelation.
* [BFGVZ22](https://arxiv.org/abs/2211.00747) show that assuming OWF (one-way functions), you can get PRQS with entanglement of any $$\omega(\log n) \le S \le n$$ that are all computationally indistinguishable from each other. They call these *pseudoentangled*, since there are states that "look entangled" but are not that entangled. (This is tight; if $$S = O(\log n)$$, then a swap test can distinguish PRQS from random states.)
* [GIKL22](https://arxiv.org/abs/2209.14530) show that that $$\omega(\log n)$$ $T$-gates are required to prepare computationally pseudorandom quantum states.





### Implications for more complex cryptographic protocols
* [GJMZ22](https://arxiv.org/abs/2210.05138) describe what it means to *commit* to a quantum states.
* [MY21](https://arxiv.org/abs/2112.06369) extends Kretschmer's oracle to show quantum commitments can exist even without OWF.
* [HMY22](https://arxiv.org/abs/2210.05978) relate this to quantum public-key encryption.
* [AHY23](https://arxiv.org/abs/2301.09236) relate this to quantum money.

### Implications for AdSCFT
* [BFV19](https://arxiv.org/abs/1910.14646) show that there is a way to view pseudorandomness as an essential element in AdSCFT dictionary within black holes.
* [Brakerski22](https://arxiv.org/abs/2211.05491) relates this to black-hole radiation decoding.

### Other papers I don't know well enough to summarize:
* [Sattath22](https://arxiv.org/abs/2210.14265)'s review on uncloneable cryptography.
* [BCQ22](https://arxiv.org/abs/2209.04101) and the relationship to EFI pairs
* [Doosti22](https://arxiv.org/abs/2210.17545)'s thesis on uncloneability.
* [ALLZZ20](https://arxiv.org/pdf/2004.09674.pdf)'s approaches for quantum copy-protection.
* [MY22b](https://arxiv.org/pdf/2210.03394.pdf) on one-way state generators.
* [DMP22](https://eprint.iacr.org/2020/1508) combinatorial approach to quantum pseudorandom functions.
* [CX22](https://eprint.iacr.org/2022/1323.pdf) have variants of pseudorandom quantum state generators.
* [Zhandry21](https://dl.acm.org/doi/abs/10.1145/3450745) has a new technique on constructing quantum random functions.
* [AKL23](https://arxiv.org/abs/2302.01874) new work on cloning games and uncloneable primitives

## What's next?

I think it would be nice to define the following:
* Pseudorandom quantum states
* Pseudorandom quantum state generators
* (classical and quantum) pseudorandom functions and generators
* pseudorandom unitaries
* single-copy security and multi-copy security

Also, the papers use slightly different definitions, are they all comparable? At least for a few papers, we can write them out and see how they differ.

Then it would be nice to start listing some open questions. Then we could send it around and ask if people have comments.

---

More to add? Email me at [kmarw@uchicago.edu](mailto:kmarw@uchicago.edu).

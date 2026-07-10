# Hi, I'm Maurice 👋

I'm a first-year PhD student in **Computing + Mathematical Sciences** at **Caltech**, working in [Anima Anandkumar's AI + Science lab](https://tensorlab.cms.caltech.edu/users/anima/). I am grateful to be fully funded by the Kortschak fellowship.

## Research Interests

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&pause=100&speed=30&color=FFFFFF&width=500&height=25&lines=%F0%9F%A7%AA%20ML%20for%20Quantum%20Chemistry;%F0%9F%94%AC%20ML%20for%20Materials%20Science;%E2%9A%9B%EF%B8%8F%20ML%20for%20Quantum%20Many-Body%20Systems;%F0%9F%94%A2%20Scientific%20Machine%20Learning" alt="Typing SVG" />

## Open Source Contributions

**Quantum Chemistry & Materials Science**
- [Quantum ESPRESSO](https://gitlab.com/QEF/q-e): found and fixed a memory-alignment bug in the FFT backend that silently corrupted wavefunction transforms on optimized CPU builds, breaking correctness of the SCF calculation ([MR !2877](https://gitlab.com/QEF/q-e/-/merge_requests/2877))
- [tblite](https://github.com/tblite/tblite): fixed spin-polarized (open-shell) restarts silently discarding the converged wavefunction and re-running the full SCF from scratch instead of resuming ([PR #298](https://github.com/tblite/tblite/pull/298)); found and fixed an OpenMP symbol collision between the published wheel and PyTorch that corrupted SCF convergence when both were imported together ([PR #341](https://github.com/tblite/tblite/pull/341))

**Scientific Machine Learning**
- [Neural Operator](https://github.com/neuraloperator/neuraloperator): added GroupNorm support to the reference FNO implementation ([PR #715](https://github.com/neuraloperator/neuraloperator/pull/715))

**Systems**
- [CheriBSD](https://github.com/CTSRD-CHERI/cheribsd): closed a vulnerability in libc's allocator (jemalloc) where a narrowed pointer could bypass CHERI's hardware memory protection ([PR #2448](https://github.com/CTSRD-CHERI/cheribsd/pull/2448))

## Contact

- 🌐 Website: [mauricedhanisch.github.io](https://mauricedhanisch.github.io)
- 💼 LinkedIn: [mauricehanisch](https://www.linkedin.com/in/mauricehanisch)

---

*Feel free to reach out if you're interested in any of these topics!*

<!---
MauriceDHanisch/MauriceDHanisch is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

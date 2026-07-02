# Source Links for Manual Verification

This file lists every reference cited in `main.tex`, in the same order as the
`thebibliography` block, with links so each citation can be checked manually.

- **Canonical** = the official publisher / DOI / proceedings page (authoritative
  for authors, title, volume, pages, year). May be paywalled.
- **Free access** = a legitimate openly accessible copy (arXiv, open-access
  journal, author PDF, or proceedings), where one exists.
- **Access** = whether a freely readable full text is available.

This bibliography was written on 2026-07-02 for the *Data-Selective Machine
Learning Training Based on Statistical Weakspot Identification* paper. All links
were checked via web search on 2026-07-02. Please still verify them yourself
before submission, since links rot and mirrors change.

---

## [1] Hestness et al. 2017 — deep learning scaling is predictable (power-law learning curve)
- J. Hestness, S. Narang, N. Ardalani, G. Diamos, H. Jun, H. Kianinejad, M. M. A. Patwary, Y. Yang, and Y. Zhou, "Deep learning scaling is predictable, empirically," arXiv:1712.00409, 2017.
- Canonical / Free: https://arxiv.org/abs/1712.00409
- **Access: FREE (arXiv).**
- Cited in: Introduction (asymptotic power-law learning curve; diminishing returns in the late stages).

## [2] Sorscher et al. 2022 — beyond neural scaling laws via data pruning
- B. Sorscher, R. Geirhos, S. Shekhar, S. Ganguli, and A. S. Morcos, "Beyond neural scaling laws: beating power law scaling via data pruning," NeurIPS 2022 (Outstanding Paper).
- Canonical: https://proceedings.neurips.cc/paper_files/paper/2022/hash/7b75da9b61eda40fa35453ee5d077df6-Abstract-Conference.html
- Free: https://arxiv.org/abs/2206.14486
- **Access: FREE (arXiv + NeurIPS proceedings).**
- Cited in: Introduction (diminishing returns; selective sampling effective); Sec. II-A (data pruning as compression); Sec. II-B (pruning needs a large, redundant dataset).

## [3] Ovadia et al. 2019 — predictive uncertainty under dataset shift
- Y. Ovadia, E. Fertig, J. Ren, Z. Nado, D. Sculley, S. Nowozin, J. V. Dillon, B. Lakshminarayanan, and J. Snoek, "Can you trust your model's uncertainty? Evaluating predictive uncertainty under dataset shift," NeurIPS 2019.
- Free: https://arxiv.org/abs/1906.02530
- Canonical (NeurIPS): https://proceedings.neurips.cc/paper/2019/hash/8558cb408c1d76621371888657d2eb1d-Abstract.html
- **Access: FREE (arXiv + NeurIPS proceedings).**
- Cited in: Introduction (models become unreliable in under-represented regions; definition of a weakspot).

## [4] Settles 2009 — active learning literature survey
- B. Settles, "Active learning literature survey," Univ. Wisconsin–Madison, Dept. Comput. Sci., Tech. Rep. 1648, 2009.
- Canonical / Free: https://burrsettles.com/pub/settles.activelearning.pdf
- Mirror: https://research.cs.wisc.edu/techreports/2009/TR1648.pdf
- **Access: FREE (author copy + institutional mirror).**
- Cited in: Introduction (selective sampling; active learning assumes an unlabelled pool + oracle); Sec. II-A (active learning); Sec. II-B (acquisition loop cannot run on a fully-labelled set).

## [5] Cohn, Ghahramani & Jordan 1996 — active learning with statistical models
- D. A. Cohn, Z. Ghahramani, and M. I. Jordan, "Active learning with statistical models," J. Artif. Intell. Res., vol. 4, pp. 129–145, 1996.
- Canonical: https://www.jair.org/index.php/jair/article/view/10158
- Free: https://arxiv.org/abs/cs/9603104
- **Access: FREE (JAIR open access + arXiv).**
- Cited in: Sec. II-A (foundational active-learning formulation).

## [6] Sener & Savarese 2018 — active learning core-set approach
- O. Sener and S. Savarese, "Active learning for convolutional neural networks: A core-set approach," ICLR 2018.
- Canonical (OpenReview): https://openreview.net/forum?id=H1aIuk-RW
- Free: https://arxiv.org/abs/1708.00489
- **Access: FREE (arXiv + OpenReview).**
- Cited in: Sec. II-A (diversity / coverage-based selection; core-set compression).

## [7] Bengio et al. 2009 — curriculum learning
- Y. Bengio, J. Louradour, R. Collobert, and J. Weston, "Curriculum learning," ICML 2009, pp. 41–48.
- Canonical (ACM): https://doi.org/10.1145/1553374.1553380
- Free: https://www.semanticscholar.org/paper/Curriculum-learning-Bengio-Louradour/8de174ab5419b9d3127695405efd079808e956e8
- **Access: FREE copies widely available (Semantic Scholar / author copies); canonical ACM page may be paywalled.**
- Cited in: Introduction (curriculum re-orders existing data); Sec. II-A (curriculum learning); Sec. II-B (re-ordering does not add information).

## [8] Kumar, Packer & Koller 2010 — self-paced learning
- M. P. Kumar, B. Packer, and D. Koller, "Self-paced learning for latent variable models," NeurIPS 2010, pp. 1189–1197.
- Canonical: https://proceedings.neurips.cc/paper/2010/hash/e57c6b956a6521b28495f2886ca0977a-Abstract.html
- Free: https://ai.stanford.edu/~bpacker/selfPacedLVM.pdf
- **Access: FREE (NeurIPS proceedings + author PDF).**
- Cited in: Introduction (self-paced re-orders existing data); Sec. II-A (self-paced learning couples ordering to training state); Sec. II-B.

## [9] Shrivastava, Gupta & Girshick 2016 — online hard example mining (OHEM)
- A. Shrivastava, A. Gupta, and R. Girshick, "Training region-based object detectors with online hard example mining," CVPR 2016, pp. 761–769.
- Canonical (CVF): https://openaccess.thecvf.com/content_cvpr_2016/html/Shrivastava_Training_Region-Based_Object_CVPR_2016_paper.html
- Free: https://arxiv.org/abs/1604.03540
- **Access: FREE (arXiv + CVF open access).**
- Cited in: Sec. II-A (hard-example mining); Sec. II-B (risk of repeatedly emphasising the same high-loss points).

## [10] Katharopoulos & Fleuret 2018 — deep learning with importance sampling
- A. Katharopoulos and F. Fleuret, "Not all samples are created equal: Deep learning with importance sampling," ICML 2018, pp. 2525–2534.
- Canonical (PMLR): https://proceedings.mlr.press/v80/katharopoulos18a.html
- Free: https://arxiv.org/abs/1803.00942
- **Access: FREE (arXiv + PMLR).**
- Cited in: Introduction (selective sampling effective); Sec. II-A (importance sampling; variance reduction); Sec. II-C (reweighting to correct altered sampling).

## [11] Mindermann et al. 2022 — prioritized training (RHO-LOSS)
- S. Mindermann, J. M. Brauner, M. T. Razzak, M. Sharma, A. Kirsch, W. Xu, B. Höltgen, A. N. Gomez, A. Morisot, S. Farquhar, and Y. Gal, "Prioritized training on points that are learnable, worth learning, and not yet learnt," ICML 2022.
- Canonical (PMLR): https://proceedings.mlr.press/v162/mindermann22a.html
- Free: https://arxiv.org/abs/2206.07137
- **Access: FREE (arXiv + PMLR).**
- Cited in: Sec. II-A ("most worth learning" refinement of hard mining); Sec. II-B; Sec. II-C (training-state staleness; noisy vs. informative points).

## [12] Farquhar, Gal & Rainforth 2021 — statistical bias in active learning
- S. Farquhar, Y. Gal, and T. Rainforth, "On statistical bias in active learning: How and when to fix it," ICLR 2021.
- Canonical (OpenReview): https://openreview.net/forum?id=JiYq3eqTKY
- Free: https://arxiv.org/abs/2101.11665
- **Access: FREE (arXiv + OpenReview).**
- Cited in: Introduction (fully-labelled setting); Sec. II-B; Sec. II-C (selective training biases the model and risk estimates; reweighting correction).

## [13] Ash et al. 2020 — deep batch active learning (BADGE)
- J. T. Ash, C. Zhang, A. Krishnamurthy, J. Langford, and A. Agarwal, "Deep batch active learning by diverse, uncertain gradient lower bounds," ICLR 2020.
- Canonical (OpenReview): https://openreview.net/forum?id=ryghZJBKPS
- Free: https://arxiv.org/abs/1906.03671
- **Access: FREE (arXiv + OpenReview).**
- Cited in: Introduction (redundant-batch instability in the low-data regime); Sec. II-A (hybrid uncertainty + diversity); Sec. II-C (batch redundancy / diversity).

## [14] Kirkpatrick et al. 2017 — overcoming catastrophic forgetting (EWC)
- J. Kirkpatrick, R. Pascanu, N. Rabinowitz, J. Veness, G. Desjardins, A. A. Rusu, K. Milan, J. Quan, T. Ramalho, A. Grabska-Barwinska, D. Hassabis, C. Clopath, D. Kumaran, and R. Hadsell, "Overcoming catastrophic forgetting in neural networks," Proc. Nat. Acad. Sci., vol. 114, no. 13, pp. 3521–3526, 2017.
- Canonical (PNAS): https://www.pnas.org/doi/10.1073/pnas.1611835114
- Free: https://arxiv.org/abs/1612.00796
- **Access: FREE (arXiv; PNAS article also openly readable).**
- Cited in: Sec. II-C (catastrophic forgetting under a shifting training distribution).

## [15] McCloskey & Cohen 1989 — catastrophic interference (original)
- M. McCloskey and N. J. Cohen, "Catastrophic interference in connectionist networks: The sequential learning problem," Psychol. Learn. Motiv., vol. 24, pp. 109–165, 1989.
- Canonical: https://doi.org/10.1016/S0079-7421(08)60536-8
- **Access: PAYWALLED (book chapter; no legitimate open-access full text located). Verify via a library.**
- Cited in: Sec. II-C (original description of catastrophic interference).

## [16] Chen et al. 2022 — cold start problem in vision active learning
- L. Chen, Y. Bai, S. Huang, Y. Lu, B. Wen, A. L. Yuille, and Z. Zhou, "Making your first choice: To address cold start problem in vision active learning," arXiv:2210.02442, 2022.
- Canonical / Free: https://arxiv.org/abs/2210.02442
- **Access: FREE (arXiv).**
- Cited in: Introduction (selection unstable in the low-data regime); Sec. II-C (cold-start problem; batch redundancy).

## [17] Companion weakspot-identification paper — prior work (this project)
- (author list and venue TBD) "Advanced methods for weakspot identification in regression models: From standard detectors to structured ensembles," 2025, unpublished.
- **Access: N/A — companion manuscript from the same author; not yet publicly released.**
- Cited in: Introduction (statistical weakspot-identification methods that the training pipeline is built on).
- **TODO:** fill in the author list and final publication venue once the companion paper is submitted/published, and mirror it in the `\bibitem{weakspotprior}` entry in `main.tex`.

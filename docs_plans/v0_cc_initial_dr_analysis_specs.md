# Deep Research Analysis Specs: Stauprimide & NDPK/NME2 Interaction (v0_cc)

**Date:** February 13, 2026
**Author:** tp53
**Target:** Scientific Review/Perspective Preprint
**Output:** `@out/v0_cc_scientific_prerint_on_detailed-stauprimide-ndpk-analysis.tex`

---

## 1. Scope and Framing

This preprint is a **review/perspective article** that integrates recent structural dynamics data on NDPK hexamers (Lim & Natarajan, 2024) with the established pharmacology of stauprimide as an NME2-targeting MYC suppressor (Bouvard et al., 2017). The paper proposes a structural hypothesis for stauprimide's mechanism and selectivity, clearly framed as a testable model requiring experimental validation.

**This is NOT an original computational study.** No molecular dynamics simulations, docking experiments, or binding free energy calculations were performed as part of this work. All quantitative data presented are from published sources and are explicitly attributed.

---

## 2. Primary Literature Sources

### Source A: Stauprimide Pharmacology
- **Bouvard C, et al.** "Small molecule selectively suppresses MYC transcription in cancer cells." *PNAS* 114(13):3497-3502, 2017. DOI: 10.1073/pnas.1702663114
- Full text ingested and verified.
- Key data: EC50 values (RXF 393: 610 nM, CAKI-1: 1004 nM, KG1A: 400 nM), in vivo xenograft efficacy, GSEA selectivity (only MYC_TARGETS_V1 and V2 enriched), nuclear exclusion mechanism, PK data (t1/2 ~4h, Cmax 1.85-2.09 uM at 20 mg/kg oral).

### Source B: NDPK Hexamer Dynamics
- **Lim YY & Natarajan KN.** "Modelling dynamics of human NDPK hexamer structure, stability and interactions." *bioRxiv* 2024.09.19.613900, 2024. DOI: 10.1101/2024.09.19.613900
- Full text ingested and verified. Review Commons manuscript (journal-agnostic peer review). Still preprint as of Feb 2026.
- Key data: MM/GBSA binding free energies for all homo/heterohexamer configurations, Arg27 mutagenesis, C-terminal truncation effects, Kpn loop dynamics, A1B5 heterohexamer stability (-172.39 kcal/mol).

### Source C: Clinical Relevance
- **Panja S, et al.** "Mechanism-centric regulatory network identifies NME2 and MYC programs as markers of Enzalutamide resistance in CRPC." *Nature Communications* 15(1):352, 2024. DOI: 10.1038/s41467-024-44686-5
- Verified via web search. Key finding: NME2-MYC co-upregulation predicts 5x reduced likelihood of enzalutamide benefit; MYCi975 + NME2 knockdown reverses resistance.

---

## 3. Complete Verified Citation Pool

19 citations, all verified by cross-referencing between the two primary papers and web searches. No citation is included unless it appears in at least one of the primary source papers or was independently verified via PubMed/web search.

| # | Authors | Title | Journal | Year | DOI | Verification |
|---|---------|-------|---------|------|-----|--------------|
| 1 | Bouvard C, et al. | Small molecule selectively suppresses MYC transcription in cancer cells | PNAS 114(13):3497-3502 | 2017 | 10.1073/pnas.1702663114 | Full text |
| 2 | Lim YY, Natarajan KN | Modelling dynamics of human NDPK hexamer structure, stability and interactions | bioRxiv 2024.09.19.613900 | 2024 | 10.1101/2024.09.19.613900 | Full text |
| 3 | Panja S, et al. | Mechanism-centric regulatory network identifies NME2 and MYC programs as markers of Enzalutamide resistance in CRPC | Nature Comms 15:352 | 2024 | 10.1038/s41467-024-44686-5 | Web verified |
| 4 | Zhu S, et al. | A small molecule primes embryonic stem cells for differentiation | Cell Stem Cell 4(5):416-426 | 2009 | 10.1016/j.stem.2009.04.001 | Cited in [1,2] |
| 5 | Abu-Taha IH, et al. | Targeting altered Nme heterooligomerization in disease? | Oncotarget 9(2):1492-1493 | 2018 | 10.18632/oncotarget.22716 | Cited in [2] |
| 6 | Thakur RK, et al. | NM23-H2 interaction with G-quadruplex DNA within c-MYC promoter NHE induces c-MYC expression | Nucleic Acids Res 37(1):172-183 | 2009 | 10.1093/nar/gkn919 | Cited in [1,2] |
| 7 | Postel EH, et al. | Mutational analysis of NM23-H2/NDP kinase identifies structural domains critical to recognition of a c-myc regulatory element | PNAS 93(14):6892-6897 | 1996 | 10.1073/pnas.93.14.6892 | Cited in [2] |
| 8 | Siddiqui-Jain A, et al. | Direct evidence for a G-quadruplex in a promoter region and its targeting with a small molecule to repress c-MYC transcription | PNAS 99(18):11593-11598 | 2002 | 10.1073/pnas.182256799 | Cited in [1] |
| 9 | Delmore JE, et al. | BET bromodomain inhibition as a therapeutic strategy to target c-Myc | Cell 146(6):904-917 | 2011 | 10.1016/j.cell.2011.08.017 | Cited in [1] |
| 10 | Tossounian MA, et al. | A unique mode of coenzyme A binding to the nucleotide binding pocket of human metastasis suppressor NME1 | Int J Mol Sci 24(11) | 2023 | 10.3390/ijms24119359 | Cited in [2] |
| 11 | Vieira PS, et al. | The role of the C-terminus and Kpn loop in the quaternary structure stability of NDK from Leishmania | J Struct Biol 192(3):336-341 | 2015 | 10.1016/j.jsb.2015.09.017 | Cited in [2] |
| 12 | Gilles AM, et al. | NDK from human erythrocytes: structural characterization of the two polypeptide chains | J Biol Chem 266(14):8784-8789 | 1991 | - | Cited in [2] |
| 13 | Karlsson A, et al. | NDK: investigation of intersubunit contacts by site-directed mutagenesis and crystallography | J Biol Chem 271(33):19928-19934 | 1996 | 10.1074/jbc.271.33.19928 | Cited in [2] |
| 14 | Boissan M, et al. | The NDPK/NME superfamily: state of the art | Lab Invest 98(2):164-174 | 2018 | 10.1038/labinvest.2017.137 | Cited in [2] |
| 15 | Casey SC, et al. | MYC regulates the antitumor immune response through CD47 and PD-L1 | Science 352(6282):227-231 | 2016 | 10.1126/science.aac9935 | Cited in [1] |
| 16 | Thakur RK, et al. | NME2-mediated suppression of lung cancer metastasis involves transcriptional regulation of vinculin | Nucleic Acids Res 42(18):11589-11600 | 2014 | 10.1093/nar/gku860 | Cited in [1] |
| 17 | Yang D, Hurley LH | Structure of the biologically relevant G-quadruplex in the c-MYC promoter | Nucleosides Nucleotides Nucleic Acids 25(8):951-968 | 2006 | - | Cited in [1] |
| 18 | Chen CW, et al. | NME3 is a gatekeeper for DRP1-dependent mitophagy in hypoxia | Nature Comms 15(1):2264 | 2024 | 10.1038/s41467-024-46385-7 | Cited in [2] |
| 19 | Puts GS, et al. | Nuclear functions of NME proteins | Lab Invest 98(2):211-218 | 2018 | 10.1038/labinvest.2017.109 | Cited in [2] |

---

## 4. Scientific Hypothesis (Novel Contribution)

**Hypothesis:** Stauprimide selectively inhibits the formation of the nuclear-competent NME1-NME2 A1B5 heterohexamer by binding at or near the 18 residues that differ between NME1 and NME2, perturbing the C-terminal/Kpn loop interface required for hexamer assembly.

**Supporting observations (from published data):**
1. Stauprimide binds NME2 and prevents nuclear translocation without affecting kinase activity or protein levels (Bouvard 2017)
2. NME1 and NME2 share 88% identity; the 18 differing residues are located outside the hexamer interface (Lim 2024)
3. The A1B5 heterohexamer is the most stable nuclear species (-172.39 kcal/mol, Lim 2024)
4. The C-terminal tail interacts with the Kpn loop of adjacent monomers; truncation dramatically destabilizes hexamers (Lim 2024)
5. NME2 has a restrictive (rigid) Kpn loop vs NME1's flexible Kpn loop (Lim 2024)
6. NME2 has a basic pI vs NME1's acidic pI, affecting surface charge and DNA binding (Lim 2024)

**Explicit caveats:**
- No co-crystal structure of stauprimide-NME2 exists
- The binding site of stauprimide on NME2 has not been experimentally determined
- This hypothesis requires validation by X-ray crystallography, cryo-EM, and/or MD simulations

---

## 5. Preprint Structure

### Title
"Targeting the NME2-MYC Transcriptional Axis: Structural Insights from NDPK Hexamer Dynamics and Implications for Stauprimide-Based Therapeutics"

### Sections
1. Abstract (~250 words)
2. Introduction (~800 words)
3. NME2 as a MYC Transcriptional Regulator (~600 words)
4. Stauprimide: Mechanism of Action (~700 words)
5. NDPK Hexamer Dynamics: A New Structural Framework (~800 words)
6. Integrative Analysis: Proposed Structural Mechanism (~600 words)
7. Clinical Implications and Therapeutic Landscape (~500 words)
8. Future Directions and Open Questions (~400 words)
9. Conclusion (~200 words)
10. References (19 citations)

### Figures
All follow Saloni's visualization guidelines: color-blind friendly (Wong palette), horizontal text, direct labels, standalone readability, source attribution.

- **Figure 1:** NME2-MYC transcriptional axis pathway schematic (TikZ)
- **Figure 2:** Stauprimide EC50 values across cancer cell lines (bar chart, data from Bouvard 2017)
- **Figure 3:** NDPK hexamer binding free energies (grouped bar chart, data from Lim 2024)
- **Figure 4:** Proposed mechanism schematic (TikZ, labeled "PROPOSED MODEL")
- **Table 1:** Heterohexamer configurations and binding energies (from Lim 2024 Table 3)
- **Table 2:** Comparison of MYC-targeting therapeutic strategies

---

## 6. Integrity Checklist

- [ ] No fabricated simulation data
- [ ] All quantitative values traceable to source papers
- [ ] Hypotheses clearly labeled as hypotheses
- [ ] Every claim has a citation
- [ ] No hallucinated paper titles, authors, or DOIs
- [ ] Preprint status of Lim 2024 acknowledged
- [ ] Limitations explicitly discussed

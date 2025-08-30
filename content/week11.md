+++
title = "Week 11 — L2 Processing & Experimental Methods"
date = '2025-05-01T08:47:59-04:00'
weight = 13
draft = false
+++


## Week 11 — L2 Processing & Experimental Methods

> **Anchor text**: Slabakova (2016), *Second Language Acquisition*, **Chapter 12**.

### ⭐ Overview (for preview)
- A compact **toolkit** for studying L2 processing: what **offline** vs. **online** methods measure and when to use them.
- How to align **theoretical claims** with **diagnostic tasks**, **dependent variables**, and **analysis plans**.
- Common **design pitfalls** (speed–accuracy tradeoff, item effects, underpowered samples) and how to avoid them.

---

### 🎯 Learning goals
By the end of this week you should be able to:
1. Map a **theory claim** to an appropriate **method** (GJT/AJT, SPR, eye-tracking, ERP) and **DV**.
2. Define key **online signatures** (e.g., first-pass vs. regression-path times; N400/P600 windows) and what they imply.
3. Draft a **minimal, well-controlled design** (counterbalancing, fillers, regions/time-windows, exclusions).
4. Specify an **analysis plan** (effect size, mixed-effects modeling basics, power/pre-registration) with a clear **falsifier**.

---

### 📖 Reading (do before Session 1)
- **Required**: Slabakova (2016), **Ch. 12** (overview of methods for L2 processing; morphology/syntax effects; individual differences).
- **Optional**: Revisit Ch. 3 for processing fundamentals to connect constructs to measures.

**Guiding questions:**
- What **new insight** does an **online** method offer beyond offline accuracy?
- For your research interest (e.g., agreement, article semantics, scope), which **task + DV** is most diagnostic and why?

---

### 🧠 Key terms
*offline vs. online; (timed) grammaticality/acceptability judgment (GJT/AJT); self-paced reading (SPR); region of interest (ROI); spillover; eye-tracking (first fixation, first-pass/gaze, regression-path, total time, skipping); ERP (baseline, time window, N400, LAN, P600); randomization, counterbalancing, Latin square; fillers; speed–accuracy tradeoff; response bias; mixed-effects models; random intercepts/slopes; effect size; power; preregistration; exclusion criteria.*

---

### 🔍 Core ideas
- **Match claim ↔ measure**: Processing claims require **time-course** measures; competence claims require **untimed** judgments/comprehension—ideally use **both**.
- **Signature patterns**:
  - **SPR**: region-locked **slowdowns** at the critical ROI (plus **spillover**).  
  - **Eye-tracking**: early **first-pass** differences vs. later **regression-path/total time**; **skipping** rates reflect predictability.  
  - **ERP**: **N400** (lexical/semantic integration), **P600** (syntactic reanalysis/morpho-syntax), sometimes **LAN** (early morpho-syntax).  
- **Design hygiene**: Control **lexical frequency/length**, avoid **item confounds**, **counterbalance** lists, add **fillers**, and include **comprehension checks** to maintain task engagement.
- **Analysis basics**: Report **effect sizes**, use **mixed-effects** models with **participants/items** as random factors, predefine **exclusions** (e.g., <60% comprehension, RT outliers), and consider **power** (planned N).

---

### 🗂️ Mini-lecture outline (Session 1, 45 min)

#### 1) Choosing the right method & DV
- **Key notes**:  
  - **Untimed AJT/GJT** → competence judgments; **Timed GJT** → adds processing pressure.  
  - **SPR** → linear text, precise **ROI** comparisons; **Eye-tracking** → natural reading with **multiple measures**; **ERP** → millisecond-level neural signatures.  
  - Avoid **speed–accuracy tradeoff** and **response bias** (include foils, practice, and comprehension probes).
- **Class spark**: Given a claim (“L2 readers compute agreement but more slowly”), students pick **one method + one DV** and justify.

#### 2) Online signatures & interpretation
- **Key notes**:  
  - **SPR**: establish **pre-critical baseline**, identify **critical** and **spillover** regions.  
  - **Eye-tracking**: what **first-pass**, **regression-path**, **total time**, and **skipping** each index.  
  - **ERP**: define **baseline**, **time-windows** (e.g., 300–500 ms N400; 500–800 ms P600); control **artifacts** and **trial counts**.
- **Micro-demo**: Annotate a sample sentence with ROIs/time-windows; predict where effects should appear.

#### 3) Design hygiene & analysis plan
- **Key notes**:  
  - **Stimuli**: balance lexical properties, avoid unintended cues; **Latin-square** lists to distribute conditions.  
  - **Fillers**: mix structures to reduce strategy.  
  - **Stats**: mixed-effects (participants/items), pre-registered **contrasts**, **effect size**, **power** (pilot or simulation).  
  - **Exclusions**: comprehension accuracy threshold; RT trimming rules; ERP artifact criteria.
- **Think–pair–share**: Identify **one threat** to validity in a sample design and propose a fix.

> **Pacing**: ~12 min each mini-topic + ~9 min Q&A fits 45 minutes.

---

### 🧪 Methods micro-lab (Session 2, 45 min)
**Goal**: From claim → materials → DV → analysis (compact prereg sheet).

Choose **ONE** template and fill it in:

- **A. Agreement attraction (SPR)**  
  - *Hypothesis*: L2 readers represent agreement but suffer **similarity-based interference**.  
  - *Materials*: Sentences like “The **key** to the **cabinets** … **is/are** …” with **match/mismatch** conditions.  
  - *DV*: RT at **verb region** (+ spillover).  
  - *Analysis*: Mixed-effects on logRTs; fixed effects = **Match** × **Grammaticality**, random intercepts/items; define outlier trimming.  
  - *Falsifier*: No mismatch cost at the verb region despite adequate power.

- **B. Wh-dependency (Eye-tracking)**  
  - *Hypothesis*: L2 readers build **filler–gap** dependencies but incur larger **reanalysis** costs.  
  - *Materials*: Grammatical vs. **island** violations; gap/disambiguation region marked.  
  - *DV*: **Regression-path time** at disambiguation; **first-pass** at gap.  
  - *Analysis*: Mixed-effects per measure; accuracy screen on comprehension Qs.  
  - *Falsifier*: Equal regression-path times across grammatical vs. island conditions.

- **C. Semantic vs. morpho-syntactic violations (ERP)**  
  - *Hypothesis*: L2 shows **N400** to semantic anomalies, **P600** to morpho-syntactic ones, with possible latency differences.  
  - *Materials*: Minimal pairs (semantic violation vs. agreement violation vs. control).  
  - *DV*: Mean amplitude in **300–500 ms** (N400) and **500–800 ms** (P600) windows at preselected electrodes.  
  - *Analysis*: Repeated-measures/mixed models; artifact rejection rules; minimum trials per condition.  
  - *Falsifier*: Absence of condition effects with sufficient clean trials and power.

**Deliverable**: 5 bullet prereg—**Hypothesis**, **Materials**, **DV(s)**, **Exclusions**, **Model/Contrasts**.

---

### 🧩 In-class application (Session 3, 45 min)
**Case vignette: Two studies, different conclusions**
- **Study 1 (Timed GJT)**: L2 group patterns with natives on agreement violations.  
- **Study 2 (SPR)**: Same learners show **slowdowns** at the verb only when a distractor noun competes.

**Discussion prompts**:
1) Reconcile the findings: **competence** intact, **processing costs** under time pressure?  
2) What **design differences** (e.g., ROI placement, spillover, list balancing) could amplify or suppress the effect?  
3) Redesign one study (change **task** or **DV**) to test the integrated hypothesis.  
4) **Instructional angle**: propose a drill or reading activity that targets the specific processing cost.

---

### ✅ Self-check (answers hidden)

1) One advantage of **SPR** over **timed GJT** for processing claims.  
<!-- Region-level time-course (critical + spillover) reveals *where* difficulty arises, not just end-point accuracy. -->

2) Name **two eye-tracking measures** and what they index.  
<!-- First-pass/gaze: early lexical/syntactic processing; Regression-path: reanalysis/integration difficulty; Total time: overall processing including late stages. -->

3) Typical **ERP** signatures for semantic vs. morpho-syntactic violations.  
<!-- N400 for semantic integration; P600 for syntactic/morpho-syntactic reanalysis/integration. -->

4) One **design practice** that reduces response strategies in AJT/GJT.  
<!-- Include varied fillers and comprehension checks; counterbalance condition order. -->

5) Why use **mixed-effects models** for psycholinguistic data?  
<!-- They account for variability by *participants* and *items*, improving generalization beyond a single sample of each. -->

---

### 📝 Weekly analytical note (due before Week 12)
Draft the **Methods & Analysis** section for your final proposal (≈300–400 words). Include: (a) **task + DV(s)** with ROIs/time-windows, (b) **materials** and counterbalancing, (c) **exclusion criteria**, (d) **planned model/contrasts** and **effect size**, and (e) a **power** or **pilot** plan. End with a **falsifier** for your main claim.

---

### 🧭 Preview of Week 12
We close with **teaching implications** and the **Bottleneck Hypothesis**—how theory-driven evidence about morphology, syntax, and processing informs **focus on form** in the classroom.

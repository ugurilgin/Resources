# qpAdm Tutorial and Model Overview

**qpAdm** (*quadrature population Admixture*) is a powerful statistical tool in population genetics used to estimate the proportions of ancestry from different source populations in a target population.

It is part of the **ADMIXTOOLS** software package developed by David Reich's lab at Harvard University. qpAdm is crucial for understanding population history by quantifying the genetic contributions of various ancestral groups to modern and ancient populations.

---

## 🔑 Key Parameters for qpAdm Analysis

Setting up an accurate qpAdm model requires a clear understanding of the three main population categories: the **Target**, **Sources**, and **Right Populations**.

### 1. Target Population

- **Definition**: The group you are analyzing to understand its genetic ancestry.  
- **Example (This Tutorial)**: `Sohi`  
- **Role**: The Target is assumed to be a mixture of the Source Populations. It should generally be a present-day or recent historical population with high-quality genetic data.

---

### 2. Source Populations (The Ancestors)

- **Definition**: Groups hypothesized to have contributed to the Target population's ancestry.  
- **Requirement**: You must provide a list of **at least two** Source populations.  
- **Role**: They should be genetically distinct and represent potential ancestral populations based on historical, archaeological, or genetic evidence. They must be **older than or contemporaneous with** the Target.

#### Example Source Populations:
- `Iran_ShahrISokhta_BA2` (Ancient Iran)  
- `Kazakhstan_Andronovo.SG` (Ancient Central Asia)  
- `Turkmenistan_Gonur_BA_1` (Bronze Age Turkmenistan)

---

### 3. Right Populations (Outgroups)

- **Definition**: Also known as **outgroups**, these are reference populations used to model the ancestry of the Target. They are vital for statistically distinguishing the contributions of the different Source populations.  
- **Role**: The Right Pops should generally include **diverse populations** that are **not direct ancestors** of the Target but are relevant to the broader population structure. The list **always begins with a basal African population** (`Mbuti.DG`).

#### Example Right Populations (Comprehensive List):

- `Mbuti.DG`  
- `Irula.DG`  
- `Turkey_N`  
- `Laos_LN_BA.SG`  
- `China_Tianyuan`  
- `Ami.DG`  
- `Karitiana.DG`  
- `Iran_GanjDareh_N`  
- `Iran_C_SehGabi`  
- `Iran_ShahrISokhta_BA1`  
- `Iran_ShahrISokhta_BA2`  
- `Turkmenistan_Gonur_BA_1`  
- `Dai.DG`  
- `Russia_Ust_Ishim_HG.DG`  
- `Chukchi.DG`  
- `Saami.DG`  
- `Georgia_Kotias.SG`  
- `Russia_Kostenki14.SG`  
- `Russia_Tyumen_HG`  
- `Russia_MLBA_Sintashta`  
- `Russia_DevilsCave_N.SG`  
- `Luxembourg_Loschbour.DG`  
- `Czech_BellBeaker`  
- `Kazakhstan_Central_Saka.SG`  
- `Portugal_MN.SG`  
- `Kazakhstan_Andronovo.SG`

---


## 🔬 Standard qpAdm Model and Output

### Model Expression

A standard qpAdm model postulates the Target as a linear combination of the Sources:

Here:
- `x` and `y` are the **admixture coefficients** (ancestry proportions)
- `x + y = 1` (or 100%)

### Key Output Metrics

The qpAdm output provides three critical pieces of information:

1. **p-value** (`tailprob`): Indicates the statistical fit of the model to the data.  
2. **Admixture Coefficients**: The estimated proportions (`x` and `y`) of ancestry from each Source.  
3. **Standard Errors**: Measure the precision of the admixture coefficient estimates.

---

## ✅ Criteria for a Successful Model

A qpAdm model is considered **robust and successful** if it meets the following criteria:

- **High p-value**: Typically **> 0.05**, indicating a good fit between the hypothesized model and the observed genetic data (i.e., the model **cannot be rejected**).  
- **Low Standard Errors**: Shows that the estimates of the admixture coefficients are **precise**.  
- **Positive Admixture Coefficients**: Ensures that all estimated contributions from the Source populations are **biologically plausible** (i.e., **no negative ancestry** is estimated).

---

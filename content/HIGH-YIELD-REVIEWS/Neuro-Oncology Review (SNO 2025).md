---
date created: Wednesday, November 19th 2025, 8:38:12 am
date modified: Saturday, November 22nd 2025, 6:46:34 am
---
## Neuro-oncology Imaging

**Tags:** #neuro-oncology #radiology #neurology #GBM #imaging #RANO  
**Related:** [[Glioblastoma]], [[Radiation Necrosis]], [[RANO Criteria]], [[IDH-mutant glioma]]

> [!summary] Key Takeaways
> 
> - **Core tools:** Conventional MRI, DWI/ADC, Perfusion (DSC), MRS, and Amino-acid PET.
> 
> - **Primary Challenge:** Distinguishing **True Progression (TP)** from treatment effects like **Pseudoprogression (PP)** and **Radiation Necrosis (RN)**.
> 
> - **Workflow:** While advanced imaging provides a "metabolic readout," **histology** remains the gold standard, and decision-making often relies on **longitudinal clinical/radiographic follow-up**.

---

### 1. Advanced Imaging Modalities

#### 1.1 DWI / ADC (Diffusion Weighted Imaging)

- **Principle:** Probes water mobility. High cellularity → restricted diffusion → **low ADC**.
- **Tumor signature:** Highly cellular tumors (e.g., Lymphoma, GBM) typically show low ADC.
- **Limitation:** Necrotic tissue (RN) usually has higher ADC, but overlap with tumor is substantial. **Cannot reliably distinguish TP vs. RN alone.**

| Feature        | **Acute infarction**                          | **Typical tumor / metastasis**                                       |
| -------------- | --------------------------------------------- | -------------------------------------------------------------------- |
| **Edema type** | **Cytotoxic** (intracellular swelling)        | **Vasogenic** (extracellular leakage)                                |
| **DWI signal** | **Hyperintense** (bright)                     | **Variable / isointense** _(unless highly cellular, e.g., lymphoma)_ |
| **ADC signal** | **Hypointense** (dark → restricted diffusion) | **Hyperintense** (bright → facilitated diffusion)                    |

> [!NOTE] Why ADC matters
> **Cytotoxic edema → low extracellular water mobility → low ADC.**  
> **Vasogenic edema → increased extracellular water → high ADC.**

#### 1.2 Perfusion MRI (DSC)

- **Principle:** Measures relative Cerebral Blood Volume (rCBV) as a proxy for **neoangiogenesis** (microvascular density).
- **Typical Patterns:**
    - **True Progression/Recurrence:** Elevated rCBV/rCBF (==rCBV > 2.2==)
	    - active neoangiogenesis
    - **Radiation Necrosis:** Reduced or heterogeneous rCBV (==rCBV < 2.0==).
	    - reduced vascularity
- **Sampling Strategy:** Focus on the enhancing rim or areas of increasing FLAIR at treatment margins.

![[Pasted image 20251126170205.png|400]]
#### 1.3 MR Spectroscopy (MRS)

A non-invasive "metabolic biopsy."

- **Choline (Cho):** Membrane turnover marker. ==**Elevated** in high-grade tumors== (proliferation).
- **NAA (N-acetylaspartate):** Marker of neuronal integrity. ==**Decreased** in tumors== and non-neoplastic insults.
- **Lactate/Lipids:** Indicators of hypoxia, necrosis, or high-grade biology.
- **2-HG (2-hydroxyglutarate):**
    - Specific oncometabolite for IDH-mutant glioma.
    - Reference: Dang et al., Nature 2009.
    - **Clinical Utility:** MRS-detectable 2-HG serves as a non-invasive IDH marker.

![[Pasted image 20251126171358.png|300]]![[Pasted image 20251126171651.png|300]]

#### 1.4 PET Imaging (Amino Acid PET)

Increasingly emphasized by **RANO/EANO** for adding diagnostic value (Lancet Oncology 2025; 26; e426).

- **Mechanism:** Tracer uptake driven by overexpression of **LAT transporters** (L-type amino acid).
    - Crucial Detail: Uptake is largely **independent of Blood-Brain Barrier (BBB) disruption**, unlike MRI contrast.
- **Specificity:** Relatively specific for glioma and brain metastases compared to normal background brain.
- **Common Tracers:**
    - **FET PET** (Fluoroethyl-tyrosine)
    - **FDOPA PET**
    - **Methionine PET** (MET)
    - **Fluciclovine PET**
- **Concept:** Think of AA-PET as the **"metabolic readout"** of active tumor when MRI is equivocal.

![[Pasted image 20251126171911.png|500]]

---

### 2. Diagnostic Challenges: The "Big Three"

The central dilemma in post-treatment neuro-oncology is distinguishing True Progression (TP) from treatment effects.

#### 2.1 Pseudoprogression (PP)

- **Definition:** A **transient increase** in contrast enhancement (often with FLAIR expansion) that stabilizes or regresses without new therapy.
- **Timing:** Typically **< 12 weeks** post-radiotherapy.
- **Risk Factors:** Concurrent alkylating agents (e.g., Temozolomide) and methylated MGMT Promoter status.
- **Incidence:** 10–30% of patients.
- **Diagnosis:** Fundamentally based on **clinical + radiographic course** (spontaneous resolution).
    - Histology Note: Biopsy is unreliable due to sampling errors (mixed tissue). Diagnosis correct in only **~32%** of cases (J Neuro-Oncology 2025).

> [!danger] The RANO "12-Week Rule"  
> **Progressive Disease (PD)** should **not** be diagnosed if TMZ chemoradiation was completed within the last **12 weeks**, unless:
> 
> - There is an **out-of-field recurrence**.
> 
> - **Histology** clearly indicates viable tumor tissue.

#### 2.2 Radiation Necrosis (RN)

- **Definition:** A late complication representing tissue death.
- **Timing:** **6 months to several years** post-RT (median ~24 months).
- **Incidence:** ~5% in Gliomas; 5–25% in Brain Metastases.
- **Risk Factors:** High radiation dose, large volume, re-irradiation, concurrent chemotherapy.
- **Pathology (Gold Standard):** Fibrinoid necrosis of small arteries, coagulative necrosis, reactive gliosis.
- **Management:**
    - Corticosteroids (First-line).
    - Bevacizumab (Reduces edema/enhancement).
    - Surgery (if refractory or significant mass effect).

> [!example] Quick pattern match
> - **Radiation necrosis**  
>   - Low rCBV  
>   - Low Cho / Low NAA  
>   - Hypometabolic (cold) on PET  
>
> - **Tumor recurrence**  
>   - High rCBV  
>   - High Cho  
>   - Hypermetabolic (hot) on PET
#### 2.3 The "Steroid Effect" Pitfall

- **Dexamethasone** can reduce contrast enhancement volumes by **~25%**.
- **Clinical Pearl:** A reduction in enhancement after starting steroids suggests inflammatory change (PP/RN) rather than cytotoxic tumor reduction, but it is **nonspecific**.

![[Pasted image 20251126173705.png|400]]

---

### 3. Differentiation Strategy

Standard MRI (Contrast/FLAIR) has **low predictive value** for differentiating RN from TP (De Quesada et al., Neurosurg 2008). A multimodal approach is required.
#### Comparative Matrix

| Feature              | Pseudoprogression (PP)       | Radiation Necrosis (RN)                       | True Progression (TP)        |
| -------------------- | ---------------------------- | --------------------------------------------- | ---------------------------- |
| **Timing**           | **< 12 weeks** post-RT       | **6–24+ months** post-RT                      | Any time                     |
| **Perfusion (rCBV)** | Low or Normal                | **Low** / Heterogeneous                       | **Elevated** (Angiogenesis)  |
| **AA PET Uptake**    | Low / Decreasing vs baseline | Low / Heterogeneous                           | **Intense / Increasing**     |
| **MRS (Cho/NAA)**    | Mild Cho ↑                   | Suppressed metabolites <br>(Lipids/Lactate ↑) | **Marked Cho ↑**<br>NAA ↓    |
| **DWI / ADC**        | Variable                     | High ADC (in necrotic core)                   | **Low ADC** (in solid tumor) |
| **Clinical Course**  | Asymptomatic / Stable        | Delayed deterioration                         | Progressive symptoms         |

#### The Role of Amino Acid PET

- **Gliomas:**
    - Diagnostic accuracy: **81–96%**.
    - Sign: Increased FLAIR with **decreased** metabolic activity on PET strongly favors Pseudoprogression.
- **Brain Metastases:**
    - Diagnostic accuracy: **75–90%** for distinguishing TP vs. RN vs. PP.

---

### 4. Limitations and Pitfalls

#### MRS Pitfalls

- **The 2-HG False Positive:** While specific for IDH mutations, a study in **IDH-wildtype GBM** showed **~21%** of patients had falsely elevated 2-HG levels. Always correlate with molecular testing.
- **Technical:** Small signals are easily missed; requires long acquisition (motion artifact risk); voxel placement errors (partial volume effect).

#### Perfusion MRI Pitfalls

- **Bone Artifacts:** Signal loss above **temporal bones** can obscure temporal lobe lesions, making TP vs. PP differentiation difficult.
- **The "Non-Enhancing" Glioma:**
    - Subset of WHO Grade 2 gliomas have low vascularity (low rCBV).
    - **Molecular GBM (WHO 2021):** May lack typical contrast enhancement and perfusion spikes despite aggressive molecular biology.

#### PET Pitfalls

- **No Histological Typing:** AA PET detects activity, not type. It cannot distinguish GBM vs. Metastasis vs. PCNSL.
- **Non-Tumoral Uptake:** Rare false positives can occur in **infectious** or **inflammatory** lesions (e.g., abscess).

---

## Neurosurgical Techniques in Neuro-oncology

presenter: James A. Balogun  
date: 2025-11-20

> [!summary]  
> Surgery in neuro-oncology is not just about "taking the tumor out."  
> It's about **diagnosis**, **disease control**, **symptom relief**, and **functional preservation**, supported by a growing toolbox of **imaging, mapping, and minimally invasive adjuncts**.

---

### 1. Role of Surgery in Neuro-oncology

Surgery serves four primary pillars in the management of brain tumors:

1. **Tissue diagnosis**
    - Establishes **histological** and **molecular** classification (WHO grade, IDH status, 1p/19q, MGMT, etc.).
        
2. **Cytoreduction**
    - Maximizes safe removal of tumor burden to:
        - Improve local control.
        - Enhance effectiveness of adjuvant therapy (RT, chemo, targeted agents).
            
3. **Symptom relief**
    - Reduces **intracranial pressure (ICP)** and mass effect.
    - Treats obstructive hydrocephalus and local edema-related symptoms.
        
4. **Functional improvement**
    - Aims to preserve or recover **neurological function**.
    - Enables return to work, independence, and adequate performance status for systemic therapy.

#### Special Consideration: Low-Grade Gliomas (LGG)

> [!info] Current paradigm  
> The trend has shifted from "watchful waiting" toward **early, functionally guided resection**, provided the risk to eloquent function is acceptable.

- **Early resection** is generally favored over a strict "wait-and-see" strategy:
    - Associated with **better OS** and **PFS** in multiple series.
    - May **delay malignant transformation**.
    - Allows more complete **molecular profiling** early in the disease course.
- **Controversies and nuance:**
    - Deep or highly eloquent tumors may still warrant a more conservative approach or staged procedures.
    - Asymptomatic, incidentally discovered LGG with stable imaging may be observed in selected cases with tight surveillance.
    - Decision-making is individualized, balancing **oncologic benefit** vs **functional risk** and patient preference.

---

### 2. Defining Extent of Resection (EOR)

> [!note] Onco-functional resection  
> The goal is not "maximal resection at all costs," but **maximal safe resection** within the constraints of **eloquent cortex and subcortical pathways**.

#### 2.1 Gliomas

- **Core concept:** **Onco-functional resection**
    - Balance **tumor removal** with preservation of **language, motor, and higher cognitive function**.
    - Guided by:
        - Tumor location.
        - Preoperative function.
        - Intraoperative mapping and adjuncts.
- **EOR thresholds:**
    - Increasing EOR correlates with improved outcomes.
    - **EOR > 75%** is commonly associated with **improved overall survival (OS)** and longer PFS in both LGG and HGG.
- **Resection spectrum:**
    - **Biopsy / Partial resection**
        - Primarily for diagnosis when resection is high risk or not feasible.
    - **Subtotal resection (STR)**
        - Debulking to reduce mass effect and improve symptoms; may still offer survival benefit vs biopsy alone.
    - **Gross total resection (GTR)**
        - Removal of all **contrast-enhancing disease** on early post-op MRI (for HGG).
    - **Supratotal resection**
        - Resection of contrast-enhancing tumor **plus portions of the surrounding T2/FLAIR abnormality** in non-eloquent regions.
        - **Potential benefits:**
            - Increases **PFS**.
            - May **delay malignant transformation**, especially in IDH-mutant LGG.

> [!tip] Practical point  
> For gliomas, define your surgical goal **preoperatively** (biopsy vs debulk vs GTR vs supratotal), and align this with the patient's expectations and functional priorities.

---

#### 2.2 Meningiomas – Simpson Grading

The **Simpson Grading** system estimates recurrence risk based on the extent of resection and dural/bone treatment.

|Grade|Definition|Outcome / Recurrence Risk|
|:--|:--|:--|
|**I**|GTR + removal of dural attachment **and** abnormal bone|Best prognosis, lowest risk|
|**II**|GTR + **coagulation** of dural attachment|Low–moderate risk|
|**III**|GTR of intradural tumor **without dural/bone treatment**|Moderate risk|
|**IV**|Subtotal resection (residual tumor left in situ)|High recurrence risk|
|**V**|Simple decompression +/- biopsy|Worst prognosis, highest risk|

> [!info]  
> Modern practice also weighs **tumor location**, **WHO grade (I–III)**, and **molecular features**; Simpson grade remains useful but is no longer the sole determinant of adjuvant RT.

---

### 3. Surgical Adjuncts

Modern neuro-oncology relies on a **multi-modal operative strategy** to maximize EOR and minimize morbidity.

> [!info] Safety of adjuncts  
> Evidence (e.g., _Maye et al._) suggests that the use of adjuncts (iMRI, iUS, fluorescence, robotics, etc.) is **not associated with increased infection risk** when standard sterile technique and perioperative protocols are followed.

#### 3.1 Neuronavigation

- **Principle:**
    - Stereotactic registration of patient anatomy to preoperative **MRI/CT**, providing a **3D anatomical roadmap**.
- **Benefits:**
    - Improved localization of:
        - Tumor boundaries.
        - Cortical entry point and craniotomy planning.
        - Relationship to vessels and eloquent cortex.
    - Associated with **improved EOR** and **better OS** in several glioma series.
- **Limitations:**
    - **Brain shift** progressively degrades accuracy:
        - CSF loss.
        - Tumor debulking.
        - Edema and gravity effects.
    - Dependent on **initial registration accuracy** (surface matching, fiducials).
- **Mitigation strategies:**
    - Re-registration when feasible.
    - Integration with **iMRI** or **iUS** to update intraoperative anatomy.

---

#### 3.2 Intra-operative MRI (iMRI)

- **Function:**
    - Provides **real-time updates** of 3D anatomy, correcting for brain shift.
    - Detects residual tumor after an initial resection pass.
- **Benefits:**
    - Particularly useful in:
        - **LGG** with indistinct borders.
        - Tumors near eloquent areas where the margin is visually ambiguous.
    - **Level 2 evidence:** iMRI-guided surgery is associated with **increased EOR** and improved local control in several series.
- **Cons:**
    - **Limited availability** (requires dedicated hybrid OR).
    - **Increased operative time** and workflow complexity.
    - Requires MRI-compatible instruments and careful logistics.

> [!tip]  
> iMRI is most valuable when your **visual margin is unreliable**—non-enhancing gliomas, deep tumors, and "second-look" passes.

---

#### 3.3 Intra-operative Ultrasound (iUS)

- **Function:**
    - Real-time, **cost-effective** intraoperative imaging for:
        - Tumor localization.
        - Assessment of residual disease.
        - Evaluation of cystic vs solid components.
- **Recent advances:**
    - **Multiparametric US** (modifications beyond standard B-mode):
        - Contrast-enhanced US.
        - Doppler modes.
        - Elastography.
    - These can improve **tissue differentiation** and help delineate tumor margins.
- **Reference:**
    - Wei et al., _Front Neurol_ (2023).

> [!info]  
> iUS is especially attractive in centers without iMRI—**repeatable, fast, and inexpensive**, with a learning curve for image interpretation.

---

#### 3.4 Fluorescence-Guided Surgery

Uses metabolic or permeability-based dyes to visualize tumor tissue intraoperatively.
##### 5-ALA (5-aminolevulinic acid)
- **Mechanism:**
    - Crosses the **blood–brain barrier (BBB)** and is metabolized intracellularly into **protoporphyrin IX (PpIX)**, which fluoresces under blue/violet light.
- **Protocol:**
    - Administered **orally ~3 hours prior** to surgery.
- **Equipment:**
    - Requires an operative microscope with a **violet-blue filter** to visualize fluorescence.
- **Efficacy:**
    - Significantly increases **GTR rates** in high-grade glioma:
        - Approximately **~65% GTR with 5-ALA** vs **<30%** with white-light alone in landmark trials.
- **Clinical notes:**
    - Fluorescence is most robust in **HGG**; less reliable in LGG.
    - Can occasionally highlight non-tumor tissue (e.g., inflamed or treatment-altered areas) and must be interpreted in context.
##### Fluorescein
- **Mechanism:**
    - Primarily reflects **BBB disruption** rather than tumor-specific metabolism.
- **Use:**
    - Alternative or adjunct to 5-ALA.
    - Often cheaper and more widely available, used with a dedicated filter system.

---

### 4. Functional Mapping & Awake Craniotomy

> [!summary]  
> Awake mapping is your main tool for pushing EOR in eloquent areas **without sacrificing function**.

#### 4.1 Goals and Principles

- **Primary goal:**
    - Identify **eloquent regions** (language, primary motor, often sensory and higher cognitive functions) to **maximize resection** without creating a new permanent deficit.
- **Integration:**
    - Usually combined with:
        - Pre-op fMRI / DTI.
        - Neuronavigation.
        - Intraoperative neurophysiology monitoring.

#### 4.2 Stimulation Techniques

- **Bipolar electrode:**
    - Used for ==**cortical stimulation**== (surface mapping).
    - Standard for delineating:
        - Language areas (speech arrest, naming errors).
        - Motor cortex (face, upper limb, lower limb).
- **Monopolar stimulation:**
    - Used for ==**subcortical mapping**==.
    - Helps identify key **descending white matter tracts** (e.g., CST, language pathways).
- **Motor mapping:**
    - Relies on:
        - **Stimulation-induced movement** observed by the surgical team.
        - Patient-reported sensations or movement when awake.
    - Can be performed under awake or asleep conditions depending on the paradigm.

![[Pasted image 20251126172353.png|500]]

> [!tip]  
> Good candidates are **motivated, cognitively intact, and well-briefed**. The best outcomes come from meticulous **pre-op counseling** and task rehearsal.

#### 4.3 Contraindications / Risk Factors for Awake Surgery

> [!warning] Awake craniotomy – when to think twice  
> Based on Hervey-Jumper et al., _J Neurosurgery_ (2015), these are relative rather than absolute but should trigger caution:

- Significant **mass effect** / high ICP.
- **Obesity (BMI > 30)** or **obstructive sleep apnea (OSA)** → airway and ventilation risk.
- Significant **psychiatric history** (poor cooperation, anxiety, psychosis).
- **Age < 10 years** (some specialized centers may manage selected cases).
- History of **intraoperative seizures** or poorly controlled epilepsy.
- **Active smoker** (coughing and airway irritability).
- **Intraoperative nausea** or intolerance of sedation.
- **Reoperation** with significant dural scarring (more painful and technically complex).
- **Severe baseline neurological impairment** that prevents meaningful participation in tasks.

---

### 5. Advanced & Minimally Invasive Techniques

#### 5.1 Laser Interstitial Thermal Therapy (LITT)

- **Mechanism:**
    - Delivers **heat** to target tissue via a stereotactically placed laser probe under MRI guidance.
    - Tissue injury is a function of **temperature × time** at the target (thermal dose).
- **Indications:**
    - **Recurrent glioblastoma (GBM)**.
    - Deep, **non-resectable tumors** in eloquent or previously irradiated regions.
    - Lesions typically **< 5 cm** in diameter.
    - Selected cases of **radiation necrosis** or focal epilepsy (center-dependent).
- **Advantages:**
    - Minimally invasive; typically short hospital stay.
    - Useful when open resection carries prohibitive risk.
- **Limitations:**
    - Limited margin control.
    - Heat spread near critical structures must be monitored carefully.

---

#### 5.2 Endoscopic Endonasal Approach (EEA)

- **Workflow:**
    - Performed as a **collaborative effort with ENT** surgeons.
- **Pros:**
    - Excellent corridor for **midline ventral skull base lesions** (pituitary adenomas, tuberculum sellae meningiomas, craniopharyngiomas, clival lesions).
    - Avoids brain retraction and offers direct access to sellar/parasellar region.
- **Cons:**
    - **Limited range of motion** and working angles.
    - **Ergonomic challenges** and surgeon fatigue over longer cases.
    - Reconstruction and CSF leak prevention are critical technical steps.

---

#### 5.3 Other Modalities

- **Robot-assisted biopsies:**
    - Provide high-precision, reproducible trajectories.
    - Particularly useful for:
        - Deep or multiple lesions.
        - Frameless stereotactic workflows.
- **Tubular retractor systems:**
    - Allow minimally disruptive **trans-sulcal access** to deep lesions.
    - Aim to **displace rather than cut** white matter, potentially reducing morbidity.
- **Focused Ultrasound (FUS):**
    - **Emerging** technology:
        - Ablative therapy for certain deep lesions (more established in movement disorders).
        - **BBB opening** to enhance delivery of systemic therapies (investigational in neuro-oncology).
    - Currently used primarily in research or highly selected clinical scenarios.

---

> [!summary] Clinical takeaway
> 
> - Define your **surgical goal** (biopsy vs debulking vs GTR vs supratotal) for each case.
> 
> - Use adjuncts—**neuronavigation, mapping, iUS/iMRI, fluorescence, LITT**—to safely push resection boundaries.
> 
> - Keep the focus on **onco-functional outcomes**: survival benefit only matters if the patient retains **meaningful quality of life**.

---

## Neuropathology in Neuro-oncology

> [!summary]
> 
> - Modern CNS tumor diagnosis is an **integrated diagnosis**:  
> **Histology + Immunophenotype + Molecular profile (IDH, 1p/19q, ATRX, TERT, H3, etc.)**.
> 
> - Many entities are now _defined_ by molecular alterations rather than morphology alone.
> 
> - Epigenetic (DNA methylation) profiling is increasingly used for **difficult or ambiguous cases**.

---

### 1. General Pathology Principles

**Pathology goal:** combine **histologic patterns** and **molecular features** to guide patient management (diagnosis, prognosis, therapy).

#### Brain Metastases

- **Epidemiology**
    - Most common brain tumors in adults (~200,000/year in the US).
- **Common primary sites**
    - Lung: **~48%**
    - Breast: **~15%**
    - Melanoma: **~9%**
    - GU and GI primaries follow.
    - **Unusual**: prostate (still important to keep on the differential).
- **Historical note**
    - Early classification and surgical descriptions attributed to **Harvey Cushing**.
- **Pathology tips**
    - Often **sharply demarcated** from brain parenchyma.
    - Immunopanels are critical to identify primary (e.g., TTF-1 for lung, ER/PR for breast, SOX10/Melan-A for melanoma).

---

### 2. Tumor Naming and Cell Lineage

> [!info] Tumors named after presumed precursor cells  
> Many CNS tumors are named for the **cell type they resemble**, not necessarily their true cell of origin.

#### Classic examples (with common immunostains)

|Tumor|Lineage pattern|Typical IHC markers|
|---|---|---|
|**Astrocytoma**|Astrocytic|**GFAP**, OLIG2|
|**Oligodendroglioma**|Oligodendroglial (often mixed)|**GFAP**, OLIG2, SYN (focal)|
|**Neurocytoma**|Neuronal|**Synaptophysin (SYN)**|

- **Key point:** Precise histogenesis of many CNS neoplasms is **uncertain**; classification now leans heavily on **molecular profiles**.

---

### 3. Grading CNS Neoplasms

- **WHO Grade 1**
    - Usually benign; often **surgically curable**.
- **WHO Grades 2–4**
    - Considered **malignant**, with increasing aggressiveness.

#### Morphologic features used in grading

- **Cellular atypia**
    - Increased **density/cellularity**.
    - **Nuclear atypia** and pleomorphism.
- **Mitotic activity**
    - Increased mitoses suggest higher grade.
- **Microvascular proliferation**
- **Necrosis** (especially pseudopalisading necrosis in high-grade gliomas).

> [!note] Integrated WHO classification
> 
> - **Histology is no longer enough.**
> 
> - Many entities now require specific **molecular alterations** for definitive diagnosis (e.g., IDH mutation, 1p/19q codeletion, H3K27 alteration, etc.).

---

### 4. Diffuse Gliomas (Adult-type)

- **Most common primary brain tumors in adults.**
- **Uniformly incurable** with current therapy.
- Characterized by **diffuse infiltration** into brain parenchyma.

#### 4.1 Adult diffuse glioma classification

Broad adult categories (WHO 2021 framework):
1. **IDH-mutant astrocytoma (grades 2–4)**
2. **IDH-mutant, 1p/19q-codeleted oligodendroglioma (grades 2–3)**
3. **IDH-wildtype glioblastoma (GBM), CNS WHO grade 4**

![[Pasted image 20251126191359.png|500]]
##### IDH Mutation
- Typically **IDH1 R132** (canonical) or related non-canonical codon 132 mutations.
- Leads to **reduced catalytic activity** and production of **2-hydroxyglutarate (2-HG)** (oncometabolite).
- Features:
    - Mutations are **heterozygous**.
    - Typically **missense**, not nonsense.
- Clinical: associated with **younger age** and **better prognosis** vs IDH-wildtype.

##### Oligodendroglioma – IDH-mutant, 1p/19q-codeleted
- Defined by:
    - **IDH mutation** AND
    - **Whole-arm 1p/19q co-deletion**.
- WHO grades 2 and 3.
- **Testing caveat:**
    - **FISH** for 1p/19q can give **false positives** if not assessing whole-arm status (partial deletions).
- Typically:
    - Retain **TERT promoter mutations**.
    - **ATRX is intact** (helps distinguish from astrocytoma).

> [!NOTE]- Calcification is seen in **70–90%** of oligodendrogliomas on CT
> ![[Pasted image 20251126193008.png|400]]
> ![[Pasted image 20251126193103.png|400]]

> [!NOTE]- Oligodendroglioma histology; cells resembling fried eggs and chicken-wire-like appearance
> ![[Pasted image 20251126175434.png|300]]
##### Astrocytoma – IDH-mutant
- Defined by **IDH mutation** with **no 1p/19q co-deletion**.
- WHO grades **2, 3, 4** (grade 4 astrocytoma replaces "secondary GBM" in nomenclature).
- **ATRX deficiency**:
    - Characteristic of IDH-mutant astrocytomas.
    - Loss by IHC is supportive of diagnosis.
- **CDKN2A homozygous deletion**:
    - Upgrades IDH-mutant astrocytoma to **WHO grade 4**, even without overt necrosis/microvascular proliferation.

> [!NOTE]- **T2-FLAIR mismatch sign** <br>highly specific radiogenomic biomarker used to non-invasively identify **IDH-mutant, 1p/19q non-codeleted astrocytomas** (typically WHO Grade 2 or 3)
> ![[Pasted image 20251126192222.png|400]]
> ![[Pasted image 20251126192248.png|400]]

> [!NOTE]- Astrocytoma histology; WHO grade II, fibrillary type
> ![[Pasted image 20251126182720.png|300]]

##### Glioblastoma – IDH-wildtype (GBM, CNS WHO grade 4)
- Prototype **high-grade diffuse glioma** in adults.
- **Molecularly heterogeneous** but with hallmark alterations:
    - **IDH-wildtype**.
    - **EGFR amplification**.
    - Combined **Chr 7 gain / Chr 10 loss (7+/10−)**.
    - **TERT promoter mutation**.
- Frequently altered pathways:
    - **Ras/RTK/PI3K** axis altered in ~88%.
    - **p53 pathway** altered in ~87%.
- **TERT promoter mutations**
    - Common in adult diffuse gliomas (especially **oligodendrogliomas** and **IDH-wildtype GBM**).
    - ==Largely **mutually exclusive with ATRX mutations**:==
        - → **TERT** more common in **oligo**.
        - → **ATRX loss** more common in **astro**.

> [!NOTE]- GBM histology; pseudopalisading necrosis
> ![[Pasted image 20251126175203.png|300]]

> [!NOTE]- GBM histology; microvascular proliferation
> ![[Pasted image 20251126175333.png|300]]


> [!warning] Terminology
> 
> - "GBM" in the modern setting usually implies **IDH-wildtype grade 4** disease.
> 
> - IDH-mutant grade 4 tumors are now labeled **astrocytoma, IDH-mutant, CNS WHO grade 4**, not "GBM."

---

### 5. Pediatric High-grade Diffuse Gliomas

> [!info] Different biology from adult GBM  
> Pediatric HGG is driven less by IDH and more by **histone mutations** affecting chromatin and epigenetic regulation.

- Defined by mutations in **core histone proteins**:
    - Key residues: **lysine 27 (K27)**, **lysine 34 (K34)** on histone H3.

#### H3 K27-altered Diffuse Midline Glioma (DMG)
- **Location:** Midline structures (pons, thalamus, spinal cord).
- **Molecular hallmark:**
    - **H3 K27M mutation** or related alterations.
    - Leads to global impairment of **H3K27me3** (trimethylation).
- **WHO grade:** 4 (by definition).
- **Diagnostics:**
    - IHC for ==**H3K27M mutation**==.
    - ==Loss of **H3K27me3== staining** is supportive.

![[Pasted image 20251126190159.png|500]]
#### H3 G34-mutant Diffuse Hemispheric Glioma
- **Location:** Cerebral hemispheres.
- **Mutation:** H3 G34R/V (glycine 34).
- **WHO grade:** 4.
- Typically in older children/adolescents with hemispheric masses.

---

### 6. [[Ependymoma]]

- **Heterogeneous** family of glial/neuroepithelial tumors with distinct **anatomic** and **molecular** subgroups.
#### Anatomic and molecular groups

1. **Supratentorial ependymoma**
    - More common in **pediatric** populations.
    - Often defined by **ZFTA (C11orf95)-RELA** or **YAP1** fusions (not detailed in talk but important in practice).
        
2. **Posterior fossa ependymoma**
    - Predominantly **pediatric**.
    - **Posterior fossa group A (PFA)**:
        - Shows **loss of H3K27me3**, similar to DMGs.
        - Worse prognosis than PFB.
            
3. **Spinal ependymoma**
    - Often **indolent**, usually adults.
    - Frequently associated with **NF2** alterations.

> [!NOTE]- Ependymoma histology
> ![[Pasted image 20251126184138.png|400]]

> [!NOTE]- Ependymoma clearcell variant
> ![[Pasted image 20251126184306.png|400]]

> [!note]  
> Ependymomas are now heavily stratified by **location + methylation class**, which trumps subtle histologic differences for prognosis.

---

### 7. Pediatric Low-grade Neuroepithelial Neoplasms (LGG)

- A **constellation** of multiple entities, some well-defined, others still evolving.
- Examples:
    - **Pilocytic astrocytoma**
    - **Pleomorphic xanthoastrocytoma (PXA)**
    - **Angiocentric glioma**
    - Dysembryoplastic neuroepithelial tumor (DNET), ganglioglioma, etc.

#### General features

- Often **indolent** with favorable prognosis.
- Histology can show **overlapping features**, making diagnosis challenging on morphology alone.
- Strong involvement of **MAPK pathway alterations**, e.g.:
    - **BRAF-KIAA1549 fusions** (pilocytic astrocytoma).
    - **BRAF V600E mutations** (PXA, ganglioglioma).
    - FGFR and NTRK fusions in some entities.
- **Reference:** Ryall et al., _Cancer Cell_ 2020 – integrated molecular and clinical analysis of ~1000 pediatric LGG.

> [!info]  
> In pediatric LGG, **molecular definition** (e.g., specific fusion/mutation) often guides prognosis and eligibility for **targeted therapy** (e.g., BRAF/MEK inhibitors).

---

### 8. [[Meningioma]]

- Tumors of the **arachnoid cap cells**, typically **dural-based**.
- Often attached to dura; can involve skull and venous sinuses.

#### Histologic features
- Classic patterns:
    - Whorls.
    - **Psammoma bodies** (calcified concentric structures).

> [!NOTE]- Meningioma histology; whorls and psammoma bodies
> ![[Pasted image 20251126183833.png|500]]

#### Molecular features
- Distinct molecular signatures often correlate with **anatomic location**.
- **NF2-mutant** vs **non-NF2** meningiomas:
    - NF2-mutant: more common convexity/posterior fossa.
    - Non-NF2: skull base, often harbor:
        - **TRAF7**, **KLF4**, **AKT1**, **SMO**, or **POLR2A** mutations (from Clark et al., _Science_ 2013).

#### Grading and proliferative activity

> [!note] Proliferation is key  
> **Mitoses per 10 high-power fields (HPF)** and other atypical features drive grading.

- **WHO Grade 1**
    - Majority of meningiomas; low recurrence risk when completely resected.
- **WHO Grade 2 (Atypical)**
    - Defined by:
        - ==4–19 mitoses per 10 HPF==, and/or
        - Certain histologic features (brain invasion, chordoid/clear cell).
    - Includes **solitary fibrous tumor** in older schemes, but in modern classification, SFT and meningioma are distinct.
        - SFT:
            - "Patternless pattern," fibrous with **staghorn vasculature**.
            - Driven by **NAB2–STAT6 fusion**.
            - STAT6 nuclear IHC positivity is characteristic.
- **WHO Grade 3 (Anaplastic)**
    - ==≥20 mitoses per 10 HPF== or frankly malignant features.
    - Molecular high-risk markers:
        - **TERT promoter mutation**
            - Strongly associated with **poor outcomes** and typically high-grade behavior.
        - **CDKN2A homozygous deletion**
            - Correlates with **aggressive disease** and high recurrence risk.

---

### 9. [[Medulloblastoma]]

- Arises in the **posterior fossa** (cerebellum).
- **Prone to ==CSF dissemination**== along neuraxis.
- Treatment can be **curative**, but with significant long-term morbidity in children (neurocognitive, endocrine, hearing).

#### Histology
- Classic **"small round blue cell tumor"**.
- All are **CNS WHO grade 4**.
- Histologic variants:
    - **Large cell/anaplastic**
        - Associated with **worse outcomes**.
    - **Nodular/desmoplastic**
        - Generally **better prognosis**, especially in SHH-subgroup infants/children.

> [!NOTE]- Medulloblastoma histology; blue cell tumor
> ![[Pasted image 20251126184446.png|400]]

#### Molecular subgroups

Four major groups:

1. **WNT-activated**
    - Best prognosis; nuclear β-catenin accumulation.
        
2. **SHH-activated**
    - Intermediate prognosis; often associated with desmoplastic/nodular morphology.
        
3. **Group 3**
    - Often MYC-amplified, high risk, higher rate of metastasis.
        
4. **Group 4**
    - Most common; intermediate prognosis; fewer defining single-gene alterations.

> [!info]  
> In practice, **subgroup (WNT/SHH/3/4)** is now integral to **risk stratification** and clinical trial design.

---

### 10. CNS Lymphoma

- Typically **primary CNS diffuse large B-cell lymphoma (DLBCL)**.
- **Immunophenotype:**
    - **CD20+** B cells.
    - Often CD79a+, PAX5+, with high Ki-67.
- **Molecular alterations:**
    - Involve **B-cell receptor (BCR) signaling** and downstream survival pathways (e.g., MYD88, CD79B).
- **Variant:** Intravascular (in situ) lymphoma
    - Tumor cells confined to **vascular lumina**; can be subtle and easily missed on small biopsies.

> [!NOTE]- PCNSL histology; perivascular growth of large atypical lymphoid cells
> ![[Pasted image 20251126184802.png|500]]
---

### 11. Epigenetic Profiling

> [!summary]  
> DNA methylation profiling has become a powerful tool to classify CNS tumors, often **reclassifying or refining "NOS/NEC" diagnoses**.

- **Key paper:** Capper et al., _Nature_ 2018.
    - TSNE maps of tumors based on **CpG methylation profiles** group tumors by developmental lineage.
- **Principles:**
    - **CpG methylation patterns** reflect:
        - Cell-of-origin.
        - Developmental lineage.
        - Tumor-specific epigenetic changes.
- **Clinical use:**
    - **DNA methylation arrays** are used when:
        - Histology and routine molecular testing are **inconclusive**.
        - Tumor shows **unusual features** or discordant markers.
    - Output can:
        - Confirm a suspected entity.
        - Classify difficult tumors into **methylation classes** that have prognosis and therapy implications.
        - Identify **novel CNS tumor entities** that do not clearly fit existing WHO categories.

Capper et al., _Nature_ 2018
![[Pasted image 20251122062100.png]]

> [!tip]  
> When you and your pathologist are stuck with "CNS tumor, NOS/NEC," consider sending tissue for **DNA methylation profiling**—especially in **pediatric** and **midline/posterior fossa** tumors where the yield is high.

---

## Radiotherapy 

Speaker: **Helen Shih**  
---

> [!summary] TL;DR
> 
> - **Most cranial RT** is photon-based, with SRS or conventional fractionation depending on target and context.
> 
> - **Protons** are reserved for select indications (large volumes, retreatment, proximity to critical structures).
> 
> - **TTFields** add an OS benefit in _newly diagnosed GBM_ (with adjuvant TMZ); their role in recurrence is mainly QoL.
> 
> - **RT strategies** differ for GBM, lower-grade gliomas, metastases, and meningiomas, but are all governed by target volume, dose constraints, and expected survival.

---

### 1. Basic principles of radiotherapy

#### 1.1 What "radiotherapy" means

- **Most commonly**: ionizing radiation.
- **Primary mechanism**: DNA damage
    - Direct double-strand breaks.
    - Indirect injury via **free radical** formation (water radiolysis).

**Radiation sources**
- **Photons / electromagnetic radiation**
    - X-rays, γ-rays.
- **Particles**
    - Electrons
    - Protons
    - Neutrons (rare in current neuro-onc practice)

---

### 2. Modalities

#### 2.1 Photon radiotherapy
- **Most cranial RT is photon-based.**

**Depth–dose characteristics**
- Typical **photon depth–dose curve**:
    - Build-up region just below the surface.
    - Peak dose near surface (a few mm to ~1–2 cm, depending on energy).
    - Gradual dose fall-off with depth, with **exit dose** beyond target.

**Bragg peak** = sharp depth–dose maximum of charged particles (protons, heavier ions) with rapid distal fall-off.
![[Pasted image 20251122062800.png|300]]

**Common techniques**
- **Conventional / 3D-CRT**
    - Forward-planned, beams shaped to target; still used for simpler volumes.
- **IMRT (Intensity Modulated RT)**
    - Inverse-planned; modulates fluence across beams to spare OARs.
- **VMAT (Volumetric Modulated Arc Therapy)**
    - Arc-based IMRT; gantry rotates while delivering modulated dose for efficient conformal treatment.

##### Stereotactic radiosurgery (SRS) – photon based
- High-dose, highly conformal; 1–5 fractions typically.
- Platforms:
    - **Gamma Knife**
    - **Gyroscopic linac** (e.g., CyberKnife-style robotic systems)
    - **Robotic or conventional linacs** with SRS capability.
- Typical indications:
    - Small brain metastases
    - Meningiomas (small, well-defined)
    - Vestibular schwannomas
    - Pituitary adenomas and select skull base lesions

![[Pasted image 20251126194415.png|400]]

---

#### 2.2 Proton radiotherapy

**Depth–dose**
- Characteristic **Bragg peak**:
    - Low entrance dose.
    - Sharp rise to high dose at a configurable depth (Bragg peak).
    - Minimal exit dose beyond the target.
- Clinically: **less collateral dose** to normal tissue, particularly distal to target.

**Key indications (neuro)**
- **Larger volumes**
    - e.g., **craniospinal irradiation** (medulloblastoma, leptomeningeal disease) to spare heart/lungs/bowel.
- **Requirement for high total dose**
    - Where photon dose would exceed safe tolerance of adjacent critical structures.
- **Near radiation-sensitive structures**
    - Optic pathways, pituitary/hypothalamus, cochlea, brainstem, spinal cord.
- **Secondary tumor risk**
    - Observational data: **lower incidence of radiation-induced meningioma vs photons** (~50% reduction in some series; mainly pediatric long-term follow-up).

---

#### 2.3 Tumor Treating Fields (TTFields)

- **Non-ionizing EM fields**
    - Low intensity, intermediate frequency, alternating electric fields.
- **Proposed mechanisms**
    - Disruption of **microtubule polymerization** → abnormal mitotic spindle.
    - **Mitotic catastrophe** and apoptosis.
    - Possibly effects on replication fork, DNA repair, and membrane proteins.

**Clinical use**

- **Newly diagnosed GBM**
    - Delivered via scalp arrays, worn **≥18 h/day**.
    - **Given with adjuvant temozolomide** (post-RT phase).
    - Trials show **improved OS and PFS** vs TMZ alone.
- **Recurrent GBM**
    - Survival: non-inferior to chemo in older trial; **better QoL and function**, but no clear OS gain vs standard salvage chemo.
- **Other histologies**
    - Survival benefit signals in **GBM**; data emerging for **NSCLC with brain metastases** (clinical trials).

---

#### 2.4 Brachytherapy

- **Common isotopes**
    - Iodine-125
    - Cesium-131
- **Typical use-case**
    - **Permanent implants** after planned tumor resection:
        - Goal: treat **microscopic residual disease** at the cavity margin.
- **Indications**
    - Selected **brain metastases** (esp. resection cavities).
    - Meningiomas (recurrent, residual, or in previously irradiated fields).
- **Planning**
    - Post-op CT used to **map dose distribution** retrospectively and for QA.

---

#### 2.5 Theranostics / radiopharmaceuticals

- **Concept**: combine **diagnostic imaging** and **targeted radiotherapy**.
- Often uses **same molecular target** for PET imaging and therapy.

**Classic example – SSTR2 (somatostatin receptor)**

- **Diagnostic:** Ga-68 DOTATATE PET
- **Therapeutic ("Ludotatate")**:
    - **Lu-DOTATOC**, **Lu-DOTA-JR**, etc.
    - Radiolabeled somatostatin analogs internalized after binding SSTR2.
- Pioneered in **prostate cancer** and **neuroendocrine tumors**, increasingly used for SSTR2-positive **intracranial meningiomas** and other skull base tumors.

---

### 3. Glioblastoma (GBM)

#### 3.1 General RT approach

- **Technique**: conventional fractionated external beam RT.
- **Target volume**
    - **GTV**: T1 contrast-enhancing lesion ± resection cavity.
    - **CTV**: GTV + involved **T2/FLAIR abnormality**.
    - **PTV**: CTV + **1–1.5 cm margin** for setup and microscopic spread (institution-specific).
- **Standard dose ([[Stupp Protocol]])**
    - **60 Gy in 30 fractions over 6 weeks** (2 Gy/fx).
    - Doses >60 Gy have **not shown added benefit** and increase toxicity.
- **Concurrent chemotherapy**
    - **Temozolomide (TMZ)** daily with RT.
- **Adjuvant chemotherapy**
    - 6–12 cycles adjuvant TMZ.
- **TTFields**
    - Offer additional **OS benefit** when added to adjuvant TMZ in motivated, compliant patients.

![[Pasted image 20251126192535.png|500]]
#### 3.2 Elderly / poor KPS GBM

- For **elderly** or **poor performance status**:
    - **Hypofractionated RT** favored:
        - e.g., **~40 Gy in 15 fractions (~3 weeks)**.
    - Rationale:
        - Comparable tumor control and OS in this subgroup.
        - **Better tolerance** and treatment completion rates.
    - Often combined with **TMZ** (and sometimes without in very frail patients).

#### 3.3 Bevacizumab + RT

- **Bevacizumab + RT**
    - Typically improves **PFS** and reduces steroid requirement.
    - **No consistent OS benefit** in newly diagnosed GBM.
    - Reserved for:
        - Symptomatic edema/"pseudoprogression."
        - Recurrent disease.

---

### 4. Non-GBM Gliomas

#### 4.1 General principles

- **Fractionated external beam RT** (photon, or proton in select cases).
- **Targeting**: similar to GBM
    - T1 enhancing ± T2/FLAIR abnormalities + margin (smaller margins in low-grade where appropriate).

#### 4.2 IDH-wildtype (high-risk astrocytoma)

- Treated akin to higher-grade disease:
    - **54–60 Gy** in conventional fractions over ~6 weeks.
    - Often **concurrent and adjuvant TMZ** (institution-specific).

#### 4.3 IDH-mutant gliomas

- **Dose**: ~**50–59 Gy** in 1.8–2 Gy fractions over 6 weeks.

**Adjuvant systemic therapy**

- **IDH-mutant, 1p/19q co-deleted oligodendroglioma (WHO 2–3)**
    - RT + **adjuvant PCV** (procarbazine, lomustine/CCNU, vincristine) based on long-term survival benefit.
- **IDH-mutant, non-codeleted astrocytoma**
    - RT + **adjuvant temozolomide** common (vs PCV, which is more toxic).
- Choice between **PCV vs TMZ** depends on:
    - Molecular profile.
    - Age/comorbidities and tolerance for myelosuppressive regimens.
    - Institutional practice and guideline adherence.

---

### 5. [[Brain metastases]]

Management is individualized by **number, size, location, histology, and prognosis**.
![[Pasted image 20251126194702.png|600]]
#### 5.1 1–3 small metastases (< 2 cm)
- **Preferred**: SRS to each lesion.
- Many centers now consider ==SRS for **up to 10 metastases**==, particularly when:
    - Cumulative tumor volume is limited.
    - Controlled systemic disease.
    - To avoid neurocognitive toxicity of WBRT.
#### 5.2 Intermediate lesions (2–4 cm)
- Need to consider:
    - **Location** (eloquent vs non-eloquent, infratentorial vs supratentorial).
    - **Histology** (radiosensitive vs radioresistant).
    - **Patient factors** (KPS, systemic disease control).
- Options:
    - **WBRT alone** (less favored in limited-lesion setting now).
    - **Pre-op SRS** to intact lesion.
    - **Post-op RT** to resection cavity (fractionated SRS or 3D/IMRT).
    - **Local fractionated RT** without surgery in selected cases.
#### 5.3 Large, single metastasis
- **First-line**: **surgical resection** if resectable and patient fit.
- Post-op options:
    - **Post-op WBRT**
        - Better intracranial control but worse neurocognition.
    - **Local fractionated RT** to cavity (often preferred now: 24–30 Gy in 3–5 fx).
    - **Post-op SRS to cavity**
        - Good local control.
        - Potential increased risk of **radiation necrosis** and **LMD** (leptomeningeal disease) vs WBRT.
#### 5.4 Multiple (numerous) metastases
- **WBRT** with neuroprotection strategies:
    - **Hippocampal avoidance** technique.
    - **Memantine** to help preserve cognitive function.
- SRS may still be used for dominant symptomatic lesions.

#### 5.5 Leptomeningeal disease (LMD)

- Goals are usually **palliation** and symptom control.
- Options:
    - **WBRT**
    - **Focal RT** to symptomatic sites.
    - Systemic or intrathecal therapy, clinical trials.
    - Early **palliative care / hospice** involvement.
- **Craniospinal irradiation**
    - Selected use, mostly in **younger, fit patients** (e.g., medulloblastoma, high-risk LM spread).
    - Can yield **improved OS/PFS** compared with focal RT, at the cost of significant marrow and systemic toxicity.

---

### 6. [[Meningioma]]

#### 6.1 General strategy

- **Small, asymptomatic**:
    - **Observe** with serial imaging.
- **Large / symptomatic / progressive**:
    - **Surgery** is first-line when safe.

#### 6.2 Grade-specific

- **WHO Grade I**
    - **Gross total resection (GTR)** often curative.
    - **RT not routinely required** after Simpson I–III resection.
    - **RT indicated** for:
        - Small unresectable lesions (skull base/optic nerve sheath).
        - Residual disease after subtotal resection.
        - Recurrence.
- **WHO Grade II–III**
    - Aim for **maximal safe resection**.
    - **Post-op RT** recommended even with GTR:
        - Typical dose: **~60 Gy** in fractions for high-risk grade II/III.
        - RT outcomes better with **minimal residual disease** (volume matters).
    - **Grade III**:
        - High rate of local failure **despite RT**; prognosis remains poor.
        - Escalating dose may improve local control but increases toxicity (brain necrosis, cognitive decline, radionecrosis).

---

### 7. Practical steps in RT delivery

#### 7.1 Simulation and planning

1. **Immobilization**
    - Custom **thermoplastic mask** (for brain).
    - Bite blocks or frames for SRS.
        
2. **Imaging**
    - **Planning CT** with **MRI fusion**.
    - Sometimes PET or functional imaging for complex cases.
        
3. **Target definition**
    - **GTV/CTV/PTV** defined with margins for microscopic spread and setup error.
        
4. **Organs at risk (OARs)**
    - Optic nerves/chiasm, brainstem, cochlea, hippocampi, pituitary, spinal cord, etc.
        
5. **Planning technique**
    - **3D-CRT** vs **IMRT** vs **VMAT**:
        - 3D-CRT: simpler geometry, more dose to surrounding tissue.
        - IMRT: highly conformal, useful near critical structures.
        - VMAT: efficient IMRT delivered via arcs.
            
6. **Daily setup**
    - **Cone-beam CT (CBCT)** or similar:
        - Rigid or deformable **registration** to planning CT.
        - Adjust couch shifts before each fraction.

#### 7.2 SRS-specific workflow

- Similar simulation, but with:
    - Higher immobilization precision (frames or dedicated masks).
    - Smaller PTV margins (1–2 mm typical).
    - Often **1–5 fractions**:
        - 1 fraction for small lesions away from critical structures.
        - Hypofractionated SRS (e.g., 3–5 fx) for larger/eloquent lesions.
- Common SRS targets:
    - **Brain metastases**
    - **Meningiomas**
    - **Vestibular schwannomas**
    - **Pituitary adenomas** and other benign skull base tumors.

---

### 8. General aspects of RT

#### 8.1 Fractionation and logistics

- **Conventional fractionation**
    - Daily (Mon–Fri), **5 days/week**.
    - Typically **2–7 weeks** in duration.
    - Time on table: **10–20 minutes** per day.
- **SRS**
    - Usually single session; **20–60 minutes**.
- **Patient experience**
    - Radiation is **not felt**: no heat or pain during delivery.
    - Fatigue and other symptoms are delayed.

#### 8.2 Factors in RT plan design

- **Tumor-related**
    - Histology, grade, radiosensitivity, molecular features.
    - Size, volume, and location (eloquent cortex, brainstem, optic apparatus).
- **Treatment-related**
    - Total dose and fractionation.
    - Prior radiation (re-irradiation constraints).
- **Patient-related**
    - Comorbidities, performance status, life expectancy.
    - Baseline cognition and neurologic deficits.

---

#### 8.3 Side effects

> [!warning] Toxicity overview
> 
> - Acute effects are common but usually self-limited.
> 
> - Late effects can be devastating (necrosis, stroke, second tumors) and drive many planning decisions.

**Acute (during or shortly after RT)**
- Fatigue
- Nausea
- Headache
- Erythema / skin irritation at entry sites
- **Alopecia** (usually patchy, field-dependent)
- Transient **worsening of neurologic symptoms** from edema
- Delayed wound healing (esp. post-craniotomy)

**Late (months–years)**
- Persistent fatigue
- **Hypopituitarism** (with sellar/parasellar or cranial base fields)
- **Brain parenchymal injury**:
    - Leukoencephalopathy, cognitive decline
    - Focal **radiation necrosis**
- **Cranial neuropathies**:
    - Visual pathway injury (optic neuritis/neuropathy, chiasmal damage)
    - Hearing loss (cochlear dose)
- **Vascular injury**
    - Vasculopathy, vessel stenosis.
    - Increased **CVA risk** in long-term survivors (esp. peds).
- **Second malignancy**
    - Lifetime risk ~**1%** for radiation-induced brain tumors (e.g., meningioma, glioma).

**SRS-specific**
- ~**90%**: no significant new symptoms.
- ~**10%**:
    - Transient fatigue, headache.
    - Seizures (rare).
    - **Late radiation necrosis** (focal edema, mass effect; often steroid-responsive, sometimes needs bevacizumab or surgery).

---
## Chemotherapy and Systemic Therapies 

**Speaker:** Lauren Schaff  

> [!summary] Key themes
> 
> - Understand basic chemo classes and where neurosurgeons intersect (e.g., timing, toxicity, coordination with RT).
> 
> - Recognize agents that penetrate CNS vs those that do not.
> 
> - Be aware of targeted and immuno-oncologic agents that can delay or modify the need for surgery/RT.

---

### 1. CNS Lymphoma – Treatment Phases

**Induction therapy**

- Goal: induce remission.
- Typically high-dose methotrexate-based regimens ± rituximab and other agents.
- Often delivered inpatient due to MTX logistics (see below).

**Consolidation therapy**

- Single or short course of intensive therapy.
- Goal: prevent early recurrence after remission.
- Modalities may include:
    - High-dose chemotherapy ± autologous stem cell rescue, or
    - Reduced-dose whole brain RT (WBRT) in some protocols.

**Maintenance therapy**

- Prolonged, lower-intensity therapy to maintain remission.
- Often oral or intermittent IV regimens; aims to delay relapse.

> [!note] Neurosurgical relevance
> 
> - Induction/consolidation regimens are myelosuppressive → perioperative planning for biopsies, shunts, Ommayas.
> 
> - WBRT and high-dose MTX have long-term neurocognitive implications – important in counseling and in shunt decisions.

---

### 2. Classical Chemotherapies

#### 2.1 Chemotherapy classes (by cell cycle)

- **Cell cycle non-specific**
    - Alkylating agents (e.g., cyclophosphamide, nitrosoureas).
- **Cell cycle specific**
    - **Phase-specific**
        - Antimetabolites
        - Antimitotic agents
- **Phase non-specific**
    - Alkylating agents
    - Platinum compounds

---

#### 2.2 Antimetabolites

_(typically S-phase specific)_

**Major subclasses**

- **Antifolates**
    - Methotrexate, pemetrexed
- **Pyrimidine antagonists**
    - 5-fluorouracil (5-FU), cytarabine
- **Purine antagonists**
    - 6-mercaptopurine

##### Methotrexate (MTX)

- **Mechanism**
    - Inhibits ==**dihydrofolate reductase**== → blocks production of tetrahydrofolic acid → impaired purine and thymidylate synthesis.
    - Halts DNA/RNA synthesis → cytotoxic in rapidly dividing cells.
- **CNS-specific considerations**
    - Requires **high doses** to achieve therapeutic CNS levels.
    - Often administered **inpatient** due to monitoring requirements.
- **Administration logistics**
    - **Continuous IV hydration** until MTX clearance documented
        - Goal: prevent **renal toxicity**.
    - **Urine alkalinization**
        - Prevents MTX crystallization in renal tubules.
    - **Leucovorin (folinic acid) rescue**
        - Systemic rescue to limit MTX toxicity.
        - Does **not** cross the BBB → does not negate anti-tumor effect within CNS.
    - Serial MTX levels to guide duration/intensity of leucovorin.
- **Clinical role**
    - **First-line backbone** of therapy for primary CNS lymphoma (PCNSL).
    - ≈ **90% overall response rate** when used in modern induction regimens.

> [!warning] Key toxicities – MTX
> 
> - Acute: nephrotoxicity, mucositis, myelosuppression.
> 
> - Delayed: leukoencephalopathy, especially with prior RT or IT MTX.
> 
> - Neurosurgical implication: careful timing of surgery relative to nadir and renal function.

---

#### 2.3 DNA-Damaging Agents

**General mechanism**

- Direct damage to DNA (cross-linking, strand breaks).
- **Alkylating agents**
    - Attach alkyl groups to DNA → cross-linking → impaired strand separation → failure of cell division → apoptosis.

**Common toxicities (class effect)**

- Myelosuppression
- Nausea, vomiting
- Alopecia
- Secondary malignancy (with cumulative exposure)

---

##### Temozolomide (TMZ) in glioma

- Part of **Stupp protocol** for GBM (NEJM 2005).
- **Concomitant phase (with RT)**
    - 75 mg/m² daily during 6 weeks of RT.
- **Adjuvant phase** (5-day cycles; "5 on, 23 off" q28 days)
    - Cycle 1: 150 mg/m²
    - Cycle 2+: 200 mg/m² (if tolerated)
- **Interactions**
    - Food → decreased absorption → administer on **empty stomach**.
    - Valproic acid (VPA) → increased myelotoxicity risk.
- **Toxicities**
    - Constipation (very common).
    - Nausea/vomiting (more prominent in adjuvant phase).
    - Fatigue.
    - Myelotoxicity, thrombocytopenia.
    - Overall "gentler" than many classic cytotoxics.
    - Increased risk with:
        - Female sex
        - Certain genetic polymorphisms (e.g., drug metabolism variants).

> [!note] Pearls – TMZ & neurosurgery
> 
> - MGMT promoter methylation status predicts benefit.
> 
> - Myelosuppression impacts timing of craniotomy, wound healing.
> 
> - Avoid peri-op VPA where possible if on TMZ.

---

##### Nitrosoureas

- **Agents**
    - Lomustine (**CCNU**), carmustine (**BCNU**).
- **Routes**
    - CCNU: oral
    - BCNU: IV (also used in wafer form for local delivery).
- **Features**
    - **Highly lipophilic** → excellent CNS penetration.
- **Toxicities**
    - Myelosuppression (often **delayed** and prolonged).
    - Pulmonary fibrosis with cumulative doses (esp. BCNU).
    - Hepatic and renal toxicity (with higher cumulative dosing).
- **Important interactions**
    - CCNU:
        - Valproic acid
        - Duloxetine (and other CYP-modulating agents)

---

##### Procarbazine (PCZ)

- Commonly used in:
    - **Oligodendroglioma** (as part of PCV regimen).
    - Some regimens for **CNS lymphoma** (e.g., R-MPV variants).
- **Drug interactions**
    - **Serotonergic agents** (SSRIs, SNRIs, TCAs, triptans)
        - Mild MAOI effect → risk of **serotonin syndrome**.
    - **Tyramine-containing foods** (aged cheeses, cured meats, certain wines)
        - Risk of **hypertensive crisis**.
    - **Ethanol** → disulfiram-like reaction possible.

> [!warning] Do-not-miss counseling
> 
> - Procarbazine = functional MAOI → always ask about antidepressants and diet.
> 
> - From a neurosurgical standpoint, unexpected hypertensive episodes peri-op should prompt a med review for PCZ.

---

#### 2.4 Anti-mitotics

**Class:** Vinca alkaloids (e.g., vincristine)
##### Vincristine
- **Use**
    - Component of **PCV regimen**:
        - P = procarbazine
        - C = CCNU (lomustine)
        - V = vincristine
    - Commonly used in **oligodendroglioma**.
- **Typical PCV cycle (approx. 6–8 weeks due to prolonged nadir)**
    - Day 1: CCNU
    - Day 8: Vincristine
    - Days 8–21: Procarbazine (oral)
    - Day 29: Vincristine
    - **Duration:** ~6 cycles (if tolerated).
    - **Monitoring:** PFTs (esp. with prior RT/bleomycin), CBC, liver function.
- **Toxicities**
    - Peripheral neuropathy (dose-limiting).
    - Constipation/ileus.
    - Rare but critical: autonomic neuropathy.

> [!danger] Route matters
> 
> - **Vincristine must never be given intrathecally** → uniformly fatal myeloencephalopathy.
> 
> - Neurosurgeons placing intrathecal catheters (Ommaya, IT chemo ports) should be absolutely clear with oncology/infusion teams about IT-eligible agents.

---

### 3. Targeted Therapies ("-inibs" and others)

#### 3.1 IDH Inhibitors

- **Pathophysiology**
    - Mutant IDH1/2 → production of **D-2-hydroxyglutarate (D2HG)** → altered histone methylation, DNA hypermethylation, defective collagen maturation, and a "glioma CpG island methylator phenotype".
- **Vorasidenib** (dual IDH1/2 inhibitor)
    - Studied in **IDH-mutant low-grade glioma (LGG)**.
    - Improved **PFS 22.6 mo vs 11.1 mo** with placebo; HR ≈ 0.39.
    - Once-daily oral agent.
    - Generally well tolerated.
    - Most common lab abnormality: **transaminitis**.

> [!tip] IDH inhibitors – neurosurgical angle
> 
> - May delay need for re-resection or RT in indolent IDH-mut LGG.
> 
> - Tissue diagnosis and accurate molecular profiling (IDH, 1p/19q, MGMT, ATRX) remain the foundation – biopsy quality matters.

---

#### 3.2 BTK Inhibitors (for CNS lymphoma)

- **Rationale**
    - B-cell receptor (BCR) and toll-like receptor (TLR) pathways upregulated in **CNS lymphoma**.
- **Use**
    - Typically in **relapsed/refractory** PCNSL or when high-dose MTX fails.
    - Often combined with other agents rather than true monotherapy.

##### Ibrutinib (1st generation BTK inhibitor)

- Monotherapy → modest PFS benefit (~4 months improvement).
- Usually used as **part of combination therapy** in practice rather than alone.
- **Adverse effects**
    - Cardiac: atrial fibrillation, other conduction abnormalities, hypertension.
    - GI: nausea, vomiting, diarrhea.
    - Dermatologic: rash.
    - MSK: myalgias, arthralgias.
    - Hematologic: cytopenias.
    - Infectious:
        - **Opportunistic infections** (e.g., aspergillosis, PCP).
        - Many patients placed on **prophylactic antibiotics/antifungals**.
- **Other BTK inhibitors**
    - Second-generation agents (e.g., acalabrutinib, zanubrutinib, tirabrutinib) with variable CNS penetration and toxicity profiles; evolving data in PCNSL.

> [!warning] Fungal risk
> 
> - Ibrutinib-associated invasive aspergillosis can present with **new brain lesions** – imaging can mimic tumor progression or abscess.
> 
> - Neurosurgeons may be asked to biopsy lesions in heavily pre-treated patients; keep drug history in mind.

---

#### 3.3 BRAF/MEK Inhibitors

- **Mechanism**
    - Target the MAPK pathway in **BRAF V600E–mutated tumors**.
- **Examples**
    - BRAF inhibitors: vemurafenib, dabrafenib, encorafenib.
    - MEK inhibitors: trametinib, binimetinib.
- **Neuro-oncologic uses**
    - Melanoma brain metastases.
    - BRAF-mutant gliomas (esp. pediatric LGG).
    - BRAF-mutant papillary craniopharyngioma (increasingly relevant).

> [!note] Practical point
> 
> - BRAF/MEK combinations can achieve rapid intracranial responses → can sometimes **defer or limit RT** in select patients.

---

#### 3.4 Tyrosine Kinase Inhibitors (TKIs)

- **Mechanism**
    - Bind ATP-binding sites on receptor tyrosine kinases → inhibit signaling.
- **Relevant targets**
    - EGFR (e.g., **osimertinib** for EGFR-mutant NSCLC).
    - ALK, ROS1, NTRK, RET, others.

##### Osimertinib for EGFR-mutant NSCLC brain metastases

- Excellent **CNS penetration**.
- High intracranial response rates.
- Can **delay or avoid RT** in some patients with good systemic control.

> [!info] Overall impact on RT/surgery
> 
> - TKIs can:
> 
>     - Improve PFS in brain metastases.
> 
>     - Allow deferral of WBRT and associated neurocognitive toxicity.
> 
> - OS benefit is variable; decisions should be individualized based on systemic disease and performance status.

---

### 4. Immuno-oncology Agents

#### 4.1 Monoclonal Antibodies

- **Targets**
    - VEGF, CD20, CD30, and many others depending on tumor type.
- **General toxicity**
    - Infusion reactions (fevers, chills, hypotension).
    - Hypersensitivity reactions.

##### Bevacizumab (anti-VEGF)

- **Roles in neuro-oncology**
    - Reduces **cerebral edema** (GBM and other tumors).
    - Steroid-sparing agent in symptomatic edema/radiation necrosis.
    - Improves **PFS** in GBM but **no OS benefit** demonstrated.

> [!tip] Neurosurgical use-case
> 
> - Helpful in decreasing peritumoral edema and steroid dose before surgery or radiosurgery.
> 
> - Be cautious with wound healing – ideally avoid close to major cranial/spine surgery if possible.

---

#### 4.2 Checkpoint Inhibitors

- **Examples**
    - Anti–PD-1: nivolumab, pembrolizumab.
    - Anti–PD-L1: atezolizumab, durvalumab.
    - Anti–CTLA-4: ipilimumab.
    - Anti–LAG-3 and others in trials.
- **Efficacy**
    - Particularly effective in **melanoma**, some NSCLC, RCC, and other immunogenic tumors.
    - Active in many **brain metastasis** settings.
- **Immune-related adverse events (irAEs)**
    - Graded 1–4:
        - **Grade 1:** usually continue therapy with monitoring.
        - **Grade 4:** permanent discontinuation (except some endocrine toxicities).
    - Managed primarily with **steroids**; severe cases may require additional immunosuppression (e.g., infliximab, mycophenolate).
    - Common sites:
        - Endocrine: thyroiditis (very common), hypophysitis, adrenalitis.
        - GI: colitis.
        - Pulmonary: pneumonitis.
        - Hepatic: hepatitis.
        - Skin: rash, pruritus.

> [!warning] Intersection with neurosurgery
> 
> - Be alert to **hypophysitis** (headache, visual change, hyponatremia, pituitary enlargement).
> 
> - Peri-operative steroids needed for irAEs can blunt ICP-related signs and alter wound healing.

---

#### 4.3 CAR T-cell Therapy

- **Concept**
    - Patient's T cells are genetically modified ex vivo to express chimeric antigen receptors (CARs) targeting specific tumor antigens.
    - Used predominantly in **hematologic malignancies** (e.g., CD19+ B-cell leukemias/lymphomas).
- **Key toxicities**
    - **Cytokine Release Syndrome (CRS)**
        - Systemic inflammatory reaction: fever, hypotension, hypoxia.
        - Managed with:
            - Tocilizumab (IL-6 blockade).
            - Steroids if severe or refractory.
    - **Immune Effector Cell–Associated Neurotoxicity Syndrome (ICANS)**
        - Manifestations: encephalopathy, aphasia, seizures, focal deficits.
        - Quantified by **ICE score**.
        - Managed with:
            - Close neurocritical care monitoring.
            - High-dose steroids for severe cases.
            - Seizure prophylaxis as needed.

> [!danger] Neurosurgical implication
> 
> - ICANS can mimic TBI, meningitis, or tumor-related edema.
> 
> - Imaging may show diffuse edema; craniotomy is rarely helpful and typically contraindicated unless another focal process exists (e.g., hemorrhage, abscess).

---

### 5. Practical Neurosurgical Pearls

- Always **review systemic therapy history** (MTX, bevacizumab, TKIs, BTK inhibitors, CAR T) before:
    - Planning craniotomy or spine surgery.
    - Placing EVDs, shunts, Ommayas.
    - Deciding on RT timing relative to surgery.
- Be proactive in:
    - Coordinating timing around **myelosuppressive nadirs**.
    - Discussing **wound healing and infection risks** with oncology (steroids, bevacizumab, ibrutinib).
    - Leveraging systemic responses (e.g., TKIs, IDH inhibitors, BRAF/MEK) to **minimize invasive interventions** when appropriate.

## Brain Metastases – Management

---

> [!summary] At-a-glance
> 
> - Brain metastases are the **most common brain tumor** in oncology practice.
> 
> - Local therapy is driven by **number, size, and symptoms**: surgery + SRS for dominant lesions; SRS over WBRT whenever feasible.
> 
> - For many histologies, **CNS-active targeted agents** now compete with or complement RT.
> 
> - In NSCLC/other solid tumors, **drug activity and mechanism matter more than MW or "BBB penetration" dogma**.

---

### 1. Epidemiology & Primary Sites

- **Most common brain tumor overall**
    - ~**160–200k** brain metastasis cases/year
    - Compare: ~**25k** cases/year for gliomas
- **Presentation**
    - **5–10%** of cancer patients present with brain metastasis as the **first** manifestation.
- **Most common primaries**
    - Lung
    - Breast
    - Melanoma
    - Renal cell carcinoma
    - Colon
    - Lymphoma
- **Less common primaries**
    - Prostate
    - Liver

---

### 2. Screening & Initial Workup

#### 2.1 Who to screen

- **Any cancer patient with neurologic symptoms**
    - Headache, seizures, focal deficits, cognitive/behavioral changes, gait issues, etc.
- **Early-stage systemic disease**
    - Stage I–II: **no routine screening** in asymptomatic patients.
- **Advanced disease**
    - Stage III–IV: low threshold to **screen with brain MRI** even if minimally symptomatic.

#### 2.2 Imaging modality

- **MRI brain with gadolinium**
    - Preferred modality; most sensitive for small metastases and LMD.
- **PET-CT**
    - **Not adequate** as a stand-alone screening tool for brain metastases.
    - Limited resolution and physiologic brain uptake mask small lesions.

---

### 3. Local Treatment Strategy

#### 3.1 Number-based approach (simplified clinical framework)

- **1–3 metastases**
    - **SRS** if lesions **< 2 cm** and not causing major mass effect.
    - **Surgery → SRS** to resection cavity:
        - Preferred over **surgery → WBRT** in most modern practices to limit neurocognitive toxicity.
- **> 3 metastases**
    - **WBRT vs SRS**:
        - SRS increasingly used for multiple lesions if total intracranial tumor volume is reasonable and performance status good.
        - WBRT still appropriate for:
            - Very numerous lesions.
            - Poor performance status.
            - Diffuse involvement.

> [!info] Nuance
> 
> - "1–3 lesions = SRS, >3 = WBRT" is the **classic teaching**, but many centers now treat **up to ~10 lesions** with SRS if total volume and patient factors are favorable.

#### 3.2 Indications for surgery

- **Tissue diagnosis**
    - When primary is unknown or histology/molecular profile may change systemic therapy.
- **Molecular profiling**
    - Access to current **driver mutations, fusions, PD-L1** etc. for targeted therapy/IO.
- **Mass effect / emergent decompression**
    - Large symptomatic lesion(s) with:
        - Significant edema
        - Midline shift
        - Risk of herniation
- **Steroid dependence**
    - Inability to wean steroids due to mass effect → resection to relieve pressure.
- **Concern that RT will worsen swelling**
    - For large lesions adjacent to critical structures, surgery may reduce risk of **post-RT edema** and symptomatic deterioration.

---

### 4. Radiation Toxicity

- **Imaging changes**
    - Progressive **T2/FLAIR hyperintensity** and **cortical/subcortical atrophy** over time.
- **Clinical picture**
    - "**Accelerated dementia**" with WBRT:
        - Cognitive decline, memory loss, executive dysfunction.
- **SRS vs WBRT**
    - **SRS**:
        - Better tolerated cognitively.
        - Focal risk of radiation necrosis.
    - **WBRT**:
        - More global neurocognitive toxicity.
        - Still valuable for extensive disease or when SRS not feasible.

> [!warning] Practical point  
> In patients expected to live **years**, avoid WBRT whenever reasonable — prioritize **SRS + systemic control**.

---

### 5. BBB, Drug Delivery, and Pharmacology

- **Gd enhancement ≈ disrupted BBB**
    - **Gd³⁺ enhancement** on MRI indicates **blood–brain barrier breakdown** at tumor sites → improves local drug access.
- **Drug delivery vs drug activity**
    - **"Drug delivery doesn't matter as much as drug activity"** in the brain met context:
        - Small molecules with "good BBB penetration" can still fail if **tumor biology is resistant**.
        - Example: **Methotrexate (MTX)**
            - **Low molecular weight**, yet **limited efficacy** in many solid tumor brain metastases.
- **Key message**
    - **Mechanism of action, potency, and resistance profile** are more important than MW alone.
    - Modern TKIs and ADCs can achieve meaningful CNS concentrations even if classic BBB metrics look mediocre.

---

### 6. Systemic Therapies with CNS Activity

#### 6.1 General observation

- In modern series:
    - **Use of SRS in the setting of CNS-active chemotherapy/targeted agents does _not_ clearly dictate survival**, especially when systemic disease drives prognosis.

---

#### 6.2 EGFR-mutant NSCLC

- **Osimertinib**
    - Improves **CNS PFS** and decreases risk of the brain as **site of first progression** in EGFR-mut NSCLC.
- **Osimertinib + platinum–pemetrexed chemo**
    - **FLAURA2** (JCO 2023):
        - Combination improves **PFS and OS** in patients with CNS metastases.
        - Cost of increased efficacy = **higher toxicity**.

---

#### 6.3 ALK-positive NSCLC

- **Lorlatinib** (ALK TKI)
    - Profound brain responses in ALK-positive NSCLC.
    - **CROWN** phase 3 study (JCO 2022):
        - Marked intracranial response rate.
        - Delays time to CNS progression.

---

#### 6.4 HER2-positive Breast Cancer

- **Tucatinib**
    - CNS-active HER2 TKI.
    - **HER2CLIMB** trial:
        - Tucatinib + trastuzumab + capecitabine.
        - Demonstrated **CNS responses** and improved outcomes in HER2+ breast cancer with brain metastases.

---

#### 6.5 KRAS G12C NSCLC

- **Adagrasib**
    - KRAS G12C inhibitor with **documented CNS activity** in NSCLC brain mets.
    - Useful option when systemic and intracranial disease are both driven by KRAS G12C.

---

#### 6.6 RET-fusion NSCLC

- **Selpercatinib**
    - RET inhibitor with significant CNS penetration.
    - Provides intracranial responses in RET fusion-positive NSCLC.

---

### 7. Can RT Be Deferred in TKI-Eligible Patients?

> [!question] Deferring SRS in the era of CNS-active TKIs?
> 
> - Data show **no significant difference in PFS** between:
> 
>     - **SRS + TKI** vs **TKI alone** in select patients.
> 
> - However, there is **no consensus in the US** about routinely deferring SRS.

**Practical take:**

- Consider deferring SRS in:
    - Small, asymptomatic brain mets.
    - Strongly CNS-active TKI available (EGFR, ALK, RET, etc.).
- Still favor **early SRS** for:
    - Larger or symptomatic lesions.
    - Uncertain systemic control.
    - Poor access/adherence to TKI therapy or trial data.

---

### 8. Immunotherapy in NSCLC Brain Metastases

- **NSCLC vs melanoma**
    - IO benefit in NSCLC brain mets is **less dramatic** than in melanoma.
- **Pembrolizumab**
    - Intracranial response rate roughly **~30%** in NSCLC brain metastases.
- IO often used:
    - With SRS (concurrent or sequential).
    - As part of systemic regimen for PD-L1–positive disease.

---

### 9. Antibody–Drug Conjugates (ADCs) & Novel Targeted Agents

> [!info] Take-home  
> ADCs can have substantial intracranial activity **despite their size**, again reinforcing that **MOA > MW**.

- **Trastuzumab–deruxtecan (T-DXd)**
    - Produces responses in **HER2+ breast cancer** with CNS involvement (including brain mets; strong data in HER2+ disease).
- **Amivantamab + lazertinib**
    - EGFR-targeted bispecific antibody + TKI combination.
    - Extends **PFS and OS** in **NSCLC brain metastases and leptomeningeal disease** in emerging data.
- **B7-H3 antibody–topoisomerase inhibitor ADC**
    - Investigational; **IDEATE-Lung01** trial.
    - Reported **~69% response rate** (early data) in selected NSCLC patients.

---

### 10. Tumor Treating Fields (TTFields) in Brain Mets

- **METIS trial**
    - TTFields + **best standard of care** in **NSCLC without classic driver mutations** (EGFR, ALK, ROS, BRAF).
    - Results:
        - Improved **time to intracranial progression**.
        - **No significant change** in median overall survival.
- Role:
    - Adjunctive option in carefully selected patients.
    - Practical adoption still evolving (device burden, adherence).

---

### 11. Leptomeningeal Metastasis (LMD)

#### 11.1 Epidemiology & clinical features

- Occurs in **5–8%** of all cancer patients.
- Frequently **underdiagnosed**:
    - Present at **autopsy in ~20%** of cancer patients.
- Incidence is **increasing** with improved systemic survival.
- Symptoms:
    - Nausea/vomiting
    - Headache
    - Seizures
    - Multifocal, non-specific decline ("**doing poorly**")
    - Cranial neuropathies, radicular pain, gait disturbance, etc. (often subtle early).

#### 11.2 Risk factors and iatrogenic aspects

- LMD risk appears higher with certain patterns:
    - Focal RT after surgery for parenchymal mets may **increase LMD risk**.
        - Approximate reported rates:
            - Breast: **~28%**
            - Lung: **~18%**
- Likely reflects:
    - **Surgical cavity + focal RT** selecting for leptomeningeal spread while preserving longer survival.

#### 11.3 CSF diagnostics – beyond cytology

- **CSF cytology**
    - Classic standard; low sensitivity, especially early.
- **CTC-based platforms**
    - **CellSearch**:
        - Isolates circulating tumor cells (CTCs) in CSF using **EpCAM**.
        - CTC burden correlates with survival.
        - Limitation: many cancers **lose EpCAM** or never express it (even in breast and lung).
- **Multi-antibody capture**
    - Uses **11-antibody cocktail** to capture more CTCs.
    - More sensitive than cytology in early work.
    - **CNSide technology** (Nagpal, Louis, Rogowski; ASN/SNO Mets 2025 cohort):
        - Proprietary CTC + molecular profiling platform.
        - Early data suggest improved sensitivity and ability to track treatment response.
- **cfDNA (cell-free DNA) in CSF**
    - Tumor-derived cfDNA in CSF may **mirror clinical course**:
        - Emerging as a tool for:
            - Detecting minimal residual disease.
            - Monitoring response/resistance.
            - Identifying targetable alterations in LMD.

#### 11.4 Treatment & trials

- Management is typically **palliative with intent to prolong meaningful function**:
    - Focal or craniospinal RT (in select cases).
    - Systemic or intrathecal therapy (TKI, IO, chemo) depending on biology.
    - Enrollment in **trials** whenever possible.
- Example trials:
    - **TUXEDO-3**
        - Ongoing/early-phase trial (HER2-directed therapy in CNS disease/LMD context; details evolving).
- Early and frank discussion of:
    - Prognosis.
    - Goals of care.
    - Role of supportive/palliative measures.

---

> [!todo] For local practice notes
> 
> - Add **institution-specific algorithms** for:
> 
>     - SRS vs WBRT thresholds (by lesion number/volume).
> 
>     - Standard molecular profiling panel for CNS disease.
> 
>     - Pathways for sending CSF to **CTC / cfDNA / CNSide** platforms.

## Management of Low-Grade (IDH-mutant) Gliomas

**Speaker:** Jennie W. Taylor (UCSF)

> [!summary] Core concepts
> 
> - Diffuse IDH-mutant LGGs affect younger adults and carry prolonged survival (often 5–20+ years).
> 
> - Extent of resection and residual tumor volume strongly correlate with OS and risk of malignant transformation.
> 
> - RT and chemotherapy (especially RT + PCV) clearly improve PFS and OS in higher-risk patients, but at the cost of long-term toxicity.
> 
> - There is an ongoing, unresolved debate: **PCV vs TMZ** in IDH-mutant gliomas.
> 
> - IDH inhibition with **vorasidenib** (INDIGO) adds a new, disease-modifying, low-toxicity option that can delay traditional RT/chemo.

---

### Background

- **Diffuse LGGs** represent a relatively small proportion of all primary brain tumors.
- **IDH-mutant gliomas**
    - Typical age at diagnosis: **36–45 years**, male > female.
    - Contrast with primary GBM, where median age ≈ 65 years.
- **Survival**
    - **IDH-mutant** patients often live **~5–20 years**, compared with ≈ 15 months median OS for IDH–wild-type GBM.
    - Slight survival advantage in females vs males has been observed.

> [!note] Why this matters for us
> 
> - Young age and long natural history mean that every decision (how aggressively we resect, when we radiate, what chemo we choose) has decades-long consequences for cognition, function, and quality of life.

---

### Prognostic Factors and Impact of Surgery

- **Postoperative residual volume**
    - Residual tumor volume correlates with:
        - Overall survival (OS)
        - Risk of malignant transformation
    - This holds across **all WHO grade 2 gliomas**.
    - Data: Hervey-Jumper et al., JCO 2023.
- **Implications**
    - Maximal safe resection remains a cornerstone.
    - Techniques to enhance safe EOR:
        - Awake mapping for language and motor.
        - Intraoperative mapping/monitoring, DTI-based tractography.
        - Repeat/staged resections in selected patients.

> [!tip] Practical surgical point
> 
> - For non-eloquent or low-risk eloquent lesions, the bar for a second or "completion" resection is lower in IDH-mut LGG than in GBM, given the long time horizon and correlation between residual volume and malignant transformation.

---

### Radiation and Chemotherapy in IDH-mutant Gliomas

#### Role of Radiation

- **Timing**
    - **Upfront RT vs RT at recurrence**:
        - Does **not improve OS**.
        - Does **improve PFS**.
    - The benefit in tumor control must be balanced against late RT toxicity:
        - Neurocognitive decline
        - Radiation necrosis
        - Endocrine dysfunction (for suprasellar/parasellar/third ventricle lesions)
- Many centers reserve RT for:
    - High-risk features (age ≥ 40, large tumors, significant residual tumor, neurologic deficits), or
    - Progression on surveillance / systemic therapy.

---

#### Role of Chemotherapy (PCV, TMZ)

##### PCV Chemotherapy

- **Regimen**: Procarbazine, CCNU (lomustine), Vincristine.
- **Evidence base**
    - **EORTC and RTOG trials**
        - RT + PCV associated with **significant survival benefit** in higher-risk LGG.
        - The OS benefit becomes clearly apparent only **after ~7 years** of follow-up.
    - Clear PFS and OS improvement when added to RT in appropriate risk groups.
- **Caveats**
    - **PCV is toxic** and requires a **lengthy course**:
        - Myelosuppression, fatigue.
        - Procarbazine: MAOI-like effects (diet and drug interactions).
        - Vincristine: neuropathy.
        - CCNU: prolonged cytopenias, cumulative toxicity.

> [!warning] PCV practicality
> 
> - This is an excellent regimen **on paper**, but real-world delivery often limited by:
> 
>     - Hematologic toxicity
> 
>     - Neuropathy
> 
>     - Patient tolerance over multiple cycles
> 
> - For younger, high-risk patients who can tolerate it, the long-term OS benefit is important.

---

##### TMZ in IDH-mutant Gliomas

- **CATNON trial** (van den Bent, Lancet 2021)
    - Population: **Anaplastic astrocytoma (WHO grade 3)**, IDH status now recognized as critical in interpretation.
    - Design:
        - RT alone vs RT + _concurrent_ TMZ vs RT + _adjuvant_ TMZ vs RT + both.
    - Key finding:
        - **Adjuvant TMZ** (after RT) improves outcomes more than concurrent-only TMZ.
        - Supports the concept that prolonged adjuvant therapy matters.
- **TMZ advantages**
    - Orally administered.
    - Generally better tolerated than PCV.
    - Familiar to both patients and clinicians (from GBM practice).
- **TMZ disadvantages / concerns**
    - Long-term use associated with **hypermutation**, particularly in IDH-mut astrocytoma:
        - Can promote emergence of more aggressive, treatment-resistant clones.
    - Unclear whether TMZ is **equivalent** to PCV in IDH-mut oligodendroglioma.

---

#### PCV vs TMZ: Current Debate

- **Ongoing debate**: which is preferred for **mIDH gliomas**, especially 1p/19q-codeleted oligodendrogliomas?
- **TMZ**
    - Milder toxicity profile.
    - Easier to deliver; widely used in practice.
- **PCV**
    - **POLA network retrospective data** (Kacimi et al., JCO 2024):
        - Suggests **PCV may be superior to TMZ** in terms of survival outcomes in some IDHm cohorts (especially oligodendroglioma).
    - Historically, PCV + RT is considered the "gold standard" for high-risk, 1p/19q-codeleted oligodendroglioma.
- **CODEL study**
    - Ongoing RCT designed to **directly compare** these approaches in IDH-mut, 1p/19q-codeleted oligodendroglioma.
    - Expected to define whether TMZ-based strategies can replace RT + PCV as standard of care.

> [!note] How we frame it with patients
> 
> - PCV: "higher potential benefit, higher toxicity, longer and more cumbersome."
> 
> - TMZ: "easier, better tolerated, but may be somewhat less effective in the long run, especially for classic oligodendroglioma."
> 
> - In practice, age, performance status, comorbidities, patient preferences, and local expertise all influence the choice.

---

### Historical Treatment Algorithms

Historically, before IDH-directed therapy and modern molecular stratification, a common approach:

- **Any WHO grade 2 glioma or oligodendroglioma grade 3 with gross total resection (GTR)**
    - **Surveillance** alone.
- **Any oligodendroglioma**
    - **Chemotherapy monotherapy** (often PCV ± delayed RT).
- **Any diffuse glioma (astro or oligo)**
    - **Surgery + chemoradiation** for higher-risk features.

> [!tip] Contemporary (simplified) risk-stratified approach
> 
> - **Low-risk IDH-mut grade 2** (younger, small tumor, minimal residual, no deficits):
> 
>     - Maximal safe resection → observation or IDH inhibitor (see below), reserving RT/PCV for progression.
> 
> - **High-risk IDH-mut grade 2 or grade 3** (older age, large volume, significant residual, deficits):
> 
>     - RT + PCV (especially for 1p/19q-codeleted oligo) or RT + TMZ (especially for astrocytoma), with consideration of IDH inhibitor integration where feasible.
> 
> - **Recurrent disease**:
> 
>     - Options include re-resection, RT (if not already given), systemic therapy (PCV/TMZ), and now IDH inhibition.

---

### Complications of Treatment

- **Radiation necrosis**
    - Can mimic tumor progression radiographically.
    - Managed with steroids, bevacizumab, sometimes surgery for mass effect or diagnostic uncertainty.
- **Hemorrhage**
    - Spontaneous intratumoral or treatment-related; more relevant in highly vascular or transformed components.
- **Hypermutation**
    - Especially after prolonged TMZ exposure in IDH-mut astrocytoma.
    - Associated with:
        - Aggressive recurrence
        - Potential resistance to further alkylating therapy
- Additional longer-term risks:
    - Neurocognitive decline.
    - Endocrinopathy (if RT involves hypothalamic-pituitary axis).
    - Secondary malignancies.

> [!warning] Balancing act
> 
> - For IDH-mut LGG, the calculus is not "do we control the tumor?" but **"how do we control the tumor over decades without destroying the brain?"**
> 
> - Extent of resection, timing of RT, choice of chemotherapy, and now use of IDH inhibitors all feed into that balance.

---

### IDH-mutant Biology and Inhibition

#### IDH-mutant Pathophysiology

- **Wild-type IDH**
    - Converts isocitrate → α-ketoglutarate (α-KG).
- **Mutant IDH (IDH1/IDH2)**
    - Gain-of-function neomorphic activity:
        - α-KG is shunted to **2-hydroxyglutarate (2-HG)**, an oncometabolite.
- **Downstream effects of 2-HG**
    - DNA hypermethylation.
    - Chromatin modification.
    - Altered hypoxia response.
    - Creation of a "glioma CpG island methylator phenotype" (G-CIMP).
- This epigenetic reprogramming is central to the biology of IDH-mutant gliomas and represents a **therapeutic target**.

---

#### INDIGO Study – Vorasidenib (IDH1/2 Inhibitor)

- **Study**: INDIGO (Cloughesy et al., _Lancet Oncology_ 2025).
- **Population**
    - Newly diagnosed **IDH-mutant WHO grade 2 glioma**.
    - Patients had undergone prior **surgical resection** (often subtotal) **within 1–5 years** before enrollment.
    - Both astrocytoma and oligodendroglioma included.
- **Design**
    - Randomized, double-blind, placebo-controlled.
    - Patients received **vorasidenib** or placebo.
    - At time of **disease progression**:
        - Unblinded.
        - If on placebo → crossed over to vorasidenib.
        - If on vorasidenib → transitioned to "secondary interventions" (RT, chemo, surgery).

##### Key Outcomes

- **Primary endpoint: PFS**
    - Vorasidenib significantly **improved PFS**.
    - Hazard ratio ≈ **0.35** vs placebo.
    - Benefit was **independent of**:
        - 1p/19q status
        - Age
        - Number of surgeries
        - Extent of resection (EOR)
        - Tumor size
- **Secondary endpoints**
    - **Time to next intervention (TTNI)**
        - Substantial delay with vorasidenib; HR ≈ **0.25**.
        - In practice, this means **deferral of RT and/or alkylating chemotherapy** in many patients.
    - **Tumor burden**
        - Associated with **smaller tumor volumes** over time, suggesting direct growth impairment.
    - **Seizure control**
        - Reduced seizure frequency; rate ratio ≈ **0.36**.
        - This effect appears **oligodendroglioma-predominant**:
            - Clear seizure reduction in oligodendroglioma.
            - No obvious change in seizure frequency in astrocytoma subgroup.

> [!tip] Practical implications of vorasidenib
> 
> - For a young patient with residual IDH-mut grade 2 glioma after maximal safe resection:
> 
>     - Vorasidenib offers a way to **stabilize disease and reduce seizures** while postponing RT and PCV/TMZ.
> 
> - Does **not eliminate** the need for RT or chemo forever but can **shift them later**, into a period where the patient may already have had several productive, neurologically intact years.

---

### Practical Neurosurgical Takeaways

- **At initial presentation**
    - Aim for **maximal safe resection**, especially in IDH-mut LGG.
    - Ensure **high-quality tissue** for full molecular profiling:
        - IDH1/2
        - 1p/19q codeletion
        - ATRX, TP53
        - CDKN2A/B (for grading in astrocytoma)
    - Early involvement of neuro-oncology to discuss:
        - Observation vs early RT/PCV/TMZ.
        - Eligibility for **IDH inhibitor** therapy.
- **At recurrence/progression**
    - Consider:
        - **Re-resection** if feasible, especially for focal progression.
        - RT (if not previously given) or re-irradiation in selected cases.
        - Systemic therapy:
            - PCV vs TMZ based on subtype, prior therapy, and patient factors.
            - IDH inhibition if not already used (or clinical trial options if it has been).
    - Reassess seizure control and taper AEDs carefully where appropriate.
- **Balancing risk over decades**
    - For many of these patients, we are planning a **lifelong trajectory**, not a single episode of care.
    - The triad to continually reassess:
        
        1. **Tumor burden** and risk of malignant transformation.
        2. **Therapy-related toxicity** (RT, PCV/TMZ, targeted agents).
        3. **Functional and cognitive outcome**, including employment, driving, and family life.

> [!quote] Colleague-to-colleague
> 
> - "In IDH-mut LGG, the best operation is almost always the first one. But with vorasidenib and rational use of RT/PCV/TMZ, we now have more room to tailor the **entire disease course**—not just the next six months."

## Management of Glioblastoma (GBM)

**Speaker:** Rimas Lukas (Northwestern University)

---

> [!summary] Big picture
> 
> - GBM is an **IDH-wildtype**, highly heterogeneous, infiltrative glioma with poor prognosis.
> 
> - Standard upfront care: **maximal safe resection → RT 60 Gy + concurrent & adjuvant TMZ ± TTFields**.
> 
> - Prognosis and treatment nuances are heavily influenced by **MGMT status**, **age**, and **KPS**.
> 
> - At progression, there is **no single standard**; we're mainly choosing between surgery, re-irradiation, Bev, alkylators (e.g., CCNU), and clinical trials.

---

### 1. Imaging & Surgical Principles

#### 1.1 Imaging characteristics

- **Heterogeneous enhancement patterns**:
    - Ring-enhancing
    - Solid enhancing
    - Heterogeneous, mixed enhancing/non-enhancing
    - Non-enhancing, infiltrative components on T2/FLAIR often extend beyond contrast enhancement.

> [!tip] Surgical relevance  
> Don't forget the **non-enhancing** margin — that's a big part of what "supramaximal" means in practice.

#### 1.2 Surgery

- **Primary goals**
    - Diagnostic: confirm GBM, obtain tissue for **molecular profiling**.
    - Therapeutic: debulk to relieve mass effect, improve symptoms, and optimize RT/chemo efficacy.
- **RANO-RESECT**
    - Framework emphasizing **maximal safe resection**, often **supramaximal**:
        - Removing **all enhancing tumor** where feasible.
        - In selected non-eloquent locations, extend into the **immediately adjacent FLAIR abnormality**.
    - Extent of resection correlates with OS, but must be balanced against functional preservation.

---

### 2. Pathology & Molecular Features

#### 2.1 Classic histology

- **Pseudopalisading necrosis**
- **Microvascular proliferation**

These features underpin the diagnosis of GBM (IDH-wildtype) in the appropriate context.

#### 2.2 Core molecular profile (GBM, IDH-wildtype)

- **IDH-wildtype** (by definition for "canonical" GBM in current WHO).
- **TERT promoter mutation**
- **EGFR gene amplification** (often with EGFRvIII)
- **Copy number alterations**
    - **Chromosome 7 gain**
    - **Chromosome 10 loss**
- **Homozygous loss of chromosome 10**
    - Can imply loss of the **MGMT locus**.
    - Pathology may report this as "**MGMT unmethylated**" on a promoter methylation assay, but:
        - Functionally, **no MGMT protein** may be present.
        - These patients can still do **clinically well on TMZ** because there is effectively no MGMT to repair alkylation damage.

#### 2.3 DNA methylation–based subtypes

- Major GBM methylation classes (Heidelberg classifier style):
    - **Mesenchymal**
        - Common genetic associations: **NF1**, **RB1** alterations.
    - **RTK I**
        - Often **PDGFRA**-driven.
    - **RTK II**
        - Often **EGFR**-driven.
    - **RTK III / MYCN**
        - MYCN-amplified subset.
- **Current clinical practice**
    - Despite these subclassifications, **all GBM subtypes are currently managed similarly** in routine practice.
    - Methylation profiling is most helpful in:
        - Borderline cases (e.g., separating GBM from IDH-mut astrocytoma or other mimics).
        - Prognostication and research/clinical trial stratification.

---

### 3. Epidemiology & Risk Factors

- **Proportion of brain tumors**: ~**14%** of all brain tumors.
- **Average age at diagnosis**: ≈ **66 years**.
- **Risk factors**
    - **Increased risk**
        - Prior **ionizing cranial radiation**.
    - **Decreased risk**
        - **Allergies / atopic disease** (eczema, psoriasis, asthma) – recurrent observation in epidemiologic studies.

---

### 4. Upfront Treatment

#### 4.1 Surgery

- **Diagnostic**:
    - Tissue for histology + molecular panel (IDH, MGMT, TERT, EGFR, etc.).
- **Therapeutic**:
    - Debulk mass to:
        - Improve neurologic symptoms.
        - Reduce steroid dependence.
        - Possibly improve RT/chemo sensitivity by reducing hypoxic, necrotic compartments.

#### 4.2 Radiation therapy

- **Standard regimen**
    - **60 Gy in 30 fractions** (2 Gy/fx over 6 weeks) to **contrast-enhancing tumor + margin**, typically including FLAIR abnormality.
- **Elderly / poor KPS** (frail or KPS < 70)
    - **40 Gy in 15 fractions** (hypofractionated RT; ~3 weeks).
    - **25 Gy in 5 fractions** (ultra-short course) for very poor prognosis or palliative intent.
    - Other modified protocols exist and should be individualized.

> [!warning] KPS matters  
> Classic Stupp data: **KPS < 70%** patients derive **little or no survival benefit** from combined RT + TMZ versus RT alone. For these patients, less intensive regimens and symptom control may be more appropriate.

#### 4.3 Chemotherapy – Temozolomide (TMZ)

- **Drug properties**
    - Oral alkylating agent that **crosses the BBB**.
    - Prodrug that is spontaneously converted to **MTIC** (the active alkylating metabolite).
- **Mechanism**
    - MTIC **methylates DNA** at several sites, particularly at **O6-guanine**, leading to DNA mismatches and cell death.

##### MGMT and temozolomide response

- **MGMT (O6-methylguanine-DNA methyltransferase)**:
    - DNA repair enzyme that removes methyl groups from the **O6 position of guanine**.
    - High MGMT expression → **repair of TMZ-induced lesions** → reduces TMZ efficacy.
- **MGMT promoter methylation**
    - Silences MGMT expression → decreased repair → **better response to TMZ** and improved survival.
    - Standard-of-care prognostic and predictive marker:
        - **Methylated**: TMZ provides **clear benefit**.
        - **Unmethylated**: benefit is **less pronounced**, but not zero; many still receive TMZ, especially younger/fit patients.

---

### 5. Survival Over Time & Key Trials

#### 5.1 Era comparison

- **Pre-TMZ era (RT alone)**
- **TMZ era (Stupp protocol)**
- **TMZ + Tumor Treating Fields (TTFields) era**

#### 5.2 Stupp protocol

- **Regimen**
    - Maximal safe resection (when feasible) → RT 60 Gy with **concurrent TMZ** → **6 cycles** of adjuvant TMZ.
- **Survival impact**
    - 5-year OS:
        - **~10%** with RT + TMZ (Stupp)
        - vs **~2%** with RT alone.
- **KPS considerations**
    - Patients with **KPS < 70%** see **limited benefit** from full Stupp regimen.

#### 5.3 GEINO trial (TMZ duration)

- Question: **6 vs 12 cycles** of adjuvant TMZ.
- Result: **No meaningful difference** in outcome.
- Practice implication:
    - Most centers default to **6 cycles** of adjuvant TMZ
    - Additional cycles sometimes used in select, well-tolerated cases, but evidence is weak.

---

### 6. Tumor Treating Fields (TTFields)

- **Mechanism – multifactorial**
    - **Biophysical**
        - Electric fields exert **forces/torque** on polar molecules and mitotic structures.
        - Interfere with microtubules and mitotic spindle apparatus.
        - Possible low-level **thermal**/membrane effects.
    - **Biochemical / cellular**
        - Modulate **immune responses**.
        - Affect organelle function and cellular signaling.
        - Disrupt intracellular ionic and molecular environment.
- **Clinical data**
    - **Stupp et al., JAMA 2017 (EF-14 trial)**:
        - Newly diagnosed GBM, post-RT:
            - Adjuvant TMZ **± TTFields**.
        - **OS benefit ~5 months**:
            - Median OS up to **~20.9 months** in TTFields + TMZ arm.
    - Benefit is **strongly adherence-dependent**:
        - Patients wearing the device **>18 h/day** derive the most benefit.

> [!info] Practical point  
> TTFields are best offered to **motivated, cognitively intact patients** with good support who can tolerate continuous device wear. The regimen is burdensome but can meaningfully extend survival.

---

### 7. Management of Progressive / Recurrent GBM

> [!summary] No universal standard  
> At recurrence, consider: **re-resection**, **re-irradiation**, systemic options (Bev, CCNU, other alkylators), **clinical trials**, and best supportive care.

#### 7.1 General options (beyond what's listed in the talk)

- **Re-resection**
    - For surgically accessible, symptomatic, or diagnostically uncertain lesions (e.g., RN vs tumor).
- **Re-irradiation**
    - SRS or hypofractionated RT for small-volume recurrences outside critical high-dose brain regions.
- **Systemic therapy**
    - Bevacizumab, nitrosoureas (CCNU/PCNU), TMZ rechallenge in selected cases.
    - Clinical trials (immunotherapy, targeted agents, vaccines, oncolytic viruses).
- **Supportive care**
    - Dexamethasone optimization, seizure management, rehab, palliative care.

---

#### 7.2 Bevacizumab

- **Mechanism**
    - Anti-VEGF monoclonal antibody → reduces vascular permeability and edema.
- **Phase III trials**
    - **RTOG**, **AVAGlio**, **EORTC**:
        - All **negative for OS improvement** in newly diagnosed GBM when Bev added up front.
- **Current role**
    - Primarily used for **symptomatic cerebral edema** at recurrence:
        - Reduces steroid requirement.
        - Can improve QoL and neurologic function.
    - Also used for symptomatic **radiation necrosis** in selected cases.

---

#### 7.3 CCNU (lomustine)

- **Class**
    - Alkylating agent; **nitrosourea**.
- **Mechanism of action**
    - DNA and RNA **alkylation**.
    - **Cross-linking** and **protein carbamylation** → mimics senescence and impairs tumor cell replication.
- **Clinical trials**
    - **STEERING**, **REGAL**, **RELOB**, **REGOMA**, among others:
        - Often used as control arm or backbone in recurrent GBM trials.
- **Efficacy**
    - **Response rate ~10%**.
    - Modest OS benefit; hence, best used either:
        - As part of a clinical trial, or
        - In patients previously treated with TMZ who still have reasonable performance status.
- **When to consider**
    - Recurrent GBM after standard RT/TMZ.
    - Especially where other options (trials, re-irradiation, resection) are limited.

---

> [!todo] For local protocol notes
> 
> - Embed center-specific:
> 
>     - Criteria for offering **TTFields**.
> 
>     - Age/KPS cutoffs for **hypofractionated RT** vs full Stupp.
> 
>     - Preferred **re-resection vs Bev vs CCNU** decision tree at first recurrence.

## Management of Primary CNS Lymphoma (PCNSL)

**Speaker:** Karan Dixit

> [!summary] Big picture
> 
> - PCNSL is an aggressive, **chemoand radiosensitive** large B-cell lymphoma confined to the CNS and other immune-privileged sites.
> 
> - Early recognition and biopsy _without prior steroids_ is critical.
> 
> - High-dose methotrexate (HD-MTX)–based chemoimmunotherapy is the cornerstone of curative-intent treatment.
> 
> - Consolidation (HDC-ASCT or RT/chemo) and, increasingly, maintenance strategies are key to prolonging remission.
> 
> - A substantial fraction of patients relapse; trial enrollment and targeted agents (BTKi, IMiDs, etc.) are increasingly important.

---

### Definition & Epidemiology

- **Uncommon variant** of aggressive extranodal large B-cell lymphoma.
- Accounts for **~2% of CNS tumors**.
- Considered a **primary large B-cell lymphoma of immune-privileged sites**, typically:
    - Brain
    - Eyes (vitreoretinal)
    - CSF/leptomeninges
- By definition:
    - Confined to CNS (and sometimes eyes) **without prior or concurrent systemic lymphoma** at diagnosis.

> [!note] Systemic workup remains essential  
> Even though PCNSL is "primary," you must still exclude systemic disease with appropriate imaging and staging before labeling it as such.

---

### Clinical Presentation

#### CNS Presentation

- Typically **subacute onset** (days–weeks).
- **Focal neurologic deficits** (≈ 50–70%)
    - Hemiparesis, aphasia, visual field deficits, ataxia, etc.
- **Cognitive/behavioral changes** (> 50%)
    - Personality change, apathy, confusion, memory loss.
- **Elevated intracranial pressure** (≈ 30%)
    - Headache, nausea/vomiting, papilledema.
- **Seizures** are **uncommon** (~10%), less frequent than in gliomas.

#### Systemic / Constitutional Symptoms

- B symptoms are **rare**:
    - Fevers
    - Night sweats
    - Unintentional weight loss

#### Ocular Involvement

- Occurs in **15–20%** of patients.
- Symptoms:
    - Blurred vision
    - Floaters
    - Photophobia
- **Action:**
    - Prompt **ophthalmology consult** for dilated funduscopic exam and possible intravitreal sampling.

#### Leptomeningeal / Cranial Nerve / Spinal Involvement

- Concomitant **leptomeningeal disease (LMD)** at presentation: ~15%.
- Isolated cranial nerve, spinal cord, or cauda equina involvement at initial presentation is **rare**, but possible.

> [!tip] Neurosurgical angle
> 
> - Think PCNSL in subacute deep periventricular lesions with homogenous enhancement, edema out of proportion to mass effect, and minimal necrosis—especially without seizures and in the right age/immunologic context.

---

### Imaging Features

> [!info] Early recognition is key  
> Imaging patterns often strongly suggest PCNSL and should prompt urgent workup and biopsy _before_ steroids are given.

#### General Characteristics

- **Irregular boundaries**, but often sharply demarcated from surrounding brain on post-contrast imaging.
- **Multifocality** is common.
- Strong predilection for **deep brain** and **periventricular** regions (~60%):
    - Thalamus
    - Basal ganglia
    - Corpus callosum
    - Periventricular white matter
- **Hemorrhage, calcification, and necrosis** are **uncommon**, especially in untreated immunocompetent patients.

#### CT

- Lesions are typically:
    - **Isoto hyperdense** relative to brain.
    - Contrast-enhancing.
- Hyperdensity reflects **high tumor cellularity**.

#### MRI

##### Immunocompetent Patients

- **Enhancement**
    - Typically **homogeneous, solid enhancement**.
- **Diffusion**
    - **Hyperintense on DWI**.
    - **Hypointense on ADC**.
    - Reflects **hypercellularity** (restricted diffusion).

##### Immunocompromised Patients

- May show more **atypical, "necrotic-appearing" lesions**.
- **Enhancement**
    - Often **peripheral/ring enhancement**.
- **Diffusion**
    - Still typically **hyperintense on DWI** and **hypointense on ADC** in viable tumor components.

> [!warning] Radiographic pitfall
> 
> - Ring-enhancing lesions in immunocompromised patients raise a broad differential: toxoplasmosis, abscess, PCNSL, metastasis.
> 
> - Diffusion characteristics and thallium PET (if available) may help, but tissue diagnosis is often still required.

---

### Diagnostic Workup

#### Steroids – Handle with Care

> [!danger] Avoid corticosteroids pre-biopsy if at all possible
> 
> - Corticosteroids are **lymphotoxic** and can:
> 
>     - Dramatically shrink lesions.
> 
>     - Disrupt cellular morphology.
> 
>     - Render biopsy **non-diagnostic**.
> 
> - For edema/ICP, prioritize:
> 
>     - Osmotic therapy (hypertonic saline, mannitol).
> 
>     - CSF diversion if needed (EVD) over immediate steroids.

#### Brain MRI

- MRI brain with and without gadolinium.
- Evaluate for:
    - Number and distribution of lesions.
    - Periventricular/deep involvement.
    - Leptomeningeal or ependymal enhancement.

#### CSF Studies

- Lumbar puncture **if safe** (no mass effect/herniation risk).
- Send CSF for:
    - Routine studies (cell count, protein, glucose).
    - **Cytology.**
    - **Flow cytometry** (B-cell clonality).
    - **Molecular biomarkers**:
        - MYD88 mutation
        - IL-10 levels
        - IgG analysis
- Important caveat:
    - Only about **7%** of patients have **positive CSF cytology** sufficient to obviate the need for brain biopsy.
    - **Do not wait** for a negative CSF result before arranging biopsy.

#### Additional Systemic & Site-specific Evaluation

- **Testicular ultrasound**
    - Particularly in **males > 60 years**, given proclivity for testicular involvement as another immune-privileged site.
- **Ophthalmologic evaluation**
    - For all patients with visual symptoms or if ocular involvement is suspected.

---

### Staging

- Goal: Exclude **systemic lymphoma** and define full extent of disease.
- **Spine MRI**
    - Indicated if:
        - Focal spinal or radicular symptoms, or
        - Positive CSF suggesting LMD.
- **Ophthalmologic evaluation**
    - Slit-lamp exam and possible vitreous sampling.
- **Systemic staging**
    - Preferred: **Whole-body PET-CT**.
    - If PET-CT not available:
        - **Testicular ultrasound** in men > 60.
        - **Bone marrow biopsy** if there are any unexplained cytopenias or suspicion for systemic involvement.

---

### Sentinel Inflammatory Lesions

- Sometimes, a first biopsy yields only **inflammatory/inconclusive pathology** despite imaging highly suggestive of PCNSL.
- These can be considered **"sentinel inflammatory lesions."**
- **Action:**
    - Maintain high index of suspicion.
    - Continue close follow-up with **serial MRI**.
    - Consider **repeat biopsy** if lesions evolve.

> [!note] Neurosurgical pearl
> 
> - When pathology is "nonspecific inflammation" in a deep, enhancing, hypercellular periventricular lesion in the right clinical context, do not dismiss it—this may be pre-diagnostic PCNSL.

---

### Pathology

- Most cases are **diffuse large B-cell lymphoma (DLBCL)**.
- Often of **non–germinal center / activated B-cell subtype**, though germinal center subtype can occur.
- Malignant cells express:
    - **Pan B-cell markers** (CD19, CD20, CD79a).
    - Variable expression of BCL6, MUM1, etc.
- High proliferation index (Ki-67 often > 80%).

---

### Prognosis

- Prognostic scoring systems (older but still used):
    - **IELSG** (International Extranodal Lymphoma Study Group)
        - Includes:
            - Age
            - KPS
            - Tumor location
            - CSF protein
            - LDH (in original model)
    - **MSKCC** score
        - Based primarily on:
            - Age
            - KPS
- General themes:
    - Younger age and good performance status = better prognosis.
    - Deep/brainstem involvement, elevated CSF protein, and poor KPS = worse prognosis.

---

### Treatment – Curative Intent

> [!summary] Core regimen concept
> 
> - Curative treatment of PCNSL is built around **high-dose methotrexate (HD-MTX)**–based chemotherapies, usually combined with **rituximab** and often other agents, followed by **consolidation** and sometimes **maintenance**.

#### Induction Therapy

**Cornerstone: High-dose methotrexate (HD-MTX)**

- HD-MTX–based regimens typically include:
    - **Alkylators:**
        - Procarbazine
        - Temozolomide
        - Thiotepa
    - **Rituximab**
    - **± Cytarabine**
    - **± Vincristine**

**Common MTX-based regimens**  
(All utilize **methotrexate + rituximab** plus additional agents.)

- **MT-R**
    - Methotrexate
    - Temozolomide (TMZ)
    - Rituximab
- **R-MVP**
    - Rituximab
    - Methotrexate
    - Procarbazine
    - Vincristine
- **MATRix**
    - Methotrexate
    - Cytarabine
    - Thiotepa
    - Rituximab

> [!warning] Logistics of HD-MTX
> 
> - Requires inpatient admission, aggressive hydration, urine alkalinization, and leucovorin rescue.
> 
> - Neurosurgeons should be aware of timing relative to any surgical interventions (biopsies, shunts).

---

#### Patients Unfit for Intensive Chemotherapy

Approximately **15%** of PCNSL patients are not candidates for full-dose multiagent chemotherapy (age, comorbidities, frailty).

**Options:**

- **Whole-brain radiation therapy (WBRT)**
    - Can achieve good short-term responses.
    - Long-term neurocognitive toxicity is a major concern, especially in older patients.
- **Less-intensive oral agents**
    - Temozolomide (TMZ)
    - BTK inhibitors (e.g., ibrutinib; others in trials)
    - IMiDs (e.g., lenalidomide, pomalidomide)
    - Rituximab (IV or intrathecal/intraventricular in selected cases)
- **Supportive care**
    - Symptom management, steroids (when biopsy completed), seizure control, ICP management, rehab.

---

#### Post-induction Therapy: Consolidation

Aim: deepen response and prolong remission.

**Options:**

- **High-dose chemotherapy with autologous stem cell transplant (HDC-ASCT)**
    - Often **thiotepa-based** regimens.
    - Increasingly favored in fit patients, given:
        - Good disease control.
        - Potentially less neurocognitive toxicity than WBRT.
- **Non-myeloablative chemotherapy**
    - For those not candidates for HDC-ASCT.
    - May use agents like cytarabine, thiotepa, or others in lower-intensity combinations.
- **Dose-reduced WBRT**
    - Lower-dose WBRT as consolidation.
    - Attempts to balance disease control with reduced late toxicity.

---

#### Post-induction Therapy: Maintenance

Goal: delay relapse and stabilize disease long-term.

Possible maintenance strategies include:

- **Temozolomide**
    - e.g., for **12–24 months**.
- **Methotrexate**
    - Intermittent HD-MTX for **up to 12 months** in some protocols.
- **Lenalidomide**
    - Continued **until progression**, often well tolerated in lower doses.
- **BTK inhibition**
    - BTK inhibitors continued **until progression**.
- **Rituximab**
    - e.g., every 2–3 months for up to **24 months**.

> [!note] Evidence evolving
> 
> - Maintenance strategies are heterogeneous and evidence is still emerging; approaches vary by center and trial availability.

---

### Refractory or Relapsed Disease

- **Refractory disease**
    - **15–25%** do **not** respond to induction therapy.
- **Relapsed disease**
    - **25–50%** relapse within **2 years** of induction.
- **Early vs delayed relapse**
    - Early relapse tends to portend a more aggressive clinical course.
    - Late relapse may remain responsive to rechallenge with MTX-based regimens.

#### Management Strategies

- **Clinical trials** (strongly encouraged).
- **HD-MTX rechallenge**
    - Particularly in late relapses and in patients who previously responded well.
- **Change of systemic agents**
    - Switch alkylators or combinations.
- **Molecularly targeted treatments**
    - BTK inhibitors (e.g., ibrutinib and newer agents).
    - IMiDs (lenalidomide, pomalidomide).
- **Immunotherapy**
    - Checkpoint inhibitors in selected settings or trials.
- **WBRT**
    - Often utilized in relapsed/refractory cases, particularly when prior RT has not been given.
    - Must balance potential benefit with neurotoxicity, especially in older adults.

---

### Neurosurgical Considerations

> [!tip] Biopsy strategy
> 
> - **Aim for stereotactic biopsy**, not debulking:
> 
>     - PCNSL is highly chemoand radiosensitive.
> 
>     - Debulking rarely adds benefit and increases morbidity.
> 
> - Choose a target that:
> 
>     - Is safely accessible.
> 
>     - Represents **solid enhancing tumor** (avoiding necrotic/hemorrhagic areas).

Additional considerations:

- Avoid pre-biopsy steroids when possible.
- Consider ICP management: EVD, osmotic therapy, careful monitoring.
- After diagnosis, early coordination with neuro-oncology/hematology to:
    - Time HD-MTX and consolidation.
    - Plan for any needed CSF diversion or Ommaya placement (e.g., for IT therapy).
- Be aware of **concomitant ocular disease**:
    - May need local ocular RT or intravitreal MTX/rituximab in addition to CNS-directed therapy.

---

---

## Pediatric neuro-oncology

source: "Sonia Partap (Stanford) – Pediatric Neuro-oncology"  
topic: Pediatric brain tumors

- Brain tumors are the **most common cancer in childhood**
    - ≈ **25% of childhood cancers**
- **Most common cause of childhood cancer–related death** in the USA
- **Sex:** boys > girls

> [!summary] Scope of this note  
> Cleaned and structured recap of key pediatric brain tumors:
> 
> - Low-grade glioma: **pilocytic astrocytoma**
> 
> - **Diffuse intrinsic pontine glioma (DIPG / diffuse midline glioma)**
> 
> - **Ependymoma**
> 
> - **Intracranial germ cell tumors**
> 
> - **Medulloblastoma & other embryonal tumors**  
> With added molecular/management pearls where helpful.

---

### Glial vs non-glial tumors

- **Glial:** pilocytic astrocytoma, diffuse gliomas, ependymoma, etc.
- **Non-glial:** germ cell tumors, medulloblastoma & embryonal tumors, ATRT, pineoblastoma, etc.

---

### Pilocytic astrocytoma (PA) – pediatric low-grade glioma (LGG)

#### Epidemiology & general

- ~**15% of childhood brain tumors**
- **WHO grade I**, well-differentiated
- Majority (**~80%**) are **cystic with a mural nodule**
- **NF1 predisposition** (classically optic pathway & hypothalamic gliomas)
- Often a **chronic disease** rather than "cured" malignancy:
    - 5-year OS ≈ **97%**
    - 20-year OS ≈ **87%**
- Boys slightly > girls (consistent with general pediatric CNS tumor trends)

#### Pathology

- **Cystic lesion with enhancing mural nodule**
- Histology:
    - **Biphasic pattern** (compact and microcystic areas)
    - **Piloid (hair-like) processes**
    - **Eosinophilic granular bodies**
    - **Rosenthal fibers**

#### Management

- **First-line**: **maximal safe surgical resection**
    - Often **surgically curable**
    - Extent of resection strongly prognostic
- If **non-resectable / progressive / recurrent**:
    - **Chemotherapy**
        - Carboplatin + vincristine
        - Vinblastine monotherapy in some protocols
    - **Clinical trials**
    - **Molecularly targeted therapy** (see below)
    - **Radiation** – generally delayed in young children when possible

> [!tip] Practice pattern  
> In younger children and midline/optic pathway tumors, **chemo or targeted therapy** is often preferred up front over XRT to delay radiation-associated neurocognitive and endocrine toxicity.

#### Molecular profile & targeted therapy

> [!info] BRAF/MAPK pathway – key LGG driver  
> BRAF alterations are common in pediatric LGG and determine **choice of inhibitor**.

- **BRAF alterations**
    - **BRAF fusion** (e.g., KIAA1549–BRAF)
        - Prognostically favorable compared to BRAF V600E
        - **Therapy**: **MEK inhibition** (e.g., **selumetinib**)
        - Avoid **first-generation BRAF inhibitors alone** → paradoxical MAPK activation and tumor growth
        - **COG ACNS 1833** – ongoing trial of selumetinib in non-BRAF V600E LGG (e.g. BRAF fusions)
        - Fangusaro et al., _Lancet Oncol_ 2019 – key reference for MEK inhibition in pediatric LGG
    - **BRAF V600E mutation**
        - Generally **worse prognosis** than BRAF fusion
        - **Therapy**:
            - **BRAF inhibitor** (e.g., **dabrafenib**) + **MEK inhibitor** (e.g., **trametinib**)
            - **Tovorafenib** (pan-RAF inhibitor)
                - ~50% response rate in relapsed pediatric LGG (FIREFLY-2)
                - Particularly relevant in relapsed/refractory setting
- **Other targetable alterations**
    - **IDH mutations (~16%)** in some pediatric LGG
        - Emerging agents: **ivosidenib**, **vorasidenib**
    - **NTRK fusions**
        - **Larotrectinib** as targeted therapy

#### Targeted therapy toxicity

> [!warning] Toxicities to watch

- **MAPK/BRAF pathway inhibitors (BRAF ± MEK)**
    - Cutaneous toxicity (rash, photosensitivity, hyperkeratosis)
    - **Retinal detachment / serous retinopathy**
    - **Cardiac toxicity** (↓ LVEF, QT issues) → baseline and serial ECHO/ECG
- **Tovorafenib**
    - **Growth retardation** (monitor height/weight curves)
    - Risk of **intratumoral hemorrhage**

---

### Diffuse intrinsic pontine glioma (DIPG)

_(now classified under diffuse midline glioma, H3 K27-altered)_

#### Clinical & imaging

- **Location:** intrinsic expansion of the **pons**
- **MRI**
    - Diffuse **pontine expansion**
    - Typically **T2 hyperintense**, infiltrative
    - Often **minimal or no contrast enhancement**
- **Presentation**
    - **CN VI palsy** (abducens)
    - **Ataxia**
    - **Long-tract signs** (UMN): hyperreflexia, hypertonia
- **Prognosis**
    - **Very poor**, median survival ≈ **11 months**

#### Molecular

- Strongly associated with **H3 K27M mutation**  
    (now: "**H3 K27-altered diffuse midline glioma**" in WHO 2021)

#### Treatment

- **Standard**
    - **Focal radiation** ~ **54 Gy** to pontine lesion
- **No role for resection** (infiltrative brainstem tumor)
- **Clinical trials essential**
    - Investigational agents; access varies by center
- **ONC201 (dordaviprone)**
    - Small molecule **dopamine receptor D2 antagonist** / DRD2 modulator
    - Being evaluated in diffuse midline glioma including H3 K27M mutants

> [!failure] Reality check  
> No systemic regimen has clearly changed survival yet. Role of neurosurgeon is:
> 
> - **Biopsy** (for molecular diagnosis, when feasible/indicated)
> 
> - **CSF diversion** if hydrocephalus
> 
> - **Multidisciplinary trial referral** early.

---

### Ependymoma

#### Epidemiology & location

- ~**5% of childhood brain tumors**
- Classically **posterior fossa / 4th ventricle tumors**
- Also seen in **supratentorial** and **spinal** compartments
- More common in **NF2** patients (especially spinal ependymomas)

#### Pathology & WHO grades

- **Characteristic histology:** **perivascular pseudorosettes**
- **WHO grades I–III**
    - **Brain**
        - Subependymoma (grade I)
        - Classic ependymoma (grade II)
        - Anaplastic ependymoma (grade III)
        - Supratentorial vs infratentorial (posterior fossa)
    - **Spinal cord**
        - **Myxopapillary ependymoma** (traditionally grade I; now grade II in WHO 2021 but clinically still "indolent")

> [!info] Modern nuance (helpful in tumor board)  
> Posterior fossa ependymomas are now divided into **PF-A** (younger, worse prognosis) and **PF-B** (older children/adults, better prognosis). Molecular classification increasingly guides risk and trial eligibility.

#### Management

1. **Staging**
    
    - **MRI brain and entire spine** ± CSF cytology (post-op when safe)
        
2. **Surgery**
    
    - **Maximal safe resection** is the key prognostic factor
    - **Extent of resection (EOR)** strongly correlates with PFS/OS
        
3. **Radiation**
    
    - **Conformal radiation** to the **tumor bed** with margin
    - CSI reserved for metastatic disease, not standard for localized ependymoma
        
4. **Chemotherapy**
    
    - Limited role; sometimes considered in infants to delay radiation or in recurrent disease

> [!summary] Surgical priority  
> For posterior fossa ependymoma, neurosurgeon's central job is **complete microsurgical resection** while preserving brainstem and lower cranial nerve function. EOR is prognostic.

---

### Intracranial germ cell tumors (GCT)

#### Epidemiology & risk factors

- **3–5%** of childhood brain tumors
- **Peak age**: **10–14 years**
- Increased incidence in **Klinefelter syndrome**
- **Sex & location**
    - **Females:** ~75% **suprasellar**
    - **Males:** ~70% **pineal region**

#### Diagnostic workup

- **MRI brain & entire spine**
- **Serum and CSF tumor markers**
    - **AFP**
    - **β-hCG**
- **Biopsy** if:
    - Markers non-diagnostic, or
    - Concern for mixed / non-germinomatous GCT where histology drives therapy

> [!warning] Marker pitfall  
> Markers must be interpreted carefully:
> 
> - **Markedly ↑AFP** → nongerminomatous elements (e.g., yolk sac)
> 
> - **Markedly ↑β-hCG** → choriocarcinoma components  
> These change prognosis and treatment intensity.

#### Types & treatment

##### Germinoma

- **Highly chemoand radiosensitive**
- Typical regimen:
    - **Chemotherapy**: carboplatin + etoposide (± others depending on protocol)
    - **Radiation**: involved-field or whole ventricular ± spinal/CSI depending on staging
- **Prognosis**
    - **5-year OS ~90%**

##### Non-germinomatous GCT (NGGCT)

- More **aggressive**, higher relapse risk
- **Chemotherapy**
    - Carboplatin / etoposide / ifosfamide–based multi-agent regimens
- **Radiation**
    - Typically **craniospinal irradiation (CSI)** with boost to primary + metastatic sites
- Additional details: risk-adapted protocols, often in cooperative group trials
- **Ongoing trials**
    - Risk-adapted reduction of field/dose in germinoma
    - Intensified regimens + CSI tailoring for NGGCT

---

### Medulloblastoma & embryonal tumors

#### Medulloblastoma – core facts

- **Pathology**
    - **Homer Wright rosettes** (neuroblastic rosettes without true lumen)
- Represents **40–50% of cerebellar tumors** in children
- Age: majority **3–9 years**
- **Sex:** male > female
- Can be associated with **germline syndromes**

#### Embryonal tumor family (old "PNET" group)

- **Medulloblastoma**
- **Embryonal tumor NOS**
- **Pineoblastoma**
- **ATRT** (atypical teratoid/rhabdoid tumor)
- **ETMR** (embryonal tumor with multilayered rosettes)

> [!info] Molecular medulloblastoma groups (high-yield board concept)
> 
> - **WNT** – best prognosis
> 
> - **SHH** – intermediate (varies with TP53 status, age)
> 
> - **Group 3** – **tends to metastasize; worst prognosis**, often MYC amplified
> 
> - **Group 4** – intermediate, common in older children

#### Chang M-staging (post-resection)

> [!summary] Chang M-staging – CSF/leptomeningeal disease

- **M0** – no evidence of subarachnoid or hematogenous metastasis
- **M1** – tumor cells present in **CSF**
- **M2** – **intracranial** tumor beyond primary site (e.g., cerebellar seeding, supratentorial nodules)
- **M3** – **spinal subarachnoid** nodular seeding
- **M4** – **extraneural metastasis** (e.g., bone, bone marrow)

#### Risk stratification

> [!info] Classic "average vs high risk" medulloblastoma

- **Average-risk**
    - Age ≥ **3 years**
    - **M0**
    - **Residual tumor <1.5 cm²** on early post-op imaging
    - No large cell/anaplastic histology
- **High-risk**
    - **M1–M4 disease**, **or**
    - **Residual ≥1.5 cm²**, **or**
    - Large cell/anaplastic histology, certain molecular subgroups (e.g., Group 3 with MYC amplification)

#### Treatment

1. **Surgery**
    
    - **Maximal safe resection**
    - Avoid excessive vermian/superior cerebellar peduncle injury → risk of **posterior fossa syndrome**
        
2. **Radiation**
    
    - **Craniospinal irradiation (CSI)** + **posterior fossa or tumor bed boost**
    - Dose and fields depend on **risk group and age**
        
3. **Chemotherapy**
    
    - Standard backbone: **cyclophosphamide, cisplatin, vincristine** ± others
    - Used in both averageand high-risk, with regimens tailored by risk group and trials

#### Germline predisposition

- Germline mutations reported in:
    - **ELP1, SUFU, CHEK2, BRIP1, APC, BRCA1, EGFR** and others
- **Implications**
    - May influence:
        - **Surveillance** strategies
        - **Family counseling**
        - Choice/intensity of radiation and systemic therapy

> [!warning] Genetics & counseling
> 
> - Consider **genetic counseling** for:
> 
>     - Very young patients
> 
>     - Strong family history / multiple primary tumors
> 
>     - Syndromic features
> 
> - Syndromes include **Gorlin (PTCH1)**, **APC-associated polyposis**, **Li–Fraumeni**, etc.

---

### Practical neurosurgical takeaways

> [!summary] At the console / in tumor board

- **Pilocytic astrocytoma**
    - Aim for **GTR** when safe; think **molecular targeted therapy** (BRAF/MEK, NTRK, IDH) for unresectable or recurrent.
    - Avoid BRAF inhibitors alone in **BRAF fusion** disease.
- **DIPG / DMG**
    - **Biopsy** increasingly important for molecular trials; **resection not indicated**.
    - Early **RT** and **trial referral** are key.
- **Ependymoma**
    - **EOR drives prognosis** → meticulous microsurgery.
    - Adjuvant XRT to **tumor bed**, not whole neuraxis unless metastatic.
- **Germ cell tumors**
    - **Never skip markers (serum + CSF)** before/at biopsy.
    - Germinoma: curable with combined **chemo + XRT**; NGGCT needs more **intensive chemo + CSI**.
- **Medulloblastoma**
    - Obtain **post-op MRI** within 24–72 h for exact residual size and M-staging.
    - Always discuss **risk group** (clinical, histologic, molecular) with oncology when shaping RT and chemo.

---

## Rare CNS Tumors – Molecularly Targeted Management

---

> [!summary] Core questions before you dive in
> 
> 1. **How will this tumor affect the patient's life and health expectancy?**
> 
>     - Natural history, growth rate, location, surgical morbidity, endocrine implications, etc.
> 
> 2. **Is this tumor likely to harbor a _targetable_ alteration?**
> 
>     - If yes, can we realistically access/sequence it and deliver the corresponding therapy safely and in a timely fashion?

Many rare CNS tumors are **oncogene-driven** and may respond dramatically to targeted therapy, sometimes allowing **surgery/RT de-escalation**. Resistance, however, is common and usually inevitable.

---

### 1. Molecular Targeting Framework

#### 1.1 Oncogenic signaling cascades of interest

- **FGFR**
- **TRK (NTRK1/2/3)**
- **BRAF / MAPK pathway**

> [!info] General principle  
> When faced with a rare CNS tumor, especially in younger patients:
> 
> - Ask: "Is this tumor in a family that often harbors **BRAF, FGFR, or NTRK fusions/mutations**?"
> 
> - If yes, consider **early comprehensive molecular profiling**.

#### 1.2 Types of alterations & how we find them

- **SNVs / point mutations**
    - Detection modalities:
        - **NGS panels** (DNA-based)
        - **IHC** (e.g., BRAF V600E)
        - Sanger sequencing (often confirmatory)
        - RNA sequencing
        - Circulating tumor DNA (ctDNA) – still emerging for CNS.
- **Gene rearrangements / fusions**
    - Detection modalities:
        - **FISH**
        - **RNA-seq** (excellent for fusion detection)
        - DNA-based probes / targeted DNA NGS panels

---

### 2. BRAF Mutations in Rare CNS Tumors

#### 2.1 General points

- **BRAF alterations are common** in certain rare CNS tumors:
    - > **50%** in some entities.
    - Vast majority of **pediatric LGG** harbor **BRAF pathway alterations** (fusions or V600E mutations).
- They often identify tumors as **MAPK-driven** and **potentially targetable**.

---

### 3. Circumscribed Astrocytic Tumors

#### 3.1 Pilocytic Astrocytoma (PA)

- **WHO Grade:** 1
- **Epidemiology**
    - Most common glioma in children.
    - ~25% occur in adults (often with somewhat different biology/behavior).
- **Molecular**
    - Frequently **BRAF pathway–altered** (e.g., KIAA1549–BRAF fusion; V600E less common but present).
- **Treatment**
    - **Surgery**:
        - First-line; often curative when gross total resection is feasible, especially in cerebellar lesions.
    - **BRAF-targeted therapy** (e.g., **dabrafenib + trametinib**)
        - Consider in:
            - Unresectable or recurrent disease.
            - Tumors in high-morbidity locations (e.g., optic pathway/hypothalamus).
    - **Radiation**
        - Reserved for:
            - Recurrent / progressive disease not amenable to surgery or targeted therapy.
            - High-risk situations where local control is critical and targeted options are limited.
        - Important to weigh against long-term neurocognitive/endocrine toxicity in children.

---

#### 3.2 Pleomorphic Xanthoastrocytoma (PXA)

- **WHO Grade:** 2–3 (anaplastic PXA = grade 3)
- **Characteristics**
    - **Circumscribed astrocytic glioma** with pleomorphic cells and xanthomatous change.
    - Often **heterogeneous enhancement** on MRI; can be superficially located (temporal lobe classic).
- **Presentation**
    - Frequently presents with **seizures**.
    - Occurs mostly in **young adults (age 20–40)**.
    - CSF spread can occur, especially with anaplastic variants ("frequent CSF spillage/spread").
- **Treatment**
    - **Surgery**
        - Aim for **gross total resection**; often highly beneficial for seizure control.
    - **Radiation therapy**
        - Consider for:
            - Incompletely resected tumors.
            - Anaplastic (grade 3) disease.
            - Recurrent disease.
    - **Systemic therapy**
        - No firmly established systemic standard.
        - Some patients respond to **alkylating agents** (e.g., TMZ, nitrosoureas).
    - **BRAF-targeted therapy**
        - For **BRAF V600E–mutated PXA**, BRAF ± MEK inhibition can produce meaningful responses, especially in recurrent or unresectable disease.

---

### 4. Glial and Glioneuronal Tumors

#### 4.1 Ganglioglioma

- **WHO Grade:** Usually grade 1.
- **Characteristics**
    - Mixed **glial and glioneuronal** neoplasm.
    - Often temporal lobe lesions associated with chronic epilepsy.
- **Presentation**
    - **Seizures** are the dominant clinical feature.
    - Sometimes found incidentally in **temporal lobectomy specimens** for medically refractory epilepsy.
    - Average age ≈ **20 years**.
- **Molecular**
    - Up to **~60%** harbor **BRAF V600E** mutation.
- **Treatment**
    - **Surgery**
        - Goal: **gross total resection**, often curative and may completely resolve seizures.
    - **Observation**
        - Reasonable after GTR in a stable, asymptomatic patient.
    - **Recurrent disease**
        - Consider **BRAF-targeted therapy** in BRAF V600E–positive cases (dabrafenib ± trametinib, etc.) to avoid or delay RT, especially in younger patients.

---

### 5. BRAF-Targeted Therapies – Mechanisms & Toxicity

#### 5.1 Mechanistic classes

- **Class 1 BRAF inhibitors – monomeric, RAS-independent**
    - Examples: **dabrafenib**, **encorafenib**, **vemurafenib** (user text: "cemurafenib" → vemurafenib).
    - Act on **mutant BRAF (e.g., V600E)**; **do not inhibit wild-type BRAF** effectively.
    - On wild-type background, may lead to **paradoxical MAPK activation**:
        - Associated with **loss of negative feedback** and secondary malignancies (e.g., cutaneous SCC).
    - To mitigate toxicity and resistance:
        - Combined with **MEK inhibitors**:
            - **Trametinib**, **binimetinib**, **cobimetinib**.
- **Class 2 BRAF alterations – dimer-dependent, RAS-independent**
    - More complex signaling; often **BRAF fusions or non-V600 mutations**.
    - **Tovorafenib**
        - Designed as a **BRAF dimer disruptor**.
        - Can be combined with **MEK inhibitors** (trametinib, selumetinib) in trials.

#### 5.2 Clinical efficacy (summary from talk)

- **Adult BRAF V600E gliomas**
    - Targeted therapy is **effective**, with responses often seen in both lowand high-grade contexts.
- **Pediatric LGG**
    - **Tovorafenib** has shown activity as a **BRAF dimer disruptor**, particularly in BRAF-driven **low-grade gliomas**.

#### 5.3 Toxicities of BRAF/MEK–based regimens

- **Frequency**
    - **~90%** experience side effects.
    - **~50%** have **grade 3 or higher** toxicities.
    - **~5%** need to discontinue therapy entirely.
- **Common adverse reactions**
    - **Skin**: maculopapular rash, photosensitivity, **squamous cell carcinoma** (esp. with BRAF inhibitors alone).
    - **Systemic**: pyrexia, fatigue, anemia.
    - **Ocular**: retinopathy, visual disturbances.
    - **Cardiac**: decreased ejection fraction (especially MEK inhibitors).
    - **Hepatic**: AST/ALT elevation.
- **Monitoring**
    - Baseline and periodic **dermatologic, cardiac (EF), and ophthalmologic** evaluations.
    - Regular labs: **CBC, CMP**, liver enzymes.

> [!warning] Neurosurgical angle  
> When planning surgery in patients on BRAF/MEK therapy, coordinate closely with oncology regarding **drug holds** to reduce wound-healing complications and cardiotoxicity-related anesthesia risk.

---

### 6. Craniopharyngioma

#### 6.1 Basics

- **WHO Grade:** 1
- **Origin:** Tumor of **Rathke's pouch** (sellar/suprasellar region).
- High morbidity because of **optic, hypothalamic, and pituitary** involvement.

#### 6.2 Subtypes and genetics

- **Papillary craniopharyngioma**
    - Occurs primarily in **adults (40–70 years)**.
    - > **90%** harbor **BRAF V600E** mutation.
- **Adamantinomatous craniopharyngioma**
    - More common in **children**.
    - > **90%** have **CTNNB1 (β-catenin)** mutations.
    - More infiltrative, cystic, and recurrent.

#### 6.3 Targeted therapy in BRAF-mutant craniopharyngioma

- **BRAFi/MEKi combinations**
    - Example: **vemurafenib + cobimetinib**.
- **Reported outcomes (from talk)**
    - **82% median reduction** in tumor size (15/16 responders).
    - **87% PFS at 12 months**.
- **Clinical utility**
    - Can be **radiation-sparing** or **surgery-sparing**:
        - Useful in:
            - Recurrent papillary craniopharyngioma.
            - Patients in whom additional RT or surgery would carry major risk of blindness, hypothalamic obesity, or panhypopituitarism.

> [!tip] Strategy  
> Consider **neoadjuvant BRAF/MEK therapy** in unresectable or high-risk papillary lesions to shrink the tumor before a definitive surgical or RT approach.

---

### 7. NTRK Fusions

#### 7.1 Overview

- **TRK fusions are oncogenic drivers**:
    - NTRK1/2/3 fusions → constitutive TRK signaling → MAPK/PI3K activation.
- **Frequency in gliomas**
    - **1–5%** of **low-grade gliomas (LGG)**.
    - **~0.5–1%** of **high-grade gliomas (HGG)**.

#### 7.2 Targeted agents

- **Larotrectinib**
    - Highly selective TRK inhibitor.
    - CNS activity with ~**30% response rate** in CNS tumors with NTRK fusions (as cited in talk).
- **Entrectinib**
    - Multi-kinase inhibitor (TRK/ROS1/ALK).
    - Also shows meaningful intracranial activity.

> [!info] Pearl  
> Any **pediatric or young adult glioma** with unusual histology or location and no other clear driver on routine panel → **think NTRK fusion**, especially if strongly TRK-positive on IHC.

---

### 8. VHL-Associated Hemangioblastoma

#### 8.1 Characteristics

- **Hemangioblastomas**
    - Highly vascular, often cystic lesions in the **posterior fossa, spinal cord**, or retina.
    - **Slow-growing**, but cause morbidity via mass effect, hydrocephalus, or spinal cord compression.
- **Etiology**
    - ~**75% are sporadic**.
    - Remainder associated with **von Hippel–Lindau (VHL) disease** (germline VHL mutation), often with multi-organ involvement (kidney, pancreas, adrenal).

#### 8.2 Treatment

- **Surgery**
    - Standard for symptomatic or enlarging lesions:
        - Often technically favorable due to sharp plane between tumor nodule and surrounding brain.
- **Belzutifan**
    - **HIF-2α inhibitor** targeting VHL pathway.
    - Reported **~44% response rate**, with **durable** responses in VHL-associated lesions, including CNS hemangioblastomas.
    - Can:
        - Delay/reduce need for surgery.
        - Help manage multifocal or deep-seated lesions.

> [!tip] Practical workflow  
> In a known or suspected **VHL patient** with multifocal CNS hemangioblastomas:
> 
> - Coordinate with genetics/medical oncology early.
> 
> - Discuss **belzutifan** as a systemic option, particularly when repeated surgeries or RT would create cumulative morbidity.

---

> [!todo] Local practice hooks
> 
> - Define your institution's **panel for "rare CNS tumors"** (which NGS/IHC tests to reflex to).
> 
> - Create a **short checklist** for when to call neuro-oncology/precision oncology early (BRAF+ PXA, papillary craniopharyngioma, NTRK+ glioma, VHL-associated lesions).

## Reducing Long-Term Toxicity in Survivors of Pediatric Brain Tumors

**Speaker:** Nicole Ullrich (Boston Children's Hospital, Harvard)

> [!summary]

> - > 500,000 adult survivors of childhood cancer in the US; CNS tumor survivors carry the **highest burden of late effects**.
> 
> - Late effects are **multisystem** and **progressive over time**, not static.
> 
> - Focus is shifting from "cure at any cost" to **toxicity mitigation and survivorship**: preserving function, independence, and quality of life.
>  

---

### Overall Burden of Late Effects

- **CNS tumor survivors** have the highest late-effect burden among childhood cancer survivors.
- Sequelae span:
    - **Neurologic**
    - **Sensory** (hearing, vision)
    - **Vascular**
    - **Endocrine**
    - **Fertility**
    - **Psychosocial** domains
- **Late effects increase over time**:
    - New issues emerge years to decades after treatment.
    - Existing problems may **progress** (e.g., neurocognitive decline, vasculopathy).

> [!note] Clinical aim
> 
> - For long-term survivors, the goal is not just survival but **maximizing function and QOL**, with proactive prevention, early recognition, and coordinated multidisciplinary care.

---

### Approach to Neurotoxicity

Major domains of neurotoxicity in pediatric brain tumor survivors:

- **Neurosensory**
    - Ototoxicity
    - Chemotherapy-induced peripheral neuropathy
    - Visual system toxicity
- **Neurocognitive**
- **Seizures**
- **Neurovascular** (stroke risk, vasculopathy)
- **White matter injury**
- **Secondary cancer** risk

> [!tip]  
> Think in **lifelong phases**:
> 
> - Acute toxicity → Subacute adaptation → Long-term surveillance and rehab.  
> Document baseline, track change, and intervene early.

---

### Chemotherapy-Related Toxicity

- Increasing in frequency due to:
    - More **aggressive multi-modality treatment**.
    - **Longer survival**, allowing toxicities to manifest and accumulate.
- Effects can be:
    - **Direct** (neurotoxic, ototoxic, vasculotoxic).
    - **Indirect** (endocrine, metabolic, psychosocial).
- May be **confused with tumor/metastatic effects**, particularly when imaging is complex.
- Toxicities can **accumulate over decades**, underscoring the need for structured survivorship programs.

---

### Ototoxicity

#### Etiology

- Primarily from **platinum-based chemotherapy**:
    - Cisplatin
    - Carboplatin
    - Oxaliplatin
- **Mechanism**
    - Platinum accumulates in the **cochlea** and remains there **indefinitely**.
    - Injury predominantly to outer hair cells → high-frequency loss.

#### Clinical Features

- Typically:
    - **Permanent**, **bilateral**, **high-frequency hearing loss** on audiogram.
    - Difficulty with speech discrimination in noisy environments.
    - Associated with:
        - Learning difficulties
        - Secondary cognitive and psychosocial impact.

#### Risk Factors

- Young **age at time of therapy**.
- **Renal dysfunction** (impaired clearance → higher exposure).
- **Concurrent radiation** to the cochlea/temporal bone.
- **Genetic predisposition** (e.g., polymorphisms in drug transport/metabolism genes).

#### Acute Management

- **Dose reduction** of cisplatin if early evidence of ototoxicity.
    - Maintain **low threshold** to further reduce or switch therapy.
- Avoid other **ototoxic agents** where possible:
    - Aminoglycosides
    - Loop diuretics (or use minimal effective dose).
- **Early audiology referral**:
    - Baseline testing.
    - Serial monitoring during and after therapy.

#### Long-Term Strategies

- **Close monitoring**
    - Lifelong periodic audiograms, especially during educational milestones.
- **Otoprotection**
    - **Sodium thiosulfate** given at the time of cisplatin administration (used in some pediatric protocols):
        - Can reduce ototoxicity; must balance with potential impact on antitumor efficacy.
    - **Statins**:
        - Emerging data in neuroblastoma for ototoxicity prevention.
- **Rehabilitation**
    - Hearing aids, FM systems, classroom accommodations.
    - Early speech and language services when deficits identified.

> [!warning]  
> High-frequency hearing loss is often "invisible" clinically but **highly impactful** academically. Always link audiology findings to school supports and neurocognitive follow-up.

---

### Visual Toxicity

- Can arise from:
    - **Radiation** (optic neuropathy, retinopathy, cataracts).
    - **Chemotherapy** (e.g., vincristine-related optic neuropathy).
    - **Tumor or surgical** injury to the optic pathways.
- Consequences:
    - Reduced visual acuity, field cuts, diplopia, photophobia.
    - Impaired reading, mobility, and learning.
- Management:
    - Routine ophthalmologic surveillance post-RT or optic pathway involvement.
    - Early low-vision services, school accommodations, orientation & mobility training.

---

### Chemotherapy-Induced Peripheral Neuropathy (CIPN)

#### Etiology

- **Common adverse effect** of several chemotherapeutic agents.
- Mechanisms differ by drug:
    - **Vincristine**: axonal transport disruption → sensorimotor peripheral neuropathy, autonomic dysfunction.
    - **Thalidomide** (and analogs): sensory predominant neuropathy; may be painful.

#### Clinical Features

- Distal numbness, tingling, burning pain.
- Weakness, foot drop, difficulty with fine motor tasks.
- Gait instability, falls, impaired participation in physical activities.

#### Mitigation Strategies

- **Symptomatic management**
    - **Duloxetine** – best evidence for neuropathic pain in chemo-induced neuropathy.
    - Gabapentin, pregabalin.
    - Tricyclic antidepressants (e.g., nortriptyline) where appropriate.
- **Non-pharmacologic**
    - Limit exposure to **cold** (for drugs like oxaliplatin).
    - **Exercise**, physical therapy, and occupational therapy.
    - Massage and desensitization techniques.

#### Prevention / Risk Reduction

- Monitor for early signs of neuropathy and **adjust doses** promptly.
- Cumulative dose limits where possible.
- Consider alternative regimens in high-risk patients.
- Education of families to report symptoms early.

---

### Cerebral White Matter Damage

- Mechanisms:
    - Chemotherapy (e.g., **high-dose methotrexate, cytarabine**).
    - Cranial **radiation therapy**.
    - Combined modality therapy → **leukoencephalopathy**.
- Clinical manifestations:
    - Slowed processing speed.
    - Attention/executive dysfunction.
    - Motor slowing, gait changes.
    - Emotional dysregulation.
- Management:
    - MRI surveillance when clinically indicated.
    - Neurocognitive testing and rehabilitation.
    - Consider pharmacologic supports (e.g., stimulants, modafinil) in selected cases.

---

### Seizures

- **Prevalence**
    - **15–25%** of children with brain tumors present with seizures.
    - Seizures may occur:
        - At **presentation**
        - During **treatment**
        - At **relapse**
        - As a **late effect** years after therapy.

#### Medication-Related Seizures (Culprits)

- MTX (especially high-dose or intrathecal).
- Cisplatin.
- Vincristine.

#### Seizure Mimics / Confounders

- Sleep myoclonus.
- REM/sleep motor activity.
- Jitteriness of newborns.
- GERD-related arching episodes.
- Breath-holding spells.
- Migraine equivalents.
- Fainting/syncope.

#### Risk Factors for True Epilepsy

- Cortical tumor location (temporal, frontal, insular).
- Subtotal resection (STR) vs gross total resection.
- Tumor recurrence or progression.
- Cortical scarring from surgery or RT.

#### Management Considerations

- Careful differentiation of **true seizures vs mimics** (EEG when uncertain).
- Tailor antiseizure meds with awareness of:
    - Drug–drug interactions (e.g., with chemotherapy).
    - Increased **suicidality risk** associated with several AEDs:
        - Requires monitoring of mood and behavior.
- Aim to **simplify regimens** and taper AEDs if seizure-free and risk is low.

> [!tip]  
> In long-term survivors, persistent seizures often correlate with **cortical scarring or ongoing disease**. A fresh look at imaging and surgery/RT history is frequently helpful.

---

### Neurocognitive Toxicity ("Chemobrain" / Treatment-Related Cognitive Impairment)

#### Scope

- Affects **40–100%** of CNS tumor survivors to some degree.
- Most frequently affected domains:
    - **Processing speed**
    - **Attention**
    - **Executive function**
    - **Language**
    - **Global IQ** (especially in younger children)

#### Mechanisms

- **Direct tumor impact** on brain networks.
- **Surgery** (especially in eloquent or deep structures).
- **Chemotherapy**:
    - Methotrexate
    - Cytarabine
- **Radiation therapy** effects:
    - White matter injury.
    - Microvascular damage.
    - Neuroinflammation and impaired neurogenesis.

#### Radiation Therapy Cognitive Effects

- **Ageand dose-dependent**
    - < 7 years old: most vulnerable, with greatest declines in IQ and academic achievement.
- Detrimental effects often **progress over time**, even after therapy ends.

##### Mitigation Strategies

- **Avoid RT** if feasible (e.g., molecularly favorable tumors where chemo alone is viable).
- **RT de-escalation**:
    - Lower total doses.
    - Smaller fields (e.g., focal RT vs whole brain).
- **Hippocampal sparing** when technically feasible to preserve memory function.
- **Pharmacologic strategies**:
    - Memantine
    - Metformin (emerging evidence for neuroprotection)
    - Modafinil (fatigue and attention)
    - Donepezil (memory/attention, especially in RT-related injury)
    - Stimulants (methylphenidate/amphetamine) for attention and processing speed.
- **Early and serial neurocognitive evaluations**:
    - Baseline pre-RT when possible.
    - Regular re-testing (e.g., every 1–2 years during key developmental stages).

#### Cognitive Rehabilitation

- **Computerized training** (e.g., working memory, attention platforms).
- **Attention and processing training** with neuropsychology/OT.
- **CBT** for mood, anxiety, and coping strategies.
- **School accommodations**:
    - IEP/504 plans.
    - Extra time, reduced workload, preferential seating, note-taking support.

> [!note]  
> Cognitive late effects are often **more disabling** than residual motor deficits. Early recognition and formal neuropsych follow-up should be standard in pediatric brain tumor survivorship.

---

### Secondary Cancer

- Survivors of pediatric brain tumors are at risk for:
    - **Therapy-related myeloid neoplasms** (e.g., t-MDS/AML after alkylators, topoisomerase II inhibitors).
    - **Secondary solid tumors**:
        - Meningiomas, sarcomas, high-grade gliomas in prior RT fields.
- Risk rises with:
    - **Younger age** at exposure.
    - **Higher radiation dose** and volume.
    - **Cumulative chemo** (particularly alkylating agents).
- Surveillance:
    - Long-term follow-up in survivorship clinics.
    - Patient/family education about concerning signs (new masses, neurologic changes).

---

### Vascular Complications

- Brain tumor and leukemia survivors have **increased stroke risk** and other vascular complications.

#### Mechanisms

- Radiation-induced **cerebral vasculopathy**:
    - Moyamoya-like changes.
    - Large and small vessel stenosis or occlusion.
- Chemotherapy-associated endothelial injury.
- Endocrine/metabolic sequelae (growth hormone deficiency, dyslipidemia, early metabolic syndrome).

#### Clinical Manifestations

- Ischemic stroke, TIA.
- Intracerebral hemorrhage (less common but possible).
- Progressive cognitive decline from chronic ischemia.

#### Management

- MRI/MRA surveillance in high-risk patients (e.g., cranial RT at young age, posterior fossa tumors with RT).
- Vascular risk factor optimization:
    - Blood pressure, lipids, glucose.
- Early neurology referral and, when indicated, consideration of surgical revascularization (e.g., moyamoya) in select cases.

---

### Practical Takeaways for Neurosurgeons & Neuro-Onc Teams

> [!summary]
> 
> - Survivorship begins **at diagnosis**: surgical and treatment choices should anticipate **decades** of life ahead.
> 
> - Key mitigation strategies:
> 
>     - Minimize RT dose/field where oncologically safe.
> 
>     - Use chemo regimens thoughtfully, with planned monitoring for toxicity.
> 
>     - Build in **routine audiology, vision, neurocognitive, and endocrine follow-up**.
> 
>     - Partner early with school systems, rehab, and mental health services.
> 
> - Our role extends beyond tumor control: we are co-stewards of the child's **future brain and life trajectory**.

---

## Symptom management in brain tumor patients

> [!summary] Big picture  
> Common, morbid, and often modifiable problems:
> 
> - **Seizures**
> 
> - **Headache**
> 
> - **Cerebral edema & steroid use**
> 
> - **Falls**
> 
> - **Venous thromboembolism (VTE)**  
> The neurosurgeon's role: recognize patterns, trigger appropriate workup, and coordinate symptom-directed therapy with neuro-oncology/palliative teams.

---

### Seizures in brain tumor patients

#### Epidemiology & impact

- **Presenting symptom** in ~**1/3** of patients with brain tumors
- **15–85%** will experience seizures over the disease course (tumor type/location dependent)
- **Tumor location predicts seizure semiology**
    - Temporal, frontal, insular lesions particularly epileptogenic
- Major impact on:
    - **Driving** (legal restrictions)
    - **Work** and safety-sensitive roles
    - Quality of life, cognition, mood

> [!warning] No seizure prophylaxis
> 
> - **Do _not_ start antiseizure medication (ASM/AED) in seizure-naïve patients** with brain tumors.
> 
> - Exceptions (short peri-op prophylaxis in selected craniotomy patients) are centerand surgeon-specific; long-term prophylaxis without a seizure history is **not recommended**.

#### Pathophysiology – why brain tumors cause seizures

- **Local irritation theory**
    - Cortical invasion/irritation → hyperexcitable foci
    - Temporal and frontal lobes are classic hot spots
- **Blood–brain barrier (BBB) disruption**
    - Tumor vasculature and edema alter ionic/molecular milieu
- **Glutamate homeostasis dysregulation**
    - Tumor cells can release glutamate → excitotoxicity and hyperexcitability
- **IDH1 mutation and 2-HG**
    - IDH1-mutant gliomas produce **2-hydroxyglutarate (2-HG)**
    - Acts as a "**glutamate analog**" → pro-epileptogenic environment

#### Antiseizure medications (ASM/AED)

> [!tip] General principles
> 
> - Prefer **monotherapy**, at the **lowest effective dose**
> 
> - Avoid **enzyme-inducing** ASMs (phenytoin, carbamazepine, phenobarbital) when possible in neuro-onc patients (chemo interactions)
> 
> - Think about **mood**, **fatigue**, and **cognition** when choosing agents.

**Common choices**

- **Levetiracetam (Keppra)**
    - Mechanism: binds **synaptic vesicle protein SV2A**
    - Pros: rapid titration, IV & PO, minimal interactions
    - Adverse effects:
        - **Fatigue**
        - **Irritability**
        - **Mood changes**, depression, behavioral activation → consider switch or add mood support if problematic
- **Lacosamide**
    - Mechanism: **voltage-gated Na⁺ channel modulation** (enhances slow inactivation)
    - Pros: IV/PO; relatively clean interaction profile
    - Watch for PR-interval prolongation and dizziness in frail patients
- **Lamotrigine**
    - Mechanism: **voltage-gated Na⁺ channel blocker**
    - Pros: mood-stabilizing properties can be helpful in some
    - Cons:
        - Requires **slow titration**
        - **Rare but serious: Stevens–Johnson syndrome (SJS)** → emphasize rash precautions

> [!summary] Practical neurosurgical pearls
> 
> - Document **pre-op seizure history** clearly; plan **post-op ASM duration** with neuro-oncology/epileptology.
> 
> - For breakthrough seizures:
> 
>     - Confirm **adherence** and **drug levels** if applicable.
> 
>     - Check for new lesions / progression with imaging.
> 
> - Counsel early about **driving/work restrictions** and coordinate with local legal requirements.

---

### Headache in brain tumor patients

#### Epidemiology & general features

- **Presenting symptom** in about **1/3** of patients
- Develops in **40–70%** during the disease course
- Majority are **intermittent and non-specific**, often overlapping with primary headache disorders

#### Causes of headache in brain tumor patients

- **Increased intracranial pressure (ICP)**
    - Mass effect, hydrocephalus, venous outflow obstruction
- **Rapid changes in corticosteroid dosing**
    - Quick reduction or withdrawal of dexamethasone → rebound edema/ICP
- **Medication-related**
    - **Ondansetron** is a known cause of headache
    - Overuse of analgesics → medication-overuse (rebound) headache
- **Intracranial hemorrhage (ICH)**
    - Tumor hemorrhage, anticoagulation-related bleed
- **Trigeminal nerve-related pain**
    - Tumor at skull base, CPA, cavernous sinus, or leptomeningeal spread
- **Posterior reversible encephalopathy syndrome (PRES)**
    - Chemo, immunotherapy, hypertension, renal dysfunction
- **Others (add-on to keep in mind)**
    - Meningeal carcinomatosis
    - Infection (meningitis, abscess)
    - CSF hypotension (post-LP, shunt overdrainage)

#### Evaluation & management

> [!warning] Red flags → image with non-contrast CT head (CTH) ± MRI
> 
> - **New-onset** or **rapidly worsening** headache
> 
> - Associated **neurologic deficits**
> 
> - Headache with **seizure**, **fever**, or **anticoagulation**
> 
> - Change in character during or after **dex taper**

**Approach**

- **Assess temporal relationship with dexamethasone taper**
    - If headaches worsen during taper → consider **slower taper** or brief steroid uptitration
- **Investigate with CTH** for:
    - New or severe headache
    - Anticoagulated patients
    - Acute change in mental status
- **Consider referral to headache specialist** when:
    - Underlying primary headache disorder (migraine, tension-type, cluster)
    - Mixed picture where tumor-related and primary headaches coexist
- Symptomatic measures:
    - Optimize **ICP-related factors** (edema, hydrocephalus)
    - Use **non-opioid analgesics** as first line
    - Avoid chronic opioids unless palliative context and no alternatives

---

### Cerebral edema & dexamethasone

#### Pathophysiology

- **Brain tumor–related edema** is predominantly **vasogenic**
    - Tumor invasion → **BBB compromise**
    - Plasma proteins and fluid leak into extracellular space → edema and mass effect

#### Dosing principles

> [!tip] Steroid strategy
> 
> - Use the **lowest effective dose** for the **shortest possible duration**
> 
> - Prefer **daily or q12h dosing** (e.g. BID) rather than QID to simplify regimen
> 
> - **PO and IV dexamethasone have similar bioavailability**; route is dictated by swallowing/GI status.

- Reassess **daily** in inpatients; plan a **taper** as soon as clinically feasible.

#### Withdrawal & bridging

- Risk of **adrenal insufficiency** after prolonged dex use
- In patients with severe withdrawal symptoms or high dependence:
    - Consider a **hydrocortisone bridge**:
        - **20 mg AM**, **10 mg PM** (~3 pm)
    - Then taper hydrocortisone slowly

#### Complications of dexamethasone

- From notes:
    - **Peptic ulcers**
    - **Bowel perforation**
    - **Encephalopathy**
- Common steroid-related issues to remember clinically:
    - **Hyperglycemia** (especially in diabetics or on TPN)
    - **Proximal myopathy / deconditioning**
    - **Mood changes, insomnia, psychosis**
    - **Infection risk** (including opportunistic infections)
    - **Weight gain, fluid retention**
    - **Osteoporosis, AVN** with chronic use
    - Skin fragility, poor wound healing

> [!warning] Steroid pitfalls
> 
> - Avoid "**set and forget**" high-dose dex in outpatients.
> 
> - Always document a **taper plan** in the chart and communicate it to family/primary team.
> 
> - Any unexplained delirium or GI pain in a patient on steroids → think **steroid toxicity**.

---

### Falls in patients with brain metastases / brain tumors

#### Epidemiology & contributors

- About **30% of patients with brain metastases > 65 years** will experience a fall
- Multifactorial etiology:
    - **Age-related** factors (sarcopenia, sensory loss)
    - **Comorbidities** (neuropathy, cardiovascular disease, orthostatic hypotension)
    - **Medications**
        - Sedatives, opioids, ASMs, antihypertensives, steroids
    - **Disinhibition** and impaired judgment (frontal lobe disease, steroids)
    - **Spatial dysfunction** (parietal lesions, visual field cuts, neglect)
    - **Syncope** (cardiac arrhythmias, vasovagal events)
    - **Seizures** themselves (ictal falls, post-ictal instability)

#### Prevention & management

> [!tip] Practical fall prevention bundle
> 
> - Early **PT/OT** for gait, balance, and assistive devices
> 
> - **Medication review** focusing on CNS depressants and polypharmacy
> 
> - Address **vision** issues and field cuts; consider prism lenses
> 
> - Home safety: remove tripping hazards, add grab bars, ensure adequate lighting

- In the hospital:
    - Use **bed/chair alarms** for high-risk patients
    - Provide **supervised ambulation**
    - Educate caregivers about **post-ictal supervision**

---

### Venous thromboembolism (VTE)

#### Background

- Brain tumor patients (both **high-grade gliomas** and **brain metastases**) have **high VTE risk**
    - Tumor-related hypercoagulability
    - Immobility, surgery, steroids, central lines all contribute

#### Diagnosis

- **Duplex Doppler ultrasound** of extremities for suspected DVT
- CT pulmonary angiography for suspected PE (as per local protocol)

#### Management

> [!warning] Anticoagulation & ICH risk
> 
> - Brain tumor patients are at **increased risk of intracranial hemorrhage (ICH)**.
> 
> - Balance VTE treatment against hemorrhage risk (tumor type, recent surgery, prior hemorrhage).

- **Preferred agents**
    - **DOACs** (e.g., apixaban, rivaroxaban) increasingly used in cancer-associated thrombosis, including brain tumor patients, when no contraindication
- **Pre-treatment safety check**
    - Obtain **non-contrast CTH** **prior to starting a DOAC** to:
        - Exclude active ICH
        - Assess tumor hemorrhagic propensity
- **Alternative**
    - **LMWH** may be preferred in:
        - Very high bleeding risk
        - Renal impairment
        - Peri-operative situations requiring predictable reversal/holding

> [!summary] Neurosurgical considerations
> 
> - Coordinate anticoagulation timing around **craniotomy, biopsy, and CSF diversion** procedures.
> 
> - After tumor-related ICH, re-initiation of anticoagulation is **individualized** with neurology/hematology input.
> 
> - Document clear **plan for holding/resuming DOAC/LMWH** in the chart.

---

### Quick bedside checklist

> [!check] When you're called about a brain tumor inpatient…

- **Seizure?**
    - First event or breakthrough? Check ASM regimen, levels/interactions, and imaging if change from baseline.
- **Headache?**
    - New/severe? On anticoagulation? → **Non-con CTH**.
    - Worsening during dex taper? → reconsider taper pace.
- **Confusion/decline?**
    - Think: progression, ICH, **PRES**, infection, metabolic derangements, **steroid toxicity**.
- **Falls?**
    - Review meds, check for seizures/syncope, order PT/OT, adjust safety measures.
- **VTE suspected?**
    - Get **Duplex** (± CTPA).
    - If planning DOAC, **non-con CTH first**; discuss risks with the onc/neuro team.

This structure should drop cleanly into Obsidian and serves as a working reference for day-to-day management discussions on the ward or in tumor board.


# Draft Notes
#### BREAK
##### Neurooncology imaging
###### Imaging Modalities

DWI/ADC

MRI perfusion

MRS

- metabolite spectrum
- choline: proliferation marker
- NAA: marker of neuronal integrity
- 2-HG: IDH-mutant glioma
	- Dang et al., 2009 Nature

PET imaging

- tracer uptake ~ overexpression of LAT transporters
	- independent of BBB disruption
- expression of AA transporters relatively specific for glioma/brain mets
- variants: FET PET, FDOPA PET, Methionine PET, fluciclovine PET
- RANO/EANO groups emphasis that PET adds diagnostic value
	- Lange oncology 2025; 26; e426

###### Challenges in neurooncology imaging

TN: tumor necrosis, TP; true tumor progression, PP; pseuodoprogression

Pseudoprogression

- transient increase in contrast enhancement that resolves spontaneously
- typically wtihin 12 weeks after radiotherapy completion, especially when alkylating agents are concurrently applied
- rate of pseudoprogression 10-30%
- Progressive disease should not be diagnosed if TMZ chemoradiation was completed wtihin 12 weeks (RANO)
	- two exceptions:
		- out-of-field recurrence
		- histology clearly indicates viable tumor tissue
- usually asymptomatic and resolve spontaneously
- histology
	- unable to reliably differentiate between peudoprogression and true progression
	- diagnoses correct only in 32%
	- journal of neuro-oncology; 2025
- Diagnosis
	- **clinical and radiographical** course

Radiation necrosis

- emerges 6 months to several years (24 months) after radiotherpay
	- late complication of radiotherapy
- occurs in 5% of irradiated glioms, 5-25% of irradiated brain mets
- several risk factors: radiation dose, tumor volume, re-irradiation, concurrent chemotherapy, etc.
- Diagnosis
	- **histology** is gold standard
	- hyalinization and fibrinoid necrosis of small arteries, nectotic areas, reactive gliosis
	- challenges:
		- mixed histology
- Managemeetn:
	- if symptomatic, corticosteroids, bevacizumab, even surgery

differentiation peudoprogression vs. radiation necrosis

- using standard MRI alone is challenging
- contrast-enhancement patterns have low predictive value for radionecrosis
	- dequesada et al. 2008 Neurosurg
- advaced neuroimaging techniques
	- perfusion weight, amino acid PET, etc. 
	- amino acid PET
		- may help detect pseudoprogression in gliomas
			- while there may be increased flair, metabolic activity decrease at follow up argues aginst true progresion and rather pseudoprogression
			- Diagnostic accuracy 81-96%
				- meaningful clinical decision making
		- brain mets also express LAT and AA PET may aid in diagnostic decision making
			- diagnostic accuracy of AA PET in brain mets for identfiyign true progression vs. RN vs. PP: 75%-90%

Contrast enhancement and corticosteroids

- CE volumes can be reduced by dexamethasone ~ 25%
- reduction in contrast enhancement suggests pseudoprogresion

MRS is 2-HG 

- MRS can detect 2-HG levels in IDHm gliomas
- a study in IDH wildtipe GBM suggestsed that 21% patient had falsely elevated 2HG levels

General challenges of MRS in clinical routine

- small signals (eg., 2HG) can be overlooked
	- require longer acquisition time but this risks motion artifacts
- 7T MRI require, expensive

Pitfall of perfusion MRI

- signal loss above temporal bones due to bone artifacts
- may negatively affect TP vs. PP differentiation using perfusion MRI
- Lack of uptake in subset of VNS WHO grade 2 gliomas
- lack of uptake in molecular GBMs (WHO 2021)
	- lack of typical histology features of GBM
	- represent distinct imaging phenotype
		- no contrast enhancement
- AA PET does not differentiate bewteen tumor types
	- eg., GBM, brain mets, PCNSL require tissue diagnosis
- non-specific uptake in non-tumoral lesions
	- occasionally AA uptake may occur in nontumor lesions, however rre
		- e.g., infectious, inflammatory lesiosn

172.16.48.249
#### Neurosurgical techniques in neurooncology

Presenter: James A. Balogun 

Role of surgery on neurooncology

- tissue diagnosis
- cytoreduction
- reduce ICP
- improve neurological function

Role of surgery in LGG

- early resection in LGG offers better surgical outcomes compared to "wait-and-see" approach
	- this is however controversial

##### defining extent of resection in brain tumor surgery
- gliomas
	- spectrum
		- biosy/partial resection
		- subtotal
		- GTR
	- onco-functional resection
		- balance maximal safe resection with preservation of function
	- guiding principle - safe maximal resection
	- extent of resection correlates with OSS in gliomas
		- > 75% EOR ~ better survival
	- supratotal resection in gliomas
		- resection of contrast-enhancing and FLAIR signal
		- increases PFS and malignancy transformation
- Meningiomas
	- simpson grading
		- Grade I-V
			- I (best) - GTR + dural attachment and abdnormal bone
			- II - GTR + dural attachment coagulation
			- III - GTR
			- V (worst) - simple decompression, +/- biospy

##### adjuncts
- key hole, endoscopic endonasal, sterotactic surgery, awake, craniotomy, robotic surgery, SPECT, fluorescence guided, etc.
- approaches
	- tumor localization techniques
	- localization of eloquent regions
		- neurophysiological monitoring
		- awake brain surgery, brain mapping
	- techniques that reduce bone/brain exposure
- Awake craniotyom and brain mapping
	- identify language, primary motor areas to maximize extent of resection
	- increases extent of resection
	- use of **bipolar electrode** for cortical stimulation, **monopolar stimulation** for subcorticl mapping
	- motor mapping: sttimulation-induced movement reported by patient and observed by team
	- contraindications - Hervey-Jumper et al. J. Neurosurgery (2015)
		- significant mass effect
		- obese BMI > 30, OSA
		- psychiatric history
		- < 10 years
		- intraop seizures
		- smoker
		- intraop nausea
		- reoperation (dural scar)
		- impaired pre-op function
- neuronavigation
	- accuracy affected by loss of CSF, tumor debulking, brain edema during surgery
	- subject to initial registration accuracy
	- associated with improved EOR and consequently OS
- intra-operative MRI
	- real-time update of 3D anatomical model
	- facilitates excision of LGG
	- limited availability and increased OR time
	- Level 2 evidence indicates that iMRI-guided surgery associated with increase EOR
- intraoperative US
	- Wei et al. Front Neurol (2023) Oct 26; 14:1240150
	- modifications, multiparametric US
- fluorescence-guided
	- 5-ALA or fluorescein
		- 5-ALA cross BBB, metabolized intracellularly to form protoporphyrin IX
			- give 3h prior to surgery orally
			- requires microscope with violet blue filter
	- 5-ALA associated with incrasesd EOR
		- 65% vs. < 30%?
- no increased risk of infection from use of adjuncts
	- Maye et al
- Endoscopic endonasal approache
	- collaborative effort with ENT
	- limited range of motion
	- ergonomics, fatigue
- mini craniotomies
- robot-assisted biopsies
- Laser interstial thermal therapy (LITT)
	- heat at target ~ temperature delivered + time
	- initial indications: recurrent GBM, expanding indications
		- non-resectable tumors
		- < 5 cm diameter
- tubular retractr systems
- focused ultrasounds

#### Neuropathology

Speaker: Jason T. Huse (MD Anderson Cancer Center)

Pathology: histology patterns + molecular features to guide patient management

 Brain metastases

- most common brain tumors; 200,000 per year in US
- Most common primary sites: Lung 48%, Breast 15%, Melanoma 9%, GU, GI
- unusually primary sites: prostate
- initial classification: Harvey Cushing

Tumors named after presumed precursor cells

	astrocytoma - GFAP, OLIG2

	oligodendroglioma - GFAP, OLIG, SYN

	neurocytoma - SYN

Precise histology of many primary CNS neoplasms is unclear

Grading CNS neoplasms

- Grade 2-4 is malignant
- WHO grade 1 - benigh neoplasm, surgically cured
- morphological features inform tumor grading
	- density/cellularity, nuclear atypia
	- increased mitotic activity
	- necrosis
	- microvascular proliferation
- more recent integration of molecular markers as diagnostic requires for many entities

##### Diffuse gliomas
- most common primary brain tumors
- uniformly incurable
- infiltrate into parenghyma
- adults: IDH-mutant vs. wild-type
		- IDH wt = GBM
		- IDH mutant = astrocytoma, oligodendroglioma
	- IDH mutation
		- codon 132 mutation; canonical vs. non-canonical
		- redcued catalytic activity
		- never nonsense, always heterozygous
	- 1p/19q codeletion = IDH mutant oligodendroglioma
		- grade 2/3
		- FISH can give false positive
	- ATRX deficiency = IDH mutant astrocytoma
		- grade 2/3/4
		- CDKN2A homogenous deletion
	- GBM (Grade 4)
		- hetergenous neoplastm
		- looks like cancer on molecular level (reminiscent of other cancerous entiries, e.g., breast, etc)
			- Ras/RTK/PI3K altered in 88%
			- p53 altered in 87%
		- IDH WT
		- EGFR amplification
		- Chr +7/-10
		- TERT promoter mutation
	- TERT promoter mutations
		- common i adult gliomas
		- mutually exclusive with ATRX mutations
			- therefore oligo > astro
- pediatric high-grade diffuse gliomas
	- core histone protein mutations define pediatric diffuse gliomas
		- lysine 26, lysine 34 residuees important
	- H3 K27 altered - diffuse midline gliomas
		- grade 4
		- H3 K27 mutation impaire H3K27me3 (methylation) genome-wide
			- presence of K3K27M (mutation) or lack of K3K27me3 (methylation) canbe assessed immunohistologically
	- H3 G34 mutant - diffuse hemispheric gliomas
		- grade 4''

##### ependymoma
- heterogenous, multple subtypes not detailed here
- supratentorial
	- pediatric usually
- posterior fossa
	- pediatric usually
	- posterior fossa A subtype (PFA)
		- show loss of H3K27me3 (similar to DMGs)
- spinal
	- indolent, adults
	- NF2

##### pediatric low grade neuroepithelial neoplasms
- constilation of multiple neoplasms; variety of disease entities, some better defined than others
- e.g., pilocytic astrocytomas, pleomorphic xanthostrocytoma, angiocentric glioma, etc.
- tend not to have defining features, often overlapping features
- see. Ryall et al Cancer cell 2020 - integrated molecular and clinical analiss of 1000 pediatric LGG

##### Meningiomas
- tumors of arachnoid, adherent to dura
- histology
	- psammoma bodies
- molecular features
	- molecular features separate anatomically
	- Genomic analysis of non-NF2 meningiomas (Science 2013, Clark et al - see figures)
- Grades - proliferative activity is most imporatnt prognostic feature
	- Grade 1
	- Grade 2 - 4 mitoses/10 HPF
		- solitary fibrous tumor
			- patternless pattern
			- fibrous, occasional branching avasculature
			- NAB2-STAT6 fusion is primary molecular driver
	- Grade 3 - 20 mitoses/10 HPF
		- TERT promoter mutation
			- correlated with poor outcomes, typically grade 3
		- CDKN2A homozygous deletion
			- correalted with poor outcomes, grade 3

##### embryonal neoplasms: medulloblastoma
- pfossa origin
- prone to CSF dissemination
- treatment can be curative but debilitating to pediatric patient
- histology
	- archetyal "small round blue cell tumor"
	- all WHO grade 4
	- Large cell/anaplastic associated with worse outcomes
	- nodular/desmoplastic better outtcomes
- molecular subgroups
	- WNT, SHH well-defined
	- Group 3/4 less defined

##### CNS lymphoma
- CD20+, primary molecular alteration involve B cell signaling pathway
- variant: intravascular (in situ) lyphome, confined to vascular

##### Epigenetic profiling
- Capper D, Nature 2018 - TSNE map of tumors by CpG methylation profiles
- CpG methylation profiles reflect developmental lineages
- DNA methylation profiling done if there is diagnostic uncertainty
- epigenetic profiling has delineates novel CNS tumor entities 
	- likely to be included in next iterattion of WHO classification

#### Radiotherapy

Speaker: Helen Shih

##### Radiotherapy
- most commonly ionizing radiation
- causes DNA damage directly and indirectly from free radical intermediates
- Radiation sources
	- photons/EM radiation (gamma wavelength)
	- particles: electrons, proton, neutron

##### Types of radioptheray
- Photons
	- most are photons
	- physics of photon
		- depth vs. dose% graph shows depth dependent decline in dose%; peak dose near surface 
	- stereotactic radiosurgery 
		- gamma knife
		- gyroscopic linear accelerator
		- flexible robotic arm linear accelerator
- Protons
	- depth vs. dose % graph shows shallow low dose, and highest dose at brag peak (as proton slows down)
	- offers less collateral radiation to surrounding tissues
	- indications
		- treating larger volumes (e.g., craniospinal irradiation)
		- require high radiation doses
		- treating near radiation sensitive tissues (e..g, pituitary gland)
	- associated with lower rates of meningioma incidence (vs. photon) ~ 50% less
- tumor treating fields
	- non-ionizing EM fields
	- low intensity, intermediate frequency, alternating electric fields
	- multiple proposed mechanisms; disrupting MT function, mitotis catastrophe
	- survival benefit in p/r GBM, NSCLC brain mets
- brachytherapy
	- common sourses: iodine 125, cesium 131
	- permanent implants placed and microscopic residual disease after planned tumor resection
	- common for brain metastases, meningiomas
		- post-hoc CT can map distribution of radiation
- Theranostics/radiopharmaceuticals
	- combining diagnostic imaging and therapeutic molecular targeting of diseas
	- pioneered in prostate cancer
	- e.g., SSTR2 
		- Lu-DOTATOC
			- internalized radiolabeled agonist
		- Lu-DOTA-JR

##### RT for GBM
- general approach
	- fractioned radiation therapy
	- target: T2/FLAIR + T1 enhancement. + 1-1.5 margin
	- Standdard
		- dose: 60 Gy in 6 weeks
			- higher doses show no additional benefit
		- concurrent and adjuvant TMZ
		- consider TTFields for motivated patients
	- Elderly/poor KPS GBM
		- hypofractionated RT in 3 weeks (~40 Gy)
		- shortened course has better toleratnce

TTFields for new diagnosis GBM

- provided alongisde adjuvant TMZ
- survival benefit
- improved QoL and function in recurrent GBM, but no different in OS

Bevacizumabe + RT better with PFS, but no incrase in OS

##### RT for non-GBM gliomas
- general approach
	- frationated radiation therapy
	- target: same as for GBM
	- IDH WT: 54-60 GY in 6 weeks
	- IDH mutant: 50-59 GY in 6 weeks
		- non-codel - adjuvant TMZ
		- PCZ (what are indications? to check)

##### Brain metastases
- 1-3 small metastases (< 2 cm)
	- SRS
	- consider SRS for up to 10 metastases
- intermediate size (2-4 cm)
	- conisder lcoation, histology, patient
	- options: WBRT alone, preop or postop RT, or local fractionated RT
- large, single metastasis
	- surgery, then
		- post-op WBRT or local fractionated RT
		- consider postop SRS (risk of LMD, necrosis)
- many metastases
	- WBRT with hippocampal avoidance + memantine
- LMD
	- local palliation: WBRT, medical therapy, trials or hospice
	- craniospinal radiation
		-  improved OS/PFS

##### Meningioma
- if small; monitor
- if large; surgery
	- grade 1 - surgery alone
		- RT only for small unresectable lesions 
		- Rt for recurrence
	- Grade 2-3 - require GTR
		- maximal surgery + postop RT (60 Gy)
			- Rt best with less residual disease
		- any grade 3 is poorly controled even with RT
		- higher RT improves local control, but associated with toxicities

##### steps to RT
- radiation planning
	- create mask
- define radiation target (integrate MRI + CT)
	- include error margin
- target and nontarget definition
- 3D-CRT vs. IMRT (intensity modular radiation therapy) vs. VMAT (volumetric modulated arc radiotherapy)
	- placeholder - further detail required
- Daily set up check by cone beam CT
	- registration (today vs. original plan)
- SRS
	- similar work flow
	- typically smaller tumors: brain metas, meningiomas, acoustics, pituitary adenoma
	- multiple fractions

##### General aspects of radiation therapy
- fractioned therapy
	- daily, 5d/w, often 2-7 wks, 10-20 min per day
	- SRS 1 treatment, 20-60 min
	- radiation is not feld, no pain or discomfrot
- factors in designing RT plan - site, volume, total dose, disease relate comorbities, life expectancy
- side effects
	- acute
		- fatigue, nausea, HA, skin redness, hair loss, neuro symptoms, delayed wound healing
	- late
		- persistent fatigue, hypopituitarism, brain parenchymla injury, visual pathway injury, hearing loss, bbrain necrosis, vascular stenosis, CVA, secondary tumor (1% llifetime risk)
	- SRS
		- 90% have no sympomts
		- 10% havef symptoms: fatigue, HA, seizure (rare), late RN

#### Chemotherapy and systemic therapies

Speaker: Lauren Schaff

CNS lymphoma terminology

	Induction

	- goal is to induce remission

	consolidation therapy

	- single or short-courrse of therapy ; goal is to prevent recurrent

	Maintenance therapy

	- maintain remission

##### Chemotherapeis

chemotherapy classess

- cell cycle non-specific
	- alkylating agents
- cell cycle specific
	- phase-specific: antitmetabolites, antimitotic agents
- Phase non-specific
	- alkylating agents, platinum compounds

###### Anti-metabolites (typically G1-specific)
- Agents 
	- antifolates: methotrexate, pemetrexed
	- pyrimidine antagonists: 5FU, cytarabine,
	- purine antagonists: 6-mercaptopurine
- Methotrexate
	- inhibits dihydrofolate reductase, blocks preduction of tetrahydrofolic acid required for purine synthesis
	- DNA/RNA replication haltered
	- reuqires high doses in CNS
	- administration requires hospital admission
		- continuous IV hydration until clearange
			- to prevent renal toxicity
		- urine aklalinization
			- to prevent crysatlization in kidneys
		- leucovorin (folinic acid) systemic 
			- does no cross BBB
	- first-line treatment of CNSL
		- 90% overall response rate

###### DNA-damaging agents
- direct damanget to DNA cross-line
- alkylating agent
	- cross-link DNA with alkyl group so canno uncoil and separate, cells cannot divide
	- toxicities: myelosuppresion, nausea, vomiting, secondary malignancy, alopecia
- TMZ in glioma
	- part of Stupp protocol (NEJ 2005)
	- conomitant phase
		- 75 mg/m2
	- adjuvant phase (5 day cycles; 5 on, 2 off)
		- cycle 1: 150 mg/m2
		- cycle 2+: 200 mg/m2
	- interactions: food (administrer on empty stomach), valproic acid 
	- toxicity: constopation (everyone), n/v (adjuvant phase), fatigue, myelotoxicity, thrombocytopenia
		- much gentler chemotherapy than "typical" chemo
		- risk: female > male, genetic morphisms
- Nitrosoureas
	- lomustine (CCNU) and carnmustine (BCNU)
	- route of administration: CCNU - oral, BCNU - IV
	- higher CNS concentrations
	- toxicities: 
		- myelosuppression
		- pulmonary fibrosis with cumulative doses
	- interactions:
		- CCNU: VPA, duloxetine
- Procarbazine (PCZ)
	- common for oligodendroglioma and CNSL
	- drug interactions
		- serotonergic agents (due to mild MAOI properties)
		- tyramine containing foods (HTN crisis)
		- ethanol

###### Anti-mitotics
- vinca alkaloids
- vincristine (used in PCV regimen)
	- procarbazine, CCNU, vincristine (PCV) for oligodendroglioma
		- 1 cycle = 6-8 weeks due to prolonged nadier
			- D1 CCNU
			- D8 vincristine
			- D8-21: procarbazine
			- D29: vincristine
		- Duration: 6 cycles
		- monitor: PFT, CBC

##### Targeted therapies (-inibs)
- IDH inhibitors
	- D2HG leads to altered histone methylation, DNA hypermethylation, defective collagen matruation
	- vorasidenib in IDHm LGG
		- 22.6 month PFS vs. 11.1 month PFS in placebo; HR 0.39
		- targets IDH1 and IDH2
		- well tolerated, taken daily
			- transaminitis most common lab derangement
- BTK inhibitors
	- BCR and TLR pathways upregulared in CNSL
	- used when methotrexate fails
	- ibrutinib
		- 4 month improvement in PFS with ibritinib monotherapy, therefore typically used as combination therapy. 
	- adverse effects
		- cardiac conduction abnormalities (e.g., afib), HTN, GI upset (n/v), rash, myalgias, cytopenias, opportunistic infections (aspergillosis, PCP pneumonia - often on prophylactic ABx)
	- First generation: ibrutinib
	- several second generation BTK ijhibitors exist
- BRAK/MEK inhibitors
- tyrosine kinase inhibitors
	- bind ATP binding site inhibiting TK activity
	- e.g., EGFR, ALK inhibitors
		- osimertinib for EGFR-mut NSCLC brain mets
	- can delay RT requirement for brain mets (improved PFS, but not OS?)
##### Immuno-oncology agent
- monoclonal Ab
	- targets: VEGF, CD30, etc.
	- toxicities: infusion reactions
	- Bevacizumab (anti-VEGF) 
		- reduces cerebral edema in glioma
		- improves PFS but no difference in OS for GBM
		- used as steroid-sparing agent
- checkpoint inhibitors
	- e.g., anti-PD1, anti-PDL1, anti-CTLA4, anti-LAG
		- effective in melanoma.
	- adverse events:
		- grade 1-4
			- grade 1: continue
			- Grade 4: permanent discontinuation
		- managed with steroids
		- common: thyroiditis
- CART therapy
	- patient's T cell genetically modified to recognized antigens expressed on cancer cells
	- toxicity: 
		- cytokine release syndrome (CRS) - systemic inflammatory reaction
		- immune effect cell-associated neurotoxicity syndrome (ICANS) - encephalopathy, aphasia
			- ICE score used to score severity 
			- managed with steroids if severe

#### Management of Brain metastasis

most common brain tumor

- 160-200k per year (25k for gliomas)
- 5-10% of cancer patients present with brain cancer first
- most common: lung, breast, melanoma, renal, colon, lymphoma
- least common: prostate, liver

Screening

- screen any cancer patient with neuro symptoms
- Stage I/II - no screening
- Stage III/IV - proceed with screening
- PET CT no adequate, MRI is preferred

Management

- 1-3 mets
	- SRS (<2 cm)
	- surgery then SRS (preferred over WBRT)
- > 3 mets
	- WBRT vs. SRS

RT toxicity

- progressive increase in FLAIR, atrophy
- "accelerated dementia"
- SRS is better tolerated than WBRT

Surgery indications

- tissue diagnosis
- molecular data
- mass effect
- steroid dependence
- concern that radiation will worsen swelling

Drug delivery doesn't matter as much as drug activity

- Gd3+ means BBB is broken down
- MTX has low MW but doesnt work well

Systemic therapies for BrM

- SRS when using CNS active chemo does not dictate survival
- osimertinib improves CNS PFS and reduces risk of CNS as site of progression in NSCLC EGFRmut
- osimertinib + chemo (plastinum-pem) improves PFS + OS in CNS met patients
	- FLAURA2 combination therapy (JCO 2023)
	- cost of increased activity is increased toxicity
- Lorlatinib (ALK TKI) has profound brain responses in NSCLC
	- CROWN P3 study (JCO 2022)
- Tucatinib produces CNS response in HER2+ breast cancer patients
	- HER2CLIMB study - tucatinib + trastuzumab + capecitabin
- Adagrasib (KRAS G12C) inhibitor in NSCLC
- Selpercatinib for RET-fusion NSCLC 

Can radiation be deferred in patient receving a potential CNS-active TKI?

- no difference in PFS in patient that received SRS with TKI vs. TKI only
- No concensus in US on deferring SRS

Immunotherapy in NSCLC BrM

- not as clear of a benefit as in melanoma
- pembrolizumab response rate was ~30% in NSCLC BrM

Activity and MOA matters more than size of agent 

antibody-drug conjugates

- trastuzumab-deruxtexan produces responses in HER2+ breast cancers
- amivantamab + lazertinib extent PFS and OS in NSCLC BrM + LMD
- B7-H3ab-topo inibitor (IDEATE-Lung01 trial), ~69% response rate 

Tumor treatment fields

- METIS: TTS + best standard of care improves time to progression in NSCLC without driver mutations (EGFR, ALK, ROS, BRAF)
	- but not change to median overal survival

Leptomeningeal metastasis

- 5-8% of cancer patients
- symptoms: n/v, HA, seizures, non-descript (doing poorly)
- diagnosis frequently missed
- prsent at autopsy in ~ 20%
- incidence increases with longer cancer surivvial
- focal RT after surgery for mets may increase risks 
	- Breast (28%) vs. lung (~18%)
- Cellsearch: isolating CTCs in CSF using EpCAM
	- CTCs correlate with survival 
	- however, many cancers loose EpCAM or don't express it (even in breast and lung)
- Mutli-Ab cocktail captures more CTCs
	- 11 antibodies to capture CTCs
	- more sensitive than cytology
	- CNSide technology*** check - Louis, rogowskim, nagpal ASN/SNO Mets 2025
- cfDNA in CSF may reflect clinical course
- Trials
	- TUXEDO-3

#### Management of Low grade (IDHm) gliomas 

speaker: Jennie W. Taylor (UCSF)

background

- diffuse LGGs represent small percent of all primary brain tumors
- IDH mutant age average: 36-45 years
	- male > female
	- vs. 65 year for GBM
- survival 
	- IDH-mutant patients live ~5-20 years (vs. 15 monh for GBM)
		- slight survival advantage in female (vs. male)
- post-op residual volume correlates with OS and malignant transformation (for all grade 2 gliomas)
	- Hervey-Jumper JCO 2023
- radiation upfront vs. at recurrence does no improve OS, but does improve PFS. 
- adjuvant chemotherapy (PCV) has PFS/OS benefit
- CATNON (van den Bent, Lancet 2021)
	- anaplastic astrocytoma (grade 3 astro)
	- adjuvant TMZ is better than only concurrent TMZ
- EORTC and RTOG trials
	- PCV (multiagent chemotherapy regimen) is associated iwth survival benefit that becomes evidence after 7 years of treatment
	- caaveat is that PCV is toxic, and requires long course of treatment.
- ongoing debate: TMZ vs. PCV for mIDH gliomas
	- TMZ has milder toxicity profile
	- retrospective data (POLA network; Kacimi JCO 2024) suggests that PCV is superior to TMZ 
	- CODEL study is RCT that will address this question
- Historical treatment algorithm - several options
	- any grade 2 or oligo grade 3 with GTR - surveillance 
	- any oligo - chemo monotherapy
	- any - surgery + chemorads
- complications of treatment
	- radiation necrosis, hemorrhage, hypermutation
	- therefore must balance risk of tumor progression vs toxicity of treatments

##### IDHm inhibition
- functional mutation
- WT - alpha ketoglutarate produced
- Mutation - aKG shunted to 2HG, oncometabolite - DNA hypermethylation, chromatin modificaiton, hypoxia response
- INDIGO study (Cloughesy Lancet oncol 2025) - vorasidenib
	- newly diagnosed IDHm grade 2 (s/p OR within 1-5 year)
	- randomized and blinded, treated
	- at time of disease progression, unblinded
		- if on placebo, cross over to vora
		- if on vora, secondary agents started
	- primary outcome: vorasidenib improves PFS (HR 0.35)
		- independent of 1p/19q status, age, number of surgeries, EOR, tumor size
	- secondary outcomes TTNI, QOL
		- improves time to next intervention (HR 0.25)
		- associated with smaller tumor volumes i.e., treament impairs tumor growth
		- reduces seizure frequencies (rate ratio = 0.36)
			- appears to be oligodendroglioma-specific seizure reduction; no obvious change seen in astrocytoma

#### Management of GBM

Speaker: Rimas Lukas (northwestern university)

- heterogenous imaging
	- ring enhacing, solid enhacnign, heterogenous enhancing, non enhancing
- Surgery
	- RANO-RESECT - supramaximal resection is advocated
- Pathology
	- pseuodopallsading necrosis
	- microvascular proliferation
- molecular characterization
	- IDH wt
	- TERT promoter mutation
	- EGFR gene amplification
	- Gain of 7, loss of 10 chromosome copy number changes
		- homozygous loss of 10 chromosome - lack MGMT gene
			- pathology reported as "MGMT gene unmethylated", but may actually do cliincally well. 
	- DNA methylation
		- subtypes: mesenchyymal (NF1, RB1), RTK1 (PDGFRA), RTK 2 (EGFF), RTK 3, MYCN
		- all subtypes currently managed the same

##### Epidemiology
- 14 % of all brain tumors
- ~66 average age
- risk
	- increase: ionizing radiation
	- decreased: allergies, atopic disease (eczema, psoriasis, asthma)

##### Treatment
- surgery
	- diagnostic and therapeutic benefit
- radiation
	- standard: 60 Gy in 30 fractions
	- Elderly/poor KPS
		- 40 Gy in 15 fractions
		- 25 Gy in 5 fractions
		- other modified protocols, etc
- chemotherapy
	- temozolomide
		- TMZ crosses BBB
		- then converted to MTIC (active agent)
	- MGMT removes guanine from O6 position, threrfor reducing efficacy of TMZ
		- MGMT methylation therefore asssociated with better outcomes

##### Improvement in survival over time
- pre TMZ vs. TMZ vs. TTF era
- GEINO trial - slight modification in TMZ regimen
	- assessed duration of therapy 6 vs. 12 cycles of TMZ - no changes 
	- therefor now using 6 cycles
- Stupp protocol
	- 10% 5y survival (Stupp protocol; RT + TMZ) vs. 2% 5 year (RT alone)
	- KPS < 70% does not benefit
- Tumor treatment fields
	- mechanism:
		- biophysical: force/torque effects, thermal effect, disturbance on MV
		- biochemical: enhances immune response, effects on organelles, unbaalnce chemical enviroemnt
	- offers 5-month OS improvement (up to 20.9 month survival)
	- Stupp et al JAMA 2017 

##### Management of Progressive disease
###### Bevacizumab
- phase 3 studies: RTOG, AVAGlio, EORTC (all negative studies, no improvmenet in OS)
- currently used to manage symptomatic cerebral edema
###### CCNU
- alkylating agent; nitrosurea
- MOA: DNA/RNA alkylation, cross-linkg and protein carbomylation (mimics senescence)
- Trials: STEERING, REGAL, RELOB, REGOMA
- response rate: ~10%
- may have a role in recurrent tumors previously treated with TMZ

#### Management of meningiomas

##### Epidemiology

Most common primary intracranil tumor

- 42,000 cases per year in US
- 99.2% non-malignant; 0.9% malignant
- female> male
- highest incidence among non-hispanic black patients
- highest incidence for malignant meningioma is in non-hispanic asian or pacific islander
- incidence increases with age
- median age of diagnosis 65-70y
- risk factors:
	- ionizing radiation
	- hormonal abnormalities
	- increased BMI
- many incidentally discovered
- only 34% histopathologically proven
- little consensus on optimal treatment
- no FDA approved chemotherapy or molecular targets
	- molecular drivers poorly understand

##### Imaging
- dural-based, occasionally invasive
- elevated CBF/perfusion
- DOTA-TATE PET/MRI

##### Molecular characteristics

Meningioma short somatic variantes correlate with tumor location and histology

- pfossa: NF2
- middle fossa skull base: KLF4/TRAF7
- midline/clival: AKT1/TRAF7
- cribiform: SMO L4a2F

meningioma clinical course difficult to predict

- WHO grade 1-3 implies behaviour, but not perfect
- Morphology/subtype alone should probably not determine grade
	- choroid/clear cell meningiom - higher likelihood of recurrence - grade 2
	- rhabdoid and papillar morphology - historically grade 3 but perhaps no suffiient

alterations of note

- BAP1 - rhabdoid, papillaryy subtype, Grade 3
- KLF4/TRAF7 - secretory subtype, Grade 1
- SMARCE1 - clear cell subtype, Grade 2
- TERT promoter mutation - grade 3
- CDKN2A/B homozyg deletion - Grade 3
- H3 K27me3 loss - Grade 2 vs. 3

Mengingiom CNS WHO grading

- Grade 1 (75%)
	- < 4 mitoses / 10 HPF 
- Grade 2 (15-20%, atypical)
	- 4-19 mitoses / 10 HPF
	- brain invasion
	- soft histologic criteria (necrosis, small cell sheeting, macronucleoli, hypercellularity)
- Grade 3 (1-5%, anaplastic
	- > 19 mitoses / 10 HPF
	- CDKN2A/B homozygous deltion or TERT promoter mutation

Menginioma DNA methylation identifies CNV independently prognostic for outcomes

- merlin-intact (best prognosis)
	- Chr 5 gain, 6p loss (HLA)
	- NF2 expression
	- 81% grade 1, 17% grade 2, 2% grade 3
- immune-enriched (intermediate prognosis)
	- 6p gain (HLA), 22q loss (NF2)
- hypermitotic (worst prognosis)
	- 1p loss, 1q gain (USF1); 6p loss (HLA); 9p loss (CDKN2A/B); 14q loss or gain, 22q loss (NF2)
	- FOXM1 expression
	- CDKN2A/B hypermethylation
	- 43% Grade 1, 45% Grade 2, 12% Grade 3

##### Management
- observation
- surgery
	- Simpson grading, 10% increased recurrence rate per grade
- radiation
	- indications
		- STR of Grade 1 (due to 50% risk of local progression in 5 years)
		- any Grade 2 or 3
	- approaches
		- fractioned
		- SRS
- systemic therapies/trials

Outcomes of meningioma after radiation

- Grade 1
	- SRS: 5y control rate 86-100%
	- fractionated 5y control rate: 68-100%
- Grade 2
	- SRS: 0-94% 5y control

IMPASSE Study

- incidental meningioma progresion during active surveillance or after stereotactic radiotherapy
- ?results of study?

Targeted therapies

- FAK inhibitor (GSK2256098) 
	- NF2 mutants
	- good response at 6 months
- various trials ongoing, with early promise

#### Management of PCNSL

Speaker: Karan Dixit

Introduction

- uncommon variant of aggressive extranodal large B-cell lymphoma
- 2% of CNS tumors
- primary large B-cell lymphoma of immune-privileged sites 
- confined to CNS without concurrent or prior systemic lymphoma

Presentation

- subacute onset
	- focal neuro deficits (50-70%)
	- nonspecific cognitive/behavioural changes (>50%)
	- elevated ICP (30%)
- seizures uncommon (10%)
- constitutional symptoms (rare)
	- fevers, night sweats, weight loss 
- ocular involvement in 15-20%
	- blurred vision, eye floaters, photophobia
	- **ophthalmology consult** warranted for intravitreous assessment
- Concomitant LMD (15%) at presentation
- isolated CN, spinal cord or cauda equina involvement at presentation is rare

Imaging

- earky recognition is key
- irregular boundaries
- multifocality common
- deep brain and periventricular involvement (~60%)
	- thalamus, basal ganglia, corpus callosum
- hemorrhage, calcification, necrosis are not common
- CT findings
	- isodense to hyperdense (high tumor cellularity) mass lesion
- MRI findings
	- immunocompetent
		- homogenous enhancement
		- hyperintense DWI
		- hypointense ADC
	- immunocompromised
		- peripheral enhancement
		- hyperintense DWI
		- hypointense ADC

Diagnosis

- defer corticosteroids if possible
	- lymphotoxic, disrupts cellular morphology
	- use osmotic therapy for edema management
- MRI +/- GAD
- CSF for routine studies; cytology, flow, molecular biomarkers (MYD88, IL10, IgG)
	- do not wait for negative CSF before considering biopsy
	- only 7% had positive CSF cytology which obviated need for biopsy
- also consider testicular U/S

Staging

- spine MRI if localizable symptoms or positive CSF
- ophthalmology evaluation
- if unable to obtain PET CT
	- testicular U/S for males > 60
	- bone marrow biopsy if any cytopenias

Sentinel inflammatory lesions

- placeholder
- even if initial pathology is negative, continue to follow with seial MRI scans

Pathology

- non-germinal center / activated B-cell subtype
	- but can be germinal center
- malignant cells express pan B cell markers

Prognosis

- scoring schemes (both older): IELSG, MSKCC 
	- both use KPS and age
	- IELSG also assess tumor location and CSF protein

Treatment - curative intent

- high-dose methotrexate (cornerstone of treatment)
	- alkylator (procarbazine, temozolomide, thiotepa)
	- rituximab
	- +/- cytarabine
	- +/- vincristina
- Regimens (all use methotrexate + rituximan, plus some additional agents)
	- MT-R: methotrexate, TMZ, rituximab
	- R-MVP
	- MATRix
- Patients that are not fit for chemotherapy
	- represent 15% of cases
	- whole brain radiation is an option
	- oral agents
		- TMZ, BTK inhibitors, IMiD, rituximab
	- supportive care
- post-induction therapy: consolidation
	- high-dose chemotherapy and autologous stem cell transplant
		- thiotepa-based HDC-ASCT
	- non-myeloablative chemotherapy
	- dose-reduced WBRT
- post-induction therapy: maintenance
	- TMZ x 12-24 months
	- methotrexate x 12 months
	- lenalidomide until progression
	- BTK inhibtiion until progression
	- rituximan x 24 months
- Refractor/relapsed disease
	- 15-25 % are refractor to induction
	- 25-50% relapse within 2 years after induction
	- early vs. delayed relapse have different clinical course
	- management
		- consider clinical trials
		- HD-MTX rechallenge
		- change agents
		- molecularly targeted treatment
		- immunotherapy
		- WBRT

#### Pediatric neuro-oncology

Speaker: Sonia Partap (Stanford)

background

- brain tumors most common cancer in childhood
	- 25% of childhood cancers
- most common cause of childhood cancer-related death in USa
- boys > girls

Glial vs. nonglial tumors

Pilocytic astrocytoma 

- cystic, mural nodule
- pathology
	- biphasic pattern
	- piloid (hair-lik) processes
	- eosinophillic granular bodies
	- rosenthal fibers
- 15% of childhood brain tumors
- well differenitatied
- grade 1 WHO
- majority (80%) are cystic
- predisposition in NF1
- management
	- surgically curable
	- 5-year OS 97%
		- becomes chronic condition
		- 20y OS 87%
	- treatment options (if non-resectable)
		- chemotherapy: carboplatin and vincristine, vinblastine
		- clinical trials 
		- molecular therapy
		- radiation 
- BRAF: sensitive to MEK and BRAK-V600E inhibtiors
- coommon mutations in pediatric gliomas
	- BRAF fusion
		- use MEK inhibitors (selumetinib), becuase BRAF inhibitor will actually lead to growth (due to feedback) - Fangusaro Lancet 2019
		- ongoing trial COG ACNS 1833 assess selumetinib in non-BRAF V600 patients
	- BRAF v600E mutations (worse prognosis than fusion)
		- use BRAF inhibitor: dabrafenib + trametinib
		- tovorafenib - 50% response rate (FIREFLY2 trial)
			- for relapsed LGG in pediatric patients
			- pan-RAF inhibitor
	- IDH mutations (16.1%)
		- ivosidenib, vorasidenib
	- NTRK fusion - larotrectinib
- adverse effects
	- MAP/BRAF
		- skin toxicities
		- retinal detachement
		- cardiac toxicitiy
	- tovorafein
		- growth retardation
		- intratumoral hemorrhage

Diffuse intrinsic pontine glioma (DIPG)

- MRI
	- expansion of pons
	- other features: to add
	- non contrast enhancement
- symptoms
	- CN6 palsy
	- ataxia
	- long-tract signs (UMN) - hyperreflexic or hypertonia
- prognosis: poor, 11 months
- molecular profile: H3 K27M mutant
- treatment
	- local field radiation 54 Gy
	- clinical trials
	- ONC201/dordaviprone
		- dopamin receptor antagonist

Epndymoma

- pathology: 
	- perivascular pseudorosettes
- 4th ventricle tumor
- 5% childhood tumors
- more common among NF2
- WHO grade 1-3
	- brain: subependymoma, classifc, anaplastic
		- supra vs. infratentorial
	- spinal cord: myxopapillary
- management
	- stage
	- surgical resection
		- EOR is prognostic
	- conformal XRT to tumor site

Germ cell tumor

- 3-5% childhood brain tumors
- peak age 10-14%
- increased incidence in klinefelter
- females: 75% suprasellar, males: 70% pineal region
- diagnosis
	- MRI brain and spine
	- serum and CSF markers: AFP, bHCG
	- biopsy
- types
	- germinoma
		- chemosensitive (carboplatin, etoposide)
		- need XRT
		- 90% 5y OS
	- non-germinoma
		- more aggressive
		- carboplatin/etoposide/ifosafmide
		- other stufff...
- ongoing trials

medulloblastoma

- pathology
	- homer wright rosettes
- 40-50% of cerebellar tumors
- majority 3-9 yeras
- male > female
- can be associated with genetic syndromes
- embryonal tumors
	- medulloblastoma
	- embryonal tumor NOS
	- pineoblastoma
	- ATRT
	- ETMR
- Group 3 tends to metastasize
- Chang M-staging for MB after surgical resection
	- M0 - no evidence of subarachnoid or hematogenous metastasis
	- M1 - tumor cells found in CSF
	- M2 intracranial tumor beyond primary site
	- M3 - nodular seeding in spinal cord
	- M4
- MB staging
	- average vs. high risk
- treatment
	- maximal resection
	- radiation (based on MB stage risik)
	- chemo: cyclophosphamide, cisplatin, vincristine +/- others
- germline mutations 
	- ELP1, SUFU, CHEK2, BRIP1, APC, BRCA1, EGFR
	- occasionaly requires genetic counselling

#### Rare CNS tumors

grounding questions

- how will it affect the patient's life / health expectancy
- is it likely to habour a targetable alteration?

many rare cancers have targetable mutations

- i.e., oncogenes
- tageted therapy may povide durable benefits
	- however resistance may emerge overtime
- signaling cascade of interest
	- FGFR, TRK, BRAF
- Types of alterations
	- SNV, poiint mutations
		- NGS, IHC, sanger sequencing , RNA seq, circulating tumor DNA
	- gene rearrangements, fusions
		- FISH, RNA-sequencing, DNA probes

BRAF mutations

- common in rare CNS tumors (> 50%)
	- also vast majority of pediatric LGG have BRAF
- Select examples of rare tumors
	- circumscribed asttrocytic tumors
		- pilocytic astrocytoma
			- WHO grade 1
			- most common glioma in children; 25% occur in adults
			- treatment: surgery, BRAF-targeted therapy (dabrafenib/trametinib), radiation (if recurrent or high risk)
		- pleomorphoic xanthoastrocytoma
			- characteristcs
				- WHO grade 2-3
				- circumscribed astrocytic gliomas
				- hetrgeoneous enhancement
			- presentation
				- seizures
				- frequent CSF spears
				- age 20-40
			- treatments
				- surgery
				- radiation therapy
				- systemic treatment - no definitive role, however some respond to alkylating agents
				- BRAF-targeted therapy
		- etc. 
	- glial and gliobeuronal tumors
		- ganglioglioma
			- characteristics
				- WHO grade 1 (usually)
				- glial and glioneuronal neoplasm
			- presentation
				- seizures
				- may be found incidentally on temporal lobectomy for epilepsy
				- average age 20 yr
				- up to 60% have BRAF V600E mutation
			- treatment
				- surgery
				- observation
				- if recurrent, BRAF-targeted therapy
		- etc.
- BRAF target therapies have diverse MOA
	- Class 1 = monomeric, RAS indpenedent
		- dabrafenib, encorafenib cemurafenib do not work against WT BRAF
			- associate with loss of negative BRAF feedback
		- to mitigate toxicity, given with MEK inhibitors - trametinib, binimetinib, cobimetinib
	- Class2 = dimer dependent, ras independent
		- tovorafenib
		- along with MEK inhibitors (trametinib, selumetinib)
- targeted therapy is effect in adult BRAF V600E gliomas
- BRAF dimer disrupter tovorafenib is effective in LGG
- toxicities
	- 90% have side effectst
	- 50% grade 3 or higher toxicities
	- 5% will need to stop
	- adverse reactions: maculopapular rash, pyrexia, retinopathy, squamous cell carcinoma, fatigue, decreased ejection fraction, anemia, AST/ALT elevation

Craniopharyngioma

- characteristics
	- WHO garrde 1
	- Rathke's pouch tumor
- Subtype
	- papillary
		- > 90% BRAF V600E mutation
		- adults 40-70 years
	- adamantinomatous
		- > 90% CTNNB1 mutation (B catenin)
		- pediatric tumor
- BRAF-mutant craniopharnyoma responds to BRAFi/MEKi targetted therapy
	- vemurafenib + cobimetinib
		- 82% reduction in tumor size (15/16 responders)
		- 87% PFS at 12 months
	- can be radiation-sparing

NTRK fusions

- rare but actionable
- characteristics
	- TRK fusion is ongogenic
	- occurs in 1-5 % of LGG, 0.5-1% HGG
- targeted treatements
	- larotrectinib - 30% response rate
	- entrectinib

VHL-associated hemangioblastoma

- characteistics
	- slow growing 
	- 75% sporadic
- treatment
	- surgery
	- belzutifan - HIF 2alpha inhibitor
		- 44% response rate, durable

#### Reducing long-term toxicity in survivors of pediatric brain tumors

Speaker: Nicole Ullrich (Boston Children's Hospital, Harvard)

- > 500,000 adult survivors of childhood cancer in US
- CNS tumor survival have the highest burden of late effects
- sequelae span multiple systems
	- neurologic, sensory, vascular, endocrine, fertility, psychosocial domains
- late effects increase overtime
- focus on toxicity mitation to improve function and QOL

Approach to neurotoxicity

- neurosensory
	- ototoxicity
	- chemotherapy induced peripheral neuropathy
- neurocognitive
- seizures
- neurovascular

chemotherapy related toxicity

- increased frequency (due to increased aggressive treatment, long survival)
	- direct and indirect effects 
	- may by confused with metastatic effects
	- issues may accumulate over span of decades
- types
	- ototoxicity
		- primarily platinum-based chemotherpay
			- cisplatin, carboplatin, oxaliplatin
		- platinum accumulates in cochlea and stays indefinitely
		- often permanent, bilateral, high-frequency deficit on audiogram
			- associated with learning issues, and secondary cognitive deficit
		- risk factors:
			- age at time of therapy
			- renal dysfunction
			- concurrent radiation
			- genetic predisposition
		- acute management
			- dose reduction of cisplatin
			- low threshold to further dose reduction
			- avoid other ototoxins
			- early audiology referral
		- Long-term strategies
			- close monitoring
			- otoprotection
				- sodium thiosulfate at time of cisplatin administration
				- statins for ototoxicity prevention in neuroblastoma
	- visual
	- peripheral neuropathy
		- common adverse
		- mechanism differs based on specific chemotherapeutic agent
			- vincristine, thalidomimde
		- neuropathic pain and discomfort
		- mitigation strategies
			- duloxetine (best evidence), gabapentin, TCA
			- limit exposure to cold, exercise, massage
		- prevention
	- cerebral white matter damage
	- seizure
		- 15-25% of children with brain tumors present with seizures
		- can occur at any time: presentation, treatment, relapse, late effect
		- increased suicidality associated with several AEDs
		- seizure mimics/culprits
			- cultprits: MTX, cisplatin, vincristine
			- mimics: sleep myoclonus, sleep/REM motor activity, hitteriness of newborn, GERD, breathholding spells, migrain, fainting/syncope
		- risk factors:
			- cortical location, STR, tumor recurrence
	- neurocognitive (chemobrain)
		- impacts 40-100% of CNS tumor survivors
		- most frequently affect domains: processing speed, attention, executive function, language, IQ
		- mechanism
			- direct tumor impact
			- surgery
			- chemotherapy (MTX, cytarabine)
			- RT effects
			- white mater injury, neuroinflammation
		- radiation therapy cognitive effects
			- age/dose-dependent
				- <7 years old most affected (greatest effect in IQ)
			- detrimental effects more pronounced over time
			- mitation-strategies
				- avoid radiation if possible
				- radiation de-escalation
				- hippocampal sparing
				- pharmacological: memantine, metformin, modafinil, donepezil, stimulants
				- early and serial neurocognitive evaluations
		- cognitive rehab
			- computerized training
			- attention processing training
			- CBT
			- school accomodations
	- secondary cnacer
	- vascular complications
		- increase stroke risk in survivors of brain tumors and leukemia

#### Symptom management for brain cancer patients

Seizures

- presenting symptoms in 1/3 patients iwth brain tumors
- 15-85% will experience seizures during disease course
- tumor location predicts seizure type 
- impact on work, driving, etc.
- No role for seizure prophylaxis
	- do no start AED in patients without seizures
- seizure etiology
	- local irritation theroy
		- temporal, frontal lobes
	- BBB disruption theory
	- dysregulation of glutamate homeostasis therapy
	- IDH1 mutant and 2HG theory
- Antiseizure medications
	- general recommendation: monotherapy, lowest dose possible
	- keppra most common
		- binds synaptic vesicle protein SV2A
		- adverse effects: fatigue, irritability, mood changes
	- lacosamide: Na channel blocker
	- lamotrigine: Na channel blocker
		- rare adverse effect: SJS

Headaches

- presenting symptom in 1/3 patients 
- develops in 40-70% during disease course
- majority intermittent and non-specific
- causes of headaches
	- increased ICP
	- quick reduction in corticosteroid doses or withdrawal
	- ondansetron can cause headaches
	- ICH
	- trigeminal nerve related pain
	- PRES
- management
	- assess temporal relationship with dex taper
	- investigate with CTH if new onset 
	- headache specialist if underlying headache disorder

Cerebral edema and dexamethasone

- brain-tumor releated edema
	- due to invasion of underlying brain tumor and compromise of blood brain barrier
- dosing: try daily or q12h to limit dosing
	- similar bioavailability PO vs. IV
- hydrocortisone bridge if severe withdrawal
	- 20 mg a.m., 10 mg p.m. (around 3 pm)
- other complciations fo dexamethasone
	- peptic ulcers
	- bowel perforation
	- encephalopathy

Falls

- 30% of BrM patients > 65y will fall 
- etiology
	- age
	- comorbitidies
	- medications
	- disinhibition
	- spatial dysfunction
	- syncope
	- seizure

VTE

- duplex doppler
- management: DOAC
	- get non-con CTH prior to starting DOAC

#### Palliative care 

"muultidisciplinary approach to pursuit of QOL"

- improves QOL and reduces suffering

palliative care vs. hospice

- palliative care can be concurrent to curative treatment
	- focuses on needs, not prognosis
- hospice is end of life
	- prognosis < 6 months
	- does no allow for concurrent treatment
# Clinical paradigms and challenges in surface guided radiation therapy: Where do we go from here?

## Important Acronyms
* SGRT- Surface Guided Radiation Therapy
* RTT- Radiation Therapy Technologists
* QMP- Qualified Medical Physicist
* CBCT- cone-beam CT
* FOV- Field of View
* IGRT- Image Guided Radiotherapy
* QA- Quality Assurance
* ART- Adapted Radiotherapy
* SBRT- Stereotactic Body Radiation Therapy
## Evolving mutidisciplinary roles
As SGRT is new to the radiation therapy system, the clinical team needs specific training to move from original 3 point view system to SGRT system.
The qualified medical physicist(QMP) is responsible to instruct users such as RTT.

Because the SGRT data results don't always match with 3 point positioning, some RTTs might choose to ignore the information from the new SGRT system. To overcome this problem, patience and communication among the team members are needed.

## Dualities
### patient positioning(3-point vs. SGRT)
SGRT
1. doesn't require tattoos which are needed for 3-point localization. 
2. provides 3D visualization of the patient's posture and topographical information
3. can rotate, which allows the patients' position to be corrected prior to verification imaging or treatment

2D x-ray imaging
1. corrections carried out predominantly along planes perpendicular to the imaging direction without indicators of any potential rotations and deformations in the patient setup

SGRT is useful in positioning breast cancer b/c: 
1. the surface is an adequate surrogate for the target volume in the case of whole breast
2. extended FOV of SGRT enables correction of the patient's arm position

However, treatment volume using SGRT isn't very useful for abdomen and pelvis b/c surface doesn't always correlate well with the internal
treatment volume in the abdomen and pelvis. It's better to combine SGRT and IGRT in this case.

### IGRT vs. SGRT/IGRT
IGRT- encompasses any imaging technique that's used for anatomical or functional localization and response assessment in the treatment room.
Most widely used IGRT technique is CBCT but non-ionizing imaging modalities such as transabdominal 3D ultra-sound imaging and MRI are also used for
IGRT. These provide additional benefits due to their real-time imaging capabilities and superior soft tissue contrast particulary in the case of MRI.

SGRT is the only modality that combines both: 
* imaging without dose 
* real-time feedback
* sub-millimeter spatial resolution in 3D
* largest FOV available in radiotherapy.

These caracteristics enable SGRT to verify:
* immobilization accuracy
* correct patient's posture
* track the respiratory state
* provide intra-fraction monitoring(used to augment 3D volumetric imaging workflows)
  * SGRT can monitor intra fraction motion during the time interval required for the physician to evaluate 3D IGRT
  * SGRT can be used to monitor the correlation between chest and abdominal breathign during lung SBRT to detect baseline drifts

### Standardization vs Individualization of Workflows
SGRT promotes: the reduction of inter-operator variabiity, mitigates users' subjectivity, and compels a rigid/specific workflow which reduce treatment time and repeat 
imaging

SGRT quantifies: variations in individual patients due to natural differences(body size, body shape), physiological processes(breast seroma shrinkage,weight loss)

SGRT response varies due difference in sex and body mass indices, breast implants, mastectomy.

SGRT provides the opportunity to reproduce the patient's external surface over the entire body habitus from the CT simulation at each treatment session in the most reproducible way thanks to large FOV, which enables the characterization of overall posture and identification of any misalignment of the limbs or the head position that are not captured by 3D volumetric imaging.

Decision support tool for SGRT doesn't exist yet. 

### Patient safety vs. a new source of risk
Examples of SGRT failure events:
* inconsistency between the patient or plan-name between the Oncology information System and SGRT database
* mismatch between the SGRT or kV/MV/radiation isocenters
* improper reference surface
* inappropriate baseline
* incorrect system configuration

The use of SGRT as a decision support tool may result in higher risk because it it impacts patient's entire treatment course compared to when 
it is used for patient positioning and verified by kV imaging

How SGRT provides additional safety measure
* provide real time feedback of patient position and monitoring during the entire treatment
* provides additional information which improves workflows and provides safety benefits(ie. patient identification, collision avoidance, cross-check of immobilization devices and bolus position)

SGRT can be a powerful risk mitigation with the following measures:
* reduce human errors and subjective decisions by automating the patient positioning/immobilization process
* increasing the detection rate of failture events as it can serve as an "independent observer" in the treatment room
* compelling workflow standardization
### Big data vs. too much data
Even with SGRT's ability to acquire image of 3D surfaces in real time, most clinical systems only use the quantitative output of 6 degrees of freedom translational/rotational shift to simplify the interpretation for the end user(i.e., RTT) which mimics the output of x-ray IGRT systems.The problem with this is that many valuable information is discarded by this process.

Because SGRT focuses on the patiet's surface while x-ray imaging focuses on internal anatomy, combining these complementary modes of information could reduce the discrepancy between the two modalities

## Harnessing the synergy between research and clinical practice

### Potential new SGRT applications
* markerless tracking for 4D image reconstruction
* Biometric patient identification
* Immobilization device identification
* In-room scene mapping
  * SGRT can can the entire treatment room, which can avoid collisions between treatment units in real time
  * SGRT can provide missing data from CT as SGRT has larger FOV
  * SGRT can scan the entire body of patient. This continous contour measurement gives us more accurate and reproducible dose calculations

* Augmented reality
   * Creates virtual objects to provide additional perceptual information,
   * intersection between the treatment beam and reference patient surface could be calculated and virtually projected
   * internal informationsuch as the contours of target volume or critical structures could be projected
* Adapted radiotherapy(ART)
  * SGRT can re-contour, re-optimize, re-evaluate and check quality without additional imaging dose due to additional degrees of freedom compared to other systems
### Decision support
SGRT can be used to:
* calculate population-based margins for anatomical sites in which the surface is an adequate surrogate for the target(i.e., breast or brain)
* calculate margines necessary to account for respiratory related motion and unexpected changes throughout the couse of treatment
As SGRT benefits for predicting anatomical changes affecting the surface, it's more promising for tumors close to the surface such as breast cancer and lymphoma

SGRT data can also be used to identify outliers in the patient's respiration pattern and to guide the 4DCT process. For breath-hold treatments, current SGRT systems quantify the amplitude and 3D surface position.

### Requirements to move forward
* Vendors and users should actively create data repositories to share information and data of patients' 3D surfaces

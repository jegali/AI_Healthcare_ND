# FDA  Submission

**Your Name:** Jens Gaulke

**Name of your Device:** PneumoNET

## Algorithm Description 

### 1. General Information

**Intended Use Statement:** PneumoNET will assist radiologists to classify a given chest x-ray for presence or absence of pneunomia by examining the x-ray image.

**Indications for Use:** PneumoNET is indicated for use in screening pneunomia in males and females of ages 1-95 years having one or more combinations ofthe following diseases: atelectasis, cardiomegaly, standardization, edema, effusion, emphysema, fibrosis, hernia, infiltration, mass, nodule, **pneunomia**, pneumothorax. Images must be of type x-ray and body part must be CHEST. The modality must be equal to "DX" and the position has to be "PA" or "AP"

**Device Limitations:** 
- The algorithm works best with an GPU and it is therefore not suitable in an emergency setting with low end hardware.

**Clinical Impact of Performance:**

### 2. Algorithm Design and Function

<< Insert Algorithm Flowchart >>

**DICOM Checking Steps:**

**Preprocessing Steps:**

**CNN Architecture:**


### 3. Algorithm Training

**Parameters:**
* Types of augmentation used during training
* Batch size
* Optimizer learning rate
* Layers of pre-existing architecture that were frozen
* Layers of pre-existing architecture that were fine-tuned
* Layers added to pre-existing architecture

<< Insert algorithm training performance visualization >> 

<< Insert P-R curve >>

**Final Threshold and Explanation:**

### 4. Databases
 (For the below, include visualizations as they are useful and relevant)

**Description of Training Dataset:** 


**Description of Validation Dataset:** 


### 5. Ground Truth



### 6. FDA Validation Plan

**Patient Population Description for FDA Validation Dataset:** Patients, male and female, in age-range of 1-95 years. The dataset includes 20% pneunomia cases and 80% non-pneunomia cases. It includes multiple follow-up records for a given patient. The total number of records in the validation set is 1430.

**Ground Truth Acquisition Methodology:**

**Algorithm Performance Standard:**

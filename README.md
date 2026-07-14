# 📊 Access to the OpenUrine Dataset

The **OpenUrine Dataset** is a comprehensive collection of urinary sediment microscopy images designed for automated detection and classification using deep learning techniques. This is the first publicly available dataset dedicated to urinary particle detection.

## Dataset Composition

The OpenUrine dataset comprises **6,430 high-resolution microscopic images** from multiple clinical laboratories:

- **790 labeled images** with expert annotations containing **31,285 bounding boxes** across **39 distinct particle categories**
- **5,640 unlabeled images** for self-supervised learning applications

### Particle Categories Include:

**Cells:** RBC, WBC, Epithelial cells (Squamous, Transitional, Renal), WBC Clumps, RBC Clumps, Lipid Casts

**Casts:** Hyaline, Granular, Waxy, Cellular (RBC, WBC), Broad, Fatty

**Crystals:** Calcium Oxalate, Triple Phosphate, Uric Acid, Amorphous, Cystine, Tyrosine, Leucine, Cholesterol, Bilirubin, and more

**Microorganisms:** Bacteria, Yeast, Fungal Hyphae, Parasites (*Trichomonas vaginalis*, *Schistosoma haematobium*, *Enterobius vermicularis*)

**Others:** Sperm, Mucus, Fat Droplets, Oval Fat Bodies

**Artifacts:** Foreign substances and imaging errors

This dataset supports the development and validation of deep learning models for comprehensive automated urinalysis, as described in the study:

**"A Multi-Head YOLOv12 with Self-Supervised Pretraining for Urinary Sediment Particle Detection"**

---

## 📥 How to Access

To request access to the OpenUrine dataset, please complete the following form:

**🔗 [Access Request Form via Google Forms](https://forms.gle/JKgV63B6hdr5XjD29)**

---

## 🔬 Dataset Features

- **High clinical diversity:** Images collected from multiple laboratories using various microscope models and smartphone cameras
- **Expert validation:** All annotations performed independently by two experienced clinical biochemistry experts
- **Comprehensive coverage:** 39 particle categories representing the full spectrum of clinical urinalysis
- **Patient-level partitioning:** Ensures realistic model evaluation and prevents data leakage
- **Ethical compliance:** Approved by the Ethics Committee of Shahid Beheshti University of Medical Sciences (Approval Code: IR.SBMU.MSP.REC.1403.318)

---

## 🏥 Ethical Considerations

This study was reviewed and approved by the Ethics Committee of Shahid Beheshti University of Medical Sciences (approval code: **IR.SBMU.MSP.REC.1403.318**). All participants provided written informed consent prior to participation. No patient metadata was collected; all samples are fully anonymized and referenced only by randomly assigned identification codes.

---

## 📊 Dataset Statistics

| Dataset Component | Images | Bounding Boxes |
|------------------|--------|----------------|
| Labeled Data     | 790    | 31,285         |
| Unlabeled Data   | 5,640  | ---            |
| **Total**        | **6,430** | **31,285**  |

---


## 📜 Usage Policy

By submitting the access request form, you agree to:

✅ Use the dataset **solely for academic and non-commercial research purposes**

✅ Properly **cite the related publication** in any resulting research outputs

✅ **Not redistribute** the dataset to third parties without explicit permission

✅ Comply with all **ethical standards and regulations** regarding medical data usage

✅ Acknowledge that all samples are **fully anonymized** with no patient-identifying information

---

## 📧 Official Contact

For questions, technical support, or collaboration inquiries, please contact:

**Ali Karimi**  
Email: aliiikarimi@ut.ac.ir  
School of Electrical and Computer Engineering  
University of Tehran, Tehran, Iran

**Corresponding Authors:**
- **Dr. Majid Sirati-Sabet:** sirati@sbmu.ac.ir (Department of Clinical Biochemistry, Shahid Beheshti University of Medical Sciences)
- **Dr. Mohammad Ali Akhaee:** akhaee@ut.ac.ir (School of Electrical and Computer Engineering, University of Tehran)

---

## 💻 Code & Resources

Sample codes, experimental results, and pre-trained models are available in this repository:

**🔗 [https://github.com/alikarimi120/OpenUrine](https://github.com/alikarimi120/OpenUrine)**

---

## 📖 Citation

If you use the OpenUrine dataset in your research, please cite:
```bibtex
@article{alizadeh2025multi,
  title={A multi-head YOLOv12 with self-supervised pretraining for urinary sediment particle detection},
  author={Alizadeh, Mehdi and Karimi, Ali and Barikbin, Mohammad Javad and Movahed, Ali and Akbarzadeh, Samad and Sirati-Sabet, Majid and Akhaee, Mohammad Ali},
  journal={Scientific Reports},
  volume={15},
  number={1},
  pages={41347},
  year={2025},
  publisher={Nature Publishing Group UK London}
}
```

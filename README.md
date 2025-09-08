# ODES: Online Domain Adaptation with Expert Guidance for Medical Image Segmentation 

Code for **ODES**, accepted in MICCAI 2025 (Medical Image Computing and Computer-Assisted Intervention), Daejeon, South Korea. (under construction)

ODES is a novel framework for **online domain adaptation** in medical image segmentation that combines active learning, image pruning, and diversity-guided annotation to adapt pre-trained models to distribution shifts in real-time.

## ✨ Key Contributions

- **First AL-based online UDA framework** for medical image segmentation.
- Novel **image pruning** strategy based on batch norm divergence to select informative images.
- A **diversity-aware acquisition** function using spatial and feature-wise distances to enhance annotation utility.
- Online, source-free, and storage-free adaptation: data is processed **once per batch**.



### Dependencies

- Python 3.8+
- PyTorch >= 1.10
- OpenCV, NumPy, SciPy, scikit-learn


### Run Demo

```bash
python demo_ODES.py --cfg cfgs/example_config.yaml
```

Edit your YAML config to match your dataset path and parameters.



## 🧪 Citation

If you find this work useful, please cite:

```
@inproceedings{islam2025odes,
  title={ODES: Domain Adaptation with Expert Guidance for Online Medical Image Segmentation},
  author={Md Shazid Islam and Sayak Nag and Arindam Dutta and Sk Miraj Ahmed and Fahim Faisal Niloy and Shreyangshu Bera and Amit K. Roy-Chowdhury},
  booktitle={MICCAI},
  year={2025}
}
```


## 📬 Contact

For questions or collaborations:  
[misla048@ucr.edu](mailto:misla048@ucr.edu)

## Academic Software License: 
© 2025 UCR (“Institution”). Academic or nonprofit researchers
are permitted to use this Software (as defined below) subject to Paragraphs 1-4:
1. Institution hereby grants to you free of charge, so long as you are an academic or
nonprofit researcher, a nonexclusive license under Institution’s copyright ownership
interest in this software and any derivative works made by you thereof (collectively, the
“Software”) to use, copy, and make derivative works of the Software solely for
educational or academic research purposes, and to distribute such Software free of charge
to other academic or nonprofit researchers for their educational or academic research
purposes, in all cases subject to the terms of this Academic Software License. Except as
granted herein, all rights are reserved by Institution, including the right to pursue patent
protection of the Software.
2. Any distribution of copies of this Software -- including any derivative works made by
you thereof -- must include a copy (including the copyright notice above), and be made
subject to the terms, of this Academic Software License; failure by you to adhere to the
requirements in Paragraphs 1 and 2 will result in immediate termination of the license
granted to you pursuant to this Academic Software License effective as of the date you
first used the Software.
3. IN NO EVENT WILL INSTITUTION BE LIABLE TO ANY ENTITY OR PERSON
FOR DIRECT, INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL
DAMAGES, INCLUDING LOST PROFITS, ARISING OUT OF THE USE OF THIS
SOFTWARE, EVEN IF INSTITUTION HAS BEEN ADVISED OF THE POSSIBILITY
OF SUCH DAMAGE. INSTITUTION SPECIFICALLY DISCLAIMS ANY AND ALL
WARRANTIES, EXPRESS AND IMPLIED, INCLUDING, BUT NOT LIMITED TO,
ANY IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A
PARTICULAR PURPOSE. THE SOFTWARE IS PROVIDED “AS IS.” INSTITUTION
HAS NO OBLIGATION TO PROVIDE MAINTENANCE, SUPPORT, UPDATES,
ENHANCEMENTS, OR MODIFICATIONS OF THIS SOFTWARE.
4. Any academic or scholarly publication arising from the use of this Software or any
derivative works thereof will include the following acknowledgment:  The Software
used in this research was created by Amit Roy-Chowdhury and members of the
Vision and Learning Group at UCR. © 2025 UCR.
Commercial entities: please contact amitrc@ucr.edu or otc@ucr.edu for licensing
opportunities.

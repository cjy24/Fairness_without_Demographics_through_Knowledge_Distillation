# Fairness_without_Demographics_through_Knowledge_Distillation
  
Most of existing work on fairness assumes available demographic information in the training set. In practice, due to legal or privacy concerns, when demographic information is not available in the training set, it is crucial to find alternative objectives to ensure fairness. Existing work on fairness without demographics follows Rawlsian Max-Min fairness objectives. However, such constraints could be too strict to improve group fairness, and could lead to a great decrease in accuracy. In light of these limitations, in this paper, we propose to solve the problem from a new perspective, ie, through knowledge distillation. Our method uses soft label from an overfitted teacher model as an alternative, and we show from preliminary experiments that soft labelling is beneficial for improving fairness. We analyze theoretically the fairness of our method, and we show that our method can be treated as an error-based reweighing. Experimental results on three datasets show that our method outperforms state-of-the-art alternatives, with notable improvements in group fairness and with relatively small decrease in accuracy. Paper available at: https://proceedings.neurips.cc/paper_files/paper/2022/file/79dc391a2c1067e9ac2b764e31a60377-Paper-Conference.pdf

# Configuration

Please install all necessary packages via: pip install -r requirements.txt

# Usage

To run the experiments, please revise the file directory accordingly.

# Citation
@article{chai2022fairness,
  title={Fairness without demographics through knowledge distillation},
  author={Chai, Junyi and Jang, Taeuk and Wang, Xiaoqian},
  journal={Advances in Neural Information Processing Systems},
  volume={35},
  pages={19152--19164},
  year={2022}
}

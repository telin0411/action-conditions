# Learning Action Conditions from Instructional Manuals for Instruction Understanding

(Under construction.)

This repository releases the curated dataset for `action-and-condition dependencies` from some popular online instructional manuals. For more details, please check out our [ACL 2023 paper](https://arxiv.org/pdf/2205.12420).

# What This Work Is About

The ability to infer pre- and postconditions of an action is vital for comprehending complex instructions, and is essential for applications such as autonomous instruction-guided agents and assistive AI that supports humans to perform physical tasks. In this work, we propose a task dubbed action condition inference, which extracts mentions of preconditions and postconditions of actions in instructional manuals. We propose a weakly supervised approach utilizing automatically constructed large-scale training instances from online instructions, and curate a densely human-annotated and validated dataset to study how well the current NLP models do on the proposed task. We design two types of models differ by whether contextualized and global information is leveraged, as well as various combinations of heuristics to construct the weak supervisions.Our experiments show a > 20% F1-score improvement with considering the entire instruction contexts and a > 6% F1-score benefit with the proposed heuristics. However, the best performing model is still well-behind human performance.

# Download The Dataset

Please download the curated resource from
[this google drive link](https://drive.google.com/drive/folders/1ubPddqMON6JNCXaXRn9-V4fYka483ZKR?usp=sharing), which encompasses the main training and testing data from our main paper.

# Check Out The Data

`TODO`

## Citation

If you find our curated resource useful, please cite our paper using:
```
@inproceedings{wu2023action,
  title = {Learning Action Conditions from Instructional Manuals for Instruction Understanding},
  author = {Wu, Te-Lin and Zhang, Caiqi and Hu, Qingyuan and Spangher, Alex and Peng, Nanyun},
  booktitle = {Proceedings of the Conference of the 61st Annual Meeting of the Association for Computational Linguistics (ACL)},
  year = {2023}
}
```

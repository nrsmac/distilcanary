# DistilCanary

A smaller version of Canary using knowledge distillation trained on prosocialdialog dataset.

`finetune.ipynb` is a notebook with the training loop:
  * should be run more to 

Original canary can be found here
https://github.com/skywalker023/prosocial-dialog

Distillation techniques from HuggingFace:
@inproceedings{sanh2019distilbert,
  title={DistilBERT, a distilled version of BERT: smaller, faster, cheaper and lighter},
  author={Sanh, Victor and Debut, Lysandre and Chaumond, Julien and Wolf, Thomas},
  booktitle={NeurIPS EMC^2 Workshop},
  year={2019}
}

Further directions:
* Reinforcement learning with human feedback
  https://doi.org/10.48550/arXiv.2111.08596
* Creating a direct distilation of Canary itself 

# [ICANN 2024] MISS: A Generative Pre-training and Fine-tuning Approach for Med-VQA
# Abstract
Medical visual question answering (VQA) is a challenging multimodal task, where Vision-Language Pre-trained (VLP) models can effectively improve the generalization performance. However, most current methods in the medical field treat VQA as an answer classification task which is difficult to transfer to practical application scenarios. Additionally, due to the privacy of medical images and the expensive annotation process, large-scale medical image-text pairs datasets for pretraining are severely lacking. In this paper, we propose an efficient MultI-task Self-Supervised-learning-based framework (MISS) for medical VQA tasks. Unlike existing methods, we treat medical VQA as a generative task. We unify the text encoder and multimodal encoder and align image-text features through multi-task learning. Furthermore, we propose a Transfer-and-Caption (TransCap) method that extends the feature space of single-modal image datasets using Large Language Models (LLMs), enabling those traditional medical vision-field task data to be applied to VLP models. We conduct extensive experiments and compare them with existing medical VQA methods adopting a no-generative paradigm. We demonstrate the advantages of pre-training with data generated by the TransCap method and our method achieves excellent results with fewer multimodal datasets.
![image](https://github.com/TIMMY-CHAN/MISS/assets/125014501/8d396e43-a55e-4f57-ba04-06a7720a0b61)
This is the PyTorch code of the <a href="https://arxiv.org/abs/2401.05163"> paper</a>. To install the dependencies, run: <pre/> pip install -r requirements.txt</pre> 

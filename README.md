# My Version Texygen

My goal is to make the Texygen models more generalizable for my research.  I will update as this goal is achieved.

## About TexyGen
Texygen is a benchmarking platform to support research on open-domain text generation models. Texygen has not only implemented a majority of text generation models, but also covered a set of metrics that evaluate the diversity, the quality and the consistency of the generated texts. The Texygen platform could help standardize the research on text generation and facilitate the sharing of fine-tuned open-source implementations among researchers for their work.  As a consequence, this would help in improving the reproductivity and reliability of future research work in text generation.

For more details, please refer to Texygen's SIGIR 2018 paper: [Texygen: A Benchmarking Platform for Text Generation Models](https://arxiv.org/abs/1802.01886) by Yaoming Zhu et al.

Should you have any questions and enquiries, please feel free to contact Yaoming Zhu (ym-zhu [AT] outlook.com) and [Weinan Zhang](http://wnzhang.net) (wnzhang [AT] sjtu.edu.cn).

## Requirement
Texygen suggests you run the platform under Python 3.6+ with following libs:
* **TensorFlow >= 1.5.0**
* Numpy 1.12.1
* Scipy 0.19.0
* NLTK 3.2.3
* CUDA 7.5+ (Suggested for GPU speed up, not compulsory)    

Or just type `pip install -r requirements.txt` in your terminal.

## Implemented Models and Original Papers

* **SeqGAN** -  [SeqGAN: Sequence Generative Adversarial Nets with Policy Gradient](https://arxiv.org/abs/1609.05473)

* **MaliGAN** - [Maximum-Likelihood Augmented Discrete Generative Adversarial Networks](https://arxiv.org/abs/1702.07983)

* **RankGAN** - [Adversarial ranking for language generation](http://papers.nips.cc/paper/6908-adversarial-ranking-for-language-generation)

* **LeakGAN** - [Long Text Generation via Adversarial Training with Leaked Information](https://arxiv.org/abs/1709.08624)

* **TextGAN** - [Adversarial Feature Matching for Text Generation](https://arxiv.org/abs/1706.03850)
 
* **GSGAN** - [GANS for Sequences of Discrete Elements with the Gumbel-softmax Distribution](https://arxiv.org/abs/1611.04051)

## Reference for Texygen
```bash
@article{zhu2018texygen,
  title={Texygen: A Benchmarking Platform for Text Generation Models},
  author={Zhu, Yaoming and Lu, Sidi and Zheng, Lei and Guo, Jiaxian and Zhang, Weinan and Wang, Jun and Yu, Yong},
  journal={SIGIR},
  year={2018}
}
```


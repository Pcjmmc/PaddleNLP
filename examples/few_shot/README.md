# Few-Shot Learning(FSL)
Few-Shot Learning 旨在研究如何从少量有监督的训练样本中学习出具有良好泛化性的模型，对训练数据很少或监督数据获取成本极高的应用场景有很大价值。

随着大规模预训练模型的不断涌现，FSL 结合预训练模型的先验知识和强大的泛化能力在下游任务效果上取得了显著提升，为大规模预训练模型结合 FSL 的工业落地应用带来了无限可能性。

我们旨在为 FSL 领域的研究者提供简单易用、全面、前沿的 FSL 策略库，便于研究者基于 FSL 策略库将注意力集中在算法创新上。我们会持续开源 FSL 领域的前沿学术工作，并在中文小样本学习测评基准 [FewCLUE](https://github.com/CLUEbenchmark/FewCLUE)  上给出常见预训练模型的 Benchmark。

## Benchmark
| 算法 | 预训练模型  | Score  | eprstmt  | bustm  | ocnli  | csldcp  | tnews  |  wsc | iflytek | csl | chid |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |------------ | ------------ | ---------- |
| P-tuning  | ERNIE1.0  | 53.67 | 77.54  | 59.14  | 35.43  | 59.75  | 57.31  | 51.54  | 50.31 | 53.59 | 38.46 |

## 策略库
- [P-tuning](./p-tuning)
- PET(Todo)
- EFL(Todo)

## 如何贡献

## References
[1]X. Liu et al., “GPT Understands, Too,” arXiv:2103.10385 [cs], Mar. 2021, Accessed: Mar. 22, 2021. [Online]. Available: http://arxiv.org/abs/2103.10385

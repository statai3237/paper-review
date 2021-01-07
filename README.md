# paper-review 

## RESERVOIR TRANSFORMER

If some layers of the transformer are kept frozen - i.e., never updated after random initialization can we match the performance of fully learned transformers, while being more efficient ?
Answer is yes, they find that freezing layers may actually improve performance.

![Screenshot from 2021-01-06 15-52-26](https://user-images.githubusercontent.com/55779293/103762010-f30e2000-505a-11eb-81d5-a973050b34d6.png)

You can check this paper for details. 

<https://arxiv.org/pdf/2012.15045.pdf>


## Unsupervised Question Decomposition for Question Answering

The authors aim to improve question answering (QA) by decomposing hard question into simpler sub-questions that existing QA systems are capable of answering.
Specifically, they propose an algorithm for One-to-N Unsupervised Sequence transduction (ONUS) that learns to map one hard, multi-hop question to many simpler, single-hop sub-question. They answer sub-questions with an off-the-shelf QA model and give the resulting answers to a recomposition model that combines them into a final answer.

You can check this paper for details. 
<https://arxiv.org/pdf/2002.09758.pdf>

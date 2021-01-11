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

![decomposition](https://user-images.githubusercontent.com/55779293/103869043-1ee9de00-510d-11eb-889f-5abe5f33418e.png)

You can check this paper for details. 
<https://arxiv.org/pdf/2002.09758.pdf>

## Ask2Transformers - Zero shot Domain Labelling with Pretrained Transformers

In this paper, they present a system that exploits different pre-trained LMs for assigning domain labels to WordNet synsets without any kind of supervision.
Furthermore, the system is not restricted to use a particular set of domain labels.
They exploit the knowledge encoded within different off-the-shelf pre-trained LMs and task formulations to infer the domain label of a particular WordNet definition. The proposed zero-shot system achieves a new state-of-the-art on the English dataset used in the evaluation.

paper :
<https://arxiv.org/pdf/2101.02661.pdf>
code :
<https://github.com/osainz59/Ask2Transformers>

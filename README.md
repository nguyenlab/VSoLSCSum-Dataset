# VSoLSCSum-Dataset
The Vietnamese dataset for social context summarization

The dataset contains 141 open-domain articles along with 3,760 sentences, 2,448 extracted standard sentences and comments as standard summaries and 6,926 comments in 12 events. This dataset was manually annotated by human. Note that the extracted standard summaries also include comments.

The label of a sentence or comment was generated based on the voting among social annotators. For example, given a sentence, each annotator makes a binary decision in order to indicate that whether this sentence is a summary candidate (YES) or not (NO). If three annotators agree yes, this sentences is labeled by 3. Therefore, the label of each sentence or comment ranges from 1 to 5 (1: very poor, 2: poor, 3: fair, 4: good; 5: perfect). The standard summary sentences are those which receive at least three agreements from annotators. The inter-agreement calculated by Cohen's Kappa after validation among annotators is 0.685.


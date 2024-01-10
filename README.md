## AugSumm Summaries

This repository contains the augmented summaries of How2-2000 dataset.
We declare that the summaries have been generated using OpenAI's ChatGPT3.5Turbo model.

### Disclaimer: ChatGPT Generated Content

This repository contains content generated by ChatGPT, a language model developed by OpenAI. 

#### Responsibility and Usage:

Users are responsible for reviewing and validating the generated content before using it for any purpose.
The creators and maintainers of this repository are not liable for any inaccuracies, errors, or consequences arising from the use of ChatGPT-generated content.

### AugSumm summaries
Generated summaries used in our experiments are located as below.
`direct` corresponds to `direct AugSumm` in the paper.
`paraphrase` corresponds to `paraphrase AugSumm` in the paper using concept words. 

```
./
`-- augsumm
    |-- direct
    |   |-- dev5_test_summaries
    |   `-- tr_2000h_summaries
    `-- paraphrase
        |-- dev5_test_summaries
        `-- tr_2000h_summaries
```

### Training and evaluation

All training has been done using ESPnet-SUMM.
Please refer to ESPnet and ESPnet-SUMM.
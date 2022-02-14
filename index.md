## Speaker-aware Mixture of Mixtures Training for Weakly Supervised Speaker Extraction

### Introduction
    hello world

### Demo 1: Performance on Libri2Mix[<sup>1</sup>](#ref)

* **Sample 1**
    * **Mixture: Female VS Male**
    * /home/jiangji/basic/dataset/librimix/Libri2Mix/wav8k/min/test/mix_clean -> /home/jiangji/basic/codebase/samom-demo/exp1_mix
    <audio src="exp1_mix/7021-79740-0012_1580-141084-0004.wav" controls="controls">
    ERROR !!! Cannot Play Audio !!!
    </audio>

    * **Baseline: Fully Supervised Training on Libri2Mix** (sup_med_1126)
    * /home/jiangji/basic/exp-samom/sup_med_1126/eval/wav_est -> /home/jiangji/basic/codebase/samom-demo/exp1_sup
    <audio src="exp1_sup/7021-79740-0012_1580-141084-0004_s1.wav" controls="controls">
    ERROR !!! Cannot Play Audio !!!
    </audio>
    <audio src="exp1_sup/7021-79740-0012_1580-141084-0004_s0.wav" controls="controls">
    ERROR !!! Cannot Play Audio !!!
    </audio>

    * **SAMoM: Weakly Supervised SAMoM Training on Libri2Mix** (smt-adapt_smt-pre_1128)
    * /home/jiangji/basic/exp-samom/smt-adapt_smt-pre_1128 -> /home/jiangji/basic/codebase/samom-demo/exp1_samom
    <audio src="exp1_samom/7021-79740-0012_1580-141084-0004_s1.wav" controls="controls">
    ERROR !!! Cannot Play Audio !!!
    </audio>
    <audio src="exp1_samom/7021-79740-0012_1580-141084-0004_s0.wav" controls="controls">
    ERROR !!! Cannot Play Audio !!!
    </audio>

* **Sample 2**
    * **Mixture: Male VS Male**
    * /home/jiangji/basic/dataset/librimix/Libri2Mix/wav8k/min/test/mix_clean -> /home/jiangji/basic/codebase/samom-demo/exp1_mix
    <audio src="exp1_mix/7021-79740-0012_8455-210777-0020.wav" controls="controls">
    ERROR !!! Cannot Play Audio !!!
    </audio>

    * **Baseline: Fully Supervised Training** (sup_med_1126)
    * /home/jiangji/basic/exp-samom/sup_med_1126/eval/wav_est -> /home/jiangji/basic/codebase/samom-demo/exp1_sup
    <audio src="exp1_sup/7021-79740-0012_8455-210777-0020_s0.wav" controls="controls">
    ERROR !!! Cannot Play Audio !!!
    </audio>
    <audio src="exp1_sup/7021-79740-0012_8455-210777-0020_s1.wav" controls="controls">
    ERROR !!! Cannot Play Audio !!!
    </audio>

    * **SAMoM: Weakly Supervised SAMoM Training** (smt-adapt_smt-pre_1128)
    * /home/jiangji/basic/exp-samom/smt-adapt_smt-pre_1128 -> /home/jiangji/basic/codebase/samom-demo/exp1_samom
    <audio src="exp1_samom/7021-79740-0012_8455-210777-0020_s0.wav" controls="controls">
    ERROR !!! Cannot Play Audio !!!
    </audio>
    <audio src="exp1_samom/7021-79740-0012_8455-210777-0020_s1.wav" controls="controls">
    ERROR !!! Cannot Play Audio !!!
    </audio>

* Sample 3
    * **Mixture: Female VS Female**
    * /home/jiangji/basic/dataset/librimix/Libri2Mix/wav8k/min/test/mix_clean -> /home/jiangji/basic/codebase/samom-demo/exp1_mix
    <audio src="exp1_mix/3575-170457-0011_2961-960-0020.wav" controls="controls">
    ERROR !!! Cannot Play Audio !!!
    </audio>

    * **Baseline: Fully Supervised Training** (sup_med_1126) 
    * /home/jiangji/basic/exp-samom/sup_med_1126/eval/wav_est -> /home/jiangji/basic/codebase/samom-demo/exp1_sup
    <audio src="exp1_sup/3575-170457-0011_2961-960-0020_s0.wav" controls="controls">
    ERROR !!! Cannot Play Audio !!!
    </audio>
    <audio src="exp1_sup/3575-170457-0011_2961-960-0020_s1.wav" controls="controls">
    ERROR !!! Cannot Play Audio !!!
    </audio>

    * **SAMoM: Weakly Supervised SAMoM Training** (smt-adapt_smt-pre_1128) 
    * /home/jiangji/basic/exp-samom/smt-adapt_smt-pre_1128/eva/wav_est -> /home/jiangji/basic/codebase/samom-demo/exp1_samom
    <audio src="exp1_samom/3575-170457-0011_2961-960-0020_s0.wav" controls="controls">
    ERROR !!! Cannot Play Audio !!!
    </audio>
    <audio src="exp1_samom/3575-170457-0011_2961-960-0020_s1.wav" controls="controls">
    ERROR !!! Cannot Play Audio !!!
    </audio>

<div id="ref"></div>
### References

[1] J. Cosentino, M. Pariente, S. Cornell, A. Deleforge, and E. Vin- cent, “Librimix: An open-source dataset for generalizable speech separation,” arXiv preprint arXiv:2005.11262, 2020.

criterion: smt-adapt_smt-pre_1128 >= (15, 15)

* sample 1 (M-M) 19-15
    /home/zzf/experiment-samom/smt-adapt_smt-pre_1128/eval/wav_est/7021-79740-0012_8455-210777-0020_s0.wav
    /home/zzf/experiment-samom/smt-adapt_smt-pre_1128/eval/wav_est/7021-79740-0012_8455-210777-0020_s1.wav
* sample 2 (F-F) 15-16
    /home/zzf/experiment-samom/smt-adapt_smt-pre_1128/eval/wav_est/3575-170457-0011_2961-960-0020_s0.wav
    /home/zzf/experiment-samom/smt-adapt_smt-pre_1128/eval/wav_est/3575-170457-0011_2961-960-0020_s1.wav
* sample 3 (M-F) 15-15
    /home/zzf/experiment-samom/smt-adapt_smt-pre_1128/eval/wav_est/7021-79740-0012_1580-141084-0004_s0.wav
    /home/zzf/experiment-samom/smt-adapt_smt-pre_1128/eval/wav_est/7021-79740-0012_1580-141084-0004_s1.wav

### exp2: baseline / proposed

Baseline: (sup-pre_1208-eval)
    ...
SAMoM: (smt-domain_smt-pre_1212/eval1227)
x 3

### sep-noisy

Baseline: (sup-noisy_med_0111)
    ...
SAMoM: (nmt-singlearm-clean_med_0107）
    ...
x 3

###

Baseline: Fully Supervised Speaker Extraction

Proposed: Weakly Supervised SAMoM Training
<audio src="wav_samom/s0.mp3" controls="controls">
ERROR !!! Cannot Play Audio !!!
</audio>

https://github.com/ZhaZhaFon/samom-demo/blob/gh-pages/wav_samom/61-70968-0000_8455-210777-0012_s0.wav

You can use the [editor on GitHub](https://github.com/ZhaZhaFon/samom-demo/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ZhaZhaFon/samom-demo/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

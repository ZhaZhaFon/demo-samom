## Speaker-aware Mixture of Mixtures Training for Weakly Supervised Speaker Extraction

### Introduction
    hello world

### Demo 1: Performance on Libri2Mix<sup>[2]</sup>

* **Sample 1: ( Female + Male ) => Female**
    * **Mixture**
    <audio src="demo1_mix/2830-3979-0011_1580-141084-0010.wav" controls="controls">ERROR</audio>
    * **Baseline: Supervised Training**
    <audio src="demo1_sup/2830-3979-0011_1580-141084-0010_s1.wav" controls="controls">ERROR</audio>
    * **Ours: Weakly Supervised Training with SAMoM**
    <audio src="demo1_samom/2830-3979-0011_1580-141084-0010_s1.wav" controls="controls">ERROR</audio>

---

* **Sample 2: ( Female + Male ) => Male**
    * **Mixture**
     <audio src="demo1_mix/1320-122617-0035_121-121726-0009.wav" controls="controls">ERROR</audio>
    * **Baseline: Supervised Training**
    <audio src="demo1_sup/1320-122617-0035_121-121726-0009_s0.wav" controls="controls">ERROR</audio>
    * **Ours: Weakly Supervised Training with SAMoM**
    <audio src="demo1_samom/1320-122617-0035_121-121726-0009_s0.wav" controls="controls">ERROR</audio>

---

* **Sample 3: ( Male + Male ) => Male**
    * **Mixture**
     <audio src="demo1_mix/6930-75918-0007_1089-134691-0022.wav" controls="controls">ERROR</audio>
    * **Baseline: Supervised Training**
    <audio src="demo1_sup/6930-75918-0007_1089-134691-0022_s1.wav" controls="controls">ERROR</audio>
    * **Ours: Weakly Supervised Training with SAMoM**
    <audio src="demo1_samom/6930-75918-0007_1089-134691-0022_s1.wav" controls="controls">ERROR</audio>

---

* **Sample 4: ( Female + Female ) => Female**
    * **Mixture**
     <audio src="demo1_mix/1580-141083-0008_4507-16021-0029.wav" controls="controls">ERROR</audio>
    * **Baseline: Supervised Training**
    <audio src="demo1_sup/1580-141083-0008_4507-16021-0029_s1.wav" controls="controls">ERROR</audio>
    * **Ours: Weakly Supervised Training with SAMoM**
    <audio src="demo1_samom/1580-141083-0008_4507-16021-0029_s1.wav" controls="controls">ERROR</audio>

### Demo 2: Cross-domain Evaluation

* Comming Soon...

### Demo 3: Noisy Extension<sup>[3]</sup>

* **Sample 1: ( Female + Male + Noise ) => Female**
    * **Mixture**
    <audio src="demo3_mix/237-134500-0008_8455-210777-0040.wav" controls="controls">
    ERROR !!! Cannot Play Audio !!!
    </audio>

    * **Baseline: Fully Supervised Training**
    <audio src="demo3_sup/237-134500-0008_8455-210777-0040_s0.wav" controls="controls">
    ERROR !!! Cannot Play Audio !!!
    </audio>

    * **SAMoM: Weakly Supervised SAMoM Training**
    <audio src="demo3_samom/237-134500-0008_8455-210777-0040_s0.wav" controls="controls">
    ERROR !!! Cannot Play Audio !!!
    </audio>

---

* **Sample 2: ( Female + Male + Noise ) => Male**
    * **Mixture**
    <audio src="demo3_mix/7127-75947-0019_1089-134691-0018.wav" controls="controls">
    ERROR !!! Cannot Play Audio !!!
    </audio>

    * **Baseline: Fully Supervised Training**
    <audio src="demo3_sup/7127-75947-0019_1089-134691-0018_s0.wav" controls="controls">
    ERROR !!! Cannot Play Audio !!!
    </audio>

    * **SAMoM: Weakly Supervised SAMoM Training** 
    <audio src="demo3_samom/7127-75947-0019_1089-134691-0018_s0.wav" controls="controls">
    ERROR !!! Cannot Play Audio !!!
    </audio>

---

* **Sample 3: ( Male + Male + Noise ) => Male**
    * **Mixture**
    <audio src="demo3_mix/7021-79740-0012_8455-210777-0020.wav" controls="controls">
    ERROR !!! Cannot Play Audio !!!
    </audio>

    * **Baseline: Fully Supervised Training**
    <audio src="demo3_sup/7021-79740-0012_8455-210777-0020_s0.wav" controls="controls">
    ERROR !!! Cannot Play Audio !!!
    </audio>

    * **SAMoM: Weakly Supervised SAMoM Training** 
    <audio src="demo3_samom/7021-79740-0012_8455-210777-0020_s0.wav" controls="controls">
    ERROR !!! Cannot Play Audio !!!
    </audio>

---

* **Sample 4: ( Female + Female + Noise ) => Female**
    * **Mixture**
    <audio src="demo3_mix/2830-3979-0011_1580-141084-0010.wav" controls="controls">
    ERROR !!! Cannot Play Audio !!!
    </audio>

    * **Baseline: Fully Supervised Training**
    <audio src="demo3_sup/2830-3979-0011_1580-141084-0010_s1.wav" controls="controls">
    ERROR !!! Cannot Play Audio !!!
    </audio>

    * **SAMoM: Weakly Supervised SAMoM Training**
    <audio src="demo3_samom/2830-3979-0011_1580-141084-0010_s1.wav" controls="controls">
    ERROR !!! Cannot Play Audio !!!
    </audio>

### GitHub Pages

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

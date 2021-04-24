# One-Shot Affordance Detection
Affordance detection $\footnote{``Detection'' follows the term pixel-wise detection task, which has also been used in the area of salient object detection.}$ refers to identifying the potential action possibilities of objects in an image, which is an important ability for robot perception and manipulation. To empower robots with this ability in unseen scenarios, we consider the challenging one-shot affordance detection problem in this paper, i.e., given a support image that depicts the action purpose, all objects in a scene with the common affordance should be detected. To this end, we devise a One-Shot Affordance Detection (OS-AD) network that firstly estimates the purpose and then transfers it to help detect the common affordance from all candidate images. Through collaboration learning, OS-AD can capture the common characteristics between objects having the same underlying affordance and learn a good adaptation capability for perceiving unseen affordances. Besides, we build a Purpose-driven Affordance Dataset (PAD) by collecting and labeling 4K images from 31 affordance and 72 object categories. Experimental results demonstrate the superiority of our model over previous representative ones in terms of both objective metrics and visual quality. The code and dataset will be released.

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

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/lhc1224/lhc.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

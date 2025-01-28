
# Testing Homepage of NTU MARS Lab

Visit **[marslab.tech](http://marslab.tech)** 🚀

_Built with [Lab Website Template](https://greene-lab.gitbook.io/lab-website-template-docs)_

## Paper Adding
Please add your paper to the `_data/citations.yaml` file. The format is as follows:
```yaml
- id: #doi#
  title: #Title of the Paper#
  authors: 
  - #Author1#
  - #Author2#
  - #Author3#
  publisher: #Conference/Journal#
  date: #YYYY-MM-DD#
  link: #Paper URL#
  image: #Upload the cover image to images/papers/#
  buttons:
  - type: paper
    link: #Paper URL#
  - type: github
    text: Github
    link: #Github URL#
  - type: website
    text: Website
    link: #Website URL#
  tags:
  - #tag1#
  - #tag2#
  - #tag3#
  plugin: sources.py
  file: sources.yaml
```
Also, add your paper to the `_data/sources.yaml` file. The data should be aligned with which written in `_data/citations.yaml`. The format is as follows:
```yaml
- id: #doi#
  publisher: #Conference/Journal#
  date: #YYYY-MM-DD#
  image: #Upload the cover image to images/papers/#
  buttons:
  - type: paper
    link: #Paper URL#
  - type: github
    text: Github
    link: #Github URL#
  - type: website
    text: Website
    link: #Website URL#
  tags:
  - #tag1#
  - #tag2#
  - #tag3#
```



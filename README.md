
# Homepage of NTU MARS Lab

Visit **[morpheus-an.github.io/marslab.github.io.dev](https://morpheus-an.github.io/marslab.github.io.dev)** 🚀

_Built with [Lab Website Template](https://greene-lab.gitbook.io/lab-website-template-docs)_

<!--
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
-->

## Paper Adding
Please add your paper to the `_data/sources.yaml` file. The format is as follows:
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
For example:
```yaml
- id: arxiv:2305.10345
  type: paper
  publisher: NeurIPS 2023 Datasets and Benchmarks Track
  description: The world-first multi-modal non-intrusive 4D human dataset (RGB, Depth, LiDAR, mmWave, WiFi).
  date: 2023-05-11
  image: https://ntu-aiot-lab.github.io/static/images/setup.png
  buttons:
    - type: paper
      link: https://arxiv.org/pdf/2305.10345
    - type: github
      text: Github
      link: ybhbingo/MMFi_dataset
    - type: website
      text: Website
      link: https://ntu-aiot-lab.github.io/mm-fi
  tags:
    - multimodal dataset
    - 4D human sensing
    - human pose estimation
    - non-intrusive sensing
```
Additional information (e.g., `paper title` and `authors`) will be automatically generated in `_data/citations.yaml` based on the `id` and `paper link` provided in the `_data/source.yaml` file.
## Highlighted Paper
To add paper into `Highlighted` under `RESEARCH`, just add `group: highlighted` to the format:
```yaml
- id: #doi#
  publisher: #Conference/Journal#
  date: #YYYY-MM-DD#
  image: #Upload the cover image to images/papers/#
  group: highlighted
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
## Project Adding
To add paper to `Project`, please add your paper to the `_data/projects.yaml` file. The format is as follows:
```yaml
- title: #Paper Title#
  subtitle:  #Paper Subtitle#
  image: #Paper Teaser Image#
  link: #Paper Code Link#
  description: #Paper Brief Description#
  tags:
    - #Tag 1#
    - #Tag 2#
```
For example:
```yaml
- title: MM-Fi Dataset
  subtitle: Multimodal 4D Human Dataset
  image: images/gif/mm-fi-dataset.gif
  link: https://ntu-aiot-lab.github.io/mm-fi
  description: The world-first multi-modal non-intrusive 4D human dataset (RGB, Depth, LiDAR, mmWave, WiFi).
  tags:
    - dataset
    - human-sensing
```
## Featured Project
To add a project into `Featured` under `PROJECT`, just add `group: featured` to the format:
```yaml
- title: #Paper Title#
  subtitle:  #Paper Subtitle#
  image: #Paper Teaser Image#
  link: #Paper Code Link#
  description: #Paper Brief Description#
  group: featured
  tags:
    - #Tag 1#
    - #Tag 2#
```



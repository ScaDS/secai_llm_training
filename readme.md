# SECAI LLM Training

This repository contains a collection of Python Jupyter notebooks used in a training session with [SECAI](https://secai.org/) explaining LLMs and how to use them using the [ScaDS.AI LLM Services](https://llm.scads.ai/) (VPN required). The content is available at

https://scads.github.io/secai_llm_training

It is maintained using [Jupyter lab](https://jupyterlab.readthedocs.io/en/stable/) and build using [Jupyter book](https://jupyterbook.org/intro.html).

To edit this book, install depencencies like this:

```
pip install jupyterlab jupyter-book jupyterlab-spellchecker

git clone https://github.com/scads/generative-ai-notebooks
cd  generative-ai-notebooks
jupyter lab
```

To build the book, you can run this from the same folder:
```
cd docs
jupyter book build .
```

## Acknowledgements

We acknowledge the financial support by the Federal Ministry of Education and Research of Germany and by Sächsische Staatsministerium für Wissenschaft, Kultur und Tourismus in the programme Center of Excellence for AI-research „Center for Scalable Data Analytics and Artificial Intelligence Dresden/Leipzig“, project identification number: ScaDS.AI

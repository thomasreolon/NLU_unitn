# NLU UNITN

**student** Thomas Reolon
**student ID** 221247

---

## Assignment 2 (27/04/2021)

**data**: CoNLL 2003 dataset was used to test spacy's performances. The notebook downloads it on its own.

**code**: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1NMxRXwLViHGGofFFcz5Lu_DeGiAmWJwN?usp=sharing)

**report**: [reports/Assignment2.pdf](reports/Assignment2.pdf)

**execution**:

```
1.  open the notebook in google colab   --> https://colab.research.google.com/drive/1NMxRXwLViHGGofFFcz5Lu_DeGiAmWJwN
2.  check to be using GPU environment (for appendix B)
3.  run the notebook
```

---

## Assignment 1 (20/04/2021)

**data**: no custom dataset was used. Some sentences have been used in the 1st part to test the functions, while nltk_treebank dataset was used for the second one.

**code**: notebook available at [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1AhaGyFlyrVaSWxLh0zcB3UX8a0--rNpc?usp=sharing) or at [notebooks/Assignment1.ipynb](notebooks/Assignment1.ipynb)

**report**: pdf report available at [reports/Assignment1.pdf](reports/Assignment1.pdf)

**execution**: open the notebook in [colab](https://colab.research.google.com/drive/1AhaGyFlyrVaSWxLh0zcB3UX8a0--rNpc?usp=sharing) & run it

> (I think that running the notebook in Colab is better)

**local-execution-requirements**: if you run the notebook locally you should check to have installed `spacy`, `nltk` and `scikit-learn`. python version: 3.6+

```bash
# setting up your system on linux based systems
sudo apt install python3 python3-pip
#curl https://bootstrap.pypa.io/get-pip.py | python3  # for MAC users
pip3 install jupyter
pip3 install spacy nltk scikit-learn

# run locally
wget https://raw.githubusercontent.com/thomasreolon/NLU_unitn/main/notebooks/Assignment1.ipynb -O ./Assignment1.ipynb
jupyter-lab Assignment1.ipynb
```

---

# Python Cryptography

This repository presents Python implementations of classical cryptographic
algorithms originally developed as part of a team coursework project for the
University of Bologna.

The current GitHub version has been reorganized, refined, and extended by
**Jiacheng Wang** as an independent educational project and will continue to
grow beyond the original coursework.

---

## Course Information

This project is inspired by the following course:

- **Course:** [90392 - Elements of Applied Data Security M](https://www.unibo.it/en/study/course-units-transferable-skills-moocs/course-unit-catalogue/course-unit/2025/443929)
- **Instructor:** [Dr. Alex Marchioni](https://www.unibo.it/sitoweb/alex.marchioni/en)
- **Institution:** Alma Mater Studiorum – University of Bologna
- **Official Course Repository:** [marchioa/security](https://github.com/marchioa/security)

---

## Original Course Project

The original coursework was completed by the **Codebreakers** team:

- Jiacheng Wang
- Muhammad Usman Afzal
- Peisong Xu

Together we completed the three course modules:

- Substitution Ciphers
- Stream Ciphers
- Block Ciphers

The version published in this repository has been reorganized and documented
by **Jiacheng Wang**.

## Repository Goals

- Implement cryptographic algorithms in Python.
- Explore practical cryptanalysis techniques.
- Document the mathematical concepts introduced during the course.
- Extend the project with additional algorithms and experiments.

---

## Repository Structure

```text
python-cryptography/
│
├── README.md
├── LICENSE
├── .gitignore
│
└── Substitution_Ciphers/
    ├── Substitution_Ciphers.ipynb
    ├── ciphertext_affine.txt
    ├── ciphertext_caesar.txt
    ├── ciphertext_simple.txt
    ├── distribution.pkl
    └── wikipedia_cybersecurity.txt
```

The `Substitution_Ciphers` folder contains:

- A Jupyter notebook with the implementations and experiments
- Ciphertext files used for cryptanalysis exercises
- English-language frequency-distribution data
- Sample text used for encryption and frequency analysis

---

## Quick Start

### Requirements

- Python 3.10 or later
- Jupyter Notebook

Install the required packages:

```bash
pip install numpy matplotlib jupyter
```

Clone the repository:

```bash
git clone https://github.com/wangjiacheng1219/python-cryptography.git
cd python-cryptography
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
Substitution_Ciphers/Substitution_Ciphers.ipynb
```

Run the notebook cells from top to bottom.

---

## Current Contents

The current notebook covers classical substitution ciphers and related
cryptanalysis techniques, including:

- Caesar cipher
- Affine cipher
- Simple substitution cipher
- Brute-force key search
- Letter-frequency analysis

---

## Future Plans

Planned extensions include:

- Additional classical ciphers
- Modern cryptographic algorithms
- More detailed mathematical explanations
- Separate notebooks for individual topics
- Performance comparisons and experiments

---

## Acknowledgements

I would like to express my sincere gratitude to
[Dr. Alex Marchioni](https://www.unibo.it/sitoweb/alex.marchioni/en)
for designing and teaching the
*90392 - Elements of Applied Data Security M* course and for providing the
official course materials that inspired this project.

I would also like to thank my teammates, **Muhammad Usman Afzal** and
**Peisong Xu**, for their collaboration on the original course assignments.

This repository is not an official course repository. The version published
here has been reorganized and documented by **Jiacheng Wang**—hopefully with
a few more updates to come.

---

## License

This project is released under the MIT License.

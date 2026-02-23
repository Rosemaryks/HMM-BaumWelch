# Hidden Markov Model (HMM) using Baum–Welch Algorithm

## Student Details

**Name:** Rose Mary KS  
**Register Number:** TCR24CS057  

---

## 📌 Project Description

This project implements a **Hidden Markov Model (HMM)** using the **Baum–Welch Algorithm**, which is an Expectation–Maximization (EM) algorithm used to train HMM parameters when only observation sequences are available.

The system models two hidden states:

- Rainy (R)
- Sunny (S)

And two observable outputs:

- Walk (W)
- Shop (H)

The model learns updated transition and emission probabilities based on the observation sequence:

(W, H, H, W, H)

---

## ⚙️ Algorithm Used

The following steps are implemented:

1. Forward Algorithm (α calculation)
2. Backward Algorithm (β calculation)
3. Gamma (γ) computation – state responsibility
4. Xi (ξ) computation – transition responsibility
5. Parameter re-estimation:
   - Initial probabilities (π)
   - Transition matrix (A)
   - Emission matrix (B)

The process is repeated for multiple iterations until convergence.

---

## 📂 Project Files

- `hmm.py` → Core implementation of HMM and Baum–Welch algorithm  
- `app.py` → Flask web application for visual output  
- `requirements.txt` → Required Python libraries  
- `README.md` → Project documentation  

---

## ▶️ How to Run the Project

### Step 1: Install Dependencies

```bash
pip install -r requirements.txt
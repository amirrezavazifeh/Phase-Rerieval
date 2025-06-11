# Phase Retrieval and the Importance of Phase in Fourier Domain

This project demonstrates the critical role of **phase** in image formation through a simple visual experiment, followed by the implementation of two classical **phase retrieval** algorithms: **Error Reduction (ER)** and **Hybrid Input-Output (HIO)**.

---

## 🔍 Why Phase Matters More Than Amplitude

We begin by loading two images (e.g., Amir and Jason), computing their Fourier transforms, and **swapping amplitude and phase**. The reconstructed images clearly reveal that **image structure is primarily encoded in the phase**, not the amplitude.

---

## 🎥 Demonstration Video

A visual comparison of the ER and HIO algorithms over iterations:

<video src="https://github.com/amirrezavazifeh/Phase-Rerieval/raw/main/HIO%20vs%20ER.mp4" controls width="100%" style="border-radius: 10px; margin-top: 10px;"></video>


---

## 🔁 Phase Retrieval from Magnitude

Given only the Fourier **magnitude** and a known **support constraint**, we implement and compare two iterative algorithms:

- **ER (Error Reduction)** – Applies alternating projections to satisfy constraints.
- **HIO (Hybrid Input-Output)** – Improves convergence using feedback from previous iterations.

Both methods are evaluated visually and with a video showing step-by-step reconstructions.

---

## 📺 Useful Video to Watch

If you're interested in the mathematical background and intuition behind phase retrieval, this video provides an excellent overview:

➡️ [YouTube: Phase Retrieval Explained](https://www.youtube.com/watch?v=8rJYhRMVvQw)

---

## 🛠️ How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/amirrezavazifeh/Phase-Rerieval.git

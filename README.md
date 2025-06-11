# Phase Retrieval and the Importance of Phase in Fourier Domain

This project demonstrates the critical role of **phase** in image formation through a simple visual experiment, followed by the implementation of two classical **phase retrieval** algorithms: **Error Reduction (ER)** and **Hybrid Input-Output (HIO)**.

---

## 🎥 Demonstration Video

A visual comparison of the ER and HIO algorithms over iterations:

[▶️ Click to Watch the Video](https://github.com/amirrezavazifeh/Phase-Rerieval/blob/main/HIO%20vs%20ER.mp4)

<video src="https://github.com/amirrezavazifeh/Phase-Rerieval/blob/main/HIO%20vs%20ER.mp4" controls width="100%"></video>

---

## 🔍 Why Phase Matters More Than Amplitude

We begin by loading two images (e.g., Amir and Jason), computing their Fourier transforms, and **swapping amplitude and phase**. The reconstructed images reveal that **image structure is primarily encoded in the phase**, not the amplitude.

---

## 🔁 Phase Retrieval from Magnitude

Given only the Fourier **magnitude** and a known **support constraint**, we implement and compare two iterative algorithms:

- **ER (Error Reduction)** – Applies alternating projections to satisfy constraints.
- **HIO (Hybrid Input-Output)** – Improves convergence using feedback from previous iterations.

Both methods are evaluated visually and via video animation of their iterative reconstruction.

---

## 🛠️ How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/amirrezavazifeh/Phase-Rerieval.git

# Phase Retrieval and the Importance of Phase in Fourier Domain

This project demonstrates the critical role of **phase** in image formation through a simple visual experiment, followed by the implementation of two classical **phase retrieval** algorithms: **Error Reduction (ER)** and **Hybrid Input-Output (HIO)**.

---

## 🖼️ Why Phase Matters?

We begin by loading two well-known images — **Astronaut** and **Cameraman** — and swapping their **Fourier amplitude** and **phase** components. The experiment clearly reveals that **image structure is primarily encoded in the phase**, not the amplitude.

<p align="center">
  <img src="https://github.com/amirrezavazifeh/Phase-Rerieval/raw/main/Why%20Phase%20Matters%3F.png" alt="Why Phase Matters" width="100%">
</p>

---

## 🔁 Phase Retrieval from Magnitude

Given only the Fourier **magnitude** and a known **support constraint**, we implement and compare two iterative algorithms:

- 🟢 **ER (Error Reduction)** – Applies alternating projections to satisfy constraints.
- 🔵 **HIO (Hybrid Input-Output)** – Improves convergence using feedback from previous iterations.

Both methods are evaluated visually and through a video showing step-by-step reconstructions.

---

## 🎥 Demonstration Video

## 🎥 Demonstration Video

A visual comparison of the ER and HIO algorithms over iterations ([download the video](https://github.com/amirrezavazifeh/Phase-Rerieval/raw/main/HIO%20vs%20ER.mp4)):

---

## 📺 Useful Video to Watch

If you're interested in the mathematical background and intuition behind phase retrieval, this video provides an excellent overview:

➡️ [YouTube: Phase Retrieval Explained](https://www.youtube.com/watch?v=8rJYhRMVvQw)

---

## 🛠️ How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/amirrezavazifeh/Phase-Rerieval.git

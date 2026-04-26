📌 Overview

This project explores the layer-wise evolution of BERT embeddings for characters in the Mahabharata using a Physics-Informed Neural Network (PINN) framework.

Instead of treating transformer layers as discrete steps, we model embedding transitions as a continuous dynamical system, enabling smooth, interpretable semantic trajectories.

🚀 Key Features
🔹 Continuous modeling of BERT embedding transitions using PINNs
🔹 Integration of narrative metadata (parva, chapter, sentence index)
🔹 Physics-informed constraints:
Smoothness
Norm conservation
Narrative consistency
🔹 Trajectory-based semantic analysis of characters
🔹 Joint modeling of transformer depth + narrative time
🔹 Comparative benchmarking with:
Linear Regression
MLP
Neural ODE

📂 Dataset
Source: Mahabharata corpus (PouranicTopic dataset)
Characters:
Arjuna
Krishna
Karna
Duryodhana
Yudhishthira
Abhimanyu
Data Format

Each sample contains:

768-dim BERT embedding
Metadata:
Parva
Chapter
Sentence index
Layer index

👉 Input dimension: 772 (768 + 4 metadata)
👉 Output dimension: 768

## SecAI - Training Cyber-Focused AI Models to Solve Complex Security & Compliance Challenges

When accuracy, consistency, and structural precision are non-negotiable, relying solely on prompt engineering with general-purpose models is a fundamentally limited approach. In mission-critical enterprise environments, specialized Cyber-Focused AI models offer a more strategic solution—delivering higher accuracy, stronger reliability, and greater operational efficiency.


## Technologies
This project makes use of the following open-source technologies and tools:

+  Python: The programming language used for implementing the project.
+  NumPy: A library used for efficient multi-dimensional data operations where PyTorch tensors aren't suitable.
+  Pandas: A library used for cleaning, transforming, and exploring the data prior to model fine-tuning.
+  PyTorch: A library used to build the BERT and LoRA models from scratch and for fine-tuning.
+  TensorFlow: open-source platform for machine learning (ML) and artificial intelligence
+  Hugging Face Transformers: A library used to access pretrained models and weights. It was predominantly employed to load models and conduct further training in the optimization section of this project.
+  Transformer: A library used to simplify the process of applying inference optimizations to the models.

## Data
This project makes use of the following open-source data:

+  HIPAA 45:  Title 45 of the Code of Federal Regulations, which contains the administrative simplification rules governing health information privacy and security.
+  NIST 800-53 Rev 5: a comprehensive catalog of security and privacy controls designed to help organizations manage risk and protect information systems

##  LoRA (Low-Rank Adaptation)
LoRA (Low-Rank Adaptation) is a fine-tuning technique designed to preserve high model accuracy while significantly reducing computational cost and complexity. Instead of updating all model parameters, LoRA injects small, low-rank adaptation matrices into selected layers, keeping the original pretrained weights frozen. This approach dramatically reduces the number of trainable parameters, enabling more efficient training, lower memory usage, and faster experimentation—without sacrificing performance

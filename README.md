# full_training_on_pytorch

A PyTorch implementation of training process with MRPC dataset (from GLUE) 

# Padding 
I have used collators for preprocessing of dataset 
# Loop
I have implemented a lower-level training loop for batch=8 
# Accelerator
I have used 🤗 Accelerate to adapt my training loop for multiple GPUs or TPUs (it was 3 min for GPU and 2.30 hours for TPU without accelerator.prepare() )
# Fine-tuning
I have used fine-tuning based on bert-base-uncased checkpoints, which much faster and less time consuming for practice like this repo

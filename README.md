# ViT_Paper_Replication

This repository contains a step-by-step replication of the Vision Transformer (ViT) paper using PyTorch. The project aims to provide a clear and concise implementation of the ViT model, breaking down the complex architecture into manageable components for better understanding and ease of learning.

## Table of Contents

0. **Get Setup**: Initial setup and environment configuration.
1. **Get Data**: Acquisition and preparation of the dataset.
2. **Create Datasets and DataLoaders**: Organizing data into PyTorch datasets and dataloaders.
    2.1 **Visualize a Single Image**: Visualizing sample images from the dataset.
3. **Replicating ViT: Overview**: Introduction to the Vision Transformer architecture.
    3.1 **ViT Overview: Pieces of the Puzzle**: Detailed breakdown of the ViT components.
        - Four Equations
        - Table 1
4. **Equation 1: Split Data into Patches and Creating the Class, Position, and Patch Embedding**: 
    4.1 **Calculate Input and Output Shapes by Hand**: Manual calculations for shapes.
    4.2 **Turning a Single Image into Patches**: Splitting images into smaller patches.
    4.3 **Creating Image Patches and Turning Them into Patch Embeddings**: Generating patch embeddings.
    4.4 **Flattening the Patch Embedding with `torch.nn.Flatten()`**: Flattening the embeddings.
    4.5 **Turning the ViT Patch Embedding Layer into a PyTorch Module**: Implementing the patch embedding as a module.
    4.6 **Creating a Class Token Embedding**: Adding class token embeddings.
    4.7 **Creating the Position Embedding**: Generating position embeddings.
    4.8 **Putting It All Together: From Image to Embedding**: Combining all embedding steps.
5. **Equation 2: Multihead Self-Attention (MSA Block)**: Implementing the MSA block.
    - Why Query, Key, and Value are Same (x)
6. **Equation 3: Multilayer Perceptron (MLP Block)**: Building the MLP block.
7. **Creating the Transformer Encoder**: Assembling the encoder from the components.

This repository serves as a comprehensive guide for understanding and implementing the Vision Transformer model. Each section includes detailed explanations and code snippets to facilitate learning and replication of the ViT architecture.

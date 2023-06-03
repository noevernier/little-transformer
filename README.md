# Little Transformer

Little Transformer is a simple implementation of the Transformer model based on the research paper "Attention is All You Need." This project aims to provide a clear and concise codebase that demonstrates the key components and functionality of the Transformer architecture.

## What is the Transformer Model?

The Transformer model is a neural network architecture introduced in the paper "Attention is All You Need" by Vaswani et al. It revolutionized natural language processing tasks by leveraging self-attention mechanisms instead of recurrent or convolutional networks. The Transformer has been widely adopted and proven to be effective in various tasks, including machine translation, language understanding, and text generation.

## Project Structure

The project is organized as follows:

- `little_transformer.py`: The main implementation of the Transformer model.
- `data_utils.py`: Utility functions for processing and preparing the input data.
- `train.py`: The training script for the Little Transformer model.
- `evaluate.py`: The evaluation script for the trained model.
- `example_usage.ipynb`: A Jupyter Notebook showcasing example usage of the Little Transformer model.

## Requirements

To run the Little Transformer project, you need the following dependencies:

- Python 3.x
- PyTorch
- TorchText
- NumPy

## Getting Started

Follow these steps to get started with the Little Transformer project:

1. Clone the repository:

   ```shell
   git clone https://github.com/noevernier/little-transformer.git
   cd little-transformer
   ```

2. Install the dependencies:

   ```shell
   pip install -r requirements.txt
   ```

3. Prepare your dataset. Modify the `data_utils.py` file to load and preprocess your specific dataset.

4. Train the model:

   ```shell
   python train.py
   ```

5. Evaluate the trained model:

   ```shell
   python evaluate.py
   ```

6. Explore the `example_usage.ipynb` Jupyter Notebook for more detailed examples and explanations.

## Contributing

Contributions are welcome! If you find any bugs or want to add new features, feel free to open an issue or submit a pull request. Please ensure that your code adheres to the project's coding style and passes the existing tests.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

The Little Transformer project was inspired by the groundbreaking work presented in the research paper "Attention is All You Need" by Vaswani et al. The codebase also benefited from various online resources and tutorials.

Enjoy using the Little Transformer!
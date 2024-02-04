# Character-Level Language Modeling Project

## Overview:

This project implements a character-level language model using PyTorch, focusing on the training and generation of new words based on learned language patterns. The primary components include:

1. **Bigram Analysis:**
    - Explore the relationships between consecutive characters in a given text using a bigram model.
    - Visualize bigram counts using a matrix representation.

2. **Language Model Training:**
    - Train a simple character-level language model using PyTorch.
    - Implement a training function that utilizes gradient descent and L2 regularization to update the model weights.

3. **Word Generation:**
    - Develop a function to generate new words using the trained language model.
    - Utilize a sampling approach to predict and simulate the generation of novel words.

## Project Structure:

- **`bigram_analysis function`:**
    - Jupyter Notebook providing insights into bigram analysis, including visualization of bigram counts.

- **`language_model_training function`:**
    - Jupyter Notebook implementing the training of the character-level language model.

- **`word_generation function`:**
    - Jupyter Notebook showcasing the generation of new words using the trained language model.

- **`data/`:**
    - Directory containing the dataset or text files used for training and analysis.



## Usage:

1. **Bigram Analysis:**
    - Open and run the `bigram_analysis.ipynb` notebook for insights into bigram relationships.

2. **Language Model Training:**
    - Open and run the `language_model_training.ipynb` notebook to train the character-level language model.

3. **Word Generation:**
    - Open and run the `word_generation.ipynb` notebook to generate new words using the trained model.

## Requirements:

- Python 3.x
- PyTorch
- Matplotlib
- Jupyter Notebooks

## Example:

```python
# Example Usage:
# Train the language model
trained_weights = training_function(words=training_data, epoch_num=10, lr=0.001)

# Generate new words
make_new_name(weights=trained_weights, num_of_words=5)

# NLP_LSTM
This project employs LSTM algorithm on the "Pride and Prejudice" text from Project Gutenberg. It generates coherent and contextually appropriate text, capturing the essence of Austen's writing style. Users can interact with the model, receiving prompts or random excerpts, making it a valuable resource for literary enthusiasts and creative writers.

## Project Name: Pride and Prejudice LSTM Text Generation

This project utilizes the LSTM algorithm to generate text inspired by Jane Austen's novel "Pride and Prejudice." The algorithm is trained on the text data obtained from Project Gutenberg, capturing the writing style and essence of the original work. The generated text can be used for creative writing, literary analysis, or simply for the enjoyment of Austen's language and storytelling.

### Dependencies
- Python (>= 3.6)
- TensorFlow (>= 2.0)
- Keras (>= 2.3)
- Numpy (>= 1.18)
- Pandas (>= 1.0)

### Installation
1. Clone the repository: `git clone https://github.com/yourusername/pride-and-prejudice-lstm.git`
2. Navigate to the project directory: `cd pride-and-prejudice-lstm`
3. Install the required dependencies: `pip install -r requirements.txt`

### Usage
1. Download the "Pride and Prejudice" text file from Project Gutenberg (e.g., `pride_and_prejudice.txt`) and place it in the project directory.
2. Preprocess the text data by running: `python preprocess.py pride_and_prejudice.txt`
3. Train the LSTM model by running: `python train.py`
4. Generate text using the trained model: `python generate.py`

### Configuration
- You can modify the hyperparameters and model architecture in `config.py`.
- Adjust the training settings, such as the number of epochs and batch size, to fit your needs.

### Resources
- "Pride and Prejudice" text file from Project Gutenberg: [Link](https://www.gutenberg.org/files/1342/1342-0.txt)

### Acknowledgments
- This project is based on the Long Short-Term Memory (LSTM) algorithm implemented in TensorFlow and Keras.
- The text data used in this project is sourced from Project Gutenberg.

### License
This project is licensed under the [MIT License](LICENSE).

### Disclaimer
This project is for educational and non-commercial use only. The generated text should not be considered as the original work of Jane Austen.

# Beginner-Friendly AI Examples

Welcome! This directory contains simple, standalone examples to help you get started with AI and machine learning. Each example is designed to be beginner-friendly with detailed comments and step-by-step explanations.

## 📚 Examples Overview

| Example | Description | Difficulty | Prerequisites |
|---------|-------------|------------|---------------|
| [Hello AI World](./01-hello-ai-world.py) | Your first AI program - simple pattern recognition | ⭐ Beginner | Python basics |
| [Simple Neural Network](./02-simple-neural-network.py) | Build a neural network from scratch | ⭐⭐ Beginner+ | Python, basic math |
| [Image Classifier](./03-image-classifier.ipynb) | Classify images with a pre-trained model | ⭐⭐ Beginner+ | Python, numpy |
| [Text Sentiment](./04-text-sentiment.py) | Analyze text sentiment (positive/negative) | ⭐⭐ Beginner+ | Python |

## 🚀 Getting Started

### Prerequisites

Make sure you have Python installed (3.8 or higher recommended).

The three Python scripts use only the standard library. For the image classifier
notebook, install:

```bash
pip install jupyter numpy pillow requests tensorflow
```

Or create the included conda environment from this directory:

```bash
# Windows
conda env create --file .devcontainer/environment-win.yml

# Linux/macOS
conda env create --file .devcontainer/environment.yml

conda activate ai4beg
```

### Running the Examples

**For Python scripts (.py files):**
```bash
python 01-hello-ai-world.py
```

**For Jupyter notebooks (.ipynb files):**
```bash
jupyter notebook 03-image-classifier.ipynb
```

## 📖 Learning Path

We recommend following the examples in order:

1. **Start with "Hello AI World"** - Learn the basics of pattern recognition
2. **Build a Simple Neural Network** - Understand how neural networks work
3. **Try the Image Classifier** - See AI in action with real images
4. **Analyze Text Sentiment** - Explore natural language processing

## 💡 Tips for Beginners

- **Read the code comments carefully** - They explain what each line does
- **Experiment!** - Try changing values and see what happens
- **Don't worry about understanding everything** - Learning takes time
- **Ask questions** - Use the [Discussion board](https://github.com/microsoft/AI-For-Beginners/discussions)



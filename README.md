# Interactive NLP Tokenization Workshop

This Jupyter Notebook provides an interactive learning experience for understanding tokenization in Natural Language Processing (NLP). The notebook features hands-on exercises, interactive visualizations, and real-world examples, with a special focus on financial text processing.

## Features

- Interactive tokenization demonstrations with multiple methods
- Visual representations of tokenization processes
- Hands-on exercises and challenges
- Real-world examples, especially in finance
- Interactive regex pattern testing and explanation
- Multiple tokenization approaches (NLTK, spaCy, Hugging Face)
- Dynamic visualizations using Matplotlib and NetworkX

## Project Structure

```
.
├── README.md
├── requirements.txt
├── tokenization_workshop.ipynb

```

## Setup Instructions

1. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Download required NLTK data:
```python
import nltk
nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')
```

4. Download spaCy model:
```bash
python -m spacy download en_core_web_sm
```

5. Launch Jupyter Notebook:
```bash
jupyter notebook
```

6. Open `tokenization_workshop.ipynb`

## Notebook Structure

1. **Introduction to Tokenization**
   - Basic concepts
   - Importance in NLP
   - Real-world applications

2. **Basic Tokenization Implementation**
   - Custom word tokenization
   - Custom sentence tokenization
   - Interactive text input

3. **Understanding Regular Expressions**
   - Interactive regex testing
   - Common patterns in NLP
   - Visual pattern matching

4. **Advanced Tokenization with NLP Libraries**
   - NLTK implementation
   - spaCy implementation
   - Hugging Face Transformers

5. **Interactive Visualizations**
   - Word frequency plots
   - Tokenization flow diagrams
   - Dynamic updates

6. **Challenges and Edge Cases**
   - Handling contractions
   - Special characters
   - Interactive problem-solving

7. **Conclusion and Further Resources**
   - Key takeaways
   - Additional reading
   - Practice exercises

## Requirements

- Python 3.7+
- See requirements.txt for package dependencies

## Methodology

This notebook was created following a structured approach:

1. **Content Organization**
   - Progressive complexity (basic → advanced)
   - Interactive elements at each step
   - Real-world examples and applications

2. **Interactive Elements**
   - Text input widgets for user interaction
   - Dynamic visualizations
   - Real-time pattern matching
   - Multiple tokenization methods comparison

3. **Visual Learning**
   - Flow diagrams
   - Frequency plots
   - Pattern matching highlights
   - Process visualization

4. **Hands-on Practice**
   - Custom implementation exercises
   - Edge case handling
   - Pattern testing
   - Real-world applications

## License

MIT License

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. 

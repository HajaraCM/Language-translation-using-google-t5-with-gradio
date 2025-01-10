# Language Translation using Google T5 with Gradio

This repository demonstrates how to use the Google T5 (Text-to-Text Transfer Transformer) model to translate English text into Hindi and German. It also includes a simple Gradio interface to make the translation process user-friendly.

## Features
- Translate text from English to Hindi.
- Translate text from English to German.
- Gradio-based interactive interface for translation.

## Installation

1. Clone the repository:
   ```bash
  github.com/HajaraCM/Language-translation-using-google-t5-with-gradio.git
   cd language-translation-t5
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Requirements
The main libraries used in this project are:
- `transformers`: For loading and using the T5 model.
- `torch`: For deep learning operations.
- `gradio`: For creating the user interface.

## Usage

Run the following command to start the Gradio interface:
```bash
python app.py
```

Once the script is running, you can access the interface in your browser at `http://127.0.0.1:7860/`.

## Code Structure

The main functionality is implemented in `app.py`. It includes:
- Loading the T5 model and tokenizer.
- Defining the `translate_text` function to handle translation tasks.
- Setting up a Gradio interface for user interaction.

### `requirements.txt`
```plaintext
transformers
torch
gradio
```



### Gradio Interface

## Future Enhancements
- Add support for more languages.
- Improve the user interface.
- Deploy the app on a cloud platform like Hugging Face Spaces or Heroku.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

Feel free to contribute by submitting issues or pull requests!

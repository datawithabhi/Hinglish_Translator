# English to Hinglish Translator

This Python tool translates English sentences to Hinglish (a hybrid of Hindi and English). It provides two methods for translation: one using the 'translate' library and the other using the 'transformers' library. Additionally, the tool allows for manual word replacement to enhance the translation quality.

## Methods Used

### Method 1: Using the 'translate' Library

In this method, the 'translate' library is employed to translate English sentences to Hinglish. It provides a straightforward way to perform translations.

#### Usage

You can run the code in `method1_translate.py` to translate English sentences to Hinglish. Here are some example sentences and their translations:

1. "Definitely share your comment and feedback in the comment section."
   - Translation: "कमेंट सेक्शन में अपना comment और feedback ज़रूर शेयर करें।"

2. "So even if it's a big video, I will clearly mention all the products."
   - Translation: "सो इवें इफ़ इट'स अ बिग video, आई विल क्लियर्ली mention ऑल थे products।"

3. "I was waiting for my bag."
   - Translation: "आई वॉज वेटिंग फ़ॉर माय bag।"

#### About the 'translate' Library

The 'translate' library is a Python module for performing text translation using various translation engines, with Google Translate being one of the options. It provides a straightforward way to translate text from one language to another.

### Method 2: Using the 'transformers' Library

In this method, the 'transformers' library is used to create a custom translation approach. It allows you to specify certain English words to keep as is while translating the rest to Hinglish.

#### Usage

You can run the code in `method2_custom_translation.py` to translate English sentences to Hinglish using the custom approach. Here are some example sentences and their translations:

1. "Definitely share your feedback in the comment section."
   - Translation: "Definitely सेक्शन में अपना feedback शेयर करें।"

2. "So even if it's a big video, I will clearly mention all the products."
   - Translation: "So even if it's a big video, I will clearly mention all the products."

3. "I was waiting for my bag."
   - Translation: "I was waiting फ़ॉर my bag."

#### About the 'transformers' Library

The 'transformers' library is a popular Python library developed by Hugging Face for natural language processing (NLP) tasks. It includes pre-trained models and tools for various NLP tasks, including translation. In this method, we use a pre-trained model for English to Hindi translation.

## Getting Started

To get started with the translator tool, follow these steps:

### Prerequisites

- Python 3.x
- Required libraries (specified in each method's script)

### Installation

1. Clone this repository to your local machine.

   ```bash
   git clone [repository-url]
   cd English-to-Hinglish-Translator

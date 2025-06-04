# Product Copy & Keyword Generator using GPT

This project uses OpenAI’s language model to automatically generate product descriptions based on the product's key details like name, features, brand, and target audience. You can customize the tone and length (short, medium, long) of the content, and it even gives you multiple variations to choose from.
Once the copies are generated, the tool analyzes them to suggest relevant marketing keywords — perfect for improving product visibility and SEO. 



## Features

- Generate short, medium, or long product copies
- Customizable tone and target audience
- Powered by `gpt-3.5-turbo` or `gpt-4`
- Outputs multiple variations for flexibility
- Clean and readable product storytelling



## How It Works

1. **Input**: Provide product details like name, category, features, tone, and audience.
2. **Prompting**: The notebook builds a custom GPT prompt using this info.
3. **Generation**: GPT responds with natural-sounding product copy.
4. **Variation**: You can generate multiple versions and choose the best fit.



## Setup Instructions

### 1. Clone the Repository or Download the Notebook

```bash
git clone https://github.com/your-username/gpt-product-copy-generator.git
cd gpt-product-copy-generator
```

### 2. Install Dependencies

Ensure you have Python 3.7+ installed, then run:

```bash
pip install openai
```

### 3. Add Your OpenAI API Key

You can either:

* Store your key in an `.env` file (using `python-dotenv`)
* Or directly set it in the notebook:

```python
import openai
openai.api_key = "sk-your-secret-key"
```



## Tips

* For more creative output, increase the `temperature` in the GPT API call.
* To generate multiple copy options, raise `num_variations`.
* You can feed in extra product keywords if needed for SEO.



## Author

Anvita Manne

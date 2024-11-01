# **ML-Tagging**

ML-Tagging is a Python program designed to **automatically generate tags** for text data scraped from **one or more sitemaps**, leveraging OpenAI’s GPT model for high-quality tagging.

This tool is particularly useful for **content categorization, SEO,** and **AI chatbot optimization**. It features stopword removal to **optimize token usage**, minimizing API call costs during tagging.

**Note:** This notebook is optimized for use in **Google Colab**, allowing users to access it with minimal setup via the link provided - see **"ML-tagging.ipynb"**.



### **Features**

**Automated Tagging:** Uses OpenAI's advanced language model to produce relevant tags for your content.

**Stopword Removal:** Reduces token usage to save on API costs.

**Customizable Prompts:** Tailor the tag output by providing custom prompts that best match your data's context.

**Flexible Sitemap Input:** Accepts multiple sitemaps to cover a wide range of web pages.




### **User Parameters**

**OpenAI API Key:** Required to access the GPT model for tag generation.

**Sitemap(s):** Input one or more sitemaps from which text data will be scraped.

**Output Directory:** Specify where the output CSV file will be saved.



### **Output**

The tagged data is saved as a CSV file in your chosen output directory. The CSV includes the following headers:

URL: Web address of the tagged content.

Webpage Title: Title of each webpage.

Tags: Generated hashtags based on the content.



### **License**

This project is licensed under the **CC-BY License**, allowing free reuse with credit.



### **Author**

Created by **Ari Guest**.


**Note:** This project is not actively maintained. You are welcome to contribute improvements under the CC-BY license. Happy tagging!

_01-11-2024_
# ML-tagging
A program used to automatically tag text data (in #tag-name format) scraped from sitemap(s) using OpenAI 4o-mini. The quality of output tags depends heavily on the prompt provided to the model - see example prompt.
This program utilises stopword removal to cut down on token usage during tagging. 

** It is recommended that this notebook be run in Google Colab via the link provided **

User parameters: OpenAI API Key, Sitemap(s), Output Directory.

Data is output as a CSV file to rhe selected output directory. Headers: URL, Webpage Title, Tags

Licence: CC-BY (free re-use with credit)

Created by: Ari Guest (2024)

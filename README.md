# Multiple-Choice-Question-Generator

This project is a Python-based Jupyter Notebook designed to help users generate questions efficiently and interactively. It leverages modern data science tools and interactive widgets to create a seamless experience for educators, students, or anyone needing to produce custom questions quickly. The notebook features progress bars and visual feedback, making the process transparent and user-friendly. By combining code, interactivity, and clear progress indicators, this project aims to make question generation both accessible and enjoyable for everyone, regardless of their technical background.


My Keyphrase Extractors
1. KeyBERT
KeyBERT is my go-to tool when I need to extract the most meaningful words and phrases from any text. What I love about KeyBERT is that it uses advanced AI language models (like BERT) to really understand the context and importance of each phrase, not just how often it appears. In my workflow, I use KeyBERT to pull out both the main ideas (which I can use as correct answers) and other relevant phrases (which make great distracters for multiple-choice questions). I can also fine-tune its settings to control the length and diversity of the keyphrases it finds, giving me flexibility based on what I need.

2. YAKE (Yet Another Keyword Extractor)
YAKE is another powerful extractor that I use, especially when I want something fast and lightweight. Unlike KeyBERT, YAKE doesn’t rely on big AI models—it uses smart statistical techniques to figure out which words and phrases are most important based on their position, frequency, and context within the document. YAKE is perfect for quickly finding key concepts in smaller or more straightforward texts, and I often use it alongside KeyBERT to give myself a broader set of options for both correct answers and distracters.

My QuesGen.ipynb Notebook
QuesGen.ipynb is my question generation engine—the notebook that brings everything together. I take the keyphrases I’ve extracted using KeyBERT and YAKE, and QuesGen.ipynb helps me turn them into ready-to-use quiz questions. Here’s how I use it:

I select the most relevant phrase as the correct answer.
I pick other meaningful phrases as distracters (the alternative options).
The notebook automatically formats these into multiple-choice questions, which saves me time and ensures everything is consistent.

How It All Comes Together:
By combining KeyBERT and YAKE, I get the best of both worlds: deep, context-aware keyphrases from KeyBERT and fast, statistically-driven phrases from YAKE. My QuesGen.ipynb notebook ties it all together, using the outputs from both extractors to create high-quality, content-driven multiple-choice questions. This integrated approach helps me make sure my questions are accurate, challenging, and closely tied to my source material.

My Chemistry Dataset:
The dataset I used for keyphrase extraction is a structured collection of chemistry lessons, saved in a JSON file. It covers foundational topics like "Some Basic Concepts of Chemistry," including the importance of chemistry in everyday life, the nature and states of matter, classification of substances, and measurement systems used in science.

Each lesson is written in clear, educational language, making it perfect for both teaching and learning. The content ranges from simple definitions—like what matter is—to more detailed explanations about mixtures, pure substances, elements, compounds, and the SI system of units. There are also practical examples and real-world applications, such as how chemistry contributes to industry, healthcare, and environmental solutions.

This rich, well-organized dataset provides the ideal material for my keyphrase extractors (KeyBERT and YAKE) to identify important concepts and generate effective quiz questions. By working with this content, I can ensure that the keyphrases and questions I create are accurate, relevant, and closely tied to the actual curriculum—making the learning process more engaging and meaningful.

In summary:
KeyBERT and YAKE help me find what matters most in my content, and QuesGen.ipynb transforms those insights into engaging questions—making my quiz creation process smarter, faster, and much more reliable!

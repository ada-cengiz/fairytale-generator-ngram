Fairytale Generator using N-gram Language Models
A simple fairytale story generator built using n-gram language modeling and Python. Trained on a corpus of Grimm’s Fairy Tales, this tool generates whimsical bedtime stories based on user-provided character names, types, and settings.

Project Overview : 
- This project explores how classic NLP techniques (specifically n-gram models) can be used for basic text generation. It’s designed as a playful, lightweight alternative to large-scale neural models, with a specific use case: helping parents generate custom bedtime stories for their children.

- While modern language models (e.g., GPT) dominate text generation, this project shows how earlier statistical approaches can still yield charming results when trained on genre-specific text like fairy tales.

Features : 
- Customizable inputs: name, character type (e.g. princess, knight), and setting
- Trigram-based generation using a tokenized Grimm corpus
- Sentence-by-sentence story construction
- Basic fallback handling for unseen n-grams

Tech Stack : 
- Python 3
- nltk for tokenization and basic NLP preprocessing
- Jupyter Notebook (project is fully runnable in .ipynb format)
- Grimm Fairy Tales corpus (manually preprocessed)

How to Run :
- Clone the repository or download the .ipynb notebook
- Make sure you have the following Python libraries installed: bash, Copy, Edit, pip install nltk
- Run the notebook Final_Fairytale_Generator_Project.ipynb
- Enter your desired character name, role, and setting when prompted

⚠️ Note: This project is a prototype — sentence structure can be quirky or repetitive due to n-gram limitations.

Example Output:
Once upon a time, there lived a brave knight named Kai in the deep forest. One day, Kai went on a journey to find a magical flower. Along the way, Kai met a mysterious fox who spoke in riddles…
(Actual outputs may vary with each generation.)

Notes : 

* This was a final project for LING360 Computational Linguistics, taught in Boğaziçi University. 

* The project was collaborative with 3 other classmates, we have all contributed equally to the project. I have especially worked on Model implementation, parameter tuning, testing, user interaction logic.

* Inspired by early rule-based generation systems and modern prompt-based NLP tools

* For demonstration purposes only — not a production-level application

License
This project is academic and non-commercial. Use freely with attribution, have fun.


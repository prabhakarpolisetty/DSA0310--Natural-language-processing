DSA03 – Natural Language Processing: 26 Lab Programs

Contents:
- 26 separate Python source files, one for each experiment.
- Each file includes the corresponding experiment title and program code.

Setup:
1. Install Python 3.
2. Install only the packages needed by the experiment you want to run:
   pip install nltk spacy scikit-learn transformers torch sentencepiece openai
3. For spaCy NER:
   python -m spacy download en_core_web_sm
4. NLTK programs may need downloadable data packages. The relevant download
   commands are included as comments in the programs.
5. The OpenAI API experiment requires an API key and access to a compatible
   model. Set OPENAI_API_KEY as an environment variable before running it.

Run a program:
   python 01_Regular_Expressions_in_Python.py

Note:
Some experiments use simplified educational implementations (for example,
reference resolution, coherence scoring, and FOPC tokenization) to demonstrate
the core concept; they are not full production NLP systems.

De-identifying Clinical Text

This project demonstrates an end-to-end pipeline for de-identifying clinical free text, removing or masking Protected Health Information (PHI) so that clinical notes can be reused for analytics and research while preserving patient privacy.

Goals
Detect PHI entities (such as patient names, dates, locations, contact details, and IDs) in clinical text using NLP techniques.

Apply redaction or replacement strategies to generate a de-identified version of the input notes.

Provide a clear, reproducible example of a de-identification workflow inside a single notebook (Coding.ipynb).

Methods
(Adjust this section so it reflects what you actually implemented.)

Preprocessing: basic text cleaning, normalisation, tokenisation, and sentence splitting.

PHI detection:

Rule-based regular expressions for emails, phone numbers, dates, postcodes, IDs.

Optional dictionaries or lookup lists for hospitals, locations, and organisations.

Optional NER model (e.g., spaCy/transformers) for names, organisations, and other entities.

De-identification strategies:

Simple redaction with placeholders, e.g. [NAME], [DATE], [HOSPITAL], [ID].

Or consistent surrogate replacement (e.g. realistic but fake names and shifted dates), if implemented.

Repository Contents
(Adapt to match your actual structure.)

Coding.ipynb – main notebook containing the complete de-identification pipeline (load text, detect PHI, mask/replace, and export results).

data/ – sample clinical-style notes (synthetic or pre-de-identified examples).

models/ – any saved NER or language models used in the notebook (if applicable).

README.md – project documentation.

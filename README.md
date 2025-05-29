# Codex-Test

Testing Codex Features

## Summarizer Script

`summarizer.py` provides abstractive summarization for long-form news
articles using a transformer-based model. Named entities are extracted
with spaCy and the script appends any missing entities to the summary to
help preserve important relationships.

### Usage
```
python summarizer.py path/to/article.txt
```

Ensure that the `transformers` and `spacy` packages are installed and
that the spaCy model `en_core_web_sm` is available. Model weights must be
downloaded beforehand in environments without network access.

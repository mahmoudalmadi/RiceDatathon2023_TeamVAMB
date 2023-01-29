# RiceDatathon2023_TeamVAMB

Mahmoud Al-Madi, Akshat Kumar, Benjamin Meisburger, Virginia Baskin

## Bill.com Challenge.

Our approach involved two main steps– Information Extraction and Information Retrieval. <br>

Information extraction involved pulling key information from images of receipts, while information retrieval matched the extracted fields from the receipts to the user inputted data. <br>

As an oversimplification, we used LayoutLMv3 for extraction and an original algorithm to score matches utilizing FuzzyWuzzy's string matching functions.

The LayoutLMv3 we fine tuned on SROIE: https://huggingface.co/bmeisburger/datathon

# Hierarchical Text Summarization

## Description
This project implements an algorithm to generate summarization of an input text following the style of another text given as input in the context window. The implementation is done using Python and NLTK.

## Operational Structure
1. **Measure the length of the two documents**.
2. **Compute the target lengths in a proportional way**.
3. **Slice the second document from start to a point within the context window**.
4. **Summarize the slice with no request for size of the target**.
5. **Repeat the previous two steps until the end of the document**.
6. **Collate the summaries above**.
7. **Repeat the shrinking activities until the summary size is within the context window**.
8. **Save the document**.
9. **Repeat the summarization for the second document**.
10. **Generate the query**.

## Technologies Used
- Python
- NLTK

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/akhlaghigithub/ASSIGNMENT-2

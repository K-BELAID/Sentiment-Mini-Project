# Sentiment Analysis Mini Project

This is a small demonstration dataset; it can be extended to larger datasets like IMDb or Twitter.  
It uses:

- **TF-IDF vectorization** to convert text into numerical features  
- **Logistic Regression** to train a simple machine learning model  
- A Python function `predict_sentiment()` for interactive predictions  

The project is designed as a **small demonstration** of NLP and machine learning for text sentiment classification.

---

## Features

- Text preprocessing (vectorization using TF-IDF)  
- Logistic Regression model for classification  
- Interactive prediction function  
- Easy to extend for larger datasets or real applications  

---

## How to Use

1. Run the notebook cells sequentially  
2. Use the function like this:

```python
# Example usage:

predict_sentiment("I love this product")
# Output: 'Positive'

predict_sentiment("I hate this film")
# Output: 'Negative'
```
## Notes

- This is a small demo dataset; you can replace it with larger datasets like IMDb or Twitter.  
- Uncomment `print(df)` in the notebook to see the TF-IDF matrix.  
- Easy to extend for real applications.

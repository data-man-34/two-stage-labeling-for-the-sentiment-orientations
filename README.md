p-hot Lexicon Embedding-based Two-level LSTM for Sentiment Analysis
1. Description of the algorithm
  Real sentences or paragraphs usually contain mixed sentiment orientations. Our algorithm is based a two-stage labeling for the sentiment orientations. A two-level network is accordingly proposed to utilize the two labeled data in the two-stage labeling strategy. Lexical cues (e.g., polar words, POS, conjunction words) are also used in our two-level network with a new encoding strategy. Please refer to our paper at arXiv for details: p-hot Lexicon Embedding-based Two-level LSTM for Sentiment Analysis.(https://arxiv.org/pdf/1803.07771.pdf)

2. Environment: python 3.5 or higher, keras (2.1.3)

3. The Baidu AI API is used for Chinese word segmentation. For the five types of lexicon words and conjunction words used in the algorithm, please contact the authors of the algorithms (Email: lm1165645137@163.com). 

4. Please run the embed_attention.py at first and then the model.py.

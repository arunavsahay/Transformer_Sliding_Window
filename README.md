When using BERT and it's variants architecture we often come arise a problem of handling long text sequences.
BERT defaults to handling sequences not more than 512 tokens.
For sequences more than 512 we often have to truncate which yeilds in loss of training data or relevant information.
I have written a SlidingWindow class with examples in the ipynb file. We'll explore how the concept of Sliding Window can be used on longer text sequences without losing any information.
More optimized code will be uploaded soon.
Thank You.

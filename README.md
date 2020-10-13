# Fast.ai-Text-Classification

Transfer learning is a technique where instead of training a model from scratch, we reuse a pre-trained model and then fine-tune it for another related task

Proposed by fast.ai’s Jeremy Howard and NUI Galway Insight Center’s Sebastian Ruder, ULMFiT is essentially a method to enable transfer learning for any NLP task and achieve great results. All this, without having to train models from scratch. That got your attention, didn’t it?

ULMFiT achieves state-of-the-art result using novel techniques like:

  - Discriminative fine-tuning
  - Slanted triangular learning rates, and
  - Gradual unfreezing

This method involves fine-tuning a pre-trained language model (LM), trained on the Wikitext 103 dataset, to a new dataset in such a manner that it does not forget what it previously learned

I highly encourage you to go through the original ULMFiT paper to understand more about how it works, the way Jeremy and Sebastian went about deriving it, and parse through other interesting details.

 

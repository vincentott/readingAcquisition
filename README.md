# reading-acquisition
Recycling of a Convolutional Neural Network for Reading Japanese Syllables: A Conceptual Replication of Hannagan et al. (2021)
  
A student project by Hanna F. Widhölzl, Maxim Zewe, and Vincent L. Ott

We built a convolutional neural network in PyTorch to model reading acquisition in humans. The model first learned to recognize objects and then learned to read handwritten Japanese hiragana syllables on top of that. We also explored (retroactive) catastrophic interference and found that object recognition was more robust to catastrophic interference than syllable recognition. It might be that catastrophic interference is weaker when learning a class of stimuli (hiragana syllables) that is simpler than what has previously been learned (objects).

see project_report for more info

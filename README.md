# FiGMaQ
**FiGMaQ** (**Fi**ne-**G**rained **M**ultimod**a**l **Q**uintuple dataset）


This dataset consists of a quintuple format in the form of `<reference image, reference caption, modification text, target image, target caption>`. Unlike traditional LLM-generated multimodal triplet datasets, our dataset introduces three key characteristics that distinguish it:

1. **Detailed Image Captions**: Each image is accompanied by a detailed caption that elaborates on various attributes of the image. These captions are typically longer than 100 tokens, offering a nuanced and rich description of the visual content, which enhances multimodal understanding.
2. **Rich Modification Text**: The modification text in this dataset provides a more precise description of changes made to the image. It is written in a more natural, human-like style, incorporating vague and imprecise terms, making it closer to how humans would describe adjustments or edits in everyday language.
3. **Quintuple Structure**: Unlike typical triplets, each sample in this dataset consists of five parts. This expanded format facilitates a wide range of fine-tuning tasks, including multimodal generation and retrieval, enabling diverse applications that require an integrated understanding of both images and text.

We will Release our data and code soon!


# word-embeddings

## Goal
Using BERT-trained contextual word embeddings, measure the similarity between certain relevant vocabulary words used in different subject tags. I will identify a subset of phrases or tags in both the English translation and the French text. Using these contextual embeddings, I would like to determine whether translation loss can be measured with word embeddings, and if so, what loss has been experienced in the translation of this manuscript. 

## Benefit to M&K
Considering the level of effort that was put into the translation process and specifically the effort that was taken to maintain the translator’s voice, this project will provide a potential metric for semantic faithfulness. The intratext vocabulary comparisons will provide an additional level of insight into the author-practitioner’s lexicon for different contexts. 

## Next Steps 
### Preliminary background research: 
* Review outstanding literature on BERT and translation loss 
* Review the manuscript and its translations/editions 
### Technological workflow:
* Google Collab with HuggingFace transformer library for BERT 
### Manuscript object: 
* What type of preprocessing needs to be done with the text 
* Narrow down examples to work with from within the manuscript 
* Some textual analysis 
* Develop more formal hypotheses about translation loss 

## References 
* “Ma<r>king and Knowing: Encoding BnF Ms. Fr. 640” https://edition640.makingandknowing.org/#/essays/ann_335_ie_19 
* “Turning Turtle: The Process of Translating BnF Ms. Fr. 640” https://edition640.makingandknowing.org/#/essays/ann_318_ie_19 
* “Principles of Encoding” https://edition640.makingandknowing.org/#/content/resources/principles 
* “Dicitionaries” https://edition640.makingandknowing.org/#/content/resources/principles#linguistic-resources-dictionaries-and-technical-encyclopedias 
* "Training Neural Machine Translation using Word Embedding-based Loss" https://arxiv.org/abs/1807.11219
* "Understanding BERT" https://www.techtarget.com/searchenterpriseai/definition/BERT-language-model#:~:text=BERT%20is%20an%20open%20source,surrounding%20text%20to%20establish%20context.
* "BERT Word Embeddings Tutorial" https://mccormickml.com/2019/05/14/BERT-word-embeddings-tutorial/

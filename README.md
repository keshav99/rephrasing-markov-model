# Corpus Rephrase using Markov Models



## Example Sentences

1. **Sentence:**  *we propose an architecture for vqa which utilizes recurrent layers to generate visual and textual attention*

​	**Sentence to be transformed to:** ['*vqa utilizes recurrent layers*', '*vqa generate visual and 	textual attention*']

[^Components]: <u>1.</u> (S (NP (PRP we)) (VP (VBP propose) (NP (NP (NP (DT an) (NN architecture)) (PP (IN for) **(NP (NN vqa))**)) (SBAR (WHNP (WDT which)) <u>2.</u> (S (VP **(VBZ utilizes)** **(NP (JJ recurrent) (NNS layers))** <u>3.</u> (S (VP (TO to) (VP (VB) (S (VP **(VB generate)** **(NP (ADJP (JJ visual) (CC and) (JJ textual)) (NN attention))**)))))))))))



2. **Sentence:**  *the memory characteristic of the proposed recurrent attention units offers a rich joint embedding of visual and textual features and enables the model to reason relations between several parts of the image and question*

​	**Sentence to be transformed to:** ['*Recurrent attention units offers visual and textual features*',  '*Recurrent attention units enables image and question*']

[^Components]: <u>1.</u> (S (NP (NP (DT the) (NN memory) (NN characteristic)) (PP (IN of) (NP (DT the) (VBN) VBN proposed) **(JJ recurrent) (NN attention) (NNS units)**))) (VP (VP **(VBZ offers)** (NP (NP (DT a) (JJ rich) (JJ joint) (NN embedding)) (PP (IN of) (NP (ADJP **(JJ visual) (CC and) (JJ) (JJ textual)) (NNS features)**)))) (CC and) <u>2.</u> (VP **(VBZ enables)** (NP (DT the) (NN model)) (S (VP (TO to) (VP (VB reason) (NP (NP (NNS relations)) (PP (IN between) (NP (NP (JJ several) (NNS) (NNS parts)) (PP (IN of) (NP (DT the) **(NN image) (CC and) (NN question)**)))))))))))



3. **Sentence:**  *our single model outperforms the first place winner on the vqa 1.0 dataset, performs within margin to the current state-of-the-art ensemble model*

​	**Sentence to be transformed to:** ['*Single model outperforms VQA 1.0 dataset*', '*Single model performs state-of-the-art ensemble model*']

[^Components]: (S (NP (PRP$ our) **(JJ single) (NN model)**) (VP (VP **(VBZ outperforms)** (NP (NP (DT the) (NML (JJ first) (NN place)) (NN) (NN winner)) (PP (IN on) (NP (DT the) (NML **(NN vqa) (CD 1.0)) (NN dataset)**)))) (, ,) (VP **(VBZ performs)** (PP (IN within) (NP (NN margin))) (PP (IN to) (NP (DT the) **(JJ current) (NML (NML (NN) (NN state)) (HYPH -) (PP (IN of) (HYPH -) (NP (DT the) (HYPH -) (NN art)))) (NN ensemble) (NN model))**))))



4. **Sentence:**  *we also experiment with replacing attention mechanisms in other state-of-the-art models with our implementation and show increased accuracy*

​	**Sentence to be transformed to:** ['*Replacing Attention mechanisms with state-of-the-art models*', '*Attention mechanisms show increased accuracy*']

[^Components]: (S (NP (PRP we)) (ADVP (RB also)) (VP (VP (VBP experiment) (PP (IN with) (S (VP **(VBG replacing)** (NP (NP **(NN attention) (NNS) (NNS mechanisms)**) (PP (IN in) (NP (JJ other) **(NML (NML (NN state)) (HYPH -) (PP (IN of) (HYPH -) (NP (DT the) (HYPH -) (NN art)))) (NNS models))**)) (PP (IN with) (NP (PRP$ our) (NN implementation))))))) (CC and) (VP **(VBP show)** (NP (VBN) **(VBN increased) (NN accuracy)**))))



5. **Sentence:**  *in both cases, our recurrent attention mechanism improves performance in tasks requiring sequential or relational reasoning on the vqa dataset*

​	**Sentence to be transformed to:** ['*Recurrent attention mechanism improves VQA dataset*', '*Recurrent attention mechanism improves sequential reasoning*', '*Recurrent attention mechanism improves relational reasoning*' ]

[^Components]: (S (PP (IN in) (NP (DT both) (NNS cases))) (, ,) (NP (PRP$ our) **(JJ recurrent) (NN attention) (NN mechanism)**) (VP **(VBZ improves)** (NP (NP (NN) (NN performance)) (PP (IN in) (NP (NP (NNS tasks)) (VP (VBG requiring) (NP (NP (ADJP **(JJ sequential)** (CC or) **(JJ relational)) (NN reasoning)**) (PP (IN on) (NP (DT the) **(NN vqa) (NN) (NN dataset)**)))))))))




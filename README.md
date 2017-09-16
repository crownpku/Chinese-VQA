# Chinese-VQA

Chinese Visual Question Answering 中文看图问答

## UNDER HEAVY DEVELOPMENT

### Downloads

Coco Pictures Train2014: http://cocodataset.org/#download

VGG16 Model: https://www.cs.toronto.edu/~frossard/post/vgg16/

Chinese VQA Text Data: http://idl.baidu.com/FM-IQA.html


### Problems

1.This is a very difficult problem combining both image and NLP. 

2.We do have a good Chinese VQA dataset (FM-IQA from Baidu). However the data is "free-style" labeled by humans, making it kind of noisy for processing (welcome to the real world!)

3.Current models usually uses categorical results for answering questions, but natural language generation as a seq2seq way should be much natural.

4.No high-quality open-sourced VQA code on github yet. Most state-of-art algorithms are coded in pytorch instead of tensorflow. Anyway, should I learn pytorch now, which according to many posts is much cooler?


### Related github projects

https://github.com/Cadene/vqa.pytorch

https://github.com/paarthneekhara/neural-vqa-tensorflow

https://github.com/JamesChuanggg/VQA-tensorflow

https://github.com/JamesChuanggg/awesome-vqa

https://github.com/pdollar/coco
Repo containing Latex code for BSc thesis "Unsupervised Deep Learning for Semantic Segmentation of Scientific 3D Images".

### Abstract 

Scientific imaging plays a major role in many clinical applications and biomedical studies. 
These scientific images must be analysed and often structures of interest need to be localised and labelled, a process called segmentation. 
Usually, domain experts are needed to manually annotate data sets in a time-consuming process. 
Fortunately, currently more and more unsupervised algorithms become available, which can be trained on data for which no ground truth is available.
However, most of the available unsupervised algorithms are optimised for photographs and applicability to high-resolution scientific images has not been shown.
The aim of this study thus was to investigate the applicability of the unsupervised algorithm “Self-supervised Transformer with Energy-based Graph Optimization (STEGO)” to high-resolution scientific imaging data, and to understand how to select and prepare scientific imaging data to be used successfully (if possible) with this algorithm.

For this the direct transferability of pretrained models was investig- ated, as well as the performance of models re-trained on a scientific data set, and the eﬀect of diﬀerent cropping schemes. 
Predicting a scientific data set with models trained on photographs did not yield satisfactory results. 
Even though the mean Intersection over Union (mIoU) values were in the same range as the mIoU of the validation set of the models (around 0.21-0.24), examining the raw predictions showed that labels were not retained sufficiently. 
When predictions were done on models trained with the same data set, mIoU improved significantly to about 0.5. 
Albeit some areas of the images could be segmented well, the obtained segmentations are not yet usable for quantitative scientific analysis. 
No definitive proposition regarding cropping regime could be made. 

Given that STEGO is an unsupervised algorithm, results are impressive. 
Further experiments, in particular a retraining of the backbone with a huge scientific data set, may even yield results fit for scientific analysis. 
Overall, unsupervised segmentation is a rapidly advancing field with promising results, even though this recent algorithm is not yet in a state suitable for scientific use-cases.

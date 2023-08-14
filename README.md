# Who are you referring to? Coreference resolution in image narrations

### Introduction

This is the code for the paper :

Arushi Goel, Basura Fernando, Frank Keller, Hakan Bilen,  Who are you referring to? Coreference resolution in image narrations, ICCV 23.

The webpage for this project is available [here](https://groups.inf.ed.ac.uk/vico/research/CIN/), with a link to the [paper](https://groups.inf.ed.ac.uk/vico/assets/pdf/Goel23.pdf) and [CIN dataset](https://drive.google.com/drive/folders/1p_v2Mnv_k5i7YsQkH1sbdRZnBn-yRYDB?usp=sharing). 

### License

The code and dataset are available for research purpose. 

### CIN Dataset

1. **Download the CIN dataset from [here](https://drive.google.com/drive/folders/1p_v2Mnv_k5i7YsQkH1sbdRZnBn-yRYDB?usp=sharing)** 

2. The folder contains the following files :
- **testval_annotations.json**: the json file has the following structure

```JSON
{
 "image": "image_id (flickr30k images)",
 "captions": "narration",
 "split": "test/val",
 "img_width": "int",
 "img_height": "int",
 "query": "list of phrases",
 "query_start_end": "list of start and end index for each phrase/query",
 "cluster": "list of cluster id for each phrase/query",
 "target_bboxes": "list of bounding boxes for each phrase/query (x,y,w,h)"

}
```
- **val_image_ids.json**: image ids for the flickr30k validation set of the [Localized Narratives dataset](https://google.github.io/localized-narratives/)
- **test_image_ids.json**: image ids for the flickr30k validation set of the [Localized Narratives dataset](https://google.github.io/localized-narratives/)
- **gold.zip**: gold/ground-truth coreference chain annotations for test/val in the CoNLL format


## Contact 

[goel.arushi@gmail.com](goel.arushi@gmail.com)



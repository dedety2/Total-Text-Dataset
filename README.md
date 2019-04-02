# Total-Text-Dataset

Updated on March 14, 2019 (Updated table ranking with evaluation protocol info.)

Updated on November 26, 2018 (Table ranking is included for reference.)

Updated on August 24, 2018 (Newly added [annotation tool](https://github.com/cs-chan/Total-Text-Dataset/tree/master/Annotation_tools) folder.)

Updated on May 15, 2018 (Added groundtruth in '.txt' format.)

Updated on May 14, 2018 (Added feature - 'Do not care' candidates filtering is now available in the latest python scripts.)

Updated on April 03, 2018 (Added pixel level groundtruth)

Updated on November 04, 2017 (Added text level groundtruth)

Released on October 27, 2017

## Table Ranking

- The results from recent papers on the Total-Text dataset are listed.

### Detection
<table>
    <thead align="center">
       <tr>
           <th rowspan=2>Method</th>
           <th colspan=3>Reported on paper</th>
           <th colspan=3>DetEval (tp=0.4, tr=0.8) (Default)</th>
           <th colspan=3>DetEval (tp=0.6, tr=0.7) (New Proposal) </th>
           <th rowspan=2>Published at</th>
        </tr>
        <tr>
            <th>Precision</th>
            <th>Recall</th>
            <th>F-measure</th>
            <th>Precision</th>
            <th>Recall</th>
            <th>F-measure</th>
            <th>Precision</th>
            <th>Recall</th>
            <th>F-measure</th>
        </tr>
    </thead>
    <tbody align="center">
        <tr>
           <td>FTSN <a href="https://arxiv.org/abs/1709.03272">[paper]</a> (*Pascal VOC IoU metric)</td>
           <td>84.7*</td>
           <td>78.0*</td>
           <td>81.3*</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>ICPR2018</td>
        </tr>
        <tr>
           <td>TextField <a href="https://arxiv.org/abs/1812.01393">[paper]</a></td>
           <td>81.2</td>
           <td>79.9</td>
           <td>80.6</td>
           <td>76.1</td>
           <td>75.1</td>
           <td>75.6</td>
           <td>83.0</td>
           <td>82.0</td>
           <td>82.5</td>
           <td>TIP2019</td>
        </tr>
        <tr>
           <td>CSE <a href="https://arxiv.org/abs/1903.08836">[paper]</a> <a href="https://arxiv.org/abs/1712.02170">[(^Polygon Regression)]</a></td>
           <td>81.4(80.9^)</td>
           <td>79.7(80.3^)</td>
           <td>80.2(80.6^)</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>CVPR2019</td>
        </tr>
        <tr>
           <td>MSR <a href="https://arxiv.org/abs/1901.02596">[paper]</a></td>
           <td>85.2</td>
           <td>73.0</td>
           <td>78.6</td>
           <td>82.7</td>
           <td>68.3</td>
           <td>74.9</td>
           <td>81.4</td>
           <td>72.5</td>
           <td>76.7</td>
           <td>arXiv:1901.02596</td>
        </tr>
        <tr>
           <td>TextSnake <a href="http://openaccess.thecvf.com/content_ECCV_2018/papers/Shangbang_Long_TextSnake_A_Flexible_ECCV_2018_paper.pdf">[paper]</a></td>
           <td>82.7</td>
           <td>74.5</td>
           <td>78.4</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>ECCV2018</td>
        </tr>
        <tr>
           <td>CTD <a href="https://www.sciencedirect.com/science/article/pii/S0031320319300664">[paper]</a></td>
           <td>74.0</td>
           <td>71.0</td>
           <td>73.0</td>
           <td>60.7</td>
           <td>58.8</td>
           <td>59.8</td>
           <td>76.5</td>
           <td>73.8</td>
           <td>75.2</td>
           <td>PR2019</td>
        </tr>
        <tr>
           <td>TextNet <a href="https://arxiv.org/abs/1812.09900">[paper]</a></td>
           <td>68.2</td>
           <td>59.5</td>
           <td>63.5</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>ACCV2018</td>
        </tr>
        <tr>
           <td>Mask TextSpotter <a href="http://openaccess.thecvf.com/content_ECCV_2018/papers/Pengyuan_Lyu_Mask_TextSpotter_An_ECCV_2018_paper.pdf">[paper]</a></td>
           <td>69.0</td>
           <td>55.0</td>
           <td>61.3</td>
           <td>68.9</td>
           <td>62.5</td>
           <td>65.5</td>
           <td>82.5</td>
           <td>75.2</td>
           <td>78.6</td>
           <td>ECCV2018</td>
        </tr>
        <tr>
           <td>CENet <a href="https://arxiv.org/abs/1901.00363">[paper]</a></td>
           <td>59.9</td>
           <td>54.4</td>
           <td>57.0</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>ACCV2018</td>
        </tr>
        <tr>
           <td>Textboxes <a href="https://arxiv.org/abs/1611.06779">[paper]</a></td>
           <td>62.1</td>
           <td>45.5</td>
           <td>52.5</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>AAAI2017</td>
        </tr>
        <tr>
           <td>EAST <a href="https://arxiv.org/abs/1704.03155">[paper]</a></td>
           <td>50.0</td>
           <td>36.2</td>
           <td>42.0</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>CVPR2017</td>
        </tr>
        <tr>
           <td>Baseline <a href="http://cs-chan.com/doc/ICDAR17.pdf">[paper]</a></td>
           <td>33.0</td>
           <td>40.0</td>
           <td>36.0</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>ICDAR2017</td>
        </tr>
        <tr>
           <td>SegLink <a href="https://arxiv.org/abs/1703.06520">[paper]</a></td>
           <td>30.3</td>
           <td>23.8</td>
           <td>26.7</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>-</td>
           <td>CVPR2017</td>
        </tr>
    </tbody>
</table>

Note:

1) For the results of TextField and CTD, the improved versions of their original paper were used, and this explains why the performance is better.

2) For Mask-TextSpotter, the relatively worse performance reported on their paper was due to a bug in the input reading module (which was fixed recently). The authors were informed about this issue.

### End-to-end Recognition (None refers to recognition without any lexicon; Full lexicon contains all words in test set.)
| Method     |  None (%)  |  Full (%)  |   Published at    |
|:--------:  | :-----:   | :----:      |    :-----:    |
|CNN+CTC [[paper]](https://www.sciencedirect.com/science/article/pii/S0925231219301870)     | 77.5     |  -    |      Neurocomputing2019         |
|TextNet [[paper]](https://arxiv.org/abs/1812.09900)     | 54.0     |  -    |      ACCV2018         |
|Mask TextSpotter [[paper]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Pengyuan_Lyu_Mask_TextSpotter_An_ECCV_2018_paper.pdf)  | 52.9     |  71.8      |    ECCV2018          |
|Textboxes [[paper]](https://arxiv.org/abs/1611.06779)        | 36.3     |  48.9       |         AAAI2017    |

(Note that these results are extracted from respective published papers. If your result is missing or incorrect, please do not hesisate to contact us.)

## Description

In order to facilitate a new text detection research, we introduce the Total-Text dataset [(ICDAR-17 paper)](https://arxiv.org/abs/1710.10400) [(presentation slides)](http://cs-chan.com/doc/TT_Slide.pdf), which is more comprehensive than the existing text datasets. The Total-Text consists of 1555 images with more than 3 different text orientations: Horizontal, Multi-Oriented, and Curved, one of a kind.

<img src="ttstatistics.png" width="100%">
<img src="ICDAR17.gif" width="50%">

## Citation
If you find this dataset useful for your research, please cite
```
@inproceedings{CK2017,
  author    = {Chee Kheng Ch’ng and
               Chee Seng Chan},
  title     = {Total-Text: A Comprehensive Dataset for Scene Text Detection and Recognition},
  booktitle = {14th IAPR International Conference on Document Analysis and Recognition {ICDAR}},
  pages     = {935--942},
  year      = {2017},
  doi       = {10.1109/ICDAR.2017.157},
}
```

## Feedback
Suggestions and opinions of this dataset (both positive and negative) are greatly welcome. Please contact the authors by sending email to
`chngcheekheng at gmail.com` or `cs.chan at um.edu.my`.

## License and Copyright
The project is open source under BSD-3 license (see the ``` LICENSE ``` file). Codes can be used freely only for academic purpose.

Copyright 2018, Center of Image and Signal Processing, Faculty of Computer Science and Information Technology, University of Malaya.



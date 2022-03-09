# Outlier Detection on NYC Taxi Trips

This is a sample [NYC Taxi Trips data](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page) labeled by our Outlier Detection algorithm `Doc`. See our paper: [Detecting outliers in data with correlated measures](https://dl.acm.org/doi/pdf/10.1145/3269206.3271798).

We release the outliers and non-outliers set described in Section 5.5 **Experiments on NYC Taxi**.

We visualized the trips in our human labeling system deployed to the DigitalOcean droplet for experienced taxi riders to flag outlier trips and to provide reasons to support their judgements.

In the file, we add few attributes in additional to the original trip features,

`sum_tis`: stores the aggregated score by our filters.
`label`: stores the ground truth flagged by the annotators. 


If you use this dataset, please consider citing the following paper:
```
@inproceedings{kuo2018detecting,
  title={Detecting outliers in data with correlated measures},
  author={Kuo, Yu-Hsuan and Li, Zhenhui and Kifer, Daniel},
  booktitle={Proceedings of the 27th ACM International Conference on Information and Knowledge Management},
  pages={287--296},
  year={2018}
}
```



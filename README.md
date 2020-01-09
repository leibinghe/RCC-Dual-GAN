# RCC-Dual-GAN: An Efficient Approach for Outlier Detection with Few Identified Anomalies


## Environment
- Python 3.5- Tensorflow (version: 1.0.1)- Keras (version: 2.0.2)

## Example to run the codes.
The instruction of commands has been clearly stated in the codes (see the parse_args function).

Run RCC-Dual-GAN:
```
python SO-GAAL.py --path_out Data/Stamps/out10.csv --path_unl Data/Stamps/unl10.csv --path_test Data/Stamps/test.csv
```


## More Details:
Use `python RCC-Dual-GAN.py -h` to get more argument setting details.

```shell
-h, --help	show this help message and exit--path_out	Input the path of the identified anomalies
--path_unl 	Input the path of the unlabeled data
--path_test 	Input the path of the test data--max_iter 	The maximum number of iterations
--nash_thr_1 	Threshold 1
--nash_thr_1 	Threshold 2```

## Dataset
We provide four real-world datasets: Pima, Stamps, Pageblocks and Optdigits in Data/

Update: January 9, 2020


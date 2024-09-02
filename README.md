# X-Copilot
This is the official implementation of X-Copilot.

## Setting：
* Clone this repo and prepare the environment.
```
git clone https://github.com/lab-sun/X-Copilot.git
cd X-Copilot
conda env create -f environment.yaml --name X-Copilot
conda activate X-Copilot
```

## Dataset
To download the dataset, please refers to: 

Download all the files and then extract them into the folder of `project_root/data/trainval/`


## Usage
* Clone this repo and prepare the environment.
* Download the dataset, create the foler `data/trainval/` in the project root, and release the dataset into the `/trainval/`.
* To pretrain/train the network, use the pre_train.py/train.py.
* To obatin the prediction results: 1) download the weight and put into the folder of `weight`; 2) use the predict.py.
* The link for the weight is: 

## Citation
If you found this code or dataset are useful in your research, please consider citing
```
...
```
If you have any questions, pleas feel free to contact us!

Contact: yx.sun@cityu.edu.hk; yuchao.feng@connect.polyu.hk

Website: https://yuxiangsun.github.io/

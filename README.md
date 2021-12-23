# 1190303503Xie_Xiaoxiao_ForCompulsoryCourse_No.2

## 1190303503 谢肖潇 必修 题目2

## 需求准备：

* PyTorch 1.0
* Python 3.9

## 使用方法：

* python train.py --help

## 用法示例:

* python train.py synthetic

## 复现论文代码:

* python train.py --queries 100000 --epochs 100 synthetic

* python train.py --queries 100000 --epochs 100 scale

* python train.py --queries 100000 --epochs 100 job-light

    上述分别对应三个workload.

## 如果你的python命名为 "python" 的话可直接点击：

* help.bat -> ```python train.py --help```

* run_test.bat -> ```python train.py synthetic```

* run_synthetic.bat -> ```python train.py --queries 100000 --epochs 100 synthetic```

* run_scale.bat -> ```python train.py --queries 100000 --epochs 100 scale```

* run_job-light.bat -> ```python train.py --queries 100000 --epochs 100 job-light```

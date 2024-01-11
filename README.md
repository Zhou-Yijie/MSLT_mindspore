# MSLT for Exposure Correction (mindspore实现)

## 运行环境
启智平台镜像mindspore2.0.0_cann6.3_notebook（NPU: 1*Ascend 910 32G）

## Train
```
python zisuanTrain.py --multi_data_url '[{"dataset_url":"obs://urchincache/attachment/9/d/9de6ff69-7f04-4bb6-9bf9-1b1ce05bc6bb/train.zip","dataset_name":"train.zip","containerPath":"/cache/dataset/train.zip","readOnly":true}]'
```
## Test
```
python infer.py
```

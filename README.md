# myYOLOv11
🚀 基于 `Tomato-Leaf-Disease-Detection` 数据集和 `YOLOv11` 实现番茄病检测

## 📌 项目简介
本项目使用 **YOLOv11** 进行 **番茄叶部病害检测**，基于 **Kaggle 数据集** 进行训练和微调。  
目标是利用 **深度学习** 提高番茄病害检测的准确率，为农业生产提供智能化解决方案。

---

## 📂 数据集下载
数据集来源于 Kaggle，可通过以下链接下载：  
[Tomato Leaf Disease Detection Dataset](https://www.kaggle.com/datasets/kpoviesistphane/tomato-leaf-disease-detection)

---
## 📊 Baseline 水平
| Model   | Precision | Recall | mAP@50 | mAP   |
| ------- | --------- | ------ | ------ | ----- |
| YOLOv11 | 0.877     | 0.856  | 0.93   | 0.825 |

---

## 🔄 微调过程
- **数据预处理**：增加数据增强，如翻转、随机裁剪、模糊等。
- **优化策略**：调整 `batch_size`、`learning_rate` 进行实验。

---

## 🎯 微调效果
| Model               | Precision | Recall | mAP@50 | mAP |
| ------------------- | --------- | ------ | ------ | --- |
| YOLOv11（Fine-tuned） | xx%       | xx%    | xx%    |     |


---

## 📸网页部署
已经将训练好的模型部署到了huggingface space当中，可以通过以下链接查看网页[tomatoleafdetect](https://ljwvv-tomatoleafdetect.hf.space/?__theme=system)
![image](https://github.com/user-attachments/assets/a41fc719-ac4b-4b77-9eeb-24a6098d03aa)






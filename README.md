# 生成对抗网络生成人脸



## 项目介绍

在这个项目中，我们会通过 DCGANs 来生成人脸，经过前面的学习，我们已经了解到了生成对抗网络的原理，下面我们就会用到我们所学的知识来完成这个项目。



## 数据下载

Celeba 是一个人脸的数据集，可以通过[百度云](https://pan.baidu.com/s/1mF8nl2zkCKpj8W0GIeX-7A)进行下载

数据下载完成之后，将本仓库下载到本地，同时将刚刚下载的 `celeba.zip` 放到仓库的主目录中

打开终端，进入到仓库目录，运行 Python 脚本

```bash
python get_data.py
```

**上面的数据解压可能会需要一点时间**

通过上面的过程，我们准备好了数据，如果你已经根据 [StartKit](https://github.com/sharedeeply/DeepLearning-StartKit) 配置好了深度学习环境，那么你可以直接进入 `dcgan_generate_face.ipynb` 完成项目，否则你需要根据 StartKit 配置你的深度学习环境。



## 评估与提交

通过 `dcgan_generate_face.ipynb` ，你能够生成一系列的人脸图片，将这个 notebook 保存并提交给我们。

除此之外，你还需要提交

- notebook 导出的 html 文件

可以考虑在 Github 上为该项目创建一个仓库，记录训练的过程、所使用的库以及数据等的 README 文档，构建一个完善的 Github 简历。
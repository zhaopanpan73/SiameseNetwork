# SiameseNetwork
<font face="微软雅黑" size=16 >**最近对孪生网络比较感兴趣、所以学习了一个孪生网络的一个小Demo**</font>

**文件列表**:
* **`run.py` : 运行的接口.**
* **`inference.py` :  网络结构和损失函数，你可以按照你的意愿修改**
* **`visualize.py` : 用来数据的可视化.**

**可以选择的运行方式：**

```markdown
$ python run.py
```
**Attention：**
* **运行以上命令后会自动下载MNIST数据集，下载一次后，以后再运行该代码将不需要再下载。**
* **在运行过程中，程序将会周期性的保存模型（model.cpkt）**
* **当执行 python run.py这个命令时，你可以选择是否load这些模型，yes:表示load上次保存的模型，然后显示此模型运行的结果，这样就可以实时随地的查看上一次训练的结果了**

**选择截图:**

```markdown
$ python run.py
We found model.ckpt file. Do you want to load it [yes/no]? yes
```
**Wish you have a nice day!**


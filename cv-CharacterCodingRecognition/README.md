## 使用方法

可以在dataset中用sh脚本下载数据，下载完我们的数据后

首先配置我们的环境，我的环境是python3.7，这个应该无所谓，不过有一部分，我发现在torch1.10+是无法复现效果的，在运行的时候，我们的损失会非常差，所以torch版本一般是1.9.1，1.8.1等



```python
pip install -r requirements.txt
```



之后，我们可以直接运行我们的baseline.py即可

```python
python baseline.py
```



如果想看到更全面的训练过程，也可以通过ipynb看运行过程和方法，就能更好的解决问题。
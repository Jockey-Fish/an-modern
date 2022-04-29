# Transformer   Pytorch实现的简单古今机器翻译
## 部分机器翻译结果
``` bash
BOS 睿 具 陈 本 末 。 EOS
BOS 睿 就 一 五 一 十 地 进 行 了 报 告 。 EOS
translation: 睿 就 一 五 一 十 地 进 行 了 报 告 。

BOS 狗 则 饲 以 粱 肉 。 EOS
BOS 以 珍 贵 的 食 物 养 狗 。 EOS
translation: 狗 就 用 肉 把 肉 食 肉 养 狗 。

BOS 城 不 没 者 三 板 。 EOS
BOS 长 社 城 涌 进 了 很 多 的 水 。 EOS
translation: 长 社 城 涌 进 了 很 多 的 水 。

BOS 如 其 语 ， 捕 获 之 。 EOS
BOS 按 她 说 的 话 ， 抓 获 了 这 个 人 。 EOS
translation: 按 他 的 话 ， 抓 获 了 这 个 人 。

BOS 由 是 睿 及 士 开 皆 侧 目 。 EOS
BOS 因 此 直 数 和 和 士 开 都 对 他 含 恨 斜 视 。 EOS
translation: 因 此 直 数 和 和 士 开 都 对 他 含 恨 斜 视 。

BOS 言 未 卒 ， 呜 咽 不 自 胜 。 EOS
BOS 话 还 没 有 说 完 ， 又 情 不 自 禁 地 哭 了 起 来 。 EOS
translation: 话 还 没 有 说 完 ， 又 情 不 自 禁 地 哭 了 起 来 。

BOS 遂 至 消 液 ， 竟 不 一 尝 。 EOS
BOS 他 统 统 地 让 给 了 兵 士 们 ， 而 自 己 则 未 尝 一 滴 。 EOS
translation: 于 是 走 了 回 家 ， 始 终 不 曾 有 一 点 。
```

## 训练自己的数据集
### 1. 按照data中train.txt所示格式准备数据集
英文与中文使用\t进行分割。
### 2. 开始训练
运行：
``` bash
python train.py
```
## 开始翻译
将训练好的模型，放置在data文件夹下。修改utils.utils_transformer中的model_path路径。
在translate.py文件下输入需要翻译的英文语句，运行：
``` bash
python translate.py
```

## 批量化测试
将训练好的模型，放置在data文件夹下。修改evaluate中的model_path路径。运行：
``` bash
python evaluate.py
```

## Reference
https://github.com/hinesboy/transformer-simple
# an-modern
# an-modern
# an-modern
# an-modern
# an-modern

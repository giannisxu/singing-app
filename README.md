# 唱歌 App 试用版

测一下你的音域，告诉你曲库里每首歌能不能唱、KTV 伴奏该升还是降、你该唱哪个八度。

在线使用：https://giannisxu.github.io/singing-app/

手机上用 Safari 或 Chrome 打开，再「添加到主屏幕」，就能全屏使用、直接录音。

- 录音只在你的设备上分析，不会上传到任何地方。
- 推荐和测音域的算法和 songbank 的 Python 引擎一致（逐项比对过）。

## 数据

曲库统计的一部分来自 M4Singer 数据集（Zhang et al., "M4Singer: A Multi-Style, Multi-Singer and Musical Score Provided Mandarin Singing Corpus", NeurIPS 2022 Datasets and Benchmarks），许可证 CC BY-NC-SA 4.0，只能非商业使用。这里只用了每句的最高音、最低音和每个音高唱了多少秒，不含歌词和旋律；index.html 里内嵌的曲库数据按同样的许可证提供。M4Singer 的版本是数据集歌手的清唱，调不一定和原唱一样。

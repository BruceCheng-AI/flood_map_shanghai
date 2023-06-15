![洪水风险反演](https://github.com/BruceCheng-AI/flood_map_shanghai/blob/main/results/%E6%B4%AA%E6%B0%B4%E9%A3%8E%E9%99%A9%E5%8F%8D%E6%BC%94_5.gif)
# Typhoon 9711 Flood Risk Inversion Study in Shanghai

This repository contains notebooks and data necessary to perform an in-depth study on flood risk in Shanghai, based on data gathered from Typhoon 9711. It is crucial to understand how past typhoons have affected the area in order to plan and prepare for future events. 

## Repository Structure

- `data_process.ipynb`: This notebook processes wind speed, submersion, and tide data. The wind speed data is handled in vector form, while the submersion and tide information is processed using contourf format. The data preparation stage is an essential step to further analyze and visualize the effects of Typhoon 9711.

- `map_ipynb`: This notebook generates an interactive flood risk map of Shanghai. It uses a topographic image of Shanghai as the base, onto which the processed data is layered. This visualization will provide a clear and dynamic image of the risks associated with such a typhoon.

## Usage

In order to run these notebooks, ensure you have the necessary Python libraries installed and run the following commands in your terminal:

```
git clone https://github.com/BruceCheng-AI/flood_map_shanghai.git
cd flood_map_shanghai
jupyter notebook
```

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/BruceCheng-AI/flood_map_shanghai).

## Show your support

Give a ⭐️ if this project helped you!

# 上海9711号台风洪涝风险反演研究

这个仓库包含了进行上海9711号台风洪涝风险反演研究所需的笔记本和数据。理解过去台风对地区的影响，对于规划和准备未来的事件至关重要。

## 仓库结构

- `data_process.ipynb`：这个笔记本处理风速、淹没、和潮位数据。风速数据以矢量形式进行处理，而淹没和潮位信息则采用等高线（contourf）格式进行处理。数据准备阶段是进一步分析和可视化9711号台风影响的必要步骤。

- `map_ipynb`：这个笔记本生成了上海的洪涝风险交互地图。地图以上海的地形图片为基础，上面覆盖了处理后的数据。这种可视化方式将清晰地展示出台风带来的风险。

## 使用方法

为了运行这些笔记本，确保您已安装必要的Python库，然后在终端运行以下命令：

```
git clone https://github.com/BruceCheng-AI/flood_map_shanghai.git
cd flood_map_shanghai
jupyter notebook
```

## 贡献

欢迎您的贡献，问题和功能请求！随时查看 [问题页面](https://github.com/BruceCheng-AI/flood_map_shanghai)。


## 表示支持

如果这个项目对你有所帮助，给我们一个 ⭐️ 吧！

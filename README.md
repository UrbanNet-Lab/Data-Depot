# Data Depot

成都地铁站点研究所用的客观环境数据，按原始数据类别存放：

| 目录 | 内容 |
| --- | --- |
| `osm路网数据/` | OpenStreetMap 道路 Shapefile 文件 |
| `成都市20242025灯光数据/` | 2024 年和 2025 年夜间灯光 HDF5 文件及数据来源 |
| `房价数据....链家/` | 链家房价数据、站点周边房价指标与保存的公开网页 |
| `高德api获取数据/` | 地铁站、POI、道路和出入口的高德 API 查询结果 |

大型 Shapefile 和夜光文件使用 Git LFS。完整下载请先安装 Git LFS，再运行：

```powershell
git lfs install
git clone https://github.com/UrbanNet-Lab/Data-Depot.git
```

各目录内的数据来源和字段说明以相应的说明文件为准。

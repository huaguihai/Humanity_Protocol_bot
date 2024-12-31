# 自动领取$RWT奖励的Humanity Protocol机器人

[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/huaguihai/Humanity_Protocol_bot)

## 介绍
本机器人用于自动从Humanity Protocol每日领取$RWT奖励，支持多个钱包同时操作。它设计简单，易于设置和使用。

## 开始使用

按照以下步骤在本地机器上设置并运行本机器人。

## 贡献指南

欢迎贡献代码！请遵循以下步骤：

1. Fork 本仓库
2. 创建新的分支 (`git checkout -b feature/YourFeatureName`)
3. 提交更改 (`git commit -m 'Add some feature'`)
4. 推送到分支 (`git push origin feature/YourFeatureName`)
5. 创建Pull Request

## 许可证

本项目采用 MIT 许可证 - 详情请参阅 [LICENSE](LICENSE) 文件

### 1. 克隆仓库

首先，使用Git将本仓库克隆到本地机器：

```bash
git clone https://github.com/vinskasenda/HumanityTestnet-Bot.git
```

### 2. 进入克隆的文件夹

导航到仓库克隆的文件夹：

```bash
cd HumanityTestnet-Bot
```

### 3. 创建private_keys.txt文件
在项目的根目录下创建一个private_keys.txt文件。该文件应每行包含一个私钥，如下所示：

```python
private_key_1
private_key_2
private_key_3
...
```

### 4. 安装所需依赖
确保系统已安装Python。然后使用requirements.txt文件安装所需依赖：

```bash
pip install -r requirements.txt
```

### 5. 运行机器人
一切设置完成后，可以使用以下命令运行机器人：

```bash
python3 bot.py

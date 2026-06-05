# 书单工作流 / Book List Workflow

Coze（扣子）书单视频自动化工作流集合。

## 工作流说明

### 书单工作流1 — book
- 基础书单视频生成工作流
- 输入书名后自动生成书单视频

### 书单工作流2 — book1
- 书单解说视频工作流（S100视频工作流）
- 一键生成"海林爱读书"风格的书单解说视频

## 使用方法

### 导入到 Coze 平台

1. 打开 https://code.coze.cn
2. 进入工作空间 → 工作流
3. 点击「导入」
4. 选择对应的 `.yaml` 文件导入
5. 根据需求配置 API Key 等参数

### 直接下载

```bash
git clone https://github.com/7464864/book-list.git
```

## 文件结构

```
book-list/
├── README.md
└── 书单工作流1-book/
    ├── MANIFEST.yml
    └── workflow/
        └── book-draft.yaml
└── 书单工作流2-book1/
    ├── MANIFEST.yml
    └── workflow/
        └── book1-draft.yaml
```

## 许可证

MIT

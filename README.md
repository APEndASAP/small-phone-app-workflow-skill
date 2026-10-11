# small-phone-app-workflow-skill

通用小手机 App 开发协作监督流程 —— 一份可安装的 AI Skill。

> 作者：蓝色鸽子窝（小红书：1139353519）

## 这是什么

一份规范 AI 与你协作开发「小手机 App」全过程的 Skill。覆盖需求、方案、审批、开发、修改、验证、交付、bug 排查等环节，核心目标是让 AI 遵守你的协作纪律：

- 需求先读全、不懂就问
- 方案先审批、批准后才开发
- 开发最小修改、不越权
- bug 排查要证据、不甩锅
- 上下文保鲜、不跑偏

通用规范，不绑定任何具体项目。

## 安装

### 方式一：直接复制

把整个目录复制到你的 skills 目录：

```
~/.workbuddy/skills/small-phone-app-development-workflow/
```

复制后，`SKILL.md` 即可被识别为可用的 Skill。

### 方式二：克隆仓库

```bash
git clone https://github.com/APEndASAP/small-phone-app-workflow-skill.git \
  ~/.workbuddy/skills/small-phone-app-development-workflow
```

## 目录结构

```
small-phone-app-workflow-skill/
└── SKILL.md    # Skill 主文件
```

## 版本

- v1.0

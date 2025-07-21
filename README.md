# Scoop Bucket

这是一个自定义的 Scoop bucket，包含了一些实用的 Windows 应用程序。

## 如何添加这个 bucket

```powershell
scoop bucket add rocklerson-bucket https://github.com/rocklerson/scoop-bucket
```

## 包含的应用程序

### sedentary-reminder - 久坐提醒工具

PC端久坐提醒小工具，帮助您养成健康的工作习惯。

**安装方法：**
```powershell
scoop install sedentary-reminder
```

**功能特点：**
- 定时提醒久坐用户起身休息
- 工作时间结束后强制锁定屏幕
- 支持系统托盘运行
- 支持 Windows 7/10 系统
- 可自定义工作时间和休息时间

**使用说明：**
1. 启动程序后，设置工作时间和休息时间
2. 点击'开始'按钮开始倒计时
3. 工作时间结束后会强制锁定屏幕进行休息
4. 支持系统托盘运行，可最小化到后台

**注意事项：**
- 程序会在休息时间屏蔽鼠标和键盘输入（保留Ctrl+Alt+Del组合键）
- 建议在开始工作前启动程序

### anx-reader - 跨平台电子书阅读器

**安装方法：**
```powershell
scoop install anx-reader
```

### sakura-editor - サクラエディタ

**安装方法：**
```powershell
scoop install sakura-editor
```

## 更新应用程序

```powershell
scoop update sedentary-reminder
```

或者更新所有应用程序：

```powershell
scoop update *
```

## 卸载应用程序

```powershell
scoop uninstall sedentary-reminder
```

## 贡献

欢迎提交 Pull Request 来添加更多有用的应用程序到这个 bucket。

## 许可证

本 bucket 中的 manifest 文件遵循各自应用程序的许可证。

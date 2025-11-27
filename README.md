# 生日快乐 - 李艳老婆

这是一个为李艳老婆准备的生日祝福网页，包含了精美的动画效果和互动功能。

## 功能特点

- 🎵 自动播放生日祝福音乐
- 💬 30条专属生日祝福语气泡
- 🎨 精美的粒子效果和动画
- 📱 响应式设计，支持手机端访问
- 🔒 密码保护功能
- ❤️ 互动爱心特效
- 🎉 彩带动画效果

## 访问方式

### 本地访问
1. 使用浏览器直接打开 `未命名.html` 文件
2. 或者启动本地HTTP服务器：
   ```bash
   python -m http.server 8000
   ```
   然后在浏览器中访问 `http://localhost:8000/%E6%9C%AA%E5%91%BD%E5%90%8D.html`

### 局域网访问
1. 确保设备和电脑在同一局域网内
2. 启动HTTP服务器：
   ```bash
   python -m http.server 8000 --bind 0.0.0.0
   ```
3. 在浏览器中访问 `http://<电脑IP地址>:8000/%E6%9C%AA%E5%91%BD%E5%90%8D.html`

### 外网访问
1. 配置路由器端口映射，将外部端口8000映射到内部IP地址的8000端口
2. 在浏览器中访问 `http://<公网IP地址>:8000/%E6%9C%AA%E5%91%BD%E5%90%8D.html`

## 密码

默认密码：1021

## 技术栈

- HTML5
- CSS3
- JavaScript
- Tailwind CSS
- Font Awesome
- GSAP 动画库

## 项目结构

```
.
├── README.md          # 项目说明文档
└── 未命名.html        # 主HTML文件
```

## 浏览器兼容性

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 开发说明

### 修改密码
在 `未命名.html` 文件中找到以下代码并修改密码：

```javascript
if (passwordInput.value === '1021') {
    // 密码正确，进入下一页
}
```

### 添加祝福语
在 `未命名.html` 文件中的 `birthdayMessages` 数组中添加新的祝福语：

```javascript
const birthdayMessages = [
    "新的祝福语...",
    // 更多祝福语
];
```

## 许可证

MIT License

## 作者

爱你的老公
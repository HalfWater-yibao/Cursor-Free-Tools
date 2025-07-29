# Cursor Tools 免费一键续杯

## 🌟 主要功能

- **📊 使用情况查询**: 查看Cursor账户的使用统计信息
- **🌐 快速访问Dashboard**: 一键打开Cursor官方Dashboard
- **🚀 一键重置**: 完整的账户重置功能，包括机器ID和认证信息


<img width="406" height="582" alt="image" src="https://github.com/user-attachments/assets/2e09bf28-2841-47fa-96db-86e018ceb316" />


### 安装步骤（目前支持只MAC系统）

1. 从 [Releases] 页面下载
2. 解压下载的文件双击打开
3. 打开隐私与安全性 设置权限


## 🚀 使用方法

### 1. 获取Session Token

在使用工具前，你需要先获取Cursor的Session Token：

1. 打开浏览器，访问 [cursor.com](https://cursor.com)
2. 登录你的Cursor账户
3. 打开浏览器开发者工具（F12）
4. 切换到 **Application** 或 **存储** 标签
5. 在左侧菜单中找到 **Cookies** → **https://cursor.com**
6. 找到名为 `WorkosCursorSessionToken` 的Cookie
7. 复制其 **Value** 值（这就是你的Session Token）

### 2. 配置Token

1. 启动Cursor Tools
2. 将复制的Session Token粘贴到Token输入框中
3. 点击 **💾 保存** 按钮

### 3. 功能使用

#### 📊 查看使用情况
- 点击 **📊 使用情况** 按钮
- 查看账户使用统计和模型调用记录


#### 🌐 打开Dashboard
- 点击 **打开官网** 按钮
- 自动在浏览器中打开Cursor Dashboard
- 可以在网页中查看详细的使用情况

#### 🚀 一键重置
- 点击 **🚀 一键重置** 按钮
- 自动执行完整的账户重置流程
- 包括生成新的机器ID和更新认证信息


## 🔒 安全特性

- **本地处理**: 所有操作都在本地执行，Token不会上传到任何服务器
- **会话存储**: Token仅在程序运行期间保存在内存中
- **隐私保护**: 不收集任何用户数据

## ⚠️ 注意事项

1. **Token安全**: 请妥善保管你的Session Token，不要分享给他人
3. **网络要求**: 需要稳定 科学 的网络连接
4. **系统权限**: 重置功能可能需要管理员权限


**免责声明**: 本工具仅供学习和研究使用，使用本工具所产生的任何后果由使用者自行承担。

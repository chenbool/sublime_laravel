# sublime_laravel

> Sublime Text 语法提示插件，支持 Laravel 框架

## 功能特性

| 特性 | 说明 |
|------|------|
| 代码片段 | 130+ 个代码片段 |
| 完整覆盖 | 覆盖 Laravel 核心功能 |
| 智能提示 | 支持 Tab 键快速补全 |
| 调试函数 | 内置常用调试方法 |

## 安装

### Sublime Text 安装

1. 打开 Sublime Text
2. 按 `Ctrl+Shift+P` 打开命令面板
3. 输入 `Package Control: Install Package`
4. 搜索 `laravel` 并安装

### 手动安装

将项目克隆到 Sublime Text 的 Packages 目录：

```bash
git clone https://github.com/chenbool/sublime_laravel.git
```

## 代码片段总览

| 分类 | 数量 | 说明 |
|------|------|------|
| Controller | 2 | 控制器 |
| Model | 1 | 模型 |
| DB | 40 | 数据库操作 |
| Route | 15 | 路由配置 |
| Request | 12 | 请求对象 |
| Middleware | 3 | 中间件 |
| Cache | 3 | 缓存 |
| Session | 2 | Session |
| Cookie | 1 | Cookie |
| Log | 4 | 日志 |
| View | 8 | 视图 |
| Auth | 6 | 认证 |
| Event | 4 | 事件 |
| Queue | 2 | 队列 |
| Mail | 1 | 邮件 |
| File | 6 | 文件操作 |
| Validate | 1 | 验证器 |
| Relation | 6 | 关联关系 |
| Provider | 3 | 服务提供者 |
| Resource | 1 | 资源 |
| Observer | 1 | 观察者 |
| Service | 1 | 服务 |
| Bug | 1 | 调试 |
| URL | 1 | URL |

## 使用示例

```php
// 数据库查询
User::where('id', 1)->first();

// 路由
Route::get('/user', 'UserController@index');

// 中间件
Route::middleware('auth')->get('/home', 'HomeController@index');

// 事件
event(new UserRegistered($user));
```

## 相关项目

| 项目 | 仓库地址 |
|------|----------|
| sublime_swoole | https://github.com/chenbool/sublime_swoole |
| sublime_yaf | https://github.com/chenbool/sublime_yaf |
| sublime_thinkphp5 | https://github.com/chenbool/sublime_thinkphp5 |
| sublime_thinkphp6 | https://github.com/chenbool/sublime_thinkphp6 |
| sublime_thinkphp8 | https://github.com/chenbool/sublime_thinkphp8 |
| sublime_laravel | https://github.com/chenbool/sublime_laravel |
| sublime_workerman | https://github.com/chenbool/sublime_workerman |
| sublime_webman | https://github.com/chenbool/sublime_webman |
| sublime_fastadmin | https://github.com/chenbool/sublime_fastadmin |

## License

MIT License

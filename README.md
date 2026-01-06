# site

## 使用说明

### 如何添加新网站？

您可以通过编辑HTML代码中的网站卡片部分来添加自己的网站链接。每个网站卡片的结构如下：

```html
<a href="https://目标网站地址" target="_blank" class="card-hover">
    <div class="bg-white rounded-xl shadow-lg p-6 text-center border border-gray-100">
        <div class="w-16 h-16 bg-颜色-100 rounded-full flex items-center justify-center mx-auto mb-4">
            <i class="fa fa-图标名称 text-颜色-600 text-2xl"></i>
        </div>
        <h3 class="font-semibold text-gray-800 mb-2">网站名称</h3>
        <p class="text-sm text-gray-500">网站地址</p>
    </div>
</a>
```

### 需要修改的部分：
1. `href="https://目标网站地址"` - 替换为您要添加的网站URL
2. `bg-颜色-100` - 选择图标背景颜色（如：bg-blue-100、bg-green-100等）
3. `fa fa-图标名称` - 选择合适的Font Awesome图标
4. `text-颜色-600` - 图标颜色
5. `网站名称` - 显示的网站名称
6. `网站地址` - 显示的网址

### 可用的图标颜色：
- blue (蓝色)
- green (绿色) 
- red (红色)
- orange (橙色)
- pink (粉色)
- purple (紫色)
- gray (灰色)

这个导航页面非常适合作为浏览器首页，让您快速访问常用网站。所有代码都保持了简洁性，方便您随时编辑和扩展。

# vue_third_5_19

本项目实现的功能：<br>
1、良好的排版与布局：<br>
                    将项目分为三个子组件开发，分为顶栏、地图、信息栏，
                    整体绿色系色彩搭配，和谐一致<br>
2、功能丰富：<br>
            顶栏：<br>
            （1）图片logo组合文字，具有特色<br>
            （2）设置超链接，点击标题可访问esri官网，介绍GIS<br>
            地图：<br>
            （1）多种图源url切换底图<br>
            （2）显示指针经纬度信息，当前比例尺<br>
            （3）放大到一定级别，显示地科院的相关图片，点击可放大查看<br>
            （4）指针移动到地科院区域，可显示信息栏中，关于地科院的详细新闻内容<br>
            信息栏：<br>
            （1）地科院logo组合文字，作为标题，突出主题<br>
            （2）新闻标题、图片、新闻内容依次呈现，展示地科院近期新闻<br>
            （3）底部按钮，可手动切换地科院新闻，实现动态切换的功能<br>
            （4）相关标题、新闻均设有超链接，点击即可详细访问地科院相关栏目内容<br>
3、代码部分：<br>
            （1）三个子组件包含于父组件中，父组件作为中介，协调子组件通讯<br>
                事件挂接、处理，均在父组件中进行，后续方便项目维护和扩展升级<br>
            （2）地图组件中，使用openlayers库，进行地图交互与逻辑判断<br>
























![QQ_1749805252857](https://github.com/user-attachments/assets/c3158c5b-ebae-4060-bd9d-4107a00872a7)

This template should help get you started developing with Vue 3 in Vite.





## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Customize configuration

See [Vite Configuration Reference](https://vite.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

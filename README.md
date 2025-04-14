# introduction
fork 自 https://github.com/6DDUU6/genshin-impact-picker

进行了修改，为了解决我的一个教师朋友的需求：
1. 每次抽名字出的颜色跟星星数量都是随机的，想要固定为五星和金色。(参考`./webdocs/docs/users/configure.md`)
2. 除了第一个池子，后面的池子就是抽卡模拟游戏，放到教室电脑里学生会玩，想要删掉后面的池子。(见`./Genshin-Impact-Wish-Simulator/src/lib/helpers/banner-loader.js`的97行)


# dev
<!-- ## 1. 修改页面 -->
1. cd Genshin-Impact-Wish-Simulator
2. npm install
3. npm run dev
4. 修改逻辑
5. `npm run tauri build` (为减少构建大小，使用tauri构建，尽量用win开发，提前创建C:\Users\xx\AppData\Local\tauri，需要先按照[tauri-Prerequisites](https://v1.tauri.app/v1/guides/getting-started/prerequisites/)配置环境`)
<!-- 7. 然后将生成的目录 `.vercel/output/static` 手动拷贝为 `electron-static/static` 目录，覆盖原有文件。 -->

<!-- ## 2. 打包为桌面端
1. cd electron-static
2. `npm install`(如果在执行`npm install`时出现了electron相关的错误，可参考[这篇文章](https://blog.csdn.net/qq_45634593/article/details/145496892)的方法来修改针对electron的镜像源)
3. npm run build-win -->

# 使用建议
1. 在问号的选项里开启unlimited，无限抽卡
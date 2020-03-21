## 组件

1. [react-sortable-hoc -- 触摸有好、可排序的列表](https://github.com/clauderic/react-sortable-hoc)
2. [react-virtualized -- react 组件高效渲染大型列表和表格数据](https://github.com/bvaughn/react-virtualized)
3. [react-table -- React 的轻量级，快速和可扩展的数据网格](https://github.com/react-tools/react-table)

   [demo](https://react-table.js.org/#/story/simple-table)

4. [hocs -- React 和 React Native 的高阶组件集合](https://github.com/deepsweet/hocs)
5. [rifm -- React Input Format＆Mask，微小（≈650b）组件，用于将任何输入组件转换为格式化或屏蔽输入](https://github.com/istarkov/rifm)
6. [react-loadable -- 用于加载具有 promise 的组件的更高阶组件。](https://github.com/jamiebuilds/react-loadable)
7. [react-window -- React 组件，用于有效地呈现大型列表和表格数据](https://github.com/bvaughn/react-window)

   [官网](https://react-window.now.sh/#/examples/list/fixed-size)

8. [zhui -- 一款带有中国风的 React 组件库](https://github.com/zhui-team/zhui) 感觉还是蛮酷的，超美

   [官方文档](https://inspiring-bardeen-426f2e.netlify.com/card)

## 地图

1. [rc-bmap -- 当百度地图遇上 React，会产生怎样的火花 🔥 🎉 欢迎您的加入](https://github.com/jser-club/rc-bmap)

   [官网](https://bmap.jser-club.com/)

## 数据可视化

1. [react-vis -- uber 开发的数据可视化组件](https://uber.github.io/react-vis/)

[官网](https://uber.github.io/react-vis/)
![demo](https://github.com/uber/react-vis/raw/master/docs/assets/react-vis.gif?raw=true)

## ssr

1. [after.js -- 类似 Next.js，使用 React Router 4 构建的 ssr React 应用程序的框架](https://github.com/jaredpalmer/after.js)
2. [rogue -- SSR for React 是不可见的（零配置！ - 只需要一个 App.js）和快速（没有 Webpack！ - Parcel <3）](https://github.com/alidcastano/rogue)

## node

1. [node-glob -- node 中 glob 模式下路径匹配](https://github.com/isaacs/node-glob)

```js
var glob = require("glob");

// options is optional
glob("**/*.js", options, function(er, files) {
  // files is an array of filenames.
  // If the `nonull` option is set, and nothing
  // was found, then files is ["**/*.js"]
  // er is an error object or null.
});
```

2. [antcloud-node-stack -- 蚂蚁金融科技官方 Node 技术栈脚本](https://github.com/alipay/antcloud-node-stack)

## ui

1. [wired-elements -- 一系列具有手绘外观的基本 UI 元素。这些可用于线框，模型，或只是有趣的手绘外观。](https://github.com/wiredjs/wired-elements)

   ![demo](https://camo.githubusercontent.com/d06779580c38ad9fc939c7599f4623598a5e6b98/68747470733a2f2f692e696d6775722e636f6d2f717474506c6c672e706e67)

2. [evergreen -- 分段的 Evergreen React UI 框架](https://github.com/segmentio/evergreen)
   [文档](https://evergreen.segment.com/components/)

## 控件

1. [react-smooth-dnd -- 用 react 写的 dnd](https://github.com/kutlugsahin/react-smooth-dnd)

   [官网](https://kutlugsahin.github.io/smooth-dnd-demo/)

2. [react-dates -- 一个易于国际化，易于移动的网页日期选择器库](https://github.com/airbnb/react-dates)

   ![demo](https://raw.githubusercontent.com/airbnb/react-dates/master/react-dates-demo.gif)

3. [react-awesome-slider -- ReactJS 60fps 轻量级高性能组件，可呈现 UI 图像/媒体画廊滑块的一组动画。](https://github.com/rcaferati/react-awesome-slider)

   ![demo](https://github.com/rcaferati/react-awesome-slider/raw/master/demo/public/images/demo-bojack-mobile.gif)

4. [用于滚动，缩放和突出显示代码的反应组件<🏄/>](https://github.com/pomber/code-surfer)

   ![demo](https://raw.githubusercontent.com/pomber/code-surfer/master/other/sample.gif)

5. [react-modal-experiment -- 用于移动端的全屏表单 react 组件](https://github.com/stereobooster/react-modal-experiment)

   ![demo](https://camo.githubusercontent.com/7829b2dcc921447e750e09e8316930e30c596c9e/68747470733a2f2f74686570726163746963616c6465762e73332e616d617a6f6e6177732e636f6d2f692f646274366d6f6f677076336b717570326b3077652e676966)

6. [react-jsonschema-form -- 用于从 JSON Schema 构建 Web 表单的 React 组件。](https://github.com/mozilla-services/react-jsonschema-form)
7. [formal -- react hooks 时代的优雅跨平台表单管理原语。](https://github.com/kevinwolfcr/formal)

```jsx
import React from "react";
import useFormal from "@kevinwolf/formal";

const initialValues = {
  firstName: "Tony",
  lastName: "Stark",
  email: "ironman@avengers.io"
};

function App() {
  const formal = useFormal(initialValues, {
    onSubmit: values => console.log("Your values are:", values)
  });

  return (
    <form onSubmit={formal.submit}>
      <div>
        <label htmlFor="firstName">First Name</label>
        <input {...formal.getFieldProps("firstName")} type="text" />
      </div>

      <div>
        <label htmlFor="lastName">Last Name</label>
        <input {...formal.getFieldProps("lastName")} type="text" />
      </div>

      <div>
        <label htmlFor="email">Email</label>
        <input {...formal.getFieldProps("email")} type="text" />
      </div>

      <button type="submit">Submit</button>
    </form>
  );
}
```

## markdown

1. [mdxc -- 在 jsx 中写 markdown](https://github.com/jamesknelson/mdxc)

   [官网示例](http://dump.jamesknelson.com/mdxc-playground.html)

## 图形处理

1. [react-morph -- 变形 Ui 转换变得简单](https://github.com/brunnolou/react-morph)

   [官方示例](https://brunnolou.github.io/react-morph/?selectedKind=Advanced&selectedStory=Morphing%20from%20card%20to%20details&full=0&addons=0&stories=1&panelRight=0)

## UI/组件库

1. [gestalt -- Pinterest 设计风格的 react ui 组件](https://github.com/pinterest/gestalt)

   [官方文档](https://pinterest.github.io/Box)

2. [rsuite -- 一组 react 组件](https://github.com/rsuite/rsuite)

   [官网](https://rsuitejs.com)

3. [mauerwerk -- react-spring grid 栅格进入/退出交互组件](https://github.com/drcmda/mauerwerk)

   ![demp](https://github.com/drcmda/mauerwerk/raw/master/assets/grid.gif)

4. [react-color -- 来自 Sketch，Photoshop，Chrome，Github，Twitter 等的颜色选择器](https://github.com/casesandberg/react-color)

   ![demo](https://camo.githubusercontent.com/cf6a12e93cfa2e84b49f1cc4343f5f509c5ff54c/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f32364666676754353371453330344377452f67697068792e676966)

   [官网](http://casesandberg.github.io/react-color/)

5. [sky -- React 的天空组件](https://github.com/lucagez/sky)

![demo](https://github.com/lucagez/sky/raw/master/gif/sky-gif.gif)

[演示地址](https://codepen.io/lucagez/full/oQoRyK/)

6. [Vibe -- 使用 Bootstrap 4 构建一个漂亮的 react.js 仪表板](https://github.com/NiceDash/Vibe)

![demo](https://github.com/NiceDash/Vibe/raw/master/assets/preview.png)

7. [react-material-dashboard -- React Dashboard 由 Material UI 的组件，React 和当然 create-react-app 制作，以促进您的应用程序开发过程！](https://github.com/devias-io/react-material-dashboard)

![demo](https://camo.githubusercontent.com/243b563a8415b4b2deaccc389e7c8242703669e2/68747470733a2f2f73332e65752d776573742d322e616d617a6f6e6177732e636f6d2f6465766961732f70726f64756374732f72656163742d6d6174657269616c2d64617368626f6172642f6d6174657269616c2d72656163742d64617368626f6172642d667265652e676966)

## 测试

1. [react-testing-library -- 测试 React 组件的一个非常轻量级的解决方案。它在 react-dom 和 react-dom / test-utils 之上提供轻型实用程序功能，以鼓励更好的测试实践。](https://github.com/kentcdodds/react-testing-library)
2. [kit -- 用于开发，记录和测试 React 组件库的工具 ](https://github.com/c8r/kit)

   [demo](https://github.com/c8r/kit/raw/master/docs/demo.gif)

## 动画

1. [react-spring -- 帮助 react-motion 和 animated 成为最好的朋友](https://github.com/drcmda/react-spring)

   ![demo](https://github.com/drcmda/react-spring/raw/master/assets/reveal.gif)

2. [react-flip-toolkit -- React FLIP 动画助手库，用于高级可配置转换](https://github.com/aholachek/react-flip-toolkit)

   ![demo](https://github.com/aholachek/react-flip-toolkit/raw/master/example-assets/photogrid.gif)

3. [react-rewards -- 奖励用户的小事，让他们微笑！](https://github.com/thedevelobear/react-rewards) 一个点赞动画组件

   ![demo](https://github.com/thedevelobear/react-rewards/raw/master/react-rewards.gif)

## 实例

1. [React Slack Clone -- 使用 react 创建 slack 聊天应用](https://github.com/pusher/react-slack-clone)

   ![demo](https://user-images.githubusercontent.com/1457604/35891289-687ad6ec-0b9b-11e8-99cc-ffbad31a017e.gif)

## 国际化

1. [JavaScript 和 React 的可读，自动化和优化（5 kb）国际化](https://github.com/lingui/js-lingui)
2. [i18nize-react -- 在午休时间内对应用程序进行国际化](https://github.com/Ghost---Shadow/i18nize-react)

## 文档

1. [react-lifecycle-methods-diagram -- 交互式 React 生命周期方法图。](https://github.com/wojtekmaj/react-lifecycle-methods-diagram)建议收藏看看非常直观，一看就理解了

   [实例展示](http://projects.wojtekmaj.pl/react-lifecycle-methods-diagram/)

2. [awesome-react-context -- 与新的 React Context API 相关的策略列表](https://github.com/diegohaz/awesome-react-context)
3. [react-projects -- 在 React 库上构建的项目集合](https://github.com/ajayns/react-projects)

   ![demo](https://camo.githubusercontent.com/3fb5af147b1a6b896122acda4cd10ab36615bbd1/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f6c30485568684174623836765941486b592f67697068792e676966)

4. [react-in-patterns -- 一本免费的书，讲述在使用 React 进行开发时使用的设计模式/技术。](https://github.com/krasimir/react-in-patterns)
5. [React-Redux-Styleguide -- 这是一套用于开发 React 应用程序的工作指南](https://github.com/iraycd/React-Redux-Styleguide)
6. [rfcs -- 用于更改 React 的 RFC](https://github.com/reactjs/rfcs)

## 脚手架

1. [react-static -- React 的渐进式静态网站生成器。](https://github.com/nozzle/react-static)
2. [generact -- 通过命令行复制你自己的产生 React 组件](https://github.com/diegohaz/generact)

   ![demo](https://user-images.githubusercontent.com/3068563/27687316-bb5bd832-5cac-11e7-9761-c489e5a3a9f0.gif)

3. [crana -- 一个 CLI 工具，只需一个命令即可创建 React + Node 应用程序](https://github.com/scriptify/crana)

## 优化

1. [why-did-you-update -- 当 React 进行不必要的更新时，将控制台置于爆炸状态。](https://github.com/maicki/why-did-you-update)

## 手势库

1. [react-with-gesture -- react 手势库](https://github.com/drcmda/react-with-gesture)

   ![demo](https://camo.githubusercontent.com/44a780a48d96323e232c62e28060a694adeccc8e/68747470733a2f2f692e696d6775722e636f6d2f7467316d4e31462e676966)

## 其他

1. [react-proto --为开发人员和设计人员提供 react 应用原型设计工具。](https://github.com/React-Proto/react-proto)
2. [the-platform -- Web API 变成了 React Hooks 和 Suspense 友好的 React 组件。](https://github.com/palmerhq/the-platform)

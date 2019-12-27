# 更新日志

## [v2.3.2](https://github.com/youzan/vant/tree/v2.3.2) (2019-12-20)
[Full Changelog](https://github.com/youzan/vant/compare/v2.3.1...v2.3.2)

**Breaking changes**

- \[Feature Request\] SwipeCell 滑动单元格关闭时触发的问题 [\#5319](https://github.com/youzan/vant/issues/5319)

**Bug Fixes**

- 打包不能编译问题 [\#5336](https://github.com/youzan/vant/issues/5336)

**Issue**

- ssr项目引入tabs时，静态化的代码还是\<van-tabs\>...\<van-tabs\>的形式 [\#5339](https://github.com/youzan/vant/issues/5339)
- Picker 选择器多列联动情况下 如何在onChange 后获得setColumnValues后的默认选中值 ？ [\#5337](https://github.com/youzan/vant/issues/5337)
- list  已经设置:immediate-check= "false"  但是在前一个页面滚动条滚动到底部之后  点击打开页面时load被即时触发  怎么回事 [\#5335](https://github.com/youzan/vant/issues/5335)
- Progress进度条的stroke-width API没用  [\#5334](https://github.com/youzan/vant/issues/5334)
- Uploader上传组件开启multiple多选属性后，加入限制上传数量是5个 第一次上传2张，第二次上次4张，并没有限制，还是上传了6张 [\#5333](https://github.com/youzan/vant/issues/5333)
- \[Feature Request\] 组件的 methods 内写有 uniapp 的生命周期会报错！ [\#5332](https://github.com/youzan/vant/issues/5332)
- \[Feature Request\] 希望能增加个支持safe-area-inset-bottom的容器组件 [\#5331](https://github.com/youzan/vant/issues/5331)
- \[Feature Request\] Uploader 文件上传 max-size 提示 [\#5317](https://github.com/youzan/vant/issues/5317)
- \[Feature Request\] TreeSelect 组件在命名slot中如何获取传递过来的值 [\#5314](https://github.com/youzan/vant/issues/5314)
- 引入Filed组件，css编译报错 [\#5302](https://github.com/youzan/vant/issues/5302)
- \[Feature Request\] 现有sku组件是否支持：不设置总库存，不设置条码对应的库存。 [\#5298](https://github.com/youzan/vant/issues/5298)
- \[Bug Report\] tabs内部列表页滚动后，点击进入详情，然后返回总是回顶部 [\#5254](https://github.com/youzan/vant/issues/5254)

**Features**

- fix\(ImagePreview\): onClose should only trigger once [\#5341](https://github.com/youzan/vant/pull/5341)
- fix\(CountDown\): infinite tick if call reset after finish [\#5340](https://github.com/youzan/vant/pull/5340)

## [v2.3.1](https://github.com/youzan/vant/tree/v2.3.1) (2019-12-20)
[Full Changelog](https://github.com/youzan/vant/compare/v2.3.0...v2.3.1)

**Issue**

- \[Feature Request\] 可拖拽的图形验证码业务组件 [\#5328](https://github.com/youzan/vant/issues/5328)
- \[Feature Request\] Field 输入框是否支持在文本框后增加类似单位的label [\#5323](https://github.com/youzan/vant/issues/5323)

## [v2.3.0](https://github.com/youzan/vant/tree/v2.3.0) (2019-12-20)
[Full Changelog](https://github.com/youzan/vant/compare/v2.3.0-beta.5...v2.3.0)

**Breaking changes**

- \[Feature Request\] checkbox-group ,toggleAll\(\) 数据量大，全选和取消全选中过程慢 [\#5284](https://github.com/youzan/vant/issues/5284)
- \[Feature Request\] 希望tabs组件支持电梯模式 [\#5264](https://github.com/youzan/vant/issues/5264)
- \[Bug Report\] 建议van-tab添加dot属性 [\#5240](https://github.com/youzan/vant/issues/5240)

**Bug Fixes**

- \[Bug Report\] DropdownMenu弹出层滑动问题 [\#5305](https://github.com/youzan/vant/issues/5305)
- \[Bug Report\] Dialog在keep-alive的页面中，跳转路由再回退，会被隐藏 [\#5243](https://github.com/youzan/vant/issues/5243)

**Issue**

- \[Feature Request\] Field控件是否支持toggle-group-button的展示效果 [\#5326](https://github.com/youzan/vant/issues/5326)
- 请问，我现在需要文件上传的绝对路径，我该怎么做，谢谢 [\#5322](https://github.com/youzan/vant/issues/5322)
- \[Feature Request\] 图片上传最大限制的提示 [\#5316](https://github.com/youzan/vant/issues/5316)
- DatetimePicker  在ios9定位跑到当前内容高度底部，而不是当前可视窗口底部 [\#5310](https://github.com/youzan/vant/issues/5310)
- \[Bug Report\] 请教下card组件如何使用图片懒加载 [\#5309](https://github.com/youzan/vant/issues/5309)
- \[Feature Request\]  DatetimePicker  时间控件能否支持秒 [\#5308](https://github.com/youzan/vant/issues/5308)
- 城市四级联动 [\#5307](https://github.com/youzan/vant/issues/5307)
- pannel组件错位 [\#5306](https://github.com/youzan/vant/issues/5306)
- \[Feature Request\] 监听物理返回键 [\#5304](https://github.com/youzan/vant/issues/5304)
- \[Feature Request\] 类似原生input的datalist功能的组件和picker支持多选 [\#5303](https://github.com/youzan/vant/issues/5303)
- 强烈建议增加表单校验功能! [\#5301](https://github.com/youzan/vant/issues/5301)
- \[Bug Report\] toast内容文字过长时，内容显示不全 [\#5300](https://github.com/youzan/vant/issues/5300)
- \[Feature Request\] 建议布局中增加一个最大宽度的设置 [\#5299](https://github.com/youzan/vant/issues/5299)
- \[Bug Report\] 图片预览 [\#5297](https://github.com/youzan/vant/issues/5297)
- \[Bug Report\] 请问2.3.0正式版发布之后，2.3.0-beta.5还可以使用么 [\#5296](https://github.com/youzan/vant/issues/5296)
- \[Bug Report\] van-tab  sticky 属性，控制台报错了，但是功能正常 [\#5295](https://github.com/youzan/vant/issues/5295)
- tabs [\#5294](https://github.com/youzan/vant/issues/5294)
- 高德地图配合使用popup 弹出层 弹出层一闪而过 [\#5293](https://github.com/youzan/vant/issues/5293)
- popup 2.2.14版本可以正常使用，但是2.3.0不能使用 [\#5292](https://github.com/youzan/vant/issues/5292)
- Popup 弹出层有bug，设置它的z-index为undefined [\#5291](https://github.com/youzan/vant/issues/5291)
- \[Bug Report\] Swipe 轮播 [\#5290](https://github.com/youzan/vant/issues/5290)
- 想知道 2.3 正式版什么时候会上线， [\#5289](https://github.com/youzan/vant/issues/5289)
- DropdownMenu 下拉菜单，奇怪问题，在线等， [\#5288](https://github.com/youzan/vant/issues/5288)
- \[Bug Report\] 轮播图滚动期间会出现白屏闪一下 [\#5287](https://github.com/youzan/vant/issues/5287)
- \[Bug Report\] van-tabs组件的animated属性在ios系统无过度动画 [\#5281](https://github.com/youzan/vant/issues/5281)

**Features**

- fix\(Tab\): add nextTick to ensure rendered [\#5327](https://github.com/youzan/vant/pull/5327)
- fix\(VantCli\): enable Lan access [\#5325](https://github.com/youzan/vant/pull/5325)
- feat\(SwipeCell\): add open event [\#5324](https://github.com/youzan/vant/pull/5324)
- feat\(SwipeCell\): add before-close prop [\#5320](https://github.com/youzan/vant/pull/5320)
- feat\(Sku\): add resetSelectedSku method [\#5318](https://github.com/youzan/vant/pull/5318)
- feat\(Tabs\): add rendered prop [\#5315](https://github.com/youzan/vant/pull/5315)
- fix\(DropdownMenu\): incorrect menu position when scroll [\#5313](https://github.com/youzan/vant/pull/5313)
- docs: fix coverage description [\#5312](https://github.com/youzan/vant/pull/5312)

## [v2.3.0-beta.5](https://github.com/youzan/vant/tree/v2.3.0-beta.5) (2019-12-16)
[Full Changelog](https://github.com/youzan/vant/compare/v2.3.0-beta.4...v2.3.0-beta.5)

**Bug Fixes**

- \[Bug Report\] Dialog 在关闭过程中快速点击，导致 beforeClose 重复触发 [\#5263](https://github.com/youzan/vant/issues/5263)

**Issue**

- \[Feature Request\] Circle 环形进度条  rate目标进度不能超过100吗  [\#5283](https://github.com/youzan/vant/issues/5283)
- IndexBar 索引栏问题 -- 一直抖动, 无法下拉到底 [\#5282](https://github.com/youzan/vant/issues/5282)
- \[Bug Report\] 购物车中van-checkbox-group中嵌套van-card中footerslot中加入Stepper 组件，当点击加减或者手动输入的时候，会冒泡导致checkbox来回选中 [\#5280](https://github.com/youzan/vant/issues/5280)
- van-datetime-picker 日期选择面板无法直接定位到给定的日期 [\#5279](https://github.com/youzan/vant/issues/5279)
- tabbbar [\#5277](https://github.com/youzan/vant/issues/5277)
- van-checkbox   [\#5276](https://github.com/youzan/vant/issues/5276)
- \[Bug Report\] uploader组件上传图片缩略图旋转90° [\#5275](https://github.com/youzan/vant/issues/5275)
- textarea 设置了autosize 但是无法自适应高度，只能滚动条滚动。 [\#5271](https://github.com/youzan/vant/issues/5271)
- toast switch dialog 组件按需引入时报错 [\#5270](https://github.com/youzan/vant/issues/5270)
- These relative modules were not found [\#5269](https://github.com/youzan/vant/issues/5269)
- \[Bug Report\] tabs 添加 animated属性后 tab中的DropdownMenu 只在第一个tab起作用 [\#5268](https://github.com/youzan/vant/issues/5268)
- upload 组件上传有before-read，multiple不能同时生效 [\#5250](https://github.com/youzan/vant/issues/5250)

**Features**

- fix\(Popup\): should reopen when activated [\#5286](https://github.com/youzan/vant/pull/5286)
- feat\(Checkbox\): improve toggleAll perf [\#5285](https://github.com/youzan/vant/pull/5285)
- feat\(Tab\): add info prop [\#5274](https://github.com/youzan/vant/pull/5274)
- feat\(Tab\): add scrollspy prop [\#5273](https://github.com/youzan/vant/pull/5273)
- feat\(Tab\): add dot prop [\#5272](https://github.com/youzan/vant/pull/5272)

## [v2.3.0-beta.4](https://github.com/youzan/vant/tree/v2.3.0-beta.4) (2019-12-13)
[Full Changelog](https://github.com/youzan/vant/compare/v2.3.0-beta.3...v2.3.0-beta.4)

**Issue**

- uniapp+vant写小程序使用tabs组件时，发现两个问题，第一绑定当前选中的标签页不生效，第二设置title文字过长省略显示为false也不生效 [\#5265](https://github.com/youzan/vant/issues/5265)
- DropdownItem应该再加一个closed事件回调 [\#5261](https://github.com/youzan/vant/issues/5261)
- \[Bug Report\] 官网示例看不到了 [\#5260](https://github.com/youzan/vant/issues/5260)
- 关于List上拉加载的问题 [\#5259](https://github.com/youzan/vant/issues/5259)
- switch开关组件异步点击的时候会有点透的问题 [\#5258](https://github.com/youzan/vant/issues/5258)
- 多级picker change 后picker.getColumnIndex未改变 [\#5256](https://github.com/youzan/vant/issues/5256)
- \[Feature Request\] 后期会考虑加入表格的组件吗 [\#5255](https://github.com/youzan/vant/issues/5255)
- \[Feature Request\] 大佬，全屏 Popup 安卓机返回键返回时如何只关Popup,不后退路由 [\#5253](https://github.com/youzan/vant/issues/5253)
- \[Feature Request\] 建议增加车牌选择框\(常规车牌和新能源\) [\#5252](https://github.com/youzan/vant/issues/5252)
- \[Bug Report\] nuxt 中直接以引入cdn，组件报错  [\#5251](https://github.com/youzan/vant/issues/5251)
- popup弹出层在iphoneX移动端中会出现样式问题 [\#5249](https://github.com/youzan/vant/issues/5249)
- upload 组件上传不能限制gif上传 [\#5248](https://github.com/youzan/vant/issues/5248)
- Collapse 每次展开van-collapse-item 内容字体大小不一样 [\#5247](https://github.com/youzan/vant/issues/5247)
- navBar 没有提供属性来改变背景色和字体颜色？ [\#5245](https://github.com/youzan/vant/issues/5245)
- nuxt 中直接以引入cdn组件报错 [\#5244](https://github.com/youzan/vant/issues/5244)
- \[Feature Request\] 2.2分支打包报错。能更新一下lazyload版本吗？ [\#5241](https://github.com/youzan/vant/issues/5241)
- \[Bug Report\] upload组件上传图片显示问题 [\#5239](https://github.com/youzan/vant/issues/5239)
- popup组件结合better-scroll无法使用 [\#5238](https://github.com/youzan/vant/issues/5238)

**Features**

- fix\(Dialog\): show not trigger close event when hidden [\#5267](https://github.com/youzan/vant/pull/5267)
- docs\(DropdownItem\): add closed event [\#5266](https://github.com/youzan/vant/pull/5266)
- build\(deps\): bump lodash from 4.17.11 to 4.17.15 [\#5262](https://github.com/youzan/vant/pull/5262)
- fix\(Stepper\): should format value when max、min changed [\#5257](https://github.com/youzan/vant/pull/5257)
- fix\(Icon\): medal typo [\#5242](https://github.com/youzan/vant/pull/5242)
- chore\(Card\): add class for currency [\#5237](https://github.com/youzan/vant/pull/5237)

## [v2.3.0-beta.3](https://github.com/youzan/vant/tree/v2.3.0-beta.3) (2019-12-09)
[Full Changelog](https://github.com/youzan/vant/compare/v2.3.0-beta.2...v2.3.0-beta.3)

## [v2.3.0-beta.2](https://github.com/youzan/vant/tree/v2.3.0-beta.2) (2019-12-06)
[Full Changelog](https://github.com/youzan/vant/compare/v2.2.16...v2.3.0-beta.2)

## [v2.2.16](https://github.com/youzan/vant/tree/v2.2.16) (2019-12-03)
[Full Changelog](https://github.com/youzan/vant/compare/v2.3.0-beta.1...v2.2.16)

## [v2.3.0-beta.1](https://github.com/youzan/vant/tree/v2.3.0-beta.1) (2019-11-30)
[Full Changelog](https://github.com/youzan/vant/compare/v2.2.15...v2.3.0-beta.1)

## [v2.2.15](https://github.com/youzan/vant/tree/v2.2.15) (2019-11-28)
[Full Changelog](https://github.com/youzan/vant/compare/v2.3.0-beta.0...v2.2.15)

## [v2.3.0-beta.0](https://github.com/youzan/vant/tree/v2.3.0-beta.0) (2019-11-28)
[Full Changelog](https://github.com/youzan/vant/compare/v2.2.14...v2.3.0-beta.0)

## [v2.2.14](https://github.com/youzan/vant/tree/v2.2.14) (2019-11-22)
[Full Changelog](https://github.com/youzan/vant/compare/v2.2.13...v2.2.14)

## [v2.2.13](https://github.com/youzan/vant/tree/v2.2.13) (2019-11-14)
[Full Changelog](https://github.com/youzan/vant/compare/v2.2.13-beta.0...v2.2.13)

## [v2.2.13-beta.0](https://github.com/youzan/vant/tree/v2.2.13-beta.0) (2019-11-10)
[Full Changelog](https://github.com/youzan/vant/compare/v2.2.12...v2.2.13-beta.0)

## [v2.2.12](https://github.com/youzan/vant/tree/v2.2.12) (2019-11-07)
[Full Changelog](https://github.com/youzan/vant/compare/v2.2.11...v2.2.12)

## [v2.2.11](https://github.com/youzan/vant/tree/v2.2.11) (2019-11-04)
[Full Changelog](https://github.com/youzan/vant/compare/v2.2.10...v2.2.11)

## [v2.2.10](https://github.com/youzan/vant/tree/v2.2.10) (2019-10-26)
[Full Changelog](https://github.com/youzan/vant/compare/v2.2.9...v2.2.10)

## [v2.2.9](https://github.com/youzan/vant/tree/v2.2.9) (2019-10-20)
[Full Changelog](https://github.com/youzan/vant/compare/v2.2.9-beta.1...v2.2.9)

## [v2.2.9-beta.1](https://github.com/youzan/vant/tree/v2.2.9-beta.1) (2019-10-18)
[Full Changelog](https://github.com/youzan/vant/compare/v2.2.9-beta.0...v2.2.9-beta.1)

## [v2.2.9-beta.0](https://github.com/youzan/vant/tree/v2.2.9-beta.0) (2019-10-17)
[Full Changelog](https://github.com/youzan/vant/compare/v2.2.8...v2.2.9-beta.0)

## [v2.2.8](https://github.com/youzan/vant/tree/v2.2.8) (2019-10-17)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.28...v2.2.8)

## [v1.6.28](https://github.com/youzan/vant/tree/v1.6.28) (2019-10-14)
[Full Changelog](https://github.com/youzan/vant/compare/v2.2.7...v1.6.28)

## [v2.2.7](https://github.com/youzan/vant/tree/v2.2.7) (2019-10-11)
[Full Changelog](https://github.com/youzan/vant/compare/v2.2.6...v2.2.7)

## [v2.2.6](https://github.com/youzan/vant/tree/v2.2.6) (2019-10-08)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.27...v2.2.6)

## [v1.6.27](https://github.com/youzan/vant/tree/v1.6.27) (2019-09-30)
[Full Changelog](https://github.com/youzan/vant/compare/v2.2.5...v1.6.27)

## [v2.2.5](https://github.com/youzan/vant/tree/v2.2.5) (2019-09-28)
[Full Changelog](https://github.com/youzan/vant/compare/v2.2.4...v2.2.5)

## [v2.2.4](https://github.com/youzan/vant/tree/v2.2.4) (2019-09-27)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.26...v2.2.4)

## [v1.6.26](https://github.com/youzan/vant/tree/v1.6.26) (2019-09-27)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.25...v1.6.26)

## [v1.6.25](https://github.com/youzan/vant/tree/v1.6.25) (2019-09-26)
[Full Changelog](https://github.com/youzan/vant/compare/v2.2.3...v1.6.25)

## [v2.2.3](https://github.com/youzan/vant/tree/v2.2.3) (2019-09-24)
[Full Changelog](https://github.com/youzan/vant/compare/v2.2.2...v2.2.3)

## [v2.2.2](https://github.com/youzan/vant/tree/v2.2.2) (2019-09-19)
[Full Changelog](https://github.com/youzan/vant/compare/v2.2.1...v2.2.2)

## [v2.2.1](https://github.com/youzan/vant/tree/v2.2.1) (2019-09-12)
[Full Changelog](https://github.com/youzan/vant/compare/v2.2.0...v2.2.1)

## [v2.2.0](https://github.com/youzan/vant/tree/v2.2.0) (2019-09-06)
[Full Changelog](https://github.com/youzan/vant/compare/v2.1.8...v2.2.0)

## [v2.1.8](https://github.com/youzan/vant/tree/v2.1.8) (2019-08-29)
[Full Changelog](https://github.com/youzan/vant/compare/v2.1.7...v2.1.8)

## [v2.1.7](https://github.com/youzan/vant/tree/v2.1.7) (2019-08-26)
[Full Changelog](https://github.com/youzan/vant/compare/v2.1.6...v2.1.7)

## [v2.1.6](https://github.com/youzan/vant/tree/v2.1.6) (2019-08-26)
[Full Changelog](https://github.com/youzan/vant/compare/v2.1.5...v2.1.6)

## [v2.1.5](https://github.com/youzan/vant/tree/v2.1.5) (2019-08-23)
[Full Changelog](https://github.com/youzan/vant/compare/v2.1.4...v2.1.5)

## [v2.1.4](https://github.com/youzan/vant/tree/v2.1.4) (2019-08-21)
[Full Changelog](https://github.com/youzan/vant/compare/v2.1.3...v2.1.4)

## [v2.1.3](https://github.com/youzan/vant/tree/v2.1.3) (2019-08-15)
[Full Changelog](https://github.com/youzan/vant/compare/v2.1.2...v2.1.3)

## [v2.1.2](https://github.com/youzan/vant/tree/v2.1.2) (2019-08-10)
[Full Changelog](https://github.com/youzan/vant/compare/v2.1.1...v2.1.2)

## [v2.1.1](https://github.com/youzan/vant/tree/v2.1.1) (2019-08-02)
[Full Changelog](https://github.com/youzan/vant/compare/v2.1.0...v2.1.1)

## [v2.1.0](https://github.com/youzan/vant/tree/v2.1.0) (2019-07-31)
[Full Changelog](https://github.com/youzan/vant/compare/v2.1.0-beta.2...v2.1.0)

## [v2.1.0-beta.2](https://github.com/youzan/vant/tree/v2.1.0-beta.2) (2019-07-26)
[Full Changelog](https://github.com/youzan/vant/compare/v2.1.0-beta.1...v2.1.0-beta.2)

## [v2.1.0-beta.1](https://github.com/youzan/vant/tree/v2.1.0-beta.1) (2019-07-25)
[Full Changelog](https://github.com/youzan/vant/compare/v2.1.0-beta.0...v2.1.0-beta.1)

## [v2.1.0-beta.0](https://github.com/youzan/vant/tree/v2.1.0-beta.0) (2019-07-22)
[Full Changelog](https://github.com/youzan/vant/compare/v2.0.9...v2.1.0-beta.0)

## [v2.0.9](https://github.com/youzan/vant/tree/v2.0.9) (2019-07-19)
[Full Changelog](https://github.com/youzan/vant/compare/v2.0.8...v2.0.9)

## [v2.0.8](https://github.com/youzan/vant/tree/v2.0.8) (2019-07-16)
[Full Changelog](https://github.com/youzan/vant/compare/v2.0.7...v2.0.8)

## [v2.0.7](https://github.com/youzan/vant/tree/v2.0.7) (2019-07-11)
[Full Changelog](https://github.com/youzan/vant/compare/v2.0.6...v2.0.7)

## [v2.0.6](https://github.com/youzan/vant/tree/v2.0.6) (2019-07-05)
[Full Changelog](https://github.com/youzan/vant/compare/v2.0.5...v2.0.6)

## [v2.0.5](https://github.com/youzan/vant/tree/v2.0.5) (2019-07-02)
[Full Changelog](https://github.com/youzan/vant/compare/v2.0.4...v2.0.5)

## [v2.0.4](https://github.com/youzan/vant/tree/v2.0.4) (2019-07-01)
[Full Changelog](https://github.com/youzan/vant/compare/v2.0.3...v2.0.4)

## [v2.0.3](https://github.com/youzan/vant/tree/v2.0.3) (2019-06-27)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.24...v2.0.3)

## [v1.6.24](https://github.com/youzan/vant/tree/v1.6.24) (2019-06-21)
[Full Changelog](https://github.com/youzan/vant/compare/v2.0.2...v1.6.24)

## [v2.0.2](https://github.com/youzan/vant/tree/v2.0.2) (2019-06-21)
[Full Changelog](https://github.com/youzan/vant/compare/v2.0.1...v2.0.2)

## [v2.0.1](https://github.com/youzan/vant/tree/v2.0.1) (2019-06-15)
[Full Changelog](https://github.com/youzan/vant/compare/v2.0.0...v2.0.1)

## [v2.0.0](https://github.com/youzan/vant/tree/v2.0.0) (2019-06-11)
[Full Changelog](https://github.com/youzan/vant/compare/v2.0.0-beta.5...v2.0.0)

## [v2.0.0-beta.5](https://github.com/youzan/vant/tree/v2.0.0-beta.5) (2019-06-10)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.23...v2.0.0-beta.5)

## [v1.6.23](https://github.com/youzan/vant/tree/v1.6.23) (2019-06-07)
[Full Changelog](https://github.com/youzan/vant/compare/v2.0.0-beta.4...v1.6.23)

## [v2.0.0-beta.4](https://github.com/youzan/vant/tree/v2.0.0-beta.4) (2019-06-05)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.22...v2.0.0-beta.4)

## [v1.6.22](https://github.com/youzan/vant/tree/v1.6.22) (2019-06-03)
[Full Changelog](https://github.com/youzan/vant/compare/v2.0.0-beta.3...v1.6.22)

## [v2.0.0-beta.3](https://github.com/youzan/vant/tree/v2.0.0-beta.3) (2019-05-31)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.21...v2.0.0-beta.3)

## [v1.6.21](https://github.com/youzan/vant/tree/v1.6.21) (2019-05-30)
[Full Changelog](https://github.com/youzan/vant/compare/v2.0.0-beta.2...v1.6.21)

## [v2.0.0-beta.2](https://github.com/youzan/vant/tree/v2.0.0-beta.2) (2019-05-28)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.20...v2.0.0-beta.2)

## [v1.6.20](https://github.com/youzan/vant/tree/v1.6.20) (2019-05-27)
[Full Changelog](https://github.com/youzan/vant/compare/v2.0.0-beta.1...v1.6.20)

## [v2.0.0-beta.1](https://github.com/youzan/vant/tree/v2.0.0-beta.1) (2019-05-24)
[Full Changelog](https://github.com/youzan/vant/compare/v2.0.0-beta.0...v2.0.0-beta.1)

## [v2.0.0-beta.0](https://github.com/youzan/vant/tree/v2.0.0-beta.0) (2019-05-22)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.19...v2.0.0-beta.0)

## [v1.6.19](https://github.com/youzan/vant/tree/v1.6.19) (2019-05-16)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.18...v1.6.19)

## [v1.6.18](https://github.com/youzan/vant/tree/v1.6.18) (2019-05-10)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.17...v1.6.18)

## [v1.6.17](https://github.com/youzan/vant/tree/v1.6.17) (2019-05-05)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.16...v1.6.17)

## [v1.6.16](https://github.com/youzan/vant/tree/v1.6.16) (2019-04-26)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.15...v1.6.16)

## [v1.6.15](https://github.com/youzan/vant/tree/v1.6.15) (2019-04-19)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.14...v1.6.15)

## [v1.6.14](https://github.com/youzan/vant/tree/v1.6.14) (2019-04-13)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.13...v1.6.14)

## [v1.6.13](https://github.com/youzan/vant/tree/v1.6.13) (2019-04-06)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.12...v1.6.13)

## [v1.6.12](https://github.com/youzan/vant/tree/v1.6.12) (2019-03-28)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.11...v1.6.12)

## [v1.6.11](https://github.com/youzan/vant/tree/v1.6.11) (2019-03-22)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.10...v1.6.11)

## [v1.6.10](https://github.com/youzan/vant/tree/v1.6.10) (2019-03-17)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.9...v1.6.10)

## [v1.6.9](https://github.com/youzan/vant/tree/v1.6.9) (2019-03-11)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.8...v1.6.9)

## [v1.6.8](https://github.com/youzan/vant/tree/v1.6.8) (2019-03-02)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.7...v1.6.8)

## [v1.6.7](https://github.com/youzan/vant/tree/v1.6.7) (2019-02-26)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.6...v1.6.7)

## [v1.6.6](https://github.com/youzan/vant/tree/v1.6.6) (2019-02-24)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.5...v1.6.6)

## [v1.6.5](https://github.com/youzan/vant/tree/v1.6.5) (2019-02-17)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.4...v1.6.5)

## [v1.6.4](https://github.com/youzan/vant/tree/v1.6.4) (2019-02-14)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.3...v1.6.4)

## [v1.6.3](https://github.com/youzan/vant/tree/v1.6.3) (2019-02-14)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.2...v1.6.3)

## [v1.6.2](https://github.com/youzan/vant/tree/v1.6.2) (2019-02-10)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.1...v1.6.2)

## [v1.6.1](https://github.com/youzan/vant/tree/v1.6.1) (2019-02-05)
[Full Changelog](https://github.com/youzan/vant/compare/v1.6.0...v1.6.1)

## [v1.6.0](https://github.com/youzan/vant/tree/v1.6.0) (2019-02-04)
[Full Changelog](https://github.com/youzan/vant/compare/v1.5.7...v1.6.0)

## [v1.5.7](https://github.com/youzan/vant/tree/v1.5.7) (2019-01-24)
[Full Changelog](https://github.com/youzan/vant/compare/v1.5.6...v1.5.7)

## [v1.5.6](https://github.com/youzan/vant/tree/v1.5.6) (2019-01-22)
[Full Changelog](https://github.com/youzan/vant/compare/v1.5.5...v1.5.6)

## [v1.5.5](https://github.com/youzan/vant/tree/v1.5.5) (2019-01-21)
[Full Changelog](https://github.com/youzan/vant/compare/v1.5.4...v1.5.5)

## [v1.5.4](https://github.com/youzan/vant/tree/v1.5.4) (2019-01-20)
[Full Changelog](https://github.com/youzan/vant/compare/v1.5.3...v1.5.4)

## [v1.5.3](https://github.com/youzan/vant/tree/v1.5.3) (2019-01-20)
[Full Changelog](https://github.com/youzan/vant/compare/v1.5.2...v1.5.3)

## [v1.5.2](https://github.com/youzan/vant/tree/v1.5.2) (2019-01-10)
[Full Changelog](https://github.com/youzan/vant/compare/v1.5.2-beta...v1.5.2)

## [v1.5.2-beta](https://github.com/youzan/vant/tree/v1.5.2-beta) (2019-01-09)
[Full Changelog](https://github.com/youzan/vant/compare/v1.5.1...v1.5.2-beta)

## [v1.5.1](https://github.com/youzan/vant/tree/v1.5.1) (2019-01-01)
[Full Changelog](https://github.com/youzan/vant/compare/v1.5.0...v1.5.1)

## [v1.5.0](https://github.com/youzan/vant/tree/v1.5.0) (2018-12-22)
[Full Changelog](https://github.com/youzan/vant/compare/v1.5.0-beta2...v1.5.0)

## [v1.5.0-beta2](https://github.com/youzan/vant/tree/v1.5.0-beta2) (2018-12-18)
[Full Changelog](https://github.com/youzan/vant/compare/v1.5.0-beta...v1.5.0-beta2)

## [v1.5.0-beta](https://github.com/youzan/vant/tree/v1.5.0-beta) (2018-12-17)
[Full Changelog](https://github.com/youzan/vant/compare/v1.4.8...v1.5.0-beta)

## [v1.4.8](https://github.com/youzan/vant/tree/v1.4.8) (2018-12-04)
[Full Changelog](https://github.com/youzan/vant/compare/v1.4.7...v1.4.8)

## [v1.4.7](https://github.com/youzan/vant/tree/v1.4.7) (2018-11-27)
[Full Changelog](https://github.com/youzan/vant/compare/v1.4.5...v1.4.7)

## [v1.4.5](https://github.com/youzan/vant/tree/v1.4.5) (2018-11-23)
[Full Changelog](https://github.com/youzan/vant/compare/v1.4.4...v1.4.5)

## [v1.4.4](https://github.com/youzan/vant/tree/v1.4.4) (2018-11-18)
[Full Changelog](https://github.com/youzan/vant/compare/v1.4.3...v1.4.4)

## [v1.4.3](https://github.com/youzan/vant/tree/v1.4.3) (2018-11-10)
[Full Changelog](https://github.com/youzan/vant/compare/v1.4.2...v1.4.3)

## [v1.4.2](https://github.com/youzan/vant/tree/v1.4.2) (2018-11-05)
[Full Changelog](https://github.com/youzan/vant/compare/v1.4.1...v1.4.2)

## [v1.4.1](https://github.com/youzan/vant/tree/v1.4.1) (2018-11-04)
[Full Changelog](https://github.com/youzan/vant/compare/v1.4.0...v1.4.1)

## [v1.4.0](https://github.com/youzan/vant/tree/v1.4.0) (2018-11-04)
[Full Changelog](https://github.com/youzan/vant/compare/v1.3.10...v1.4.0)

## [v1.3.10](https://github.com/youzan/vant/tree/v1.3.10) (2018-10-29)
[Full Changelog](https://github.com/youzan/vant/compare/v1.3.9...v1.3.10)

## [v1.3.9](https://github.com/youzan/vant/tree/v1.3.9) (2018-10-24)
[Full Changelog](https://github.com/youzan/vant/compare/v1.3.8...v1.3.9)

## [v1.3.8](https://github.com/youzan/vant/tree/v1.3.8) (2018-10-17)
[Full Changelog](https://github.com/youzan/vant/compare/v1.3.7...v1.3.8)

## [v1.3.7](https://github.com/youzan/vant/tree/v1.3.7) (2018-10-12)
[Full Changelog](https://github.com/youzan/vant/compare/v1.3.6...v1.3.7)

## [v1.3.6](https://github.com/youzan/vant/tree/v1.3.6) (2018-10-11)
[Full Changelog](https://github.com/youzan/vant/compare/v1.3.5...v1.3.6)

## [v1.3.5](https://github.com/youzan/vant/tree/v1.3.5) (2018-10-10)
[Full Changelog](https://github.com/youzan/vant/compare/v1.3.4...v1.3.5)

## [v1.3.4](https://github.com/youzan/vant/tree/v1.3.4) (2018-10-02)
[Full Changelog](https://github.com/youzan/vant/compare/v1.3.3...v1.3.4)

## [v1.3.3](https://github.com/youzan/vant/tree/v1.3.3) (2018-09-23)
[Full Changelog](https://github.com/youzan/vant/compare/v1.3.2...v1.3.3)

## [v1.3.2](https://github.com/youzan/vant/tree/v1.3.2) (2018-09-14)
[Full Changelog](https://github.com/youzan/vant/compare/v1.3.1...v1.3.2)

## [v1.3.1](https://github.com/youzan/vant/tree/v1.3.1) (2018-09-07)
[Full Changelog](https://github.com/youzan/vant/compare/v1.3.0...v1.3.1)

## [v1.3.0](https://github.com/youzan/vant/tree/v1.3.0) (2018-08-31)
[Full Changelog](https://github.com/youzan/vant/compare/v1.2.1...v1.3.0)

## [v1.2.1](https://github.com/youzan/vant/tree/v1.2.1) (2018-08-24)
[Full Changelog](https://github.com/youzan/vant/compare/v1.2.0...v1.2.1)

## [v1.2.0](https://github.com/youzan/vant/tree/v1.2.0) (2018-08-20)
[Full Changelog](https://github.com/youzan/vant/compare/v1.1.16...v1.2.0)

## [v1.1.16](https://github.com/youzan/vant/tree/v1.1.16) (2018-08-10)
[Full Changelog](https://github.com/youzan/vant/compare/v1.1.15...v1.1.16)

## [v1.1.15](https://github.com/youzan/vant/tree/v1.1.15) (2018-08-03)
[Full Changelog](https://github.com/youzan/vant/compare/v1.1.14...v1.1.15)

## [v1.1.14](https://github.com/youzan/vant/tree/v1.1.14) (2018-07-19)
[Full Changelog](https://github.com/youzan/vant/compare/v1.1.13...v1.1.14)

## [v1.1.13](https://github.com/youzan/vant/tree/v1.1.13) (2018-07-13)
[Full Changelog](https://github.com/youzan/vant/compare/v1.1.12...v1.1.13)

## [v1.1.12](https://github.com/youzan/vant/tree/v1.1.12) (2018-07-06)
[Full Changelog](https://github.com/youzan/vant/compare/v1.1.11...v1.1.12)

## [v1.1.11](https://github.com/youzan/vant/tree/v1.1.11) (2018-07-04)
[Full Changelog](https://github.com/youzan/vant/compare/v1.1.10...v1.1.11)

## [v1.1.10](https://github.com/youzan/vant/tree/v1.1.10) (2018-06-28)
[Full Changelog](https://github.com/youzan/vant/compare/v1.1.9...v1.1.10)

## [v1.1.9](https://github.com/youzan/vant/tree/v1.1.9) (2018-06-22)
[Full Changelog](https://github.com/youzan/vant/compare/v1.1.8...v1.1.9)

## [v1.1.8](https://github.com/youzan/vant/tree/v1.1.8) (2018-06-14)
[Full Changelog](https://github.com/youzan/vant/compare/v1.1.7...v1.1.8)

## [v1.1.7](https://github.com/youzan/vant/tree/v1.1.7) (2018-06-06)
[Full Changelog](https://github.com/youzan/vant/compare/v1.1.6...v1.1.7)

## [v1.1.6](https://github.com/youzan/vant/tree/v1.1.6) (2018-06-01)
[Full Changelog](https://github.com/youzan/vant/compare/v1.1.5...v1.1.6)

## [v1.1.5](https://github.com/youzan/vant/tree/v1.1.5) (2018-05-24)
[Full Changelog](https://github.com/youzan/vant/compare/v1.1.4...v1.1.5)

## [v1.1.4](https://github.com/youzan/vant/tree/v1.1.4) (2018-05-18)
[Full Changelog](https://github.com/youzan/vant/compare/v1.1.3...v1.1.4)

## [v1.1.3](https://github.com/youzan/vant/tree/v1.1.3) (2018-05-12)
[Full Changelog](https://github.com/youzan/vant/compare/v1.1.2...v1.1.3)

## [v1.1.2](https://github.com/youzan/vant/tree/v1.1.2) (2018-05-08)
[Full Changelog](https://github.com/youzan/vant/compare/v1.1.1...v1.1.2)

## [v1.1.1](https://github.com/youzan/vant/tree/v1.1.1) (2018-05-04)
[Full Changelog](https://github.com/youzan/vant/compare/v1.1.0...v1.1.1)

## [v1.1.0](https://github.com/youzan/vant/tree/v1.1.0) (2018-04-25)
[Full Changelog](https://github.com/youzan/vant/compare/v1.0.8...v1.1.0)

## [v1.0.8](https://github.com/youzan/vant/tree/v1.0.8) (2018-04-20)
[Full Changelog](https://github.com/youzan/vant/compare/v1.0.7...v1.0.8)

## [v1.0.7](https://github.com/youzan/vant/tree/v1.0.7) (2018-04-17)
[Full Changelog](https://github.com/youzan/vant/compare/v1.0.6...v1.0.7)

## [v1.0.6](https://github.com/youzan/vant/tree/v1.0.6) (2018-04-17)
[Full Changelog](https://github.com/youzan/vant/compare/v1.0.5...v1.0.6)

## [v1.0.5](https://github.com/youzan/vant/tree/v1.0.5) (2018-04-13)
[Full Changelog](https://github.com/youzan/vant/compare/v1.0.4...v1.0.5)

## [v1.0.4](https://github.com/youzan/vant/tree/v1.0.4) (2018-04-10)
[Full Changelog](https://github.com/youzan/vant/compare/v1.0.3...v1.0.4)

## [v1.0.3](https://github.com/youzan/vant/tree/v1.0.3) (2018-03-26)
[Full Changelog](https://github.com/youzan/vant/compare/v1.0.2...v1.0.3)

## [v1.0.2](https://github.com/youzan/vant/tree/v1.0.2) (2018-03-22)
[Full Changelog](https://github.com/youzan/vant/compare/v1.0.1...v1.0.2)

## [v1.0.1](https://github.com/youzan/vant/tree/v1.0.1) (2018-03-19)
[Full Changelog](https://github.com/youzan/vant/compare/v1.0.0...v1.0.1)

## [v1.0.0](https://github.com/youzan/vant/tree/v1.0.0) (2018-03-19)
[Full Changelog](https://github.com/youzan/vant/compare/v0.12.14...v1.0.0)

## [v0.12.14](https://github.com/youzan/vant/tree/v0.12.14) (2018-03-09)
[Full Changelog](https://github.com/youzan/vant/compare/v0.12.13...v0.12.14)

## [v0.12.13](https://github.com/youzan/vant/tree/v0.12.13) (2018-03-09)
[Full Changelog](https://github.com/youzan/vant/compare/v0.12.12...v0.12.13)

## [v0.12.12](https://github.com/youzan/vant/tree/v0.12.12) (2018-03-06)
[Full Changelog](https://github.com/youzan/vant/compare/v0.12.11...v0.12.12)

## [v0.12.11](https://github.com/youzan/vant/tree/v0.12.11) (2018-02-27)
[Full Changelog](https://github.com/youzan/vant/compare/v0.12.10...v0.12.11)

## [v0.12.10](https://github.com/youzan/vant/tree/v0.12.10) (2018-02-12)
[Full Changelog](https://github.com/youzan/vant/compare/v0.12.9...v0.12.10)

## [v0.12.9](https://github.com/youzan/vant/tree/v0.12.9) (2018-02-08)
[Full Changelog](https://github.com/youzan/vant/compare/v0.12.8...v0.12.9)

## [v0.12.8](https://github.com/youzan/vant/tree/v0.12.8) (2018-02-07)
[Full Changelog](https://github.com/youzan/vant/compare/v0.12.7...v0.12.8)

## [v0.12.7](https://github.com/youzan/vant/tree/v0.12.7) (2018-01-31)
[Full Changelog](https://github.com/youzan/vant/compare/v0.12.6...v0.12.7)

## [v0.12.6](https://github.com/youzan/vant/tree/v0.12.6) (2018-01-25)
[Full Changelog](https://github.com/youzan/vant/compare/v0.12.5...v0.12.6)

## [v0.12.5](https://github.com/youzan/vant/tree/v0.12.5) (2018-01-23)
[Full Changelog](https://github.com/youzan/vant/compare/v0.12.4...v0.12.5)

## [v0.12.4](https://github.com/youzan/vant/tree/v0.12.4) (2018-01-18)
[Full Changelog](https://github.com/youzan/vant/compare/v0.12.3...v0.12.4)

## [v0.12.3](https://github.com/youzan/vant/tree/v0.12.3) (2018-01-12)
[Full Changelog](https://github.com/youzan/vant/compare/v0.12.2...v0.12.3)

## [v0.12.2](https://github.com/youzan/vant/tree/v0.12.2) (2018-01-08)
[Full Changelog](https://github.com/youzan/vant/compare/v0.12.1...v0.12.2)

## [v0.12.1](https://github.com/youzan/vant/tree/v0.12.1) (2018-01-05)
[Full Changelog](https://github.com/youzan/vant/compare/v0.12.0...v0.12.1)

## [v0.12.0](https://github.com/youzan/vant/tree/v0.12.0) (2017-12-29)
[Full Changelog](https://github.com/youzan/vant/compare/v0.11.15...v0.12.0)

## [v0.11.15](https://github.com/youzan/vant/tree/v0.11.15) (2017-12-25)
[Full Changelog](https://github.com/youzan/vant/compare/v0.11.14...v0.11.15)

## [v0.11.14](https://github.com/youzan/vant/tree/v0.11.14) (2017-12-21)
[Full Changelog](https://github.com/youzan/vant/compare/v0.11.13...v0.11.14)

## [v0.11.13](https://github.com/youzan/vant/tree/v0.11.13) (2017-12-19)
[Full Changelog](https://github.com/youzan/vant/compare/v0.11.12...v0.11.13)

## [v0.11.12](https://github.com/youzan/vant/tree/v0.11.12) (2017-12-15)
[Full Changelog](https://github.com/youzan/vant/compare/v0.11.11...v0.11.12)

## [v0.11.11](https://github.com/youzan/vant/tree/v0.11.11) (2017-12-13)
[Full Changelog](https://github.com/youzan/vant/compare/v0.11.10...v0.11.11)

## [v0.11.10](https://github.com/youzan/vant/tree/v0.11.10) (2017-12-12)
[Full Changelog](https://github.com/youzan/vant/compare/v0.11.9...v0.11.10)

## [v0.11.9](https://github.com/youzan/vant/tree/v0.11.9) (2017-12-11)
[Full Changelog](https://github.com/youzan/vant/compare/v0.11.8...v0.11.9)

## [v0.11.8](https://github.com/youzan/vant/tree/v0.11.8) (2017-12-08)
[Full Changelog](https://github.com/youzan/vant/compare/v0.11.7...v0.11.8)

## [v0.11.7](https://github.com/youzan/vant/tree/v0.11.7) (2017-12-07)
[Full Changelog](https://github.com/youzan/vant/compare/v0.11.6...v0.11.7)

## [v0.11.6](https://github.com/youzan/vant/tree/v0.11.6) (2017-12-07)
[Full Changelog](https://github.com/youzan/vant/compare/v0.11.5...v0.11.6)

## [v0.11.5](https://github.com/youzan/vant/tree/v0.11.5) (2017-12-04)
[Full Changelog](https://github.com/youzan/vant/compare/v0.11.4...v0.11.5)

## [v0.11.4](https://github.com/youzan/vant/tree/v0.11.4) (2017-11-30)
[Full Changelog](https://github.com/youzan/vant/compare/v0.11.3...v0.11.4)

## [v0.11.3](https://github.com/youzan/vant/tree/v0.11.3) (2017-11-28)
[Full Changelog](https://github.com/youzan/vant/compare/v0.11.2...v0.11.3)

## [v0.11.2](https://github.com/youzan/vant/tree/v0.11.2) (2017-11-24)
[Full Changelog](https://github.com/youzan/vant/compare/v0.11.1...v0.11.2)

## [v0.11.1](https://github.com/youzan/vant/tree/v0.11.1) (2017-11-24)
[Full Changelog](https://github.com/youzan/vant/compare/v0.11.0...v0.11.1)

## [v0.11.0](https://github.com/youzan/vant/tree/v0.11.0) (2017-11-17)
[Full Changelog](https://github.com/youzan/vant/compare/v0.10.9...v0.11.0)

## [v0.10.9](https://github.com/youzan/vant/tree/v0.10.9) (2017-11-15)
[Full Changelog](https://github.com/youzan/vant/compare/v0.10.8...v0.10.9)

## [v0.10.8](https://github.com/youzan/vant/tree/v0.10.8) (2017-11-11)
[Full Changelog](https://github.com/youzan/vant/compare/v0.10.7...v0.10.8)

## [v0.10.7](https://github.com/youzan/vant/tree/v0.10.7) (2017-11-08)
[Full Changelog](https://github.com/youzan/vant/compare/v0.10.6...v0.10.7)

## [v0.10.6](https://github.com/youzan/vant/tree/v0.10.6) (2017-11-06)
[Full Changelog](https://github.com/youzan/vant/compare/v0.10.5...v0.10.6)

## [v0.10.5](https://github.com/youzan/vant/tree/v0.10.5) (2017-10-30)
[Full Changelog](https://github.com/youzan/vant/compare/v0.10.4...v0.10.5)

## [v0.10.4](https://github.com/youzan/vant/tree/v0.10.4) (2017-10-26)
[Full Changelog](https://github.com/youzan/vant/compare/v0.10.3...v0.10.4)

## [v0.10.3](https://github.com/youzan/vant/tree/v0.10.3) (2017-10-25)
[Full Changelog](https://github.com/youzan/vant/compare/v0.10.2...v0.10.3)

## [v0.10.2](https://github.com/youzan/vant/tree/v0.10.2) (2017-10-20)
[Full Changelog](https://github.com/youzan/vant/compare/v0.10.1...v0.10.2)

## [v0.10.1](https://github.com/youzan/vant/tree/v0.10.1) (2017-10-18)
[Full Changelog](https://github.com/youzan/vant/compare/v0.10.0...v0.10.1)

## [v0.10.0](https://github.com/youzan/vant/tree/v0.10.0) (2017-10-13)
[Full Changelog](https://github.com/youzan/vant/compare/v0.9.12...v0.10.0)

## [v0.9.12](https://github.com/youzan/vant/tree/v0.9.12) (2017-10-11)
[Full Changelog](https://github.com/youzan/vant/compare/v0.9.11...v0.9.12)

## [v0.9.11](https://github.com/youzan/vant/tree/v0.9.11) (2017-10-11)
[Full Changelog](https://github.com/youzan/vant/compare/v0.9.10...v0.9.11)

## [v0.9.10](https://github.com/youzan/vant/tree/v0.9.10) (2017-10-09)
[Full Changelog](https://github.com/youzan/vant/compare/v0.9.9...v0.9.10)

## [v0.9.9](https://github.com/youzan/vant/tree/v0.9.9) (2017-09-26)
[Full Changelog](https://github.com/youzan/vant/compare/v0.9.8...v0.9.9)

## [v0.9.8](https://github.com/youzan/vant/tree/v0.9.8) (2017-09-24)
[Full Changelog](https://github.com/youzan/vant/compare/v0.9.7...v0.9.8)

## [v0.9.7](https://github.com/youzan/vant/tree/v0.9.7) (2017-09-21)
[Full Changelog](https://github.com/youzan/vant/compare/v0.9.6...v0.9.7)

## [v0.9.6](https://github.com/youzan/vant/tree/v0.9.6) (2017-09-20)
[Full Changelog](https://github.com/youzan/vant/compare/v0.9.4...v0.9.6)

## [v0.9.4](https://github.com/youzan/vant/tree/v0.9.4) (2017-09-15)
[Full Changelog](https://github.com/youzan/vant/compare/v0.9.3...v0.9.4)

## [v0.9.3](https://github.com/youzan/vant/tree/v0.9.3) (2017-09-13)
[Full Changelog](https://github.com/youzan/vant/compare/v0.9.2...v0.9.3)

## [v0.9.2](https://github.com/youzan/vant/tree/v0.9.2) (2017-09-08)
[Full Changelog](https://github.com/youzan/vant/compare/v0.9.1...v0.9.2)

## [v0.9.1](https://github.com/youzan/vant/tree/v0.9.1) (2017-09-07)
[Full Changelog](https://github.com/youzan/vant/compare/v0.9.0...v0.9.1)

## [v0.9.0](https://github.com/youzan/vant/tree/v0.9.0) (2017-09-07)
[Full Changelog](https://github.com/youzan/vant/compare/v0.8.9...v0.9.0)

## [v0.8.9](https://github.com/youzan/vant/tree/v0.8.9) (2017-09-01)
[Full Changelog](https://github.com/youzan/vant/compare/v0.8.8...v0.8.9)

## [v0.8.8](https://github.com/youzan/vant/tree/v0.8.8) (2017-09-01)
[Full Changelog](https://github.com/youzan/vant/compare/v0.8.7...v0.8.8)

## [v0.8.7](https://github.com/youzan/vant/tree/v0.8.7) (2017-08-29)
[Full Changelog](https://github.com/youzan/vant/compare/v0.8.6...v0.8.7)

## [v0.8.6](https://github.com/youzan/vant/tree/v0.8.6) (2017-08-24)
[Full Changelog](https://github.com/youzan/vant/compare/v0.8.5...v0.8.6)

## [v0.8.5](https://github.com/youzan/vant/tree/v0.8.5) (2017-08-21)
[Full Changelog](https://github.com/youzan/vant/compare/v0.8.4...v0.8.5)

## [v0.8.4](https://github.com/youzan/vant/tree/v0.8.4) (2017-08-18)
[Full Changelog](https://github.com/youzan/vant/compare/v0.8.3...v0.8.4)

## [v0.8.3](https://github.com/youzan/vant/tree/v0.8.3) (2017-08-18)
[Full Changelog](https://github.com/youzan/vant/compare/v0.8.1...v0.8.3)

## [v0.8.1](https://github.com/youzan/vant/tree/v0.8.1) (2017-08-18)
[Full Changelog](https://github.com/youzan/vant/compare/v0.8.0...v0.8.1)

## [v0.8.0](https://github.com/youzan/vant/tree/v0.8.0) (2017-08-17)
[Full Changelog](https://github.com/youzan/vant/compare/v0.7.10...v0.8.0)

## [v0.7.10](https://github.com/youzan/vant/tree/v0.7.10) (2017-08-16)
[Full Changelog](https://github.com/youzan/vant/compare/v0.7.8...v0.7.10)

## [v0.7.8](https://github.com/youzan/vant/tree/v0.7.8) (2017-08-10)
[Full Changelog](https://github.com/youzan/vant/compare/v0.7.7...v0.7.8)

## [v0.7.7](https://github.com/youzan/vant/tree/v0.7.7) (2017-08-09)
[Full Changelog](https://github.com/youzan/vant/compare/v0.7.6...v0.7.7)

## [v0.7.6](https://github.com/youzan/vant/tree/v0.7.6) (2017-08-08)
[Full Changelog](https://github.com/youzan/vant/compare/v0.7.5...v0.7.6)

## [v0.7.5](https://github.com/youzan/vant/tree/v0.7.5) (2017-08-08)
[Full Changelog](https://github.com/youzan/vant/compare/v0.7.3...v0.7.5)

## [v0.7.3](https://github.com/youzan/vant/tree/v0.7.3) (2017-08-04)
[Full Changelog](https://github.com/youzan/vant/compare/v0.7.2...v0.7.3)

## [v0.7.2](https://github.com/youzan/vant/tree/v0.7.2) (2017-07-31)
[Full Changelog](https://github.com/youzan/vant/compare/v0.6.6...v0.7.2)

## [v0.6.6](https://github.com/youzan/vant/tree/v0.6.6) (2017-07-15)
[Full Changelog](https://github.com/youzan/vant/compare/v0.6.5...v0.6.6)

## [v0.6.5](https://github.com/youzan/vant/tree/v0.6.5) (2017-07-11)
[Full Changelog](https://github.com/youzan/vant/compare/v0.6.4...v0.6.5)

## [v0.6.4](https://github.com/youzan/vant/tree/v0.6.4) (2017-07-06)
[Full Changelog](https://github.com/youzan/vant/compare/v0.6.3...v0.6.4)

## [v0.6.3](https://github.com/youzan/vant/tree/v0.6.3) (2017-07-04)
[Full Changelog](https://github.com/youzan/vant/compare/v0.6.2...v0.6.3)

## [v0.6.2](https://github.com/youzan/vant/tree/v0.6.2) (2017-06-26)
[Full Changelog](https://github.com/youzan/vant/compare/v0.6.1...v0.6.2)

## [v0.6.1](https://github.com/youzan/vant/tree/v0.6.1) (2017-06-19)
[Full Changelog](https://github.com/youzan/vant/compare/v0.6.0...v0.6.1)

## [v0.6.0](https://github.com/youzan/vant/tree/v0.6.0) (2017-06-15)
[Full Changelog](https://github.com/youzan/vant/compare/v0.5.12...v0.6.0)

## [v0.5.12](https://github.com/youzan/vant/tree/v0.5.12) (2017-06-02)
[Full Changelog](https://github.com/youzan/vant/compare/v0.5.11...v0.5.12)

## [v0.5.11](https://github.com/youzan/vant/tree/v0.5.11) (2017-05-25)
[Full Changelog](https://github.com/youzan/vant/compare/v0.5.10...v0.5.11)

## [v0.5.10](https://github.com/youzan/vant/tree/v0.5.10) (2017-05-25)
[Full Changelog](https://github.com/youzan/vant/compare/v0.5.9...v0.5.10)

## [v0.5.9](https://github.com/youzan/vant/tree/v0.5.9) (2017-05-25)
[Full Changelog](https://github.com/youzan/vant/compare/v0.5.8...v0.5.9)

## [v0.5.8](https://github.com/youzan/vant/tree/v0.5.8) (2017-05-25)
[Full Changelog](https://github.com/youzan/vant/compare/v0.5.7...v0.5.8)

## [v0.5.7](https://github.com/youzan/vant/tree/v0.5.7) (2017-05-19)
[Full Changelog](https://github.com/youzan/vant/compare/v0.5.6...v0.5.7)

## [v0.5.6](https://github.com/youzan/vant/tree/v0.5.6) (2017-05-15)
[Full Changelog](https://github.com/youzan/vant/compare/v0.5.4...v0.5.6)

## [v0.5.4](https://github.com/youzan/vant/tree/v0.5.4) (2017-05-09)
[Full Changelog](https://github.com/youzan/vant/compare/v0.5.3...v0.5.4)

## [v0.5.3](https://github.com/youzan/vant/tree/v0.5.3) (2017-04-27)
[Full Changelog](https://github.com/youzan/vant/compare/v0.5.2...v0.5.3)

## [v0.5.2](https://github.com/youzan/vant/tree/v0.5.2) (2017-04-26)
[Full Changelog](https://github.com/youzan/vant/compare/v0.5.1...v0.5.2)

## [v0.5.1](https://github.com/youzan/vant/tree/v0.5.1) (2017-04-24)
[Full Changelog](https://github.com/youzan/vant/compare/v0.5.0...v0.5.1)

## [v0.5.0](https://github.com/youzan/vant/tree/v0.5.0) (2017-04-23)
[Full Changelog](https://github.com/youzan/vant/compare/v0.1.2...v0.5.0)

## [v0.1.2](https://github.com/youzan/vant/tree/v0.1.2) (2017-04-14)
[Full Changelog](https://github.com/youzan/vant/compare/v0.1.1...v0.1.2)

## [v0.1.1](https://github.com/youzan/vant/tree/v0.1.1) (2017-04-13)
[Full Changelog](https://github.com/youzan/vant/compare/v0.1.0...v0.1.1)

## [v0.1.0](https://github.com/youzan/vant/tree/v0.1.0) (2017-04-11)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.50...v0.1.0)

## [v0.0.50](https://github.com/youzan/vant/tree/v0.0.50) (2017-04-05)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.49...v0.0.50)

## [v0.0.49](https://github.com/youzan/vant/tree/v0.0.49) (2017-04-01)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.48...v0.0.49)

## [v0.0.48](https://github.com/youzan/vant/tree/v0.0.48) (2017-03-31)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.47...v0.0.48)

## [v0.0.47](https://github.com/youzan/vant/tree/v0.0.47) (2017-03-30)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.46...v0.0.47)

## [v0.0.46](https://github.com/youzan/vant/tree/v0.0.46) (2017-03-30)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.45...v0.0.46)

## [v0.0.45](https://github.com/youzan/vant/tree/v0.0.45) (2017-03-29)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.44...v0.0.45)

## [v0.0.44](https://github.com/youzan/vant/tree/v0.0.44) (2017-03-26)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.43...v0.0.44)

## [v0.0.43](https://github.com/youzan/vant/tree/v0.0.43) (2017-03-25)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.42...v0.0.43)

## [v0.0.42](https://github.com/youzan/vant/tree/v0.0.42) (2017-03-24)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.41...v0.0.42)

## [v0.0.41](https://github.com/youzan/vant/tree/v0.0.41) (2017-03-22)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.40...v0.0.41)

## [v0.0.40](https://github.com/youzan/vant/tree/v0.0.40) (2017-03-22)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.39...v0.0.40)

## [v0.0.39](https://github.com/youzan/vant/tree/v0.0.39) (2017-03-22)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.38...v0.0.39)

## [v0.0.38](https://github.com/youzan/vant/tree/v0.0.38) (2017-03-19)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.37...v0.0.38)

## [v0.0.37](https://github.com/youzan/vant/tree/v0.0.37) (2017-03-16)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.31...v0.0.37)

## [v0.0.31](https://github.com/youzan/vant/tree/v0.0.31) (2017-03-15)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.30...v0.0.31)

## [v0.0.30](https://github.com/youzan/vant/tree/v0.0.30) (2017-03-10)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.29...v0.0.30)

## [v0.0.29](https://github.com/youzan/vant/tree/v0.0.29) (2017-03-10)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.28...v0.0.29)

## [v0.0.28](https://github.com/youzan/vant/tree/v0.0.28) (2017-03-10)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.27...v0.0.28)

## [v0.0.27](https://github.com/youzan/vant/tree/v0.0.27) (2017-03-10)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.26...v0.0.27)

## [v0.0.26](https://github.com/youzan/vant/tree/v0.0.26) (2017-03-10)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.25...v0.0.26)

## [v0.0.25](https://github.com/youzan/vant/tree/v0.0.25) (2017-03-09)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.24...v0.0.25)

## [v0.0.24](https://github.com/youzan/vant/tree/v0.0.24) (2017-03-09)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.23...v0.0.24)

## [v0.0.23](https://github.com/youzan/vant/tree/v0.0.23) (2017-03-08)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.22...v0.0.23)

## [v0.0.22](https://github.com/youzan/vant/tree/v0.0.22) (2017-03-08)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.21...v0.0.22)

## [v0.0.21](https://github.com/youzan/vant/tree/v0.0.21) (2017-03-08)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.20...v0.0.21)

## [v0.0.20](https://github.com/youzan/vant/tree/v0.0.20) (2017-03-08)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.19...v0.0.20)

## [v0.0.19](https://github.com/youzan/vant/tree/v0.0.19) (2017-03-08)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.18...v0.0.19)

## [v0.0.18](https://github.com/youzan/vant/tree/v0.0.18) (2017-03-08)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.17...v0.0.18)

## [v0.0.17](https://github.com/youzan/vant/tree/v0.0.17) (2017-03-07)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.15...v0.0.17)

## [v0.0.15](https://github.com/youzan/vant/tree/v0.0.15) (2017-03-07)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.14...v0.0.15)

## [v0.0.14](https://github.com/youzan/vant/tree/v0.0.14) (2017-03-03)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.13...v0.0.14)

## [v0.0.13](https://github.com/youzan/vant/tree/v0.0.13) (2017-03-03)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.12...v0.0.13)

## [v0.0.12](https://github.com/youzan/vant/tree/v0.0.12) (2017-03-02)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.11...v0.0.12)

## [v0.0.11](https://github.com/youzan/vant/tree/v0.0.11) (2017-03-02)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.10...v0.0.11)

## [v0.0.10](https://github.com/youzan/vant/tree/v0.0.10) (2017-03-02)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.9...v0.0.10)

## [v0.0.9](https://github.com/youzan/vant/tree/v0.0.9) (2017-03-02)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.8...v0.0.9)

## [v0.0.8](https://github.com/youzan/vant/tree/v0.0.8) (2017-03-01)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.7...v0.0.8)

## [v0.0.7](https://github.com/youzan/vant/tree/v0.0.7) (2017-02-28)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.4...v0.0.7)

## [v0.0.4](https://github.com/youzan/vant/tree/v0.0.4) (2017-02-27)
[Full Changelog](https://github.com/youzan/vant/compare/v0.0.3...v0.0.4)

## [v0.0.3](https://github.com/youzan/vant/tree/v0.0.3) (2017-02-27)
[Full Changelog](https://github.com/youzan/vant/compare/2.3.0...v0.0.3)



\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*
# react-native-flowlayout

[ ![release](https://img.shields.io/badge/Release-V0.0.2-blue.svg)](https://github.com/a741762308/react-native-flowlayout/releases)
[![License MIT](http://img.shields.io/badge/license-MIT-orange.svg)](https://raw.githubusercontent.com/a741762308/react-native-flowlayout/master/LICENSE)

FlowLayout 标签布局，适用于Android与iOS

## 效果图

![](https://raw.githubusercontent.com/a741762308/react-native-flowlayout/master/Screenshots/react-native-flowlayout-screenshots.gif)

## 安装
终端run `npm i react-native-flowlayout --save`

## 使用
js中引入`import FlowLayout from 'react-native-flowlayout'`

render方法中
```
<FlowLayout/>
```
or
```
<FlowLayout ref="flow" multiselect={false} dataValue={this.state.monitorValue}/>
```

## API
|Props|Type|Default|Description|
| --- | --- | --- | --- |
|style|View.propTypes.style||flowlayout style|
|dataValue| PropTypes.array|["标签1", "标签2", "标签3标签4标签4", "标签4", "标签5", "标签5标签6", "标签7", "标签8", "标签9", "标签10标签8"]|数据|
|multiselect|PropTypes.bool|true|支持多选|

- getSelectedPosition
返回已选中的位置，类型[]
- resetData
重置选中状态即不选中

## 说明
欢迎大家issue、star、pull request
## License
MIT

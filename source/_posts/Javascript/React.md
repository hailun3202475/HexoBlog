title: "React"
---

VUE 
双向绑定，强调在不同组件中同步状态REACT 只有单一数据源（状态提升和单向数据流），在应用中保持自上而下的数据流，在有数据源的地方做综合处理

npx 调用包里的某个模块 npm run 会新建一个shell执行脚本命令，将node_modules 模块加入path变量，执行结束后将path命令恢复原样

**React Hook**

- 使用函数式组件代替class组件的写法（没有破坏性改动 / 百分之百向后兼容 / 完全可选 / 没有计划移除Class）

- 组件很难复用状态逻辑

- 业务复杂难以理解，尤其是生命周期

- React 组件一直是函数，使用Hook完全拥抱函数

**Effect Hook** react 更新DOM后：发送一个网络请求，主动变更DOM，记录日志）

- 无需清除的effect
- 需要清除的effect 在下一次的render后 remove effect 


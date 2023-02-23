# 快速开始

### 安装组件库

```bash
npm i mooc-ui-dk
```

### 使用组件库
> 在main.js 中引用组件库

```javascript
import 'mooc-ui-dk/dist/css/index.css';
import MUI from 'mooc-ui-dk';
Vue.use(MUI);

//按需引入
import 'mooc-ui-dk/dist/css/demo.css';
import { Demo } from 'mooc-ui-dk';
Vue.use(MUI);
```
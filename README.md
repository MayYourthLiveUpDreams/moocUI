# mooc-ui9 组件库

### 快速开始

#### 1.安装组件库

```bash
npm i mooc-ui9
```

#### 2.引用组件库
```javascript
// 全部引入
import 'mooc-ui9/dist/css/index.css';
import 'MUI' from 'mooc-ui9';
Vue.use(MUI);

// 按需引入
import 'mooc-ui9/dist/css/demo.css';
import { Demo } from 'mooc-ui9';
Vue.use(Demo);
```
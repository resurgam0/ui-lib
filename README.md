# ui-lib组件库

### 快速开始

#### 1.安装组件库

```bash
npm i ui-lib-test
```

#### 2.引用组件库
```javascipt
//全部引入
import 'mooc-ui/dist/css/index.css';
import MUI from 'mooc-ui'
Vue.use(MUI)
```
//按需引用
import 'mooc-ui/dist/css/demo.css'
import {Demo} from 'mooc-ui'
Vue.use(Demo)
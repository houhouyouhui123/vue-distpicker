## vue-distpicker

> A simple Vue component for picking provinces, cities and districts of China.

## Installation and Use

```
$ npm install vue-distpicker --save
```

```
import Distpicker from 'vue-distpicker';
export default {
  components: {
    Distpicker
  }
}
```

or

```
import Vue from 'vue';
import Distpicker from 'vue-distpicker';
Vue.component('Distpicker', Distpicker);
```
## Props
| Name | Type | Description |
| --- | --- | --- |
| ids | Array | 默认省市区的 id |
| onchange | Function | 回调， 三个参数分别为省市区的 id |
| prov | String | 省份选择框 name 值 |
| city | String | 城市选择框 name 值 |
| dist | String | 地区限制框 name 值 |


## LICENSE

MIT

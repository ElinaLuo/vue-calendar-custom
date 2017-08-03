## vue-calendar-custom

[参考了vue-calendar](https://github.com/jinzhe/vue-calendar)，在此基础上做了小改动

#vue-calendar

- 日历组件
- 可自定义日期下面展示文案，例如价钱


```
npm install

npm start

```

## API

参数 | 格式 | 默认值 | 是否必写 | 描述
---|---|---|---|---
value | array | [] | 否 | 日历选中的值，例如[2017,8,3]
begin | array | [] | 否 | 日历限制的开始日期，格式同value
end | array | [] | 否 | 日历限制的结束日期，格式同value
range | Bool | false | 否 | 是否展示日历区间
zero | Bool | true | 否 | 月和日为单数时，是否补0
lunar | Bool | false | 否 | 是否显示农历
weeks | array | [] | 否 | 自定义周展示文案，从周日到周六
months | array | [] | 否 | 自定义月份展示文案，从一月到十二月
events | Object | {} | 否 | 自定义某天的展示文案，例如{'2017-08-14':'$408','2017-08-15':'$460','2017-08-16':'$500'}


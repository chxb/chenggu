# 简介
根据农历年/月/日/时换算称骨重量及获取袁天罡称骨歌诀信息。
```javascript
/**
 * 根据农历年/月/日/时换算称骨重量
 * @param year  干支年，六十甲子的顺序，从1开始.
 * @param month 农历月，从1开始
 * @param day   日,从1开始
 * @param hour  时辰,从子时(数字0)开始，亥时(数字11)止。
 * @return 骨重
 */
function chenggu(year,  month,  day,  hour) {
  ...
}

/**
 * 查询称骨歌决.
 * @param {string} zong 骨重
 * @param {boolean} isman 性别
 * @returns 歌决
 */
function chengguInfo(zong, isman)
  ...
}

/**
 * 查询称骨歌决详细解释.
 * @param {string} zong 骨重
 * @param {boolean} isman 性别
 * @returns 详细解释
 */
function chengguDetails(zong, isman) {
  ...
}
```

# 应用示例
本称骨算法已应用于吉时雨排盘软件：https://ji.js.cn

# 关于作者
xianbo.chen@gmail.com


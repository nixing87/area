# Area - 中国省市区数据
省份城市区县数据，包含`国家标准行政区划代码 adcode`，整理成了 sql、json 形式，数据来源于百度地图。

## 特色
* 省市区之间通过 adcode 和 id 关联；
* sql 可直接执行入库；
* 多种数据格式

## 文件结构说明
    ├── README.md
    ├── json
    │   ├── all_area.json    所有省市区
    │   ├── all_area_with_adcode_key.json    所有省市区（使用 adcode 作为键）
    │   ├── all_city.json    所有城市
    │   ├── all_city_with_adcode_key.json    所有城市（使用 adcode 作为键）
    │   ├── all_district.json    所有区县
    │   ├── all_district_with_adcode_key.json    所有区县（使用 adcode 作为键）
    │   ├── all_province.json    所有省份
    │   └── all_province_with_adcode_key.json    所有省份（使用 adcode 作为键）
    └── sql
        ├── area_city.sql    所有城市
        ├── area_district.sql    所有区县
        └── area_province.sql    所有省份

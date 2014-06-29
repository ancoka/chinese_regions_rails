# chinese_regions_rails

中国省市区县数据库，包含 行政编码，邮政编码，地区拼音和简拼。 数据来源 https://github.com/xixilive/chinese_regions_db

## 使用

Gemfile

```
gem 'chinese_regions_rails'
```

generate `Region` model

```
rails g chinese_regions:install
```

db migration and seed

```
rake db:migrate
rake db:seed:regions
```

---
title: "First Post"
date: 2021-12-15T13:58:16+08:00
draft: true
toc: false
images:
tags:
  - untagged
---

## 平台

- 接口调用次数统计

  ```sql
  use platform;
  select app_id,count(*),api_hash from billing_api_consumption group by app_id,api_hash
  ```

  接口和apihash的对应关系

  SubmitPulseTest-- -832952479
  GetReport-- -488801682
  SearchReports-- -913874297
  GetRawData-- -69459196

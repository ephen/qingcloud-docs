---
title: "产品动态"
date: 2020-09-13
collapsible: false
weight: 12

product:
    - time: 2020-05-15
      title: 开放雅加达（ap3）区
      content: 青云QingCloud 雅加达区日前正式开放对象存储服务。此次对象存储服务在雅加达区的开放，将为出海及海外企业提供面向海量非结构化数据的通用数据平台，提供安全可靠、低成本的云存储服务，进一步满足中国企业国际化业务的开展、国际化企业全球市场的开拓，以及海外本地企业对云能力的需求。这是青云QingCloud 自 2019 年 12 月正式开放雅加达区提供公有云服务以来，又一次重要的能力输出。<a target="_blank" href="https://log.qingcloud.com/archives/7013">更多详细内容</a>

    - time: 2020-02-23
      title: 新增 Append Object 接口
      content: 用于以追加写的方式上传对象到存储桶，通过 Append Object 接口创建的对象类型为 appendable。
      # todo update url
      url: /storage/object-storage/api

    - time: 2019-09-04
      title: List Buckets 接口支持分页
      url: /storage/object-storage/api

    - time: 2018-08-01
      title: 图片处理功能增加部分 Exif 信息支持
      url: /storage/object-storage/api

    - time: 2018-08-01
      title: List Objects (Bucket Get) 接口 增加 "has_more" 标志
      url: /storage/object-storage/api

    - time: 2018-05-16
      title: 上线生命周期功能
      url: /storage/object-storage/api

    - time: 2018-05-16
      title: 上线低频存储功能
      url: /storage/object-storage/api

    - time: 2018-03-15
      title: 发布挂载盘 Qsfs 和 Elastic Drive
      content: QingStor 对象存储提供了多种命令行和GUI工具，便于用户高效操作、管理对象存储资源，迁移数据到对象存储。
      url: /storage/object-storage/api

    - time: 2017-12-08
      title: 兼容 AWS S3 v2/v4 参数签名
      content: 为了使众多基于 AWS S3 开发的应用程序、SDK、及第三方服务在不修改代码的前提下，更容易的接入到 QingStor，QingStor 兼容了 AWS S3 的接口。
      url: /storage/object-storage/api

    - time: 2017-12-08
      title: 兼容 S3 Multipart Copy 接口
      url: /storage/object-storage/api

    - time: 2017-12-03
      title: 新增自定义元数据功能
      content: Put Object 支持请求头 Cache-Control、Content-Disposition、Content-Encoding、Expires。 兼容S3各接口的元数据功能。 所有返回的 x-qs-* Header 均统一为小写
      url: /storage/object-storage/api

    - time: 2017-10-10
      title: 新增列取对象存储可用区接口
      url: /storage/object-storage/api

    - time: 2017-08-28
      title: 兼容 S3 Get Bucket Location 接口
      url: /storage/object-storage/api

    - time: 2017-07-19
      title: 新增图片处理功能
      url: /storage/object-storage/api

    - time: 2017-06-28
      title: 新增第三方图片鉴黄功能
      url: /storage/object-storage/api

    - time: 2017-05-30
      title: 支持分段复制
      url: /storage/object-storage/api

    - time: 2017-05-02
      title: 分段上传改进，支持同一个 object 的并行多个上传过程，相互不影响
      url: /storage/object-storage/api

    - time: 2017-01-13
      title: 新增列取 Multipart Uploads 接口
      url: /storage/object-storage/api

    - time: 2016-12-21
      title: 新增对象抓取 (fetch) 接口
      url: /storage/object-storage/api

    - time: 2016-12-16
      title: 接口 GET Object 支持设置响应头
      url: /storage/object-storage/api

    - time: 2016-11-09
      title: 新增对象批量删除接口
      url: /storage/object-storage/api

    - time: 2016-10-17
      title: 新增对象移动接口
      url: /storage/object-storage/api

    - time: 2016-10-17
      title: 支持对象数据加密
      url: /storage/object-storage/api

    - time: 2016-09-28
      title: 新增存储空间外部镜像设置
      url: /storage/object-storage/api

    - time: 2016-09-12
      title: 新增表单上传
      url: /storage/object-storage/api

    - time: 2016-08-15
      title: 接口 GET Bucket 响应体增加元素 etag
      url: /storage/object-storage/api

    - time: 2016-08-15
      title: 错误返回中，响应体增加元素 request_id
      url: /storage/object-storage/api

    - time: 2016-08-04
      title: 新增对象拷贝接口，支持存储空间内和跨存储空间的对象复制操作
      # content: PUT Object - Copy,- |
      url: /storage/object-storage/api

    - time: 2016-08-04
      title: 新增存储空间策略设置接口，支持存储策略
      url: /storage/object-storage/api

    - time: 2016-08-04
      title: 新增跨域访问控制 (CORS) 接口，支持用户自定义设置 CORS 策略
      url: /storage/object-storage/api

    - time: 2016-08-04
      title: 增加错误码 bad_digest，当用户请求头 Content-MD5 与服务端计算不符时返回此错误
      url: /storage/object-storage/api

    - time: 2016-07-15
      title: 默认文件类型由 application/oct-stream 变更为 application/octet-stream
      url: /storage/object-storage/api

    - time: 2016-07-15
      title: 接口 List Parts 响应体增加元素 etag
      url: /storage/object-storage/api

    - time: 2016-07-15
      title: 接口 List Objects 字段名 marker 变更为 next_marker
      url: /storage/object-storage/api

    - time: 2016-07-15
      title: 请求头 Content-MD5 字段值改为 base64 编码
      url: /storage/object-storage/api

    - time: 2016-06-18
      title: 兼容 AWS S3 接口
      url: /storage/object-storage/api

---

<!-- 设置上述参数可生成产品动态页  -->

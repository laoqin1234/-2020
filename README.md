# 武汉新型冠状病毒防疫信息收集平台

[![NPM Dependency](https://david-dm.org/EasyWebApp/wuhan2020.svg)][1]
[![Build Status](https://travis-ci.com/EasyWebApp/wuhan2020.svg?branch=master)][2]

针对 2020 年初在武汉爆发的新型冠状病毒疫情，本项目旨在收集各医院、酒店、工厂、物流、捐赠、捐款、预防、治疗、动态等信息，统一收集，统一发布，以便各方之间进行信息互通，有效调配社会资源。

# 分类

本平台仅为信息收集平台，而非信息发布平台。
本平台收集信息包含如下几类信息，请分别申报填写。
为保证信息有效性，关于医院、酒店、物流、捐款等信息，**_务必注明官方链接_**。
工厂信息申报，**_请提供资质证明，如经营许可、工商信息等_**，以保证供应商有效性。

本平台信息暂以 csv 文件格式提交存储，以便进行前端获取结构化数据。

## 医院

医院信息主要指目前物资与资源紧缺医院的申报信息，包含医院名称、省、市、县/区、医院地址、目前医护人员数量、每日所需各类医护用具数量、相关官方链接、联系方式、备注。

具体数据信息请点击[这里](data/Hospital.yml)。

## 酒店

医护人员为保证隔离性，应集中休息，以免与家人交叉传染，需要酒店提供临时住宿。信息包含酒店名称、酒店地址、酒店可提供床位数、联系方式。

具体数据信息请点击[这里](data/HOTEL.csv)

## 物流

各大物流都已开始提供免费物资物流，但均由各自官方渠道发布，信息不对称。物流名称、物流区域、物流能力、官方链接、联系方式。

具体数据信息请点击[这里](data/Logistics.yml)

## 生产

目前大量捐款到位，但生产厂商复工情况未知，可提供生产厂商信息，方便快速联系。厂商名称、资质证明、厂商位置、生产物资类型、产能、联系方式。

具体数据信息请点击[这里](data/FACTORY.csv)

## 捐款

各类平台捐款方式，保证捐款信息的有效性。捐款发起方、捐款方式、官方链接、联系方式、当前状态等。

具体数据信息请点击[这里](data/DONATION.csv)

## 国外捐赠资源

注意：这部分数据没有真实来源，请酌情考虑有效性

国外捐赠资源信息，包括：捐赠物资、数量、联系人、联系方式、出发地。

具体数据信息请点击[这里](DONATION_ABROAD.csv)


## 预防与治疗

收集相关疫情预防治疗信息，以图文形式提入项目。

## 义诊

收集各地义诊信息。包含义诊单位或个人、联系方式、备注等。

具体数据信息请点击[这里](data/CLINIC.csv)

## 动态

收集关于疫情的新闻动态。包含新闻标题、新闻概要、时间、媒体链接等。

具体数据信息请点击[这里](data/NEWS.csv)

# 贡献指南

请点击[这里](./CONTRIBUTION.md)

[1]: https://david-dm.org/EasyWebApp/wuhan2020
[2]: https://travis-ci.com/EasyWebApp/wuhan2020

# 201701 GCPUG.TW with Hadoop Taiwan合辦Meetup

## 本次活動介紹
本次活動為 Taiwan Hadoop User Group 與 Google Cloud Platform User Group (GCPUG) 一起舉辦，透過社群間的合作，讓講題更多樣化發展，大家在了解 Hadoop Ecosystem 的當下，也可以一起深入了解在 Google Cloud Platform 上的各項 Big Data 與 Computing Service 唷～

 
### Taiwan Hadoop User Group
我們是台灣的 Hadoop Ecosystem User Group，透過分享的力量，讓 Hadoop 帶領台灣的大資料環境向上成長，並且透過大家的分享與交流，讓知識交流無國界，歡迎對 Hadoop Ecosystem 的朋友們可以一起加入分享！

臉書粉絲團：https://fb.com/groups/hadoop.tw/

### Google Cloud Platform User Group
大家好，我們是 Google Cloud Platform User Group (GCPUG) 台灣分支，我們是一個Google Cloud Platform 相關技術的民間社群，成立的宗旨在分享與交換 Google Cloud Platform 上的一些技術與使用經驗。歡迎對 Google Cloud Platform 有興趣的朋友們可以共襄盛舉。

臉書粉絲團：https://fb.com/groups/GCPUG.TW/

## 報名頁面

http://gcpugtw.kktix.cc/events/meetup201701

## 時間

2017/01/21 9:00 - 17:30

## 地點

台北101 - Google辦公室 

## 本次活動議程


### 9:30 - 10:30 The journey of Moving from AWS ELK to GCP Data Pipeline
Speaker: 
Randy Huang, Data team leader of VMfive

Abstract:
This is a real case from VMfive to shifting ELK architecture from AWS. Currently GCP Data Pipeline provide us more efficiency and stable environment for running our service. 

* 直播URL: http://youtu.be/bH9e__8bT5k
* PPT: http://www.slideshare.net/randyviola/the-journey-of-moving-from-aws-elk-to-gcp-data-pipeline


### 10:45 - 11:45 Google Cloud Computing compares - GCE, GKE and GAE

Speaker:
Simon Su, Co-organizer of GCPUG.TW

Abstract:
Google provide different kinds of computing service, like: Google Computing Engine, Google Container Engine, Google App Engine. And I want to use a sample to let you know what is the different in these kinds of service. Maybe next time, you will have a batter way to deploy your service in Google Cloud!

* 直播URL: http://youtu.be/dsJLqQ-zets
* PPT: http://www.slideshare.net/peihsinsu/google-cloud-computing-compares-gce-gae-and-gke
* code: https://github.com/peihsinsu/gcpug-meetup-201701

### 11:45 - 13:30 Lunch & Welcome Lightly Talk

### 13:30 - 14:30 Hadoop 3 is coming -- what’s new and what’s next?

Speaker: 
Wei-Chiu Chuang, Apache Hadoop Committer/ Software Engineer, Cloudera

Abstract: 
Hadoop is becoming the foundation of many data architectures, and many new use cases are flocking to the Hadoop ecosystem. With new opportunities comes new challenges, and Hadoop 3 will be addressing some of these emerging challenges.
In this talk, I am going to highlight a few major features that will be shipped with Hadoop 3. In particular, a new storage architecture that reduces storage cost, a new architecture that scales compute better, improvement that makes Hadoop applications easier to develop, among others. Finally, I will also mention some new concepts that may one day be incorporated into Hadoop 4.

* 直播URL: http://youtu.be/ZlG_xidzzL4

### 14:45 - 15:45 Hadoop Compatible File System (HCFS) 初探

Speaker:
Jazz Wang, Co-founder of Hadoop.TW

Abstract:
Hadoop 提供了抽象化的 File System 類別，因此只要實作對應的 Java 類別，就可以讓 Hadoop 支援其他雲端的檔案系統。這些額外與 Hadoop 相容的檔案系統，統稱 HCFS。例如 Hadoop 0.10 就存在的 Amazon S3 (s3://) 支援，Hadoop 2.7 才正式納入的 Windows Azure Blob Storage (was://)。由 Ceph 官方提供的 cephfs:// 支援等。

本次分享將使用 Apache BigTop 來展示怎麼拿 hadoop distcp 指令來當作 Local File System 跟 Azure Blob Storage 之間的 rsync 指令、 探討三種不同的 S3 實作(s3:// , s3n:// , s3a://)，並簡略分享近期測試 CephFS 的心得。

PS. 若準備來得及，會追加 Google Cloud Storage Connector for Spark and Hadoop 。

[1] https://wiki.apache.org/hadoop/HCFS
[2] https://wiki.apache.org/hadoop/AmazonS3
[3] http://hadoop.apache.org/docs/r2.7.3/hadoop-azure/
[4] https://github.com/ceph/cephfs-hadoop
[5] https://cloud.google.com/.../google-cloud-storage-connector

* 直播URL: https://youtu.be/p1SKNSkZGPc

### 16:00 - 17:00 Apache Impala 在 ETL 的實作案例

Speaker:

陳之駿 Chih-Chun Chen, 炬識科技

Abstract:

Impala 是 Cloudera 所開發用於 Hadoop 的 SQL Query 工具，於 2016 年捐給 Apache 軟體基金會。用途與 Hive 相近，但是基於快速回應查詢結果的特性，非常適合用來作交互式的資料挖掘與調校分析式查詢。
這個場次將分享在每日以 TB 等級增加資料量的環境中，如何用 Impala 實做 data extract, data transfer and data load。

* 直播URL: https://m.youtube.com/watch?v=U0o6yLYdnjw&feature=youtu.be

### 17:00 - 17:30 Networking & Wellcome Lightly Talk again~

## 其他

* [活動留影](https://photos.google.com/share/AF1QipOTuBOP6ctVcEQv1HHy_VsMS-58NWU_tZtPaFmojQkWUKVJnrK5xmhjy3hduv-x6A?key=T0E4VFNFTDNlaDZzck9CMkkyaWZRQXNCM2h2c0Fn)
* 贊助單位
	* 感謝Google贊助場地(特別感謝Axa協助申請)
	* 感謝MiTAC提供美味的Pizza
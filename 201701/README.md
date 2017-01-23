# 201701 Meetup

## 報名頁面

http://gcpugtw.kktix.cc/events/meetup201701

## 時間

2017/01/21 9:00 - 17:30

## 地點

台北101 - Google辦公室 (確認中，暫定）

## 本次活動議程


### 9:30 - 10:30 The journey of Moving from AWS ELK to GCP Data Pipeline
Speaker: 
Randy Huang, Data team leader of VMfive

Abstract:
This is a real case from VMfive to shifting ELK architecture from AWS. Currently GCP Data Pipeline provide us more efficiency and stable environment for running our service. 


### 10:45 - 11:45 Google Cloud Computing compares - GCE, GKE and GAE

Speaker:
Simon Su, Co-organizer of GCPUG.TW

Abstract:
Google provide different kinds of computing service, like: Google Computing Engine, Google Container Engine, Google App Engine. And I want to use a sample to let you know what is the different in these kinds of service. Maybe next time, you will have a batter way to deploy your service in Google Cloud!

### 11:45 - 13:30 Lunch & Welcome Lightly Talk

### 13:30 - 14:30 Hadoop 3 is coming -- what’s new and what’s next?

Speaker: 
Wei-Chiu Chuang, Apache Hadoop Committer/ Software Engineer, Cloudera

Abstract: 
Hadoop is becoming the foundation of many data architectures, and many new use cases are flocking to the Hadoop ecosystem. With new opportunities comes new challenges, and Hadoop 3 will be addressing some of these emerging challenges.
In this talk, I am going to highlight a few major features that will be shipped with Hadoop 3. In particular, a new storage architecture that reduces storage cost, a new architecture that scales compute better, improvement that makes Hadoop applications easier to develop, among others. Finally, I will also mention some new concepts that may one day be incorporated into Hadoop 4.

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

### 16:00 - 17:00 Apache Impala 在 ETL 的實作案例

Speaker:

陳之駿 Chih-Chun Chen, 炬識科技

Abstract:

Impala 是 Cloudera 所開發用於 Hadoop 的 SQL Query 工具，於 2016 年捐給 Apache 軟體基金會。用途與 Hive 相近，但是基於快速回應查詢結果的特性，非常適合用來作交互式的資料挖掘與調校分析式查詢。
這個場次將分享在每日以 TB 等級增加資料量的環境中，如何用 Impala 實做 data extract, data transfer and data load。

### 17:00 - 17:30 Networking & Wellcome Lightly Talk again~



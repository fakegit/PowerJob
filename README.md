English | [简体中文](./README_zhCN.md)

<p align="center">
<img src="https://raw.githubusercontent.com/KFCFans/PowerJob/master/others/images/logo.png" alt="PowerJob" title="PowerJob" width="557"/>
</p>

<p align="center">
<a href="https://github.com/PowerJob/PowerJob/actions"><img src="https://github.com/PowerJob/PowerJob/workflows/Java%20CI%20with%20Maven/badge.svg?branch=master" alt="actions"></a>
<a href="https://search.maven.org/search?q=com.github.kfcfans"><img alt="Maven Central" src="https://img.shields.io/maven-central/v/com.github.kfcfans/powerjob-worker"></a>
<a href="https://github.com/PowerJob/PowerJob/releases"><img alt="GitHub release (latest SemVer)" src="https://img.shields.io/github/v/release/kfcfans/powerjob?color=%23E59866"></a>
<a href="https://github.com/PowerJob/PowerJob/blob/master/LICENSE"><img src="https://img.shields.io/github/license/KFCFans/PowerJob" alt="LICENSE"></a>
</p>

[PowerJob](https://github.com/PowerJob/PowerJob) is an open-source distributed computing and job scheduling framework which allows developers to easily schedule tasks in their own application.

Refer to [Quick Started Tutorial](https://www.yuque.com/powerjob/en/baz8y6) for detailed information.

# Introduction

### Features
- **Friendly UI:** [Front-end](http://try.powerjob.tech/#/welcome) page is provided and developers can manage their task, monitor the status, check the logs online, etc.

- **Abundant Timing Strategies:** Four timing strategies are supported, including CRON expression, fixed rate, fixed delay and OpenAPI.

- **Multiple Execution Mode:** Four execution modes are supported, including stand-alone, broadcast, Map and MapReduce. Distributed computing resource could be utilized in MapReduce mode, try the magic out [here](http://try.powerjob.tech/)!

- **DAG Job Flow Support:** Both job dependency management and data communications between jobs are supported.

- **Cross-language Client Support:** So far, developers can use Java, Spring, Shell, Python to write their own PowerJob client and define tasks that can be triggered by PowerJob workflow.

- **Disaster Tolerance Support:** As long as there are enough computing nodes, configurable retry policies make it possible for your task to be executed and finished successfully.  

### Applicable scenes

- Timed tasks, for example, allocating e-coupons on 9 AM every morning.
- Broadcast tasks, for example, broadcasting to the cluster to clear logs.
- MapReduce tasks, for example, speeding up certain job like updating large amounts of data.
- Delayed tasks, for example, processing overdue orders.
- Customized tasks, triggered with [OpenAPI](https://www.yuque.com/powerjob/en/fs3vg0).

### Online trial

- Trial address: [Online Trial Address](http://try.powerjob.tech/)  
- Application name: powerjob-agent-test  
- Application password: 123

# Documents
**[Docs](https://www.yuque.com/powerjob/en/introduce)**

**[中文文档](https://www.yuque.com/powerjob/guidence/ztn4i5)**

# Known Users
[Click to register as PowerJob user!](https://github.com/PowerJob/PowerJob/issues/6)  
ღ( ´・ᴗ・\` )ღ Many thanks to the following registered users. ღ( ´・ᴗ・\` )ღ
<p style="text-align: center">
<img src="https://raw.githubusercontent.com/KFCFans/PowerJob/master/others/images/user.png" alt="PowerJob User" title="PowerJob User"/>
</p>

# License

PowerJob is released under Apache License 2.0. Please refer to [License](./LICENSE) for details.

# Others

- Any developer interested in getting more involved in PowerJob may join our [Gitter Community](https://gitter.im/PowerJob/community) and make [contributions](https://github.com/PowerJob/PowerJob/pulls)!

- Reach out to me through email **tengjiqi@gmail.com**. Any issues or questions are welcomed on [Issues](https://github.com/PowerJob/PowerJob/issues).

- Look forward to your opinions. Response may be late but not denied.

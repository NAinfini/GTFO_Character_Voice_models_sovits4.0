<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT LOGO -->
<br />
<div align="center">

  <h3 align="center">GTFO_Character_Voice_models</h3>
  <h3 align="center">GTFO 角色语音模型</h3>

  [English Version](README.md)
  
</div>




<!-- TABLE OF CONTENTS -->
<details>
  <summary>目录</summary>
  <ol>
    <li>
      <a href="#项目概述">项目概述</a>
    </li>
    <li>
      <a href="#安装方法">安装方法</a>
    </li>
    <li>
      <a href="#使用方法">使用方法</a>
    </li>
    <li><a href="#版权">版权</a></li>
    <li><a href="#联系方式">联系方式</a></li>
  </ol>
</details>

<br/></br>
<!-- ABOUT THE PROJECT -->

## 项目概述

这个项目提供用于音频替换的AI模型， 模型基于so-vits-4.1训练， 每个模型均已训练至少 20K 段（steps），可直接运用于音频模拟。

这个项目包括:
* 训练AI所使用的音频数据
* 基本模型
* 扩散模型
* 聚类模型
* 音频样品



使用音频取自:
* [Hacket](https://youtu.be/eX5f9dVZP2A)
* [Woods](https://www.youtube.com/watch?v=UE5h4AowjoU)
* [Dauda](https://www.youtube.com/watch?v=kgdOFGUQMVA)
* [Bishop](https://www.youtube.com/watch?v=OJp-yALvqGU)

样品:

https://github.com/NAinfini/GTFO_Character_Voice_models_sovits4.0/assets/68311621/702f1842-637b-41ca-958c-702ab315e8e3

https://github.com/NAinfini/GTFO_Character_Voice_models_sovits4.0/assets/68311621/4b0a5e2d-3316-44bb-ae0b-fcf948341489

https://github.com/NAinfini/GTFO_Character_Voice_models_sovits4.0/assets/68311621/2356e863-149a-4bef-9ea9-786cdf13a157

https://github.com/NAinfini/GTFO_Character_Voice_models_sovits4.0/assets/68311621/33f597ab-d2e4-4cc6-9521-c0937b725735

https://github.com/NAinfini/GTFO_Character_Voice_models_sovits4.0/assets/68311621/31004584-c393-409f-ad4e-0a4ac2746a33


所有模型均使用  [so-vits-svc](https://github.com/svc-develop-team/so-vits-svc/tree/4.0) 进行训练



<!-- GETTING STARTED -->
## 安装方法

首先需要安装 [so-vits-svc](https://github.com/svc-develop-team/so-vits-svc/tree/4.0) 或 [so-vits-svc-fork](https://github.com/voicepaw/so-vits-svc-fork)， 如有需要，使用由[羽毛布団](https://space.bilibili.com/3493141443250876)提供的[懒人安装包](https://www.bilibili.com/video/BV1Cc411H74D/?share_source=copy_web&vd_source=8116d735052da197cb39c474a91467dc)
安装完成后将目录中的文件夹拖入即可，若出现问题， 根据下面的目录进行移动。


```
so-vits-svc-4.1
    │   
    └───logs
          └───44k
                ├───G_(name of character).pth -  默认模型
                ├───(name of character)Kmeans.pt - 聚集模型
                ├───config.json - 默认模型训练设置
                └───diffusion
                        └───(name of character).pt - 扩散模型

data_set - 使用的音频片段，已经过筛选和切片。
```

<!-- USAGE EXAMPLES -->
## 使用方法

选择任务对应的模型， 聚集模型，扩散模型， 以及设置， 进行训练， 训练软件可能不支持聚集或扩散模型。
注意：训练之前将设置文件中的 Speaker 更改为所使用任务名称："Hacket_data_set,Dauda_data_set,Bishop_data_set,Woods_data_set"以避免错误
若继续出现问题，使用预处理以及预设置处理一个文件夹， 将素有设置的声音名称统一
<!-- LICENSE -->
## 版权

使用 MIT License 以及 so-vits 所使用的版权。 查看 [版权](LICENSE.txt) 以及  [so-vits-svc](https://github.com/svc-develop-team/so-vits-svc/tree/4.0)。
如有使用，请标注此项目。



<!-- CONTACT -->
## 联系方式

NAinfini - na.infini@gmail.com

NA infini#6457 -Discord

项目链接: [GTFO_Character_Voice_models](https://github.com/NAinfini/GTFO_Character_Voice_models_sovits4.0)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


---
title: 实验室资源（Resources）
---

本页面展示 YS Laboratory 开放的研究资源，包括数据集、开源代码、软件工具与实验平台。

{% include section.html %}

## 推荐资源（Featured Resources）

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 24px; margin: 20px 0;">

  <!-- 资源卡片 1 -->
  <div style="border: 1px solid #ddd; border-radius: 10px; padding: 24px; background: #fafafa;">
    <div style="color: #e07b39; font-weight: bold; font-size: 1.1em;">YS Intelligent Dataset</div>
    <div style="color: #555; margin: 6px 0 4px;">智能系统实验数据集</div>
    <div style="color: #777; font-size: 0.9em; margin-bottom: 12px;">用于机器学习模型训练与测试。</div>
    <div style="font-size: 0.85em; color: #e07b39; margin-bottom: 12px;">
      <span>Dataset</span> | <span>2025</span>
    </div>
    <div style="font-size: 0.9em;">
      <a href="https://github.com/YS-Open-Lab" target="_blank" style="margin-right: 10px;">[GitHub]</a>
      <a href="#" target="_blank">[Download]</a>
    </div>
  </div>

  <!-- 资源卡片 2 -->
  <div style="border: 1px solid #ddd; border-radius: 10px; padding: 24px; background: #fafafa;">
    <div style="color: #e07b39; font-weight: bold; font-size: 1.1em;">YS Analysis Toolkit</div>
    <div style="color: #555; margin: 6px 0 4px;">智能分析工具包</div>
    <div style="color: #777; font-size: 0.9em; margin-bottom: 12px;">提供数据预处理、可视化与模型评估功能。</div>
    <div style="font-size: 0.85em; color: #e07b39; margin-bottom: 12px;">
      <span>Code</span> | <span>2025</span>
    </div>
    <div style="font-size: 0.9em;">
      <a href="https://github.com/YS-Open-Lab" target="_blank" style="margin-right: 10px;">[GitHub]</a>
      <a href="#" target="_blank">[Documentation]</a>
    </div>
  </div>

  <!-- 资源卡片 3 -->
  <div style="border: 1px solid #ddd; border-radius: 10px; padding: 24px; background: #fafafa;">
    <div style="color: #e07b39; font-weight: bold; font-size: 1.1em;">YS Lab Platform</div>
    <div style="color: #555; margin: 6px 0 4px;">实验室开放平台</div>
    <div style="color: #777; font-size: 0.9em; margin-bottom: 12px;">面向科研人员的在线实验与协作平台。</div>
    <div style="font-size: 0.85em; color: #e07b39; margin-bottom: 12px;">
      <span>Platform</span> | <span>2025</span>
    </div>
    <div style="font-size: 0.9em;">
      <a href="#" target="_blank" style="margin-right: 10px;">[Website]</a>
      <a href="#" target="_blank">[Documentation]</a>
    </div>
  </div>

</div>

{% include section.html %}

## 全部资源（All Resources）

### Dataset
{% include list.html data="projects" component="card" filters="type: dataset" %}

### Code
{% include list.html data="projects" component="card" filters="type: code" %}

### Software
{% include list.html data="projects" component="card" filters="type: software" %}

### Platform
{% include list.html data="projects" component="card" filters="type: platform" %}

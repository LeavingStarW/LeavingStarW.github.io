---
layout: archive
permalink: /
author_profile: true
---
<head>
  <style>
    /* 基础样式 */
    a { 
      color: #2891CB; 
      text-decoration: none;
      transition: all 0.3s;
    }
    a:hover { 
      color: #1a6a96;
      text-decoration: underline;
    }
    div { 
      font-size: 15px; 
      line-height: 1.8;
      margin-bottom: 5px;
    }
    
    /* Emoji样式 */
    .emoji { 
      vertical-align: middle; 
      margin-right: 8px;
      font-size: 1.1em;
    }
    
    /* 章节标题 */
    .section-title { 
      margin: 25px 0 15px;
      color: #2c3e50;
      font-weight: 600;
    }
    
    /* 出版物容器 */
    .pub-container { 
      display: flex; 
      margin-bottom: 35px;
      align-items: center;
      gap: 25px;
    }
    
    /* 图片固定尺寸 */
    .pub-image {
      width: 300px;
      height: 200px;
      flex-shrink: 0;
      border: 1px solid #eaeaea;
      box-shadow: 0 3px 10px rgba(0,0,0,0.08);
      display: flex;
      justify-content: center;
      align-items: center;
      overflow: hidden;
    }
    .pub-image img {
      width: 100%;
      height: 100%;
      object-fit: contain;
      padding: 10px;
    }
    
    /* 信息区域 */
    .pub-info { 
      flex-grow: 1;
    }
    
    /* 新版年份标签 */
    .pub-badge {
      display: inline-block;
      padding: 6px 12px;
      background: linear-gradient(135deg, #3498db, #2980b9);
      color: white;
      border-radius: 4px;
      margin-bottom: 12px;
      font-size: 14px;
      font-weight: 500;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      position: relative;
    }
    .pub-badge::after {
      content: "";
      position: absolute;
      bottom: -5px;
      left: 10px;
      width: 0;
      height: 0;
      border-left: 5px solid transparent;
      border-right: 5px solid transparent;
      border-top: 5px solid #2980b9;
    }
    
    /* 论文标题 */
    .pub-title {
      font-weight: 500;
      margin-bottom: 8px;
      line-height: 1.4;
    }
    
    /* 作者行 */
    .pub-authors {
      color: #555;
      font-size: 14px;
      line-height: 1.5;
    }
    .pub-authors b {
      color: #2c3e50;
    }
    
    /* 列表样式 */
    ul { 
      padding-left: 22px;
      margin-top: 5px;
    }
    li { 
      margin-bottom: 10px;
      position: relative;
    }
    li::before {
      content: "•";
      color: #3498db;
      font-weight: bold;
      display: inline-block;
      width: 1em;
      margin-left: -1em;
    }
    
    /* 时间强调 */
    .year {
      font-weight: 600;
      color: #2c3e50;
    }
  </style>
</head>

## <span class="section-title">About me</span>
<div>
  <span class="emoji">😊</span> Hello, I am a third-year <b>Computer Science and Technology</b> student at Hangzhou Dianzi University, supervised by <a href="https://faculty.hdu.edu.cn/jsjxy/grq/main.htm">Prof. Ruiquan Ge (葛瑞泉)</a> from Hangzhou Dianzi University and <a href="https://www.sribd.cn/teacher/505">Prof. Changmiao Wang (王昌淼)</a> from Shenzhen Research Institute of Big Data.<br>
  <span class="emoji">📭</span> My email: 22320308@hdu.edu.cn
</div>

## <span class="section-title">News</span>
<div>
  <ul>
    <li><span class="year">2024.12:</span> We won the <b>National Bronze Medal</b> in the <a href="https://pilcchina.org/home">China International College Students' Innovation Competition 2024.</a></li>
    <li><span class="year">2024.12:</span> Our paper for <a href="https://link.springer.com/journal/521">Neural Computing and Applications</a> was <b>Accepted!</b></li>
    <li><span class="year">2024.08:</span> Our paper for <a href="https://ieeebibm.org/BIBM2024/">BIBM 2024</a> was accepted as a <b>Regular Paper!</b></li>
    <!-- 其他news条目保持相同结构 -->
  </ul>
</div>

## <span class="section-title">Publications</span>

<div class="pub-container">
  <div class="pub-image">
    <img src="https://raw.githubusercontent.com/LeavingStarW/LeavingStarW.github.io/refs/heads/master/images/GCINet.webp">
  </div>
  <div class="pub-info">
    <div class="pub-badge">2025 Neural Computing and Applications</div>
    <div class="pub-title">
      <a href="https://link.springer.com/article/10.1007/s00521-024-10692-3">GCINet: global convolution interaction network with a pre-trained reversible normalization method for long-term time series forecasting</a>
    </div>
    <div class="pub-authors">
      Jin Fan, Baoshun Yang, Danfeng Sun, Jie Liu, Qikai Chen, <b>Zhipeng Wang</b>, Jia Wu
    </div>
  </div>
</div>

<div class="pub-container">
  <div class="pub-image">
    <img src="https://raw.githubusercontent.com/LeavingStarW/LeavingStarW.github.io/refs/heads/master/images/CCLNet.png">
  </div>
  <div class="pub-info">
    <div class="pub-badge">2024 BIBM (Regular)</div>
    <div class="pub-title">
      <a href="https://ieeexplore.ieee.org/document/10821899">CCLNet: Causal and Contrastive Learning Framework for Enhanced Pulmonary Embolism Detection</a>
    </div>
    <div class="pub-authors">
      <b>Zhipeng Wang</b>, Ruiquan Ge<sup>*</sup>, Jianxun Yu, Feiwei Qin, Yuan Tian, Nannan Li, Wenwen Min, Ahmed Elazab, Changmiao Wang<sup>*</sup>
    </div>
  </div>
</div>

<!-- 其他出版物保持相同结构 -->

## <span class="section-title">Internships</span>
<div>
  <ul>
    <li><span class="year">2023.10 - Present:</span> Healthcare Big Data Lab, <a href="https://www.sribd.cn/">Shenzhen Research Institute of Big Data</a>, Shenzhen, China</li>
    <li><span class="year">2023.10 - Present:</span> Advanced Networking and Big Data Lab, Hangzhou Dianzi University, Hangzhou, China</li>
  </ul>
</div>

## <span class="section-title">Honors</span>
<div>
  <ul>
    <li><span class="year">2025:</span> <a href="https://mp.weixin.qq.com/s/lcgUXEJ5ITtSLiq1ltnagw">Top 10 Students of HDU-ITMO Joint Institute</a></li>
    <li><span class="year">2024:</span> <a href="https://student.hdu.edu.cn/2025/0402/c795a277007/page.htm">Zhejiang Provincial Government Scholarship</a></li>
    <!-- 其他荣誉保持相同结构 -->
  </ul>
</div>

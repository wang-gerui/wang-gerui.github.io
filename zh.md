---
layout: homepage_zh
---

## 个人介绍

我是北京微芯区块链与边缘计算研究院的区块链研究员，在国家区块链技术创新中心担任相同职位，目前正在积极寻求与区块链技术相关领域研究者的合作。

我于伊利诺伊大学厄巴纳-香槟分校获得计算机科学博士学位，师从Pramod Viswanath教授。

我本科毕业于清华大学交叉信息研究院（姚班）。

## 研究兴趣

- **区块链：** 区块链安全与可扩展性
- **分布式协议：** 共识算法、分布式计算、分布式存储
- **零知识证明：** zkSNARKs、zkRollups、zkVMs

## 教育背景

<h4 style="margin:0 10px 0;">计算机科学博士</h4>

  <p style="margin:0 20px 0;">伊利诺伊大学厄巴纳-香槟分校计算机科学系。导师：Pramod Viswanath教授。<i>2017年8月 - 2022年5月</i>
  <br><a href="assets/files/dissertation.pdf">学位论文下载</a>
  </p>

  

<h4 style="margin:0 10px 0;">计算机科学与技术学士</h4>

<p style="margin:0 20px 20px;">清华大学交叉信息研究院（姚班）。<i>2013年8月 - 2017年7月</i></p>


<h2 id="publications" style="margin: 2px 0px -15px;">代表性论文</h2>

<div class="publications">
<ol class="bibliography">

{% for link in site.data.publications.main %}

<li>
<div class="pub-row">
  <div class="col-sm-3 abbr" style="position: relative;padding-right: 15px;padding-left: 15px;">
    {% if link.image %} 
    <img src="{{ link.image }}" class="teaser img-fluid z-depth-1" style="width=100;height=40%">
    {% endif %}
    {% if link.conference_short %} 
    <abbr class="badge">{{ link.conference_short }}</abbr>
    {% endif %}
  </div>
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><a href="{{ link.pdf }}">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em>{{ link.conference }}</em>
      </div>
    <div class="links">
      {% if link.pdf %} 
      <a href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">BibTex</a>
      {% endif %}
      {% if link.notes %} 
      <strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>

<br>

{% endfor %}

</ol>
</div>


## 代表性经历

<h4 style="margin:0 10px 0;">所获荣誉</h4>
<ul style="margin:0 0 20px;">
  <li>北京市劳动模范</li>
</ul>
<h4 style="margin:0 10px 0;">工作经历</h4>

<ul style="margin:0 0 5px;">
  <li><i>2022年5月至今</i>，<b>区块链研究员</b>，北京区块链与边缘计算研究院，中国北京</li>
  <li><i>2021年5月 - 2022年5月</i>，<b>算法工程师/研究员</b>，Hash Laboratories Pty. Ltd.，澳大利亚新南威尔士州北悉尼</li>
  <li><i>2019年夏季</i>，<b>研究实习生</b>，Applied Protocol Research，美国加利福尼亚州帕罗奥图。导师：David Tse教授</li>
</ul>

<h4 style="margin:0 10px 0;">学术访问</h4>

<ul style="margin:0 0 20px;">
  <li><i>2016年春季</i>，<b>访问学生</b>，康奈尔大学计算机科学系</li>
</ul>

<h4 style="margin:0 10px 0;">教学工作</h4>

<ul style="margin:0 0 20px;">
  <li><i>2021年春季与2022年春季</i>，<b>区块链原理课程</b>，伊利诺伊大学厄巴纳-香槟分校</li>
</ul>


---
title: News
---
<style>
.info.obfuscate {
unicode-bidi: bidi-override;
direction: rtl;
text-align:left;
}

div {
  margin: 0 0 0 0;
}

#right {
  float:right;
  margin-left: 50px;
}

#contact {
  width:70%;
}

body {
  font-family: "Source Sans Pro", "Lucida Grande", Calibri, Helvetica, sans-serif;
  font-size: normal;
  margin-top:0%;
  margin-bottom:0%;
  margin-right:0%;
  margin-left:0%;
  line-height: 1;

}

h1 {
  font-size: 2.0em;
  margin-bottom: 10px;
}

li {
  margin: 0 0 5px 0;
  line-height: 1.5;
}

li li {
  list-style-type: none;
  margin-right: 20%;
}

img {
  vertical-align: top;
}
</style>

<style>
/* 隐藏真实复选框（用 label 触发） */
.fold-toggle { position: absolute; left: -9999px; }

/* 按钮：醒目的描边 + 轻阴影，内联显示，跟在文字后 */
.fold-btn {
  display: inline-flex; align-items: center; gap: .35em;
  padding: .18rem .6rem;
  border: 1px solid var(--gray-300, rgba(0,0,0,.22));
  border-radius: .5rem;
  background: var(--card-bg, #fff);
  font-weight: 600; line-height: 1; cursor: pointer; user-select: none;
  margin-left: .5em; vertical-align: baseline;
  box-shadow: 0 1px 0 rgba(0,0,0,.04);
  transition: background .15s, border-color .15s, box-shadow .15s;
}
.fold-btn:hover {
  background: var(--hover, #f5f7fb);
  border-color: rgba(0,0,0,.32);
  box-shadow: 0 2px 8px rgba(0,0,0,.08);
}

/* 按钮右侧的小三角：展开/收起 */
.fold-btn::after { content: "▾"; font-size: .9em; }
.fold-toggle:checked + .fold-btn::after { content: "▴"; }

/* 折叠内容：默认隐藏，选中后显示；与按钮在同一个 <li> 下 */
.fold-content { display: none; margin-top: .6rem; }
li > .fold-toggle:checked ~ .fold-content { display: block; }

/* 可选：让图片更协调 */
.fold-content img { max-width: 50%; height: auto; border-radius: 10px; }
</style>

<style>
/* 仅对“折叠组件”的 checkbox 取消任务列表样式影响 */
li:has(> input.fold-toggle) {
  list-style: initial !important;         /* 恢复圆点 */
  padding-left: 0 !important;             /* 取消额外缩进 */
  text-decoration: none !important;       /* 取消删除线 */
  color: inherit !important;              /* 取消变灰 */
}

/* 勾选后也保持正常文本样式 */
li:has(> input.fold-toggle:checked) {
  text-decoration: none !important;
  color: inherit !important;
}

/* 可选：如果主题还对 ul/ol 套了 contains-task-list 的类，再兜底一层 */
ul:has(> li > input.fold-toggle),
ol:has(> li > input.fold-toggle) {
  list-style: initial !important;
  padding-left: revert !important;
}
</style>





<ul class="news-list">
  <li><a href="https://laggedcorshiny.jaspershenlab.com/">lagcishiny</a> is online</li>

  <li>Become maintainer of R packages: <a href="https://github.com/tidymass/masstools">masstools</a></li>

  <li>
    Summer internship experience at Shen-Lab (NTU) (07.10.2025 - 08.25.2025)
    <input id="fold-ntu" type="checkbox" class="fold-toggle"><label for="fold-ntu" class="fold-btn">View</label>
    <div class="fold-content">
      <img src="/static/images/Certif_NTU.jpg" alt="Certif_NTU" loading="lazy" style="max-width:70%;border-radius:10px;">
    </div>
  </li>

  <li>
    Remote internship experience at Shen-Lab (NTU) (03.20.2025 - 07.09.2025)
  </li>

  <li>
    2024 Gold Award in the Synthetic Biology Innovation Competition.
    <input id="fold-gold" type="checkbox" class="fold-toggle"><label for="fold-gold" class="fold-btn">View</label>
    <div class="fold-content">
      <img src="/static/images/syn-gold.jpg" alt="syn-gold.jpg" loading="lazy" style="max-width:70%;border-radius:10px;">
    </div>
  </li>

  <li>
    Organic lecture titled "Understanding organic reaction from Markov addition reaction mechanism" for undergraduate student.
    <input id="fold-lecture" type="checkbox" class="fold-toggle"><label for="fold-lecture" class="fold-btn">View</label>
    <div class="fold-content">
      <img src="/static/images/ma-lecture.jpg" alt="ma-lecture.jpg" loading="lazy" style="max-width:70%;border-radius:10px;">
    </div>
  </li>

  <li>
    Third Prize in the 15th "Huazhong Cup" College Students' Mathematical Modeling competition.
    <input id="fold-hzcup15" type="checkbox" class="fold-toggle"><label for="fold-hzcup15" class="fold-btn">View</label>
    <div class="fold-content">
      <img src="/static/images/hzcup15.jpg" alt="hzcup15.jpg" loading="lazy" style="max-width:70%;border-radius:10px;">
    </div>
  </li>

  <li>
    Award for Excellence in the 14th "Huazhong Cup" College Students' Mathematical Modeling competition.
    <input id="fold-hzcup14" type="checkbox" class="fold-toggle"><label for="fold-hzcup14" class="fold-btn">View</label>
    <div class="fold-content">
      <img src="/static/images/hzcup14.jfif" alt="hzcup14.jfif" loading="lazy" style="max-width:70%;border-radius:10px;">
    </div>
  </li>

  <li>
    Served as a peer tutor for the chemistry course at Huazhong Agricultural University (2022.2-2022.7).
    <input id="fold-tutor" type="checkbox" class="fold-toggle"><label for="fold-tutor" class="fold-btn">View</label>
    <div class="fold-content">
      <img src="/static/images/tutor.jpg" alt="tutor.jpg" loading="lazy" style="max-width:70%;border-radius:10px;">
    </div>
  </li>
</ul>


















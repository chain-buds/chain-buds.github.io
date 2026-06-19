---
title: Publications
---

<style>
/* ====== 基础排版：延续你现有的 News 风格 ====== */
.info.obfuscate {
  unicode-bidi: bidi-override;
  direction: rtl;
  text-align:left;
}
div { margin: 0; }
#right { float:right; margin-left: 50px; }
#contact { width:70%; }
body {
  font-family: "Source Sans Pro","Lucida Grande",Calibri,Helvetica,sans-serif;
  font-size: normal;
  margin: 0;
  line-height: 1;
}
h1 { font-size: 2.0em; margin-bottom: 10px; }
li { margin: 0 0 5px 0; line-height: 1.5; }
li li { list-style-type: none; margin-right: 20%; }
img { vertical-align: top; }

/* ====== 按钮样式：与 News 页 fold-btn 保持一致视觉 ====== */
.btn {
  display: inline-flex; align-items: center; gap: .35em;
  padding: .18rem .6rem;
  border: 1px solid var(--gray-300, rgba(0,0,0,.22));
  border-radius: .5rem;
  background: var(--card-bg, #fff);
  font-weight: 600; line-height: 1;
  cursor: pointer; user-select: none;
  box-shadow: 0 1px 0 rgba(0,0,0,.04);
  transition: background .15s, border-color .15s, box-shadow .15s, transform .02s;
  text-decoration: none;     /* <a> 去下划线 */
  color: inherit;            /* 继承文本色 */
}
.btn:hover {
  background: var(--hover, #f5f7fb);
  border-color: rgba(0,0,0,.32);
  box-shadow: 0 2px 8px rgba(0,0,0,.08);
}
.btn:active { transform: translateY(1px); }

/* 按钮尺寸&间距：跟在条目文本后 */
.pub-actions { display:inline-flex; gap:.5rem; margin-left:.6rem; }

/* 列表容器：与 News 一致的外观 */
.pub-list { padding-left: 1.25rem; margin: .5rem 0 0; }
.pub-list li { margin-bottom: .9rem; }

/* 可选：小图标（如需） */
.btn .icon { width: 1em; height: 1em; display: inline-block; }
</style>



<ul class="pub-list">
  <li>
    Du, D., Peng, H., He, L., <b>Bai, S.</b>, Li, Z., &amp; Teng, H. (2022).
    Synthesis of remote fluoroalkenyl ketones by photo-induced ring-opening addition
    of cyclic alkoxy radicals to fluorinated alkenes. <i>Organic &amp; Biomolecular Chemistry</i>, 20(47), 9313-9318.
    <span class="pub-actions">
      <a class="btn" href="/static/pdfs/ddh2022.pdf" target="_blank" rel="noopener">Download</a>
      <a class="btn" href="https://pubs.rsc.org/en/content/articlelanding/2022/ob/d2ob01533a/unauth" target="_blank" rel="noopener">Read online</a>
    </span>
  </li>

  <li>
    Zheng, J#., Li, S#., <b>Bai, S.</b>#., Liu, X., Sun, R., Xu, S., &amp; Qu, W. (2025).
    An organic small molecule fluorescent probe for nondestructive detection of Zn<sup>2+</sup> in plants.
    <i>Tetrahedron Letters</i>, 155553.
    <span class="pub-actions">
      <a class="btn" href="/static/pdfs/zjy2025.pdf" target="_blank" rel="noopener">Download</a>
      <a class="btn" href="https://www.sciencedirect.com/science/article/pii/S0040403925001029" target="_blank" rel="noopener">Read online</a>
    </span>
  </li>

  <li>
    Shen, X., Qiang, Z., <b>Bai, S.</b>, &amp; Wu, Y. (2026).
    LagCI Enables Inference of Temporal Causal Relationships from Dense Multi-Omic Time Series.
    <i>bioRxiv</i>.
    <span class="pub-actions">
      <a class="btn" href="/static/pdfs/lagci-biorxiv.pdf" target="_blank" rel="noopener">Download</a>
      <a class="btn" href="https://www.biorxiv.org/content/10.64898/2026.04.15.718654v1" target="_blank" rel="noopener">Read online</a>
      <a class="btn" href="https://github.com/jaspershen-lab/lagci" target="_blank" rel="noopener">Code</a>
    </span>
  </li>
</ul>

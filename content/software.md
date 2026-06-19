---
title: Software
---

<style>
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
  text-decoration: none;
  color: inherit;
}
.btn:hover {
  background: var(--hover, #f5f7fb);
  border-color: rgba(0,0,0,.32);
  box-shadow: 0 2px 8px rgba(0,0,0,.08);
}
.btn:active { transform: translateY(1px); }

.sw-actions { display:inline-flex; gap:.5rem; margin-left:.6rem; }
.sw-list { padding-left: 1.25rem; margin: .5rem 0 0; }
.sw-list li { margin-bottom: .9rem; line-height: 1.5; }
</style>

Open-source tools and applications I build and maintain. See more on my [GitHub](https://github.com/chain-buds).

<ul class="sw-list">
  <li>
    <b>lagci</b> — One of the developers of this method and R package for lagged correlation inference.
    <span class="sw-actions">
      <a class="btn" href="https://www.biorxiv.org/content/10.64898/2026.04.15.718654v1" target="_blank" rel="noopener">Preprint</a>
      <a class="btn" href="https://www.shen-lab.org/lagci-tutorial/" target="_blank" rel="noopener">Tutorial</a>
      <a class="btn" href="https://github.com/jaspershen-lab/lagci" target="_blank" rel="noopener">GitHub</a>
    </span>
  </li>

  <li>
    <b>lagcishiny</b> — One of the developers of this web application for lagged correlation analysis.
    <span class="sw-actions">
      <a class="btn" href="https://lagcishiny.jaspershenlab.com/" target="_blank" rel="noopener">Launch app</a>
    </span>
  </li>
</ul>

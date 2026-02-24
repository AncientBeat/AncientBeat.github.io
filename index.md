---
layout: home
title: "我的技術筆記"
---

# 歡迎來到我的部落格 👋

這是利用 **GitHub Pages** 與 **Jekyll** 建立的個人網站。

---

## 最新文章
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> 
      <small>({{ post.date | date: "%Y-%m-%d" }})</small>
    </li>
  {% endfor %}
</ul>

---

### 關於我
我正在學習如何使用 Markdown 寫部落格！

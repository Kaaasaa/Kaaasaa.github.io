\---

title: "Home"

\---



\## 我在试图理解这个世界



不是记录，而是构建一套长期有效的认知结构。



\---



\## 📍 进入内容



\### 🧠 思考（Thoughts）

记录对社会、信息与个体的判断



👉 \[进入 Thoughts](/thoughts/)



\---



\### 🧩 系统（Systems）

方法论与分析框架



👉 \[进入 Systems](/systems/)



\---



\### 📚 评析（Reviews）

对书籍、产品与现象的结构化评价



👉 \[进入 Reviews](/reviews/)



\---



\## 🧭 最新文章



{{ range first 5 (where site.RegularPages "Type" "posts") }}

\- \[{{ .Title }}]({{ .RelPermalink }})

{{ end }}


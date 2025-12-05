---
---

# pyenparty's Website

歡迎來到屁眼派對!一個都是男同的天地
{% include section.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/cup.jpg"
  link="research"
  title="應用深度學習於成年男性玩具的實務應用 --- 以電動飛機杯為例"
  text=text
%}

{% capture text %}

本研究由 「臨陣退縮」怯戰甲甲魚博士 主導，探討深度學習技術在成年男性電動飛機杯中的實務應用。透過感測回饋、行為建模與個人化控制策略，本研究展示了智慧化裝置如何大幅提升互動體驗與產品效能。研究成果凸顯 AI 與成人用品跨領域結合的創新潛力。

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}

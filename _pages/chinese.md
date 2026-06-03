---
layout: archive
title: "唐义鸿"
permalink: /chinese/
author_profile: true
redirect_from:
  - /chinese
---

{% include base_path %}

<!-- 🌱 唐义鸿的主页 -->

## 🌟 关于我 

<div style="background: #f8f9fa; padding: 20px; border-radius: 10px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); line-height: 1.6;">
    <p style="margin-bottom: 15px;">
        自2025年3月起，我在 <span style="color: #2196F3; font-weight: 500;">哈尔滨工业大学（深圳）</span> 计算机技术专业攻读博士学位，师从 <strong>Prof. Kehai Chen</strong>。自2025年9月起，我也在 <span style="color: #2196F3; font-weight: 500;">深圳河套学院（SLAI）</span> 进行研究学习。在此之前，我于 <span style="color: #2196F3; font-weight: 500;">天津大学</span> 获得了硕士学位，师从 <strong>Prof. Bo Wang</strong>。
    </p>
    <p style="margin-bottom: 15px;">
        我的主要研究兴趣集中在 <span style="color: #4CAF50; font-weight: 500;">自然语言处理（NLP）、大语言模型（LLMs）、智能体（Agents） 以及 角色扮演（Role-Playing）</span>。 我致力于探索 LLM 在模拟人类行为与交互方面的潜力。具体而言，我关注如何构建具有更强推理能力和个性化的角色扮演智能体，并深入研究这些智能体在复杂交互场景下的鲁棒性。我的目标是推动智能体从单一工具向更拟人的交互伙伴进化。
    </p>
    <p>
        我非常乐意参与学术讨论和合作，请随时与我联系！
    </p>
</div>
-------------

## 🧭 研究图谱

{% include research-map.html lang="zh" %}

-------------

## 🎓 教育经历
- 2025年3月 - 至今：计算技术博士，哈尔滨工业大学（深圳），中国深圳。导师：[Dr. kehai Chen](https://faculty.hitsz.edu.cn/chenkehai) 。
- 2025年9月 - 至今：计算技术研究学习，深圳河套学院，中国深圳（不授予学位）。导师：Prof. Min Zhang。
- 2022年6月 - 2025年1月：计算技术硕士，天津大学，中国天津。导师：[Dr. Bo Wang](https://cic.tju.edu.cn/faculty/wangbo/index.htm) 。
- 2018年9月 - 2022年6月：计算机科学与技术工学学士，东北大学秦皇岛分校，中国秦皇岛。

## 📚 Publication（*表示共同一作）

{% include publications.md %}

## 🔬 科研贡献
- [Chinese-medical-dialogue-data](https://github.com/Toyhom/Chinese-medical-dialogue-data)：高质量的中文医疗问答数据集。
- 基于角色扮演的情绪增强对话智能体，2025年1月 - 2025年12月，CCF-百度松果基金，参与（学生第一负责人）。
- 审稿人：ACL ARR, NeurIPS, ICML, Neural Networks

<style>
  .friend-egg {
    margin-top: 1.5rem;
  }

  .friend-egg__grid {
    display: grid;
    gap: 20px;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    margin-top: 20px;
  }

  .friend-egg__card {
    background: #fff;
    border: 1px solid #e7ebef;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.08);
    padding: 15px;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }

  .friend-egg__card:hover {
    box-shadow: 0 5px 14px rgba(0, 0, 0, 0.12);
    transform: translateY(-2px);
  }

  .friend-egg__link {
    color: inherit;
    text-decoration: none;
  }

  .friend-egg__inner {
    text-align: center;
  }

  .friend-egg__avatar {
    border-radius: 50%;
    height: 80px;
    margin-bottom: 10px;
    object-fit: cover;
    width: 80px;
  }

  .friend-egg__name {
    color: #2c3e50;
    margin: 5px 0;
  }

  .friend-egg__nick {
    color: #7f8c8d;
    font-size: 0.9em;
    margin: 0;
  }
</style>

<div id="friend-easter-egg" class="friend-egg" hidden></div>

<script>
  (function () {
    var code = ["ArrowUp", "ArrowUp", "ArrowDown", "ArrowDown", "ArrowLeft", "ArrowRight", "ArrowLeft", "ArrowRight", "b", "a"];
    var cursor = 0;
    var payload = "W3sibmFtZSI6IkFsdHJpYSIsIm5pY2siOiLmtpvmtpsiLCJ1cmwiOiJodHRwczovL2FsdHJpYTExMjIuZ2l0aHViLmlvLyIsImltZyI6Imh0dHBzOi8vYWx0cmlhMTEyMi5naXRodWIuaW8vaW1nL0FsdHJpYS5wbmcifSx7Im5hbWUiOiJXZW9zaGluIiwibmljayI6IuaZn+aZnyIsInVybCI6Imh0dHBzOi8vd2Vvc2hpbi5naXRodWIuaW8vIiwiaW1nIjoiaHR0cHM6Ly93ZW9zaGluLmdpdGh1Yi5pby9pbWcvYXZhdGFyLmpwZyJ9LHsibmFtZSI6Ik1hc3RlcmVuTHUiLCJuaWNrIjoi6Zyy6ZyyIiwidXJsIjoiaHR0cHM6Ly9ibG9nLm1hc3RlcmVuLnRvcC8iLCJpbWciOiJodHRwczovL2FsdHJpYTExMjIuZ2l0aHViLmlvLy9pbWcvbHVsdUF2YXRhci5naWYifV0=";

    function decodeFriends() {
      var bytes = Uint8Array.from(atob(payload), function (char) {
        return char.charCodeAt(0);
      });
      return JSON.parse(new TextDecoder("utf-8").decode(bytes));
    }

    function revealFriends() {
      var root = document.getElementById("friend-easter-egg");
      if (!root || root.dataset.unlocked === "true") return;

      root.dataset.unlocked = "true";
      root.hidden = false;

      var divider = document.createElement("hr");
      var title = document.createElement("h2");
      var grid = document.createElement("div");
      title.textContent = "🤝 友链";
      grid.className = "friend-egg__grid";

      decodeFriends().forEach(function (friend) {
        var card = document.createElement("div");
        var link = document.createElement("a");
        var inner = document.createElement("div");
        var avatar = document.createElement("img");
        var name = document.createElement("h3");
        var nick = document.createElement("p");

        card.className = "friend-egg__card";
        link.className = "friend-egg__link";
        inner.className = "friend-egg__inner";
        avatar.className = "friend-egg__avatar";
        name.className = "friend-egg__name";
        nick.className = "friend-egg__nick";

        link.href = friend.url;
        link.target = "_blank";
        link.rel = "noopener";
        avatar.src = friend.img;
        avatar.alt = friend.name;
        name.textContent = friend.name;
        nick.textContent = friend.nick;

        inner.appendChild(avatar);
        inner.appendChild(name);
        inner.appendChild(nick);
        link.appendChild(inner);
        card.appendChild(link);
        grid.appendChild(card);
      });

      root.appendChild(divider);
      root.appendChild(title);
      root.appendChild(grid);
      root.scrollIntoView({ behavior: "smooth", block: "start" });
    }

    window.addEventListener("keydown", function (event) {
      var key = event.key.length === 1 ? event.key.toLowerCase() : event.key;
      cursor = key === code[cursor] ? cursor + 1 : (key === code[0] ? 1 : 0);
      if (cursor === code.length) {
        cursor = 0;
        revealFriends();
      }
    });
  })();
</script>



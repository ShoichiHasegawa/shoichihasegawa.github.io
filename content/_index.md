---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        Hi! I'm Shoichi Hasegawa.

        I'm interested in multimodal language understanding for domestic service robots.
        Currently, I'm conducting research on robots that support human life in the home, based on the framework of symbol emergence in robotics, by leveraging spatial semantic understanding technologies and large language models.
        I'm a doctoral student at Ritsumeikan University and am involved in the <a href="https://avatar-ss.org/en/index.html">ISHIGURO Project (Moonshot Goal 1)</a>，<a href="https://en.ritsumei.ac.jp/research/r-giro/project/fourth/sato/">R-GIRO (Symbol Emergence Systems Science)</a>，<a href="https://xtech.nikkei.com/atcl/nxt/mag/rob/18/00003/00123/">HSRT-X (Matsuo Lab)</a>.
        My goal is to realize a domestic service robot that interacts with humans like a member of the family—much like "Doraemon."

        Keywords:

        Domestic service robot, multimodal language understanding, large language models, robotics foundation models, symbol emergence robotics

        長谷川翔一と申します．

        私は家庭用サービスロボットにおけるマルチモーダル言語理解に関心を持っています．
        現在は記号創発ロボティクスの枠組みに基づき、空間の意味理解技術と大規模言語モデルの知識を活用しながら、家庭内で人間の生活を支援するロボットの研究に取り組んでいます．
        立命館大学の博士課程に在籍し、<a href="https://avatar-ss.org/">石黒浩ムーンショット</a>，<a href="https://www.ritsumei.ac.jp/rgiro/project/fourth/sato/">R-GIRO (記号創発システム科学創成)</a>，<a href="https://xtech.nikkei.com/atcl/nxt/mag/rob/18/00003/00123/">HSRT-X (東京大学松尾研主導)</a>に参画しています．
        最終的には、「家族の一員のように人と関わる家庭用サービスロボット（ドラえもん）」の実現を目指しています．

        キーワード:

        家庭用サービスロボット，マルチモーダル言語理解，大規模言語モデル，ロボティクス基盤モデル，記号創発ロボティクス

    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: '⭐ Featured Publications'
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  # - block: markdown
  #   id: publications
  #   content:
  #     title: '💪 Recent Publications'
  #     text: |
  #       1. <div style="font-size: 0.8em">遠藤純音, <u><strong>長谷川翔一</strong></u>, 中田友貴, 杉山滉平, 谷口彰, 上川多恵子, 安田裕子, 谷口忠大 "大規模言語モデルを活用した複線径路等至性モデリングのための図生成システムの開発," <strong>第4回TEAと質的探究学会</strong>, 2025, accepted. </div>
  #       1. <div style="font-size: 0.8em">L. El Hafi, K. Onishi, <u><strong>S. Hasegawa</strong></u>, A. Oyama, T. Ishikawa, M. Osada, C. Tornberg, R. Kado, K. Murata, S. Hashimoto, S. Carrera Villalobos, A. Taniguchi, GA. Garcia Ricardez, Y. Hagiwara, T. Aoki, K. Iwata, T. Horii, Y. Horikawa, T. Miyashita, T. Taniguchi, H. Ishiguro, "Public Evaluation on Potential Social Impacts of Fully Autonomous Cybernetic Avatars for Physical Support in Daily-Life Environments: Large-Scale Demonstration and Survey at Avatar Land," <strong>IEEE International Conference on Advanced Robotics and its Social Impacts (ARSO)</strong>, 2025, accepted. </div>
      # filters:
      #   folders:
      #     - publication
      #   exclude_featured: false
    # design:
    #   view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1
  - block: collection
    id: news
    content:
      title:  '🚀 Recent News'
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
    
  - block: markdown
    id: publications
    content:
      title: '📜 Representative Papers'
      subtitle: ''
      text: |
        Full Publications (Google Scholor and Researchmap) is here.

        ### Integration of Probabilistic Logic and Probabilistic Generative Models for Understanding Object Placements
        1. <div style="font-size: 0.8em"><u><strong>S. Hasegawa</strong></u>, A. Taniguchi, Y. Hagiwara, L. El Hafi, T. Taniguchi, "Integrating Probabilistic Logic and Multimodal Spatial Concepts for Efficient Robotic Object Search in Home Environments," <strong>SICE Journal of Control, Measurement, and System Integration (SICE JCMSI)</strong>, Vol. 16, No. 1, pp. 400-422, 2023, <a href="https://www.tandfonline.com/doi/full/10.1080/18824889.2023.2283954">paper</a>. DOI: 10.1080/18824889.2023.2283954 </div>


        ### Large Language Models-based Robot Action Planning
        1. <div style="font-size: 0.8em">萩原 良信, 長谷川 翔一, 大山 瑛, 谷口 彰, エル ハフィ ロトフィ, 谷口 忠大, "現場環境で学習した知識に基づく曖昧な発話からの生活物理支援タスク," 第41回日本ロボット学会学術講演会 (RSJ), 大阪, 2023年9月. (🏆<strong>HSRコミュニティ優秀論文賞</strong>, 🏆<strong>第5回 優秀研究・技術賞</strong>)</div>


        ### Large Language Models-based Multi-Robot Collaboration
        1. <div style="font-size: 0.8em"><u><strong>S. Hasegawa</strong></u>, K. Murata, T. Ishikawa, Y. Hagiwara, A. Taniguchi, L. El Hafi, G. Garcia, T. Taniguchi, "大規模言語モデルによる複数ロボットの知識統合とタスク割当を用いた現場学習のコスト削減," <strong>Journal of RSJ Letter</strong>, 2024, accepted. </div>


        ### Robotics Foundation Models
        1. <div style="font-size: 0.8em">松嶋 達也, 高波 亮介, 神原 元就, 野口 裕貴, 有馬 純平, 池田 悠也, 柳田 栞吾, 岩田 健輔, 長谷川 翔一, エル ハフィ ロトフィ, 山尾 晃世, 磯本 航世, 山口 直紀, 小林 遼平, 柴 智也, 矢野 優雅, 水谷 彰伸, 田向 権, 堀井 隆斗, 杉浦 孔明, 谷口 忠大, 松尾 豊, 岩澤 有祐, "HSRT-X: コミュニティを活用したロボット基盤モデルの構築," 第42回日本ロボット学会学術講演会 (RSJ), 大阪, 2024年9月.</div>


        ### Exophora Resolution
        1. <div style="font-size: 0.8em">A. Oyama, S. Hasegawa, H. Nakagawa, A. Taniguchi, Y. Hagiwara, T. Taniguchi, "Exophora Resolution of Linguistic Instructions with a Demonstrative based on Real-World Multimodal Information," <strong>IEEE International Conference on Robot & Human Interactive Communication (RO-MAN)</strong>, pp. 2617-2623, Korea, Aug. 2023, <a href="https://ieeexplore.ieee.org/document/10309487">paper</a>. DOI: 10.1109/RO-MAN57019.2023.10309487 (🏆<strong>ロボカップ研究賞</strong>) </div>
        1. <div style="font-size: 0.8em">H. Nakagawa, S. Hasegawa, Y. Hagiwara, A. Taniguchi, T. Taniguchi, "Pointing Frame Estimation with Audio-Visual Time Series Data for Daily Life Service Robots," <strong>IEEE International Conference on Systems, Man, and Cybernetics (SMC)</strong>, Malaysia, Oct. 2024, in press, <a href="https://emergentsystemlabstudent.github.io/PointingImgEst/">project page</a>, <a href="https://speakerdeck.com/shoichi_hasegawa/pointing-frame-estimation-with-audio-visual-time-series-data-for-daily-life-service-robots">slide</a>. (🏆<strong>Best Paper Award</strong>)</div>


        ### Instance Specific Image-Goal Navigation with Self-Supervised Learning
        1. <div style="font-size: 0.8em">T. Sakaguchi, A. Taniguchi*, Y. Hagiwara, L. El Hafi, S. Hasegawa, T. Taniguchi, "Object Instance Retrieval in Assistive Robotics: Leveraging Fine-Tuned SimSiam with Multi-View Images Based on 3D Semantic Map," <strong>IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)</strong>, Abu Dabi, Oct. 2024, in press, <a href="https://arxiv.org/abs/2404.09647">arxiv</a>, <a href="https://emergentsystemlabstudent.github.io/MultiViewRetrieve/">project page</a>, <a href="https://github.com/EmergentSystemLabStudent/MultiViewRetrieve">code</a>. </div>
        
        
        ### Foundation Models for Human-Robot Interaction
        1. <div style="font-size: 0.8em">E. Martin, <u><strong>S. Hasegawa</strong></u>, J. Solis, B. Macq, R. Ronsse, G A. Garcia Ricardez, L. El Hafi, T. Taniguchi, "Integrating Multimodal Communication and Comprehension Evaluation during Human-Robot Collaboration for Increased Reliability of Foundation Model-based Task Planning Systems," <strong>IEEE/SICE International Symposium on System Integration (SII)</strong>, Germany, Jan. 2025, accepted. </div>
        1. <div style="font-size: 0.8em">B. Bastin, S. Hasegawa, J. Solis, R. Ronsse, B. Macq, L. El Hafi, G A. Garcia Ricardez, T. Taniguchi, "GPTAlly: A Safety-Oriented System for Human-Robot Collaboration based on Foundation Models," <strong>IEEE/SICE International Symposium on System Integration (SII)</strong>, Germany, Jan. 2025, accepted. </div>

        <a href="./slides/#domestic" style="color: #4B65E2;">See All Slides ></a>
    design:
      columns: '1'
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['80px', '0px', '20px', '0px']
  # - block: resume-awards
  #   id: awards
  #   content:
  #     title: 🏆 Awards
  #     username: admin
  #   design:
  #     spacing:
  #       # Customize the section spacing. Order is top, right, bottom, left.
  #       padding: ['80px', '0px', '20px', '0px']
  - block: markdown
    id: experience
    content:
      title: 'Experience'
      subtitle: ''
      text: |
        ### 🏢 Employments
        - <a href="">立命館大学総合科学技術研究機構</a>, Shiga.
          - Research Assistant (Apr. 2023 - Present)
        - <a href="">立命館大学グローバルイノベーション機構</a>, Shiga.
          - Research Assistant (Apr. 2022 - Mar. 2023)
        - <a href="">OMRON Corporation</a>, Kyoto.
          - Research Internship (Feb. 2021 - Mar. 2021)
    
    design:
      columns: '1'
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['80px', '0px', '20px', '0px']

  - block: markdown
    id: fellowships
    content:
      title: '🎓 Fellowships & Scholarships'
      subtitle: ''
      text: |
        ### Fellowships
        1. <div style="font-size: 0.8em"><a href="">立命館先進研究アカデミー学生フェローシッププログラム（RARA×SPRING）(国立研究開発法人科学技術振興機構(JST) 次世代研究者挑戦的研究プログラム)</a>, <strong>JPY 180K/month</strong>, Apr. 2024 - Mar. 2025.</div>
        1. <div style="font-size: 0.8em"><a href="">立命館大学NEXTフェローシップ・プログラム (文部科学省 科学技術イノベーション創出に向けた大学フェローシップ創設事業)</a>, <strong>JPY 180K/month</strong>, Apr. 2022 - Mar. 2024.</div>

        ### Scholarships
        1. <div style="font-size: 0.8em"><a href="https://www.ritsumei.ac.jp/ru_gr/g-career/fellow/doctor/article.html/?id=2">立命館大学大学院 博士課程後期課程研究奨励奨学金B</a>, <strong>JPY 250K</strong>, Jul. 2024.</div>
        1. <div style="font-size: 0.8em"><a href="https://www.ritsumei.ac.jp/ru_gr/g-career/fellow/master/article.html/?id=48">2年次対象成績優秀者奨学金</a>, <strong>JPY 450K</strong>, May. 2021.</div>
        1. <div style="font-size: 0.8em"><a href="https://www.ritsumei.ac.jp/ru_gr/g-career/fellow/master/article.html/?id=50">1年次対象成績優秀者奨学金</a>, <strong>JPY 450K</strong>, May. 2020.</div>
        1. <div style="font-size: 0.8em"><a href="https://www.ritsumei.ac.jp/scholarship/curriculum/#curriculum01">2018年度秋学期 西園寺記念奨学金 (成績優秀者枠)</a>, <strong>JPY 300K</strong>, Oct. 2018.</div>
        1. <div style="font-size: 0.8em"><a href="https://www.ritsumei.ac.jp/scholarship/curriculum/#curriculum01">2016年度 西園寺記念奨学金（成績優秀者枠)</a>, <strong>JPY 300K</strong>, Apr. 2017.</div>
    design:
      columns: '1'
      # background:
      #   color: 'gray'
      # TODO:
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['80px', '0px', '20px', '0px']
  - block: resume-skills
    id: skills
    content:
      title: 💻 Skills & Certifications
      username: admin
    design:
      show_skill_percentage: false
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['80px', '0px', '40px', '0px']
  - block: resume-languages
    content:
      title: 💬 Languages
      username: admin
    design:
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['10px', '0px', '20px', '0px']
  # - block: markdown
  #   content:
  #     title: '📰 Misc'
  #     subtitle: ''
  #     text: |
  #       - <div style="font-size: 0.8em">長谷川 翔一, 牧原 昂志, パドマナバン シッダート, 若林 勇太, "学生編集委員会取材企画：人が"こころ''を感じる気の利いたロボットの実現を目指して,"日本ロボット学会誌, vol.42, no.3, pp.247-252, 2024年4月,　<a href="https://www.jstage.jst.go.jp/article/jrsj/42/3/42_42_247/_article/-char/ja/">pdf</a>.</div>
  #       - <div style="font-size: 0.8em">長谷川 翔一, "第41回日本ロボット学会学術講演会レポート（オーガナイズドセッション：基盤モデルの実ロボット応用（2/3））,"日本ロボット学会誌, vol.42, no.1, pp.48-49, 2024年1月,　<a href="https://www.jstage.jst.go.jp/article/jrsj/42/1/42_42_48/_article/-char/ja/">pdf</a>.</div>
        
  #   design:
  #     columns: '1'
  #     spacing:
  #       # Customize the section spacing. Order is top, right, bottom, left.
  #       padding: ['80px', '0px', '40px', '0px']
---
#   - block: cta-card
#     demo: true # Only display this section in the Hugo Blox Builder demo site
#     content:
#       title: 👉 Build your own academic website like this
#       text: |-
#         This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

#         <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

#         Easily build anything with blocks - no-code required!
        
#         From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
#       button:
#         text: Get Started
#         url: https://hugoblox.com/templates/
#     design:
#       card:
#         # Card background color (CSS class)
#         css_class: "bg-primary-700"
#         css_style: ""
# ---

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
        Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

        I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
        Please reach out to collaborate 😃
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
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
      title: Recent News
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
      title: '📜 Representative Publications'
      subtitle: ''
      text: |
        ### Journal
        1. <div style="font-size: 0.8em"><u><strong>S. Hasegawa</strong></u>, K. Murata, T. Ishikawa, Y. Hagiwara, A. Taniguchi, L. El Hafi, G. Garcia, T. Taniguchi, "大規模言語モデルによる複数ロボットの知識統合とタスク割当を用いた現場学習のコスト削減," <strong>Journal of RSJ Letter</strong>, 2024, accepted. </div>
        1. <div style="font-size: 0.8em"><u><strong>S. Hasegawa</strong></u>, A. Taniguchi, Y. Hagiwara, L. El Hafi, T. Taniguchi, "Integrating Probabilistic Logic and Multimodal Spatial Concepts for Efficient Robotic Object Search in Home Environments," <strong>SICE Journal of Control, Measurement, and System Integration (SICE JCMSI)</strong>, Vol. 16, No. 1, pp. 400-422, 2023, <a href="https://www.tandfonline.com/doi/full/10.1080/18824889.2023.2283954">paper</a>. DOI: 10.1080/18824889.2023.2283954 (🏆<strong>2023年度立命館大学大学院 情報理工学研究科奨励賞</strong>) </div>

        ### International Conference (Peer-Reviewed)
        1. <div style="font-size: 0.8em">E. Martin, <u><strong>S. Hasegawa</strong></u>, J. Solis, B. Macq, R. Ronsse, G A. Garcia Ricardez, L. El Hafi, T. Taniguchi, "Integrating Multimodal Communication and Comprehension Evaluation during Human-Robot Collaboration for Increased Reliability of Foundation Model-based Task Planning Systems," <strong>IEEE/SICE International Symposium on System Integration (SII)</strong>, Germany, Jan. 2025, accepted. </div>
        1. <div style="font-size: 0.8em">B. Bastin, S. Hasegawa, J. Solis, R. Ronsse, B. Macq, L. El Hafi, G A. Garcia Ricardez, T. Taniguchi, "GPTAlly: A Safety-Oriented System for Human-Robot Collaboration based on Foundation Models," <strong>IEEE/SICE International Symposium on System Integration (SII)</strong>, Germany, Jan. 2025, accepted. </div>
        1. <div style="font-size: 0.8em">A. Oyama, S. Hasegawa, Y. Hagiwara, A. Taniguchi, T. Taniguchi, "ECRAP: Exophora Resolution and Classifying User Commands for Robot Action Planning by Large Language Models," <strong>IEEE International Conference on Robotic Cpmputing (IRC)</strong>, Japan, Dec. 2024, in press, <a href="https://emergentsystemlabstudent.github.io/ECRAP/">project page</a>. </div>
        1. <div style="font-size: 0.8em">T. Sakaguchi, A. Taniguchi*, Y. Hagiwara, L. El Hafi, S. Hasegawa, T. Taniguchi, "Real-world Instance-specific Image Goal Navigation for Service Robots: Bridging the Domain Gap with Contrastive Learning," <strong>IEEE International Conference on Robotic Cpmputing (IRC)</strong>, Japan, Dec. 2024, in press, <a href="https://arxiv.org/abs/2404.09645">arxiv</a>, <a href="https://emergentsystemlabstudent.github.io/DomainBridgingNav/">project page</a>, <a href="https://github.com/EmergentSystemLabStudent/DomainBridgingNav">code</a>, <a href="https://speakerdeck.com/shoichi_hasegawa/irc24-real-world-instance-specific-image-goal-navigation-bridging-domain-gap-via-contrastive-learning">slide</a>. (🏆<strong>Best Paper Award</strong>)</div>
        1. <div style="font-size: 0.8em">H. Nakagawa, S. Hasegawa, Y. Hagiwara, A. Taniguchi, T. Taniguchi, "Pointing Frame Estimation with Audio-Visual Time Series Data for Daily Life Service Robots," <strong>IEEE International Conference on Systems, Man, and Cybernetics (SMC)</strong>, Malaysia, Oct. 2024, in press, <a href="https://emergentsystemlabstudent.github.io/PointingImgEst/">project page</a>, <a href="https://speakerdeck.com/shoichi_hasegawa/pointing-frame-estimation-with-audio-visual-time-series-data-for-daily-life-service-robots">slide</a>. (🏆<strong>Best Paper Award</strong>)</div>
        1. <div style="font-size: 0.8em">T. Sakaguchi, A. Taniguchi*, Y. Hagiwara, L. El Hafi, S. Hasegawa, T. Taniguchi, "Object Instance Retrieval in Assistive Robotics: Leveraging Fine-Tuned SimSiam with Multi-View Images Based on 3D Semantic Map," <strong>IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)</strong>, Abu Dabi, Oct. 2024, in press, <a href="https://arxiv.org/abs/2404.09647">arxiv</a>, <a href="https://emergentsystemlabstudent.github.io/MultiViewRetrieve/">project page</a>, <a href="https://github.com/EmergentSystemLabStudent/MultiViewRetrieve">code</a>. </div>
        1. <div style="font-size: 0.8em">A. Oyama, S. Hasegawa, H. Nakagawa, A. Taniguchi, Y. Hagiwara, T. Taniguchi, "Exophora Resolution of Linguistic Instructions with a Demonstrative based on Real-World Multimodal Information," <strong>IEEE International Conference on Robot & Human Interactive Communication (RO-MAN)</strong>, pp. 2617-2623, Korea, Aug. 2023, <a href="https://ieeexplore.ieee.org/document/10309487">paper</a>. DOI: 10.1109/RO-MAN57019.2023.10309487 (🏆<strong>ロボカップ研究賞</strong>) </div>
        1. <div style="font-size: 0.8em">S. Hasegawa, A. Taniguchi, Y. Hagiwara, L. El Hafi, T. Taniguchi, "Inferring Place-Object Relationships by Integrating Probabilistic Logic and Multimodal Spatial Concepts," <strong>IEEE/SICE International Symposium on System Integration (SII)</strong>, pp. 1-8, USA, Jan. 2023, <a href="https://ieeexplore.ieee.org/document/10039318">paper</a>. DOI: 10.1109/SII55687.2023.10039318 (🏆<strong>Best Paper Award</strong>, 🏆<strong>SICE International Young Authors Award for SII</strong>, 🏆<strong>ロボカップ研究賞</strong>, 🏆<strong>計測自動制御学会 関西支部 奨励賞</strong>, 🏆<strong>第4回とめ研究所若手研究者懸賞論文 優秀賞</strong>, 🏆<strong>2022年度立命館大学大学院 情報理工学研究科研究奨励賞</strong>)</div>

        <a href="./slides/#international" style="color: #4B65E2;">See All Slides ></a>

        ### International Conference (Non Peer-Reviewed)
        1. <div style="font-size: 0.8em">長谷川 翔一, 伊藤 昌樹, 山木 良輔, 坂口 太一, 萩原 良信, 谷口 彰, エル ハフィ ロトフィ, 谷口 忠大, "生活支援ロボットの行動計画のための大規模言語モデルと場所概念モデルの活用," 第41回日本ロボット学会学術講演会 (RSJ), 大阪, 2023年9月, <a href="https://speakerdeck.com/shoichi_hasegawa/rsj23-leveraging-a-large-language-model-and-a-spatial-concept-model-for-action-planning-of-a-daily-life-support-robot">slide</a>.</div>
        1. <div style="font-size: 0.8em">S. Hasegawa, 伊藤 昌樹, 山木 良輔, 坂口 太一, 萩原 良信, 谷口 彰, エル ハフィ ロトフィ, 谷口 忠大, "生活支援ロボットの行動計画のための大規模言語モデルと場所概念モデルの活用," 第41回日本ロボット学会学術講演会 (RSJ), 大阪, 2023年9月, <a href="https://speakerdeck.com/shoichi_hasegawa/rsj23-leveraging-a-large-language-model-and-a-spatial-concept-model-for-action-planning-of-a-daily-life-support-robot">slide</a>.</div>

        ### Domestic Conference
        1. <div style="font-size: 0.8em">松嶋 達也, 高波 亮介, 神原 元就, 野口 裕貴, 有馬 純平, 池田 悠也, 柳田 栞吾, 岩田 健輔, 長谷川 翔一, エル ハフィ ロトフィ, 山尾 晃世, 磯本 航世, 山口 直紀, 小林 遼平, 柴 智也, 矢野 優雅, 水谷 彰伸, 田向 権, 堀井 隆斗, 杉浦 孔明, 谷口 忠大, 松尾 豊, 岩澤 有祐, "HSRT-X: コミュニティを活用したロボット基盤モデルの構築," 第42回日本ロボット学会学術講演会 (RSJ), 大阪, 2024年9月.</div>
        1. <div style="font-size: 0.8em">長谷川 翔一, 伊藤 昌樹, 山木 良輔, 坂口 太一, 萩原 良信, 谷口 彰, エル ハフィ ロトフィ, 谷口 忠大, "生活支援ロボットの行動計画のための大規模言語モデルと場所概念モデルの活用," 第41回日本ロボット学会学術講演会 (RSJ), 大阪, 2023年9月, <a href="https://speakerdeck.com/shoichi_hasegawa/rsj23-leveraging-a-large-language-model-and-a-spatial-concept-model-for-action-planning-of-a-daily-life-support-robot">slide</a>.</div>
        1. <div style="font-size: 0.8em">萩原 良信, 長谷川 翔一, 大山 瑛, 谷口 彰, エル ハフィ ロトフィ, 谷口 忠大, "現場環境で学習した知識に基づく曖昧な発話からの生活物理支援タスク," 第41回日本ロボット学会学術講演会 (RSJ), 大阪, 2023年9月. (🏆<strong>HSRコミュニティ優秀論文賞</strong>, 🏆<strong>第5回 優秀研究・技術賞</strong>)</div>
        1. <div style="font-size: 0.8em">大竹 俊輔, 前山 功伊, 長谷川 翔一, 中島 毅士, 谷口 彰, 谷口 忠大, 山川 宏, "海馬体に学んだ確率的生成モデルの実装と有効性検証," 第37回人工知能学会全国大会, 熊本, 2023年6月, <a href="https://www.jstage.jst.go.jp/article/pjsai/JSAI2023/0/JSAI2023_1Q3OS7a05/_article/-char/ja/">paper</a>. </div>
        1. <div style="font-size: 0.8em">長谷川 翔一, 下ノ村 和弘, "曲面型触覚画像センサによる生エビ接触検査," ロボティクス・メカトロニクス講演会2020, オンライン, 2020年5月, <a href="https://www.jstage.jst.go.jp/article/jsmermd/2020/0/2020_2A1-P06/_article/-char/ja/">pdf</a>. </div>
        

        <a href="./slides/#domestic" style="color: #4B65E2;">See All Slides ></a>
    design:
      columns: '1'
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['80px', '0px', '20px', '0px']
  - block: resume-awards
    id: awards
    content:
      title: 🏆 Awards
      username: admin
    design:
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['80px', '0px', '20px', '0px']
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

        ### 🏫 Professional Memberships
        - <a href="https://www.ieeesmc.org/">IEEE Systems, Man, & Cybernetics Society</a>
          - Student Member (Sep. 2024 - Present)
        - <a href="https://www.ai-gakkai.or.jp/en/">The Japanese Society for Artificial Intelligence (JSAI)</a>
          - Student Member (Oct. 2023 - Present)
        - <a href="https://www.ieee.org/">Institute of Electrical and Electronics Engineers (IEEE)</a>
          - Student Member (Sep. 2023 - Present)
        - <a href="https://www.rsj.or.jp/en/">The Robotics Society of Japan (RSJ)</a>
          - Student Member (Jun. 2023 - Present)
          - Student Editor (Apr. 2023 - Present)
        - <a href="https://www.sice.jp/">The Society of Instrument and Control Engineers (SICE)</a>
          - Student Member (Jan. 2023 - Present)
    
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
  - block: markdown
    content:
      title: '📰 Misc'
      subtitle: ''
      text: |
        - 日刊工業新聞 (19面), 「<a href="https://www.nikkan.co.jp/articles/view/00724640">慶大、実世界検索エンジンで物探しの推薦効率向上</a>」, 2024年9月16日.
        - Research demonstration for the U.S. Ambassador to the United Nations and the State Minister for Foreign Affairs of Japan.
          - Keio University, "<a href="https://www.keio.ac.jp/en/news/2024/Apr/30/48-158580/">US Ambassador to the United Nations Linda Thomas-Greenfield Visits Keio University</a>," Apr. 30, 2024.
          - Ministry of Foreign Affairs of Japan, "<a href="https://www.mofa.go.jp/press/release/pressite_000001_00289.html">Participation of State Minister for Foreign Affairs TSUJI Kiyoto in Japan-U.S. Joint Event on Artificial Intelligence (AI)</a>," Apr. 18, 2024.
          - JIJI.com, 「<a href="https://www.jiji.com/jc/article?k=2024041801147&g=soc">ＡＩ研究の学生にエール　米国国連大使</a>」, 2024年4月18日. (ほか多数)
        - <a href="https://www.oreilly.co.jp/books/9784814400591/">ゼロから作るDeep Learning ❺ ―生成モデル編</a>, <a href="https://tree-radius-a8e.notion.site/80f8bfc333d244fdbd1f69a2acd37dc0">公開レビュー</a>, 2024年4月10日.
        - 「<a href="https://www.ymd.nii.ac.jp/tid-crest/event/jst-crest-imaiyamadasympo2024">JST CREST今井・山田チーム合同シンポジウム2024『信頼と文脈の研究がもたらす新たな人工知能』</a> 」, 2024年2月20日.
        - ロボ學, 「<a href="https://robogaku.jp/news/2023/rsj2022_4f3.html">学生編集委員企画：第40回日本ロボット学会学術講演会レポート（OS16：確率ロボティクスとデータ工学ロボティクス〜認識・行動学習・記号創発〜（4/4））</a>」, 2023年2月14日.
        - <a href="https://www.oreilly.co.jp/books/9784873119755/">ゼロから作るDeep Learning ❹ ―強化学習編</a>, <a href="https://tree-radius-a8e.notion.site/442ed77a97a64bd8aa5527fe66009817?v=dedb2b6f537c49278d07f6c8e7ebbbea">公開レビュー</a>, 2022年4月6日.
        - Journal Club (in Japanese🎌)
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-ram-retrieval-based-affordance-transfer-for-generalizable-zero-shot-robotic-manipulation">RAM [Kuang+, CoRL24]</a>
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-language-embedded-gaussian-splats-legs-incrementally-building-room-scale-representations-with-a-mobile-robot">LEGS [Yu+, IROS24]</a>
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-seeing-the-unseen-visual-common-sense-for-semantic-placement">Semantic Placement [Ramrakhya+, CVPR24]</a>
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-moka-open-vocabulary-robotic-manipulation-through-mark-based-visual-prompting">MOKA [Fang+, RSS24]</a>
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-rrex-bot-remote-referring-expressions-with-a-bag-of-tricks">RREx-BoT [Sigurdsson+, IROS23]</a>
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-tidybot-personalized-robot-assistance-with-large-language-models">TidyBot [Wu+, IROS23]</a>
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-ifor-iterative-flow-minimization-for-robotic-object-rearrangement">IFOR [Goyal+, CVPR22]</a>
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-dialfred-dialogue-enabled-agents-for-embodied-instruction-following">DialFRED [Gao+, RA-L22]</a>
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-object-memory-transformer-for-object-goal-navigation">OMT [Fukushima+, ICRA22]</a>
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-following-natural-language-instructions-for-household-tasks-with-landmark-guided-search-and-reinforced-pose-adjustment">LGS-RPA [Murray+, RA-L22]</a>
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-a-simple-approach-for-visual-rearrangement-3d-mapping-and-semantic-search">Visual Rearrangement [Trabucco+, ICLR23]</a>
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-doorgym-a-scalable-door-opening-environment-and-baseline-agent">DoorGym [Urakami+, NeurIPSW19]</a>
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-mobile-former-bridging-mobilenet-and-transformer">Mobile-Former [Chen+, CVPR22]</a>
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-rapid-exploration-for-open-world-navigation-with-latent-goal-models">RECON [Shah+, CoRL21]</a>
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-iterative-shrinking-for-referring-expression-grounding-using-deep-reinforcement-learning">ISREG [Sun+, CVPR21]</a>
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-uniter-universal-image-text-representation-learning">UNITER [Chen+, ECCV20]</a>

          <a href="./slides/#journal-club" style="color: #4B65E2;">See All Slides ></a>
    # TODO: KTM?
    design:
      columns: '1'
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['80px', '0px', '40px', '0px']
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

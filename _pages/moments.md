---
layout: page
title: moments
title_en: "Moments‌"
title_zh: "朋友圈"
permalink: /moments/
nav: true
nav_order: 6
author_profile: true
---

<style>
  .performance-page {
    --performance-purple: #7c3aed;
    --performance-purple-dark: #5b21b6;
    --performance-border: rgba(124, 58, 237, 0.18);
    --performance-muted: var(--global-text-color-light);
  }

  .performance-section {
    margin: 1.25rem 0 1.75rem;
    padding: 1.25rem;
    border: 1px solid var(--performance-border);
    border-radius: 8px;
    background: var(--global-card-bg-color);
    box-shadow: 0 0.35rem 1.2rem rgba(0, 0, 0, 0.04);
  }

  .performance-section h2 {
    margin: 0 0 1rem;
    font-size: 1.25rem;
    line-height: 1.35;
  }

  .performance-summary {
    display: grid;
    grid-template-columns: minmax(0, 1fr) minmax(220px, 32%);
    gap: 1.25rem;
    align-items: start;
  }

  .performance-summary p {
    margin: 0;
    text-align: justify;
  }

  .performance-photo {
    width: 100%;
    aspect-ratio: 4 / 3;
    object-fit: cover;
    border-radius: 8px;
    border: 1px solid var(--performance-border);
  }

  .performance-timeline {
    display: grid;
    gap: 0.85rem;
  }

  .performance-item {
    display: grid;
    grid-template-columns: 8.75rem minmax(0, 1fr);
    gap: 1rem;
    align-items: stretch;
  }

  .performance-section--ensembles .performance-item {
    grid-template-columns: max-content minmax(0, 1fr);
  }

  .performance-date {
    display: flex;
    align-items: center;
    justify-content: center;
    min-height: 3rem;
    padding: 0.55rem 0.7rem;
    border-radius: 8px;
    background: linear-gradient(135deg, var(--performance-purple), var(--performance-purple-dark));
    color: #fff;
    font-weight: 700;
    line-height: 1.25;
    text-align: center;
  }

  .performance-section--ensembles .performance-date {
    white-space: nowrap;
  }

  .performance-content {
    min-width: 0;
    padding: 0.75rem 0.95rem;
    border: 1px solid var(--performance-border);
    border-radius: 8px;
    background: rgba(124, 58, 237, 0.035);
  }

  .performance-content strong {
    display: block;
    margin-bottom: 0.2rem;
  }

  .performance-note {
    margin: -0.35rem 0 1rem;
    color: var(--performance-muted);
    font-size: 0.95rem;
  }

  @media (max-width: 680px) {
    .performance-section {
      padding: 1rem;
    }

    .performance-summary,
    .performance-item {
      grid-template-columns: 1fr;
    }

    .performance-date {
      justify-content: flex-start;
      min-height: auto;
    }
    .performance-content a {
    color: inherit;           /* 继承原有文字颜色 */
    text-decoration: none;    /* 去除下划线 */
}

.performance-content a:hover {
    text-decoration: underline; /* 鼠标悬停显示下划线 */
}
  }
</style>

<div class="performance-page">
  <section class="performance-section">
    <h2>乐团概述</h2>
    <div class="performance-summary">
      <div>
        <p> 卢锦鑫，小号演奏员。曾任哈尔滨工程大学大学生管弦乐团（军乐团）团长，国防科技大学高地号角军乐团小号声部长，国防科技大学109爱乐乐团学生指挥。</p>
        <p> 哈尔滨工程大学大学生管弦乐团成立于2010年，作为学校推广素质教育的一个两点，现已发展成为一支具有较高演奏水平的校园精品艺术团队，乐团指挥由国家一级指挥孙南航担任。乐团成立以来，一直活跃在校内外的舞台上。作为艺术团，我们参加了哈尔滨之夏音乐会、哈工程艺苑芳菲专场演出、哈尔滨工程大学新年音乐会等一系列演出。近年来，乐团参与了多项大型比赛。在第四届全国大学生艺术展演中荣获三等奖、在第四届黑龙江大学生艺术展演荣获三等奖、在第四届全省舞台艺术教育成果调研评比中荣获二等奖。在黑龙江省第六届大学生艺术展演活动中荣获二等奖、部分优秀乐团团员也在第三节舞台艺术教育成果调研评比中荣获一、二等奖。</p>
        <p> 国防科技大学高地号角军乐团是学校大型业余管弦乐团，位居学校基层俱乐部之首，现有成员百余人，由在校师生及家属组成，设团长、副团长及俱乐部骨干7人，特邀中国著名指挥家、“高地”文化大使于海、肖鸣等名师艺术指导，聘请湖南工商大学音乐学院专业师资授课教学。乐团坚持以文化人、以文育人，奏响强军号角、激昂奋斗精神，担任学校开学典礼、毕业典礼、颁奖典礼等重大活动司礼任务，多次开展专场音乐会等群众性文化活动，丰富了校园文化生活，为部队培养输送了大批文艺骨干，2024年参加全军“强军号角”军乐视频汇演，被评为全军优秀业余军乐队（仅10支）。2025年，42名乐团骨干参加纪念中国人民抗日战争暨世界反法西斯战争胜利80周年大会，在联合军乐团千人受阅方阵中，以如磐的信念和昂扬的姿态接受了党和人民的检阅。</p>
        <p> 国防科技大学109爱乐乐团成立于2023年10月，挂靠电子科学学院，成员主要为科大在读硕博生。乐团具备作曲、编曲和排练能力，现有成员超过30人。乐团的选曲风格广泛，涵盖古典、现代、流行及影视音乐，并致力于融合古典与现代元素，形成独特风格。乐团每周进行排练和兴趣小组学习，过去三年进行了十余次各类演出，涵盖”华为之夜”、“乐动风华“等校内外各大活动，并举办两届新年专场音乐会。</p>
      </div>
      <img class="performance-photo" src="{{ '/assets/img/kaixuedianli.jpg' | relative_url }}" alt="performance photo">
    </div>
  </section>

  <section class="performance-section performance-section--ensembles">
    <h2>乐团经历</h2>
    <div class="performance-timeline">
      <div class="performance-item">
        <div class="performance-date">2021.10 - 2025.07</div>
        <div class="performance-content">
          哈尔滨工程大学大学生管弦乐团、大学生军乐团 小号声部演奏员
        </div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2022.10 - 2023.09</div>
        <div class="performance-content">
          哈尔滨工程大学大学生管弦乐团、大学生军乐团 小号声部长
        </div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2023.09 - 2024.09</div>
        <div class="performance-content">
          哈尔滨工程大学大学生管弦乐团、大学生军乐团 团长
        </div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2025.10 - 2026.07</div>
        <div class="performance-content">
          国防科技大学高地号角军乐团、高地交响乐团 小号声部演奏员
        </div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2026.03 - 2026.07</div>
        <div class="performance-content">
          国防科技大学高地号角军乐团、高地交响乐团 小号声部长
        </div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2025.10 - 2026.07</div>
        <div class="performance-content">
          国防科技大学109爱乐乐团 学生指挥
        </div>
      </div>
    </div>
  </section>

  <section class="performance-section">
    <h2>演出经历</h2>
    <p class="performance-note">截至2026.7（含）累计31场</p>
    <div class="performance-timeline">
      <div class="performance-item">
        <div class="performance-date">2022.06</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/2P43g92RfnH6QJDVicn2_A" target="_blank" rel="noopener noreferrer">参与黑龙江省首届“田家炳”杯大学生美育成果展演</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2023.08</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/GVUbr3Wd16UwkHwHSZkZ5w" target="_blank" rel="noopener noreferrer">参与“七秩辉煌、国韵悠扬”哈尔滨工程大学建校70周年民族交响音乐会演出</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2023.08</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/W8hIK33U3dq6eL_Fyokjsg" target="_blank" rel="noopener noreferrer">参与哈尔滨工程大学2023级本科生开学典礼暨军训动员大会演出</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2023.09</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/jgIZI3OqQnCWp1Jz7KL8DA" target="_blank" rel="noopener noreferrer">参与哈尔滨工程大学建校70周年创新发展大会演出</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2023.09</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/cvqDIHxCgqkUkhak2duulg" target="_blank" rel="noopener noreferrer">参与“七秩颂歌、逐光远航”哈尔滨工程大学建校70周年文艺晚会演出</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2023.09</div>
        <div class="performance-content">
        <a href="https://weixin.qq.com/sph/AeQX1vE8sx" target="_blank" rel="noopener noreferrer">参与哈尔滨工程大学2023级本科生新生行军拉练演出</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2023.09</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/WOOIU1Y4vYnHb94AL5U4NA" target="_blank" rel="noopener noreferrer">参与哈尔滨工程大学2023级本科生军训成果汇报大会演出</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2023.09</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/TDSx1qGNuXU8k__GFljsxQ" target="_blank" rel="noopener noreferrer">参与哈尔滨工程大学“秋韵华章”庆中秋、迎国庆交响音乐会演出</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2023.11</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/dG6ykwCxMRrM8c2z__I5kg" target="_blank" rel="noopener noreferrer">参与哈尔滨工程大学“金晖行动”志愿活动演出</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2023.12</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/PxjAoIlW0bTwBFJVd5xftA" target="_blank" rel="noopener noreferrer">参与哈尔滨工程大学新时代本科教育高质量创新发展大会演出</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2024.05</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/ATKFxkMJT-PBlizTVqkQ1w" target="_blank" rel="noopener noreferrer">参与哈尔滨工程大学“五季五节”活动——“臻美”艺术节演出</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2024.05</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/6e8D04ff3BCa9j7UHBjvJw" target="_blank" rel="noopener noreferrer">参与哈尔滨工程大学“唱响青春、挺膺担当”主题歌会演出（担任指挥）</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2024.05</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/b7x2HKdyigDiPZ94KL-12w" target="_blank" rel="noopener noreferrer">参与哈尔滨工程大学第四十七届田径运动会开幕式演出</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2024.06</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/jmN_fNOzxKFwFf-wDPvucw" target="_blank" rel="noopener noreferrer">参与哈尔滨工程大学2024届毕业晚会演出</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2024.08</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/MaBA-tN8qrnz6RgRFkJJvw" target="_blank" rel="noopener noreferrer">参与哈尔滨工程大学2024级本科生新生行军拉练演出</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2024.11</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/4eXLByWjJIyBd1APbzDNuw" target="_blank" rel="noopener noreferrer">参与哈尔滨工程大学“金晖行动”志愿活动演出</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2025.06</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/1bISTyyPa2ySKpgrHYJ0-Q" target="_blank" rel="noopener noreferrer">参与哈尔滨工程大学“飞扬的旋律”西洋管弦乐合奏教学成果展示</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2025.11</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/GSI86gZ60KAVKYJCQSvy-Q" target="_blank" rel="noopener noreferrer">参与国防科技大学“我们从阅兵场走来”高地号角军乐团专场音乐会演出</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2025.11</div>
        <div class="performance-content">参与“华为杯”第四届中国研究生网络安全创新大赛全国总决赛颁奖晚会演出（担任指挥）</div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2026.01</div>
        <div class="performance-content">
        <a href="https://weixin.qq.com/sph/AfOazMzrEL" target="_blank" rel="noopener noreferrer">参与国防科技大学“高地迎新春、号角启征程”高地号角军乐团环校演奏</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2026.01</div>
        <div class="performance-content">
        <a href="https://weixin.qq.com/sph/AkfLpB0NUK" target="_blank" rel="noopener noreferrer">参与国防科技大学“高地荣光——致敬最美科大人”颁奖典礼演出</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2026.01</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/6cYe6uTshWP-PPC0B-7yxg" target="_blank" rel="noopener noreferrer">参与国防科技大学109爱乐乐团新年音乐会演出（担任指挥）</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2026.02</div>
        <div class="performance-content">
        <a href="https://weixin.qq.com/sph/AJEJsI5xIO" target="_blank" rel="noopener noreferrer">参与国防科技大学“高地号角”军乐团拜年视频录制</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2026.03</div>
        <div class="performance-content">
        <a href="https://weixin.qq.com/sph/AGbpEv2HPJ" target="_blank" rel="noopener noreferrer">参与国防科技大学“高地加速度”春季环校马拉松开幕式演出</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2026.05</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/kavbdY8L_QtBe8_d7-igdQ" target="_blank" rel="noopener noreferrer">参与中国军号、人民日报新媒体、湖南卫视 “热血青春 正步向前”首届迷彩音乐主题直播</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2026.05</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/iON4nNnCmPliTg0jftQBaA" target="_blank" rel="noopener noreferrer">参与国防科技大学“高地风华”校园路演（担任指挥）</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2026.05</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/EDZxBldJr2u6hxcu8Tqn8A" target="_blank" rel="noopener noreferrer">参与国防科技大学“高地乐动”校园路演</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2026.06</div>
        <div class="performance-content">参与国防科技大学“E路通行·唱响未来”毕业季歌手大赛嘉宾演出</div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2026.06</div>
        <div class="performance-content">
        <a href="https://weixin.qq.com/sph/AXPuVnExDw" target="_blank" rel="noopener noreferrer">参与国防科技大学献礼中国共产党成立105周年《红旗颂》视频录制</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2026.07</div>
        <div class="performance-content">参与全军“强军风采”群众性文化活动“强军号角”军乐视频汇演</div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2026.07</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/67jG4Gs_PabyMLO5iXYyiw" target="_blank" rel="noopener noreferrer">参与国防科技大学高地启航“告别母校”专场音乐会演出</a></div>
      </div>
    </div>
  </section>
  <section class="performance-section">
    <h2>其他媒体推送</h2>
    <p class="performance-note">出镜或撰文，截至2026.7（含）累计21条</p>
    <div class="performance-timeline">
      <div class="performance-item">
        <div class="performance-date">2021.11</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/JSzaCaQdyCRIC2GUOzrOqQ" target="_blank" rel="noopener noreferrer">【哈尔滨工程大学】Hi，哈工程初雪！</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2023.05</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/CRkQqEra-tv0oY7foq_6gA" target="_blank" rel="noopener noreferrer">【哈尔滨工程大学】今天，这些哈工程硬核青年获表彰！（参加全国五四红旗团支部表演）</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2023.08</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/eo93E1SlE_4qJqqYKwTQwg" target="_blank" rel="noopener noreferrer">【HEU国家大学生文化素质教育基地】超燃!2023校庆晚会排练现场</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2024.04</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/kQSunzXN0JfwuZBc4LU48A" target="_blank" rel="noopener noreferrer">【哈尔滨工程大学】“杏”会，一场倾“程”花海 ！</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2024.06</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/ykKsoJWLcUKML9_UKj1NEA" target="_blank" rel="noopener noreferrer">【哈尔滨工程大学】牢记嘱托！3432名哈工程毕业生逐梦启程！</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2024.06</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/_kW6RoXKf1JwgMjXtfoiKQ" target="_blank" rel="noopener noreferrer">【哈尔滨工程大学】哈工程毕业生最真情的告白，致你们！</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2024.09</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/FR208B6v73fbOLatsgagOg" target="_blank" rel="noopener noreferrer">【哈尔滨工程大学】牢记殷切嘱托！矢志不渝沿着习近平总书记指引的方向前进！（参会）</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2024.10</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/zB4LOI1bTMi2s9y-pFefbQ" target="_blank" rel="noopener noreferrer">【工学小程】倾囊相授！工学全媒体全体大会暨培训工作圆满结束！</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2024.11</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/VtSrpc9vcihQJxY5fx84GQ" target="_blank" rel="noopener noreferrer">【哈尔滨工程大学】倒计时30天，哈工程见！</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2024.11</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/bQhNXQZHZ9QEHKR7lBcqPw" target="_blank" rel="noopener noreferrer">【工学小程】管弦乐团“冬日交响”室内乐演出回顾（封面）</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2025.03</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/mwwYwtVaA-_q49e6wTaf4w" target="_blank" rel="noopener noreferrer">【哈尔滨工程大学】从“大国重器”看中国智慧！“华龙一号”总师邢继哈工程开讲！</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2025.04</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/PiPwrRyiaOvMYFwbIYa_Mw" target="_blank" rel="noopener noreferrer">【哈尔滨工程大学】全民国家安全教育走深走实十周年 | 忠诚捍卫 人人有责！（撰文）</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2025.06</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/F-p-hNlIz0SqBMvMOYaYgw" target="_blank" rel="noopener noreferrer">【HEU石榴籽】从“籽籽相拥”到“花开遍地”：这些榜样让民族团结有了生动模样！</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2025.06</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/wtegqzAQvNWFFE2EomScEw" target="_blank" rel="noopener noreferrer">【哈尔滨工程大学】石榴花开！这场文化盛宴爱住了！</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2025.06</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/T_BjWmBo5RyuMt1-CPoUqA" target="_blank" rel="noopener noreferrer">【哈尔滨工程大学】Show Time！哈工程毕业季，等你的高光镜头！🤳</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2025.06</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/PwehhTlaUE3vMc-olZMJfQ" target="_blank" rel="noopener noreferrer">【哈尔滨工程大学】强国强军 再立新功！2025届哈工程毕业生出发新征程！</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2025.06</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/HPg5SUU3MgUpP-FTm2Zs8Q" target="_blank" rel="noopener noreferrer">【哈工程学工】星语寄心 榜样如炬 | 哈尔滨工程大学2025届“毕业星语”特辑（六）</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2025.07</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/jKrCXDCGvCPMIwe-n3tEfA" target="_blank" rel="noopener noreferrer">【哈尔滨工程大学】跨越时空的入学通知书：强国强军的不变宣言！</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2025.09</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/3EqHC3txbeB75FuX6p4JAQ" target="_blank" rel="noopener noreferrer">【军科研究生院】闪亮蜕变丨研究生入学军训剪影</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2025.12</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/GZx6iP5Rzc_jm3QEH4jdmw" target="_blank" rel="noopener noreferrer">【哈尔滨工程大学】全省模范集体！哈工程+1！</a></div>
      </div>
      <div class="performance-item">
        <div class="performance-date">2026.06</div>
        <div class="performance-content">
        <a href="https://mp.weixin.qq.com/s/NUOvCFH_Q-OvfOlxnJSFwQ" target="_blank" rel="noopener noreferrer">【哈工程学工】HEU隐藏任务 | 集齐十项小事，领取哈工程专属青春毕业证</a></div>
      </div>
    </div>
  </section>
</div>

---
title: 보안 리소스
---

# 📚 보안 리소스

국가별, 주제별 보안 관련 리포트 페이지를 정리한 공간입니다.

<style>
.chapter-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
  gap: 20px;
  margin: 32px 0;
  padding: 0;
}

.chapter-card {
  background: #ffffff;
  border: 1px solid #e1e4e8;
  border-radius: 10px;
  padding: 0;
  transition: all 0.25s cubic-bezier(0.4, 0, 0.2, 1);
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.08);
  text-decoration: none;
  color: inherit;
  display: flex;
  flex-direction: column;
  overflow: hidden;
  height: 100%;
}

.chapter-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 6px 20px rgba(0, 0, 0, 0.12);
  border-color: #6200ea;
}

.chapter-header {
  padding: 20px;
  color: white;
  position: relative;
}

.chapter-card:nth-child(1) .chapter-header {
  background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
}

.chapter-card:nth-child(2) .chapter-header {
  background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
}

.chapter-card:nth-child(3) .chapter-header {
  background: linear-gradient(135deg, #43e97b 0%, #38f9d7 100%);
}

.chapter-card:nth-child(4) .chapter-header {
  background: linear-gradient(135deg, #fa709a 0%, #fee140 100%);
}

.chapter-card:nth-child(5) .chapter-header {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}

.chapter-number {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  background: rgba(255, 255, 255, 0.2);
  backdrop-filter: blur(10px);
  color: white;
  width: 32px;
  height: 32px;
  border-radius: 6px;
  font-weight: 700;
  font-size: 14px;
  margin-bottom: 10px;
  border: 1px solid rgba(255, 255, 255, 0.3);
}

.chapter-title {
  font-size: 20px;
  font-weight: 700;
  margin: 0;
  color: white;
  line-height: 1.3;
  letter-spacing: -0.01em;
}

.chapter-body {
  padding: 18px 20px;
  flex-grow: 1;
  display: flex;
  flex-direction: column;
}

.chapter-description {
  font-size: 13px;
  color: #586069;
  line-height: 1.6;
  margin: 0 0 16px 0;
  flex-grow: 1;
}

.chapter-link {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 8px 16px;
  background: #f6f8fa;
  color: #24292f;
  border: 1px solid #d0d7de;
  border-radius: 6px;
  text-decoration: none;
  font-size: 13px;
  font-weight: 600;
  transition: all 0.2s;
  width: 100%;
  box-sizing: border-box;
}

.chapter-link:hover {
  background: #6200ea;
  color: white;
  border-color: #6200ea;
  transform: translateY(-1px);
}

@media (max-width: 768px) {
  .chapter-grid {
    grid-template-columns: 1fr;
    gap: 16px;
  }
}
</style>

<div class="chapter-grid">

<a href="resource/" class="chapter-card">
  <div class="chapter-header">
    <span class="chapter-number">1</span>
    <div class="chapter-title">보안 리소스</div>
  </div>
  <div class="chapter-body">
    <div class="chapter-description">
      세계 여러나라의 정보보안 기관, 기업, 언론사 등 국가별 보안 리소스를 모아놓은 챕터입니다.
    </div>
    <div class="chapter-link">챕터 보기 →</div>
  </div>
</a>

</div>
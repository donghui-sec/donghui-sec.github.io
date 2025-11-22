---
title: Security Resource
---

# 📚 Security Resource

Country, Topic Security report page space.

<style>
.book-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: 28px;
  margin: 40px 0;
  padding: 0;
}

.book-card {
  background: #ffffff;
  border: 1px solid #e1e4e8;
  border-radius: 12px;
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

.book-card:hover {
  transform: translateY(-6px);
  box-shadow: 0 8px 24px rgba(0, 0, 0, 0.12);
  border-color: #6200ea;
}

.book-header {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  padding: 24px;
  color: white;
  position: relative;
}

.book-card:nth-child(1) .book-header {
  background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
}

.book-card:nth-child(2) .book-header {
  background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
}

.book-card:nth-child(3) .book-header {
  background: linear-gradient(135deg, #43e97b 0%, #38f9d7 100%);
}

.book-card:nth-child(4) .book-header {
  background: linear-gradient(135deg, #fa709a 0%, #fee140 100%);
}

.book-number {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  background: rgba(255, 255, 255, 0.25);
  backdrop-filter: blur(10px);
  color: white;
  width: 36px;
  height: 36px;
  border-radius: 8px;
  font-weight: 700;
  font-size: 16px;
  margin-bottom: 12px;
  border: 1px solid rgba(255, 255, 255, 0.3);
}

.book-title {
  font-size: 22px;
  font-weight: 700;
  margin: 0;
  color: white;
  line-height: 1.3;
  letter-spacing: -0.02em;
}

.book-body {
  padding: 20px 24px;
  flex-grow: 1;
  display: flex;
  flex-direction: column;
}

.book-description {
  font-size: 14px;
  color: #586069;
  line-height: 1.6;
  margin: 12px 0 20px 0;
  flex-grow: 1;
}

.book-meta {
  display: flex;
  align-items: center;
  gap: 12px;
  font-size: 12px;
  color: #8b949e;
  margin-bottom: 16px;
  padding-top: 16px;
  border-top: 1px solid #f0f0f0;
}

.book-meta-item {
  display: flex;
  align-items: center;
  gap: 4px;
}

.book-link {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 10px 20px;
  background: #6200ea;
  color: white;
  border-radius: 6px;
  text-decoration: none;
  font-size: 14px;
  font-weight: 600;
  transition: all 0.2s;
  width: 100%;
  box-sizing: border-box;
}

.book-link:hover {
  background: #7c3aed;
  transform: translateY(-1px);
  box-shadow: 0 4px 12px rgba(98, 0, 234, 0.3);
}

@media (max-width: 768px) {
  .book-grid {
    grid-template-columns: 1fr;
    gap: 20px;
  }
}
</style>

<div class="book-grid">

<a href="korea/" class="book-card">
  <div class="book-header">
    <span class="book-number">1</span>
    <div class="book-title">🇰🇷 South Korea</div>
  </div>
  <div class="book-body">
    <div class="book-description">
      South Korea Country, Topic Security report page space.
    </div>
    <div class="book-meta">
      <span class="book-meta-item">📊 Country Resource</span>
    </div>
    <div class="book-link">View →</div>
  </div>
</a>

<a href="usa/" class="book-card">
  <div class="book-header">
    <span class="book-number">2</span>
    <div class="book-title">🇺🇸 USA</div>
  </div>
  <div class="book-body">
    <div class="book-description">
      USA Country, Topic Security report page space.
    </div>
    <div class="book-meta">
      <span class="book-meta-item">📊 Country Resource</span>
    </div>
    <div class="book-link">View →</div>
  </div>
</a>

</div>
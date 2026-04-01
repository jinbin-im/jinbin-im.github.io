---
layout: about
title: About
permalink: /
---

<div class="about-container">
  <!-- 왼쪽 고정 프로필 -->
  <aside class="profile-sidebar">
    <div class="profile-content">
      <div class="profile-image">
        <img src="{{ '/assets/img/profile.jpg' | relative_url }}" alt="Jin-Bin Im">      
      </div>
      
      <h1 class="profile-name">Jin-Bin Im</h1>
      <p class="profile-title">Ph.D. Candidate</p>
      <p class="profile-affiliation">Hanyang University<br>Architectural Engineering</p>
      
      <div class="profile-links">
        <a href="mailto:your-email@hanyang.ac.kr" class="profile-link">
          <span>📧</span> Email
        </a>
        <a href="#" class="profile-link">
          <span>🎓</span> Google Scholar
        </a>
        <a href="#" class="profile-link">
          <span>📄</span> ResearchGate
        </a>
        <a href="#" class="profile-link">
          <span>💼</span> LinkedIn
        </a>
      </div>
    </div>
  </aside>

  <!-- 오른쪽 스크롤 가능한 메인 콘텐츠 -->
  <main class="main-content">
    <section class="about-section">
      <h2>About</h2>
      <p>Jin-Bin Im is a Ph.D. candidate at Hanyang University, specializing in Architectural Engineering. He is a graduate research assistant at the Client Briefing and Program Management (CB&PM) Lab.</p>
      
      <p>His research focuses on integrating AI and extended reality technologies to enhance human-centered design in built environments.</p>
    </section>

    <section class="research-section">
      <h2>Research Interest</h2>
      <ul class="research-list">
        <li>User-centered design</li>
        <li>Human responses to built environments</li>
        <li>Extended Reality (VR/MR) for architectural design</li>
        <li>AI-driven spatial design automation</li>
      </ul>
    </section>

    <section class="education-section">
      <h2>Education</h2>
      <div class="education-list">
        <div class="education-item">
          <div class="education-header">
            <strong class="degree">M.S/Ph.D. in Architectural Engineering, Construction Management</strong>
            <span class="year">2026 (Expected)</span>
          </div>
          <div class="institution">Hanyang University, South Korea</div>
        </div>

        <div class="education-item">
          <div class="education-header">
            <strong class="degree">B.S. Interior Architecture Design</strong>
            <span class="year">2020</span>
          </div>
          <div class="institution">Hanyang University, South Korea</div>
        </div>
      </div>
    </section>

    <section id="publications" class="publications-section">
      <h2>Publications</h2>
      <p class="section-description">Journal publications in reversed chronological order.</p>
  
      <div class="bibliography">
        {% bibliography --file papers --template papers %}
      </div>
    </section>

    <section id="conferences" class="conferences-section">
      <h2>Conferences</h2>
      <p class="section-description">Conference presentations in reversed chronological order.</p>
  
      <div class="bibliography">
        {% bibliography --file conferences --template conferences %}
      </div>
    </section>
  </main>
</div>

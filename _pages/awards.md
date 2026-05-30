---
layout: archive
title: "Awards & Honors"
permalink: /awards/
author_profile: true
---

<style>
.lightbox-overlay {
  display: none;
  position: fixed;
  inset: 0;
  background: rgba(0,0,0,0.9);
  z-index: 9999;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  gap: 16px;
  padding: 24px;
  cursor: zoom-out;
}
.lightbox-overlay.active { display: flex; }
.lightbox-overlay img {
  max-width: 90vw;
  max-height: 80vh;
  border-radius: 8px;
  object-fit: contain;
  cursor: default;
}
.lightbox-close {
  position: fixed;
  top: 16px;
  right: 24px;
  color: white;
  font-size: 40px;
  font-weight: 300;
  cursor: pointer;
  line-height: 1;
}
</style>

<div class="lightbox-overlay" id="lightbox" onclick="closeLightbox(event)">
  <span class="lightbox-close" onclick="closeLightbox()">&times;</span>
  <img id="lightbox-img" src="" alt="">
</div>

<script>
function openLightbox(src) {
  document.getElementById('lightbox-img').src = src;
  document.getElementById('lightbox').classList.add('active');
  document.body.style.overflow = 'hidden';
}
function closeLightbox(e) {
  if (e && e.target === document.getElementById('lightbox-img')) return;
  document.getElementById('lightbox').classList.remove('active');
  document.body.style.overflow = '';
}
document.addEventListener('keydown', function(e) {
  if (e.key === 'Escape') closeLightbox();
});
</script>

## Fellowships & Grants

<div style="display: flex; align-items: center; gap: 20px; margin-bottom: 20px;">
  <img src="/images/ieee_india_council.png" alt="IEEE India Council Logo" style="width: 200px; flex-shrink: 0;">
  <div>
    <strong>Shri Pralhad P Chhabria Best Graduate Student Award 2025</strong> | <em>2026</em><br>
    Awarded the Shri Pralhad P. Chhabria Best Graduate Student Award from the IEEE India Council, Hope Foundation and Research Centre (HFRC), IEEE Pune Section, and IEEE Women In Engineering Affinity Group, with a prize of INR 125,000. This award, established in 2017 in memory of Late Shri Pralhad P. Chhabria, Founder Chairman of Finolex Group of Companies, recognizes the top female graduate in Science, Technology, and Engineering across India for outstanding academic achievement and contributions to research, innovation, institute, and community. <a href="https://www.hfrc-ieeeawards.org/award-winners/" target="_blank">Award Details</a>
  </div>
</div>

<div style="display: flex; align-items: center; gap: 20px; margin-bottom: 20px;">
  <img src="/images/india_ai.jpg" alt="IndiaAI Logo" style="width: 200px; flex-shrink: 0;">
  <div>
    <strong>IndiaAI Mission Fellowship</strong> | <em>2024</em><br>
    Awarded the IndiaAI Mission fellowship with a grant of INR 100,000 from the Government of India's Ministry of Electronics & Information Technology (MeitY) to implement a text-to-SQL question answering system for medical records. This fellowship is given to ~100 undergraduate AI researchers from the top 50 engineering colleges in India.
  </div>
</div>

<div style="display: flex; align-items: center; gap: 20px; margin-bottom: 20px;">
  <img src="/images/mitacs.png" alt="Mitacs Logo" style="width: 200px; flex-shrink: 0;">
  <div>
    <strong>MITACS Globalink Research Scholar</strong> | <em>2024</em><br>
    Chosen as one of 1,000 students worldwide (300 from India) for the <strong>fully funded</strong> research internship offered by MITACS, the Government of Canada, and Canadian Universities. Worked with Dr. Sunil Kalmady Vasu and Dr. Russ Greiner at the University of Alberta and the Alberta Machine Intelligence Institute (Amii) on synthesizing ECGs with generative models.
  </div>
</div>

<div style="display: flex; align-items: center; gap: 20px; margin-bottom: 20px;">
  <img src="/images/netmob.jpg" alt="NetMob Logo" style="width: 200px; flex-shrink: 0;">
  <div>
    <strong>NetMob Student Grant</strong> | <em>2023</em><br>
    One of six students, and <strong>only undergraduate</strong>, to receive a grant to travel to NetMob 2023, Madrid, Spain. The grant was sponsored by the Spanish Ministry of Economic Affairs and Digital Transformation through PRTR and the European Union-NextGenerationEU. NetMob is the primary conference for mobile dataset analysis.
  </div>
</div>

<div style="display: flex; align-items: center; gap: 20px; margin-bottom: 20px;">
  <img src="/images/mn.png" alt="United Nations Millennium Fellowship" style="width: 200px; flex-shrink: 0;">
  <div>
    <strong>United Nations Millennium Fellow - Emerging Technologist</strong> | <em>2023</em><br>
    Part of the 2023 Class of the Millennium Fellowship, organized jointly by the United Nations Academic Impact (UNAI) and MCN, to develop solutions to promote Sustainable Development Goals. Selected from 44,000 applicants worldwide.<br>
    <a href="https://www.millenniumfellows.org/fellow/2023/snuadmissions/pooja-premnath" target="_blank">Fellowship Profile</a>
  </div>
</div>

<div style="display: flex; align-items: center; gap: 20px; margin-bottom: 20px;">
  <img src="/images/ssn.png" alt="SSN IFSP" style="width: 200px; flex-shrink: 0;">
  <div>
    <strong>SSN IFSP Grant</strong> | <em>2022</em><br>
    Awarded the Internally Funded Student Projects grant (INR 15,000) under the Stimuli for Technological Innovation & Research for Students (STIRS) program to develop a prototype for <em>Identification of Optimal Nodes in an Electrical Grid using Heatmap Centrality</em>.
  </div>
</div>

---

## Academic Merit Scholarships

<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 30px;">
  <img src="/images/silvermedal.jpg" style="width: 300px; flex-shrink: 0; cursor: zoom-in;" onclick="openLightbox(this.src)">
  <div>
    <strong>Department Silver Medallist - SSN College of Engineering</strong>
    <ul>
      <li>Awarded the Department Silver Medal for ranking 2nd out of 136 students in the Computer Science and Engineering graduating class of 2025.</li>
    </ul>
  </div>
</div>

<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 30px;">
  <img src="/images/scholarship.jpg" style="width: 300px; flex-shrink: 0; cursor: zoom-in;" onclick="openLightbox(this.src)">
  <div>
    <strong>Merit Scholarship Recipient - SSN College of Engineering</strong>
    <ul>
      <li>Awarded for academic excellence in 2022, 2024 and 2025.</li>
    </ul>
  </div>
</div>
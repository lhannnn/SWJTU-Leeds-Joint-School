---
layout: page
title: Home Page
permalink: /
---

<style>
.course-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 20px;
  padding: 20px 0;
}
.course-card {
  background: #fff;
  border-radius: 12px;
  padding: 20px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  text-align: center;
}
.course-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.15);
}
.course-icon {
  font-size: 40px;
  margin-bottom: 10px;
}
.course-title {
  font-size: 1.2rem;
  font-weight: bold;
  margin: 10px 0;
}
.course-desc {
  font-size: 0.95rem;
  color: #666;
  margin-bottom: 15px;
}
.course-button {
  display: inline-block;
  background-color: #007bff;
  color: white;
  padding: 8px 18px;
  border-radius: 6px;
  text-decoration: none;
  transition: background-color 0.2s ease;
}
.course-button:hover {
  background-color: #0056b3;
}
</style>

<div style="text-align: center;">
  <h1>🎓 SWJTU-Leeds Joint School Course Evaluation</h1>
  <p style="font-size: 1.1rem; color: #555;">A student-run platform to share study strategies and course feedback.</p>
</div>

<hr>

<div class="course-grid">

<!-- Engineering English -->
<div class="course-card">
  <div class="course-icon">📘</div>
  <div class="course-title">Engineering English</div>
  <div class="course-desc">Academic writing & communication skills.</div>
  <a class="course-button" href="{{ site.baseurl }}/engineering-english">Enter Course</a>
</div>

<!-- Physics -->
<div class="course-card">
  <div class="course-icon">🔭</div>
  <div class="course-title">Physics</div>
  <div class="course-desc">Theory, lab work & problem solving.</div>
  <a class="course-button" href="{{ site.baseurl }}/physics">Enter Course</a>
</div>

<!-- Mathematics -->
<div class="course-card">
  <div class="course-icon">📐</div>
  <div class="course-title">Mathematics</div>
  <div class="course-desc">Calculus, linear algebra, logic.</div>
  <a class="course-button" href="{{ site.baseurl }}/mathematics">Enter Course</a>
</div>

<!-- SPS -->
<div class="course-card">
  <div class="course-icon">🧪</div>
  <div class="course-title">Scientific Problem Solving</div>
  <div class="course-desc">Teamwork & logical reasoning.</div>
  <a class="course-button" href="{{ site.baseurl }}/sps">Enter Course</a>
</div>

</div>

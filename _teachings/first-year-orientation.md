---
layout: course
title: First-Year Orientation Course
description: >-
  This course is designed primarily for first-year undergraduate students and supports their transition from high school to university through general education, scientific inquiry, and personal development. It is organized around three modules: Me and My University, Me and My Major, and Me and Myself. Through small-group seminars and hands-on experiences, students learn about university life and Tsinghua traditions, explore interdisciplinary research through intelligent vehicle cases, and develop self-awareness, resilience, and a sense of responsibility.
instructor: Bingbing Nie, Hong Wang
year: 2026
term: Fall
course_id: 00150241-90
# Weekly plan rendered by this page (named "syllabus" so the default layout does not add its own schedule table)
syllabus:
  - week: 1
    topic: Course Introduction and Icebreaking
    description: An introduction to the course framework and assessment, followed by personal growth stories, small-group icebreaking activities, and a discussion of students' expectations for university life.

  - week: 2
    topic: Peer Experiences and University Life
    description: Invited upper-year students share their experiences of academic study, research and innovation, student leadership, public service, sports, and campus life. The session encourages students to build confidence, explore their interests, and find an approach to university life that suits them.

  - week: 3
    topic: North Gymnasium Visit and Fencing Experience
    description: Students visit Tsinghua University's North Gymnasium and take part in an introductory fencing experience, learning about campus sports facilities and experiencing physical education beyond the classroom.

  - week: 4
    topic: Vehicle Engineering and My Major
    description: Using vehicle engineering as an example, the session introduces major technological directions, industry and career pathways, the role of automobiles in society, and how research questions emerge from real engineering problems.

  - week: 5
    topic: "AI and Automotive Safety: A Research Case Study"
    description: A student research case on an AI-enabled active hood for pedestrian protection shows how a project develops from a safety problem and research question to simulation, analysis, and results.

  - week: 6
    topic: Intelligent Connected Vehicles
    description: An introduction to the history, definitions, and levels of intelligent connected vehicles, followed by discussion of their social value, development in China and abroad, and major technical and societal challenges.

  - week: 7
    topic: Reflection, Interaction, and Student Presentations
    description: Students present their interests, experiences, or personal reflections in a format of their choice, exchange ideas with classmates and instructors, and reflect on the course and their plans for university life.
---

<style>
/* Course page layout (identical block in all course pages) */
.post-description { display: none !important; }
.course > .course-info { display: none; }

.course-page {
  --cp-purple: #5b21b6;
  --cp-purple-dark: #351063;
  --cp-purple-soft: #f4efff;
  --cp-purple-line: #ded2f6;
  --cp-text: #202033;
  --cp-muted: #67677a;
  --cp-border: #e7e4ee;
  color: var(--cp-text);
}

/* Overview card: tags and key facts */
.course-hero {
  margin: 6px 0 36px;
  padding: 24px;
  border: 1px solid var(--cp-border);
  border-radius: 18px;
  background: linear-gradient(135deg, #fff 0%, #f7f3ff 100%);
}

.course-tags { display: flex; flex-wrap: wrap; gap: 8px; margin-bottom: 18px; }
.course-tags span {
  padding: 5px 11px;
  border: 1px solid var(--cp-purple-line);
  border-radius: 999px;
  background: #fff;
  color: var(--cp-purple);
  font-size: 12px;
  font-weight: 700;
}

.course-facts { display: grid; grid-template-columns: repeat(3, minmax(0, 1fr)); gap: 14px 20px; margin: 0; }
.course-facts > div { min-width: 0; }
.course-facts .wide { grid-column: span 2; }
.course-facts dt {
  margin-bottom: 3px;
  color: var(--cp-muted);
  font-size: 11.5px;
  font-weight: 700;
  letter-spacing: 0.06em;
  text-transform: uppercase;
}
.course-facts dd { margin: 0; color: var(--cp-text); font-size: 14.5px; font-weight: 600; line-height: 1.45; }

.course-photo { margin: 0; }
.course-photo img {
  display: block;
  width: 100%;
  height: auto;
  border-radius: 12px;
  box-shadow: 0 8px 24px rgba(33, 25, 48, 0.10);
}
.course-photo figcaption { margin-top: 8px; color: #858394; font-size: 12px; line-height: 1.45; text-align: center; }

/* Course Overview: text on the left, classroom photo on the right */
.course-overview { display: grid; grid-template-columns: minmax(0, 1.25fr) minmax(0, 1fr); gap: 28px; align-items: start; }
.course-overview-text > p:last-child { margin-bottom: 0; }

/* Sections */
.course-section { margin: 0 0 34px; }
.course-section h2 {
  margin: 0 0 14px;
  padding-bottom: 8px;
  border-bottom: 1px solid var(--cp-border);
  color: var(--cp-purple-dark);
  font-size: 23px;
  font-weight: 750;
}
.course-section p,
.course-section li { color: var(--cp-muted); font-size: 15.5px; line-height: 1.75; }
.course-section strong { color: var(--cp-text); }
.course-section a { font-weight: 600; }

/* Cards for course content, modules or class formats */
.course-cards { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 14px; margin-top: 14px; }
.course-card {
  padding: 16px 18px;
  border: 1px solid var(--cp-border);
  border-left: 4px solid var(--cp-purple);
  border-radius: 12px;
  background: #fff;
}
.course-card h3 { margin: 0 0 6px; color: var(--cp-purple-dark); font-size: 16px; font-weight: 700; }
.course-card p { margin: 0; font-size: 14.5px; line-height: 1.65; }

/* Learning objectives with check marks */
.course-checklist { margin: 0; padding-left: 0; list-style: none; }
.course-checklist li { position: relative; margin-bottom: 6px; padding-left: 26px; }
.course-checklist li::before { content: "✓"; position: absolute; top: 0; left: 0; color: var(--cp-purple); font-weight: 800; }

/* Prerequisites as chips */
.course-chips { display: flex; flex-wrap: wrap; gap: 8px; margin: 0; padding: 0; list-style: none; }
.course-section .course-chips li {
  padding: 6px 12px;
  border: 1px solid var(--cp-purple-line);
  border-radius: 999px;
  background: var(--cp-purple-soft);
  color: var(--cp-purple-dark);
  font-size: 13.5px;
  font-weight: 600;
  line-height: 1.4;
}

/* Schedule */
.course-note { font-size: 14px !important; }
.course-module { margin: 22px 0 8px; color: var(--cp-purple); font-size: 13px; font-weight: 800; letter-spacing: 0.06em; text-transform: uppercase; }
.course-schedule { margin: 0; padding: 0; overflow: hidden; border: 1px solid var(--cp-border); border-radius: 12px; background: #fff; list-style: none; }
.course-schedule li { display: grid; grid-template-columns: 76px minmax(0, 1fr); gap: 14px; padding: 13px 16px; border-bottom: 1px solid #efedf3; }
.course-schedule li:last-child { border-bottom: none; }
.schedule-no {
  align-self: start;
  padding: 4px 0;
  border-radius: 8px;
  background: var(--cp-purple-soft);
  color: var(--cp-purple-dark);
  font-size: 12.5px;
  font-weight: 700;
  text-align: center;
}
.schedule-topic { display: block; color: var(--cp-text); font-size: 15px; font-weight: 700; line-height: 1.5; }
.schedule-desc { display: block; margin-top: 3px; color: var(--cp-muted); font-size: 14px; line-height: 1.6; }
.schedule-optional {
  margin-left: 6px;
  padding: 1px 7px;
  border: 1px solid var(--cp-purple-line);
  border-radius: 999px;
  color: var(--cp-purple);
  font-size: 11px;
  font-weight: 700;
  vertical-align: middle;
}

@media (max-width: 900px) {
  .course-overview { grid-template-columns: 1fr; }
  .course-facts { grid-template-columns: repeat(2, minmax(0, 1fr)); }
}
@media (max-width: 640px) {
  .course-hero { padding: 18px; }
  .course-facts { grid-template-columns: 1fr; }
  .course-facts .wide { grid-column: auto; }
  .course-schedule li { grid-template-columns: 1fr; gap: 6px; }
  .schedule-no { justify-self: start; padding: 3px 10px; }
}
</style>

<div class="course-page">

<section class="course-hero">
<div class="course-hero-text">
<dl class="course-facts">
<div><dt>Instructors</dt><dd>{{ page.instructor }}</dd></div>
<div><dt>Term</dt><dd>{{ page.term }}</dd></div>
<div><dt>Course No.</dt><dd>{{ page.course_id }}</dd></div>
<div><dt>Credits &amp; Hours</dt><dd>1 credit · 16 hours · {{ page.syllabus.size }} sessions</dd></div>
<div class="wide"><dt>Format</dt><dd>Small-class seminars combining classroom teaching, experiential learning, peer sharing, and student presentations</dd></div>
</dl>
</div>
</section>

<section class="course-section">
<h2>Course Overview</h2>
<p>This one-credit course consists of 16 hours delivered across seven sessions. It is conducted in a small-class format and combines classroom instruction with experiential learning, peer sharing, interactive discussion, feedback, and student presentations. The course is organized into three connected modules:</p>
<div class="course-cards">
<div class="course-card"><h3>Me and My University</h3><p>Students explore the characteristics of university study and life, learn about Tsinghua's history, traditions, and culture, and build supportive relationships with teachers and peers.</p></div>
<div class="course-card"><h3>Me and My Major</h3><p>Using intelligent vehicles as an accessible interdisciplinary case, students examine technological development, experience research and industry practice, and learn the basic process of scientific inquiry.</p></div>
<div class="course-card"><h3>Me and Myself</h3><p>Students reflect on their interests, strengths, values, and goals, strengthen their resilience and emotional adjustment, and consider the responsibilities that accompany scientific and technological development.</p></div>
</div>
</section>

<section class="course-section">
<h2>Prerequisites</h2>
<ul class="course-chips">
<li>No prerequisites</li>
<li>Primarily intended for first-year undergraduate students</li>
</ul>
</section>

<section class="course-section">
<h2>Course Schedule</h2>
<p class="course-note">The course includes classroom teaching, peer sharing, a campus sports visit and fencing experience, research case studies, small-group discussions, and student presentations. Exact guest speakers and activity arrangements may vary by year. Current course announcements take precedence.</p>
<ul class="course-schedule">
{%- for item in page.syllabus %}
<li><span class="schedule-no">Week {{ item.week }}</span><div><span class="schedule-topic">{{ item.topic | escape }}</span><span class="schedule-desc">{{ item.description | escape }}</span></div></li>
{%- endfor %}
</ul>
</section>

</div>

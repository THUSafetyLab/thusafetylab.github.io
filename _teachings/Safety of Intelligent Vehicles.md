---
layout: course
title: Safety of Intelligent Vehicles
description: "This undergraduate general education elective traces the development of automotive safety from passive crash protection to intelligent safety systems. It introduces the scientific foundations, research methods, and emerging challenges of intelligent vehicle safety and future mobility."
instructor: Bingbing Nie, Hong Wang, Shaobing Xu
year: 2026
term: Fall
course_id: "00150222"
# Weekly plan rendered by this page (named "syllabus" so the default layout does not add its own schedule table)
syllabus:
  - week: 1
    topic: Introduction
    description: An introduction to the course, road traffic, and intelligent vehicles; the scope of intelligent vehicle safety; and key research questions, methods, trends, and case studies in automotive safety.

  - week: 2
    topic: Overview of Automotive Safety
    description: An introduction to active and passive safety through practical examples of vehicle safety challenges.

  - week: 3
    topic: Occupant Restraint Systems
    description: Fundamentals of occupant restraint systems, simplified analysis of crash dynamics, and principles of restraint system design.

  - week: 4
    topic: Research Methods in Automotive Safety
    description: Experimental and numerical methods, human surrogates for safety research, and the role of active occupant responses in vehicle safety.

  - week: 5
    topic: "Field Visit: Intelligent Mobility in Practice"
    description: An off-campus field study, tentatively planned in Yizhuang with Luobo Chuxing, Baidu, or Qingzhou Chuxing.

  - week: 6
    topic: Road User Behavior
    description: An introduction to different road user groups and intelligent vehicle cockpits, with a discussion of travel preferences.

  - week: 7
    topic: Electric Vehicle Safety
    description: A guest lecture on electric vehicle technologies and key safety concerns, including battery crash safety and protective measures.

  - week: 8
    topic: Thermal Runaway Protection for Electric Vehicles
    description: Case studies of electric vehicle incidents, thermal runaway protection for traction batteries, and prediction of safety risks following battery damage.

  - week: 9
    topic: Operational Safety of Intelligent Vehicles
    description: Foundations of operational safety, hazard identification, quantitative risk assessment, and decision-making and control for safe vehicle operation.

  - week: 10
    topic: Intelligent Vehicle System Safety
    description: Fundamentals of intelligent vehicles, functional safety, safety of the intended functionality, information security, and the role of artificial intelligence in intelligent vehicle systems.

  - week: 11
    topic: Automotive Safety Testing and Evaluation
    description: Test scenarios and tools, safety regulations, consumer safety assessment methods, and the implications of changes in the automotive industry for safety testing.

  - week: 12
    topic: Immersive Laboratory Session
    description: Immersive interaction in hazardous traffic scenarios.

  - week: 13
    topic: Automotive Safety and Future Mobility
    description: A seminar on safety in connected and automated mobility, cooperation between vehicles and road infrastructure, advances in intelligent protection, and the role of intelligent vehicles in future transport systems and cities.

  - week: 14
    topic: Automotive Safety and Future Society
    description: A seminar examining whether road traffic crashes can ever be eliminated and the ethical dilemmas in autonomous vehicle decision-making.

  - week: 15
    topic: Course Project Presentations
    description: Group presentations and instructor feedback on the course projects.
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
/* A card alone in its row spans the full width of the card grid */
.course-card.full-row { grid-column: 1 / -1; }
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
<div class="course-tags"><span>General Education in Science</span><span>General Education Course Excellence Initiative</span><span>Demonstration Course in Moral and Values Education</span></div>
<dl class="course-facts">
<div><dt>Instructors</dt><dd>{{ page.instructor }}</dd></div>
<div><dt>Term</dt><dd>{{ page.term }}</dd></div>
<div><dt>Course No.</dt><dd>{{ page.course_id }}</dd></div>
<div><dt>Duration</dt><dd>{{ page.syllabus.size }} weeks</dd></div>
<div class="wide"><dt>Format</dt><dd>Lectures, a field visit, laboratory activities, seminars, and a group project</dd></div>
</dl>
</div>
</section>

<section class="course-section">
<h2>Course Overview</h2>
<div class="course-overview">
<div class="course-overview-text">
<p>This course introduces the scientific foundations, current research, and future directions of intelligent vehicle safety. Students explore how safety technologies protect lives and shape future mobility, while building a foundation for understanding transportation safety. The course also examines the contributions of science, technology, and industry to society and encourages students to develop the confidence and skills to innovate responsibly. Course content includes:</p>
<div class="course-cards">
<div class="course-card"><h3>Foundations</h3><p>An overview of automotive safety and occupant restraint systems</p></div>
<div class="course-card"><h3>Future Trends</h3><p>Intelligent vehicles, future mobility, and transportation safety</p></div>
<div class="course-card full-row"><h3>Current Research</h3><p>Our team's research on intelligent vehicle safety and electric vehicle battery thermal runaway prevention, illustrated through incident case studies and recent findings</p></div>
</div>
</div>
<figure class="course-photo">
<img src="{{ '/assets/img/courses/SIV-1.jpg' | relative_url }}" alt="Classroom photo from Safety of Intelligent Vehicles" loading="lazy">
<figcaption>Classroom photo</figcaption>
</figure>
</div>
</section>

<section class="course-section">
<h2>Prerequisites</h2>
<ul class="course-chips">
<li>No formal prerequisites</li>
<li>Recommended for students in their second year or later</li>
</ul>
</section>

<section class="course-section">
<h2>Course Schedule</h2>
<ul class="course-schedule">
{%- for item in page.syllabus %}
<li><span class="schedule-no">Week {{ item.week }}</span><div><span class="schedule-topic">{{ item.topic | escape }}</span><span class="schedule-desc">{{ item.description | escape }}</span></div></li>
{%- endfor %}
</ul>
</section>

</div>

---
layout: course
title: Safety of Intelligent Vehicles
description: "This undergraduate general education elective examines the evolution of automotive safety from passive protection to intelligent safety. It introduces fundamental theories, research methods, current research topics, and future directions in intelligent vehicle and mobility safety."
instructor: Bingbing Nie, Hong Wang, Shaobing Xu
year: 2026
term: Fall
course_id: "00150222"
# Weekly plan rendered by this page (named "syllabus" so the default layout does not add its own schedule table)
syllabus:
  - week: 1
    topic: Introduction
    description: Course information; road traffic and intelligent vehicles; the meanings of intelligent vehicle safety; and the research subjects, methods, trends, and classic cases of automotive safety.

  - week: 2
    topic: Overview of Automotive Safety
    description: An introduction to active and passive safety through specific vehicle safety issues.

  - week: 3
    topic: Occupant Restraint Systems
    description: Basic concepts of automotive occupant restraint systems, simplified analysis of the collision process, and restraint system design principles.

  - week: 4
    topic: Research Methods in Automotive Safety
    description: Experimental methods, numerical methods, human surrogates, and a discussion of active occupant response.

  - week: 5
    topic: "Field Study: Mobility on the Production Line"
    description: An off-campus field study, tentatively planned in Yizhuang with Luobo Chuxing, Baidu, or Qingzhou Chuxing.

  - week: 6
    topic: Behavioral Characteristics of Traffic Participants
    description: An introduction to diverse road users and intelligent cockpits, with a discussion of travel preferences.

  - week: 7
    topic: Electric Vehicle Safety
    description: A guest lecture on the characteristics and safety categories of electric vehicles, as well as battery crash safety and protection.

  - week: 8
    topic: Thermal Runaway Protection for Electric Vehicles
    description: A case-based discussion covering electric vehicles and their accident characteristics, thermal runaway protection for traction batteries, and risk prediction associated with battery damage.

  - week: 9
    topic: Operational Safety of Intelligent Vehicles
    description: Operational safety theory, risk identification and quantitative assessment, and safety decision-making and control.

  - week: 10
    topic: Intelligent Vehicle System Safety
    description: Fundamental concepts of intelligent vehicles, functional safety, safety of the intended functionality, information security, and a discussion of the relationship between artificial intelligence and intelligent vehicles.

  - week: 11
    topic: Automotive Safety Testing and Evaluation
    description: Test scenarios and tools, regulations and consumer-oriented assessment methods, and a discussion of safety testing in the context of ongoing transformations in the automotive industry.

  - week: 12
    topic: Experiential Laboratory Class
    description: Immersive interaction in hazardous traffic scenarios.

  - week: 13
    topic: Automotive Safety and Future Mobility
    description: A seminar exploring future safety under intelligent connectivity and vehicle-road coordination, the development of intelligent protection, and the relationship among intelligent vehicles, smart transportation, and future cities.

  - week: 14
    topic: Automotive Safety and Future Society
    description: A seminar examining whether road traffic crashes will always exist and the ethical dilemmas underlying autonomous vehicle decision-making.

  - week: 15
    topic: Course Project Presentation
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
<div class="course-tags"><span>Science General Education</span><span>High-Quality General Education Course Development Initiative</span><span>Model Course in Ideological and Political Education</span></div>
<dl class="course-facts">
<div><dt>Instructors</dt><dd>{{ page.instructor }}</dd></div>
<div><dt>Term</dt><dd>{{ page.term }}</dd></div>
<div><dt>Course No.</dt><dd>{{ page.course_id }}</dd></div>
<div><dt>Duration</dt><dd>{{ page.syllabus.size }} weeks</dd></div>
<div class="wide"><dt>Format</dt><dd>Lectures, field study, laboratory experience, seminars, and a group course project</dd></div>
</dl>
</div>
</section>

<section class="course-section">
<h2>Course Overview</h2>
<div class="course-overview">
<div class="course-overview-text">
<p>This course introduces the fundamental theories, research topics, and future trends of intelligent vehicle safety. Through this course, students are expected to understand how vehicle safety technologies affect human life, build a knowledge framework for future transportation safety, appreciate the value of science, technology, and industry, and develop the courage and ability to create and take responsibility. Course content includes:</p>
<div class="course-cards">
<div class="course-card"><h3>Fundamental Theories</h3><p>An overview of automotive safety and occupant restraint systems</p></div>
<div class="course-card"><h3>Future Trends</h3><p>Intelligent vehicles, future mobility, and transportation safety</p></div>
<div class="course-card full-row"><h3>Research Hotspots</h3><p>Explore our work on intelligent vehicle safety and EV thermal runaway prevention, featuring typical accident case analyses and an overview of our team's latest research</p></div>
</div>
</div>
<figure class="course-photo">
<img src="{{ '/assets/img/courses/SIV-1.jpg' | relative_url }}" alt="Classroom photo from Safety of Intelligent Vehicle" loading="lazy">
<figcaption>Classroom photo</figcaption>
</figure>
</div>
</section>

<section class="course-section">
<h2>Prerequisites</h2>
<ul class="course-chips">
<li>No formal prerequisites</li>
<li>Sophomore standing or above recommended</li>
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

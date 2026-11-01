---
layout: "course"
title: "Fundamentals of Automotive Crash Safety"
description: "This course introduces the scientific foundations and advanced technologies of automotive crash safety and impact protection. Topics include crash mechanics, injury biomechanics, occupant restraint systems, pedestrian protection, the impact behavior of vehicle structures and materials, adaptive protection for autonomous vehicles, and battery crash safety."
instructor: Qing Zhou, Bingbing Nie, Yong Xia
year: 2026
term: "Fall"
course_id: "80150193"
class_hours: 48
credits: 3
language: "Separate Chinese- and English-language sections"
# Lecture plan rendered by this page (named "syllabus" so the default layout does not add its own schedule table)
syllabus:
  - lecture: "1"
    module: "Crash Mechanics and Safety Assessment"
    topic: "Fundamentals of Vehicle Safety"
    description: "An introduction to vehicle safety; crash sequences and collision types; components and structures involved in crash protection; crash safety design requirements and processes; emerging safety challenges for electric and autonomous vehicles."

  - lecture: "2"
    module: "Crash Mechanics and Safety Assessment"
    topic: "Vehicle Response and Occupant Ride-Down in Frontal Crashes"
    description: "Vehicle crash pulses and their characterization; vehicle and occupant kinematics; occupant ride-down; design strategies for coordinating vehicle and occupant responses; factors affecting crash severity."

  - lecture: "3"
    module: "Crash Mechanics and Safety Assessment"
    topic: "Injury Biomechanics in Vehicle Crashes"
    description: "Foundations, applications, and methods of injury biomechanics; injury mechanisms and characterization; human mechanical response and injury tolerance under impact loading; examples organized by body region."

  - lecture: "4"
    module: "Crash Mechanics and Safety Assessment"
    topic: "Vehicle Crash Safety Assessment"
    description: "Part 1: Crash test methods, facilities, equipment, and preparation; test types and applicable regulations; sled testing. Part 2: The purpose and development of crash test dummies, including the Hybrid III frontal impact dummy and other dummy designs; improvements to dummies and their evaluation through simulation."

  - lecture: "5"
    module: "Occupant Restraint Systems"
    topic: "Seat Belts and Airbags"
    description: "Design and components of seat belts and airbags; principles of occupant protection; risks associated with airbag deployment; advanced seat belt and airbag technologies."

  - lecture: "5"
    optional: true
    module: "Occupant Restraint Systems"
    topic: "Crash Sensing"
    description: "Crash data, analysis, and signals; crash sensing criteria and algorithms; procedures for determining deployment thresholds; key considerations in crash sensing."

  - lecture: "6"
    module: "Occupant Restraint Systems"
    topic: "Vehicle Seats and Occupant Crash Protection"
    description: "Functions and structure of vehicle seats; whiplash injury and prevention; trade-offs between stiff and yielding seat designs; sliding seats and seat-mounted restraints."

  - lecture: "7"
    optional: true
    module: "Occupant Restraint Systems"
    topic: "Child Occupant Protection"
    description: "Child occupant safety in road traffic crashes; child restraint systems and assessment of their crash protection performance."

  - lecture: "8"
    module: "Occupant Restraint Systems"
    topic: "Adaptive Occupant Protection for Autonomous Vehicles"
    description: "Challenges in occupant crash protection; adaptive restraint systems; body size variation in Asian populations and its implications for protection; intelligent and personalized crash protection; unavoidable collisions involving autonomous vehicles; the European OSCCAR project."

  - lecture: "9"
    module: "Impact Interactions between the Human Body and Vehicle Structures"
    topic: "Side Impact Protection"
    description: "Side impact crashes and safety assessment; analysis of side impact dynamics and pelvis pusher design; interactions between the vehicle side structure and the occupant; increasingly stringent requirements for side impact protection."

  - lecture: "10"
    module: "Impact Interactions between the Human Body and Vehicle Structures"
    topic: "Occupant Head Impact Protection"
    description: "Occupant head impact risks; mechanical models and their underlying principles; application of research findings to the design of protective measures."

  - lecture: "11"
    module: "Impact Interactions between the Human Body and Vehicle Structures"
    topic: "Pedestrian Impact Protection"
    description: "Characteristics of vehicle–pedestrian collisions and resulting injuries; methods for assessing pedestrian protection; vehicle design to reduce pedestrian injuries; emerging research and future directions in pedestrian safety."

  - lecture: "12"
    module: "Vehicle Structures and Materials under Impact"
    topic: "Impact Mechanics of Thin-Walled Tubes"
    description: "Thin-walled vehicle body structures and their functions; the plastic hinge concept; design of thin-walled tubes for axial crushing; bending of box-section tubes."

  - lecture: "13"
    module: "Vehicle Structures and Materials under Impact"
    topic: "Material Failure under Impact Loading (Overview)"
    description: "Material characterization and modeling requirements for vehicle crash simulation; challenges in testing and modeling fracture under impact loading; emerging data-driven methods."

  - lecture: "14"
    module: "Vehicle Structures and Materials under Impact"
    topic: "Battery Crash Safety"
    description: "Battery safety in vehicle crashes; cell damage under crush and impact loading; cell failure mechanisms under mechanical abuse; battery and electric vehicle modeling for crash safety assessment."

  - lecture: "15"
    module: "Vehicle Structures and Materials under Impact"
    topic: "Small, Lightweight Vehicles and Crash Compatibility"
    description: "The relationship between vehicle size and crash safety; factors affecting crash compatibility; methods for assessing compatibility; balancing weight reduction with crash protection."
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
<div class="course-tags"><span>National First-Class Course</span><span>Tsinghua University Course of Excellence</span></div>
<dl class="course-facts">
<div><dt>Instructors</dt><dd>{{ page.instructor }}</dd></div>
<div><dt>Term</dt><dd>{{ page.term }}</dd></div>
<div><dt>Course No.</dt><dd>{{ page.course_id }}</dd></div>
<div><dt>Credits &amp; Hours</dt><dd>{{ page.credits }} credits · {{ page.class_hours }} class hours</dd></div>
<div><dt>Language</dt><dd>{{ page.language }}</dd></div>
<div><dt>Open to</dt><dd>Undergraduate and graduate students, including international students</dd></div>
</dl>
</div>
</section>

<section class="course-section">
<h2>Course Overview</h2>
<div class="course-overview">
<div class="course-overview-text">
<p>Fundamentals of Automotive Crash Safety (FACS) introduces the scientific principles and engineering methods used to understand crashes and design effective protection. The course welcomes undergraduate and graduate students, including international students.</p>
<p>Students study vehicle and occupant responses in collisions, injury mechanisms, crash testing and assessment, occupant restraints, pedestrian protection, lightweight vehicle design, and the impact behavior of vehicle structures and materials. The course also addresses adaptive protection for autonomous vehicles and battery failure mechanisms, prediction models, and crash protection for electric vehicles.</p>
</div>
<figure class="course-photo">
<img src="{{ '/assets/img/courses/FACS-1.jpg' | relative_url }}" alt="Classroom photo from Fundamentals of Automotive Crash Safety" loading="lazy">
<figcaption>Classroom photo</figcaption>
</figure>
</div>
</section>

<section class="course-section">
<h2>Learning Objectives</h2>
<p>By the end of the course, students will be able to:</p>
<ul class="course-checklist">
<li>Explain the role of vehicle safety in product development and design, including the evolution and limitations of safety technologies.</li>
<li>Explain how lightweighting and vehicle packaging requirements constrain crash protection design.</li>
<li>Explain human injury mechanisms under impact loads and the principles of occupant restraint systems.</li>
<li>Describe safety risks and protection strategies for autonomous vehicles.</li>
<li>Describe methods for establishing battery safety envelopes and failure tolerance under impact loading.</li>
<li>Identify innovative battery pack designs that improve electric vehicle crash protection.</li>
</ul>
</section>

<section class="course-section">
<h2>Prerequisites</h2>
<ul class="course-chips">
<li>Engineering mechanics</li>
<li>Engineering mathematics</li>
<li>Numerical methods</li>
</ul>
</section>

<section class="course-section">
<h2>Teaching Format</h2>
<p>The course offers separate Chinese- and English-language sections with the same course number and teaching team. Students may attend either section.</p>
<div class="course-cards">
<div class="course-card">
<h3>Chinese-Language Section</h3>
<p>Lectures and discussions are conducted in Chinese, with slides and supplementary materials in English. Sessions are also streamed live via Rain Classroom for students who wish to audit the course online without enrolling.</p>
</div>
<div class="course-card">
<h3>English-Language Section</h3>
<p>Students study <a href="https://www.xuetangx.com/course/thu08021000357intl/14314101" target="_blank" rel="noopener">prerecorded lectures on XuetangX</a> at their own pace and attend four in-person sessions during the semester. These sessions may include reviews of key topics, questions and answers, and, where appropriate, student presentations with feedback and discussion. All sessions are conducted in English.</p>
</div>
</div>
</section>

<section class="course-section">
<h2>Course Schedule</h2>
<p class="course-note">The syllabus is organized into four modules. Lecture numbers indicate the sequence of topics and do not correspond to specific teaching weeks. Crash Sensing (an extension of Lecture 5) and Lecture 7 are optional.</p>
{%- assign modules = page.syllabus | group_by: "module" -%}
{%- for module in modules %}
<div class="course-module">Module {{ forloop.index }} · {{ module.name }}</div>
<ul class="course-schedule">
{%- for item in module.items %}
<li><span class="schedule-no">Lecture {{ item.lecture }}</span><div><span class="schedule-topic">{{ item.topic | escape }}{% if item.optional %}<span class="schedule-optional">Optional</span>{% endif %}</span><span class="schedule-desc">{{ item.description | escape }}</span></div></li>
{%- endfor %}
</ul>
{%- endfor %}
</section>

</div>

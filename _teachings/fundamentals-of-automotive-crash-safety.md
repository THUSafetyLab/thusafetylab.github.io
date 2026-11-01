---
layout: "course"
title: "Fundamentals of Automotive Crash Safety"
description: "This course introduces the fundamentals and state-of-the-art technologies of automotive crash safety and impact protection, including crash mechanics, injury biomechanics, occupant restraint systems, pedestrian protection, vehicle structures and materials, adaptive protection for autonomous vehicles, and battery crash safety."
instructor: Qing Zhou, Bingbing Nie, Yong Xia
year: 2026
term: "Fall"
course_id: "80150193"
class_hours: 48
credits: 3
language: "Chinese and English (parallel classes)"
# Lecture plan rendered by this page (named "syllabus" so the default layout does not add its own schedule table)
syllabus:
  - lecture: "1"
    module: "Crash Mechanics and Safety Assessment"
    topic: "Fundamentals of Vehicle Safety"
    description: "Background of vehicle safety; Vehicle crash process and types of collisions; Components and structures relevant to crash safety design; Crash design requirements and process; New safety issues for electric vehicles and autonomous vehicles."

  - lecture: "2"
    module: "Crash Mechanics and Safety Assessment"
    topic: "Vehicle Response and Occupant Ride-Down under Frontal Collision"
    description: "Vehicle crash pulse; Vehicle kinematics and occupant kinematics; Occupant ride-down; Crash pulse characterization; Design for harmonizing responses of vehicle and occupant; Influencing factors of crash severity."

  - lecture: "3"
    module: "Crash Mechanics and Safety Assessment"
    topic: "Human Body Injuries in Vehicle Collisions"
    description: "Injury biomechanics – background, applications & methods; Injury mechanism, injury characterization, mechanical response & injury tolerance of human body under impact loading; Impact biomechanics exampled with body regions."

  - lecture: "4"
    module: "Crash Mechanics and Safety Assessment"
    topic: "Vehicle Crash Safety Assessment"
    description: "Part 1: Vehicle Crash Test Methods; Vehicle crash test laboratory & devices; Preparation of vehicle crash test; Types of vehicle crash tests and regulations; Sled test; Part 2: Crash Test Dummy; Purpose of crash test dummies; Hybrid III frontal impact dummy; Other dummies; Historical development of crash dummies; Crash dummy improvement and virtual assessment."

  - lecture: "5"
    module: "Occupant Restraint Systems"
    topic: "Seatbelt and Airbag"
    description: "Structures and components of seatbelt and airbag; Protection functions of seatbelt and airbag; Risks and hazards of airbag; Advanced seatbelts and airbags."

  - lecture: "5"
    optional: true
    module: "Occupant Restraint Systems"
    topic: "Crash Sensing"
    description: "Crash Data, Crash Analyses, Crash Signals; Crash Sensing Criteria and Algorithms; Procedure for Determining Trigger Threshold; Key Things of Crash Sensing."

  - lecture: "6"
    module: "Occupant Restraint Systems"
    topic: "Seat as Occupant Impact Protection Device"
    description: "Functions and structure of vehicle seat; Whiplash injury and protection; The debate between stiff and yielding seats; Sliding seat and seat mounted restraints."

  - lecture: "7"
    optional: true
    module: "Occupant Restraint Systems"
    topic: "Protection of Child Passengers"
    description: "Child safety issues in traffic accidents; Child Restraint System and crash safety assessment."

  - lecture: "8"
    module: "Occupant Restraint Systems"
    topic: "Adaptive Protection for Autonomous Vehicle"
    description: "Challenges in occupant crash protection; Adaptive occupant restraint; Crash protection concerning Asian body sizes; Smart and individualized crash protection; Unavoidable collisions to autonomous vehicles; The Europe OSCCAR Project."

  - lecture: "9"
    module: "Impact Interactions between Human Body and Vehicle Structures"
    topic: "Side Impact Protection"
    description: "Side impact accident and crash safety assessment; Analysis of side impact process; Analysis of pelvis pusher design; Interaction between side structure and occupant; Increasingly strict side impact protection requirement."

  - lecture: "10"
    module: "Impact Interactions between Human Body and Vehicle Structures"
    topic: "Occupant Head Impact Protection"
    description: "Background of occupant head impact problem; Mechanics model and rationales; How findings guide countermeasure design."

  - lecture: "11"
    module: "Impact Interactions between Human Body and Vehicle Structures"
    topic: "Pedestrian Impact Protection"
    description: "Characteristics of car-to-pedestrian collision accidents; Injuries in car-to-pedestrian collisions; Assessment methods for pedestrian impact safety; Vehicle design for pedestrian impact protection; Emerging subjects and future pedestrian protection."

  - lecture: "12"
    module: "Vehicle Structures and Materials under Impact"
    topic: "Impact Mechanics of Thin-Walled Tubes"
    description: "Thin-walled structural members of vehicle body and functions; Concept of plastic hinge; Design of axial crush of thin-walled tube; Bending of box tube."

  - lecture: "13"
    module: "Vehicle Structures and Materials under Impact"
    topic: "Impact Failures of Vehicle Materials (a short version)"
    description: "Needs of material characterization and modeling for vehicle crash simulations; Challenges in testing and modeling material fracture behaviors under impact loading; Future development: data-driven method."

  - lecture: "14"
    module: "Vehicle Structures and Materials under Impact"
    topic: "Impact Safety of Battery"
    description: "Battery safety in vehicle collision accidents; Damage of battery cell under crush and impact; Failure mechanisms of battery cell under mechanical abuse; Modeling of battery and electric vehicle for crash safety."

  - lecture: "15"
    module: "Vehicle Structures and Materials under Impact"
    topic: "Small Lightweight Vehicle and Crash Compatibility"
    description: "Problem in reality: vehicle size and safety; Influencing factors of crash compatibility; Assessment of vehicle compatibility; Lightweight and safety."
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
<div class="course-tags"><span>National First-Class Course</span><span>THU Excellent Course</span></div>
<dl class="course-facts">
<div><dt>Instructors</dt><dd>{{ page.instructor }}</dd></div>
<div><dt>Term</dt><dd>{{ page.term }}</dd></div>
<div><dt>Course No.</dt><dd>{{ page.course_id }}</dd></div>
<div><dt>Credits &amp; Hours</dt><dd>{{ page.credits }} credits · {{ page.class_hours }} class hours</dd></div>
<div><dt>Language</dt><dd>{{ page.language }}</dd></div>
<div><dt>Open to</dt><dd>Undergraduate, graduate, and international students</dd></div>
</dl>
</div>
</section>

<section class="course-section">
<h2>Course Overview</h2>
<div class="course-overview">
<div class="course-overview-text">
<p>Fundamentals of Automotive Crash Safety (FACS) covers fundamental knowledge, theory, and current technologies in vehicle crash safety and impact protection. It is open to graduate students, international students, and undergraduate students.</p>
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
<li>Understand crash protection design constraints arising from lightweighting and packaging requirements.</li>
<li>Explain human injury mechanisms under impact loads and the principles of occupant restraint systems.</li>
<li>Understand safety risks and protection strategies for autonomous vehicles.</li>
<li>Understand methods for establishing battery safety envelopes and failure tolerance under impact loads.</li>
<li>Recognize innovative battery pack designs for electric vehicle crash protection.</li>
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
<p>The Chinese and English classes share the same course number and teaching team. Students may attend either language class.</p>
<div class="course-cards">
<div class="course-card">
<h3>Chinese Class</h3>
<p>Lectures and discussions are in Chinese; slides and supplementary materials are in English. Classes are also broadcast live via Rain Classroom for students who wish to attend online without registering.</p>
</div>
<div class="course-card">
<h3>English Class</h3>
<p>Self-paced study of <a href="https://www.xuetangx.com/course/thu08021000357intl/14314101" target="_blank" rel="noopener">prerecorded lectures on XuetangX</a>, combined with four in-person sessions during the semester. These sessions may include focused reviews, questions and answers, and, where appropriate, student presentations followed by feedback and discussion. All sessions are conducted in English.</p>
</div>
</div>
</section>

<section class="course-section">
<h2>Course Schedule</h2>
<p class="course-note">The lecture sequence is organized into four modules. Lecture numbers identify course content rather than confirmed teaching weeks. Crash sensing (an extension of Lecture 5) and Lecture 7 are optional.</p>
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

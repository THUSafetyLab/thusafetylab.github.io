---
layout: page
permalink: /people/
title: Team
description:
nav: true
nav_order: 5
---

<style>
/* ============================================
   TEAM PAGE
   Faculty Profiles
   ============================================ */

.team-faculty {
  width: 100%;
  margin: 0 auto;
}

/* Three faculty members in one row */

.team-faculty .faculty-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 28px;
  margin: 20px 0 45px;
  align-items: start;
}

/* Individual faculty member */

.team-faculty .faculty-card {
  min-width: 0;
  text-align: center;
}

/* Faculty portrait */

.team-faculty .faculty-photo {
  display: block;
  width: 100%;
  max-width: 175px;
  height: 215px;
  margin: 0 auto 16px;

  object-fit: cover;
  object-position: center top;

  border-radius: 6px;
}

/* Faculty name */

.team-faculty .faculty-name {
  margin: 0 0 8px;

  font-size: 1.1rem;
  font-weight: 650;
  line-height: 1.4;

  color: var(--global-text-color, #222);
}

/* Academic position */

.team-faculty .faculty-role {
  min-height: 0;
  margin: 0 0 10px;

  font-size: 0.9rem;
  line-height: 1.5;

  color: var(--global-text-color-light, #666);
}

/* Homepage and email */

.team-faculty .faculty-links {
  font-size: 0.86rem;
  line-height: 1.8;
  overflow-wrap: anywhere;
}

.team-faculty .faculty-links a {
  display: block;
  text-decoration: none;
}

.team-faculty .faculty-email {
  display: block;
  color: var(--global-text-color-light, #666);
}


/* ============================================
   Shared Faculty Introduction
   ============================================ */

.team-faculty .faculty-overview {
  margin-top: 42px;
  padding-top: 30px;

  border-top: 1px solid
    var(--global-divider-color, #ddd);
}

/* Section headings: "Faculty members ..." and "About the Faculty Team" */
.team-faculty .faculty-heading,
.team-faculty .faculty-overview h2 {
  margin: 0 0 20px;

  font-size: 1.6rem;
  font-weight: 650;

  color: var(--global-text-color, #222);
}

.team-faculty .faculty-overview p {
  margin: 0 0 20px;

  font-size: 0.98rem;
  line-height: 1.85;
  text-align: justify;
}

.team-faculty .faculty-overview ul {
  margin: 0;
  padding-left: 24px;
}

.team-faculty .faculty-overview li {
  margin-bottom: 18px;

  font-size: 0.96rem;
  line-height: 1.85;

  text-align: justify;
}


/* ============================================
   Responsive Layout
   ============================================ */

@media (max-width: 650px) {

  .team-faculty .faculty-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 30px 18px;
  }

  .team-faculty .faculty-photo {
    max-width: 155px;
    height: 195px;
  }

}

@media (max-width: 420px) {

  .team-faculty .faculty-grid {
    grid-template-columns: 1fr;
    gap: 30px;
  }

  .team-faculty .faculty-photo {
    max-width: 175px;
    height: 215px;
  }

  .team-faculty .faculty-role {
    min-height: 0;
  }

  .team-faculty .faculty-overview p,
  .team-faculty .faculty-overview li {
    text-align: left;
  }

}
</style>


<div class="team-faculty">

  <!-- ==========================================
       Faculty Members
       ========================================== -->

  <h2 class="faculty-heading">Faculty Members of the Intelligent Safety Lab</h2>

  <div class="faculty-grid">

    <!-- Zhou Qing -->

    <div class="faculty-card">

      <img
        class="faculty-photo"
        src="{{ '/assets/img/professor_zhou.jpg' | relative_url }}"
        alt="Zhou Qing"
      >

      <h3 class="faculty-name">
        Zhou Qing
      </h3>

      <p class="faculty-role">
        Professor
      </p>

      <div class="faculty-links">

        <a
          href="https://www.svm.tsinghua.edu.cn/essay/75/1831.html"
          target="_blank"
          rel="noopener noreferrer"
        >
          Personal homepage
        </a>

        <span class="faculty-email">
          zhouqing[at]tsinghua.edu.cn
        </span>

      </div>

    </div>


    <!-- Xia Yong -->

    <div class="faculty-card">

      <img
        class="faculty-photo"
        src="{{ '/assets/img/professor_xia.jpg' | relative_url }}"
        alt="Xia Yong"
      >

      <h3 class="faculty-name">
        Xia Yong
      </h3>

      <p class="faculty-role">
        Associate Research Fellow
      </p>

      <div class="faculty-links">

        <a
          href="https://www.svm.tsinghua.edu.cn/essay/75/1827.html"
          target="_blank"
          rel="noopener noreferrer"
        >
          Personal homepage
        </a>

        <span class="faculty-email">
          xiayong[at]tsinghua.edu.cn
        </span>

      </div>

    </div>


    <!-- Nie Bingbing -->

    <div class="faculty-card">

      <img
        class="faculty-photo"
        src="{{ '/assets/img/professor_nie.jpg' | relative_url }}"
        alt="Nie Bingbing"
      >

      <h3 class="faculty-name">
        Nie Bingbing
      </h3>

      <p class="faculty-role">
        Associate Professor
      </p>

      <div class="faculty-links">

        <a
          href="https://www.svm.tsinghua.edu.cn/essay/75/1819.html"
          target="_blank"
          rel="noopener noreferrer"
        >
          Personal homepage
        </a>

        <span class="faculty-email">
          nbb[at]tsinghua.edu.cn
        </span>

      </div>

    </div>

  </div>


  <!-- ==========================================
       Shared Faculty Introduction
       ========================================== -->

  <section class="faculty-overview">

    <h2>About the Faculty Team</h2>

    <p>
      The Automotive Safety and Lightweighting Research Team
      is led by
      <strong>Professor Zhou Qing</strong>,
      with
      <strong>Associate Research Fellow Xia Yong</strong>
      and
      <strong>Associate Professor Nie Bingbing</strong>
      sharing responsibility for research and student mentoring.
      Together, they bring extensive experience in research
      and education and have contributed to advances in
      automotive safety in China and internationally.
    </p>

    <ul>

      <li>
        <strong>Research achievements.</strong>
        In recent years, the team has led more than 20
        research projects supported by the National Natural
        Science Foundation of China, national key research
        and development programs, and international
        collaborative initiatives. The team has published
        more than 100 research papers and been granted
        nearly 100 invention patents in China and
        the United States. Long-term collaborations with
        leading automotive companies in China and abroad
        help translate research into industrial applications.
        Some of the team's core technologies have achieved
        internationally leading performance and have been
        adopted in mass production.
      </li>

      <li>
        <strong>Academic leadership and service.</strong>
        Faculty members have served in leadership and
        advisory roles in international professional
        organizations and at Tsinghua University. These
        include service on the Council of the
        International Research Council on Biomechanics of
        Injury (IRCOBI), where a team member became the first
        Chinese scholar to serve; leadership of SAE International's
        Pedestrian Safety Division; membership of Tsinghua
        University's Academic Committee; and chairing the
        School Academic Committee.
        They have also served as associate editors or
        editorial board members of internationally
        recognized journals, including
        <em>International Journal of Impact Engineering</em>,
        <em>Accident Analysis &amp; Prevention</em>,
        <em>Traffic Injury Prevention</em>, and
        <em>SAE International Journals</em>.
      </li>

      <li>
        <strong>Education and mentoring.</strong>
        Faculty members teach foundational courses in
        automotive crash safety. One of these courses was
        selected for the inaugural group of National
        First-Class Undergraduate Courses by China's
        Ministry of Education and has enrolled more than
        47,000 students. Other distinctions include
        recognition for excellence in undergraduate
        teaching plans among Beijing universities,
        designation as Tsinghua University Courses of
        Excellence, and recognition as Demonstration
        Courses in Moral and Values Education, which
        integrate ethical reflection and social responsibility
        into technical education. Graduates have gone on
        to careers at leading universities worldwide and
        in industry. Faculty members have received
        Tsinghua University's "Outstanding Mentor and Friend"
        Award on six occasions, recognizing their guidance
        and support for students.
      </li>

    </ul>

  </section>

</div>

---
layout: page
permalink: /people/
title: Team
description: Faculty members of Automotive Crash Laboratory
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
  min-height: 44px;
  margin: 0 0 12px;

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

  <div class="faculty-grid">

    <!-- Professor Zhou Qing -->

    <div class="faculty-card">

      <img
        class="faculty-photo"
        src="{{ '/assets/img/professor_zhou.jpg' | relative_url }}"
        alt="Professor Zhou Qing"
      >

      <h3 class="faculty-name">
        Prof. Zhou Qing
      </h3>

      <p class="faculty-role">
        Professor<br>
        Tsinghua University
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


    <!-- Associate Researcher Xia Yong -->

    <div class="faculty-card">

      <img
        class="faculty-photo"
        src="{{ '/assets/img/professor_xia.jpg' | relative_url }}"
        alt="Associate Researcher Xia Yong"
      >

      <h3 class="faculty-name">
        Xia Yong
      </h3>

      <p class="faculty-role">
        Associate Researcher<br>
        Tsinghua University
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


    <!-- Associate Professor Nie Bingbing -->

    <div class="faculty-card">

      <img
        class="faculty-photo"
        src="{{ '/assets/img/professor_nie.jpg' | relative_url }}"
        alt="Associate Professor Nie Bingbing"
      >

      <h3 class="faculty-name">
        Assoc. Prof. Nie Bingbing
      </h3>

      <p class="faculty-role">
        Associate Professor<br>
        Tsinghua University
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
      is academically led by
      <strong>Professor Zhou Qing</strong>,
      with
      <strong>Associate Researcher Xia Yong</strong>
      and
      <strong>Associate Professor Nie Bingbing</strong>
      jointly contributing to its academic supervision.
      The faculty members have long been actively engaged
      in research and education, and have established
      distinguished academic influence in the field of
      automotive safety both in China and internationally.
    </p>

    <ul>

      <li>
        <strong>Research achievements.</strong>
        In recent years, the team has led more than 20
        research projects supported by the National Natural
        Science Foundation of China, national key research
        and development programs, and international
        collaborative initiatives. The team has published
        over 100 high-quality academic papers and obtained
        nearly 100 granted invention patents in China and
        the United States. It has established long-term,
        stable collaborations with leading companies in
        the automotive industry, both domestically and
        internationally. Some of its core technologies
        have achieved internationally leading performance
        and have been implemented in mass production.
      </li>

      <li>
        <strong>Academic leadership and influence.</strong>
        Faculty members have held prominent academic
        positions, including Council Member of the
        International Research Council on Biomechanics of
        Injury (IRCOBI), with the first Chinese scholar
        to serve in this capacity; head of the Pedestrian
        Safety Division of SAE International; Member of
        the Academic Committee of Tsinghua University;
        and Chair of the School Academic Committee.
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
        Faculty members teach a series of foundational
        courses on automotive crash safety. Their teaching
        achievements include recognition as one of the
        inaugural National First-Class Undergraduate
        Courses by the Ministry of Education of China,
        with enrollment exceeding 47,000 students;
        recognition for high-quality undergraduate
        teaching plans among Beijing universities;
        designation as Tsinghua University Excellent
        Courses; and recognition as Model Courses for
        Curriculum-Based Ideological and Political
        Education. Graduates have pursued careers at
        leading universities worldwide and in frontline
        positions across industry. Faculty members
        have received Tsinghua University's
        "Good Teacher and Helpful Friend"
        recognition on six occasions.
      </li>

    </ul>

  </section>

</div>

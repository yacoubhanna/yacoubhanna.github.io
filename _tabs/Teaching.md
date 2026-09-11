---
layout: page
title: Teaching
permalink: /teaching/
icon: fas fa-chalkboard-teacher
order: 1
---

<style>

/* ==========================================
   Teaching Cards
   ========================================== */

.teaching-card {
  border: 1px solid var(--main-border-color, #e5e5e5);
  border-radius: 14px;
  margin-bottom: 20px;
  background: var(--main-bg, #ffffff);
  overflow: hidden;

  transition:
    transform 0.2s ease,
    box-shadow 0.2s ease,
    border-color 0.2s ease;
}

.teaching-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.08);
}

.teaching-card[open] {
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.08);
}


/* ==========================================
   Card Header
   ========================================== */

.teaching-card > summary {
  list-style: none;
  cursor: pointer;

  padding: 22px 24px;

  display: flex;
  align-items: center;
  justify-content: space-between;

  gap: 18px;
}

.teaching-card > summary::-webkit-details-marker {
  display: none;
}

.teaching-card > summary::marker {
  content: "";
}

.teaching-summary {
  display: flex;
  align-items: center;
  gap: 16px;
  min-width: 0;
}

.teaching-icon {
  width: 48px;
  height: 48px;
  min-width: 48px;

  border-radius: 12px;

  display: flex;
  align-items: center;
  justify-content: center;

  font-size: 1.3rem;

  background: rgba(13, 110, 253, 0.10);
  color: var(--link-color, #0d6efd);
}

.teaching-title {
  display: block;

  font-size: 1.08rem;
  font-weight: 700;

  color: var(--heading-color, inherit);
}

.teaching-subtitle {
  display: block;

  margin-top: 4px;

  font-size: 0.90rem;
  font-weight: 400;

  color: var(--text-muted-color, #6c757d);
}


/* ==========================================
   Arrow
   ========================================== */

.teaching-card > summary::after {
  content: "›";

  font-size: 1.9rem;
  font-weight: 300;

  color: var(--text-muted-color, #777);

  transition: transform 0.2s ease;
}

.teaching-card[open] > summary::after {
  transform: rotate(90deg);
}


/* ==========================================
   Expanded Content
   ========================================== */

.teaching-body {
  padding: 22px 24px 26px 24px;

  border-top: 1px solid var(--main-border-color, #e5e5e5);
}

.teaching-body p {
  line-height: 1.75;
}


/* ==========================================
   Course Badges
   ========================================== */

.course-badges {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;

  margin-bottom: 20px;
}

.course-badge {
  display: inline-block;

  padding: 5px 11px;

  border-radius: 20px;

  font-size: 0.78rem;
  font-weight: 600;

  background: rgba(13, 110, 253, 0.10);
  color: var(--link-color, #0d6efd);
}


/* ==========================================
   Previous Teaching Items
   ========================================== */

.teaching-item {
  padding: 18px 20px;
  margin-bottom: 14px;

  border: 1px solid var(--main-border-color, #e5e5e5);
  border-radius: 10px;

  background: var(--card-bg, var(--main-bg, #ffffff));

  transition:
    transform 0.2s ease,
    box-shadow 0.2s ease;
}

.teaching-item:last-child {
  margin-bottom: 0;
}

.teaching-item:hover {
  transform: translateY(-1px);
  box-shadow: 0 5px 16px rgba(0, 0, 0, 0.06);
}

.teaching-item-title {
  font-weight: 700;
  margin-bottom: 4px;
}

.teaching-item-institution {
  font-size: 0.90rem;

  margin-bottom: 10px;

  color: var(--text-muted-color, #6c757d);
}


/* ==========================================
   Mobile
   ========================================== */

@media (max-width: 700px) {

  .teaching-card > summary {
    padding: 18px;
  }

  .teaching-body {
    padding: 18px;
  }

  .teaching-icon {
    width: 42px;
    height: 42px;
    min-width: 42px;

    font-size: 1.1rem;
  }

  .teaching-title {
    font-size: 1rem;
  }

  .teaching-subtitle {
    font-size: 0.82rem;
  }

}

</style>


<!-- =========================================================
     CDA 3200
     ========================================================= -->

<details class="teaching-card">

<summary>

  <span class="teaching-summary">

    <span class="teaching-icon">
      <i class="fa-solid fa-microchip"></i>
    </span>

    <span>

      <span class="teaching-title">
        CDA 3200 — Digital Systems & Architecture
      </span>

      <span class="teaching-subtitle">
        Digital Logic · Computer Architecture · Hardware Design
      </span>

    </span>

  </span>

</summary>


<div class="teaching-body">

  <div class="course-badges">

    <span class="course-badge">
      Undergraduate
    </span>

    <span class="course-badge">
      Fall 2026
    </span>

    <span class="course-badge">
      Florida Gulf Coast University
    </span>

  </div>

  <p>
  This course covers the design and application of datapaths, controllers,
  memory systems, and registers used in digital systems. It introduces
  traditional and modern computer architecture and explores foundational
  design topics, including Boolean algebra, logic gates, combinational and
  sequential circuits, finite-state machines, and processor organization.
  </p>

  <p>
  The course combines lectures, problem-solving exercises, digital-logic
  design activities, hands-on laboratories, and examinations.
  </p>

  <!--
  <p>
  <strong>Textbook:</strong>
  Enoch O. Hwang,
  <em>Digital Logic and Microprocessor Design with Interfacing</em>,
  2nd Edition, 2018.
  </p>
  -->

</div>

</details>



<!-- =========================================================
     CEN 3078
     ========================================================= -->

<details class="teaching-card">

<summary>

  <span class="teaching-summary">

    <span class="teaching-icon">
      <i class="fa-solid fa-shield-halved"></i>
    </span>

    <span>

      <span class="teaching-title">
        CEN 3078 — Computer Security
      </span>

      <span class="teaching-subtitle">
        Cybersecurity · Cryptography · Network & Software Security
      </span>

    </span>

  </span>

</summary>


<div class="teaching-body">

  <div class="course-badges">

    <span class="course-badge">
      Undergraduate
    </span>

    <span class="course-badge">
      Fall 2026
    </span>

    <span class="course-badge">
      Florida Gulf Coast University
    </span>

  </div>

  <p>
  This course covers the foundations of computer security, including
  threats, vulnerabilities, and attacks that exploit computer systems
  and networks.
  </p>

  <p>
  Topics include security principles, risk assessment, threat modeling,
  authentication, access control, cryptography, network security,
  software security, penetration testing, and prevention and mitigation
  techniques.
  </p>

  <p>
  The learning experience combines lectures, hands-on laboratories,
  security demonstrations, and scenario-based exercises to connect
  fundamental security concepts with practical applications.
  </p>

</div>

</details>



<!-- =========================================================
     PREVIOUS TEACHING EXPERIENCE
     ========================================================= -->

<details class="teaching-card">

<summary>

  <span class="teaching-summary">

    <span class="teaching-icon">
      <i class="fa-solid fa-person-chalkboard"></i>
    </span>

    <span>

      <span class="teaching-title">
        Previous Teaching Experience
      </span>

      <span class="teaching-subtitle">
        Cybersecurity · Networking · IoT · Cyber-Physical Systems
      </span>

    </span>

  </span>

</summary>


<div class="teaching-body">

  <p>
  Before joining Florida Gulf Coast University, I taught and contributed
  to cybersecurity and networking courses through several educational
  and professional-development programs.
  </p>


  <div class="teaching-item">

    <div class="teaching-item-title">
      Critical Infrastructure Resilience Program
    </div>

    <div class="teaching-item-institution">
      Florida International University
    </div>

    <p>
    Contributed to curriculum assessment and led courses covering the
    Internet of Things (IoT) and Cyber-Physical Systems (CPS). The courses
    addressed the design, operation, resilience, and security of connected
    systems and critical infrastructure.
    </p>

  </div>


  <div class="teaching-item">

    <div class="teaching-item-title">
      CyberSkills2Work
    </div>

    <div class="teaching-item-institution">
      Florida International University
    </div>

    <p>
    Taught courses in Foundations of Cybersecurity and Networking for
    veterans and first responders. The courses combined cybersecurity
    fundamentals with practical exercises and workforce-relevant skills.
    </p>

  </div>

</div>

</details>
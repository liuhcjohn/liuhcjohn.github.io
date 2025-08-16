---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="cv-download-section" style="text-align: center; margin-bottom: 30px; padding: 20px; background-color: #f8f9fa; border-radius: 8px;">
  <h2 style="margin-bottom: 15px;">Download Resume</h2>
  <p style="margin-bottom: 20px;">View or download my complete resume in PDF format:</p>
  <a href="{{ base_path }}/files/Liu_John_Resume.pdf" class="btn btn--primary btn--large" target="_blank" style="font-size: 16px; padding: 12px 24px;">
    <i class="fas fa-download"></i> Download Resume (PDF)
  </a>
</div>

Education
======
* **Bachelor of Science in Electrical Engineering**  
  University Name, Year
  * Relevant Coursework: Circuit Design, Digital Systems, Signal Processing
  * GPA: [Your GPA]

* **Master of Science in [Your Field]** (if applicable)  
  University Name, Year
  * Focus: [Your specialization]
  * Thesis: [Your thesis title]

Professional Experience
======
* **Senior Design Engineer** | [Current/Recent Position]  
  Company Name, [Start Date] - [End Date/Present]
  * Led development of [specific projects/technologies]
  * Collaborated with cross-functional teams to deliver [specific outcomes]
  * Implemented [specific technologies/methodologies] resulting in [specific improvements]
  * Mentored junior engineers and contributed to technical documentation

* **[Previous Position Title]**  
  Company Name, [Start Date] - [End Date]
  * Designed and implemented [specific systems/solutions]
  * Managed [specific responsibilities]
  * Achieved [specific accomplishments/metrics]

* **[Earlier Position Title]**  
  Company Name, [Start Date] - [End Date]
  * Developed [specific skills/projects]
  * Contributed to [specific team/department goals]
  * Gained experience in [specific technologies/domains]

Technical Skills
======
* **Programming Languages**: [e.g., Python, C++, MATLAB, Verilog]
* **Software & Tools**: [e.g., CAD software, simulation tools, development environments]
* **Hardware**: [e.g., FPGA, microcontrollers, circuit design, testing equipment]
* **Specialized Knowledge**: 
  * [Specific domain expertise]
  * [Relevant technologies]
  * [Industry standards/protocols]

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Certifications & Awards
======
* **[Professional Certification]** - [Issuing Organization], [Year]
* **[Industry Award/Recognition]** - [Organization], [Year]
* **[Academic Honor]** - [Institution], [Year]

Projects & Research
======
* **Cisco 1RU Senior Design Project** - [Year]
  * [Brief description of the project]
  * Technologies used: [List relevant technologies]
  * [Key achievements/outcomes]

* **[Additional Project Name]**
  * [Project description and your role]
  * [Technologies and methodologies used]
  * [Results and impact]

Professional Activities
======
* **[Professional Organization]** - Member since [Year]
* **[Committee/Board Position]** - [Organization], [Year-Year]
* **[Conference/Workshop]** - Presenter/Attendee, [Year]
* **[Volunteer Experience]** - [Organization], [Year-Year]

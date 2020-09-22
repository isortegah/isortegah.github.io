---
layout: page
title: Curriculum Vitae
permalink: /about/cv
---
<link rel="stylesheet" href="{{ "/assets/css/cv.css" | relative_url }}">
<div class="cv-page">
<h3>RESUME
<a href="https://drive.google.com/file/d/1BM9-hzQDQVj7_EkTKyihXDAtk3NaxS2Y/view?usp=sharing" target="_blank" class="down">Download</a></h3>
<br>
<div class="p">
    Computing Engineer with professional development in ​Q.A. area for more than 10 years. I have participated in the software development life cycle in different areas of the industry such as telecommunications, banking, doing manual and automated testing frameworks with languages such as Javascript, Java, Scala and Python.
</div>
<br>
<div class="cv-section">EXPERIENCE</div>
<div class="p">
<div class="cv-experience-title">Big Data QA Automation Engineer, Datio America​ ​ <span class="cv-period">Nov 2017 - Present</span></div>

<ul class="list">
    <li>Agile framework</li>
    <li>Training of new co-workers</li>
    <li>At charge of communication with scrum team from geographies such as Colombia and Argentina</li>
    <li>Review of global pieces of the bank’s information processing, for their adaptation and implementation in the bank’s local geographies</li>
    <li>Working with big data technologies</li>
    <li>Coding of libraries with Java and Scala, to perform functional validations to Rest API services and front end pieces in the big data platform</li>
    <li>CI/CD Jenkins Pipelines Upgrade with Shared Libraries (Groovy)</li>
    <li>QA in the ingestion process, working in deep understanding about ETL and Governance process in Banking Big Data environment</li>
    <li>QA in the processing data projects (Spark, Scala, Python)</li>
    <li>Continuous learning Spark, Scala, Python, Java, Hadoop</li>
    <li>Tools: Docker, Maven, Cucumber, Gherkin, Sikulix, Jupyter, IntelliJ IDE, Hadoop, Jenkins, Monitoring Tools, Postman, JIRA</li>
    </ul>
</div>
<div class="cv-experience-title">QA Automation Engineer, NearBPO​ <span class="cv-period">Jun 2014 - Nov 2017</span></div>

<ul class="list">
    <li>Agile framework</li>
    <li>Responsible of QA Area</li>
    <li>Communicate status and reports to CEO and other stakeholders</li>
    <li>On charge of projects status monitoring</li>
    <li>Automation e2e Testing with JavaScript Framework (Protractor, Jasmine, Selenium Webdriver with Java)</li>
    <li>Automation API Rest Testing with JavaScript Framework (Mocha, Chai, Should)</li>
    <li>SQL (MySQL, PostgreSQL)</li>
    <li>API design and developer training with Apigee Edge</li>
    <li>noSQL (MongoDB)</li>
    <li>Test case design</li>
    <li>Tracking bugs and resolutions with Redmine</li>
    <li>API Testing with Postman and SoapUI</li>
    <li>Functional and regression testing</li>
</ul>  

<div class="cv-experience-title">Systems Analyst QA, Commercial Collection Systems <span class="cv-period">Jan 2012 - May 2014</span></div>

<div class="p">
Implemented the Agile framework, user stories review for the request to the software factory, receipt of artifact and implementation of acceptance tests and execution of code coverage tests with IMB-Purify. Monitoring projects life cycle and defects control. Review production environment deployments and final tests with the user.
</div><br>
<div class="cv-experience-title">Test Manager, Quality and Testing Center TELMEX <span class="cv-period">Jun 2008 - Jul 2010</span></div>
<div class="p">
Requirements and Test environment Analysis for the design and implementation of  black and white box test plan. Creation and execution of plans for coverage and stress tests. Research and implementation of tools for the validation of results and execution of tests.
</div>
<br>
<div class="cv-section">EDUCATION</div>

<div class="p">
<span class="cv-instituto">Universidad Nacional Autónoma de México</span>
<br>
B.Sc. in Computer Engineering - 4.0 GPA
<br>
Period 2003-2008
</div>
<br>
<div class="p">
<span class="cv-instituto">Diploma in Information Technology and Communications Project Management. UNAM.</span>
<br>
Period 2013-2014
</div>
<br>
<div class="cv-sectionedu">Certifications</div>

SCRUM Fundamentals
<br><br>
<div class="cv-sectionedu">
Additional Experience And Awards</div>

<div class="p">
    <ul class="list">
        <li>“Mención Honorífica”: Award granted for Bachelor’s degree students of excellence</li>
        <li>Excellence Scholarship for academic merit (2003 – 2008): Scholarship for at least 4 GPA</li>
        <li>“Gabino Barreda” medal winner: Award granted for the best 2003-2008 Bachelor’s Generation student</li>
    </ul>
</div>
<br>
<div class="cv-section">
PROGRAMMING LANGUAGES AND TECHNOLOGIES
</div>

<div class="cv-subsection">Programming languages:</div>
<ul>
    {% for skill in site.data.LanguageProgramming %}
    <li class="skill">{{ skill.name }} <span class="cv-nivel">{{ skill.nivel }}</span></li>
    {% endfor %}
</ul>

<div class="cv-subsection">Operating systems:</div>

<ul>
    {% for skill in site.data.OperatingSystems %}
    <li class="skill">{{ skill.name }} <span class="cv-nivel">{{ skill.nivel }}</span></li>
    {% endfor %}
</ul>

<div class="cv-subsection">BD:</div>
<ul>
    {% for skill in site.data.Db %}
    <li class="skill">{{ skill.name }} <span class="cv-nivel">{{ skill.nivel }}</span></li>
    {% endfor %}
</ul>

<div class="cv-subsection">Others:</div>
 <ul>
    {% for skill in site.data.Others %}
    <li class="skill">{{ skill.name }} <span class="cv-nivel">{{ skill.nivel }}</span></li>
    {% endfor %}
</ul>

</div>
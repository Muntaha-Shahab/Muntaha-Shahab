<img src="assets/header.svg" alt="Muntaha Shahab, Backend Developer (Python / Django). Terminal-style header: python manage.py runserver" width="100%" />

<div align="center">

Status: `200 OK` &nbsp;|&nbsp; Version: `1.0` &nbsp;|&nbsp; Region: `Lahore, PK`

[LinkedIn](https://linkedin.com/in/muntahashahab) &nbsp;|&nbsp; [itsmuntaha010@gmail.com](mailto:itsmuntaha010@gmail.com)

</div>

| Endpoint | Description |
| --- | --- |
| [`GET /about`](#get-about) | Who I am and what I'm looking for |
| [`GET /projects`](#get-projects) | What I've built |
| [`GET /stack`](#get-stack) | Technologies I work with |
| [`GET /activity`](#get-activity) | GitHub contribution graph, updated daily |
| [`GET /education`](#get-education) | Academic background |
| [`POST /contact`](#post-contact) | How to reach me |

---

## `GET /about`

```json
{
  "name": "Muntaha Shahab",
  "role": "Backend Developer (Python / Django)",
  "focus": ["REST APIs", "Authentication", "Database design"],
  "currently_building": "HaqDaar, AI-powered legal aid platform",
  "languages": ["Urdu", "English"],
  "location": "Lahore, Pakistan",
  "status": "open_to_work",
  "looking_for": ["backend internships", "junior developer roles"],
  "work_mode": ["onsite (Lahore)", "remote"]
}
```

---

## `GET /projects`

### Featured

<img src="assets/haqdaar.svg" alt="HaqDaar: AI-powered legal aid platform. Final year project, team of 3, in development. Django, Django REST Framework, PostgreSQL, JWT, Next.js, Tailwind CSS." width="100%" />

### Repositories

<table width="100%">
  <tr>
    <td width="50%"><a href="https://github.com/Muntaha-Shahab/django-student-management-system"><img src="assets/student.svg" alt="django-student-management-system" width="100%" /></a></td>
    <td width="50%"><a href="https://github.com/Muntaha-Shahab/django-skill-management-system"><img src="assets/skills.svg" alt="django-skill-management-system" width="100%" /></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://github.com/Muntaha-Shahab/django-profile-management-portal"><img src="assets/profile.svg" alt="django-profile-management-portal" width="100%" /></a></td>
    <td width="50%"><a href="https://github.com/Muntaha-Shahab/ResumeBuilder-Web"><img src="assets/resume.svg" alt="ResumeBuilder-Web" width="100%" /></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://github.com/Muntaha-Shahab/task-manager-cli"><img src="assets/taskcli.svg" alt="task-manager-cli" width="100%" /></a></td>
    <td width="50%"><a href="https://github.com/Muntaha-Shahab?tab=repositories"><img src="assets/folioverse.svg" alt="FolioVerse" width="100%" /></a></td>
  </tr>
</table>

---

## `GET /stack`

<img src="assets/stack.svg" alt="Languages: Python, C++, Java, JavaScript, HTML, CSS. Backend: Django, Django REST Framework, REST APIs, JWT. Frontend: Next.js, Bootstrap, Tailwind CSS. Databases: PostgreSQL, MySQL, SQLite, Firestore. ML: scikit-learn, Jupyter. Tools: Git, GitHub, Linux, Selenium, Android Studio." width="100%" />

```json
{
  "languages": ["Python", "C++", "Java", "JavaScript", "HTML", "CSS"],
  "backend": ["Django", "Django REST Framework", "REST APIs", "JWT"],
  "frontend": ["Next.js", "Bootstrap", "Tailwind CSS"],
  "databases": ["PostgreSQL", "MySQL", "SQLite", "Cloud Firestore"],
  "machine_learning": ["scikit-learn", "Jupyter"],
  "tools": ["Git", "GitHub", "Linux", "Selenium", "Android Studio"]
}
```

---

## `GET /activity`

<img src="assets/activity.svg" alt="GitHub contribution graph for the last year" width="100%" />

---

## `GET /education`

```json
{
  "degree": "B.S. Software Engineering",
  "institution": "University of Management and Technology (UMT), Lahore",
  "period": "Mar 2023 - Feb 2027 (expected)",
  "focus_areas": ["Database Systems", "Software Architecture", "Information Security", "Machine Learning", "NLP"],
  "certifications": [
    { "name": "JavaScript Mastery Bootcamp", "issuer": "Kohaq", "date": "Nov 2025" }
  ]
}
```

---

## `POST /contact`

[LinkedIn](https://linkedin.com/in/muntahashahab) &nbsp;|&nbsp; [itsmuntaha010@gmail.com](mailto:itsmuntaha010@gmail.com)

```json
{ "status": 202, "message": "Accepted. I reply within a day or two." }
```

<!--
FUTURE ENDPOINTS (uncomment and fill in as they become true):

## `GET /achievements`
## `GET /open-source`
## `GET /experience`
-->

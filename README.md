# Muntaha Shahab

**Backend Developer API** &nbsp;|&nbsp; Python &middot; Django &middot; REST &middot; PostgreSQL

> Documentation for a backend developer who builds secure, well-structured APIs.
> Status: `200 OK` &nbsp;|&nbsp; Version: `1.0` &nbsp;|&nbsp; Region: `Lahore, PK`

| Endpoint | Description |
| --- | --- |
| [`GET /about`](#get-about) | Who I am and what I'm looking for |
| [`GET /projects`](#get-projects) | What I've built |
| [`GET /stack`](#get-stack) | Technologies I work with |
| [`GET /education`](#get-education) | Academic background |
| [`GET /certifications`](#get-certifications) | Courses and certifications |
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

### Featured: HaqDaar

```json
{
  "name": "HaqDaar",
  "type": "Final year project (team of 3)",
  "status": "in_development",
  "summary": "Bilingual (Urdu/English) platform that helps citizens in Pakistan understand their legal rights and connect with volunteer lawyers and NGOs.",
  "stack": ["Django", "Django REST Framework", "PostgreSQL", "JWT", "Next.js", "Tailwind CSS"],
  "my_contributions": [
    "REST APIs for admin citizen management: search, filters, block/unblock, soft delete and restore, CSV export, audit log",
    "PostgreSQL models for citizens and cases: assignments, deadlines, activity, notes, documents",
    "JWT authentication between the Next.js frontend and the backend",
    "Migrated a 240-file frontend to Next.js",
    "Manage the GitHub organization and review teammates' pull requests"
  ]
}
```

### Other projects

| Project | Description | Stack |
| --- | --- | --- |
| [Student Management System](https://github.com/Muntaha-Shahab/django-student-management-system) | Student records with email account activation, login, dashboard, add and search | Django, SQLite |
| [Skill Management System](https://github.com/Muntaha-Shahab/django-skill-management-system) | Per-user dashboard to track skills, proficiency and years of experience | Django, SQLite |
| [Profile Management Portal](https://github.com/Muntaha-Shahab/django-profile-management-portal) | Registration, activation, login and profile page with picture upload | Django, Pillow |
| [CV Builder](https://github.com/Muntaha-Shahab/ResumeBuilder-Web) | Resume builder with live preview, 10 templates, autosave and PDF export | JavaScript, Bootstrap |
| [Task Manager CLI](https://github.com/Muntaha-Shahab/task-manager-cli) | Terminal task manager with persistent JSON storage | Python |

---

## `GET /stack`

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

## `GET /education`

```json
{
  "degree": "B.S. Software Engineering",
  "institution": "University of Management and Technology (UMT), Lahore",
  "period": "Mar 2023 - Feb 2027 (expected)",
  "focus_areas": ["Database Systems", "Software Architecture", "Information Security", "Machine Learning", "NLP"]
}
```

---

## `GET /certifications`

```json
[
  { "name": "JavaScript Mastery Bootcamp", "issuer": "Kohaq", "date": "Nov 2025" }
]
```

---

## `POST /contact`

```
Content-Type: application/json
```

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

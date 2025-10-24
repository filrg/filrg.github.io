---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %} **Team**

## Meet Our Team of Researchers and Innovators
Our team is a dynamic blend of faculty and students passionate about immersive multimedia, networking, and smart applications. Together, we drive cutting-edge research and real-world innovation.

---

### Professors
{% include list.html data="members" component="portrait" filter="tag == 'professor'" %}

---

### Academic Staff
{%
  include button.html
  link="#"
  text="Academic Staff"
  icon="fa-solid fa-user-graduate"
  flip=true
  style="primary"
  onclick="toggleSection('staff')"
%}

<div id="staff" style="display:none; margin-top: 1.5rem;">
  {% include list.html data="members" component="portrait" filter="description == 'Academic Staff'" %}
</div>

---

### Graduate Students
{%
  include button.html
  link="#"
  text="Graduate Students"
  icon="fa-solid fa-user-graduate"
  flip=true
  style="primary"
  onclick="toggleSection('graduate')"
%}

<div id="graduate" style="display:none; margin-top: 1.5rem;">
  {% include list.html data="members" component="portrait" filter="role == 'grad'" %}
</div>

---

### Undergraduate Students
{%
  include button.html
  link="#"
  text="Undergraduate Students"
  icon="fa-solid fa-user-graduate"
  flip=true
  style="primary"
  onclick="toggleSection('undergraduate')"
%}

<div id="undergraduate" style="display:none; margin-top: 1.5rem;">
  {% include list.html data="members" component="portrait" filter="description == 'Cohort 67'" %}
  {% include list.html data="members" component="portrait" filter="description == 'Cohort 68'" %}
  {% include list.html data="members" component="portrait" filter="description == 'Cohort 69'" %}
  {% include list.html data="members" component="portrait" filter="description == 'Cohort 70'" %}
</div>

---

### Alumni
{%
  include button.html
  link="#"
  text="Alumni"
  icon="fa-solid fa-user-graduate"
  flip=true
  style="primary"
  onclick="toggleSection('alumni')"
%}

<div id="alumni" style="display:none; margin-top: 1.5rem;">
  {% include list.html data="members" component="portrait" filter="description == 'Cohort 66'" %}
</div>

---

<script>
function toggleSection(id) {
  const section = document.getElementById(id);
  if (!section) return;
  section.style.display = (section.style.display === 'none' || section.style.display === '') 
    ? 'block' 
    : 'none';
}
</script>


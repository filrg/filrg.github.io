---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}**Team**

## Meet Our Team of Researchers and Innovators
Our team is a dynamic blend of faculty and students passionate about immersive multimedia, networking, and smart applications. Together, we drive cutting-edge research and real-world innovation.

### Professors

{% include list.html data="members" component="portrait" filter="tag == 'professor'" %}

### Academic Staff
{%
  include button.html
  link="#"
  text="Academic Staff"
  icon="fa-solid fa-user-graduate"
  flip=true
  style="primary"
  onclick="toggleAcademicStaff()"
%}
<div id="staff" style="display:none; margin-top: 1.5rem;">
{% include list.html data="members" component="portrait" filter="description == 'Academic Staff'"%}
</div>
<script>
function toggleStaff() {
  const section = document.getElementById('staff');
  const isHidden = section.style.display === 'none';
  section.style.display = isHidden ? 'block' : 'none';
}
</script>
###Grad

{%
  include button.html
  link="#"
  text="Graduate Student"
  icon="fa-solid fa-user-graduate"
  flip=true
  style="primary"
  onclick="toggleStudents()"
%}

<div id="graduate" style="display:none; margin-top: 1.5rem;">
{% include list.html data="members" component="portrait" filter="role == 'grad'"%}
</div>

<script>
function toggleGradStudent() {
  const section = document.getElementById('graduate');
  const isHidden = section.style.display === 'none';
  section.style.display = isHidden ? 'block' : 'none';
}
</script>

###Undergrad 
{%
  include button.html
  link="#"
  text="Undergraduate Student"
  icon="fa-solid fa-user-graduate"
  flip=true
  style="primary"
  onclick="toggleStudents()"
%}

<div id="undergraduate" style="display:none; margin-top: 1.5rem;">


{% include list.html data="members" component="portrait" filter="description == 'Cohort 67'" %}
{% include list.html data="members" component="portrait" filter="description == 'Cohort 68'" %}
{% include list.html data="members" component="portrait" filter="description == 'Cohort 69'" %}
{% include list.html data="members" component="portrait" filter="description == 'Cohort 70'" %}
</div>

<script>
function toggleStudents() {
  const section = document.getElementById('undergraduate');
  const isHidden = section.style.display === 'none';
  section.style.display = isHidden ? 'block' : 'none';
}
</script>

### "Alumni"
{%
  include button.html
  link="#"
  text="Alumni"
  icon="fa-solid fa-user-graduate"
  flip=true
  style="primary"
  onclick="toggleStudents()"
%}


<div id="alumni" style="display:none; margin-top: 1.5rem;">
{% include list.html data="members" component="portrait" filter="description == 'Cohort 66'" %}
</div>

<script>
function toggleAlumni(){
  const section = document.getElementById('"alumni"');
  const isHidden = section.style.display === 'none';
  section.style.display = isHidden ? 'block' : 'none';
}
</script>








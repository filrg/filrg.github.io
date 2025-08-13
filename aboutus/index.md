---
title: About Us
nav:
  order: 5
  tooltip: About Us
---

# {% include icon.html icon="fa-solid fa-book" %}**History of FIL**



# {% include icon.html icon="fa-solid fa-mug-hot" %} **Life at FIL**

From research achievements to lab celebrations, our journey is shaped by the people who make it possible. Here's a glimpse into our vibrant community life.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/fil/graduation-2024.jpg" %}
{% include figure.html image="images/fil/YEP-2025.jpg" %}
{% include figure.html image="images/fil/8-3-2025.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}

# {% include icon.html icon="fa-regular fa-envelope" %}**Contact**

{%
  include button.html
  type="facebook"
  tooltip="Chat with us"
  link="future-internet-lab"
%}
{%
  include button.html
  type="address"
  tooltip="our location on google maps for easy navigation"
  link="https://maps.app.goo.gl/yldx4sj79wvedyac6"
%}

For inquiries regarding **FIL Research Group (FILRG)**, please reach out to our faculty members:

{% include section.html %}

{% capture col1 %}
## Assoc. Prof. Truong Thu Huong  
{%
  include button.html
  type="email"
  text="huong.truongthu@hust.edu.vn"
  link="mailto:huong.truongthu@hust.edu.vn"
%}
<!-- {%
  include button.html
  type="phone"
  text="+84 XXX XXX XXX"
  link="tel:+84XXXXXXXXX"
%} -->

{%
  include figure.html
  image="images/fil/members/co-truong-thu-huong.jpg"
%}

{% endcapture %}

{% capture col2 %}
## Assoc. Prof. Nguyen Huu Thanh  
{%
  include button.html
  type="email"
  text="thanh.nguyenhuu@hust.edu.vn"
  link="mailto:thanh.nguyenhuu@hust.edu.vn"
%}

<!-- {%
  include button.html
  type="phone"
  text="+84 XXX XXX XXX"
  link="tel:+84XXXXXXXXX"
%} -->

{%
  include figure.html
  image="images/fil/members/thay-nguyen-huu-thanh.jpg"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}


# {% include icon.html icon="fa-regular fa-envelope" %}**Join us**

<form id="contactForm" method="POST" action="https://formsubmit.co/filrg.hr@husteduvn.onmicrosoft.com" enctype="multipart/form-data" style="max-width:600px; margin: 2em auto; display: flex; flex-direction: column; gap: 1em;">
  <label for="name">Your full name</label>
  <input type="text" name="name" id="name" required style="padding: 0.5em; font-size: 1em; border: 1px solid #ccc; border-radius: 4px; width: 100%" />

  <label for="cpa">Your CPA record</label>
<input type="number" name="cpa" id="cpa"
       step="0.01" min="0" max="4"
       required
       style="padding: 0.5em; font-size: 1em; border: 1px solid #ccc; border-radius: 4px; width: 100%;" />


  <label for="email">Your email</label>
  <input type="email" name="email" id="email" required style="padding: 0.5em; font-size: 1em; border: 1px solid #ccc; border-radius: 4px; width: 100%" />

  <label for="message">What is your motivation?</label>
  <textarea name="message" id="message" rows="10" required style="padding: 0.5em; font-size: 1em; border: 1px solid #ccc; border-radius: 4px; width: 100%"></textarea>

 <label for="attachment">Attach your CV (PDF only)</label>
  <input type="file" name="attachment" id="attachment" accept="application/pdf" required 
         style="padding: 0.5em; font-size: 1em; border: 1px solid #ccc; border-radius: 4px; width: 100%;" />

  <button type="submit" style="padding: 0.7em 1.2em; font-size: 1em; background-color: #000000; color: white; border: none; border-radius: 4px; cursor: pointer;">
    Submit
  </button>

  <p id="formStatus" style="margin-top: 1em;"></p>
</form>

{% include section.html dark=true %}

## FIL Research Group - ANSA Laboratory

{% capture col1 %}
#### Informations

Room E.711, Building C7, Hanoi University of Science and Technology, 1 Dai Co Viet, Hai Ba Trung, Hanoi.

futureinternetlab@gmail.com
{% endcapture %}

{% capture col2 %}

{% endcapture %}

{% capture col3 %}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}

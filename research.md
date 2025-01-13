---
layout: page
title: "Research"
---

{% comment %}
{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Research" %}
{% endif %}
{% endcomment %}

---

## Working Papers

- ### [Rainfall shocks and land use intensity]()
  <button class="dropdown-button" onclick="toggleAbstract('abstract1')">Show/Hide Abstract</button>
  <div id="abstract1" class="abstract-content">
      <p>Growing multiple crops per year (cropping intensity) is a crucial determinant of agricultural
      production, especially in multi-cropping and drought-prone regions. However, existing studies
      assessing the adverse effects of extreme weather events on global food security, have primarily
      focused on crop yield and area, while neglecting their effect on cropping intensity. In the face
      of extreme weather, farmers may adjust cropping intensity - either increasing or decreasing it - 
      which can mitigate or exacerbate impacts on overall production. Using district-level panel
      data from India, this study examines how cropping intensity responds to rainfall shocks both
      droughts and excessive rainfall. We find that rainfall shocks have an asymmetric effect on 
      cropping intensity: it declines in response to drought but increases under excess rainfall, 
      reflecting farmers’ behavioral response to these shocks. This adjustment primarily involves 
      changes in cultivated areas and area shares of crops, especially that of water-intensive crops. 
      Our results also suggest that the crop diversification significantly reduces the variability of 
      cropping intensity to droughts, while irrigation proves ineffective in mitigating the adverse 
      effects of droughts.</p>
  </div>

- ### [Does financial transparency within firms promote innovation?](#)
  Co-author: [Krishna Dixit](https://www.imthyderabad.edu.in/faculty/krishnadixit)

- ### [After the Storm. The Impact of Tropical Cyclones on Household Welfare](#)
  Co-author: [Digvijay Singh Negi](https://sites.google.com/view/digvijaysnegi/home?authuser=0)

<script>
    function toggleAbstract(id) {
        const abstract = document.getElementById(id);
        if (abstract.style.display === 'none' || abstract.style.display === '') {
            abstract.style.display = 'block';
        } else {
            abstract.style.display = 'none';
        }
    }
</script>

<style>
    .abstract-content {
        display: none;
        margin-top: 10px;
        border-left: 4px solid #007BFF;
        padding: 10px;
        background-color: #f9f9f9;
    }
    .dropdown-button {
        background-color: #007BFF;
        color: white;
        border: none;
        padding: 10px 20px;
        cursor: pointer;
        font-size: 14px;
        border-radius: 4px;
    }
    .dropdown-button:hover {
        background-color: #0056b3;
    }
</style>

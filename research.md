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
  <button class="dropdown-button" onclick="toggleAbstract('abstract1')">Show Abstract</button>
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

   <button class="dropdown-button" onclick="toggleAbstract('abstract2')">Show Abstract</button>
  <div id="abstract2" class="abstract-content">
      <p> Firms’ innovations spur their productivity growth and provide them with a sustainable competitive advantage. However, the positive effects of firms’ innovations extend beyond their own productivity improvements, contributing to overall economic growth and employment. Existing empirical studies suggest that firms’ innovations are influenced by several factors, among which firm financial transparency is an important one, as it reduces the firm’s cost of capital and improves its contractual efficiency. However, a priori, how financial transparency would affect innovation is ambiguous since there are two competing hypotheses: one suggests that financial transparency could increase firm innovation, while the other suggests it may reduce it. Existing empirical studies have found mixed evidence, with some studies suggesting a positive relationship, while others have found a negative association. In this context, using multi-country firm-level data from the World Bank Enterprises Survey, this paper re-examines the question: how does firm financial transparency affect innovation? Our results suggest that financial transparency is positively correlated with firm innovation and remains robust across several checks, including endogeneity concerns. This positive association between financial transparency and innovation also holds for both intensive and extensive margins of firm innovativeness, including when we separate innovation into adoption and invention aspects. Lastly, we also conduct a heterogeneity analysis across firm size, female ownership, and shareholding patterns, uncovering some interesting patterns.</p>
  </div>

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
        font-size: 10px;
        border-radius: 4px;
    }
    .dropdown-button:hover {
        background-color: #0056b3;
    }
</style>

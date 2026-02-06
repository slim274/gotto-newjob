# Gotto Job Website

## Project Overview
This is a static HTML/CSS/JS website for Gotto Job, a job listing platform. The site includes multiple pages such as Home, About, Contact, Job Listings, and Job Details.

---

## Day 2 Update: Dynamic Deployment Date

### Feature Added
- The website footer now displays a **dynamic deployment date**.
- This automatically shows the current date when the site is deployed.
- Code snippet:

```html
<p id="deploy-date"></p>
<script>
  const today = new Date();
  document.getElementById('deploy-date').innerText = 
    "Deployed on: " + today.toLocaleDateString();
</script>



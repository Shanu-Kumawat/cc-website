+++
title = "CC Club Alumni"
description = "Our alumni network spanning top companies and institutions worldwide"
template = "alumni.html"
weight = 3

[extra]
# This page will use data from data/alumni.yaml
# Custom template with search/filter functionality
use_alumni_data = true
+++

# CC Club Alumni

Our alumni are our pride! From students who learned their first lines of code in our workshops to seasoned engineers at top companies - the CC Club family extends across the globe.

---

## 🔍 Find Alumni

<!-- Search bar will be inserted here by template -->
<!-- Filters (by year, company, domain) will be here -->

---

## Alumni Directory

<!-- 
    Alumni cards will be rendered here from data/alumni.yaml
    with search and filter functionality from static/js/alumni-search.js
-->

<!-- Year-wise tabs or accordion structure -->
<!-- Each alumni card shows: photo, name, batch, current role, company, LinkedIn -->

---

## Want to Be Featured?

**CC Club Alumni:** Update your profile!

If you're a CC Club alumnus and want to be featured here:

1. Fill out the [Alumni Form](https://forms.gle/alumni-update-form)
2. Provide: Name, Batch, Current Role, Company, LinkedIn, Photo
3. Optional: Share your experience, advice for juniors

**Privacy**: Only information you choose to share will be displayed.

---

## Alumni Success Stories

Read about journeys of our alumni:

- [From CC Club to Google: Vikram's Story](/blog/alumni-stories/vikram-google)
- [How CC Club Prepared Me for Startup Life](/blog/alumni-stories/priya-startup)
- [From Contributor to Open Source Maintainer](/blog/alumni-stories/rahul-opensource)

---

## Alumni Engagement

### Give Back to CC Club

- **Mentorship**: Guide current students in their technical and career journeys
- **Guest Lectures**: Share your experiences and insights
- **Recruitment**: Hire talented CC Club members
- **Sponsorship**: Support club events and initiatives

Interested? Contact us at alumni@ccclub.edu

---

## Connect with Alumni

- **LinkedIn Group**: [CC Club Alumni Network](https://linkedin.com/groups/ccclub-alumni)
- **Discord**: [Join Alumni Channel](https://discord.gg/ccclub-alumni)
- **Email**: alumni@ccclub.edu

---

<!--
    ALUMNI PAGE TEMPLATE
    
    This page requires:
    - Custom template (templates/alumni.html)
    - JavaScript for search/filter (static/js/alumni-search.js)
    - YAML data file (data/alumni.yaml)
    
    FEATURES TO IMPLEMENT:
    1. Search by name, company, domain
    2. Filter by graduation year, company, role
    3. Year-wise organization (tabs or accordion)
    4. Lazy loading for performance
    5. Responsive cards
    
    ALUMNI CARD STRUCTURE:
    - Photo
    - Name
    - Batch (e.g., "2020-2024")
    - Current Role (e.g., "SDE-2 @ Google")
    - Company logo (optional)
    - LinkedIn link
    - Optional: Brief message for juniors
    
    SEARCH/FILTER IMPLEMENTATION:
    See static/js/alumni-search.js for the JavaScript implementation.
    
    DATA STRUCTURE:
    See data/alumni.yaml for the expected format.
-->

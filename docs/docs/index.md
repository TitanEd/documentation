---
title: TitanEd Docs
hide:
  - navigation
  - toc
---

<!-- ### TitanEd Docs -->

<div class="titaned-commerce-message">
  <strong> Your Learning, Our Technology — TitanEd LMS Suite</strong><br>
  Launch your LMS instantly with TELS — a secure, subscription-based, AI-driven learning experience platform designed for educators, institutions, and businesses of all sizes. </br></br>

  <a href="https://titaned.com/get-started/">Start today with a free trial</a>
</div>

<div class="search-block">
  <div class="titaned-search-bar">
    <input type="text" id="titaned-search" placeholder="How can we help you?" aria-label="Search TitanEd Docs">
    <div id="titaned-search-results" role="navigation" tabindex="0" class="csh-include-search"></div>
  </div>
</div>

<style>
/* Homepage Layout: Full-width styling only for the homepage (index.md) */
.md-content--home .md-main__inner {
  max-width: 100%;
  padding: 0;
}

.md-typeset h1{
  display:none;
  font-size: 1rem;
  margin: 0;
  padding: 0;
}
.md-typeset{
  padding: 0;
}
.titaned-commerce-message{
  margin-top:0;
  padding-top:0;
}
/* Commerce Message: Styles the promotional text above the search bar */
.titaned-commerce-message {
  text-align: center;
  padding: 0 16px 0 16px;
  margin: 0 auto 0;
  max-width: 900px;
  font-size: 16px;
  font-weight: 500;
  font-family: 'Syne', sans-serif;
  background: none; /* Primary color */
  color: #2C2C2C; /* Secondary color */
  line-height: 1.1;
}

.titaned-commerce-message strong {
  font-size: 32px;
  font-weight: 700;
  display: block;
  margin-bottom: 0px;
}

.titaned-commerce-message a {
  font-size: 24px;
  color: #EB5939; /* Highlight color */
  text-decoration: none;
  font-weight: 600;
  margin:0;
  padding:0;
}

.titaned-commerce-message a:hover {
  color: #232323; /* Darker for hover */
  text-decoration: underline;
}

/* Search Block: Container for isolating search styling */
.search-block {
  max-width: 900px;
  display: flex;
  align-item: center;
  justify-contant: center;
  margin: 0 auto;
  padding: 0;
}
.md-header{
  background-color: #2C2C2C;
}

.md-header__inner > .md-header__button > img {
  width: 152px;
  height: 68px;
}

/* Search Bar: Styled within the search block with custom height and red accent */
.titaned-search-bar {
  display: flex;
  align-items: center;
  width: 100%;
  margin: 16px auto 0;
  z-index: -1000;
}
.search-block .titaned-search-bar input {
  width: 100%;
  height: 60px;
  padding: 20px 20px 20px 60px;
  font-family: 'Roboto', sans-serif;
  border: 2px solid #ff0000;
  outline: none;
  border-radius: 30px;
  background: linear-gradient(135deg, #fffdfdff, #ffffff);
  color: #000000;
  box-sizing: border-box;
  transition: border-color 0.3s ease, box-shadow 0.3s ease;
  outline: none;
  /* box-shadow: 0 2px 5px rgba(255, 0, 0, 0.1); */
}

.search-block .titaned-search-bar input::placeholder {
  color: #cc0000;
  opacity: 0.8;
}

.search-block .titaned-search-bar input:focus {
  outline: none;
  border-color: #cc0000;
  box-shadow: 0 4px 8px rgba(255, 0, 0, 0.3);
}

/* Search Icon: Font Awesome magnifying glass with red accent */
.search-block .titaned-search-bar::before {
  content: '\f002';
  font-family: 'Font Awesome 6 Free';
  font-weight: 900;
  position: absolute;
  left: 38px;
  top: 50%;
  transform: translateY(-50%);
  font-size: 22px;
  color: #cc0000;
  /* z-index: 31; */
}

.search-block .titaned-search-bar input:focus + ::before {
  color: #ff0000;
}

/* Search Results Popup: Styled as a dropdown outside the input */
.search-block .csh-include-search {
  position: absolute;
  top: calc(100% + 12px);
  left: 16px;
  right: 16px;
  background: #fff;
  border: 1px solid #ff0000;
  border-radius: 20px;
  max-height: 400px;
  overflow-y: auto;
  /* z-index: 50; */
  box-shadow: 0 10px 25px rgba(255, 0, 0, 0.2);
  opacity: 0;
  transform: translateY(-15px);
  animation: popupSlideIn 0.4s ease forwards;
  padding: 10px 0;
  display: none;
}

.search-block .csh-include-search.active {
  display: block;
}

@keyframes popupSlideIn {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

/* Individual Search Result */
.search-block .csh-include-search-result {
  padding: 12px 16px;
  border-bottom: 1px solid #ffebee;
  transition: background-color 0.2s ease;
}

.search-block .csh-include-search-result:last-child {
  border-bottom: none;
}

.search-block .csh-include-search-result a {
  color: #000000;
  text-decoration: none;
  font-size: 16px;
  display: block;
  padding: 6px 10px;
  border-radius: 8px;
}

.search-block .csh-include-search-result a:hover,
.search-block .csh-include-search-result a:focus {
  color: #cc0000;
  background-color: #ffebee;
  outline: none;
}

/* Card Grid: Styles the 2x2 grid of cards */
@media only screen and (min-width: 768px){
.titaned-tile-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  /* grid-template-rows: repeat(2, auto); */
  gap: 15px;
  /* padding: 32px 16px; */
  max-width: 900px;
  margin: 0 auto;
}
}


/* Individual Card: Styles each card in the grid */
.titaned-tile {
  background: #f8f8f8; /* Lighter for image contrast */
  border: .4px solid #ddd;
  border-radius: 12px;
  overflow: hidden;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.titaned-tile:hover {
  transform: translateY(-4px);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
}

.titaned-tile a {
  display: grid;
  grid-template-columns: 30% 70%;
  padding: 12px 16px;
  gap: 16px;
  text-decoration: none;
  color: #000000;
}


/* Card Icon: Styles the image container */
.titaned-tile__icon {
  flex-shrink: 0;
  border: 0px solid black;
  width: 60px;
  height: 60px;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
  border-radius: 8px;
  background-color: #f8f8f8;
}

.titaned-tile__icon img {
  width: 100%; 
  height: 100%;
  object-fit: contain;
}

/* Remove span styling as no longer used */
/* .titaned-tile__icon span {
  font-size: 28px;
  color: #fff;
} */

 .titaned-tile__text{
  display: flex;
  flex-direction: column;
  text-align: center;
  justify-content: center;
 }  

/* Card Text: Styles the card title and description */
.titaned-tile h3 {
  text-align: left;
  font-size: 16px;
  color: #000000;
  overflow-wrap: break-word;
}

.titaned-tile p {
  text-align: left;
  font-size: 12px;
  color: #666;
  overflow-wrap: break-word;
}

/* FAQ Section: Styles for accordion-based FAQ section (site-wide) */
.program-faq {
  max-width: 100%;
  width: min(1800px, 100%);
  margin: 16px auto;
  padding: 0 32px;
  background: var(--md-default-bg-color);
  border-radius: 8px;
  box-shadow: 0 2px 8px hsla(var(--md-hue), 15%, 9%, 0.1);
  overflow: auto;
}

.program-faq h2 {
  font-size: 28.8px;
  font-weight: 700;
  margin-bottom: 24px;
  color: var(--md-default-fg-color);
  text-align: center;
}

.program-faq .sub-accordion {
  border-bottom: 1px solid hsla(var(--md-hue), 15%, 9%, 0.15);
  margin-bottom: 19.2px;
  max-width: 100%;
  transition: background-color 0.3s ease;
}

.program-faq .sub-accordion:hover {
  background-color: hsla(var(--md-hue), 15%, 9%, 0.02);
}

.program-faq .sub-accordion__title {
  font-size: 17.6px;
  font-weight: 600;
  padding: 19.2px 24px;
  color: var(--md-default-fg-color);
  cursor: pointer;
  display: flex;
  justify-content: space-between;
  align-items: center;
  transition: color 0.3s ease, background-color 0.3s ease;
  white-space: normal;
  word-wrap: break-word;
  line-height: 24px;
  border-radius: 6px;
}

.program-faq .sub-accordion__title:hover {
  color: #666;
  background-color: hsla(var(--md-hue), 15%, 9%, 0.05);
}

.program-faq .sub-accordion__title::after {
  content: '';
  display: inline-block;
  width: 24px;
  height: 24px;
  background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 16l6-6H6z" fill="%23666"/></svg>') no-repeat center;
  transition: transform 0.3s ease;
  flex-shrink: 0;
  margin-left: 16px;
}

.program-faq .sub-accordion__title:hover::after {
  background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 16l6-6H6z" fill="%23999"/></svg>') no-repeat center;
}

.program-faq .sub-accordion[open] .sub-accordion__title::after {
  transform: rotate(180deg);
}

/* Override Material for MkDocs default toggle icon */
.md-typeset details[open] > summary::after,
[dir=ltr] .md-typeset summary::after {
  display: none !important;
}

.program-faq .sub-accordion__body {
  padding: 19.2px 24px;
  font-size: 14.4px;
  color: var(--md-default-fg-color--light);
  line-height: 25.6px;
  white-space: normal;
  word-wrap: break-word;
  opacity: 0;
  animation: fadeIn 0.3s ease forwards;
}

@keyframes fadeIn {
  to {
    opacity: 1;
  }
}

/* Dark Mode: Adjustments for slate theme */
[data-md-color-scheme="slate"] {
  /* Commerce Message Dark Mode */
  .titaned-commerce-message {
    background: #2C2C2C; /* Secondary color */
    color: #FFFFFF; /* Accent color */
  }

  .titaned-commerce-message a {
    color: #EB5939; /* Highlight color */
  }

  .titaned-commerce-message a:hover {
    color: #FFFFFF; /* Accent color */
  }

  /* Search Block Dark Mode */
  .search-block .titaned-search-bar input {
    background: linear-gradient(135deg, #4a0000, #1a0000);
    color: #fff;
    border-color: #ff3333;
  }

  .search-block .titaned-search-bar::before {
    color: #ff6666;
  }

  .search-block .titaned-search-bar input:focus {
    border-color: #ff6666;
    box-shadow: 0 0 20px rgba(255, 51, 51, 0.3);
  }

  .search-block .csh-include-search {
    background: #1a0000;
    border-color: #ff3333;
    box-shadow: 0 10px 25px rgba(255, 51, 51, 0.2);
  }

  .search-block .csh-include-search-result a {
    color: #fff;
  }

  .search-block .csh-include-search-result a:hover,
  .search-block .csh-include-search-result a:focus {
    color: #ff6666;
    background-color: #330000;
  }

  /* Card Grid Dark Mode */
  .titaned-tile {
    background: #1e1e1e;
    border-color: #444;
  }

  .titaned-tile a {
    color: #fff;
  }

  .titaned-tile h3 {
    color: #fff;
  }

  .titaned-tile p {
    color: #bbb;
  }

  .titaned-tile__icon {
    background: transparent;
  }

  /* FAQ Section Dark Mode */
  .program-faq {
    background: var(--md-default-bg-color);
    box-shadow: 0 2px 8px hsla(var(--md-hue), 15%, 90%, 0.1);
  }

  .program-faq .sub-accordion {
    border-bottom: 1px solid hsla(var(--md-hue), 15%, 90%, 0.15);
  }

  .program-faq .sub-accordion:hover {
    background-color: hsla(var(--md-hue), 15%, 90%, 0.02);
  }

  .program-faq .sub-accordion__title {
    color: var(--md-default-fg-color);
  }

  .program-faq .sub-accordion__title:hover {
    color: #bbb;
    background-color: hsla(var(--md-hue), 15%, 90%, 0.05);
  }

  .program-faq .sub-accordion__title::after {
    background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 16l6-6H6z" fill="%23bbb"/></svg>') no-repeat center;
  }

  .program-faq .sub-accordion__title:hover::after {
    background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 16l6-6H6z" fill="%23ddd"/></svg>') no-repeat center;
  }

  .program-faq .sub-accordion__body {
    color: var(--md-default-fg-color--light);
  }
}

/* Responsive Adjustments: For mobile devices */
@media (max-width: 600px) {
  .titaned-commerce-message {
    font-size: 16px;
    padding: 16px;
    margin: 24px auto;
  }

  .titaned-commerce-message strong {
    font-size: 22px;
  }

  .search-block {
    max-width: 100%;
    margin-bottom: 60px;
    padding: 0 8px;
  }

  .search-block .titaned-search-bar input {
    height: 50px;
    padding: 16px 16px 16px 50px;
    font-size: 16px;
    border-radius: 20px;
  }

  .search-block .titaned-search-bar::before {
    left: 20px;
    font-size: 18px;
  }

  .search-block .csh-include-search {
    left: 8px;
    right: 8px;
    max-height: 300px;
  }

  .search-block .csh-include-search-result a {
    font-size: 14px;
    padding: 4px 8px;
  }

  /* .titaned-tile-grid {
    grid-template-columns: 1fr;
    grid-template-rows: auto;
  } */

  .titaned-tile {
    padding: 16px;
  }

  .titaned-tile__icon {
    width: 80px;
    height: 80px;
    margin-bottom: 12px;
  }

  .titaned-tile h3 {
    font-size: 18px;
  }

  .titaned-tile p {
    font-size: 14px;
  }

  .program-faq {
    padding: 0 16px;
    max-width: 100%;
    box-shadow: none;
  }

  .program-faq .sub-accordion__title {
    font-size: 16px;
    line-height: 22.4px;
    padding: 16px;
  }

  .program-faq .sub-accordion__body {
    font-size: 13.6px;
    padding: 16px;
  }
}
</style>

<script src="https://unpkg.com/fuse.js@6.6.2/dist/fuse.min.js"></script>
<script>
  // Hardcoded search data with improved structure
  const searchData = [
    { title: "TitanBI", url: "/TitanBi/TitanBi", content: "Course and learner analytics." },
    { title: "Studio", url: "/Studio/What_Is_Studio", content: "Create engaging courses." },
    { title: "LMS (Learner)", url: "/LMS/lms_home_page_overview", content: "Navigate courses and track learning." },
    { title: "LMS (Admin)", url: "/LMS_ADMIN/LMS_Administration_Overview", content: "Manage courses and users." },
    { title: "Live Tab Overview", url: "/LMS/Live_Tab_Overview", content: "Overview of the Live Tab in the LMS for learners." },
    { title: "Taking Notes", url: "/LMS/Taking_Notes", content: "Guide on taking notes within the LMS." },
    { title: "Wiki Overview", url: "/LMS/Wiki_Overview", content: "Overview of the Wiki feature in the LMS." },
    { title: "Learners Activity In LMS", url: "/LMS/What_Learners_Can_Do_overview", content: "Details on what learners can do in the LMS." },
    { title: "Instructor Course Overview", url: "/LMS_ADMIN/Instructor_Course_Overview", content: "Overview for instructors managing courses." },
    { title: "Sign UP and Sign In", url: "/LMS/Signup_and_Signin", content: "Instructions for signing up and signing in to the LMS." },
    { title: "Instructor Tab", url: "/LMS_ADMIN/Instructor_tab", content: "Details on the Instructor Tab features." },
    { title: "Membership", url: "/LMS_ADMIN/membership", content: "Information on membership management in the LMS." },
    { title: "Cohorts", url: "/LMS_ADMIN/Cohorts", content: "Guide to managing cohorts in the LMS." },
    { title: "Extensions", url: "/LMS_ADMIN/Extensions", content: "Details on extension features for the LMS." },
    { title: "Student Admin", url: "/LMS_ADMIN/Student_Admin", content: "Admin tools for managing students." },
    { title: "Data Download", url: "/LMS_ADMIN/Data_Download", content: "Instructions for downloading data from the LMS." },
    { title: "Special Exam Allowance", url: "/LMS_ADMIN/Special_Exam_Allowance", content: "Information on special exam allowances." },
    { title: "Certificates Management", url: "/LMS_ADMIN/Certificates_Management", content: "Guide to managing certificates in the LMS." },
    { title: "Open Response Assessments", url: "/LMS_ADMIN/Open_Response_Assessments", content: "Details on open response assessments." },
    { title: "Accessing Reports", url: "/LMS_ADMIN/Accessing_Reports", content: "How to access reports in the LMS." },
    { title: "Course Creator vs Admin", url: "/LMS_ADMIN/Course_Creator_and_Admin", content: "Comparison of course creator and admin roles." },
    { title: "LMS Administration Overview", url: "/LMS_ADMIN/LMS_Administration_Overview", content: "Comprehensive overview of LMS administration." }
  ];

  // Initialize Fuse.js
  const fuse = new Fuse(searchData, {
    keys: ['title', 'content'],
    threshold: 0.4,
    includeScore: true,
    minMatchCharLength: 2
  });

  // Search bar functionality with improved output
  const searchInput = document.getElementById('titaned-search');
  const resultsContainer = document.getElementById('titaned-search-results');

  searchInput.addEventListener('input', function(e) {
    const query = e.target.value.trim();
    resultsContainer.innerHTML = '';
    resultsContainer.classList.remove('active');

    if (query.length < 2) return;

    const results = fuse.search(query);
    if (results.length === 0) {
      resultsContainer.innerHTML = '<div class="csh-include-search-result">No results found.</div>';
    } else {
      results.slice(0, 10).forEach(result => {
        const item = result.item;
        const li = document.createElement('ul');
        li.role = "list";
        const listItem = document.createElement('li');
        listItem.role = "listitem";
        const a = document.createElement('a');
        a.href = item.url;
        a.setAttribute('onmouseenter', "CrispHelpdeskCommon.mouse_search_result(this, true)");
        a.setAttribute('onmouseleave', "CrispHelpdeskCommon.mouse_search_result(this, false)");
        a.setAttribute('data-active', "false");
        a.setAttribute('role', "button");
        a.setAttribute('aria-label', item.title);
        a.className = "csh-include-search-result";
        a.innerHTML = `<span class="csh-include-search-result-title csh-font-sans-semibold">${item.title}</span><br><span class="csh-include-search-result-description csh-text-ellipsis-multiline csh-text-ellipsis-multiline-lines-2">${item.content}</span>`;
        listItem.appendChild(a);
        li.appendChild(listItem);
        resultsContainer.appendChild(li);
      });
    }
    resultsContainer.classList.add('active');
  });

  // Hide results when clicking outside
  document.addEventListener('click', function(e) {
    if (!searchInput.contains(e.target) && !resultsContainer.contains(e.target)) {
      resultsContainer.classList.remove('active');
    }
  });

  // Autocomplete on Enter
  searchInput.addEventListener('keyup', function(e) {
    if (e.key === 'Enter' && resultsContainer.children.length > 0) {
      const firstResult = resultsContainer.querySelector('a');
      if (firstResult) window.location.href = firstResult.getAttribute('href');
    }
  });
</script>

<div class="titaned-tile-grid">
  <div class="titaned-tile">
    <a href="/documentation/TitanBi/TitanBi">
      <div class="titaned-tile__icon">
        <img src="homepage_images/titanbi.png" alt="TitanBI Analytics">
      </div>
      <div class="titaned-tile__text">
        <h3>TitanBI</h3>
        <p>Course and learner analytics.</p>
      </div>
    </a>
  </div>
  <div class="titaned-tile">
    <a href="/documentation/Studio/What_Is_Studio">
      <div class="titaned-tile__icon">
        <img src="homepage_images/studio.png" alt="Studio Course Creation">
      </div>
      <div class="titaned-tile__text">
        <h3>Studio</h3>
        <p>Create engaging courses.</p>
      </div>
    </a>
  </div>
  <div class="titaned-tile">
    <a href="/documentation/LMS/lms_home_page_overview">
      <div class="titaned-tile__icon">
        <img src="homepage_images/learner.png" alt="LMS Learner">
      </div>
      <div class="titaned-tile__text">
        <h3>LMS (Learner)</h3>  
        <p>Navigate courses and track learning.</p>
      </div>
    </a>
  </div>
  <div class="titaned-tile">
    <a href="/documentation/LMS_ADMIN/LMS_Administration_Overview">
      <div class="titaned-tile__icon">
        <img src="homepage_images/admin.png" alt="LMS Admin">
      </div>
      <div class="titaned-tile__text">
        <h3>LMS (Admin)</h3>
        <p>Manage courses and users.</p>
      </div>
    </a>
  </div>
  <div class="titaned-tile">
    <a href="documentation/faq">
      <div class="titaned-tile__icon">
        <img src="homepage_images/controlhub.png" alt="LMS Admin">
      </div>
      <div class="titaned-tile__text">
        <h3>Control Hub</h3>
        <p>Centralized Control for Efficient Platform Administration</p>
      </div>
    </a>
  </div>
  <div class="titaned-tile">
    <a href="documentation/faq">
      <div class="titaned-tile__icon">
        <img src="homepage_images/faqs-icon.png" alt="LMS Admin">
      </div>
      <div class="titaned-tile__text">
        <h3>FAQs</h3>
        <p>Find answers to common questions about using the platform.</p>
      </div>
    </a>
  </div>
</div>

---
title: "GT Movies Store"
---

<!-- Hide the site-wide banner on this page -->
<style>
  .page-header, .site-header { display: none !important; }
  .main-content { padding-top: 0 !important; }

  /* Project hero */
  .project-hero{
    background: linear-gradient(120deg,#2a7ae2,#17a2b8);
    color:#fff;
    text-align:center;
    padding:56px 16px;
    border-radius:6px;
    margin:0 0 24px;
  }
  .project-hero h1{
    color:#fff !important;   /* override theme */
    margin:0;
    font-size:2.2rem;
    font-weight:700;
  }

  /* Optional: nice spacing for back link */
  .back { display:inline-block; margin:12px 0 24px; }
</style>

<div class="project-hero"><h1>GT Movies Store</h1></div>

<a class="back" href="/">← Home</a>

## Project Description
**GT Movies Store** is a Django 5 web app built for CS 2340 at Georgia Tech. It lets people browse a movie catalog, search by title, view details and reviews, sign up/log in, add reviews, and manage purchases with a cart and orders. The goal was to turn a clear set of user stories into a working, easy-to-use site.

**How the user stories were satisfied:**
- **Discovery:** Home/About pages orient users; **Movies** index lists all titles with a **search** bar.
- **Accounts:** **Sign Up / Login / Logout** flows; actions like writing reviews or ordering require being signed in.
- **Details & Reviews:** Movie pages show full info; users can **create, edit, and delete** their own reviews and read others.
- **Cart & Orders:** Add/remove items, adjust quantities, and **checkout** to create an **order** with date/total and a viewable history.
- **Usability:** Responsive templates keep pages clean on different screen sizes; an **admin** area manages movies, reviews, users, and orders.

---

## Process Description
I followed *Django 5 for the Impatient* and Django’s **Model–View–Template (MVT)** structure:

- Defined models for **Movie**, **Review**, **Cart**, **Order**, etc.
- Built views/URLs and templates for pages.
- Implemented forms for creating/editing records; gated actions with user signup/login/logout.
- Used **Django Admin** to manage data while testing.
- Kept the UI simple and responsive with Bootstrap.

### Challenges & Notes
- **What was tricky:** There were many moments where my site looked drastically different from the book's example. This was often due to broken HTML lines in the code, etc.
- **How I solved it:** Reviewing the code carefully before deploying, and making use of Git Version Control.
- **If I had more time:** I would love to expand on the site by integrating data from the IMDb API.

---

## Video Demonstration
👉 🎬 **[Watch the demo](https://youtu.be/ocTHmeA8y00)**

<!-- Responsive YouTube embed -->
<div class="yt-container">
  <iframe
    src="https://www.youtube-nocookie.com/embed/ocTHmeA8y00"
    title="GT Movies Store demo"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    allowfullscreen>
  </iframe>
</div>

<style>
  .yt-container{
    position:relative; padding-bottom:56.25%; height:0; overflow:hidden;
    border-radius:8px; box-shadow:0 2px 12px rgba(0,0,0,.08); margin:12px 0 24px;
  }
  .yt-container iframe{
    position:absolute; top:0; left:0; width:100%; height:100%;
  }
</style>

## Tech Stack
Django 5 • Python • Bootstrap • Django Admin

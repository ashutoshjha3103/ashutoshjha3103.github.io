---
layout: page
title: Home
permalink: /
---

<style>
  /* Flexbox container to place text and image side-by-side */
  .hero-container {
    display: flex;
    align-items: center; /* Vertically centers the content */
    justify-content: space-between;
    gap: 3rem; /* Space between text and image */
    margin-top: 2rem;
  }

  /* Left column for text */
  .hero-text {
    flex: 1; /* Takes up the remaining space */
    font-size: 1.05rem;
    line-height: 1.6;
  }

  /* Right column for image */
  .hero-image-container {
    flex-shrink: 0; /* Prevents the image from shrinking */
  }

  /* The Photo Style */
  .profile-img {
    width: 280px;       
    height: 280px;
    object-fit: cover;  
    border-radius: 12px; 
    border: 3px solid #e1e4e8; 
    box-shadow: 0 8px 20px rgba(0,0,0,0.15); 
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }

  .profile-img:hover {
    transform: translateY(-5px); 
    box-shadow: 0 12px 25px rgba(0,0,0,0.2);
  }

  /* Dark mode overrides for the image border */
  body.dark-theme .profile-img {
    border-color: #444;
  }

  /* Mobile responsiveness: Stack image on top of text on small screens */
  @media (max-width: 768px) {
    .hero-container {
      flex-direction: column-reverse; /* Image moves to the top */
      text-align: center;
      gap: 2rem;
    }
  }
</style>

<div class="hero-container">
  
  <div class="hero-text" markdown="1">

### Welcome!

I am **Ashutosh Jha**, a Quantitative Data Scientist based in Tübingen, Germany.

An engineer at heart, I specialize in the intersection of **Quantitative Methods**, **Machine Learning** and **Financial Economics**. I leverage a strong foundation in software development to build rigorous, data-driven solutions and research training in my master's degree to further my research objectives.

* [Check out my Projects](/portfolio/)
* [Read more about my Experience](/about/)
* [Get in Touch](/contact/)

  </div>

  <div class="hero-image-container">
    <img src="/assets/profile.jpg" alt="Ashutosh Jha" class="profile-img">
  </div>

</div>
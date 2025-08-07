<template>
  <div class="home-wrapper">
    <div class="home-container">
      <img src="/assets/profile.jpg" alt="Profile Picture" class="profile-pic" />
      <div class="about-text">
        <h1>shinigami-777's Domain</h1>
        <p>
          Hey! I am Tamaghna, a passionate engineer from India. I like to learn about how things work.
        </p>
        <p>
          I am currently a Electronics Engineering Junior at IIT(BHU) Varanasi. I explore different things in my free time. I am particularly fond of Security, Cloud and Low Level System architecture. I am interested in Competitive Programming and have contributed to some open-source orgs as well. My most used languages are C++, Python, Golang, C, Java and Javascript.
        </p> 
      </div>
    </div>
  </div>
</template>


<style scoped>
/* Center the entire block in the page */
.home-wrapper {
  display: flex;
  justify-content: center;
}

/* Container for profile + text */
.home-container {
  border-radius: 12px;
  max-width: 800px;
}

/* Round profile picture */
.profile-pic {
  width: 160px;
  height: 160px;
  border-radius: 50%;
  object-fit: cover;
  margin-right: 30px;
  border: 3px solid #ccc;
}

/* Text content */
.about-text h1 {
  margin-bottom: 16px;
  font-family: monospace;
  color:rgba(36, 7, 68, 0.85); 
}

.about-text p {
  font-size: 1rem;
  font-family: monospace;
  line-height: 1.6;
  color:rgba(14, 2, 27, 0.85); 
}
</style>

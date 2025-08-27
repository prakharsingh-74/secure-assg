<template>
  <div class="hero-container">
   

    <!-- Hero Section -->
    <section class="hero-content">
      <div class="text-section">
        <h1>
          Lorem Ipsum is simply <br />
          dummy text of the <br />
          printing and typesetting.
        </h1>
        <p>
          Our products are fully custom-made, built with the latest technologies
          and cloud-architectures.
        </p>
        <button class="cta-btn">Get Started →</button>
      </div>

      <!-- Make SVG span full width -->
      <div class="rocket-bg-fixed">
        <img src="../assets/Mask Group 4.svg" alt="Rocket Background" />
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "HeroSection",
};
</script>

<style scoped>
.hero-container {
  background-color: #007bff;
  color: white;
  width: 100%;
  min-height: 100vh;
  position: relative;
  overflow-x: hidden; 
}

/* Navbar */
.navbar {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 32px 0 0 0;
  width: 100%;
  gap: 0;
}
.logo {
  color: #fff;
  font-size: 18px;
  font-weight: 400;
  font-family: 'Poppins', sans-serif;
  margin-right: 80px;
}
.nav-links {
  display: flex;
  gap: 36px;
  align-items: center;
}
.nav-links a {
  color: #fff;
  font-size: 15px;
  font-family: 'Poppins', sans-serif;
  font-weight: 400;
  text-decoration: none;
  transition: color 0.2s;
}
.nav-links a:hover {
  color: #e0e0e0;
}
.login-btn {
  margin-left: 36px;
  background: #fff;
  color: #222;
  border: none;
  border-radius: 6px;
  font-family: 'Poppins', sans-serif;
  font-size: 15px;
  font-weight: 400;
  padding: 8px 32px;
  box-shadow: 0 2px 8px 0 rgba(0,0,0,0.03);
  cursor: pointer;
  transition: background 0.2s, color 0.2s;
}
.login-btn:hover {
  background: #f0f0f0;
}

/* Hero Content */
.hero-content {
  display: flex;
  align-items: flex-start;
  justify-content: flex-start;
  position: relative;
  width: 100%;
  min-height: 420px;
  padding: 40px 0 0 12vw;
  box-sizing: border-box;
}

.text-section {
  max-width: 500px;
  z-index: 2; /* ensure text is above SVG */
}

.text-section h1 {
  font-size: 36px;
  line-height: 1.4;
  margin-bottom: 10px;
  font-weight: 700;
}

.text-section p {
  font-size: 15px;
  color: #cce0ff;
  margin-bottom: 25px;
}

.cta-btn {
  background-color: white;
  color: black;
  border: none;
  padding: 12px 28px;
  border-radius: 30px;
  font-weight: bold;
  cursor: pointer;
}

/* Make SVG span entire background edge-to-edge */
.rocket-bg-fixed {
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100vw;
  z-index: 0;
  pointer-events: none;
}
.rocket-bg-fixed img {
  width: 100vw;
  height: auto;
  display: block;
}
</style>

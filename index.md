---
layout: default
---

<style>
  body {
    background-color: #ffffff;
    color: #000000;
  }
  .project-bubble {
    background-color: #4682B4;
  }
  .associated-project a {
    background-color: rgba(255, 255, 255, 0.2);
  }
  .slideshow-container {
    display: none;
    position: fixed;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    width: 80%;
    height: 80%;
    background-color: rgba(0, 0, 0, 0.8);
    z-index: 1000;
  }
  .slideshow-content {
    position: relative;
    width: 100%;
    height: 100%;
  }
  .close-slideshow {
    position: absolute;
    top: 10px;
    right: 20px;
    color: white;
    font-size: 30px;
    cursor: pointer;
  }
</style>

<script
    type="module"
    src="https://cdn.jsdelivr.net/npm/@bufferhead/nightowl@0.0.14/dist/nightowl.js"
></script>

<a href="https://www.linkedin.com/in/breyon-bowman-729391237/" style="display: inline-block; background-color: #4682B4; color: white; text-decoration: none; padding: 10px 20px; border-radius: 25px; font-weight: bold;">LinkedIn Profile</a>

# About me

I am an enthusiastic cybersecurity professional with a solid background in network security, incident response, and vulnerability management. My journey in computer science has cultivated a deep passion for cybersecurity. I am eager to launch my professional career in this field, with a long-term goal of becoming a penetration tester.

<h2 style="text-align: center; margin-top: 50px; margin-bottom: 50px;">Projects</h2>

<style>
.project-bubble {
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #4682B4;
  color: white;
  padding: 10px;
  border-radius: 50%;
  width: 150px;
  height: 150px;
  margin: 10px;
  cursor: pointer;
  transition: all 0.3s ease;
  text-align: center;
  overflow: hidden;
  position: relative;
  box-shadow: 0 10px 20px rgba(0,0,0,0.19), 0 6px 6px rgba(0,0,0,0.23);
  transform: perspective(1000px) rotateY(0deg);
}

.project-bubble:hover {
  transform: perspective(1000px) rotateY(10deg) scale(1.1);
  background-color: rgba(0, 0, 0, 0.5);
}

.project-name {
  display: block;
  transition: opacity 0.3s ease;
}

.associated-project {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  opacity: 0;
  transition: opacity 0.3s ease;
}

.project-bubble:hover .associated-project {
  opacity: 1;
}

.project-bubble:hover .project-name {
  opacity: 0;
}

.associated-project a {
  color: white;
  text-decoration: none;
  font-size: 0.8em;
  padding: 5px;
  border-radius: 5px;
  background-color: rgba(0, 0, 0, 0.5);
  target: _blank; /* Added to open links in a new tab */
}

.project-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  perspective: 1000px;
}

.project-bubble:nth-child(odd) {
  transform: perspective(1000px) rotateY(-5deg) translateY(-10px);
}

.project-bubble:nth-child(even) {
  transform: perspective(1000px) rotateY(5deg) translateY(10px);
}

.project-bubble:hover {
  transform: perspective(1000px) rotateY(10deg) scale(1.1) translateY(0);
}
</style>

<script>
  function hideSlideshow() {
    document.getElementById('slideshow').style.display = 'none';
  }

  function loadRandomSlide() {
    const slides = [
      'https://docs.google.com/presentation/d/104vj63hCLHkrugQQTfK1Dd7oiMhas2HH2_lNUsSmCNk/edit#slide=id.g1e1e3a8c0d4_0_0',
      'https://docs.google.com/presentation/d/104vj63hCLHkrugQQTfK1Dd7oiMhas2HH2_lNUsSmCNk/edit#slide=id.g1e1e3a8c0d4_0_5',
      'https://docs.google.com/presentation/d/104vj63hCLHkrugQQTfK1Dd7oiMhas2HH2_lNUsSmCNk/edit#slide=id.g1e1e3a8c0d4_0_10'
    ];
    const randomSlide = slides[Math.floor(Math.random() * slides.length)];
    document.getElementById('slideContent').src = randomSlide;
  }
</script>

<div class="project-container">
  <div class="project-bubble">
    <span class="project-name">Updating a File Using Python</span>
    <div class="associated-project">
      <a href="https://docs.google.com/presentation/d/104vj63hCLHkrugQQTfK1Dd7oiMhas2HH2_lNUsSmCNk/edit#slide=id.p" target="_blank">Updating a File Using Python lab</a>
    </div>
  </div>

  <div class="project-bubble">
    <span class="project-name">Document an incident with an incident handler's journal</span>
    <div class="associated-project">
      <a href="https://docs.google.com/document/d/1zzNWQI49lH9ITrDKudjlw4stTf1I7yuZCtP2FJTDzK0/edit?resourcekey=0-zsGjrRjrrO7KNZuAUyZMOg" target="_blank">Incident handler's journal example</a>
    </div>
  </div>

  <div class="project-bubble">
    <span class="project-name">Vulnerability assessment report</span>
    <div class="associated-project">
      <a href="https://docs.google.com/document/d/1AsN7zZNlcRHzRmOQk43vi8Z-uJ_TSroLbJ_ci9qFQIo/edit?resourcekey=0-wFIjLbfogxxC3RqkiK02Wg" target="_blank">Vulnerability assessment report lab</a>
    </div>
  </div>

  <div class="project-bubble">
    <span class="project-name">Incident response execution</span>
    <div class="associated-project">
      <a href="https://docs.google.com/presentation/d/1BoN-haIWpvA5R5iYkNsq2a7nGKuK5lOv4adJcEHwMEE/edit#slide=id.g279c45888cd_0_36" target="_blank">Use the NIST Cybersecurity Framework to respond to a security incident lab</a>
    </div>
  </div>

  <div class="project-bubble">
    <span class="project-name">Use Linux commands to manage file permissions</span>
    <div class="associated-project">
      <a href="https://docs.google.com/document/d/1BCXBdrraCHh7w3FrnfMvs-FiOzDjWzsWIlFiUcTBME8/edit?resourcekey=0--jfRjUAXgWP7VlQLR32liw" target="_blank">File permissions in Linux lab</a>
    </div>
  </div>

  <div class="project-bubble">
    <span class="project-name">Conduct a security audit</span>
    <div class="associated-project">
      <a href="https://docs.google.com/document/d/1yi9OqjPmkz0-nPTWne3W0Jqnzct7HHyOgSKWU_dvSyA/edit" target="_blank">Controls and compliance checklist lab</a>
    </div>
  </div>
</div>

<div id="slideshow" class="slideshow-container">
  <div class="slideshow-content">
    <iframe id="slideContent" width="100%" height="100%" frameborder="0" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
  </div>
  <span class="close-slideshow" onclick="hideSlideshow()">&times;</span>
</div>

<h2 style="text-align: center;">Skills, Tools, and Certifications</h2>

<div style="text-align: center; margin: 20px 0;">
  <p>Proficiency indicator</p>
  <div id="proficiency-gauge" style="background: linear-gradient(to right, #ff0000, #ffff00, #00ff00); width: 200px; height: 20px; position: relative; margin: 0 auto;">
    <div id="moving-line" style="position: absolute; left: 0; width: 2px; height: 100%; background-color: white; cursor: pointer;"></div>
  </div>
</div>

<style>
@keyframes moveLineBackAndForth {
  0% { left: 0; }
  50% { left: calc(100% - 2px); }
  100% { left: 0; }
}

#moving-line {
  animation: moveLineBackAndForth 6s linear infinite;
}

#moving-line:hover {
  animation-play-state: paused;
}

.category-title {
  transition: font-size 0.3s ease;
}

.category-title:hover {
  font-size: 200%;
}

.category-content {
  transition: margin-top 0.3s ease;
}

.tool-link {
  transition: transform 0.3s ease;
  display: inline-block;
}

.tool-link:hover {
  transform: scale(1.2) translateX(10%);
}

.tool-gauge {
  transition: transform 0.3s ease;
}

.tool-gauge:hover {
  transform: scale(1.2) translateX(10%);
}

.tools-container {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}

.network-section {
  flex: 1;
  max-width: 45%;
}

.endpoint-section {
  flex: 1;
  max-width: 45%;
}

.siem-section {
  width: 100%;
  text-align: left;
  margin-top: 20px;
}

.certification-link {
  transition: transform 0.3s ease;
  display: inline-block;
}

.certification-link:hover {
  transform: scale(1.2);
}
</style>

<script>
document.addEventListener('DOMContentLoaded', (event) => {
  const gauge = document.getElementById('proficiency-gauge');
  const line = document.getElementById('moving-line');
  let isDragging = false;

  gauge.addEventListener('mousedown', (e) => {
    updateLinePosition(e);
    e.preventDefault();
  });

  line.addEventListener('mousedown', (e) => {
    isDragging = true;
    updateLinePosition(e);
    e.preventDefault();
    e.stopPropagation();
  });

  document.addEventListener('mousemove', (e) => {
    if (isDragging) {
      updateLinePosition(e);
    }
  });

  document.addEventListener('mouseup', () => {
    if (isDragging) {
      isDragging = false;
      line.style.animation = 'moveLineBackAndForth 6s linear infinite';
    }
  });

  function updateLinePosition(e) {
    const rect = gauge.getBoundingClientRect();
    let x = e.clientX - rect.left;
    x = Math.max(0, Math.min(x, rect.width - 2));
    line.style.left = `${x}px`;
    line.style.animation = 'none';
  }

  const categoryTitles = document.querySelectorAll('.category-title');
  categoryTitles.forEach(title => {
    title.addEventListener('mouseenter', () => {
      const content = title.nextElementSibling;
      content.style.marginTop = '20px';
    });
    title.addEventListener('mouseleave', () => {
      const content = title.nextElementSibling;
      content.style.marginTop = '0';
    });
  });
});
</script>

<div class="tools-container">
  <div class="network-section">
    <h3 class="category-title">Network</h3>
    <div class="category-content">
       <div class="tool-link">
         <a href="https://www.wireshark.org"><img src="https://img.shields.io/badge/-Wireshark-1679A7?&style=for-the-badge&logo=Wireshark&logoColor=white" /></a>
       </div>
       <div class="tool-gauge" style="margin-top: 5px; margin-bottom: 10px;">
         <div style="background: linear-gradient(to right, #ff0000, #ffff00, #00ff00); width: 100px; height: 10px; position: relative;">
           <div style="position: absolute; left: 70%; width: 2px; height: 100%; background-color: white;"></div>
         </div>
       </div>
       <div class="tool-link">
         <a href="https://suricata.io"><img src="https://img.shields.io/badge/-Suricata-EF3B2D?&style=for-the-badge&logo=Suricata&logoColor=white" /></a>
       </div>
       <div class="tool-gauge" style="margin-top: 5px; margin-bottom: 10px;">
         <div style="background: linear-gradient(to right, #ff0000, #ffff00, #00ff00); width: 100px; height: 10px; position: relative;">
           <div style="position: absolute; left: 20%; width: 2px; height: 100%; background-color: white;"></div>
         </div>
       </div>
       <div class="tool-link">
         <a href="https://zeek.org"><img src="https://img.shields.io/badge/-Zeek-777BB4?&style=for-the-badge&logo=Zeek&logoColor=white" /></a>
       </div>
       <div class="tool-gauge" style="margin-top: 5px; margin-bottom: 10px;">
         <div style="background: linear-gradient(to right, #ff0000, #ffff00, #00ff00); width: 100px; height: 10px; position: relative;">
           <div style="position: absolute; left: 20%; width: 2px; height: 100%; background-color: white;"></div>
         </div>
       </div>
    </div>
  </div>

  <div class="endpoint-section">
    <h3 class="category-title">Endpoint</h3>
    <div class="category-content">
       <div class="tool-link">
         <a href="https://www.microsoft.com/en-us/security/business/threat-protection/microsoft-defender-endpoint"><img src="https://img.shields.io/badge/-Microsoft_Defender_for_Endpoint-00A4EF?&style=for-the-badge&logo=Microsoft&logoColor=white" /></a>
       </div>
       <div class="tool-gauge" style="margin-top: 5px; margin-bottom: 10px;">
         <div style="background: linear-gradient(to right, #ff0000, #ffff00, #00ff00); width: 100px; height: 10px; position: relative;">
           <div style="position: absolute; left: 20%; width: 2px; height: 100%; background-color: white;"></div>
         </div>
       </div>
       <div class="tool-link">
         <a href="https://velociraptor.app"><img src="https://img.shields.io/badge/-Velociraptor-4B275F?&style=for-the-badge&logo=Velociraptor&logoColor=white" /></a>
       </div>
       <div class="tool-gauge" style="margin-top: 5px; margin-bottom: 10px;">
         <div style="background: linear-gradient(to right, #ff0000, #ffff00, #00ff00); width: 100px; height: 10px; position: relative;">
           <div style="position: absolute; left: 20%; width: 2px; height: 100%; background-color: white;"></div>
         </div>
       </div>
    </div>
  </div>

  <div class="siem-section">
    <h3 class="category-title">SIEM</h3>
    <div class="category-content">
       <div class="tool-link">
         <a href="https://azure.microsoft.com/en-us/services/azure-sentinel/"><img src="https://img.shields.io/badge/-Microsoft_Sentinel-0078D4?&style=for-the-badge&logo=Microsoft&logoColor=white" /></a>
       </div>
       <div class="tool-gauge" style="margin-top: 5px; margin-bottom: 10px;">
         <div style="background: linear-gradient(to right, #ff0000, #ffff00, #00ff00); width: 100px; height: 10px; position: relative;">
           <div style="position: absolute; left: 50%; width: 2px; height: 100%; background-color: white;"></div>
         </div>
       </div>
       <div class="tool-link">
         <a href="https://www.splunk.com"><img src="https://img.shields.io/badge/-Splunk-000000?&style=for-the-badge&logo=Splunk&logoColor=white" /></a>
       </div>
       <div class="tool-gauge" style="margin-top: 5px; margin-bottom: 10px;">
         <div style="background: linear-gradient(to right, #ff0000, #ffff00, #00ff00); width: 100px; height: 10px; position: relative;">
           <div style="position: absolute; left: 70%; width: 2px; height: 100%; background-color: white;"></div>
         </div>
       </div>
       <div class="tool-link">
         <a href="https://www.elastic.co"><img src="https://img.shields.io/badge/-Elastic-005571?&style=for-the-badge&logo=Elastic&logoColor=white" /></a>
       </div>
       <div class="tool-gauge" style="margin-top: 5px; margin-bottom: 10px;">
         <div style="background: linear-gradient(to right, #ff0000, #ffff00, #00ff00); width: 100px; height: 10px; position: relative;">
           <div style="position: absolute; left: 20%; width: 2px; height: 100%; background-color: white;"></div>
         </div>
       </div>
    </div>
  </div>
</div>

## Certifications
<div>
<span class="certification-link"><a href="https://coursera.org/share/bc6afea8abfe7bdd0f1dcda62a987cef"><img src="https://img.shields.io/badge/-Google_Security-FF0000?&style=for-the-badge&logo=Google&logoColor=white" /></a></span>
<span class="certification-link"><img src="https://img.shields.io/badge/-Security%2B-FF0000?&style=for-the-badge&logo=CompTIA&logoColor=white" /></span>
<span class="certification-link"><img src="https://img.shields.io/badge/-Network%2B-007ACC?&style=for-the-badge&logo=CompTIA&logoColor=white" /></span>
<span class="certification-link"><img src="https://img.shields.io/badge/-A%2B-4D4D4D?&style=for-the-badge&logo=CompTIA&logoColor=white" /></span>
<span class="certification-link"><img src="https://img.shields.io/badge/-CDSA-006400?&style=for-the-badge&logoColor=white" /></span>
<span class="certification-link"><img src="https://img.shields.io/badge/-CCD-000080?&style=for-the-badge&logoColor=white" /></span>
</div>

![Octocat]()

### Light shall come forth

![Branching](Screenshot 2023-12-02 205935.png)

<dl>
<dt>Name</dt>
<dd>Breyon Bowman</dd>
<dt>Born</dt>
<dd>Not born but created</dd>
<dt>Birthplace</dt>
<dd>Test tube</dd>
</dl>


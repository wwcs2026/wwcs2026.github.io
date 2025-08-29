<style>

 
  body {
    text-align: justify;
  }

.speaker-container {
  display: flex;
  flex-direction: column;
  gap: 2rem;
  margin-top: 2rem;
}

.speaker-card {
  display: flex;
  flex-direction: row; /* side-by-side layout */
  align-items: center;
  border: 1px solid #e0e0e0;
  border-radius: 12px;
  padding: 1.5rem;
  box-shadow: 0 4px 8px rgba(0,0,0,0.05);
  background-color: #fff;
  transition: transform 0.2s ease;
  text-align: left;
}

.speaker-card:hover {
  transform: translateY(-4px);
}

.speaker-photo {
  flex-shrink: 0;
  width: 160px; /* bigger square size */
  height: 160px;
  margin-right: 1.5rem;
  border-radius: 8px;
  overflow: hidden;
}

.speaker-photo img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.speaker-details h3 {
  margin: 0 0 0.5rem;
  font-size: 1.3rem;
}

.speaker-details p {
  margin: 0;
  color: #555;
  font-size: 0.85rem; /* smaller text */
  line-height: 1.5;
}

.speaker-link {
  text-decoration: none;
  color: inherit;
}
</style>

<p>We’re still finalizing our list of invited speakers, but once it’s ready, you will find a description of their work and research here. They’ll be sharing insights on exciting topics in complex systems science, from social science and network science to collective behavior and beyond.<br>
Stay tuned for updates!</p>

<div class="speaker-container">

  <a class="speaker-link" href="https://rafaelprietocuriel.com/home/" target="_blank">
    <div class="speaker-card">
      <div class="speaker-photo">
        <img src="/assets/image26/speakers/rafael.jpg" alt="Rafael picture">
      </div>
      <div class="speaker-details">
        <h3>Rafael Prieto-Curiel</h3>
        <p>
          Rafael Prieto-Curiel is a Faculty Member at the Complexity Science Hub, where he works on topics including violence, mobility, migration, and urban dynamics.
          He works for the OECD and the World Bank, conducting spatial and demographic analyses of cities. He is the Scientific Advisor of Aleph.
          In 2024, he was awarded the “Science Breakthrough” award by the Falling Walls Foundation.<br>
          Previously, he was at the Mathematical Institute of the University of Oxford, working on urban dynamics as part of the Peak Urban project. He earned an MSc in Statistics and a PhD in Mathematics and Security and Crime at UCL.
          He also worked in the Emergency Attention Centre in Mexico City (C5) as Director of Strategic Analysis, where his work primarily consisted of crime forecasting and police and resource allocation.
        </p>
      </div>
    </div>
  </a>

</div>

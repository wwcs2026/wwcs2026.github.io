<style>
.sponsor-container {
  display: flex;
  flex-direction: column;
  gap: 2rem;
  margin-top: 2rem;
}

.sponsor-card {
  display: flex;
  flex-direction: column;
  align-items: center;
  border: 1px solid #e0e0e0;
  border-radius: 12px;
  padding: 1.5rem;
  box-shadow: 0 4px 8px rgba(0,0,0,0.05);
  background-color: #fff;
  transition: transform 0.2s ease;
  text-align: center;
}

.sponsor-card:hover {
  transform: translateY(-4px);
}

.sponsor-logo {
  max-width: 250px;
  margin-bottom: 1rem;
}

.sponsor-logo img {
  width: 100%;
  height: auto;
  object-fit: contain;
}

.sponsor-details h3 {
  margin: 0 0 0.5rem;
  font-size: 1.3rem;
}

.sponsor-details p {
  margin: 0;
  color: #555;
  font-size: 0.95rem;
}

.sponsor-link {
  text-decoration: none;
  color: inherit;
}
</style>

<div class="sponsor-container">

  <a class="sponsor-link" href="https://www.uib.eu/" target="_blank">
    <div class="sponsor-card">
      <div class="sponsor-logo">
        <img src="/assets/image26/sponsors/uib.png" alt="University of the Balearic Islands logo">
      </div>
      <div class="sponsor-details">
        <h3>University of the Balearic Islands</h3>
        <p>The UIB is a cutting-edge university for teaching and research. It has deep roots in the region and is committed to society, sowing values that honour humanity with an ever-increasing international calling.</p>
      </div>
    </div>
  </a>

  <a class="sponsor-link" href="https://ifisc.uib-csic.es/en/" target="_blank">
    <div class="sponsor-card">
      <div class="sponsor-logo">
        <img src="/assets/image26/sponsors/ifisc.jpeg" alt="IFISC logo">
      </div>
      <div class="sponsor-details">
        <h3>IFISC (Institute for Cross-Disciplinary Physics and Complex Systems)</h3>
        <p>IFISC is a joint research institute of the University of the Balearic Islands (UIB) and the Spanish National Research Council (CSIC) whose mission is to develop Cross-Disciplinary and Strategic Research in complex systems following the established scientific approach of physicists.</p>
      </div>
    </div>
  </a>
    
  <!--<a class="sponsor-link" href="https://www.fundacionsicomoro.org/" target="_blank">
    <div class="sponsor-card">
      <div class="sponsor-logo">
        <img src="/assets/image24/sicomoro.png" alt="Fundación Sicomoro logo">
      </div>
      <div class="sponsor-details">
        <h3>Fundación Sicomoro</h3>
        <p>Fundación Sicómoro is a non-profit organization dedicated to the study and application of General Systems Theory. Leveraging an interdisciplinary approach, their mission is to develop collective knowledge that enhances societal understanding and decision-making.</p>
      </div>
    </div>
  </a>-->

</div>

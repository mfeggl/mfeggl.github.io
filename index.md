---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
list_title: "Recent News"
---

<style>
  .feature-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
    gap: 1rem;
    justify-items: center;
    align-items: start;
    margin: 2rem 0;
  }

  .feature-item img {
    width: 250px;
    height: 120px;
    object-fit: cover;
    border-radius: 8px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.1);
  }
  /* --- NEW: center all text inside each feature-item --- */
  .feature-item {
    text-align: center;
  }

  /* --- NEW: style your intro copy --- */
  .intro {
    text-align: center;
    max-width: 600px;      /* optional, to avoid super-wide lines */
    margin: 0 auto 2rem;   /* center + bottom spacing */
  }
</style>

I am currently a La Caixa Junior Leader Fellow at the Institute of Neuroscience, Alicante. My research interests are a bit eclectic, ranging from optimal control theory, computational neuroscience to machine learning. 

<div class="feature-grid">
  <a class="feature-item" href="/fluids/">
    <img src="/assets/Pictures/Fluids.png" alt="Fluids" />
    <h3>Fluids</h3>
  </a>
  <a class="feature-item" href="/Synapses/">
    <img src="/assets/Pictures/Synapses.png" alt="Computational Neuroscience" />
    <h3>Computational Neuroscience</h3>
  </a>
  <a class="feature-item" href="/Imaging/">
    <img src="/assets/Pictures/MRI.png" alt="Imaging Neuroscience" />
    <h3>Imaging Neuroscience</h3>
  </a>
</div>

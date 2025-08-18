---
---
# The Composites and Advanced Materials Processing Lab

CAMP Lab is a research group at [TU Delft (NL)](https://www.tudelft.nl/en/) focusing on advanced materials processing and composite structures. The group is led by [Prof. Baris Caglar](members/baris-caglar), and is part of the [Aerospace Structures and Materials department from the Faculty of Aerospace Engineering](https://www.tudelft.nl/en/ae/organisation/departments/aerospace-structures-and-materials).

At CAMP Lab, our research focuses on sustainable composites and their manufacturing through resource and energy efficient processing enabled by data-driven approaches. The three main pillars of our research are:
- **Resource-efficient** advanced composites based on unidirectional thermoplastic tapes 
- **Energy-efficient** processing of thermoset-based advanced composites through frontal polymerization
- **Data-driven** approaches for improved process design and control through the use state-of-the-art AI models


{% include section.html %}

## Highlights

<div class="glider-container">
  <div class="glide">
    <div class="glide__track" data-glide-el="track">
      <div class="glide__slides">
        {% include project-list.html data="projects" component="project-excerpt" glider=true style="slide" filter="!end_date"%}
      </div>
    </div>
    <!-- arrows from https://github.com/glidejs/glidejs.com/blob/master/resources/templates/partials/hero/hero.html -->
    <div class="slider__arrows" data-glide-el="controls">
      <button class="slider__arrow slider__arrow--prev glide__arrow glide__arrow--prev" data-ref="fadereveal[el]" data-glide-dir="<">
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24">
          <path d="M0 12l10.975 11 2.848-2.828-6.176-6.176H24v-3.992H7.646l6.176-6.176L10.975 1 0 12z"/>
        </svg>
      </button>
      <button class="slider__arrow slider__arrow--next glide__arrow glide__arrow--next" data-ref="fadereveal[el]" data-glide-dir=">">
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24">
          <path d="M13.025 1l-2.847 2.828 6.176 6.176h-16.354v3.992h16.354l-6.176 6.176 2.847 2.828 10.975-11z"/>
        </svg>
      </button>
    </div>
  </div>
</div>
<script src="https://cdn.jsdelivr.net/npm/@glidejs/glide"></script>
<script>
  const glide = new Glide('.glide', {
    type: "carousel",
    perView: 2,
    breakpoints: {
      600: { perView: 1 },
      1200: { perView: 2 }
    },
    autoplay: 2000,
    hoverpause: true
  }).mount()
</script>

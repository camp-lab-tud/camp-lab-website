---
---
# The Composites and Advanced Materials Processing Lab

CAMP Lab is a research group at [TU Delft (NL)](https://www.tudelft.nl/en/) focusing on advanced materials processing and composite structures. The group is led by [Prof. Baris Caglar](members/baris-caglar), and is part of the [Aerospace Structures and Materials department from the Faculty of Aerospace Engineering](https://www.tudelft.nl/en/ae/organisation/departments/aerospace-structures-and-materials).

At CAMP Lab, our research advances sustainable, high-performance composite manufacturing by combining AI-driven digitalization with next-generation materials and processing routes. Our work is organized around two main pillars:

**Sustainable Composites** - Resource- and energy-efficient manufacturing enabled through frontal polymerization, biobased composites, and thermoplastic tapes, aimed at reducing the environmental footprint of high-performance structures.

**AI and Digitalization** - Data-driven approaches for improved process design, monitoring, and control, leveraging state-of-the-art AI and machine learning models to accelerate the development and optimization of composite manufacturing processes.


{% include section.html %}

## Highlights

<div class="glider-container">
  <div class="glide">
    <div class="glide__track" data-glide-el="track">
      <div class="glide__slides">
        {% include project-list.html data="projects" component="project-excerpt" glider=true style="slide" filter="!end_date"%}
      </div>
    </div>
    <div class="glide__arrows" data-glide-el="controls">
      <button class="glide__arrow glide__arrow--left" data-glide-dir="<">{% include icon.html icon="fa-solid fa-arrow-left" %}</button>
      <button class="glide__arrow glide__arrow--right" data-glide-dir=">">{% include icon.html icon="fa-solid fa-arrow-right" %}</button>
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
    autoplay: 5000,
    hoverpause: true,
    focusAt: "center"
  }).mount()
</script>

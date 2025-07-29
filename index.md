---
---
# The Composites and Advanced Materials Processing Lab

CAMP Lab is a research group at [TU Delft (NL)](https://www.tudelft.nl/en/) focusing on advanced materials processing and composite structures. The group is led by [Prof. Baris Caglar](members/baris-caglar), and is part of the [Aerospace Structures and Materials department from the Faculty of Aerospace Engineering](https://www.tudelft.nl/en/ae/organisation/departments/aerospace-structures-and-materials).

{% include section.html %}

## Highlights

<div class="glide">
  <div class="glide__track" data-glide-el="track">
    <ul class="glide__slides">
      {% include project-glider.html data="projects" component="project-excerpt" filter="!end_date"%}
    </ul>
  </div>
  <div class="glide__arrows" data-glide-el="controls">
    <button class="glide__arrow glide__arrow--left" data-glide-dir="<">{% include icon.html icon="fa-solid fa-arrow-left" %}</button>
    <button class="glide__arrow glide__arrow--right" data-glide-dir=">">{% include icon.html icon="fa-solid fa-arrow-right" %}</button>
  </div>
</div>
<script src="https://cdn.jsdelivr.net/npm/@glidejs/glide"></script>
<script>
  const config = {
    type: "carousel",
    perView: 2,
    breakpoints: {
      600: {
        perView: 2
      }
    }
  }
  new Glide('.glide', config).mount()
</script>
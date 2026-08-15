---
show: true
group: Moments
width: 12
date: 2026-08-15 00:01:00 +0800
images:
- /assets/images/photos/showcase/moment-01.jpg
- /assets/images/photos/showcase/moment-02.jpg
- /assets/images/photos/showcase/moment-03.jpg
- /assets/images/photos/showcase/moment-04.jpg
- /assets/images/photos/showcase/moment-05.jpg
- /assets/images/photos/showcase/moment-06.jpg
- /assets/images/photos/showcase/moment-07.jpg
- /assets/images/photos/showcase/moment-08.jpg
- /assets/images/photos/showcase/moment-09.jpg
- /assets/images/photos/showcase/moment-10.jpg
- /assets/images/photos/showcase/moment-11.jpg
- /assets/images/photos/showcase/moment-12.jpg
- /assets/images/photos/showcase/moment-13.jpg
---

<div class="p-3">
  <h5 class="mb-2">Moments</h5>
  <p class="small text-muted mb-3">
    A few snapshots from my master's and Ph.D. journey: people, places, classes, and ordinary days along the way.
  </p>

  <div class="row">
    {% for image in page.images %}
    <div class="col-6 col-md-4 col-lg-3 mb-3">
      <img
        data-src="{{ image | relative_url }}"
        class="lazy w-100 rounded-sm"
        src="{{ '/assets/images/empty_300x200.png' | relative_url }}"
        style="aspect-ratio: 4 / 3; object-fit: cover;"
        alt="Moment from academic life">
    </div>
    {% endfor %}
  </div>
</div>

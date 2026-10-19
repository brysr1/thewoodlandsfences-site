---
title: Contact & Free Estimate
description: Request a free fence estimate from 76 Fence of The Woodlands. 1401 Lake Plaza Dr, Suite 200, Spring, TX 77389. Open 7 days, 7 AM to 7 PM. Call or text (713) 331-9385.
permalink: /contact/
no_cta: true
---

{% include hero.html small=true eyebrow="Contact" title="Request a free estimate" lede="Call, text, book online, or send the form. We'll come out, walk the line, and send a written quote." image="/assets/images/fences/walk-gate-cedar.jpg" alt="New cedar walk gate in a privacy fence" %}

<section class="fx-band">
  <div class="fx-container fx-contact-grid">
    <div>
      {% include eyebrow.html text="Reach us" %}
      <h2>{{ site.business.name }}</h2>
      <p><strong>Phone &amp; text:</strong> <a href="tel:{{ site.business.phone_tel }}">{{ site.business.phone }}</a></p>
      <p><strong>Office:</strong> {{ site.business.street }}<br>{{ site.business.city }}, {{ site.business.state }} {{ site.business.zip }}</p>
      <p><strong>Hours:</strong> {{ site.business.hours_text }}</p>
      <div class="fx-btn-row">
        <a class="fx-btn fx-btn-red" href="{{ site.business.book_url }}">Book a Free Estimate</a>
        <a class="fx-btn fx-btn-navy" href="tel:{{ site.business.phone_tel }}">Call {{ site.business.phone }}</a>
      </div>
      <div class="fx-map"><iframe src="https://www.google.com/maps?q=1401+Lake+Plaza+Dr+Suite+200,+Spring,+TX+77389&amp;output=embed" loading="lazy" referrerpolicy="no-referrer-when-downgrade" title="Map of 76 Fence of The Woodlands, 1401 Lake Plaza Dr, Spring, TX"></iframe></div>
      <p class="fx-note">We serve The Woodlands, Spring, Porter, New Caney, Splendora, Kingwood, Atascocita, Humble, and Huffman. <a href="{{ '/service-areas/' | relative_url }}">See service areas</a>.</p>
    </div>
    <form class="fx-form" action="{{ site.business.form_action }}" method="POST">
      <input type="hidden" name="_subject" value="New lead from thewoodlandsfences.com">
      <input type="hidden" name="location" value="The Woodlands">
      <div class="fx-two">
        <label>Name<input type="text" name="name" autocomplete="name" required></label>
        <label>Phone<input type="tel" name="phone" autocomplete="tel" required></label>
      </div>
      <label>Email (optional)<input type="email" name="email" autocomplete="email"></label>
      <label>Address or neighborhood<input type="text" name="address" autocomplete="street-address" placeholder="e.g. Alden Bridge, or a street address"></label>
      <label>What do you need?
        <select name="service">
          <option>New fence</option>
          <option>Fence replacement</option>
          <option>Repair</option>
          <option>Gate or gate opener</option>
          <option>Staining or power washing</option>
          <option>Commercial or HOA project</option>
          <option>Something else</option>
        </select>
      </label>
      <label>Message<textarea name="message" required placeholder="Tell us about the property and the fence you have in mind."></textarea></label>
      <button class="fx-btn fx-btn-red" type="submit">Send request</button>
    </form>
  </div>
</section>

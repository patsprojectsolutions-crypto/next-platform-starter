<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Pat’s Project Solutions — The solution to your project.</title>
  <meta name="description" content="Remodeling, renovations, siding, windows, doors, decks, kitchens, bathrooms, and more across Upstate SC." />
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header class="wrap header">
    <div>
      <h1>Pat’s Project Solutions</h1>
      <p class="tagline">The solution to your project.</p>
      <p class="sub">
        Serving Upstate SC — Greenville, Spartanburg, Anderson + surrounding areas
      </p>
    </div>

    <div class="cta">
      <a class="btn" href="tel:18647483815">Call/Text: (864) 748-3815</a>
      <a class="btn secondary" href="mailto:patsprojectsolutions@gmail.com">Email Pat</a>
      <a class="btn ghost" href="#estimate">Request an Estimate</a>
    </div>
  </header>

  <main class="wrap">
    <section class="card">
      <h2>About Pat</h2>
      <p>
        At <strong>Pat’s Project Solutions</strong>, you’re not just hiring a contractor — you’re partnering with someone
        who believes every project deserves a tailored solution. I’m Pat, and I bring hands-on expertise and a commitment
        to quality to every renovation and remodel. From kitchens and bathrooms to exteriors and full-home updates, I’m
        here to make your vision a reality with a straightforward, friendly approach. Whatever the project, I’ve got the solution.
      </p>
    </section>

    <section class="card">
      <h2>Services</h2>
      <div class="grid">
        <div>
          <h3>Exterior</h3>
          <ul>
            <li>Siding repair & replacement</li>
            <li>Window installation & replacement</li>
            <li>Interior & exterior doors</li>
            <li>Deck builds, repairs & upgrades</li>
          </ul>
        </div>
        <div>
          <h3>Renovations & Remodels</h3>
          <ul>
            <li>Kitchens (partial or full remodels)</li>
            <li>Bathrooms (partial or full remodels)</li>
            <li>Flooring (tile, LVP, laminate, hardwood)</li>
            <li>Drywall, trim, painting, and more</li>
          </ul>
        </div>
      </div>
      <p class="note">
        Don’t see your project listed? <strong>If you have the project, I’ll help you with the solution.</strong>
      </p>
    </section>

    <section class="card" id="estimate">
      <h2>Request an Estimate & Consultation</h2>
      <p class="sub">
        Fill this out and Pat will reply with questions, ideas, and next steps.
        <br><strong>Tip:</strong> include photos and measurements if you can.
      </p>

      <!-- FREE email form via FormSubmit (no account needed) -->
      <form id="estimateForm" action="https://formsubmit.co/patsprojectsolutions@gmail.com" method="POST">
        <!-- FormSubmit settings -->
        <input type="hidden" name="_subject" value="New Estimate Request — Pat’s Project Solutions" />
        <input type="hidden" name="_captcha" value="false" />
        <!-- Optional: after submit, redirect to your site section -->
        <input type="hidden" name="_next" value="" />

        <div class="formGrid">
          <label>
            Your Name*
            <input name="name" required placeholder="Jane Smith" />
          </label>

          <label>
            Email*
            <input name="email" type="email" required placeholder="jane@email.com" />
          </label>

          <label>
            Phone (optional)
            <input name="phone" placeholder="(864) 555-1234" />
          </label>

          <label>
            City / Area
            <input name="area" placeholder="Greenville / Spartanburg / Anderson / etc." />
          </label>

          <label>
            Project Type*
            <select name="project_type" required>
              <option value="">Select…</option>
              <option>Exterior siding</option>
              <option>Windows</option>
              <option>Doors</option>
              <option>Deck</option>
              <option>Kitchen remodel</option>
              <option>Bathroom remodel</option>
              <option>Flooring</option>
              <option>Full/partial renovation</option>
              <option>Other</option>
            </select>
          </label>

          <label>
            Budget Range (optional)
            <select name="budget">
              <option value="">Select…</option>
              <option>Under $1,000</option>
              <option>$1,000–$5,000</option>
              <option>$5,000–$15,000</option>
              <option>$15,000–$30,000</option>
              <option>$30,000+</option>
            </select>
          </label>

          <label class="full">
            Project Details*
            <textarea name="details" required placeholder="Describe what you want done. Include measurements and timeline if you have them."></textarea>
          </label>
        </div>

        <button class="btn" type="submit">Send Request to Pat</button>
        <p class="fineprint">
          Estimate requests are informational. Final pricing depends on details and verification.
        </p>
      </form>

      <div class="quickLinks">
        <a class="btn secondary" href="sms:18647483815">Text Pat</a>
        <a class="btn ghost" href="mailto:patsprojectsolutions@gmail.com?subject=Estimate%20Request%20-%20Pat%E2%80%99s%20Project%20Solutions">Email With Photos</a>
      </div>
    </section>

    <section class="card">
      <h2>Photos (Coming Soon)</h2>
      <p class="sub">You can add before/after pics here once you have a few.</p>
      <div class="gallery">
        <div class="ph">Project Photo</div>
        <div class="ph">Project Photo</div>
        <div class="ph">Project Photo</div>
      </div>
    </section>
  </main>

  <footer class="wrap footer">
    <div><strong>Pat’s Project Solutions</strong> — The solution to your project.</div>
    <div class="sub">Call/Text: (864) 748-3815 · Email: patsprojectsolutions@gmail.com</div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
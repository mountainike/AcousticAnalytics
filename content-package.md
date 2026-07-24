# Acoustic Analytics — Content Package for Mobirise

Copy/paste source for rebuilding the site in Mobirise. Organized by page, in the order
content should appear top-to-bottom. Suggested Mobirise block types are noted in
[brackets] — swap for whichever block styles you like visually.

Photos needed (from your WordPress media library) are called out inline as
**[PHOTO NEEDED: ...]** — grab these from your existing site before you start, since
Mobirise will want an image file for each of these blocks.

---

## Global elements (same on every page)

**Site title:** Acoustic Analytics
**Tagline:** Outdoor Warning & Acoustic Consulting

**Nav menu:** Home / Services / Modeling / Measurements / Documents / About / Contact

**Footer:**
© 2026 Acoustic Analytics LLC — Asheville, NC
contact@AcousticAnalytics.com

---

## PAGE: Home (index)

**[Header/Hero block]**
- Eyebrow: Est. sound propagation modeling
- Headline: Be sure you're heard.
- Body: With over 25 years of experience in outdoor warning system design, testing, and analysis, Acoustic Analytics makes sure your emergency message reaches the people who need it most — with modeling that accounts for real terrain, land cover, and atmospheric conditions.
- Buttons: "View services" → services page · "Contact us" → contact page
- **[PHOTO NEEDED: siren/horn banner image — the wide shot of siren horns against the sky used at the top of the original homepage]**

**[Text block]**
Headline: Outdoor warning systems are what we do.

With over 25 years of experience in the design, testing, and outdoor warning system analysis, Acoustic Analytics makes sure your emergency message reaches the people who need it most. Specifically, our advanced acoustic modeling tools calculate sound propagation across real terrain, accounting for elevation, land cover, and atmospheric conditions to give you an accurate picture of true siren coverage.

Staying compliant with FEMA guidelines is critical for municipalities, utilities, and nuclear facilities alike. To that end, we analyze your existing siren network against FEMA coverage standards, identifying gaps where populations may not receive adequate warning. By combining acoustic modeling with US Census population data, we pinpoint exactly where sirens are most needed — helping you prioritize investments and demonstrate compliance with confidence.

Whether you need a full system analysis, coverage verification, or help designing a new outdoor warning system from scratch, Acoustic Analytics provides the precise, defensible analysis that emergency planners trust.

*Learn about all aspects of outdoor warning systems, from the science behind the sound to the important regulatory documents. Click below to find out more.*

**[3-column feature/card block]**
1. **Acoustic Modeling** — Details about sound propagation and how computer modeling works. → links to Modeling page
   **[PHOTO NEEDED: the green/yellow coverage contour map screenshot]**
2. **Outdoor Measurements** — Learn about the different types of measurements available. → links to Measurements page
   **[PHOTO NEEDED: mic-in-the-field photo, or a second field shot]**
3. **Key Documents** — A library of some of the most crucial documents. → links to Documents page
   **[PHOTO NEEDED: bookshelf photo]**

**[CTA band]**
Headline: Need help with sirens? We are the experts.
Button: Contact Us → contact page

---

## PAGE: Services

**[Page header block]**
Headline: Services

**[4-column card block]**
1. **Background noise measurements**
   We have extensive experience with measuring the ambient noise in all kinds of environments, from remote desert trails to the middle of an urban environment. Long and short term measurements are all part of what we do.
   Sub-line: Learn what your background noise levels are.
   **[PHOTO NEEDED: AmbientNoise photo — mic/tripod outdoors]**

2. **Siren source characterization**
   We have experience measuring all types of sirens, following the ANSI S12.14 standard as well as other types of measurements, both near field and far field. Let us help you understand exactly how your sirens are performing.
   Sub-line: How loud are your sirens?
   **[PHOTO NEEDED: SirenMeasurements photo]**

3. **Acoustic Modeling**
   We are experts at acoustic modeling, using the latest noise models. From siren coverage analysis to community noise planning, we've got the tools to calculate the noise environment.
   Sub-line: Acoustic modeling can save money and time.
   **[PHOTO NEEDED: SirenModel photo]**

4. **Industrial Noise**
   Field measurements of industrial noise environments can help with OSHA requirements and improve the health (and hearing!) of your employees.
   Sub-line: How loud is your facility?
   **[PHOTO NEEDED: SaudiSLM photo]**

**[CTA band]**
Headline: Contact us for all your acoustic needs. We are experts!
Button: Contact Us → contact page

---

## PAGE: Modeling

**[Page header block]**
Eyebrow: Acoustic models for calculating coverage
Headline: Modeling
Body: Computers running acoustic models are the best way to determine the coverage of your sirens. There is a wide number of acoustic models that range from simple spreadsheets to complex computational models. However, all models share some basic principles. There are also several different software packages that can be used to compute your coverage contours.

**[PHOTO NEEDED: GoogleEarthSirens image]**

**[Text section: "Acoustical Principles"]**
There are several basic acoustic principles that govern all sound propagation:
- **Spherical Spreading** — The loss of acoustical energy as the sound spreads out from the source.
- **Atmospheric Absorption** — The absorption of acoustical energy by the air between the source and the receiver.
- **Ground Reflections** — Sounds we hear come directly from the source, and are reflected off of the ground.
- **Diffraction** — The 'bending' of sound around obstructions.
- **Refraction** — The 'bending' of sound due to gradients in temperature and/or wind.

**[Text section: "Propagation Algorithms"]**
Different acoustic models handle the basic acoustic principles differently, with some providing more detail than others, in increasing levels of complexity:
- **Outdoor Sound Propagation Model (OSPM)** — Included because it has been used in the past for some siren system design. No information is available about the inner workings of this model.
- **CONCAWE** — An older, largely heuristic model developed to calculate industrial noise generated by petroleum and petrochemical complexes.
- **ISO 9613** — An international algorithm for propagating industrial noise. Uses simplistic formulas and table look-ups, generally assumes down-wind propagation, and is designed to be conservative (tends to over-predict received sound level).
- **Nord2000** — A modern propagation algorithm that includes a more complex propagation system, atmospheric turbulence, and more complex barrier definitions.
- **Computational Models** — New and updated models are always being investigated; they often have shockingly complex data input requirements.

**[Text section: "Software Packages"]**
Acoustic Analytics has developed our own custom build software that uses Google Earth as the interface and Nord2000 as the propagation algorithm, specifically designed to rapidly develop and display siren contours. There are also several commercial software packages:
- **SoundPLAN** — Designed for computing the noise of a large number of sources spread out over a wide area. Includes CONCAWE, ISO 9613, Nord2000, plus many others. Well suited to full siren system calculations, but complex and cumbersome for quick what-if calculations.
- **CadnaA** — A similar software package to SoundPLAN, used in Europe to compute city-wide noise footprints, with an equal level of complexity.

**[CTA band]**
Headline: Need help with sirens? We are experts!
Button: Contact Us → contact page

---

## PAGE: Measurements

**[Page header/banner block]**
Headline: Measurements
Subhead: The do's and don'ts of outdoor sound measurements
**[PHOTO NEEDED: sky/siren banner photo used at top of this page]**

**[Text + photo side-by-side block]**
We love outdoor sound measurements – nothing better than getting outside to do our work. But we always tell clients, don't ask questions if you are not prepared for the answers. Acoustic data, collected in the field, is often messy with potentially confusing results (as opposed to computer modeling). However, nothing will give you better ground truth than physical measurements. Below are several of the types of field measurements that can be performed, and what you could expect from the results. And feel free to contact us to learn more about outdoor sound measurements and how they can help.

**[PHOTO NEEDED: BruceWithMic photo — you in the field with hard hat and mic]**

**[Table block: "Field Measurement Guide"]**

| Data you want | How to get it | What to watch for |
|---|---|---|
| Siren Source Levels | Conduct a formal source characterization following the ANSI S12.14 protocol. | Source levels may not be what you expect. |
| Background sound levels | Conduct field measurements, following ANSI S12.9 Part 2 | These measurements are designed to be taken over a long period of time, over a wide area. The longer and wider, the better. |
| Industrial noise levels | Conduct field measurements, following ANSI S12.9 Part 3. | Depending on the situation, you need to ensure you can isolate the specific noise elements you are trying to analyze. |
| Check the contour edge / Verifying model predictions | Conduct field measurements, following ANSI S12.9 Part 3. | A popular but risky type of measurement that can produce confusing results — atmospheric conditions can make some locations read high and others low. Collect as much data as possible and look for the average within the spread. |

**[CTA band]**
Headline: Need help with sirens? We are experts!
Button: Contact Us → contact page

---

## PAGE: Documents

**[Page header block]**
Headline: Documents
Body: A collection of key documents that govern the design, testing, and regulation of outdoor warning systems.

**[Text block]**
The history of outdoor warning sirens began with church bells used to warn the local population about an urgent need such as fire or flood. These then transitioned to early civil defense sirens used to warn the public of impending attack, then expanded to include weather warnings for tornadoes. It wasn't until the near disaster at Three-Mile Island that federal regulations governing siren systems were developed. Today, the only regulatory information for sirens pertains to nuclear power plants — but while these regulations are specific to that industry, the guidance is based on best practices that can and should be used for other siren applications.

**[Table block]**

| Title | Author / Agency | Date | Notes | Download |
|---|---|---|---|---|
| NUREG-0654 | NRC and FEMA | Sep 1980 | The primary regulatory document governing the creation of a Design Report for an entire alert and notification system. Pertains to nuclear plants, but has valuable information for any system. | [link to PDF] |
| FEMA REP-10 | FEMA | Nov 1985 | Supplements NUREG-0654 and provides clarification. | [link to PDF] |
| CPG 1-17 | FEMA | Mar 1980 | One of the key documents, created largely from the Bolt, Beranek and Newman Outdoor Warning Systems Guide from the previous year. Introduces key acoustic elements, including guidance to achieve 70 dBC in high population areas (>2,000 people/sq mi) and 60 dBC in low population areas. | [link to PDF] |
| FEMA – Outdoor Warning Systems Technical Bulletin (v2.0) | FEMA | Jan 2006 | Improved guidance over CPG 1-17, includes details about determining range predictions for sirens. | [link to PDF] |
| Outdoor Warning Systems Guide | Bolt Beranek and Newman Inc. | Jun 1979 | Some of the first technical work into designing and building an outdoor warning system. Interesting historically, with useful info. | [link to PDF] |
| NUREG/CR-2654 | Bolt Beranek and Newman Inc. | Sep 1982 | Details on how to analyze an outdoor warning system's effectiveness. Largely superseded by modern computer modeling, but shows how to estimate siren coverage with just a map, pencil, and calculator. | [link to Google Drive/PDF] |

**[CTA band]**
Headline: Need help with sirens? We are experts!
Button: Contact Us → contact page

---

## PAGE: About

**[Page header block]**
Headline: About Us
Subhead: Expert in outdoor sound propagation

**[Photo + text side-by-side block]**
**[PHOTO NEEDED: Bruce-with-Guitar.jpg]**

Dr. Ikelheimer has been studying outdoor sound and acoustic propagation for more than 25 years.

As a graduate student, Dr. Ikelheimer worked on Active Noise Control – the process of cancelling one noise with an equal and opposite anti-noise. Since then he has worked on projects with DARPA, NASA, the National Park Service, and a wide range of commercial clients.

Projects have included the noise analysis of airfields, acoustic source measurements of UAVs, traffic noise studies, military environmental assessments, and the design and testing of large and small outdoor warning systems.

Dr. Ikelheimer has developed cutting edge acoustic propagation software for the Department of Defense, NASA, and the National Park Service. He has specialized in acoustic propagation and simulation modeling, with experience with many of the common acoustic models.

He is an average guitar player, a kick-butt bass player, an average cyclist, and a kick-butt skier! He lives in Asheville, NC, deep in the Blue Ridge Mountains.

**[CTA band]**
Headline: Need help with a noise problem? We are experts!
Button: Contact Us → contact page

---

## PAGE: Contact

**[Page header block]**
Headline: Contact
Subhead: Contact us
Body: We are located in Asheville, NC – right in the heart of the Blue Ridge Mountains. We are happy to answer any questions – just let us know how we can help.

**[Contact info block]**
- Address: 89 Saint Dunstan's Rd., Asheville, NC
- Email: contact@AcousticAnalytics.com
- Phone: +1 703-403-9842

**[Form block — set up with a form-handling service like Formspree, since GitHub Pages can't process PHP]**
Fields: Name, Email, Message → Submit button "Send message"

---

## Notes on SEO carry-over (see chat for full discussion)

- Keep the same URL paths where possible (`/services/`, `/about/`, etc. rather than `.html`) to preserve existing search rankings and backlinks.
- Re-create a sitemap.xml and robots.txt for the new site (WordPress/Yoast auto-generated these; a static site needs them added manually).
- Keep meta descriptions and image alt text — carried over into this content package where known, but confirm/expand once real photos are in place.
- Set up 301-equivalent redirects for any URL that does change (GitHub Pages can't do true server-side 301s — a meta-refresh redirect page is the fallback, weaker but workable).

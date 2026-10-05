REVENEW — PODCAST WEBSITE PAGE UPDATE
=====================================

NEW
  podcast-website.html        The new Podcast Website page
  images/podcast/             Nine screenshots used on that page

UPDATED
  style.css                   Original styles unchanged; new block added at the end
                              (seven-item navigation spacing + Podcast Website page)
  index.html                  New nav + one line under the Focused Assets diagram
                              linking to the Podcast Website page
  get-started.html            New nav + a small script: visitors arriving from the
                              Podcast Website page find "Podcast Website: " already
                              typed in the Discovery form's message box
  about.html, problem.html,
  how-it-works.html,
  revenew-roadmap.html        New nav and footer only

NAVIGATION (all pages)
  Top:    Home · About · The Problem · How It Works · The Roadmap ·
          Podcast Website · [Schedule a Call]
  Footer: Home · About · The Problem · How It Works · The Roadmap ·
          Podcast Website · Get Started

CTA WORDING (all pages)
  "Schedule a Discovery Call" is now "Schedule a Call" (nav button and every
  page button). On Get Started, the form heading reads "Schedule A Call" and
  the submit button reads "Request a Call". The "Discovery Call" step in the
  Business Process diagram is unchanged.

OTHER CHANGES
  index.html                  Home page diagram center label now reads
                              "Existing Content" (the same diagram on The Roadmap
                              page still reads "Focused Assets")
  revenew-roadmap.html        "The Five Components": the fifth card spans the full
                              row, so there is no empty sixth box

ABOUT PAGE PHOTO
  about.html loads the founder photo from images/scott-long.jpg (included).

BEFORE YOU UPLOAD
  Discovery form
     These files were built from the project copy of get-started.html, where the
     form's action is "#". If the live form sends to your email through a
     service (Netlify Forms, Formspree, etc.), keep the live <form ...> tag and
     copy only the new nav, footer, and the <script> at the bottom of the page.

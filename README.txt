THE BK SHOW — website (v3, screen-first format)
================================================

FILES
  index.html         Home — format, run of the evening, the rounds, tickets
  sponsorship.html   Packages, screen inventory, named rounds, enquiry form
  partners.html      Partner directory (sample data — replace before launch)
  about.html         The show, the host, the producer, the vision
  contact.html       Contact routes, message form, FAQ

EACH PAGE IS SELF-CONTAINED
  The stylesheet and all photographs are built into every HTML file.
  There is no assets folder and nothing else to upload. Open any file on
  its own, email it, or drop it on any host and it looks correct.
  index.html must sit at the root of the domain.

  The only things loaded from the internet are the two Google fonts
  (Anton and Jost) and the YouTube thumbnails in the home page gallery.
  Both need a live connection — offline they fall back to a system font
  and blank gallery tiles. That is normal.

  Editing the styling: the CSS lives in the <style> block near the top of
  each page. It is identical in all five, so a change has to be pasted
  into each one. If you would rather keep one shared stylesheet, ask and
  we can split it back out.

WHAT CHANGED FROM THE PREVIOUS SITE
  - Businesses appear on the main screen and are named from the stage.
    There is no trade floor and no exhibition tables anywhere in the format.
  - Show length is a tight 3 hours: doors 7:00 PM, show 7:30 PM,
    close 10:30 PM.
  - A 20-minute interval at 8:55 PM is built in so customers meet the
    businesses and the businesses meet the community. Partner teams take
    the floor and the host makes introductions.
  - Ticket SAR 100 with tiers  ->  one flat SAR 50 for every seat.
  - Entry tier is Screen Partner at SAR 3,000.
  - New: named rounds (BK Quiz, Jackpot, Business Battle, Family Challenge,
    BK Hero, Golden Box) sold as separate sponsor properties.
  - New pages: about.html and contact.html.

BEFORE YOU GO LIVE — CHECKLIST
  1. Partner directory in partners.html is SAMPLE DATA. The list is at the
     top of the <script> block at the bottom of the file, marked with a
     comment. Replace with signed partners.
  2. Same for the brand wall in index.html (section id="brands").
  3. Card payment is not connected. Every booking button composes a WhatsApp
     message to +966 57 538 5090. Connect a real gateway before selling at
     volume — at SAR 50 a seat, manual confirmation will cost more than the
     ticket.
  4. Event dates and venues live in the SHOWS array at the bottom of
     index.html. Update as venues are contracted.
  5. Add a favicon and an Open Graph share image (1200x630).
  6. Replace the placeholder contact name on the sponsorship deck if you
     are sending both together.

CONTACT DETAILS USED
  WhatsApp / tickets  +966 57 538 5090   (all WhatsApp buttons and forms)
  Partnerships        +966 59 501 2436   (contact page only)
  Email               info@4starsint.com
  Instagram           @bkksa.live

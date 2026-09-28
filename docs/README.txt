INFRIGIDATE WEBSITE - STATIC FILES
==================================

Contents
  index.html   The complete website (all pages: Home, About, Solutions,
               Capabilities, Industries, Projects + 6 case studies,
               Quality & Safety, Careers, Contact)
  img/         Photos, client logos and letters (from the company profile deck)

How to view on your computer
  Unzip the folder and double-click index.html. Keep index.html and the img
  folder together.

How to put it live on infrigidate.in
  Upload index.html and the img folder to the website's root folder
  (public_html or www) using the hosting control panel (cPanel File Manager)
  or FTP. Replace the old index.html. No database or server software needed.

Before going live - for the web developer
  1. Forms: the Contact and Careers forms currently show a "Preview only"
     message. Connect them to email (e.g. a PHP mail script, Formspree or
     the hosting provider's form handler) so enquiries reach
     sales.pune@infrigidate.in, then change the message text in the script
     at the bottom of index.html (search for "Preview only").
  2. Old pages: add 301 redirects from installation.html, repair.html,
     maintenance-2.html and contact.html to index.html (or matching sections).
  3. Add Privacy Policy and Terms of Use pages (linked in the footer).
  4. Set up Google Analytics 4 and Google Search Console.
  5. Page links use #about, #projects, #project-jotun etc. They work as-is.

Content still to confirm
  - Leadership bios (About page)
  - ISO standard and certificate details (Quality & Safety page)
  - Pune address, if the office moves to Escala, Kharadi

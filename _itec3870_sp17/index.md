---
layout: projects
title:  "Spring 2017 Software Development 2 Course Projects"
date:   2017-08-16 14:49:25
categories: itec3870 create
collection: itec3870_sp16
photos:
- IMG_20170427_145146955.jpg
- IMG_20170427_144410982.jpg
- IMG_20170427_144413728.jpg
- IMG_20170427_144433983.jpg
- IMG_20170427_145050656.jpg
- IMG_20170427_145114857.jpg
- IMG_20170427_145202939_HDR.jpg

projects:
- name: GGCmaps
  title: "Search rooms. Find rooms. Don't get lost in A (even offline!)"
  demo-url: http://ggcmaps.com/
  members: David Rivera-Rocha, Josh Gerth, Carlos Pacheco-Perez, Margaret "Maggie" Muse
  client: "Dr. Catherine Moore & Michael Deiters"
  client-url: http://www.ggc.edu/about-ggc/directory/catherine-moore
  description: "Webapp that allows finding GGC campus rooms from their numbers (second semester)."
  tech: "Progressive webapp that can work offline with a custom Javascript front-end. It requires no back-end to function. It can save itself as a desktop shortcut on mobile platforms."
  logo-full: images/flyer-ggcmaps.png
  logo-thumb: images/thumb-flyer-ggcmaps.png
  repo-url: https://github.com/soft-eng-practicum/ggcmaps
- name: CellPhysics42
  title: "A Cellular Automaton Demo and Visualization Tool"
  screencast-youtube: HGxIZMmUeGA
  members: "Michael Holtmann, Jory Alexander, and Bess Burnett"
  client: "Dr. Kenneth Sales"
  client-url: http://www.ggc.edu/about-ggc/directory/kenneth-sales
  description: "Can visualize 1-D and 2-D rules as 2-D triangles and 3-D pyramids, respectively."
  tech: Java application with JavaFX GUI and 3D visualization. 3-D models were also printed using a 3-D printer.
  logo-full: images/flyer-team42.png
  logo-thumb: images/thumb-flyer-team42.png
  repo-url: https://github.com/soft-eng-practicum/CellPhysics42
- name: PicturePerfect
  title: "A cinematography and photo teaching app"
  demo-url: http://alvinuity.altervista.org/SimpleQ/Home.php
  screencast-youtube: cIvjVlIS4lM
  members: "Alain Hirwa, Anwar Saleeby, and Neal Klemenc"
  client: "Dr. Lyndsay Gratch"
  client-url: http://www.ggc.edu/about-ggc/directory/lyndsay-gratch
  description: "Learn the basics of cinematography and photo composition"
  tech: Mobile app with Ionic 2. No backend or database. Not on app markets yet.
  logo-full: images/flyer-pictureperfect.png
  logo-thumb: images/thumb-flyer-pictureperfect.png
  repo-url: https://github.com/soft-eng-practicum/pictureperfect
- name: AtomPuzzler
  title: "Learn chemistry for fun!"
  demo-url: http://johnjlam.com/AtomPuzzlerPages/
  screencast-youtube: oK54BlI11o4
  members: "Matt Nelson, King Lo, Caleb Sears, and John Lam"
  client: "Dr. Thomas Gluick"
  client-url: http://www.ggc.edu/about-ggc/directory/thomas-gluick
  description: "College-level gamified learning tool for chemical naming and molecular geometry."
  tech: Website created using GameMaker Studio. No database or backend.
  logo-full: images/flyer-atompuzzler.png
  logo-thumb: images/thumb-flyer-atompuzzler.png
  repo-url: https://github.com/soft-eng-practicum/AtomPuzzler
- name: GGRAwebsite
  title: A new design for the Greater Gwinnett Reentry Alliance website 
  screencast-youtube: EWj7w-kcm3A
  members: "Team Monstars: King Oruga, Joshua Tran, Peter Odeojo, William \"Matt\" Smith"
  client: "Karen Klett, Koko Hunt, and Dr. Lana McDowell"
  client-url: http://www.ggc.edu/about-ggc/directory/lana-mcdowell
  description: "Reintegration, restoration, and reentry of returning citizens."
  tech: Website with HTML/CSS/Javascript frontend and an ASP.Net backend using C#. SQL Server database.
  logo-full: images/flyer-GGRA.png
  logo-thumb: images/thumb-flyer-GGRA.png
  repo-url: https://github.com/soft-eng-practicum/GGRAwebsite
- name: InternApp
  title: "Kickstart your career! Apply now!"
  demo-url: http://ggc-internapp.herokuapp.com/
  screencast-youtube: TNs-tkoyQG8
  members: "Team DaSquad: Robert Bryan, Blake Norman, Khaled Asad, and Michael Cawton"
  client: <a href="http://www.ggc.edu/about-ggc/directory/latanya-hammonds-odie" target="_blank">Dr. Latanya Hammonds-Odie (Biology)</a> and <a href="http://www.ggc.edu/about-ggc/directory/lissa-pollacia" target="_blank">Dr. Lissa Pollacia (IT)</a>
  description: "Online applications for ITEC 4900 and BIOL 4800 internship courses (second semester)."
  tech: Website with EJS templating in the frontend, Express+Node.JS in the backend with MongoDB hosted on mLab.
  logo-full: images/flyer-internapp.png
  logo-thumb: images/thumb-flyer-internapp.png
  repo-url: https://github.com/soft-eng-practicum/internapp

---

These projects were developed during the ITEC 3870 Software
Development 2 course taught by [Dr. Cengiz Gunay][gunay-ggc] in the
Spring 2017 semester by [Georgia Gwinnett College][ggc] students. Each
project was commissioned and supervised by a GGC professor who
provided the idea, requirements, and direction throughout the
semester. Final products were demonstrated and tested by other
students and faculty at the GGC CREATE symposium. Click on
titles to see their demo sites.

  <!-- lightgallery -->
  <script src="https://code.jquery.com/jquery-2.2.4.min.js"></script>
  <script src="https://cdn.jsdelivr.net/lightgallery/1.3.7/js/lightgallery.min.js"></script>  
  <script src="https://cdn.jsdelivr.net/g/lg-zoom"></script>  

  <script type="text/javascript">
    $(document).ready(function() {
    $("body").lightGallery({
	zoom: true,
	selector: 'a#lightgallery',
	selectWithin: 'body'
    }); 
    });
  </script>

[ggc]:		http://www.ggc.edu
[gunay-ggc]: 	http://www.ggc.edu/about-ggc/directory/cengiz-gunay

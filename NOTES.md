Prerequisites/milestones to delivery

 docker run pulsetile should result in a running pulsetile front end application on a given port

 docker run qewd should result in a running QEWD stack application (or several applications) running on a given port

 docker run ethercis should result in a running etherCIS server at a given port

 EtherCIS should be installed with a preinstalled set of commonly-used templates which enable basic functionality: add a patient, add a patient to a list, add a patient encounter, add some clinical detail. (The actual deliverable templates may need significant consideration and discussion)

Acceptance criteria

 docker-compose up in the root directory of a freshly cloned Ripple Stack repo should pull the necessary Docker containers as detailed above, configure and run them, make them available to each other on the requisite ports, and set up Docker storage volumes as necessary, resulting in a fully operable Ripple stack which can be interacted with via the web browser in the first instance.

 vagrant up in that same root directory should alternatively instantiate a Virtual Machine in which the docker-compose vagrant provisioner plugin will provision the Ripple Stack as in the preceding criterion. Although this setup has significant performance disadvantages compared to native Docker, it is often a preferred option for Windows users.

 At this point of installation, the Ripple Stack should be able to demonstrate basic patient operations such as: Add a patient, view patient, add encounter, add clinical detail. From there, the putative Hack Day developer can follow the 'Getting Started' tutorial in order to add a small unit of new functionality eg a new view, new data entry form, or new integration.


.. include:: /Includes.rst.txt

.. _s3-d3:

===========================================================
Day 3 — Advanced CI/CD Implementation and Quality Assurance
===========================================================

.. _s3-d3-lessons:

Today's lessons
===============

Today advances CI/CD practices with a focus on deployment optimization and quality assurance. Students will learn advanced deployment strategies, automated testing methodologies, and comprehensive backup techniques. The day emphasizes hands-on experience with collaborative development workflows and implementing robust testing and backup systems in a continuous deployment environment.

.. toctree::
    :titlesonly:

    Lesson-1
    Lesson-2
    Lesson-3
    Lesson-4
    Lesson-5
    Lesson-6
    Lesson-7


.. _s3-d3-prerequisites-goals:

Prerequisites and goals
=======================


.. _s3-d3-prerequisites:

Prerequisites
-------------


.. _s3-d3-theoretical-prerequisites:

Theoretical prerequisites
~~~~~~~~~~~~~~~~~~~~~~~~~

This day assumes that you already know the following:

* The difference between and benefits of differentiated testing, staging, and production/live environments
* Understand how and why to separate environments, including the isolation of changes and the progressive steps toward live deployment
* Understand the challenges associated with database versioning and migration
* How to perform database schema and data migrations in TYPO3 as part of a CD workflow
* Know the theoretical best practices for handling these changes seamlessly


.. _s3-d3-practical-prerequisites:

Practical prerequisites
~~~~~~~~~~~~~~~~~~~~~~~

Before you start this day, please have the following things ready:

* Configured TYPO3 differently for development, testing, staging, and production environments
* Implemented scripts or tools that manage database changes
* Ensure that migrations are smoothly and automatically handled during deployments
* Demonstrated the setup of each environment and validated that each configuration and migration strategy works as expected


.. _s3-d3-goals:

Goals
-----

.. _s3-d3-theoretical-goals:

Theoretical goals
~~~~~~~~~~~~~~~~~

By the end of this day, you should know the following:

* Understand how these advanced deployment strategies can minimize downtime and risk
* Know the tools and methodologies used for automated testing, including unit tests, integration tests, and end-to-end tests
* Understand different backup techniques and the importance of data redundancy
* Understand how to effectively plan and execute backups in continuous deployment environments


.. _s3-d3-practical-goals:

Practical goals
~~~~~~~~~~~~~~~

By the end of this day, you should have completed the following:

* Used a continuous integration and continuous deployment pipeline for code contribution in a team with other contributors
* Set up, execute, and monitor advanced deployment techniques
* Write and run various types of automated tests, and integrate these tests into their deployment pipelines
* Implement a backup system that complements their CI/CD setup
* Fixed issues discovered in failed automated and manual code reviews
* Deployed database schema changes and automated data migrations using TYPO3 core technologies

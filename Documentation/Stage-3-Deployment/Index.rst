.. include:: /Includes.rst.txt

.. _s3

====================
Stage 3 — Deployment
====================

.. _s3-about

About this stage
================

This stage focuses on implementing continuous integration and deployment (CI/CD) with TYPO3. Over five days, participants learn CI/CD concepts, configuring TYPO3 for various environments, and advanced deployment strategies. Day 1 introduces CI/CD principles and effective workflows. Day 2 covers setting up testing environments and managing database migrations. Day 3 dives into advanced CI/CD techniques, including automated testing and backup strategies. Day 4 is dedicated to practical application and troubleshooting in CI/CD pipelines. Day 5 wraps up with project presentations, Q&A, and peer feedback to solidify the learning experience.

.. toctree::
    :titlesonly:

    Day-1/Index
    Day-2/Index
    Day-3/Index
    Day-4/Index
    Day-5/Index

.. _s3-prerequisites-goals

Prerequisites and goals
=======================


.. _s3-prerequisites

Prerequisites
-------------


.. _s3-theoretical-prerequisites

Theoretical prerequisites
~~~~~~~~~~~~~~~~~~~~~~~~~

This stage assumes that you already know the following:

* How to create a sitepackage extension which:
    * Deliver the expected design
    * Allow editing of the site's content
* How to configure and provide proper access to Backend Users in order to edit the content


.. _s3-practical-prerequisites

Practical prerequisites
~~~~~~~~~~~~~~~~~~~~~~~

Before you start this stage, please have the following things ready:

* A functional TYPO3 website with:
    * Customized design
    * Editable content according to the site's requirements
    * Configured Backend Users


.. _s3-goals

Goals
-----

.. _s3-theoretical-goals

Theoretical goals
~~~~~~~~~~~~~~~~~

By the end of this stage, you should know the following:

* The concepts and benefits of continuous integration (CI) and continuous deployment (CD) workflows for quality assurance
* How an ideal deployment workflow and pipeline works for you, your team, and on a technology level
* The difference between and benefits of differentiated testing, staging, and production/live environments
* How to configure TYPO3 for different environments.
* How to perform database schema and data migrations in TYPO3 as part of a CD workflow
* Backup best practices for continuous deployment environments.
* The most common tools for automated quality assurance in PHP-based continuous integration workflows
* Best practices for code review


.. _s3-practical-goals

Practical goals
~~~~~~~~~~~~~~~

By the end of this stage, you should have completed the following:

* Configured your own continuous integration and continuous deployment workflow locally and remotely
* Used a continuous integration and continuous deployment pipeline for code contribution in a team with other contributors
* Fixed issues discovered in failed automated and manual code reviews
* Deployed database schema changes and automated data migrations using TYPO3 core technologies

.. include:: /Includes.rst.txt

.. _s4:

==================================
Stage 4 — Maintenance and Security
==================================

.. _s4-about:

About this stage
================

This stage is focused on maintaining and securing TYPO3 installations. Over five days, participants will delve into TYPO3 system architecture, security best practices, and upgrade processes. Day 1 introduces TYPO3 maintenance and security, including setting up secure environments and advanced user management. Day 2 focuses on performing upgrades, understanding TYPO3's release cycle, and managing custom code during upgrades. Day 3 covers advanced security settings, mitigating threats, and system monitoring. Day 4 emphasizes securing custom code, managing vulnerabilities, and applying security patches through hands-on workshops. Day 5 concludes with crisis management, including responding to security incidents, recovery techniques, and conducting post-mortem analysis, ensuring participants are well-prepared to handle real-world security challenges in TYPO3.

.. toctree::
    :titlesonly:

    Day-1/Index
    Day-2/Index
    Day-3/Index
    Day-4/Index
    Day-5/Index

.. _s4-prerequisites-goals:

Prerequisites and goals
=======================


.. _s4-prerequisites:

Prerequisites
-------------


.. _s4-theoretical-prerequisites:

Theoretical prerequisites
~~~~~~~~~~~~~~~~~~~~~~~~~

This stage assumes that you already know the following:

* The knowledge required by the theoretical prerequisites of previous curriculum stages.
* The theoretical knowledge goals of the previous curriculum stage.

Particularly important to know for success at this stage:

* How to use Composer, the command line, and TYPO3's built-in tools to upgrade a TYPO3 installation.
* The concepts and benefits of continuous integration (CI) and continuous deployment (CD) workflows for quality assurance
* How to develop for and deploy to a testing, staging, and production/live environments
* Backup best practices for continuous deployment environments.


.. _s4-practical-prerequisites:

Practical prerequisites
~~~~~~~~~~~~~~~~~~~~~~~

Before you start this stage, please have the following things ready:

* A working TYPO3 installation under Git-based version control
* A working continuous integration and continuous deployment workflow with local and remote parts

Ideally a contribution team with other contributors should be available for you to test best-practice collaboration and review processes.


.. _s4-goals:

Goals
-----

.. _s4-theoretical-goals:

Theoretical goals
~~~~~~~~~~~~~~~~~

By the end of this stage, you should know the following:

* Maintenance and security best practices, both generally and specifically, in a TYPO3 context.
* How to perform major and minor upgrades to TYPO3 and your own code
* How to deploy upgraded versions of TYPO3 and your own code using continuous deployment while ensuring minimal downtime.
* Security best practices for your own code in TYPO3 instances and hosting environments, including the :ref:`TYPO3 Security guidelines <t3coreapi:security>`
* How to correctly handle security issues in the TYPO3 core.
* How to correctly handle security issues with your own code.
* Who to work with and best practices for handling compromised live environments and minimizing impact.


.. _s4-practical-goals:

Practical goals
~~~~~~~~~~~~~~~

By the end of this stage, you should have completed the following:

* Performed major and minor upgrade of TYPO3 and deployed it to a live environment using a continuous integration and continuous deployment pipeline.
* Created new versions of your own code and deployed it to a live environment using a continuous integration and continuous deployment pipeline.
* Simulated handling of a compromised live environment.

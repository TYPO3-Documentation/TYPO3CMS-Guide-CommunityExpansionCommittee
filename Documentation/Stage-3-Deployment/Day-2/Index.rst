.. include:: /Includes.rst.txt

.. _s3-d2:

====================================================
Day 2 — Testing Environments and Database Management
====================================================

.. _s3-d2-lessons:

Today's lessons
===============

Today focuses on managing different TYPO3 environments and database operations in a deployment workflow. Students will learn to distinguish between development, testing, staging, and production environments, while mastering database versioning and migration strategies. The day emphasizes practical implementation of automated database management and environment-specific configurations.

.. toctree::
    :titlesonly:

    Lesson-1
    Lesson-2
    Lesson-3
    Lesson-4
    Lesson-5
    Lesson-6
    Lesson-7


.. _s3-d2-prerequisites-goals:

Prerequisites and goals
=======================


.. _s3-d2-prerequisites:

Prerequisites
-------------


.. _s3-d2-theoretical-prerequisites:

Theoretical prerequisites
~~~~~~~~~~~~~~~~~~~~~~~~~

This day assumes that you already know the following:

* The concepts and benefits of continuous integration (CI) and continuous deployment (CD) workflows for quality assurance
* How an ideal deployment workflow and pipeline works for you, your team, and on a technology level
* How to configure TYPO3 for different environments.
* Understand how CI/CD practices improve software delivery and quality, streamline workflows, and reduce the risk of errors in production.
* Be able to differentiate between tools like Jenkins, Travis CI, and GitLab CI, and understand the scenarios in which each tool would be most effective.
* Recognize the components of effective deployment workflows and understand how to design these to enhance collaboration and efficiency.


.. _s3-d2-practical-prerequisites:

Practical prerequisites
~~~~~~~~~~~~~~~~~~~~~~~

Before you start this day, please have the following things ready:

* Configured a simple pipeline that automates building, testing, and deploying TYPO3 applications.
* Conducted hands-on exercises to manage TYPO3 configuration files and adjust settings based on the specific requirements of each environment.
* Created and managed multiple environment setups, ensuring each is optimized for its purpose.


.. _s3-d2-goals:

Goals
-----

.. _s3-d2-theoretical-goals:

Theoretical goals
~~~~~~~~~~~~~~~~~

By the end of this day, you should know the following:

* The difference between and benefits of differentiated testing, staging, and production/live environments
* Understand how and why to separate environments, including the isolation of changes and the progressive steps toward live deployment
* Understand the challenges associated with database versioning and migration
* How to perform database schema and data migrations in TYPO3 as part of a CD workflow
* Know the theoretical best practices for handling these changes seamlessly


.. _s3-d2-practical-goals:

Practical goals
~~~~~~~~~~~~~~~

By the end of this day, you should have completed the following:

* Configured TYPO3 differently for development, testing, staging, and production environments
* Implemented scripts or tools that manage database changes
* Ensure that migrations are smoothly and automatically handled during deployments
* Demonstrated the setup of each environment and validated that each configuration and migration strategy works as expected

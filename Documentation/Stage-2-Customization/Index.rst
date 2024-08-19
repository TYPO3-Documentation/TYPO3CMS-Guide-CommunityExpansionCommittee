.. include:: /Includes.rst.txt

.. _s2

=======================
Stage 2 — Customization
=======================

.. _s2-about

About this stage
================

This stage is about customizing TYPO3. Day 1 covers TYPO3's architecture, backend modules, extension management, and content editing. Day 2 focuses on creating and organizing pages, managing files, and building forms. Day 3 delves into TypoScript, including setting up page templates, website navigation, and backend layouts. On Day 4, you'll explore Fluid templates and the Rich Text Editor (RTE), learning to create and manage templates and customize the RTE. Day 5 culminates in creating and configuring a site package extension, optimizing performance, and applying best practices for security and efficiency. Each day concludes with a recap and catch-up session to reinforce learning and ensure a solid grasp of the material.

.. toctree::
    :titlesonly:

    Day-1/Index
    Day-2/Index
    Day-3/Index
    Day-4/Index
    Day-5/Index

.. _s2-prerequisites-goals

Prerequisites and goals
=======================


.. _s2-prerequisites

Prerequisites
-------------


.. _s2-theoretical-prerequisites

Theoretical prerequisites
~~~~~~~~~~~~~~~~~~~~~~~~~

This stage assumes that you already know the following:

* How to install and configure DDEV on your local computer
* How to setup a Git repository for your project
* How to use Composer to install a TYPO3 project in a DDEV container
* How to configure a TYPO3 project
* How to install and configure Bootstrap Package extension


.. _s2-practical-prerequisites

Practical prerequisites
~~~~~~~~~~~~~~~~~~~~~~~

Before you start this stage, please have the following things ready:

* A working local development environment based on DDEV
* A Git repository for your project
* A new TYPO3 project
    * Installed using Composer
    * Configured and up and running in your local development environment
    * Versioned using Git
    * With the Bootstrap Package extension installed


.. _s2-goals

Goals
-----

.. _s2-theoretical-goals

Theoretical goals
~~~~~~~~~~~~~~~~~

By the end of this stage, you should know the following:

* Basic TYPO3 concepts:
    * Backend & Frontend
    * Backend Modules
    * Extensions
* Editing concepts and how to edit and customize:
    * Pages and page tree
    * Content
    * Files management
    * Create forms (ex. the contact form)
    * Backend Users and access rights
    * WYSIWYG editor
* Specific TYPO3 concepts and how to use them:
    * TypoScript
        * Setup the Page template
        * Create the website navigation (menus, breadcrumb)
    * Backend Layouts
    * TsConfig
        * Page TsConfig
        * User TsConfig
        * Backend Layouts configuration
    * Fluid Templates
    * WYSIWYG Editor configuration
* How to create and configure a Site Package Extension


.. _s2-practical-goals

Practical goals
~~~~~~~~~~~~~~~

By the end of this stage, you should have completed the following:

* Create and configure a Site Package Extension which:
    * Deliver the expected design
    * Allow editing of the site's content
* Configure and provide proper access to Backend Users in order to edit the content

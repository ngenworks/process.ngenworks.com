=======================
Phase Four: Development
=======================

Contents:

.. contents::
  :local:

-------------
Phase Summary
-------------

* Confirm the specifications
* Develop the CMS
* Finalize integrations
* Continuous testing
* Update the GitHub Repo
* Going to Market

----------------
Typical Outcomes
----------------

* Pre-production meeting
* CMS or database development
* Content flowing
* Brand and content guidelines

How the prototyping and production phase unrolls depends on whether the team is building an app or a site. Building apps usually involves determining more complex functionality; rapid prototyping allows the project or product to form quickly with ongoing collaboration from the team and client before development. Simple sites don’t usually require development of vertical slices unless their functionality would benefit from it. They usually move from design directly into development, although we don't want to box ourselves into calling this either a waterfall or agile method. We just take the approach that works the best with each individual product or site. Design may run parallel to, staggered with, or ahead of development, and can follow up with styling CSS if necessary. 


.. note:: For larger projects and applications, it's a good idea to have an early conversation with the client so they can establish a team to carry on support and maintenance (or hire a developer) if required. 

----------------------
Confirm Specifications
----------------------

Review The Components
^^^^^^^^^^^^^^^^^^^^^

It's development time. The first step is to make sure there are no gaps in information regarding functionality and its interaction with the look and feel of the site or app we are building. Ongoing communication between the designer, developer, and all other teammates prevent misinterpretation about how we translate the prototype into a functional site or application.

Before any development work is completed, we re-review our components list together and cross-check it against what we've been building so far. This allows us to see any gaps or directional shifts taken since we started and also keeps us on target for our initial release.

Pre-Production Meeting
^^^^^^^^^^^^^^^^^^^^^^

Once we've met with our team to go over the core components list, it's time for a pre-production meeting. Our PM and developer(s) coordinate a pre-production meeting with the designer and content strategist to determine any special areas of focus or development considerations. This is also a good way to ensure that our design build and content hierarchy are completely in sync with the development plan. Be sure we have access to all the right login credentials before any code is committed.
API Specification

An API allows a web browser or mobile device to interact with the system to fetch or update data. Our developers work together to create documentation that outlines exactly how that API should work with the app and the steps we need to take to ensure the interactions are seamless. We also make sure we have any required account information if that API already exists or the specifications we need to create and refine APIs for our project. API building takes time and should be fleshed out as early as possible to account for all the moving parts.

Develop the CMS
^^^^^^^^^^^^^^^

Next the developer considers the CMS. If we're building an app we have to determine what, if any type of CMS, is necessary and what kind of flexibility the client should have to be able to update the content. This also means we should have a clear idea of how we're approaching the development: a CMS like `ExpressionEngine <http://expressionengine.com/>`_ or `Craft <http://buildwithcraft.com/>`_, or a custom built framework like `Django <https://www.djangoproject.com/>`_. Usually the team will adjust content for the client when building apps, since content changes affect the design of the app in later releases. For simple sites, we almost always develop the CMS that the HTML/CSS or face of the site or app hooks into. 





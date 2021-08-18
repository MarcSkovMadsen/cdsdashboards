.. _overview:

Overview
--------

`ContainDS <https://containds.com/>`__ is a data science platform for teams working on discrete projects. 
It provides simple infrastructure to share prototypes and dashboards based on any open source frameworks.

Your data scientists will always use their preferred development environments.

ContainDS Solutions will:

- Grant decision makers and clients easy access to actionable insights helping them move projects forward quickly and with confidence.
- Save time and reduce errors for your Data Science team, allowing them to focus on their core roles.
- Eliminate IT security threats from data science teams hosting web apps and sensitive data in arbitrary insecure cloud locations.
- Empower data scientists to use their dashboarding framework of choice while unifying your team’s approach to publishing.

ContainDS Dashboards is an extension for JupyterHub that allows users to instantly publish notebooks and other source code files 
as user-friendly interactive dashboards to share with non-technical colleagues.

Currently supports:

- Jupyter notebooks (`Voilà <https://github.com/voila-dashboards/voila>`__)
- `Streamlit <https://streamlit.io/>`__ apps
- `Plotly Dash <https://plotly.com/dash/>`__ apps
- `Bokeh <https://docs.bokeh.org/>`__ apps
- `Panel <https://panel.holoviz.org/>`__ apps and notebooks
- `R Shiny <https://shiny.rstudio.com/>`__ apps
- Any :ref:`custom web app<customlaunchers>` server or framework

Selected authorised JupyterHub users can view the dashboard. This means that you can protect the dashboard with any authentication that works 
with JupyterHub - including single-sign-on through corporate email accounts or LDAP.

Dashboard scripts and notebooks can be sourced from a Git repo or from your Jupyter tree.

How it works
~~~~~~~~~~~~

- Data scientist creates a visualization as normal, on a Git Repo or by creating/uploading files on the Jupyter tree
- Data scientist creates a new Dashboard to clone their Jupyter server or Git Repo
- Other logged-in JupyterHub users see the dashboard in their list
- Click to launch as a server, using OAuth to gain access
- User sees a safe user-friendly version of the original notebook or script

All of this works through a new Dashboards menu item added to JupyterHub's header.

Data scientist creates a Jupyter Notebook as normal

.. figure:: ../_static/screenshots/1_Original_Jupyter_Notebook.png
   :alt: Screenshot of Original Jupyter Notebook

   
Data scientist creates a new Dashboard to clone their Jupyter server, or take files from a Git repo

.. figure:: ../_static/screenshots/2_Create_New_Dashboard.png
   :alt: Screenshot of Create New Dashboard


Other logged-in JupyterHub users see the dashboard in their list

.. figure:: ../_static/screenshots/3_Other_User_sees_dashboard.png
   :alt: Screenshot of Other User sees dashboard

Uses OAuth to gain access

.. figure:: ../_static/screenshots/5_Other_user_OAuths.png
   :alt: Screenshot of Uses OAuth to gain access


Other user sees a safe user-friendly Voilà version of the original notebook

.. figure:: ../_static/screenshots/6_Voila_Dashboard.png
   :alt: Screenshot of Voilà Dashboard


Or build dashboards using other frameworks - Streamlit, Plotly Dash, Bokeh, Panel, R Studio or anything else

.. figure:: ../_static/screenshots/AppCollage.png
   :alt: Dashboards built with various frameworks

More details on how this works are in the :ref:`user guide<userguide>`, or you can find out :ref:`how to install<setup>` ContainDS Dashboards.


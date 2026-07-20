---
title: Switching Courses
parent: Getting Started
nav_order: 4
layout: default
---

# Switching Courses

## At a glance

- Open the Hub Control Panel from JupyterLab.
- Stop the course server that is currently running.
- Start your server again.
- Select a different course.

This procedure applies only if you are associated with more than one course. JupyterHub can run one of your course environments at a time, so you must stop the current server before starting a different course.

To return to the Hub Control Panel from JupyterLab:

1. Select **File** from the menu bar.
2. Choose **Hub Control Panel**.

![JupyterLab File menu with Hub Control Panel option]({{ site.baseurl }}/assets/images/screenshots/jupyterlab-hub-control-panel.png){: .figure }

<div class="figure-caption">
<strong>Figure 4.</strong> Access the Hub Control Panel from the File menu in JupyterLab.
</div>

![Hub Control Panel course management menu]({{ site.baseurl }}/assets/images/screenshots/hub-control-panel-course-management.png){: .figure }

<div class="figure-caption">
<strong>Figure 5.</strong> The Hub Control Panel provides access to the course management tools available to you.
</div>

3. On the Hub Control Panel, select **Stop My Server**.
4. Wait for the current course server to stop. When it has stopped, the page displays a **Start My Server** button.

![Hub Control Panel after the current course server has stopped]({{ site.baseurl }}/assets/images/screenshots/hub-control-panel-server-stopped.png){: .figure }

<div class="figure-caption">
<strong>Figure 6.</strong> After the current server stops, select Start My Server to choose another course.
</div>

5. Select **Start My Server**.
6. On the Course Selection page, choose the course you want to use from the **Course** drop-down menu.
7. Select **Start**.

{: .expect }
> JupyterHub starts the environment for the newly selected course. When it is ready, JupyterLab opens automatically with that course's files and software.

{: .good-to-know }
> Stopping your server does not delete your course files. It only ends the currently running JupyterLab session so that another course environment can be started.

---

## Next step

Continue to [Your JupyterLab Workspace]({{ site.baseurl }}/getting-started/jupyterlab/).

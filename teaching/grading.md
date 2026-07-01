---
title: Reviewing and Grading Notebooks
parent: Teaching Workflows
nav_order: 3
layout: default
---

# Reviewing and Grading Student Notebooks

There are several ways to review and grade Jupyter notebooks. You may encounter online discussions about **nbgrader**, but Research Computing Services does **not** currently support nbgrader as part of the F&M JupyterHub environment.

Instead, we recommend one of the following approaches, depending on course size and teaching style.

## Option 1: Review notebooks in JupyterHub

For smaller classes, the **Course Administration** tools provide a convenient way to review student work directly within JupyterHub.

Using Course Administration, you can:

- Start a student's notebook server.
- Open the student's JupyterLab environment.
- Review notebooks exactly as the student sees them.
- Run code, if desired.
- Stop the student's notebook server when finished.

{: .good-to-know }
> Viewing notebooks directly in JupyterHub allows you to interact with them just as the student would. You can execute cells, inspect outputs, and better understand issues the student may be experiencing.

## Option 2: Collect assignments through Canvas

For larger classes, it may be more practical to have students submit completed notebooks through **Canvas**.

Students have two common options for exporting their work from JupyterLab.

### Download the notebook (`.ipynb`)

Students can select **File → Download**.

![JupyterLab File menu showing Download option]({{ site.baseurl }}/assets/images/screenshots/download-notebook-ipynb.png){: .figure }

<div class="figure-caption">
<strong>Figure 12.</strong> Downloading a notebook in its native Jupyter Notebook (`.ipynb`) format.
</div>

Submitting the notebook in its original `.ipynb` format provides the greatest flexibility.

As the instructor, you can:

- Open the notebook in JupyterLab.
- Execute the student's code.
- Add comments or feedback.
- Modify notebook cells if needed.
- Interactively explore the student's work.

### Export to another format

Students can select **File → Save and Export Notebook As** and choose formats such as PDF, HTML, or Markdown.

![JupyterLab File menu showing Save and Export Notebook As options]({{ site.baseurl }}/assets/images/screenshots/export-notebook.png){: .figure }

<div class="figure-caption">
<strong>Figure 13.</strong> Exporting a notebook to another format.
</div>

Exporting is useful when you need only a static copy of the notebook for review or archival purposes. Unlike a Jupyter notebook, exported files generally cannot be executed or edited as interactive notebooks.

{: .recommendation }
> **Small classes:** Reviewing notebooks directly through **Course Administration** is often the simplest approach.  
>
> **Larger classes:** Collecting `.ipynb` notebooks through **Canvas** generally provides the most practical grading workflow.  
>
> At this time, Research Computing Services does **not** support **nbgrader** as part of the F&M JupyterHub environment.

---

## Next step

Continue to [Need Help?]({{ site.baseurl }}/help/support/).

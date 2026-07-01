---
title: GitHub and nbgitpuller
parent: Teaching Workflows
nav_order: 2
layout: default
---

# Managing Course Materials with GitHub

{: .optional }
> GitHub is **not required** to use F&M JupyterHub. This page describes an optional workflow that Research Computing Services recommends for faculty who want to manage, reuse, and distribute course materials more efficiently.

Research Computing Services recommends using **GitHub** to manage course materials, particularly if you expect to teach the course again or collaborate with colleagues.

Using GitHub provides several advantages:

- Version history for notebooks and other course materials.
- Easy reuse of course materials from semester to semester.
- Backup of course content.
- Collaboration with other instructors.
- Efficient distribution of updated materials to students.

## Sharing materials with students

If your course uses **Canvas**, Research Computing Services recommends using **nbgitpuller** to distribute notebooks and other course materials.

Rather than asking students to download notebook (`.ipynb`) files from Canvas and upload them into JupyterHub, **nbgitpuller** allows students to open course materials with a single link.

When a student clicks an nbgitpuller link in Canvas:

- The latest version of the course materials is copied into the student's JupyterHub workspace.
- Each student receives their own copy of the notebooks.
- Students can complete assignments without modifying the instructor's originals.
- Updated materials can be distributed throughout the semester by sharing a new nbgitpuller link.

![GitHub to nbgitpuller to Canvas workflow]({{ site.baseurl }}/assets/images/diagrams/github-nbgitpuller-canvas.svg){: .figure }

<div class="figure-caption">
<strong>Figure 11.</strong> A recommended workflow for distributing notebooks: GitHub repository → nbgitpuller link → Canvas → student clicks link.
</div>

{: .good-to-know }
> Research Computing Services recommends placing **nbgitpuller links directly in Canvas** instead of uploading Jupyter notebook (`.ipynb`) files. This provides a smoother experience for students and helps ensure they are working with the intended version of the materials.

{: .good-to-know }
> Students do **not** need GitHub accounts to receive course materials distributed using nbgitpuller.

## Want to learn more?

If you are interested in using GitHub and nbgitpuller to manage course materials, these resources provide useful starting points.

| Resource | Why we recommend it |
|:---|:---|
| [**GitHub Skills**](https://skills.github.com) | Interactive, hands-on tutorials from GitHub. A good place to learn the fundamentals of GitHub repositories and workflows. |
| [**Sharing Jupyter Notebooks with GitHub**](https://reproducible-science-curriculum.github.io/sharing-RR-Jupyter/01-sharing-github/) | A practical tutorial focused on organizing and sharing Jupyter notebooks with GitHub. Especially relevant for instructors using notebooks in courses. |
| [**nbgitpuller Documentation**](https://nbgitpuller.readthedocs.io) | Learn how to create nbgitpuller links and distribute notebooks to students through Canvas. |

{: .good-to-know }
> You do not need to become a Git expert to benefit from GitHub. Many instructors begin by using GitHub simply as a place to organize and back up course materials. As you become more comfortable, you can take advantage of version history, collaboration, and distributing updates with nbgitpuller.

---

## Next step

Continue to [Reviewing and Grading Notebooks]({{ site.baseurl }}/teaching/grading/).

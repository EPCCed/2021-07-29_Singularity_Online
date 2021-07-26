---
layout: lesson
root: .  # Is the only page that doesn't follow the pattern /:path/index.html
permalink: index.html  # Is the only page that doesn't follow the pattern /:path/index.html
venue: Online
address: 
country: "UK"
language: "English"
latlng: 
humandate: 10:00-16:00 BST, 28 - 29 July 2021
humantime: 10:00-16:00 BST
startdate: 2021-07-28
enddate: 2021-07-29
instructor: ["Andy Turner", "Jeremy Cohen"]
helper: []
email: ["support@archer2.ac.uk"]
collaborative_notes: https://pad.archer2.ac.uk/p/210728-Containers
---

This is the material for day 2 of the workshop. The material for day 1 can be found at: [Introduction to Docker](https://epcced.github.io/2021-07-28_Containers_Online/).

This lesson provides an introduction to using the [Singularity container platform](https://github.com/hpcng/singularity). Singularity is particularly suited to running containers on infrastructure where users don't have administrative privileges, for example shared infrastructure such as High Performance Computing (HPC) clusters. 

This lesson will introduce Singularity from scratch showing you how to run a simple container and building up to creating your own containers and running parallel scientific workloads on HPC infrastructure.

<!-- this is an html comment -->

{% comment %} This is a comment in Liquid {% endcomment %}

> ## Prerequisites
> There are two core elements to this lesson - _running containers_ and _building containers_. The prerequisites are slightly different for each and are explained below.
>
> **Running containers:** (episodes 1, 2 and 4)
> - Access to a local or remote platform with Singularity pre-installed and accessible to you as a user (i.e. no administrator/root access required).
>   - If you are attending a taught version of this material, it is expected that the course organisers will provide access to a platform (e.g. an institutional HPC cluster) that you can use for these sections of the material.
> - The platform you will be using should also have MPI installed (required for episode 4).
>
> **Building containers:** (episode 3)
> Building containers requires access to a platform with an installation of Singularity on which you also have administrative access. If you run Linux and are comfortable with following the [Singularity installation instructions](https://sylabs.io/guides/3.6/admin-guide/installation.html), then installing Singularity directly on your system is an option. However, we strongly recommend using the [Docker Singularity container](https://quay.io/repository/singularity/singularity?tab=tags) for this section of the material. Details are provided on how to use the container in the relevant section of the lesson material. To support building containers, the prerequisite is therefore:
> 
> - Access to a system with Docker installed on which you can run the Singularity Docker container.
>
>      OR
>
> - Access to a local or remote Linux-based system on which you have administrator (root) access and can install the Singularity software.
>
{: .prereq}

{% include links.md %}

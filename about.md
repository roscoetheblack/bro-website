---
layout: default
title: About
---

## Project

{{ site.description }}

## Funders

We gratefully acknowledge funding from the XYZ Founding Council, under grant number 'abc'.

## Team

 The following people are members of our research team:
 {% for team_member in site.team_members %}
 - {{ team_member.name }}, role: {{ team_member.role }}
 {% endfor %}

## Cite us

You can cite the project as:

>    *The Carpentries 2019 Annual Report. Zenodo. https://doi.org/10.5281/zenodo.3840372*

## Contact us


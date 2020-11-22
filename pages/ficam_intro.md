---
layout: default
title: Introduction
permalink: /
---

Welcome to the Federal Identity, Credential, and Access Management (FICAM) Enterprise Architecture! FICAM is the Federal Government’s implementation of Identity, Credential, and Access Management (ICAM).

> **_ICAM_** is the set of tools, policies, and systems that an agency uses to enable the **_right individual_** to access the **_right resource_**, at the **_right time_**, for the **_right reason_** in support of **_federal business objectives_**.

This page describes the basics of ICAM, the FICAM Architecture, and how you can use this playbook to facilitate ICAM practices at your agency. The FICAM Architecture applies to Federal Government IT systems, which are primarily used by government employees, contractors, and authorized partners. While citizens can access some of these systems, their identities are not managed under the FICAM Architecture.
- [What is the FICAM Architecture?](#what-is-the-ficam-architecture)
- [What is ICAM?](#what-is-icam)
- [Who is the FICAM Architecture for?](#who-is-the-ficam-architecture-for)
- [FICAM Architecture Background](#ficam-architecture-background)

The following diagram is a high-level view of the ICAM practice areas and supporting elements. 

![A color-coded diagram that has three large connected boxes and two small auxillary boxes. The three large boxes include definitions and diagrams for Identity, Credential, and Access Management, and the two small boxes include definitions for Federation and Governance.]({{site.baseurl}}/img/ConceptualDiagram.png)

The FICAM Architecture includes government-wide enterprise architecture views with the flexibility to support each agency’s unique business or mission needs. Use the FICAM Architecture as a tool to continuously improve upon your agency’s approach and align with federal security and privacy initiatives.

These are the views you’ll find in this playbook:
- [**Goals and Objectives**](goals) - The aims and outcomes of enterprise Federal ICAM.
- [**Services Framework**](services) - Descriptions of the services within each ICAM practice area that support enterprise ICAM.
- [**Use Cases**](usecases) - High-level summaries and examples of the common procedures in ICAM.
- [**Component Examples**](components) - A list of example enterprise ICAM tools, aligned to each ICAM service area. These tools, such as solutions, applications, and software, are representative examples that illustrate ICAM functionality within an agency.
- [**Standards and Policies**](standards) - The federal policies and standards that shape the implementation of enterprise ICAM.

Copy the graphics and text throughout this playbook to use at your agency to drive ICAM awareness, strategy developments, and communications.

## What is the FICAM Architecture?
FICAM is the Federal Government’s enterprise approach to design, plan, and execute common ICAM processes.

The FICAM Architecture is a framework for an agency to use in ICAM program and solution roadmap planning. The FICAM Architecture focuses on enterprise identity processes, practices, policies and information security disciplines. 

>  A federal enterprise identity is the unique representation of an employee, contractor, or enterprise user, which could be a mission or business partner, or even a device or technology managed by a Federal agency to achieve its mission and business goals. [(OMB Memorandum 19-17)](https://www.whitehouse.gov/wp-content/uploads/2019/05/M-19-17.pdf){:target="_blank"}{:rel="noopener noreferrer"}.

## What is ICAM?
ICAM is the set of tools, policies, and systems that an agency uses to enable the right individual to access the right resource, at the right time, for the right reason in support of federal business objectives.

Agencies implement ICAM services and solutions to unify their IT services, improve physical access control, and improve information security and decisions. Understanding the building blocks of ICAM is key to understanding the FICAM Architecture. ICAM has three practice areas and two supporting elements. The supporting elements enhance the capabilities of the practice areas.

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px; overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px; overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-yj5y{background-color:#efefef;border-color:inherit;text-align:center;vertical-align:middle;font-family: "Cambria", "Georgia", "Times New Roman", "Times", serif;}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top;font-family: "Cambria", "Georgia", "Times New Roman", "Times", serif;}
</style>

<table class="tg">
<thead>
  <tr>
    <th class="tg-yj5y" colspan="2"><span style="font-weight:bold">ICAM Practice Areas</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky"><img src="img/ICAM-Identity.png" alt="Three hexagons with the letters I, C, and A. The I is highlighted in red for Identity Management." width="125"><br></td>
    <td class="tg-0pky"><span style="font-weight:bold">Identity Management</span> is how an agency collects, verifies, and manages attributes to establish and maintain enterprise identities for employees and contractors.</td>
  </tr>
  <tr>
    <td class="tg-0pky"><img src="img/ICAM-Credential.png" alt="Three hexagons with the letters I, C, and A. The C is highlighted in green for Credential Management." width="125"><br></td>
    <td class="tg-0pky"><span style="font-weight:bold">Credential Management</span> is how an agency issues, manages, and revokes credentials bound to enterprise identities.</td>
  </tr>
  <tr>
    <td class="tg-0pky"><img src="img/ICAM-Access.png" alt="Three hexagons with the letters I, C, and A. The A is highlighted in blue, for Access Management." width="125"><br></td>
    <td class="tg-0pky"><span style="font-weight:bold">Access Management</span> is how an agency authenticates enterprise identities and authorizes appropriate access to protected services.</td>
  </tr>
  <tr>
    <td class="tg-yj5y" colspan="2"><span style="font-weight:bold">ICAM Supporting Elements</span></td>
  </tr>
  <tr>
    <td class="tg-0pky"><img src="img/ICAM-Federation.png" alt="Three hexagons with the letters I in red, C in green, and A in blue, with a gray banner for Federation." width="125"><br></td>
    <td class="tg-0pky"><span style="font-weight:bold">Federation</span> is the technology, policies, standards, and processes that allow an agency to accept digital identities, attributes, and credentials managed by other agencies.</td>
  </tr>
  <tr>
    <td class="tg-0pky"><img src="img/ICAM-Governance.png" alt="Three hexagons with the letters I in red, C in green, and A in blue, with a navy banner for Governance." width="125"><br></td>
    <td class="tg-0pky"><span style="font-weight:bold">Governance</span> is the set of practices and systems that guides ICAM functions, activities, and outcomes.</td>
  </tr>
</tbody>
</table>

## Who is the FICAM Architecture for?
The FICAM Architecture is for agency personnel. An enterprise architecture is primarily used by:
- **Senior Federal IT and agency stakeholders** to understand the concepts for identity and access management services and the basic use cases supporting business objectives.
- **Program Managers** to find common definitions and frameworks for use in planning.
- **Enterprise and Application Architects** to use a common framework for designing and governing IT systems, applications, and implementations.

## FICAM Architecture Background
The FICAM Enterprise Architecture, as described in the FICAM Roadmap and Implementation Guidance v2.0, was created in 2009 to provide a common ICAM segment architecture for federal agencies. While the FICAM Roadmap remains a comprehensive source of information that plays a guiding role for ICAM programs and implementation efforts across the Federal Government, it is a lengthy document that does not translate well to today’s digital society. With that in mind, in 2015, ICAM experts from across the Federal Government collaborated on an updated FICAM Enterprise Architecture that is concise, easy to understand, and visually appealing, while reflecting the latest updates in cybersecurity, enterprise architecture, and ICAM policy and technology.

This site contains the current 2020 update for the FICAM Architecture.

### The Architecture & Playbook Tiger Team
In 2015, members of the FICAM community participated in a tiger team under the direction and guidance of the Federal CIO Council’s ICAMSC to review, validate, and revise elements of the FICAM Architecture as described in the FICAM Roadmap and Implementation Guidance v2.0. Members of this effort and the 2020 update effort worked under the following guiding principles:

- The initial architecture was still largely correct and relevant, and revision activities should focus on modernization and enhancements rather than a complete overhaul.
- Existing architecture elements should be considered for update and inclusion to maintain “backwards compatibility” with existing agency enterprise architecture design.
- Architecture artifacts should focus on common ICAM goals, processes, and requirements rather than outliers or “one-off” agency use cases.
- Any new elements should address gaps or improve clarity to decrease the original documents length.
- Updates should address the need for greater efficiencies, cost savings, and shared infrastructure.
- Elements should align with the Common Approach to Federal Enterprise Architecture for government-wide consistency.

### The Move to Online Collaboration
To support a collaborative, iterative environment for the Federal ICAM Community, the FICAM Enterprise Architecture was released to this site for continuous refinement and improvement.
Stakeholders and partners are encouraged to regularly review this information and provide comments and recommended edits on how it can be improved, clarified, or updated to support agency knowledge and ICAM implementation. Source files, final records, and future revisions will be managed by the FICAM Program, with guidance and support from the CIO Council’s ICAMSC.

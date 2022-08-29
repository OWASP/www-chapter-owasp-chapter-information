---

layout: col-sidebar
title: OWASP Chapter Information
tags: example-tag
region: North America
meetup-group:

---
## Welcome
Include some information here about your chapter

## Participation
The Open Web Application Security Project (OWASP) is a nonprofit foundation that works to improve the security of software. All of our projects ,tools, documents, forums, and chapters are free and open to anyone interested in improving application security. 

Chapters are led by local leaders in accordance with the [Chapters Policy](/www-policy/operational/chapters). Financial contributions should only be made online using the authorized online donation button. 

Everyone is welcome and encouraged to participate in our [Projects](/projects/), [Local Chapters](/chapters/), [Events](/events/), [Online Groups](https://groups.google.com/a/owasp.com/){:target='_blank'}, and [Community Slack Channel](https://owasp.slack.com/){:target='_blank'}. We especially encourage diversity in all our initiatives. OWASP is a fantastic place to learn about application security, to network, and even to build your reputation as an expert. We also encourage you to be [become a member](/membership/) or consider a [donation](/donate/) to support our ongoing work.

## FAQ

* Where can ALL the approved OWASP Policies be found? 
  All of OWASP's approved policies are publicly posted on the OWASP website for transparency for all to read.[OWASP POLICY page](https://owasp.org/www-policy/)
   
* Where is the OWASP Foundation's financial information? All of the Foundation's financial information is posted for transparency on the [Finance page](https://owasp.org/finance/) The [2022 Approved Budget](https://owasp.org/www-staff/budget/2022) can be found on the OWASP website finance page. 

* Where can OWASP's current financial statements? 
The OWASP Board meeting agenda/minutues is open to the public as well as posted on the [OWASP wesbite/Global Board page](https://owasp.org/www-board/)for anyone to read. OWASP outsources all accounting to Virtual  Click on any months's agenda/minutes and
* What are shared services does the Foundation offer all chapter and how do I request them?
 Meetup Group Pro and Shared Zoom account -> Submit a [Contact Us - Chapter Support - Request for Shared Service ticket](https://owasporg.atlassian.net/servicedesk/customer/portals)

* Are chapters required to hold events? 
  No, chapters are only required to hold 3 meeting activites, in 12 months. Meetings are informal repeatable gatherings of two or more people that has been convened for the purpose of achieving a common goal through verbal interaction, such as sharing information or reaching agreemeent. Meetings may occur face-to-face or virtually.
* Events are now seperate from chapters and chapter meetings. See the OWASP Event policy on the procedures to follow if you would like to submit to hold an approved OWASP event. The [OWASP Events team](mailto:events@owasp.com) will review you request and respond. 



Standard Chapter Page Template
This is an example of a Project or Chapter page.
Please change these items to indicate the actual information you wish to present. In addition to this information, the 'front-matter' above the text should be modified to reflect your actual information.  An explanation of each of the front-matter items is below:

{front matter for this file}

```
- layout: This is the layout used by project and chapter pages.  You should leave this value as col-sidebar
- title: This is the title of your project or chapter page, usually the name.  For example, OWASP Zed Attack Proxy or OWASP Baltimore
- tags: This is a space-delimited list of tags you associate with your project or chapter.  If you are using tabs, at least one of these tags should be unique in order to be used in the tabs files (an example tab is included in this repo) 
- region: This is the region you are in according to our data
```

{copy for this file (index.md)}
Replace the text above the commented area with your information in the format below:
```
## Welcome
Include some information here about your chapter

## Participation
The Open Web Application Security Project (OWASP) is a nonprofit foundation that works to improve the security of software. All of our projects ,tools, documents, forums, and chapters are free and open to anyone interested in improving application security. 

Chapters are led by local leaders in accordance with the [Chapter Leader Handbook](/www-policy/rules-of-procedure/chapter-handbook). Financial contributions should only be made online using the authorized online donation button. To be a SPEAKER at ANY OWASP Chapter in the world simply review the [speaker agreement](/www-policy/speaker-agreement) and then contact the local chapter leader with details of what OWASP Project, independent research, or related software security topic you would like to present.

Everyone is welcome and encouraged to participate in our [Projects](/projects), [Local Chapters](/chapters), [Events](/events), [Online Groups](https://groups.google.com/a/owasp.com/){:target='_blank'}, and [Community Slack Channel](https://owasp.slack.com/){:target='_blank'}. We especially encourage diversity in all our initiatives. OWASP is a fantastic place to learn about application security, to network, and even to build your reputation as an expert. We also encourage you to be [become a member](/membership) or consider a [donation](/donate) to support our ongoing work.

## Next Meeting/Event
---------------------
{% comment %}
{% include chapter_events.html group=page.meetup-group %}
{% endcomment %}

```
{info.md}

This separate file is where you should place links to your Google Group and Meetup page. It will be automatically rendered in the column sidebar.

{leaders.md}

Another separate file that should simply include each leaders name with mailto link as a list. It will also be automatically rendered in the column sidebar.

-->

---
title: Teaching
layout: collection
permalink: /teaching
group: teaching
---

## Courses Taught

{% assign courses_grouped = site.data.courses | group_by: 'coursegroup' | sort: 'coursesemesterid' %}
{% for group in courses_grouped %}

### {{group.name}}

<table class="stack">
  <thead>
    <tr>
      <th>Semester</th>
      <th>Format</th>
      <th>Assignments</th>
    </tr>
  </thead>
  <tbody>
{% for item in group.items %}
    <tr>
      <td data-label="Semester">{% if item.courseid.size > 1 %}<a href="/courses/{{item.courseid}}">{% endif %}{{item.coursesemester}}{% if item.courseid.size > 1 %}</a>{% endif %}</td>
      <td data-label="Format">{% if group.name == "Digital History for Undergraduates" or  group.name == "Medieval Survey" %}{{item.course}}: {% endif %}{{item.coursetype}}</td>
      <td data-label="Short Desc">{{item.coursegrading}}</td>
    </tr>
{% endfor %}
  </tbody>
</table>
{% endfor %}

When I began teaching history, my primary goal was to help students understand the skills involved in historical practice as a way to accommodate, synthesize and intelligently use the ever-increasing volume of communication they deal with, both personally and professionally. The high-level critical thinking and analysis we employ to deconstruct, contextualize and synthesize primary and secondary sources can be used equally well in support of a historical argument, to analyze a voting choice, or to justify an important business decision. In an early course evaluation, though, a student expressed disappointment that my assignments were too focused on supporting an argument with evidence. While I was thrilled that the student felt comfortable using a newly learned historian's tool kit, I was also reminded that historical practice sometimes overshadows the wonder that comes with exploring a world full of new names, dates, and places. My ongoing teaching challenge is thus to both demonstrate the utility of historical practice and simultaneously communicate my awe of and enthusiasm for exploring the past.

## Curriculum development

Curriculum development at the campus level has occupied a portion of my service duties, at both the undergraduate and graduate level. Each of these curriculum-development efforts has centered on the ways in which humanities learning can be augmented by digital methods at the same time that we encourage students to question the assumptions and algorithms built into those digital methods.

At the graduate level, I served on IU Bloomington's Digital Arts and Humanities PhD Certificate creation committee in 2014. On my appointment as IDAH’s co-director in August of 2017, I developed the curricular and administrative infrastructure necessary to launch the program based on that 2014 committee's design, including the recruiting and convening of a curriculum committee to oversee the development, submission and teaching of new courses to meet the program requirements, and advising prospective students. Since Spring of 2018, we've done individual advising each semester for 40 individual students, admitted 24 to the program overall, and awarded 10 minors and certificates.

At the undergraduate level, I've been involved in the development of several undergraduate programs that center technical and scientific practice in the critical lens of humanities interpretation. ASURE, the program has been on offer for College direct admits since Fall of 2018 and includes a fall-semester introductory course, which I chaired a subcommittee to develop, and a spring-semester hands-on research course, for which I developed and taught A200 Digital Public History. These curricular-development efforts also include a committee seat on the College's Undergrad Computing Task Force and its subsequent Committee on Undergraduate Computing in the College, which resulted in a Spring 2020 report that lays out concrete curricular programming, in several tracks, to prepare students for disciplinary-specific use of technology in service of their chosen humanities majors.

<div class="flexible-article-image-right">
<div class="thumbnail" markdown="1" >
[![Born Digital Dissertation Support]({{ site.baseurl }}/assets/img/DAHCertRecipient_BorgoTon.png "Born Digital Dissertation Support"){:.intextright}](https://twitter.com/IUBHistory/status/1192801229941936128){: target="_blank"}
</div>
</div>

## Course development

My course development is either oriented toward teaching digital methods for historical argument or is "digitally inflected" and uses digital methods where appropriate to support the learning of historical content in a topics course. As I develop or redevelop a course, I keep a single guiding principle in mind: history's systematic approach to interpreting documents in service of rebuilding historical context and exploring change and continuity over time. While a professional historian can and should push the boundaries of that system in order to create new knowledge, our students often need scaffolding before they can be asked to use all of these skills together. This approach means each course has two practical goals for students: a learned independence that fosters willingness to make mistakes, which in turn supports the construction of open-ended historical argumentation. I emphasize classroom-based activities over lecture to give students access to expert guidance in class, so that guidance can shape their reading and research outside of class.

This approach is reflected in student evaluations. Across all classes, evaluations consistently note the emphasis on learning in class, on having high expectations for student work, and on instructor support for in-class projects. Clarity of expectations has been less consistent, a rating which I'm willing to accept for the sake of encouraging students to set their own expectations, and which I believe is more prevalent in my digital history courses, which require undergraduates to undertake an initially scary digital-history research project from the ground up in a single semester (see H301 below). To address this gap, I start each semester by clearly communicating my preference for learning over grading, which I have supported in all of my classrooms with generous grading policies that encourage mistakes and revisions.

<iframe id="kaltura_player" src="https://cdnapisec.kaltura.com/p/1751071/sp/175107100/embedIframeJs/uiconf_id/26683571/partner_id/1751071?iframeembed=true&playerId=kaltura_player&entry_id=1_h59vdccx&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=1_cslshiil" width="400" height="285" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="Kaltura Player" style="float:right;"></iframe>

In all of these courses, I use what I've affectionately nicknamed a "Living Syllabus", [documented by a 2015 CITL faculty spotlight](https://citl.indiana.edu/teaching-resources/faculty-spotlights/kalani-craig.html){: data-info="url" target="_blank"}, that replaces the static syllabus with several pages in our learning-management system, Canvas, and uses cloud storage to archive and organize the work students do in class. The end result is a body of resources collaboratively built by students in the class, with my guidance, that brings all of their work over the course of the semester together into an archive. I start with individual Canvas assignments for each reading assignment and due dates easily accessible from the Canvas calendar. I then use the Canvas web-pages feature to build a course home page that changes, course-session by course-session, linking to the day's reading, any resources students might need for in-class activities that day, and to the specific location in our cloud storage where I'd like them to save their work. 

<iframe id="kaltura_player" src="https://cdnapisec.kaltura.com/p/1751071/sp/175107100/embedIframeJs/uiconf_id/26683571/partner_id/1751071?iframeembed=true&playerId=kaltura_player&entry_id=1_3wjv5tys&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=1_28rnmg9v" width="400" height="285" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="Kaltura Player" style="float:right;"></iframe>

The syllabi in this packet were originally structured as interactive web sites on this model to support daily active-learning engagement. I've provided a brief 3-minute tour of one course to model how students interact with the syllabus to engage in in-class inquiry, team-based argumentation and writing, and the creation of an activity archive built over the course of the semester. While H213 The Black Death and H301 Digital History are both well developed courses with several versions of each course in place, I've chosen to feature B200 Medieval Saints and Sinners as the case study for the syllabus walkthrough and the video demo of my teaching practice. As a new course prep that hasn't been repeated since it's initial offering, it provides a good example of how I bring all of the different elements of my appointment into conversation. It's 2 years old, so I had a well developed digital history and Black Death course at the undergraduate level to draw on; at the same time, because it's now 2 years old, I can point to specific elements of this class that made it into the digital history courses that took place in the two following semesters, and I'm using the grading scheme from Saints and Sinners in a redeveloped Black Death course for the Fall 2020.

From small to large classrooms, from teaching to research and back again, with an eye to assessing each course activity at a small scale, the "Living Syllabus" is emblematic on a small scale of how I look at the evolving framework of my teaching from semester to semester on a larger scale, so that even well-developed courses get a critical look each time I teach them.


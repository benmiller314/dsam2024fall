---
layout: featuredimage
featured_image: course-title.png
featured_alt: {{site.course.featured_alt}}
featured_width: 28%
---

<h1>{{site.course.name}}</h1>
<h2>{{site.course.description}}</h2>

{{site.course.term}}, {{site.course.time}}, in {{site.course.room}}

{{site.course.instructor.name}}, PhD, MFA \
{{site.course.instructor.email}}

Office hours: {{site.course.instructor.office_hours}}, {{site.course.instructor.office}}

<div class="alert alert-info">
NB: All this information and more will be accessible, in its most up-to-date form, on our class website: <strong><a href="{{site.github_url}}">{{site.github_url}}</a></strong>
</div>

## Contents
* [Major Projects](#major-projects)
* [Course Policies](#course-policies)
* [Resources at Pitt](#resources-at-pitt)
* [Assignment Schedule](#assignment-schedule)


<!-- ## Major Projects -->

{% include_relative projects.md %}

<!-- ## Course Policies -->

{% include_relative policies.md %}

<!-- ## Resources at Pitt -->

NB: Additional resources can be found on the course site at [{{site.github_url}}/resources]({{site.github_url}}/resources).

{% include microcontent.html content=resources.services_at_pitt %} <!-- This doesn't work: it's just pulling in an empty div. -->


## Assignment Schedule

{% include_relative schedule.md %}

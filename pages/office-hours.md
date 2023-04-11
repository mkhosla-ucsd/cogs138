---
layout: default
title: Office Hours
has_children: false
nav_order: 4
permalink: /office-hours/
---

{% assign variables = site.data[site.data_folder].variables %}
{% assign course_calendar = site.data[site.data_folder].course_calendar %}

# Office Hours


Office hours are a great place to personally interact. Beyond projects and course material, we are interested in your goals, career endeavors, and what you want to gain from COGS 9. Data Science is a rapidly changing field and there is always a lot to discuss!

<table style="table-layout: fixed; text-align: center; width: 100%;">
    <thead>
        <tr class="header">
            <th style="width: 40%;"> Staff </th>
            <th style="width: 30%;"> Day & Time </th>
            <th style="width: 30%;"> Location </th>
            <!-- <th style="width: 12.5%;"> Link </th> -->
            <!-- <th style="width: 12.5%;"> Pass </th> -->
        </tr>
    </thead>
    <tbody>
        {% for oh in variables.instructor.office_hours %}
        <tr>
            <td> {{ variables.instructor.name }} </td>
            <td> {{ oh.day }} {{ oh.time }} </td>
            <td> {{ oh.location }} </td>
            <!-- <td> <a href='{{ oh.zoom_link }}' target="_blank" rel="noopener">Join &#x2197;</a> </td> -->
            <!-- <td> {% if oh.zoom_pw %} {{ oh.zoom_pw }} {% endif %} </td> -->
        </tr>
        {% endfor %}
        {% for row in variables.teaching_assistants %}
            {% for oh in row.office_hours %}
            <tr>
                <td> {{ row.name }} </td>
                <td> {{ oh.day }} {{ oh.time }} </td>
                <td> {{ oh.location }} </td>
                <!-- <td> <a href='{{ oh.zoom_link }}' target="_blank" rel="noopener">Join &#x2197;</a> </td> -->
                <!-- <td> {% if oh.zoom_pw %} {{ oh.zoom_pw }} {% endif %} </td> -->
            </tr>
            {% endfor %}
        {% endfor %}
        <!-- {% for row in variables.instructional_assistants %} -->
            <!-- {% for oh in row.office_hours %} -->
            <!-- <tr> -->
                <!-- <td> {{ row.name }} </td> -->
                <!-- <td> {{ oh.day }} {{ oh.time }} </td> -->
                <!-- <td> {{ oh.location }} </td> -->
                <!-- <td> <a href='{{ oh.zoom_link }}' target="_blank" rel="noopener">Join &#x2197;</a> </td> -->
                <!-- <td> {% if oh.zoom_pw %} {{ oh.zoom_pw }} {% endif %} </td> -->
            <!-- </tr> -->
            <!-- {% endfor %} -->
        <!-- {% endfor %} -->
    </tbody>
</table>

Zoom Links can be found on Canvas homepage.

{: .note .fs-3 }
If you are unable to join or are having other issues, please reach out before or after class (I try to get to class a few minutes early and can stay for a few minutes after, although I do teach a class right after this one so can't stay too long) or in the discussion sections.

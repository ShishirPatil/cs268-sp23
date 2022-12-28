---
layout: default
---


# Graduate Comupter Networks (Spring 2023)

* **When**: Tuesday and Thursday from 9:30am to 10:59am
* **Where**: Wheeler 24 (Zoom policy TBD)
* **Instructor**: [Sylvia Ratnasamy](https://eecs.berkeley.edu/~sylvia)
* **GSI**: [Shishir Patil](https://eecs.berkeley.edu/~shishirpatil)
* **Office Hours:**: TBD Sylvia at SODA #413
* **Announcements**: Ed (please send us an email if you are not added by Jan 15) 
* **Sign-up to Present**: Every student should sign-up to present. More information will be shared in class


## Course Description

CS268 is a graduate level course in computer networks. The course involves readings, lectures, and discussions throughout the semester along with a project. We will read about 50 research papers on various aspects of computer networking: internetworking principles, LAN/WAN technologies, routing, congestion control, measurement, management, multicast, router design. We will also look at some of the recent emerging trends and their impact on networking. Students are expected to read papers before the class, submit a short summary for each paper, and participate in the discussion during the class. Lectures will be conducted in an interactive fashion and everyone is expected to participate. You will be graded for both the paper summaries and class discussion. 

## Projects

A major component of this course, both in terms of your grade and your time, is a term project. The project in CS268 is an open-ended research project. The goal is to investigate new research ideas and solutions. The project requires a proposal, and a final report (both written and presented). 


## Grading

Grades will be largely based on class participation and projects.  In addition, we will require weekly paper summaries submitted before class.
* **Project:** 50%
* **Paper presentation:** 25%
* **Paper reviews and class participation:** 25%

Each student will present and lead the discussion on one reading assignment from the syllabus.

For each paper you read you are required to provide a short review. You will have to review no more than two papers per class. The goal of these reviews is to help you synthetise the main ideas and concepts presented in each paper. Details on when and how to submit your review will be posted to piazza. 



## Course Syllabus
{% capture dates %}
1/17/23
1/19/23
1/24/23
1/26/23
1/31/23
2/02/23
2/07/23
2/09/23
2/14/23
2/16/23
2/21/23
2/23/23
2/28/23
03/02/23
03/07/23
03/09/23
03/14/23
03/16/23
03/21/23
03/23/23
03/28/23
03/30/23
04/04/23
04/06/23
04/11/23
04/13/23
04/18/23
04/20/23
04/25/23
04/27/23
05/02/23
05/04/23
05/09/23
05/11/23
{% endcapture %}
{% assign dates = dates | split: " " %}

This is a tentative schedule. Specific readings are subject to change.

<a href="#today"> Jump to Today </a>

<table class="table table-striped syllabus">
<thead>
   <tr>
      <th style="width: 5%"> Week </th>
      <th style="width: 10%"> Date </th>
      <th style="width: 85%"> Topic </th>
   </tr>
</thead>
<tbody>


{% include syllabus_entry %}
[//]: <> (lecture 1)
## Introduction and Course Overview (Sylvia)
This lecture will be an overview of the class, requirements.

* Lecture slides: [[pdf](tbd)]

<div class="reading">
<div class="optional_reading" markdown="1">
* [Turing](https://www.youtube.com/watch?v=JLAfLWE76fE) 
</div>
</div>


{% include syllabus_entry %}
[//]: <> (lecture 2)
## Classics: Internet Architecture (Sylvia)

* Reminder to submit your review before xx pm at yy link.

<div class="reading">
<div class="required_reading" markdown="1">
* [Design](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers//darpa-internet.pdf)
</div>
<div class="optional_reading" markdown="1">
* [E2E](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers//saltzer-e2e.pdf)
* [Tussles](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers/tussles.pdf)
</div>
</div>

{% include syllabus_entry %}
[//]: <> (lecture 3)
## Classics: Beyond best-effort (Sylvia)

<div class="reading">
<div class="required_reading" markdown="1">
* [Active](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers//active.pdf)
* [QoS](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers//rfc1633.pdf)
</div>
<div class="optional_reading" markdown="1">
* [Debate](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers/Active-vs-E2E.pdf)
</div>
</div>

{% include syllabus_entry %}
[//]: <> (lecture 4)
## Guest Lecture ([Manya Ghobadi](https://people.csail.mit.edu/ghobadi/))

<div class="reading">
<div class="required_reading" markdown="1">
* TBD
</div>
</div>




{% include syllabus_entry %}
[//]: <> (lecture 5)
## Classics: Beyond unicast (Sylvia)

<div class="reading">
<div class="required_reading" markdown="1">
* [Multicast](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers/cbt.pdf)
* [Overlays](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers//esm.pdf)
</div>
<div class="optional_reading" markdown="1">
* [Deering](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers//Deering88.pdf)
* [Sprint Experience](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers/diot-multicast.pdf)
</div>
</div>

{% include syllabus_entry %}
[//]: <> (lecture 6)
## Congestion Control

* Reminder: Student presentation start this week. 

<div class="reading">
<div class="required_reading" markdown="1">
* [VanCC](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers//congavoid.pdf)
* [XCP](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers//xcp.pdf)
</div>
<div class="optional_reading" markdown="1">
* [RCP](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers/rcp-ccr.pdf)
</div>
</div>




<!-- {% include syllabus_entry %}
# RRR Week

{% include syllabus_entry %}
# Project Presentations -->


</td>
</tr>
</tbody>
</table>



<script type="text/javascript">


var current_date = new Date();
var rows = document.getElementsByTagName("th");
var finished =  false;
for (var i = 1; i < rows.length && !finished; i++) {
   var r = rows[i];
   if (r.id.startsWith("counter_")) {
      var fields = r.id.split("_")
      var week_div_id = "week_" + fields[2]
      var lecture_date = new Date(fields[1] + " 23:59:00")
      if (current_date <= lecture_date) {
         finished = true;
         r.style.background = "orange"
         r.style.color = "black"
         var week_td = document.getElementById(week_div_id)
         week_td.style.background = "#043361"
         week_td.style.color = "white"
         var anchor = document.createElement("div")
         anchor.setAttribute("id", "today")
         week_td.prepend(anchor)
      }
   }
}

$(".reading").each(function(ind, elem) {
   var optional_reading = $(elem).find(".optional_reading");
   if(optional_reading.length == 1) {
      optional_reading = optional_reading[0];
      optional_reading.setAttribute("id", "optional_reading_" + ind);
      var button = document.createElement("button");
      button.setAttribute("class", "btn btn-primary btn-sm");
      button.setAttribute("type", "button");
      button.setAttribute("data-toggle", "collapse");
      button.setAttribute("data-target", "#optional_reading_" + ind);
      button.setAttribute("aria-expanded", "false");
      button.setAttribute("aria-controls", "#optional_reading_" + ind);
      optional_reading.setAttribute("class", "optional_reading_no_heading collapse")
      button.innerHTML = "Additional Optional Reading";
      optional_reading.before(button)
   }
   
})


$(".details").each(function(ind, elem) {
      elem.setAttribute("id", "details_" + ind);
      var button = document.createElement("button");
      button.setAttribute("class", "btn btn-primary btn-sm");
      button.setAttribute("type", "button");
      button.setAttribute("data-toggle", "collapse");
      button.setAttribute("data-target", "#details_" + ind);
      button.setAttribute("aria-expanded", "false");
      button.setAttribute("aria-controls", "#details_" + ind);
      elem.setAttribute("class", "details_no_heading collapse")
      button.innerHTML = "Detailed Description";
      elem.before(button)
   })

</script>



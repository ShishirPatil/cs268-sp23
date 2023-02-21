---
layout: default
---


# Graduate Computer Networks (Spring 2023)

* **When**: Tuesday and Thursday from 9:30am to 10:59am
* **Where**: Wheeler 24. Lectures are not recorded and in-person attendance is required
* **Instructor**: [Sylvia Ratnasamy](https://eecs.berkeley.edu/~sylvia)
* **GSI**: [Shishir Patil](https://eecs.berkeley.edu/~shishirpatil)
* **Office Hours**: Sylvia on Fridays 9:10-10am at SODA 413, Shishir on Wednesdays 11-11:30am at SODA 465E
* **Announcements**: Ed (please send us an email if you are not added by Jan 15) 
* **Sign-up to Present**: Every student should sign-up to present. More information will be shared in class


## Course Description

CS268 is a graduate level course in computer networks. The course involves readings, lectures, and discussions throughout the semester along with a project. We will read about 50 research papers on various aspects of computer networking: internetworking principles, LAN/WAN technologies, routing, congestion control, measurement, management, multicast, router design. We will also look at some of the recent emerging trends and their impact on networking. Students are expected to read papers before the class, submit a short summary for each paper, and participate in the discussion during the class. Lectures will be conducted in an interactive fashion and everyone is expected to participate. You will be graded for both the paper summaries and class discussion. 

## Projects

A major component of this course, both in terms of your grade and your time, is a term project. The project in CS268 is an open-ended research project. The goal is to investigate new research ideas and solutions. The project requires a proposal, and a final report (both written and presented).

* **10 Feb 2023:** Teams due. Please discuss your project with Sylvia/Shishir for 15 min anytime before 20 Feb 2023.
* **25 Feb 2023:** Project proposals are due



## Grading

Grades will be largely based on class participation and projects.  In addition, we will require weekly paper summaries submitted before class.
* **Project:** 40%
* **Paper presentation:** 30%
* **Paper reviews and in-class participation:** 30%

Each student will present and lead the discussion on one reading assignment from the syllabus.

For each paper you read you are required to provide a short review. You will have to review no more than two papers per class. The goal of these reviews is to help you synthetise the main ideas and concepts presented in each paper. Details on when and how to submit your review will be posted to Ed. 



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

* [Slides](assets/lectures/cs268-2023-L1.pdf)

<div class="reading">
<div class="optional_reading" markdown="1">
* [Turing](https://www.youtube.com/watch?v=JLAfLWE76fE) 
</div>
</div>


{% include syllabus_entry %}
[//]: <> (lecture 2)
## Internet Architecture (Sylvia)

* Reminder to submit your review before 5pm on Jan 18.

<div class="reading">
<div class="required_reading" markdown="1">
* [Clark](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers//darpa-internet.pdf)
* [Active Nets](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers//active.pdf)
</div>
<div class="optional_reading" markdown="1">
* [E2E](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers//saltzer-e2e.pdf)
</div>
</div>

{% include syllabus_entry %}
[//]: <> (lecture 3)
## Beyond best-effort/Unicast (Sylvia)

* Reminder to submit your preferences for which paper your would like to present by Jan 23. 

<div class="reading">
<div class="required_reading" markdown="1">
* [Multicast](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers/cbt.pdf)
* [QoS](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers//rfc1633.pdf)
</div>
<div class="optional_reading" markdown="1">
Background reading
* [Deering](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers//Deering88.pdf)

Advanced Reading
* [JustWorks](http://www.cs.ucl.ac.uk/staff/m.handley/papers/only-just-works.pdf)
</div>
</div>

{% include syllabus_entry %}
[//]: <> (lecture 4)
## Congestion Control ([Manya Ghobadi](https://people.csail.mit.edu/ghobadi/))

<div class="reading">
<div class="required_reading" markdown="1">
* [VanCC](http://web.mit.edu/6.829/www/2020/papers/vanjacobson-congavoid.pdf)
* [XCP](https://web.mit.edu/6.829/www/currentsemester/papers/xcp.pdf) Sections 1-3
</div>
</div>

{% include syllabus_entry %}
[//]: <> (lecture 5)
## Datacenter Networking (Student Led)

* Student presentations start this week.

<div class="reading">
<div class="required_reading" markdown="1">
* [Fat-Tree](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers//al-fares-sigcomm08.pdf) (Alvin Tan)
* [Jellyfish](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers//jellyfish-nsdi12.pdf) (Joonho Whangbo)
</div>
</div>

{% include syllabus_entry %}
[//]: <> (lecture 6)
## Software Defined Networking: Context (Scott Shenker)


<div class="reading">
<div class="required_reading" markdown="1">
* [4D](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers/4D-ccr05.pdf), [OF](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers/openflow.pdf), [video1](https://www.youtube.com/watch?v=c9-K5O_qYgA), [video2](https://www.youtube.com/watch?v=YHeyuD89n1Y)
* [Road](https://www.sigcomm.org/sites/default/files/ccr/papers/2014/April/0000000-0000012.pdf)
</div>
</div>

{% include syllabus_entry %}
[//]: <> (lecture 7)
## Software Defined Networking: Practice (Student Led)

<div class="reading">
<div class="required_reading" markdown="1">
* [B4](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers//b4.pdf) (Simon Mo)
* [ONIX](https://people.eecs.berkeley.edu/~sylvia/cs268-2013/papers//onix.pdf) (Mark Theis)
</div>
</div>

{% include syllabus_entry %}
[//]: <> (lecture 8)
## BGP (Student Led)

* Teams for project are due Feb 10th.

<div class="reading">
<div class="required_reading" markdown="1">
* [Labovitz, SIGCOMM'10](https://dl.acm.org/doi/10.1145/1851182.1851194) (Fuzail Shakir)
* [RCP](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers//rcp-fdna.pdf) (Emily Marx)
</div>
<div class="optional_reading" markdown="1">
* [BGP-notes](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers/hari-bgpnotes.pdf)
* [lec9](https://cs168.io/assets/lectures/9.pdf)
* [lec10](https://cs168.io/assets/lectures/10.pdf)
</div>
</div>

{% include syllabus_entry %}
[//]: <> (lecture 9)
## Programmable Networks (Student Led)

* Project proposals are due on Feb 20th.

<div class="reading">
<div class="required_reading" markdown="1">
* [RMT](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers//rmt.pdf) Sections 1-3 (Daniel Rothchild)
* [Netcache](https://www.cs.cornell.edu/~jnfoster/papers/netcache.pdf) (Rithvik Chuppala)
</div>
<div class="optional_reading" markdown="1">
* [P4](http://www.sigcomm.org/sites/default/files/ccr/papers/2014/July/0000000-0000004.pdf) 
</div>
</div>


{% include syllabus_entry %}
[//]: <> (lecture 10)
## BGP Security [Anees Shaikh](http://ashaikh.com/ashaikh_com/)

<div class="reading">
<div class="required_reading" markdown="1">
* [BGP](https://www.caida.org/catalog/papers/2019_profiling_bgp_serial_hijackers/profiling_bgp_serial_hijackers.pdf)
* [Routing](https://cacm.acm.org/magazines/2021/6/252822-securing-internet-applications-from-routing-attacks/fulltext)
</div>
</div>


{% include syllabus_entry %}
[//]: <> (lecture 11)
## Datacenter Congestion Control ([Nandita Dukkipati](https://research.google/people/author39115/))

<div class="reading">
<div class="required_reading" markdown="1">
* [pFabric](https://dl.acm.org/doi/10.1145/2486001.2486031)
* [Swift](https://dl.acm.org/doi/abs/10.1145/3387514.3406591)
</div>
<div class="optional_reading" markdown="1">
* [Clock Sync](https://www.usenix.org/system/files/conference/nsdi18/nsdi18-geng.pdf) 
</div>
</div>

{% include syllabus_entry %}
[//]: <> (lecture 12)
## WAN Congestion Control (Student Led)

<div class="reading">
<div class="required_reading" markdown="1">
* [Starvation](https://dl.acm.org/doi/pdf/10.1145/3544216.3544223) (Nicholas Ngai)
* [RCS](assets/papers/RCS_SIGCOMM.pdf) (Alex Krentsel)
</div>
</div>

{% include syllabus_entry %}
[//]: <> (lecture 13)
## Peer-to-Peer Networking (Student Led)

<div class="reading">
<div class="required_reading" markdown="1">
* [Chord](https://pdos.csail.mit.edu/papers/chord:sigcomm01/chord_sigcomm.pdf) / [Geometry](https://www.conviva.com/wp-content/uploads/2017/09/The-Impact-of-DHT-Routing-Geometry-on-Resilience-and-Proximity.pdf) (Noelle Davis)
* [deWeb](https://dl.acm.org/doi/10.1145/3544216.3544232) (Michaela Murray)
</div>
</div>

{% include syllabus_entry %}
[//]: <> (lecture 14)
## Net SW (Student Led)

<div class="reading">
<div class="required_reading" markdown="1">
* [Click](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers//click.pdf) (Shreyas Krishnaswamy)
* [mTCP](https://www.usenix.org/system/files/conference/nsdi14/nsdi14-paper-jeong.pdf) (Sean Kim)
</div>
<div class="optional_reading" markdown="1">
* [RouteBricks](https://www.sigops.org/s/conferences/sosp/2009/papers/dobrescu-sosp09.pdf) 
</div>

</div>

{% include syllabus_entry %}
[//]: <> (lecture 15)
## NFV (Student Led)

<div class="reading">
<div class="required_reading" markdown="1">
* [Aplomb](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers/aplomb.pdf) (Efsane Soyer)
* [PIX](https://www.usenix.org/system/files/nsdi22-paper-iyer.pdf) (Shubham Mishra)
</div>
</div>


{% include syllabus_entry %}
[//]: <> (lecture 16)
## Disaggregation (Student Led)

<div class="reading">
<div class="required_reading" markdown="1">
* [Net-Req](https://www.usenix.org/system/files/conference/osdi16/osdi16-gao.pdf) (Sam Son)
* [MIND](https://dl.acm.org/doi/pdf/10.1145/3477132.3483561) (Josh Kang)
</div>
<div class="optional_reading" markdown="1">
* [Vahdat-keynote](https://www.youtube.com/watch?v=Am_itCzkaE0)
* [Partha-ISCA](https://web.eecs.umich.edu/~twenisch/papers/isca09-disaggregate.pdf)
</div>
</div>


{% include syllabus_entry %}
[//]: <> (lecture 17)
## Low-latency (Student Led)

<div class="reading">
<div class="required_reading" markdown="1">
* [cISP](https://www.usenix.org/system/files/nsdi22-paper-bhattacherjee.pdf) (Tess Despres)
* [Acquila](https://www.usenix.org/system/files/nsdi22-paper-gibson.pdf) (Vikranth Srivatsa)

</div>
</div>

{% include syllabus_entry %}
[//]: <> (lecture 18)
## IoT (TBD)

<div class="reading">
<div class="required_reading" markdown="1">
* [TBD]
* [TBD]
</div>
</div>

{% include syllabus_entry %}
[//]: <> (lecture 19)
## Tenant Networking (Student Led)

<div class="reading">
<div class="required_reading" markdown="1">
* [NetHint](https://www.usenix.org/system/files/nsdi22-paper-chen_jingrong.pdf) (Shu Liu)
* [Invisinets] (Miles Wada)
</div>
</div>


{% include syllabus_entry %}
[//]: <> (lecture 20)
## Verification (Student Led)

<div class="reading">
<div class="required_reading" markdown="1">
* [HSA](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers//hsa.pdf) (Preston McCrary)
* [Minesweeper](https://ratul.org/papers/sigcomm2017-minesweeper.pdf) (Reggie Frank)
</div>
</div>


{% include syllabus_entry %}
# Spring Break

{% include syllabus_entry %}
# Spring Break

{% include syllabus_entry %}
[//]: <> (lecture 21)
## Edge ([Ranveer Chandra](https://www.microsoft.com/en-us/research/people/ranveer/))

<div class="reading">
<div class="required_reading" markdown="1">
* [TBD]
* [TBD]
</div>
</div>


{% include syllabus_entry %}
[//]: <> (lecture 22)
## Space (Student Lad)

<div class="reading">
<div class="required_reading" markdown="1">
* [Starlink](https://people.eecs.berkeley.edu/~sylvia/cs268-2019/papers//starlink.pdf) (Tenzin Ukyab)
* [LOON](https://dl.acm.org/doi/pdf/10.1145/3544216.3544231) (Sarah Wooders)
</div>
</div>

{% include syllabus_entry %}
[//]: <> (lecture 23)
## Cellular ([Kurtis Heimerl](https://kurti.sh/))

<div class="reading">
<div class="required_reading" markdown="1">
* [Magma](https://arxiv.org/abs/2209.10001)
* [Congestion](https://kurti.sh/pubs/commgestion_2020.pdf)
</div>
</div>


{% include syllabus_entry %}
[//]: <> (lecture 24)
## Time (Student Led)

<div class="reading">
<div class="required_reading" markdown="1">
* [Clock-sync](https://www.usenix.org/system/files/conference/nsdi18/nsdi18-geng.pdf) (Junsun Choi)
* [FinExch](https://conferences.sigcomm.org/hotnets/2022/papers/hotnets22_goyal.pdf) (Ujjaini Mukhopadhyay)
</div>
</div>

{% include syllabus_entry %}
[//]: <> (lecture 25)
## Networks for ML (TBD)

<div class="reading">
<div class="required_reading" markdown="1">
* [TBD]
* [TBD]
</div>
</div>

{% include syllabus_entry %}
[//]: <> (lecture 26)
## New Directions in Networking (Sylvia)

<div class="reading">
<div class="required_reading" markdown="1">
* [TBD]
* [TBD] (Jiachen Yuan)
</div>
</div>

{% include syllabus_entry %}
# Project Presentations

{% include syllabus_entry %}
# Project Presentations


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



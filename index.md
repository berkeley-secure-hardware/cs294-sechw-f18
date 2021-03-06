## Instructors

<table style="table-layout: fixed; font-size: 88%;">
  <thead>
    <tr>
      <th style="width: 25%;"><img height="200px" src="https://people.eecs.berkeley.edu/~dawnsong/dawn-berkeley.jpg" alt="Dawn Song"></th>
      <th style="width: 25%;"><img height="200px" src="http://people.eecs.berkeley.edu/~krste/k.jpg" alt="Krste Asanović"></th>
      <th style="width: 25%;"><img height="200px" src="https://cseweb.ucsd.edu/~dkohlbre/2016_dkpic.png" alt="David Kohlbrenner"></th>
      </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://people.eecs.berkeley.edu/~dawnsong/">Dawn Song</a></td>
      <td><a href="https://people.eecs.berkeley.edu/~krste/">Krste Asanović</a></td>
      <td><a href="https://people.eecs.berkeley.edu/~dkohlbre/">David Kohlbrenner</a></td>
    </tr>
    <tr>
      <td>Professor, <a href="https://eecs.berkeley.edu/">EECS</a></td>
      <td>Professor, <a href="https://eecs.berkeley.edu/">EECS</a></td>
      <td>Postdoc, <a href="https://eecs.berkeley.edu/">EECS</a></td>
    </tr>
  </tbody>
</table>

## Volunteer Teaching Assistant
Volunteer TA: Dayeol Lee

## Lectures

**Time**: Monday 10:00--11:30 am

**Location**: Soda 405

## Office Hours

Contact David as needed. (dkohlbre@berkeley.edu)

## Piazza and Mailing List

To receive announcements on information about the course please sign
up for the [public mailing
list](https://groups.google.com/forum/#!forum/cs-294-156-f18-all) for
future announcements. You can add yourself to the list by clicking the
link and "Join group". Be sure to be signed in to your Google account.

[Piazza](https://piazza.com/class/jlbppizryjy74k)

## Course description

Secure hardware is an increasing part of all system designs, from TPMs
in every laptop to hardware/software enclaves in every
phone. Different types of secure hardware must make different security
and performance tradeoffs and contend with different adversaries.  We
will discuss current and classic research papers in the area, as well
as state of the art deployed designs. We will have a special focus on
the development of hardware enclaves: secure hardware components
designed to support verifiable and trusted execution of programs
remotely.

The course is 3-units, and will consist of several research paper
readings per week, in-class discussions of the papers, and a large
course project per project group.

We require that students have taken at least one architecture course
previously, and strongly recommend that students have a background in
relevant security topics.

Course intro [slides](cs294-156-f18-overview.pdf).

## Syllabus
<table style="table-layout: fixed; font-size: 88%;">
  <thead>
    <tr>
      <th style="width: 5%;">Date</th>
      <th style="width: 40%;">Topic</th>
      <th style="width: 55%;">Readings</th>
      <th style="width: 20%;">Talk</th>
      <th style="width: 10%;">Deadlines</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>08/27</td>
      <td>Secure Hardware guest lecture</td>
      <td></td>
      <td>Guest lecture by Paul Kocher</td>
      <td></td>
    </tr>
    <tr>
      <td>09/03</td>
      <td>No Class, Labor Day</td>
      <td>Start on 9/10 readings</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>09/10</td>
      <td>Enclaves I</td>
      <td><ul><li><a href="https://eprint.iacr.org/2016/086.pdf"> Intel SGX Explained </a><br>
       Sections 1, 4, 5.1-5.4, 5.6, 5.8</li>
      <li><a href="http://infocenter.arm.com/help/topic/com.arm.doc.prd29-genc-009492c/PRD29-GENC-009492C_trustzone_security_whitepaper.pdf"> ARM TrustZone whitepaper</a><br>Pages 3-1 to 3-16 </li></ul></td>
      <td>Deployed enclaves</td>
      <td>Team Formation Due 09/10<br>
      <a href="https://goo.gl/forms/WocFXgnNgXpJAWmV2">Discussion Questions</a> 9/7</td>
    </tr>
    <tr>
      <td>09/17</td>
      <td>Side channel attacks on hardware</td>
      <td><ul><li><a href="https://foreshadowattack.eu/">Foreshadow + Foreshadow-NG</a> (-NG is short, read both!)</li>
      <li><a href="https://vvdveen.com/publications/drammer.pdf"> Drammer</a>: Deterministic Rowhammer Attacks on Mobile Platforms</li></ul></td>
      <td></td>
      <td>      <a href="https://goo.gl/forms/FrcGQUQB2O3tqbxw1">Discussion Questions</a> 9/14</td>
    </tr>
    <tr>
      <td>09/24</td>
      <td>Side channel defenses</td>
      <td><ul><li><a href="https://ieeexplore.ieee.org/abstract/document/6237011/">TimeWarp</a></li>
      <li><a href="https://eprint.iacr.org/2018/418.pdf">DAWG</a>: A Defense Against Cache Timing Attacks in Speculative Execution Processors</li>
      <li>OPTIONAL: <a href="https://www.usenix.org/system/files/conference/usenixsecurity16/sec16_paper_costan.pdf">Sanctum</a></li></ul></td>
      <td></td>
<td>Project Proposals Due 09/27<br>
       <a href="https://goo.gl/forms/k2JyUkzZ3GGI3wit2">Discussion Questions</a> 9/21</td>
    </tr>
    <tr>
      <td>09/27 : 10am</td>
      <td>Office Hours on Speculative Attacks</td>
      <td>Bring any papers you have questions on!</td>
      <td>Location Soda 580</td>
      <td></td>
    </tr>

    <tr>
      <td>10/01</td>
      <td>DRAM for secure hardware</td>
      <td><ul><li><a href="https://eprint.iacr.org/2016/204.pdf">SGX Memory Encryption</a> (Sec 4 may be challenging, don't worry too much)</li>
      <li><a href="https://users.ece.utexas.edu/~tiwari/pubs/CCS-13-phantom.pdf">PHANTOM</a>: Practical Oblivious Computation in a Secure Processor</li>
      <li>OPTIONAL: <a href="https://people.eecs.berkeley.edu/~krste/papers/phantom-carl2013.pdf">PHANTOM Memory controller</a></li></ul></td>
      <td></td>
      <td>      <a href="https://goo.gl/forms/eTb81mwr1fsshfcO2">Discussion Questions</a> 9/28</td>
    </tr>
    <tr>
      <td>10/08</td>
      <td>GPUs</td>
      <td><ul><li><a href="https://www.microsoft.com/en-us/research/uploads/prod/2018/09/Graviton-Trusted-Execution-Environments-on-GPUs.pdf">Graviton</a></li>
      <li>OPTIONAL: <a href="https://www.vusec.net/wp-content/uploads/2018/05/glitch.pdf">Grand Pwning Unit</a></li>
      <li>OPTIONAL: <a href="http://www.cs.ucr.edu/~nael/pubs/ccs18.pdf">Rendered Insecure</a></li></ul></td>
      <td></td>
      <td>      <a href="https://goo.gl/forms/hdDOExBTxZB5jJR62">Discussion Questions</a> 10/5</td>

    </tr>
    <tr>
      <td>10/15</td>
      <td>No class, ADEPT lab outing</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>10/22</td>
      <td>Mitigation of side-channels and speculative attacks</td>
      <td><ul><li><a href="https://dl.acm.org/citation.cfm?id=3214297">Spectres, virtual ghosts, and hardware support</a></li>
      <li><a href="https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-dong.pdf">Shielding Software From Privileged Side-Channel Attacks</a></li></ul></td>
      <td>John Criswell</td>
      <td>      <a href="https://goo.gl/forms/sETLhwfMPRSuWm7i2">Discussion Questions</a> 10/19</td>
    </tr>
    <tr>
      <td>10/29</td>
      <td>Formal verification of hardware</td>
      <td><ul><li><a href="https://people.eecs.berkeley.edu/~sseshia/pubdir/ccs17.pdf">A Formal Foundation for Secure Remote Execution of Enclaves</a></li>
      <li><a href="https://www.usenix.org/system/files/conference/usenixsecurity16/sec16_paper_costan.pdf">Sanctum</a></li></ul></td>
      <td>Sanjit Seshia</td>
      <td><a href="Project-status-reqs.pdf">Project Progress Report</a> Due 10/29 - <a href="https://goo.gl/forms/lWWGWXSlqxjCypiA3">here</a><br><br>
      <a href="https://goo.gl/forms/OjuYaBVU4Zd11tQ23">Discussion Questions</a> 10/26</td>
    </tr>
    <tr>
      <td>11/05</td>
      <td>Physical and glitch attacks</td>
      <td><ul><li><a href="http://static.usenix.org/events/smartcard99/full_papers/kommerling/kommerling.pdf">Design Principles for Tamper-Resistant Smartcard Processors</a></li>
      <li><a href="https://eprint.iacr.org/2004/100.pdf">The Sorcerer’s Apprentice Guide to Fault Attacks</a></li></ul></td>
      <td></td>
      <td>      <a href="https://goo.gl/forms/sl0ZKPLR3bd07MWN2">Discussion Questions</a> 11/2</td>
    </tr>
    <tr>
      <td>11/12</td>
      <td>No Class, Veterans Day</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>11/19</td>
      <td>FPGA remote physical side channels</td>
      <td><ul><li><a href="https://www.cs.ox.ac.uk/files/9835/fpga.pdf">Leaky Wires: Information Leakage and Covert Communication Between FPGA Long Wires</a></li>
      <li><a href="https://cpb-us-w2.wpmucdn.com/sites.coecis.cornell.edu/dist/7/89/files/2018/04/SP2018-FPGA-2m12dnp.pdf">FPGA-Based Remote Power Side-Channel Attacks</a></li></ul></td>
      <td></td>
      <td>      <a href="https://goo.gl/forms/MmMMj03WhCdOFVDR2">Discussion Questions</a> 11/16</td>
    </tr>
    <tr>
      <td>11/26</td>
      <td>Project Presentations</td>
      <td></td>
      <td>Instructions for paper and presentation <a href="Project-report-presentation.pdf">here</a></td>
      <td>Project Report Due 11/30</td>
    </tr>
  </tbody>
</table>


## Class format and project

This is a paper reading and project class. Each week, students are
expected to complete reading assignments before class and participate
actively in class discussion.

Students must submit a set of questions or ideas for discussion about
the assigned papers, due Friday at noon before class. Submit weekly
questions to the form linked in the deadlines section for that week.

Students will also form project groups and complete a research
project. The final project/deliverable will be a team presentation and
a paper/report on the project.

Some project ideas available [here](projects.html)

[Proposal guidelines](Project-proposal-reqs.pdf), submit proposal [here](https://goo.gl/forms/eJFsKlzFJ2ujGH1H3).

Paper and presentation instructions <a href="Project-report-presentation.pdf">here</a>.

## Grading

<ul>
  <li>20% class participation</li>
  <li>20% weekly reading assignment</li>
  <li>60% project</li>
</ul>

## Enrollment information

Enrollment space is limited for undergraduates. If you are an
undergrad would like to enroll in the class, Please fill out **[this
form](https://docs.google.com/forms/d/e/1FAIpQLScskMACikbExvLm1Pbhf6AeIj0F6-ZXWAr9lOteJYqV3VMKQQ/viewform?usp=sf_link)**. Accepted
students will be given instructor codes to register for the
class. Decisions for admission will be released on a rolling
basis. Due to limited space, please apply as soon as possible.

## Additional Notes

For students who need computing resources for the class project, we recommend you to look into AWS educate program for students. You’ll get 100 dollar’s worth of sign up credit. Here’s the
[link](https://aws.amazon.com/education/awseducate/apply/).

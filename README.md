# Data Structures and Algorithms Using Java

- [DSA Using Java](#dsa-using-java)
  - [Announcements](#announcements)
  - [Schedule](#schedule)
  - [Session - 1 Contents](#january-1)

## Announcements

<script>
  var countDownDate = new Date("Jan 09, 2023 09:30:00").getTime();
  var myfunc = setInterval(function() {
    var now = new Date().getTime();
    var timeleft = countDownDate - now;
        
    // Calculating the days, hours, minutes and seconds left
    var days = Math.floor(timeleft / (1000 * 60 * 60 * 24));
    var hours = Math.floor((timeleft % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    var minutes = Math.floor((timeleft % (1000 * 60 * 60)) / (1000 * 60));
    var seconds = Math.floor((timeleft % (1000 * 60)) / 1000);

    document.getElementById("time").innerHTML = 'The Training starts in ' + days + ' days ' + hours + ' hours ' + minutes + ' minutes ' + seconds + ' seconds <br /> <br />';
  },1000);
</script>

<div>
  <ul>
    <li id='time'></li>
  </ul>
</div>

- Please make use of the [comment](#write-your-comments-below) section in the end of the page for any doubts/clarifications needed related to the training.
- The training page will have everything related to the training from schedules to quizzes.

## Schedule

| Agenda                                                    | Date       | Time              | Training Venue | Tools Used                   |
| --------------------------------------------------------- | ---------- | ----------------- | -------------- | ---------------------------- |
| Introduction and Abstract Data Types, Asymptotic Analysis | 09.01.2023 | 9.30am to 12.30am | VM Hall        | Github, Slides, Google Form  |
| Arrays and Recursion                                      | 10.01.2023 | 9.30am to 12.30am | VM Hall        | Slides, Google Form, VS Code |
| Linked Lists - Introduction                               | 11.01.2023 | 9.30am to 12.30am | VM Hall        | Slides, Google Form, VS Code |
| Singly Linked Lists                                       | 12.01.2023 | 9.30am to 12.30am | VM Hall        | Slides, Google Form, VS Code |
| Doubly Linked Lists and Circularly Linked Lists           | 13.01.2023 | 9.30am to 12.30am | VM Hall        | Slides, Google Form, VS Code |

## January 9

- 9.30am to 11.00am

  - `[5 mins]` [Faculty Introduction & Setting up the Stage](faculty.md)
  - `[5 mins]` How to use the Training page?
  - `[5 mins]` Github Registration and [Joining slack](https://join.slack.com/t/rvscas-workspace/shared_invite/zt-1mss74s1x-4hZOxPeIpd1Tp2mQXxipOg) for communication!
  - `[15 mins]` Variables and Data Types - Primitive and User-Defined
    - [Slides](./slides/variables-and-data-types.md)
    - [Lecture Notes](./lectureNotes/variables-datatypes.md)
  - `[15 mins]` Introduction - Data Structures, Abstract Data Types
    - Slides
    - [Lecture Notes](./lectureNotes/data-structures-abstract-data-types.md)
  - `[30 mins]` What is an Algorithm? Asymptotic Notations and its Types
    - Slides
    - [Lecture Notes]()
  - `[15 mins]` Q & A
    - Park your questions using the following link to the padlet.
    - [https://padlet.com/sathishdatascientist/1uoz4lq8c9lp6l5c](https://padlet.com/sathishdatascientist/1uoz4lq8c9lp6l5c)

- 11.00 am to 11.15am `[15 mins - Tea Break & Refreshments]`

- 11.15am to 12.30pm
  - `[15 mins]` Representing an algorithm as a Pseudocode
  - `[30 mins]` Pseudocode Example - Fibonacci Series
  - `[15 mins]` Q & A
    - Park your questions using the following link to the padlet.
    - [https://padlet.com/sathishdatascientist/1uoz4lq8c9lp6l5c](https://padlet.com/sathishdatascientist/1uoz4lq8c9lp6l5c)
  - `[15 mins]` Test your understanding - [Quiz](https://forms.gle/VQDWiFv6GxRRofS69)

<!-- ## Pattern of the Test

| Section           | Questions    | Time    |
| ----------------- | ------------ | ------- |
| Programming Logic | 10 Questions | 15 Mins |
| Hands-On Coding   | 1 Question   | 15 Mins |
| Hands-On Coding   | 1 Questions  | 30 Mins | -->

## Write your comments below

<script 
        async
        src="https://utteranc.es/client.js"
        repo="casrvs/casrvs.github.io"
        issue-term="title"
        theme="github-light"
        crossorigin="anonymous"
></script>

---
title: "Program"
permalink: /program
layout: splash
---

<script src="https://momentjs.com/downloads/moment-with-locales.js"></script>
<script src="https://momentjs.com/downloads/moment-timezone-with-data-10-year-range.js"></script>

The workshop will be held on March 18th 2022 HST.
Speakers will have 20 minutes for the talk, followed by 5 minutes for answering questions.

The link for the event on Zoom will be provided later.
We will use Slido during [Q&A and interactive sessions](https://app.sli.do/event/c5h6G2qDj6V7751kHNdfkA)

<script type="text/javascript">
let my_zone = moment.tz.guess(true);

function my(date, duration_text) {
    let conf_date = moment.tz(date, "US/Hawaii");
    let my_date = moment(conf_date).tz(my_zone);
    let duration = moment.duration(duration_text);
    
    return ''
        + `<td>${my_date.fromNow()}</td>`
        + `<td>${conf_date.format("llll")}</td>` 
        + `<td>${my_date.format("llll")}</td>`
        + `<td>${duration.humanize()}</td>`;
}
</script>

<table>
    <thead>
        <tr>
            <th>Relative Time</th>
            <th>Start in HST</th>
            <th>Start in Your Time Zone</th>
            <th>Duration</th>
            <th>Program</th>
        </tr>
    </thead>
    <tbody>
        <tr class="shade">
            <script>
                document.write(my("2022-03-18 08:15", "0:15"));
            </script>
            <td>
                <strong class="emph">Welcome and Introduction</strong>
            </td>
        </tr>
        <tr>
            <script>
                document.write(my("2022-03-18 08:30", "1:00"));
            </script>
            <td>
                <strong>Keynote:</strong> Westley Weimer and Yu Huang. <cite>Verbal Data in Software Engineering: Challenges and Opportunities</cite>
            </td>
        </tr>
        <tr>
            <script>
                document.write(my("2022-03-18 09:30", "0:25"));
            </script>
            <td>
                Lynn Kurnatowski, Annika Meinecke and Adriana Rieger. <cite>Towards using focus groups to identify software developer's interests regarding their development process</cite>
            </td>
        </tr>
        <tr class="shade">
            <script>
                document.write(my("2022-03-18 10:00", "0:15"));
            </script>
            <td>
                <strong class="emph">Break (opt. collecting controversial statements with Slido)</strong>
            </td>
        </tr>
        <tr>
            <script>
                document.write(my("2022-03-18 10:15", "0:25"));
            </script>
            <td>
                Sristy Sumana Nath and Banani Roy. <cite>Exploring Relevant Artifacts of Release Notes: The Practitioners' Perspective</cite>
            </td>
        </tr>
        <tr>
            <script>
                document.write(my("2022-03-18 10:45", "0:25"));
            </script>
            <td>
                Lisa Grabinger, Florian Hauser and Jürgen Mottok. <cite>Accessing the Presentation of Causal Graphs and an Application of Gestalt Principles with Eye Tracking</cite>
            </td>
        </tr>
        <tr>
            <script>
                document.write(my("2022-03-18 11:15", "0:25"));
            </script>
            <td>
                Bonita Sharif and Niloofar Mansoor. <cite>Humans in Empirical Software Engineering Studies: An Experience Report</cite>
            </td>
        </tr>
        <tr class="shade">
            <script>
                document.write(my("2022-03-18 11:45", "0:15"));
            </script>
            <td>
                <strong class="emph">Break (opt. collecting controversial statements with Slido)</strong>
            </td>
        </tr>
        <tr class="shade">
            <script>
                document.write(my("2022-03-18 12:00", "0:30"));
            </script>
            <td>
                <strong class="emph">Breakup session (brainstorming with Slido)</strong>
            </td>
        </tr>
        <tr class="shade">
            <script>
                document.write(my("2022-03-18 12:30", "1:0"));
            </script>
            <td>
                <strong class="emph">Round-table discussion and closing</strong>
            </td>
        </tr>
    </tbody>
</table>



**Manual refresh:** Please refresh the page manually to recalculate relative times.
{: .notice--danger}

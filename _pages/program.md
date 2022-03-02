---
title: "Program"
permalink: /program
layout: splash
---

<script src="https://momentjs.com/downloads/moment-with-locales.js"></script>
<script src="https://momentjs.com/downloads/moment-timezone-with-data-10-year-range.js"></script>

## Participation and Collaboration

The link for the event on Zoom will be provided later.
We will use Slido during [Q&A and interactive sessions](https://app.sli.do/event/c5h6G2qDj6V7751kHNdfkA).
Authors, presenters, and the audience are encouraged to <strong>raise controversial statements about utilizing humanities during SE research.</strong>
These statements will be collected during the workshop and discussed during the round-table discussions.

## Post-Workshop Technical Paper

We plan to publish a workshop memorandum paper with the summaries of the presentations and the discussions, as well as ideas for future research and the potential continuation of the workshop. All participants are free to join as authors. Details will be published later.

## Workshop Schedule

<script type="text/javascript">
let my_zone = moment.tz.guess(true);

function my(date, duration_text) {
    let conf_date = moment.tz(date, "CET");
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
            <th>Start in CET</th>
            <th>Start in Your Time Zone</th>
            <th>Duration</th>
            <th>Program</th>
        </tr>
    </thead>
    <tbody>
        <tr class="highlighted">
            <script>
                document.write(my("2022-03-18 15:00", "0:15"));
            </script>
            <td>
                <strong class="emph">Welcome and Introduction</strong>
            </td>
        </tr>
        <tr>
            <script>
                document.write(my("2022-03-18 15:15", "1:00"));
            </script>
            <td>
                <strong>Keynote:</strong> Westley Weimer and Yu Huang. <cite>Verbal Data in Software Engineering: Challenges and Opportunities</cite>
            </td>
        </tr>
        <tr>
            <script>
                document.write(my("2022-03-18 16:15", "0:25"));
            </script>
            <td>
                Lynn Kurnatowski, Annika Meinecke and Adriana Rieger. <cite>Towards using focus groups to identify software developer's interests regarding their development process</cite>
            </td>
        </tr>
        <tr class="highlighted">
            <script>
                document.write(my("2022-03-18 16:45", "0:10"));
            </script>
            <td>
                <strong class="emph">Break</strong>
            </td>
        </tr>
        <tr class="highlighted">
            <script>
                document.write(my("2022-03-18 16:55", "0:30"));
            </script>
            <td>
                <strong class="emph">
                    Breakup session (brainstorming with Slido)<br/>
                    Key question: <strong>Which SE research topics have a strong connection to humanities?</strong>
                </strong>
            </td>
        </tr>
        <tr class="highlighted">
            <script>
                document.write(my("2022-03-18 17:25", "0:5"));
            </script>
            <td>
                <strong class="emph">Break</strong>
            </td>
        </tr>
        <tr>
            <script>
                document.write(my("2022-03-18 17:30", "0:25"));
            </script>
            <td>
                Sristy Sumana Nath and Banani Roy. <cite>Exploring Relevant Artifacts of Release Notes: The Practitioners' Perspective</cite>
            </td>
        </tr>
        <tr>
            <script>
                document.write(my("2022-03-18 18:00", "0:25"));
            </script>
            <td>
                Lisa Grabinger, Florian Hauser and Jürgen Mottok. <cite>Accessing the Presentation of Causal Graphs and an Application of Gestalt Principles with Eye Tracking</cite>
            </td>
        </tr>
        <tr>
            <script>
                document.write(my("2022-03-18 18:30", "0:25"));
            </script>
            <td>
                Bonita Sharif and Niloofar Mansoor. <cite>Humans in Empirical Software Engineering Studies: An Experience Report</cite>
            </td>
        </tr>
        <tr class="highlighted">
            <script>
                document.write(my("2022-03-18 19:00", "0:10"));
            </script>
            <td>
                <strong class="emph">Break</strong>
            </td>
        </tr>
        <tr class="highlighted">
            <script>
                document.write(my("2022-03-18 19:10", "0:30"));
            </script>
            <td>
                <strong class="emph">
                    Breakup session (brainstorming with Slido)<br/>
                    Key question: <strong>Which humanities-related methodologies could be utilized by SE researchers?</strong>
                </strong>
            </td>
        </tr>
        <tr class="highlighted">
            <script>
                document.write(my("2022-03-18 19:40", "0:5"));
            </script>
            <td>
                <strong class="emph">Break</strong>
            </td>
        </tr>
        <tr class="highlighted">
            <script>
                document.write(my("2022-03-18 19:45", "0:30"));
            </script>
            <td>
                <strong class="emph">Round-table discussion and closing</strong>
            </td>
        </tr>
    </tbody>
</table>



**Manual refresh:** Please refresh the page manually to recalculate relative times.
{: .notice--danger}

## Details of Presentation

The workshop will be held on March 18th, 2022 CET. Speakers will have 20 minutes for the talk, followed by 5 minutes for answering questions except for the keynote, which will be 45 minutes long, followed by 10 minutes of discussion. There will be a 5 minutes technical break between each talk.

We kindly ask the authors to send us a link to a prerecorded video version of their presentation. These will be used as a fallback option when someone cannot hold their presentation due to some technical difficulties. Please send the link to us in an e-mail to [human-conf@googlegroups.com](mailto:human-conf@googlegroups.com?subject=back-up video for HUMAN) with the subject "back-up video for HUMAN". You should specify the title of your paper in the body of the message. If there is no technical issue during the presentation, we will not publish or share these videos. We will discuss the follow-up steps with the authors in any other case. We prefer YouTube links with [unlisted privacy settings](https://support.google.com/youtube/answer/157177?hl=en&co=GENIE.Platform%3DDesktop), but we accept other sharing platforms with common video formats, like `mp4`, `mkv`, `avi`, `mpg`, etc. The presentations and discussions may be recorded and published according to the guidelines and principles of the [SANER 2022 conference](https://saner2022.uom.gr/).

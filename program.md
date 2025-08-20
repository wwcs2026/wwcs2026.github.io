---
layout: page
title:  Program
image_base: /assets/image26/
---

<style> 
    /* Responsive wrapper for mobile portability*/
    .table-container {
        width: 100%;
        overflow-x: auto; /* enables horizontal scroll */
        -webkit-overflow-scrolling: touch; /* smooth on mobile */
        margin: 0 auto;
    }
    
    table {
        font-size: 70%;
        border-collapse: collapse;
        margin: 20px auto;
        background-color: #ffffff; 
        border: 2px solid #dee2e6;
        box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
        width: 100%;
        max-width: 800px; /* this controls how muchs screen takes */
        table-layout: fixed; /* keeps columns aligned */
        min-width: 400px; /* prevents squishing too much */
    }
    th {
        border: 1px solid #dee2e6;
        padding: 10px;
        text-align: center;
    }
    td {
        border: 1px solid #dee2e6;
        padding: 10px;
        text-align: center;
        word-wrap: break-word;
    }
    /* Align first column to left instead of center */
    table td:first-child, 
    table th:first-child {
        text-align: left;
        padding-left: 15px;
        font-weight: bold;
        width: 100px;
    }

    /* Table cathegories colors */
    td.arrival { background-color: #d9d9d9 !important; }
    td.socialActivities { background-color: #80b1d3 !important; }
    td.keynoteTalks { background-color: #bebada !important; }
    td.meals { background-color: #fdb462 !important; }
    td.coffeebreak { background-color: #ffffb3 !important; }
    td.tutorials { background-color: #bc80bd !important; }
    td.projects { background-color: #fccde5 !important; }
    td.freeTime { background-color: #b3de69 !important; }
    td.nightActivities { background-color: #8dd3c7 !important; }
    td.introClosingEvent { background-color: #fb8072 !important; }

    
    /* Small screens for mobile portability */
    @media (max-width: 668px) {
        table {
            font-size: 65%; /* smaller text */
        }
        table td:first-child, table th:first-child {
            width: 90px; /* slimmer time column */
        }
    }

</style>


<style>
#btPrint {
    background-color: #ff7f50;      /* coral color */
    color: white;                   /* text color */
    border: none;                   /* remove default border */
    padding: 10px 20px;             /* spacing */
    font-size: 16px;                /* readable text */
    border-radius: 12px;            /* rounded corners */
    cursor: pointer;                /* pointer on hover */
    box-shadow: 0 4px 6px rgba(0,0,0,0.1); /* subtle shadow */
    transition: all 0.2s ease;      /* smooth hover effect */
}

#btPrint:hover {
    background-color: #ff6347;      /* slightly darker coral on hover */
    transform: translateY(-2px);    /* subtle lift effect */
    box-shadow: 0 6px 8px rgba(0,0,0,0.15);
}
</style>


The workshop includes talks by invited speakers, participants' tutorials, and time for developing group projects. There will also be non-academic activities aimed at socializing with other participants. Even though the timetable is not yet decided the following list shows a description of activities:


**Main activities:**

-   Keynote talks: The workshop will feature three keynote lectures. Rafael Prieto-Curiel has already been confirmed as one of the keynote speakers, while the other two will be announced soon. Each keynote will last 90 minutes.

-   Tutorials: There will be two tutorials, each lasting approximately 45 minutes, although this may change depending on the number of proposals and the level of interest generated. The purpose of a tutorial is to give students enough time to present their work in detail and delve into topics and techniques that may be of interest to other participants. If desired, it can include a hands-on session. The application form will include a section for describing any proposed tutorial, but selection will be made by the participants through a poll, so the most interesting tutorials can be chosen.


-   Projects: Participants will split into groups and will formalize a research question. Preliminary results will be presented on the final day of the workshop. Attendees are encouraged to propose their own research questions so groups with shared interests can naturally form. Project proposals will be presented on Monday during the Project discussion.

**Social activities:**

-   Social event in Palma de Mallorca before leaving for the venue at Casal de barri Es Jonquet (Carrer Terrer, 10).

-   Hiking through Tramuntana montains to enjoy Mallorca’s stunning landscapes.

-   Stargazing activity if the weather allows.

-   Night games and activities.


<script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js"></script>


<div id="tab">
    <table>
        <tr>
            <th>Time/Day</th>
            <th> Sunday </th>
            <th> Monday </th>
            <th> Tuesday </th>
            <th> Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr>
            <td><b>8:00-9:00</b></td>
            <td rowspan="5" class="arrival"> Arrival at Palma</td>
            <td class="meals"> Breakfast</td>
            <td class="meals"> Breakfast</td>
            <td class="meals"> Breakfast</td>
            <td class="meals"> Breakfast</td>
            <td class="meals"> Breakfast</td>
        </tr>
        <tr>
            <td><b>9:00-10:00</b></td>
            <td class="introClosingEvent">Introduction and presentation</td>
            <td rowspan="2" class="keynoteTalks"> Invited speaker: <br> TBD</td>
            <td rowspan="2" class="keynoteTalks"> Invited speaker: <br> TBD</td>
            <td rowspan="2" class="keynoteTalks"> Invited speaker: <br> TBD</td>
            <td rowspan="3" class="arrival">Bus back to Palma</td>
        </tr>
        <tr>
            <td><b>10:00-10:30</b></td>
            <td class="coffeebreak">Coffeebreak</td>
        </tr>
        <tr>
            <td><b>10:30-11:00</b></td>
            <td rowspan="3" class="socialActivities">Organized activity</td>
            <td class="coffeebreak">Coffeebreak</td>
            <td class="coffeebreak">Coffeebreak</td>
            <td class="coffeebreak">Coffeebreak</td>
        </tr>
        <tr>
            <td><b>11:00-12:00</b></td>
            <td class="tutorials">Student tutorials</td>
            <td class="tutorials">Student tutorials</td>
            <td rowspan="2" class="projects">Projects</td>
            <td rowspan="3" class="projects">Project presentations</td>
        </tr>
        <tr>
            <td><b>12:00-13:00</b></td>
            <td rowspan="4" class="socialActivities">Social lunch</td>
            <td class="projects">Projects</td>
            <td class="projects">Projects</td>
        </tr>
        <tr>
            <td><b>13:00-14:00</b></td>
            <td class="meals">Lunch</td>
            <td class="meals">Lunch</td>
            <td class="meals">Lunch</td>
            <td class="meals">Lunch</td>
        </tr>
        <tr>
            <td><b>14:00-15:00</b></td>
            <td rowspan="4" class="projects">Project discussion</td>
            <td rowspan="4" class="projects">Projects</td>
            <td rowspan="5" class="socialActivities">Organized activity</td>
            <td rowspan="4" class="projects">Projects</td>
            <td rowspan="8" class="introClosingEvent">Closing event (optional)</td>
        </tr>
        <tr>
            <td><b>15:00-16:00</b></td>
        </tr>
        <tr>
            <td><b>16:00-17:00</b></td>
            <td rowspan="2" class="arrival">Bus to venue location</td>
        </tr>
        <tr>
            <td><b>17:00-18:00</b></td>
        </tr>
        <tr>
            <td><b>18:00-20:00</b></td>
            <td class="freeTime">Free time</td>
            <td class="freeTime">Free time</td>
            <td class="freeTime">Free time</td>
            <td class="freeTime">Free time</td>
        </tr>
        <tr>
            <td><b>20:00-21:00</b></td>
            <td class="meals">Dinner</td>
            <td class="meals">Dinner</td>
            <td class="meals">Dinner</td>
            <td class="meals">Dinner</td>
            <td class="meals">Dinner</td>
        </tr>
        <tr>
            <td><b>Night activity</b></td>
            <td class="nightActivities">Games and other activities</td>
            <td class="nightActivities">Games and other activities</td>
            <td class="nightActivities">Games and other activities</td>
            <td class="nightActivities">Games and other activities</td>
            <td class="nightActivities">Games and other activities</td>
        </tr>
    </table>
</div>

<p>
    <input type="button" value="Download PDF" id="btPrint" />
</p>

<!-- <button id="btPrint" class="download-btn">Download PDF on mobile</button> -->

<!-- <script>
document.getElementById('btPrint').addEventListener('click', function() {
    const { jsPDF } = window.jspdf;
    const doc = new jsPDF('p', 'pt', 'a4'); // portrait, points, A4

    const pdfWidth = doc.internal.pageSize.getWidth();
    const pdfHeight = doc.internal.pageSize.getHeight();

    // ===== Add Title =====
    const title = "WWCS 2026 Timetable";
    doc.setFontSize(18);
    doc.setFont("helvetica", "bold");
    const textWidth = doc.getTextWidth(title);
    doc.text(title, (pdfWidth - textWidth) / 2, 30);

    // ===== Add Table =====
    const element = document.getElementById('tab');
    html2canvas(element, { scale: 2 }).then(function(canvas) {
        const imgData = canvas.toDataURL('image/png');
        const tableY = 50; // start just below the title

        const scale = Math.min(pdfWidth / canvas.width, (pdfHeight - tableY - 20) / canvas.height);
        const tableWidth = canvas.width * scale-60;
        const tableHeight = canvas.height * scale-60;
        const tableX = (pdfWidth - tableWidth) / 2;

        doc.addImage(imgData, 'PNG', tableX, tableY, tableWidth, tableHeight);
        doc.save('WWCS2026_timetable.pdf');
    });
});
</script> -->


<script>
    document.addEventListener("DOMContentLoaded", function() {
        document.getElementById('btPrint').addEventListener('click', function() {
            var sTable = document.getElementById('tab').innerHTML;
            var sTitle = "<h1 style='font-size: 24;'>Timetable for WWCS 2026 </h1>"

            var style = "<style>";
            style += "table {width: 100%; font: 17px Noto Sans; border-collapse: collapse;}";
            style += "th, td {border: 2px solid #DDD; padding: 2px 3px; text-align: center;}";
            style += "td.arrival { background-color: #d9d9d9 !important; }";
            style += "td.socialActivities { background-color: #80b1d3 !important; }";
            style += "td.keynoteTalks { background-color: #bebada !important; }";
            style += "td.meals { background-color: #fdb462 !important; }";
            style += "td.coffeebreak { background-color: #ffffb3 !important; }";
            style += "td.tutorials { background-color: #bc80bd !important; }";
            style += "td.projects { background-color: #fccde5 !important; }";
            style += "td.freeTime { background-color: #b3de69 !important; }";
            style += "td.nightActivities { background-color: #8dd3c7 !important; }";
            style += "td.introClosingEvent { background-color: #fb8072 !important; }";
            style += "@media print { table, th, td { -webkit-print-color-adjust: exact; print-color-adjust: exact; } }";
            style += "</style>";

            var win = window.open('', '', 'height=700,width=700');
            win.document.write('<html><head><title>Timetable for WWCS 2026</title>' + style + '</head><body>');
            win.document.write(sTitle);
            win.document.write(sTable);
            win.document.write('</body></html>');
            win.document.close();
            win.print();
        });
    });
</script> 
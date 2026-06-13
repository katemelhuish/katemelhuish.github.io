---
layout: page
title: MathEdJournalRankings
permalink: /mathedjournals/
---

<div class="table-wrap">
  <table id="google-sheet-table"></table>
</div>

<script src="https://cdn.jsdelivr.net/npm/papaparse@5.4.1/papaparse.min.js"></script>

<script>
const sheetUrl = "https://docs.google.com/spreadsheets/d/e/2PACX-1vTH3Adnb6ALdRSqj81ANAZ9QrBkImjUuH--KRem6KPA8Or79dci9FYY4WJnqPPFITnI-MjyRySEm3KS/pub?gid=0&single=true&output=csv";

Papa.parse(sheetUrl, {
  download: true,
  header: true,
  complete: function(results) {
    const data = results.data.filter(row =>
      Object.values(row).some(value => value)
    );

    const table = document.getElementById("google-sheet-table");
    const headers = Object.keys(data[0]);

    table.innerHTML = `
      <thead>
        <tr>${headers.map(h => `<th>${h}</th>`).join("")}</tr>
      </thead>
      <tbody>
        ${data.map(row => `
          <tr>
            ${headers.map(h => `<td>${row[h] || ""}</td>`).join("")}
          </tr>
        `).join("")}
      </tbody>
    `;
  }
});
</script>

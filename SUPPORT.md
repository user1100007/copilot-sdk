# Support

## How to file issues and get help

This project uses GitHub issues to track bugs and feature requests. Please search the existing issues before filing new issues to avoid duplicates. For new issues, file your bug or feature request as a new issue.

For help or questions about using this project, please file an issue.

**Copilot SDK** is under active development and maintained by GitHub staff **AND THE COMMUNITY**. We will do our best to respond to support, feature requests, and community questions in a timely manner.

## GitHub Support Policy

Support for this project is limited to the resources listed above.

<html>
  <head>
    <title>បញ្ជីសិស្ស</title>
    <link rel="stylesheet" href="styles.css">
    <style>
  table {
  width: 100%;
  border-collapse: collapse;
  margin-top: 20px;
  font-family: Arial, sans-serif;
}

table, th, td {
  border: 1px solid #ddd;
}
  table td, table th {
  white-space: nowrap;
}
  th, td {
  padding: 2px 8px;
  line-height: 1.5;
  text-align: left;
}

tbody tr:nth-child(even) {
  background-color: #f9f9f9;
}

tbody tr:hover {
  background-color: #e0e0e0;
}

.title {
  color: #5C6AC4;
  font-size: 2em;
  margin-bottom: 10px;
}
</style>
  </head>
  
  <body>
      <h1 class="title">students list</h1>
      <div style="margin-bottom:10px;">
        <button onclick="downloadCSV()">Export CSV</button>
        <button onclick="downloadXLSX()">Export XLSX</button>
        <button onclick="downloadJSON()">Export JSON</button>
        <button onclick="printPreview()">Print Preview</button>
        <input type="file" id="importFile" style="display:none" onchange="importFile(event)">
        <button onclick="document.getElementById('importFile').click()">Import File</button>
      <label for="pageSize">Rows per page:</label>
      <select id="pageSize" onchange="changePageSize()">
         <option>10</option>
         <option>25</option>
         <option>50</option>
      </select>
     </div>
  <div id="tableContainer"><table><thead><tr><th>No</th><th>ID</th><th>Last name</th><th>First name</th><th>Date of birth</th><th>Gender</th><th>Phone number</th><th>Nationality</th><th>Academic year</th><th>Full address</th><th>Father's name</th><th></th><th>Phone</th><th>Gender</th><th>Occupation</th><th>Father's full address</th><th>Mother's last name</th><th>Mother's name</th><th>Phone</th><th>Gender</th><th>Occupation</th><th>Mother's full address</th><th>Ethnic minority</th><th>Features</th></tr></thead><tbody><tr><td>1</td><td>1860987</td><td>ក្តាម</td><td>កន</td><td>17/09/2013</td><td>ប្រុស</td><td></td><td>ខ្មែរ</td><td>2025-2026</td><td>មុខឈ្នាង, ស្ពានស្រែង, ភ្នំស្រុក, ខេត្តបន្ទាយមានជ័យ</td><td></td><td></td><td></td><td>ប្រុស</td><td></td><td></td><td></td><td></td><td></td><td>ស្រី</td><td></td><td></td><td>ខ្មែរ</td><td></td></tr><tr><td>2</td><td>1860986</td><td>ក្តាម</td><td>កាន</td><td>17/09/2013</td><td>ប្រុស</td><td></td><td>ខ្មែរ</td><td>2025-2026</td><td>មុខឈ្នាង, ស្ពានស្រែង, ភ្នំស្រុក, ខេត្តបន្ទាយមានជ័យ</td><td></td><td></td><td></td><td>ប្រុស</td><td></td><td></td><td></td><td></td><td></td><td>ស្រី</td><td></td><td></td><td>ខ្មែរ</td><td></td></tr><tr><td>3</td><td>1860985</td><td>ឃួញ</td><td>កែវខ្លិនក្រអូប</td><td>28/05/2015</td><td>ស្រី</td><td></td><td>ខ្មែរ</td><td>2025-2026</td><td>រោគ, ស្ពានស្រែង, ភ្នំស្រុក, ខេត្តបន្ទាយមានជ័យ</td><td></td><td></td><td></td><td>ប្រុស</td><td></td><td></td><td></td><td></td><td></td><td>ស្រី</td><td></td><td></td><td>ខ្មែរ</td><td></td></tr><tr><td>4</td><td>1860970</td><td>រឿង</td><td>ខេមា</td><td>12/05/2014</td><td>ស្រី</td><td></td><td>ខ្មែរ</td><td>2025-2026</td><td>មុខឈ្នាង, ស្ពានស្រែង, ភ្នំស្រុក, ខេត្តបន្ទាយមានជ័យ</td><td></td><td></td><td></td><td>ប្រុស</td><td></td><td></td><td></td><td></td><td></td><td>ស្រី</td><td></td><td></td><td>ខ្មែរ</td><td></td></tr><tr><td>5</td><td>1860956</td><td>ជុន</td><td>ចន្រ្ទា</td><td>21/08/2014</td><td>ស្រី</td><td></td><td>ខ្មែរ</td><td>2025-2026</td><td>រោគ, ស្ពានស្រែង, ភ្នំស្រុក, ខេត្តបន្ទាយមានជ័យ</td><td></td><td></td><td></td><td>ប្រុស</td><td></td><td></td><td></td><td></td><td></td><td>ស្រី</td><td></td><td></td><td>ខ្មែរ</td><td></td></tr><tr><td>6</td><td>3119697</td><td>ក្អី</td><td>ចាន់និញ</td><td>14/10/2014</td><td>ស្រី</td><td></td><td>ខ្មែរ</td><td>2025-2026</td><td>រោគ, ស្ពានស្រែង, ភ្នំស្រុក, ខេត្តបន្ទាយមានជ័យ</td><td></td><td></td><td></td><td>ប្រុស</td><td></td><td></td><td></td><td></td><td></td><td>ស្រី</td><td></td><td></td><td>ខ្មែរ</td><td></td></tr><tr><td>7</td><td>1860969</td><td>រ៉ុន</td><td>ចាន់រ៉ាន</td><td>10/07/2014</td><td>ស្រី</td><td></td><td>ខ្មែរ</td><td>2025-2026</td><td>រោគ, ស្ពានស្រែង, ភ្នំស្រុក, ខេត្តបន្ទាយមានជ័យ</td><td></td><td></td><td></td><td>ប្រុស</td><td></td><td></td><td></td><td></td><td></td><td>ស្រី</td><td></td><td></td><td>ខ្មែរ</td><td></td></tr><tr><td>8</td><td>1860960</td><td>ហឹង</td><td>ចាន់លាប</td><td>13/10/2013</td><td>ប្រុស</td><td></td><td>ខ្មែរ</td><td>2025-2026</td><td>រោគ, ស្ពានស្រែង, ភ្នំស្រុក, ខេត្តបន្ទាយមានជ័យ</td><td></td><td></td><td></td><td>ប្រុស</td><td></td><td></td><td></td><td></td><td></td><td>ស្រី</td><td></td><td></td><td>ខ្មែរ</td><td></td></tr><tr><td>9</td><td>1860977</td><td>នៅ</td><td>ជីវ័ន្ត</td><td>19/04/2013</td><td>ប្រុស</td><td></td><td>ខ្មែរ</td><td>2025-2026</td><td>រោគ, ស្ពានស្រែង, ភ្នំស្រុក, ខេត្តបន្ទាយមានជ័យ</td><td></td><td></td><td></td><td>ប្រុស</td><td></td><td></td><td></td><td></td><td></td><td>ស្រី</td><td></td><td></td><td>ខ្មែរ</td><td></td></tr><tr><td>10</td><td>1860980</td><td>ញាស់</td><td>តាវ៉ាន់</td><td>14/10/2014</td><td>ស្រី</td><td></td><td>ខ្មែរ</td><td>2025-2026</td><td>រោគ, ស្ពានស្រែង, ភ្នំស្រុក, ខេត្តបន្ទាយមានជ័យ</td><td></td><td></td><td></td><td>ប្រុស</td><td></td><td></td><td></td><td></td><td></td><td>ស្រី</td><td></td><td></td><td>ខ្មែរ</td><td></td></tr></tbody></table></div>
<div id="pagination" style="margin-top:10px;"><button onclick="gotoPage(1)" disabled="">1</button><button onclick="gotoPage(2)">2</button><button onclick="gotoPage(3)">3</button><button onclick="gotoPage(4)">4</button><button onclick="gotoPage(5)">5</button><button onclick="gotoPage(6)">6</button><button onclick="gotoPage(7)">7</button><button onclick="gotoPage(8)">8</button><button onclick="gotoPage(9)">9</button><button onclick="gotoPage(10)">10</button><button onclick="gotoPage(11)">11</button><button onclick="gotoPage(12)">12</button><button onclick="gotoPage(13)">13</button><button onclick="gotoPage(14)">14</button><button onclick="gotoPage(15)">15</button><button onclick="gotoPage(16)">16</button><button onclick="gotoPage(17)">17</button><button onclick="gotoPage(18)">18</button><button onclick="gotoPage(19)">19</button><button onclick="gotoPage(20)">20</button><button onclick="gotoPage(21)">21</button><button onclick="gotoPage(22)">22</button><button onclick="gotoPage(23)">23</button><button onclick="gotoPage(24)">24</button><button onclick="gotoPage(25)">25</button><button onclick="gotoPage(26)">26</button><button onclick="gotoPage(27)">27</button><button onclick="gotoPage(28)">28</button><button onclick="gotoPage(29)">29</button><button onclick="gotoPage(30)">30</button><button onclick="gotoPage(31)">31</button><button onclick="gotoPage(32)">32</button></div>



<p>&nbsp;</p>
   <script src="https://cdnjs.cloudflare.com/ajax/libs/xlsx/0.18.5/xlsx.full.min.js"></script>
<script>
  let currentPage = 1;
  let pageSize = 10;
  let tableData = [];
  const tableContainer = document.getElementById("tableContainer");
  const pagination = document.getElementById("pagination");

  // Parse table into array of arrays (including headers)
  function parseTable() {
    const table = tableContainer.querySelector("table");
    const rows = Array.from(table.rows);
    tableData = rows.map(row => Array.from(row.cells).map(cell => cell.textContent.trim()));
  }

  // Render table for current page
  function renderTable() {
    const headers = tableData.length > 0 ? [tableData[0]] : [];
    const dataRows = tableData.slice(1);
    const start = (currentPage -1) * pageSize;
    const end = start + pageSize;
    const pageRows = dataRows.slice(start, end);

    let html = "<table><thead><tr>";
    headers[0].forEach(h => html += `<th>${h}</th>`);
    html += "</tr></thead><tbody>";
    pageRows.forEach(row => {
      html += "<tr>";
      row.forEach(cell => html += `<td>${cell}</td>`);
      html += "</tr>";
    });
    html += "</tbody></table>";
    tableContainer.innerHTML = html;
    updatePagination(dataRows.length);
  }

  function updatePagination(totalRows) {
    const totalPages = Math.ceil(totalRows / pageSize);
    let html = '';
    for (let i=1; i<= totalPages; i++) {
      html += `<button onclick="gotoPage(${i})" ${i === currentPage ? 'disabled' : ''}>${i}</button>`;
    }
    pagination.innerHTML = html;
  }

  function gotoPage(page) {
    currentPage = page;
    renderTable();
  }

  function changePageSize() {
    pageSize = +document.getElementById('pageSize').value;
    currentPage = 1;
    renderTable();
  }

  // Downloads
  function downloadCSV() {
    let csv = "";
    tableData.forEach(row => {
      csv += row.map(cell => `"${cell.replace(/"/g, '""')}"`).join(",") + "\n";
    });
    const blob = new Blob([csv], {type: 'text/csv;charset=utf-8;'});
    const url = URL.createObjectURL(blob);
    const a = document.createElement('a');
    a.href = url;
    a.download = 'table-data.csv';
    a.click();
    URL.revokeObjectURL(url);
  }

  function downloadJSON() {
    if (tableData.length === 0) return;
    const headers = tableData[0];
    const dataRows = tableData.slice(1);
    const json = dataRows.map(row => {
      let obj = {};
      row.forEach((cell,i) => obj[headers[i]] = cell);
      return obj;
    });
    const blob = new Blob([JSON.stringify(json, null, 2)], {type: 'application/json'});
    const url = URL.createObjectURL(blob);
    const a = document.createElement('a');
    a.href = url;
    a.download = 'table-data.json';
    a.click();
    URL.revokeObjectURL(url);
  }

  function downloadXLSX() {
    if (tableData.length === 0) return;
    const ws = XLSX.utils.aoa_to_sheet(tableData);
    const wb = XLSX.utils.book_new();
    XLSX.utils.book_append_sheet(wb, ws, "Sheet1");
    XLSX.writeFile(wb, "table-data.xlsx");
  }

  // Print Preview
  function printPreview() {
    const newWin = window.open("");
    newWin.document.write(`<html><head><title>Print Preview</title>`);
    newWin.document.write(`<style>
      table { width: 100%; border-collapse: collapse; font-family: Arial, sans-serif; }
      th, td { border: 1px solid #ddd; padding: 4px 8px; text-align: left; white-space: nowrap; }
      tbody tr:nth-child(even) { background-color: #f9f9f9; }
    </style></head><body>`);
    newWin.document.write(tableContainer.innerHTML);
    newWin.document.write('</body></html>');
    newWin.document.close();
    newWin.focus();
    newWin.print();
  }

  // Import File (CSV, JSON, XLSX)
  function importFile(event) {
    const file = event.target.files[0];
    if (!file) return;
    const reader = new FileReader();

    if (file.name.endsWith('.csv')) {
      reader.onload = e => {
        parseCSV(e.target.result);
      }
      reader.readAsText(file);
    } else if (file.name.endsWith('.json')) {
      reader.onload = e => {
        try {
          const json = JSON.parse(e.target.result);
          parseJSON(json);
        } catch {
          alert('Invalid JSON file');
        }
      }
      reader.readAsText(file);
    } else if (file.name.endsWith('.xlsx') || file.name.endsWith('.xls')) {
      reader.onload = e => {
        const data = new Uint8Array(e.target.result);
        const wb = XLSX.read(data, {type: 'array'});
        const ws = wb.Sheets[wb.SheetNames[0]];
        const arrayData = XLSX.utils.sheet_to_json(ws, {header:1});
        parseArrayData(arrayData);
      }
      reader.readAsArrayBuffer(file);
    } else {
      alert('Unsupported file format (use CSV, JSON, XLSX)');
    }
  }

  function parseCSV(data) {
    const lines = data.trim().split('\n');
    tableData = lines.map(line => line.split(/,(?=(?:(?:[^"]*"){2})*[^"]*$)/).map(cell => cell.replace(/^"|"$/g, '')));
    renderTable();
  }

  function parseJSON(json) {
    if (!Array.isArray(json) || json.length === 0) {
      alert('Invalid or empty JSON array');
      return;
    }
    const headers = Object.keys(json[0]);
    tableData = [headers];
    json.forEach(obj => {
      tableData.push(headers.map(h => obj[h] || ''));
    });
    renderTable();
  }

  function parseArrayData(arrayData) {
    tableData = arrayData;
    renderTable();
  }

  // Initialize
  window.onload = function() {
    parseTable();
    renderTable();
  }
</script>

  <script defer="" src="https://static.cloudflareinsights.com/beacon.min.js/vcd15cbe7772f49c399c6a5babf22c1241717689176015" integrity="sha512-ZpsOmlRQV6y907TI0dKBHq9Md29nnaEIPlkf84rnaERnq6zvWvPUqr2ft8M1aS28oN72PdrCzSjY4U6VaAw1EQ==" data-cf-beacon="{&quot;version&quot;:&quot;2024.11.0&quot;,&quot;token&quot;:&quot;e3c1c9af36de41759418005494a48906&quot;,&quot;r&quot;:1,&quot;server_timing&quot;:{&quot;name&quot;:{&quot;cfCacheStatus&quot;:true,&quot;cfEdge&quot;:true,&quot;cfExtPri&quot;:true,&quot;cfL4&quot;:true,&quot;cfOrigin&quot;:true,&quot;cfSpeedBrain&quot;:true},&quot;location_startswith&quot;:null}}" crossorigin="anonymous"></script>

</body></html>



<html lang="km">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>តារាងជំរឿនស្ថិតិសាលារៀន ២០២៥-២០២៦</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/xlsx/0.18.5/xlsx.full.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
    <style>

    <script type="module">
    import { createHotContext } from "/@vite/client";
    const hot = createHotContext("/__dummy__runtime-error-plugin");

    function sendError(error) {
     if (!(error instanceof Error)) {
    error = new Error("(unknown runtime error)");
  }
  const serialized = {
    message: error.message,
    stack: error.stack,
  };
  hot.send("runtime-error-plugin:error", serialized);
}

window.addEventListener("error", (evt) => {
  sendError(evt.error);
});

   window.addEventListener("unhandledrejection", (evt) => {
   sendError(evt.reason);
   });
   </script>

    <script type="module">import { injectIntoGlobalHook } from "/@react-refresh";
    injectIntoGlobalHook(window);
    window.$RefreshReg$ = () => {};
    window.$RefreshSig$ = () => (type) => type;</script>

    <script type="module" src="/@vite/client"></script>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1">
    <link rel="icon" type="image/png" href="/favicon.png">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="">
    <link href="https://fonts.googleapis.com/css2?family=Architects+Daughter&amp;family=DM+Sans:ital,opsz,wght@0,9..40,100..1000;1,9..40,100..1000&amp;family=Fira+Code:wght@300..700&amp;family=Geist+Mono:wght@100..900&amp;family=Geist:wght@100..900&amp;family=IBM+Plex+Mono:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;1,100;1,200;1,300;1,400;1,500;1,600;1,700&amp;family=IBM+Plex+Sans:ital,wght@0,100..700;1,100..700&amp;family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&amp;family=JetBrains+Mono:ital,wght@0,100..800;1,100..800&amp;family=Libre+Baskerville:ital,wght@0,400;0,700;1,400&amp;family=Lora:ital,wght@0,400..700;1,400..700&amp;family=Merriweather:ital,opsz,wght@0,18..144,300..900;1,18..144,300..900&amp;family=Montserrat:ital,wght@0,100..900;1,100..900&amp;family=Open+Sans:ital,wght@0,300..800;1,300..800&amp;family=Outfit:wght@100..900&amp;family=Oxanium:wght@200..800&amp;family=Playfair+Display:ital,wght@0,400..900;1,400..900&amp;family=Plus+Jakarta+Sans:ital,wght@0,200..800;1,200..800&amp;family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&amp;family=Roboto+Mono:ital,wght@0,100..700;1,100..700&amp;family=Roboto:ital,wght@0,100..900;1,100..900&amp;family=Source+Code+Pro:ital,wght@0,200..900;1,200..900&amp;family=Source+Serif+4:ital,opsz,wght@0,8..60,200..900;1,8..60,200..900&amp;family=Space+Grotesk:wght@300..700&amp;family=Space+Mono:ital,wght@0,400;0,700;1,400;1,700&amp;display=swap" rel="stylesheet">
    <script type="module">"use strict";(()=>{var P="0.4.4";var v={HIGHLIGHT_COLOR:"#0079F2",HIGHLIGHT_BG:"#0079F210",ALLOWED_DOMAIN:".replit.dev",THEME_PREVIEW_STYLE_ID:"replit-theme-preview",MAX_SIBLING_HIGHLIGHTERS:1e3,MAX_DESCENDANTS_FOR_SCREENSHOT:1500},Z=`
  [contenteditable] {
    outline: none !important;
  }

  [contenteditable]:focus {
    outline: none !important;
  }
`,ee=`
  .beacon-highlighter {
    content: '';
    position: absolute;
    z-index: ${Number.MAX_SAFE_INTEGER-3};
    box-sizing: border-box;
    pointer-events: none;
    outline: 2px dashed ${v.HIGHLIGHT_COLOR} !important;
    outline-offset: 0 !important;
    margin: 0 !important;
    padding: 0 !important;
    transform: none !important;
    background: ${v.HIGHLIGHT_BG} !important;
    opacity: 0;
  }
  
  .beacon-hover-highlighter {
    position: fixed;
    z-index: ${Number.MAX_SAFE_INTEGER};
  }
  
  .beacon-selected-highlighter {
    position: fixed;
    pointer-events: none;
    outline: 2px solid ${v.HIGHLIGHT_COLOR} !important;
    outline-offset: 3px !important;
    background: none !important;
  }
  
  .beacon-label {
    position: absolute;
    background-color: ${v.HIGHLIGHT_COLOR};
    color: #FFFFFF;
    padding: 4px 8px;
    border-radius: 4px;
    font-size: 14px;
    font-family: monospace;
    line-height: 1;
    white-space: nowrap;
    box-shadow: 0 2px 4px rgba(0,0,0,0.2);
    transform: translateY(-100%);
    margin-top: -4px;
    left: 0;
    z-index: ${Number.MAX_SAFE_INTEGER-2};
    pointer-events: none;
    opacity: 0;
  }
  
  .beacon-hover-label {
    position: fixed;
    z-index: ${Number.MAX_SAFE_INTEGER};
  }
  
  .beacon-selected-label {
    position: fixed;
    pointer-events: none;
  }
  
  .beacon-sibling-highlighter {
    position: fixed;
    pointer-events: none;
    outline: 2px dashed ${v.HIGHLIGHT_COLOR} !important;
    outline-offset: 0 !important;
    margin: 0 !important;
    padding: 0 !important;
    transform: none !important;
    background: ${v.HIGHLIGHT_BG} !important;
  }
`;function Me(e,i){return e[13]=1,e[14]=i>>8,e[15]=i&255,e[16]=i>>8,e[17]=i&255,e}var le=112,ae=72,ce=89,he=115,G;function Re(){let e=new Int32Array(256);for(let i=0;i<256;i++){let t=i;for(let n=0;n<8;n++)t=t&1?3988292384^t>>>1:t>>>1;e[i]=t}return e}function De(e){let i=-1;G||(G=Re());for(let t=0;t<e.length;t++)i=G[(i^e[t])&255]^i>>>8;return i^-1}function Oe(e){let i=e.length-1;for(let t=i;t>=4;t--)if(e[t-4]===9&&e[t-3]===le&&e[t-2]===ae&&e[t-1]===ce&&e[t]===he)return t-3;return 0}function Pe(e,i,t=!1){let n=new Uint8Array(13);i*=39.3701,n[0]=le,n[1]=ae,n[2]=ce,n[3]=he,n[4]=i>>>24,n[5]=i>>>16,n[6]=i>>>8,n[7]=i&255,n[8]=n[4],n[9]=n[5],n[10]=n[6],n[11]=n[7],n[12]=1;let s=De(n),r=new Uint8Array(4);if(r[0]=s>>>24,r[1]=s>>>16,r[2]=s>>>8,r[3]=s&255,t){let l=Oe(e);return e.set(n,l),e.set(r,l+13),e}else{let l=new Uint8Array(4);l[0]=0,l[1]=0,l[2]=0,l[3]=9;let o=new Uint8Array(54);return o.set(e,0),o.set(l,33),o.set(n,37),o.set(r,50),o}}var de="[modern-screenshot]",H=typeof window<"u",Fe=H&&"Worker"in window,ke=H&&"atob"in window,Yt=H&&"btoa"in window,V=H?window.navigator?.userAgent:"",ue=V.includes("Chrome"),F=V.includes("AppleWebKit")&&!ue,j=V.includes("Firefox"),Ue=e=>e&&"__CONTEXT__"in e,$e=e=>e.constructor.name==="CSSFontFaceRule",Be=e=>e.constructor.name==="CSSImportRule",S=e=>e.nodeType===1,N=e=>typeof e.className=="object",ge=e=>e.tagName==="image",Ge=e=>e.tagName==="use",x=e=>S(e)&&typeof e.style<"u"&&!N(e),We=e=>e.nodeType===8,Ve=e=>e.nodeType===3,L=e=>e.tagName==="IMG",k=e=>e.tagName==="VIDEO",je=e=>e.tagName==="CANVAS",qe=e=>e.tagName==="TEXTAREA",ze=e=>e.tagName==="INPUT",Xe=e=>e.tagName==="STYLE",Ye=e=>e.tagName==="SCRIPT",Ke=e=>e.tagName==="SELECT",Je=e=>e.tagName==="SLOT",Qe=e=>e.tagName==="IFRAME",Ze=(...e)=>console.warn(de,...e);function et(e){let i=e?.createElement?.("canvas");return i&&(i.height=i.width=1),!!i&&"toDataURL"in i&&!!i.toDataURL("image/webp").includes("image/webp")}var W=e=>e.startsWith("data:");function me(e,i){if(e.match(/^[a-z]+:\/\//i))return e;if(H&&e.match(/^\/\//))return window.location.protocol+e;if(e.match(/^[a-z]+:/i)||!H)return e;let t=U().implementation.createHTMLDocument(),n=t.createElement("base"),s=t.createElement("a");return t.head.appendChild(n),t.body.appendChild(s),i&&(n.href=i),s.href=e,s.href}function U(e){return(e&&S(e)?e?.ownerDocument:e)??window.document}var $="http://www.w3.org/2000/svg";function tt(e,i,t){let n=U(t).createElementNS($,"svg");return n.setAttributeNS(null,"width",e.toString()),n.setAttributeNS(null,"height",i.toString()),n.setAttributeNS(null,"viewBox",`0 0 ${e} ${i}`),n}function it(e,i){let t=new XMLSerializer().serializeToString(e);return i&&(t=t.replace(/[\u0000-\u0008\v\f\u000E-\u001F\uD800-\uDFFF\uFFFE\uFFFF]/gu,"")),`data:image/svg+xml;charset=utf-8,${encodeURIComponent(t)}`}async function nt(e,i="image/png",t=1){try{return await new Promise((n,s)=>{e.toBlob(r=>{r?n(r):s(new Error("Blob is null"))},i,t)})}catch(n){if(ke)return rt(e.toDataURL(i,t));throw n}}function rt(e){let[i,t]=e.split(","),n=i.match(/data:(.+);/)?.[1]??void 0,s=window.atob(t),r=s.length,l=new Uint8Array(r);for(let o=0;o<r;o+=1)l[o]=s.charCodeAt(o);return new Blob([l],{type:n})}function fe(e,i){return new Promise((t,n)=>{let s=new FileReader;s.onload=()=>t(s.result),s.onerror=()=>n(s.error),s.onabort=()=>n(new Error(`Failed read blob to ${i}`)),i==="dataUrl"?s.readAsDataURL(e):i==="arrayBuffer"&&s.readAsArrayBuffer(e)})}var st=e=>fe(e,"dataUrl"),ot=e=>fe(e,"arrayBuffer");function C(e,i){let t=U(i).createElement("img");return t.decoding="sync",t.loading="eager",t.src=e,t}function _(e,i){return new Promise(t=>{let{timeout:n,ownerDocument:s,onError:r,onWarn:l}=i??{},o=typeof e=="string"?C(e,U(s)):e,c=null,h=null;function a(){t(o),c&&clearTimeout(c),h?.()}if(n&&(c=setTimeout(a,n)),k(o)){let d=o.currentSrc||o.src;if(!d)return o.poster?_(o.poster,i).then(t):a();if(o.readyState>=2)return a();let u=a,m=g=>{l?.("Failed video load",d,g),r?.(g),a()};h=()=>{o.removeEventListener("loadeddata",u),o.removeEventListener("error",m)},o.addEventListener("loadeddata",u,{once:!0}),o.addEventListener("error",m,{once:!0})}else{let d=ge(o)?o.href.baseVal:o.currentSrc||o.src;if(!d)return a();let u=async()=>{if(L(o)&&"decode"in o)try{await o.decode()}catch(g){l?.("Failed to decode image, trying to render anyway",o.dataset.originalSrc||d,g)}a()},m=g=>{l?.("Failed image load",o.dataset.originalSrc||d,g),a()};if(L(o)&&o.complete)return u();h=()=>{o.removeEventListener("load",u),o.removeEventListener("error",m)},o.addEventListener("load",u,{once:!0}),o.addEventListener("error",m,{once:!0})}})}async function lt(e,i){x(e)&&(L(e)||k(e)?await _(e,i):await Promise.all(["img","video"].flatMap(t=>Array.from(e.querySelectorAll(t)).map(n=>_(n,i)))))}var pe=function(){let i=0,t=()=>`0000${(Math.random()*36**4<<0).toString(36)}`.slice(-4);return()=>(i+=1,`u${t()}${i}`)}();function be(e){return e?.split(",").map(i=>i.trim().replace(/"|'/g,"").toLowerCase()).filter(Boolean)}var te=0;function at(e){let i=`${de}[#${te}]`;return te++,{time:t=>e&&console.time(`${i} ${t}`),timeEnd:t=>e&&console.timeEnd(`${i} ${t}`),warn:(...t)=>e&&Ze(...t)}}function ct(e){return{cache:e?"no-cache":"force-cache"}}async function q(e,i){return Ue(e)?e:ht(e,{...i,autoDestruct:!0})}async function ht(e,i){let{scale:t=1,workerUrl:n,workerNumber:s=1}=i||{},r=!!i?.debug,l=i?.features??!0,o=e.ownerDocument??(H?window.document:void 0),c=e.ownerDocument?.defaultView??(H?window:void 0),h=new Map,a={width:0,height:0,quality:1,type:"image/png",scale:t,backgroundColor:null,style:null,filter:null,maximumCanvasSize:0,timeout:3e4,progress:null,debug:r,fetch:{requestInit:ct(i?.fetch?.bypassingCache),placeholderImage:"data:image/png;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7",bypassingCache:!1,...i?.fetch},fetchFn:null,font:{},drawImageInterval:100,workerUrl:null,workerNumber:s,onCloneNode:null,onEmbedNode:null,onCreateForeignObjectSvg:null,includeStyleProperties:null,autoDestruct:!1,...i,__CONTEXT__:!0,log:at(r),node:e,ownerDocument:o,ownerWindow:c,dpi:t===1?null:96*t,svgStyleElement:Ee(o),svgDefsElement:o?.createElementNS($,"defs"),svgStyles:new Map,defaultComputedStyles:new Map,workers:[...Array.from({length:Fe&&n&&s?s:0})].map(()=>{try{let m=new Worker(n);return m.onmessage=async g=>{let{url:f,result:p}=g.data;p?h.get(f)?.resolve?.(p):h.get(f)?.reject?.(new Error(`Error receiving message from worker: ${f}`))},m.onmessageerror=g=>{let{url:f}=g.data;h.get(f)?.reject?.(new Error(`Error receiving message from worker: ${f}`))},m}catch(m){return a.log.warn("Failed to new Worker",m),null}}).filter(Boolean),fontFamilies:new Map,fontCssTexts:new Map,acceptOfImage:`${[et(o)&&"image/webp","image/svg+xml","image/*","*/*"].filter(Boolean).join(",")};q=0.8`,requests:h,drawImageCount:0,tasks:[],features:l,isEnable:m=>m==="restoreScrollPosition"?typeof l=="boolean"?!1:l[m]??!1:typeof l=="boolean"?l:l[m]??!0};a.log.time("wait until load"),await lt(e,{timeout:a.timeout,onWarn:a.log.warn}),a.log.timeEnd("wait until load");let{width:d,height:u}=dt(e,a);return a.width=d,a.height=u,a}function Ee(e){if(!e)return;let i=e.createElement("style"),t=i.ownerDocument.createTextNode(`
.______background-clip--text {
  background-clip: text;
  -webkit-background-clip: text;
}
`);return i.appendChild(t),i}function dt(e,i){let{width:t,height:n}=i;if(S(e)&&(!t||!n)){let s=e.getBoundingClientRect();t=t||s.width||Number(e.getAttribute("width"))||0,n=n||s.height||Number(e.getAttribute("height"))||0}return{width:t,height:n}}async function ut(e,i){let{log:t,timeout:n,drawImageCount:s,drawImageInterval:r}=i;t.time("image to canvas");let l=await _(e,{timeout:n,onWarn:i.log.warn}),{canvas:o,context2d:c}=gt(e.ownerDocument,i),h=()=>{try{c?.drawImage(l,0,0,o.width,o.height)}catch(a){i.log.warn("Failed to drawImage",a)}};if(h(),i.isEnable("fixSvgXmlDecode"))for(let a=0;a<s;a++)await new Promise(d=>{setTimeout(()=>{h(),d()},a+r)});return i.drawImageCount=0,t.timeEnd("image to canvas"),o}function gt(e,i){let{width:t,height:n,scale:s,backgroundColor:r,maximumCanvasSize:l}=i,o=e.createElement("canvas");o.width=Math.floor(t*s),o.height=Math.floor(n*s),o.style.width=`${t}px`,o.style.height=`${n}px`,l&&(o.width>l||o.height>l)&&(o.width>l&&o.height>l?o.width>o.height?(o.height*=l/o.width,o.width=l):(o.width*=l/o.height,o.height=l):o.width>l?(o.height*=l/o.width,o.width=l):(o.width*=l/o.height,o.height=l));let c=o.getContext("2d");return c&&r&&(c.fillStyle=r,c.fillRect(0,0,o.width,o.height)),{canvas:o,context2d:c}}function ve(e,i){if(e.ownerDocument)try{let r=e.toDataURL();if(r!=="data:,")return C(r,e.ownerDocument)}catch(r){i.log.warn("Failed to clone canvas",r)}let t=e.cloneNode(!1),n=e.getContext("2d"),s=t.getContext("2d");try{return n&&s&&s.putImageData(n.getImageData(0,0,e.width,e.height),0,0),t}catch(r){i.log.warn("Failed to clone canvas",r)}return t}function mt(e,i){try{if(e?.contentDocument?.body)return z(e.contentDocument.body,i)}catch(t){i.log.warn("Failed to clone iframe",t)}return e.cloneNode(!1)}function ft(e){let i=e.cloneNode(!1);return e.currentSrc&&e.currentSrc!==e.src&&(i.src=e.currentSrc,i.srcset=""),i.loading==="lazy"&&(i.loading="eager"),i}async function pt(e,i){if(e.ownerDocument&&!e.currentSrc&&e.poster)return C(e.poster,e.ownerDocument);let t=e.cloneNode(!1);t.crossOrigin="anonymous",e.currentSrc&&e.currentSrc!==e.src&&(t.src=e.currentSrc);let n=t.ownerDocument;if(n){let s=!0;if(await _(t,{onError:()=>s=!1,onWarn:i.log.warn}),!s)return e.poster?C(e.poster,e.ownerDocument):t;t.currentTime=e.currentTime,await new Promise(l=>{t.addEventListener("seeked",l,{once:!0})});let r=n.createElement("canvas");r.width=e.offsetWidth,r.height=e.offsetHeight;try{let l=r.getContext("2d");l&&l.drawImage(t,0,0,r.width,r.height)}catch(l){return i.log.warn("Failed to clone video",l),e.poster?C(e.poster,e.ownerDocument):t}return ve(r,i)}return t}function bt(e,i){return je(e)?ve(e,i):Qe(e)?mt(e,i):L(e)?ft(e):k(e)?pt(e,i):e.cloneNode(!1)}function Et(e){let i=e.sandbox;if(!i){let{ownerDocument:t}=e;try{t&&(i=t.createElement("iframe"),i.id=`__SANDBOX__-${pe()}`,i.width="0",i.height="0",i.style.visibility="hidden",i.style.position="fixed",t.body.appendChild(i),i.contentWindow?.document.write('<!DOCTYPE html><meta charset="UTF-8"><title></title><body>'),e.sandbox=i)}catch(n){e.log.warn("Failed to getSandBox",n)}}return i}var vt=["width","height","-webkit-text-fill-color"],wt=["stroke","fill"];function we(e,i,t){let{defaultComputedStyles:n}=t,s=e.nodeName.toLowerCase(),r=N(e)&&s!=="svg",l=r?wt.map(f=>[f,e.getAttribute(f)]).filter(([,f])=>f!==null):[],o=[r&&"svg",s,l.map((f,p)=>`${f}=${p}`).join(","),i].filter(Boolean).join(":");if(n.has(o))return n.get(o);let h=Et(t)?.contentWindow;if(!h)return new Map;let a=h?.document,d,u;r?(d=a.createElementNS($,"svg"),u=d.ownerDocument.createElementNS(d.namespaceURI,s),l.forEach(([f,p])=>{u.setAttributeNS(null,f,p)}),d.appendChild(u)):d=u=a.createElement(s),u.textContent=" ",a.body.appendChild(d);let m=h.getComputedStyle(u,i),g=new Map;for(let f=m.length,p=0;p<f;p++){let b=m.item(p);vt.includes(b)||g.set(b,m.getPropertyValue(b))}return a.body.removeChild(d),n.set(o,g),g}function ye(e,i,t){let n=new Map,s=[],r=new Map;if(t)for(let o of t)l(o);else for(let o=e.length,c=0;c<o;c++){let h=e.item(c);l(h)}for(let o=s.length,c=0;c<o;c++)r.get(s[c])?.forEach((h,a)=>n.set(a,h));function l(o){let c=e.getPropertyValue(o),h=e.getPropertyPriority(o),a=o.lastIndexOf("-"),d=a>-1?o.substring(0,a):void 0;if(d){let u=r.get(d);u||(u=new Map,r.set(d,u)),u.set(o,[c,h])}i.get(o)===c&&!h||(d?s.push(d):n.set(o,[c,h]))}return n}function yt(e,i,t,n){let{ownerWindow:s,includeStyleProperties:r,currentParentNodeStyle:l}=n,o=i.style,c=s.getComputedStyle(e),h=we(e,null,n);l?.forEach((d,u)=>{h.delete(u)});let a=ye(c,h,r);a.delete("transition-property"),a.delete("all"),a.delete("d"),a.delete("content"),t&&(a.delete("margin-top"),a.delete("margin-right"),a.delete("margin-bottom"),a.delete("margin-left"),a.delete("margin-block-start"),a.delete("margin-block-end"),a.delete("margin-inline-start"),a.delete("margin-inline-end"),a.set("box-sizing",["border-box",""])),a.get("background-clip")?.[0]==="text"&&i.classList.add("______background-clip--text"),ue&&(a.has("font-kerning")||a.set("font-kerning",["normal",""]),(a.get("overflow-x")?.[0]==="hidden"||a.get("overflow-y")?.[0]==="hidden")&&a.get("text-overflow")?.[0]==="ellipsis"&&e.scrollWidth===e.clientWidth&&a.set("text-overflow",["clip",""]));for(let d=o.length,u=0;u<d;u++)o.removeProperty(o.item(u));return a.forEach(([d,u],m)=>{o.setProperty(m,d,u)}),a}function St(e,i){(qe(e)||ze(e)||Ke(e))&&i.setAttribute("value",e.value)}var Tt=[":before",":after"],At=[":-webkit-scrollbar",":-webkit-scrollbar-button",":-webkit-scrollbar-thumb",":-webkit-scrollbar-track",":-webkit-scrollbar-track-piece",":-webkit-scrollbar-corner",":-webkit-resizer"];function Ht(e,i,t,n,s){let{ownerWindow:r,svgStyleElement:l,svgStyles:o,currentNodeStyle:c}=n;if(!l||!r)return;function h(a){let d=r.getComputedStyle(e,a),u=d.getPropertyValue("content");if(!u||u==="none")return;s?.(u),u=u.replace(/(')|(")|(counter\(.+\))/g,"");let m=[pe()],g=we(e,a,n);c?.forEach((E,y)=>{g.delete(y)});let f=ye(d,g,n.includeStyleProperties);f.delete("content"),f.delete("-webkit-locale"),f.get("background-clip")?.[0]==="text"&&i.classList.add("______background-clip--text");let p=[`content: '${u}';`];if(f.forEach(([E,y],A)=>{p.push(`${A}: ${E}${y?" !important":""};`)}),p.length===1)return;try{i.className=[i.className,...m].join(" ")}catch(E){n.log.warn("Failed to copyPseudoClass",E);return}let b=p.join(`
  `),w=o.get(b);w||(w=[],o.set(b,w)),w.push(`.${m[0]}:${a}`)}Tt.forEach(h),t&&At.forEach(h)}var ie=new Set(["symbol"]);async function ne(e,i,t,n,s){if(S(t)&&(Xe(t)||Ye(t))||n.filter&&!n.filter(t))return;ie.has(i.nodeName)||ie.has(t.nodeName)?n.currentParentNodeStyle=void 0:n.currentParentNodeStyle=n.currentNodeStyle;let r=await z(t,n,!1,s);n.isEnable("restoreScrollPosition")&&Ct(e,r),i.appendChild(r)}async function re(e,i,t,n){let s=(S(e)?e.shadowRoot?.firstChild:void 0)??e.firstChild;for(let r=s;r;r=r.nextSibling)if(!We(r))if(S(r)&&Je(r)&&typeof r.assignedNodes=="function"){let l=r.assignedNodes();for(let o=0;o<l.length;o++)await ne(e,i,l[o],t,n)}else await ne(e,i,r,t,n)}function Ct(e,i){if(!x(e)||!x(i))return;let{scrollTop:t,scrollLeft:n}=e;if(!t&&!n)return;let{transform:s}=i.style,r=new DOMMatrix(s),{a:l,b:o,c,d:h}=r;r.a=1,r.b=0,r.c=0,r.d=1,r.translateSelf(-n,-t),r.a=l,r.b=o,r.c=c,r.d=h,i.style.transform=r.toString()}function Lt(e,i){let{backgroundColor:t,width:n,height:s,style:r}=i,l=e.style;if(t&&l.setProperty("background-color",t,"important"),n&&l.setProperty("width",`${n}px`,"important"),s&&l.setProperty("height",`${s}px`,"important"),r)for(let o in r)l[o]=r[o]}var xt=/^[\w-:]+$/;async function z(e,i,t=!1,n){let{ownerDocument:s,ownerWindow:r,fontFamilies:l}=i;if(s&&Ve(e))return n&&/\S/.test(e.data)&&n(e.data),s.createTextNode(e.data);if(s&&r&&S(e)&&(x(e)||N(e))){let c=await bt(e,i);if(i.isEnable("removeAbnormalAttributes")){let g=c.getAttributeNames();for(let f=g.length,p=0;p<f;p++){let b=g[p];xt.test(b)||c.removeAttribute(b)}}let h=i.currentNodeStyle=yt(e,c,t,i);t&&Lt(c,i);let a=!1;if(i.isEnable("copyScrollbar")){let g=[h.get("overflow-x")?.[0],h.get("overflow-y")?.[0]];a=g.includes("scroll")||(g.includes("auto")||g.includes("overlay"))&&(e.scrollHeight>e.clientHeight||e.scrollWidth>e.clientWidth)}let d=h.get("text-transform")?.[0],u=be(h.get("font-family")?.[0]),m=u?g=>{d==="uppercase"?g=g.toUpperCase():d==="lowercase"?g=g.toLowerCase():d==="capitalize"&&(g=g[0].toUpperCase()+g.substring(1)),u.forEach(f=>{let p=l.get(f);p||l.set(f,p=new Set),g.split("").forEach(b=>p.add(b))})}:void 0;return Ht(e,c,a,i,m),St(e,c),k(e)||await re(e,c,i,m),c}let o=e.cloneNode(!1);return await re(e,o,i),o}function _t(e){if(e.ownerDocument=void 0,e.ownerWindow=void 0,e.svgStyleElement=void 0,e.svgDefsElement=void 0,e.svgStyles.clear(),e.defaultComputedStyles.clear(),e.sandbox){try{e.sandbox.remove()}catch(i){e.log.warn("Failed to destroyContext",i)}e.sandbox=void 0}e.workers=[],e.fontFamilies.clear(),e.fontCssTexts.clear(),e.requests.clear(),e.tasks=[]}function It(e){let{url:i,timeout:t,responseType:n,...s}=e,r=new AbortController,l=t?setTimeout(()=>r.abort(),t):void 0;return fetch(i,{signal:r.signal,...s}).then(o=>{if(!o.ok)throw new Error("Failed fetch, not 2xx response",{cause:o});switch(n){case"arrayBuffer":return o.arrayBuffer();case"dataUrl":return o.blob().then(st);case"text":default:return o.text()}}).finally(()=>clearTimeout(l))}function I(e,i){let{url:t,requestType:n="text",responseType:s="text",imageDom:r}=i,l=t,{timeout:o,acceptOfImage:c,requests:h,fetchFn:a,fetch:{requestInit:d,bypassingCache:u,placeholderImage:m},font:g,workers:f,fontFamilies:p}=e;n==="image"&&(F||j)&&e.drawImageCount++;let b=h.get(t);if(!b){u&&u instanceof RegExp&&u.test(l)&&(l+=(/\?/.test(l)?"&":"?")+new Date().getTime());let w=n.startsWith("font")&&g&&g.minify,E=new Set;w&&n.split(";")[1].split(",").forEach(O=>{p.has(O)&&p.get(O).forEach(Q=>E.add(Q))});let y=w&&E.size,A={url:l,timeout:o,responseType:y?"arrayBuffer":s,headers:n==="image"?{accept:c}:void 0,...d};b={type:n,resolve:void 0,reject:void 0,response:null},b.response=(async()=>{if(a&&n==="image"){let T=await a(t);if(T)return T}return!F&&t.startsWith("http")&&f.length?new Promise((T,O)=>{f[h.size&f.length-1].postMessage({rawUrl:t,...A}),b.resolve=T,b.reject=O}):It(A)})().catch(T=>{if(h.delete(t),n==="image"&&m)return e.log.warn("Failed to fetch image base64, trying to use placeholder image",l),typeof m=="string"?m:m(r);throw T}),h.set(t,b)}return b.response}async function Se(e,i,t,n){if(!Te(e))return e;for(let[s,r]of Nt(e,i))try{let l=await I(t,{url:r,requestType:n?"image":"text",responseType:"dataUrl"});e=e.replace(Mt(s),`$1${l}$3`)}catch(l){t.log.warn("Failed to fetch css data url",s,l)}return e}function Te(e){return/url\((['"]?)([^'"]+?)\1\)/.test(e)}var Ae=/url\((['"]?)([^'"]+?)\1\)/g;function Nt(e,i){let t=[];return e.replace(Ae,(n,s,r)=>(t.push([r,me(r,i)]),n)),t.filter(([n])=>!W(n))}function Mt(e){let i=e.replace(/([.*+?^${}()|\[\]\/\\])/g,"\\$1");return new RegExp(`(url\\(['"]?)(${i})(['"]?\\))`,"g")}var Rt=["background-image","border-image-source","-webkit-border-image","-webkit-mask-image","list-style-image"];function Dt(e,i){return Rt.map(t=>{let n=e.getPropertyValue(t);return!n||n==="none"?null:((F||j)&&i.drawImageCount++,Se(n,null,i,!0).then(s=>{!s||n===s||e.setProperty(t,s,e.getPropertyPriority(t))}))}).filter(Boolean)}function Ot(e,i){if(L(e)){let t=e.currentSrc||e.src;if(!W(t))return[I(i,{url:t,imageDom:e,requestType:"image",responseType:"dataUrl"}).then(n=>{n&&(e.srcset="",e.dataset.originalSrc=t,e.src=n||"")})];(F||j)&&i.drawImageCount++}else if(N(e)&&!W(e.href.baseVal)){let t=e.href.baseVal;return[I(i,{url:t,imageDom:e,requestType:"image",responseType:"dataUrl"}).then(n=>{n&&(e.dataset.originalSrc=t,e.href.baseVal=n||"")})]}return[]}function Pt(e,i){let{ownerDocument:t,svgDefsElement:n}=i,s=e.getAttribute("href")??e.getAttribute("xlink:href");if(!s)return[];let[r,l]=s.split("#");if(l){let o=`#${l}`,c=t?.querySelector(`svg ${o}`);if(r&&e.setAttribute("href",o),n?.querySelector(o))return[];if(c)return n?.appendChild(c.cloneNode(!0)),[];if(r)return[I(i,{url:r,responseType:"text"}).then(h=>{n?.insertAdjacentHTML("beforeend",h)})]}return[]}function He(e,i){let{tasks:t}=i;S(e)&&((L(e)||ge(e))&&t.push(...Ot(e,i)),Ge(e)&&t.push(...Pt(e,i))),x(e)&&t.push(...Dt(e.style,i)),e.childNodes.forEach(n=>{He(n,i)})}async function Ft(e,i){let{ownerDocument:t,svgStyleElement:n,fontFamilies:s,fontCssTexts:r,tasks:l,font:o}=i;if(!(!t||!n||!s.size))if(o&&o.cssText){let c=oe(o.cssText,i);n.appendChild(t.createTextNode(`${c}
`))}else{let c=Array.from(t.styleSheets).filter(a=>{try{return"cssRules"in a&&!!a.cssRules.length}catch(d){return i.log.warn(`Error while reading CSS rules from ${a.href}`,d),!1}});await Promise.all(c.flatMap(a=>Array.from(a.cssRules).map(async(d,u)=>{if(Be(d)){let m=u+1,g=d.href,f="";try{f=await I(i,{url:g,requestType:"text",responseType:"text"})}catch(b){i.log.warn(`Error fetch remote css import from ${g}`,b)}let p=f.replace(Ae,(b,w,E)=>b.replace(E,me(E,g)));for(let b of Ut(p))try{a.insertRule(b,b.startsWith("@import")?m+=1:a.cssRules.length)}catch(w){i.log.warn("Error inserting rule from remote css import",{rule:b,error:w})}}}))),c.flatMap(a=>Array.from(a.cssRules)).filter(a=>$e(a)&&Te(a.style.getPropertyValue("src"))&&be(a.style.getPropertyValue("font-family"))?.some(d=>s.has(d))).forEach(a=>{let d=a,u=r.get(d.cssText);u?n.appendChild(t.createTextNode(`${u}
`)):l.push(Se(d.cssText,d.parentStyleSheet?d.parentStyleSheet.href:null,i).then(m=>{m=oe(m,i),r.set(d.cssText,m),n.appendChild(t.createTextNode(`${m}
`))}))})}}var kt=/(\/\*[\s\S]*?\*\/)/g,se=/((@.*?keyframes [\s\S]*?){([\s\S]*?}\s*?)})/gi;function Ut(e){if(e==null)return[];let i=[],t=e.replace(kt,"");for(;;){let r=se.exec(t);if(!r)break;i.push(r[0])}t=t.replace(se,"");let n=/@import[\s\S]*?url\([^)]*\)[\s\S]*?;/gi,s=new RegExp("((\\s*?(?:\\/\\*[\\s\\S]*?\\*\\/)?\\s*?@media[\\s\\S]*?){([\\s\\S]*?)}\\s*?})|(([\\s\\S]*?){([\\s\\S]*?)})","gi");for(;;){let r=n.exec(t);if(r)s.lastIndex=n.lastIndex;else if(r=s.exec(t),r)n.lastIndex=s.lastIndex;else break;i.push(r[0])}return i}var $t=/url\([^)]+\)\s*format\((["']?)([^"']+)\1\)/g,Bt=/src:\s*(?:url\([^)]+\)\s*format\([^)]+\)[,;]\s*)+/g;function oe(e,i){let{font:t}=i,n=t?t?.preferredFormat:void 0;return n?e.replace(Bt,s=>{for(;;){let[r,,l]=$t.exec(s)||[];if(!l)return"";if(l===n)return`src: ${r};`}}):e}async function Gt(e,i){let t=await q(e,i);if(S(t.node)&&N(t.node))return t.node;let{ownerDocument:n,log:s,tasks:r,svgStyleElement:l,svgDefsElement:o,svgStyles:c,font:h,progress:a,autoDestruct:d,onCloneNode:u,onEmbedNode:m,onCreateForeignObjectSvg:g}=t;s.time("clone node");let f=await z(t.node,t,!0);if(l&&n){let y="";c.forEach((A,T)=>{y+=`${A.join(`,
`)} {
  ${T}
}
`}),l.appendChild(n.createTextNode(y))}s.timeEnd("clone node"),await u?.(f),h!==!1&&S(f)&&(s.time("embed web font"),await Ft(f,t),s.timeEnd("embed web font")),s.time("embed node"),He(f,t);let p=r.length,b=0,w=async()=>{for(;;){let y=r.pop();if(!y)break;try{await y}catch(A){t.log.warn("Failed to run task",A)}a?.(++b,p)}};a?.(b,p),await Promise.all([...Array.from({length:4})].map(w)),s.timeEnd("embed node"),await m?.(f);let E=Wt(f,t);return o&&E.insertBefore(o,E.children[0]),l&&E.insertBefore(l,E.children[0]),d&&_t(t),await g?.(E),E}function Wt(e,i){let{width:t,height:n}=i,s=tt(t,n,e.ownerDocument),r=s.ownerDocument.createElementNS(s.namespaceURI,"foreignObject");return r.setAttributeNS(null,"x","0%"),r.setAttributeNS(null,"y","0%"),r.setAttributeNS(null,"width","100%"),r.setAttributeNS(null,"height","100%"),r.append(e),s.appendChild(r),s}async function Vt(e,i){let t=await q(e,i),n=await Gt(t),s=it(n,t.isEnable("removeControlCharacter"));t.autoDestruct||(t.svgStyleElement=Ee(t.ownerDocument),t.svgDefsElement=t.ownerDocument?.createElementNS($,"defs"),t.svgStyles.clear());let r=C(s,n.ownerDocument);return await ut(r,t)}async function Ce(e,i){let t=await q(e,i),{log:n,type:s,quality:r,dpi:l}=t,o=await Vt(t);n.time("canvas to blob");let c=await nt(o,s,r);if(["image/png","image/jpeg"].includes(s)&&l){let h=await ot(c.slice(0,33)),a=new Uint8Array(h);return s==="image/png"?a=Pe(a,l):s==="image/jpeg"&&(a=Me(a,l)),n.timeEnd("canvas to blob"),new Blob([a,c.slice(33)],{type:s})}return n.timeEnd("canvas to blob"),c}var M={METADATA:"data-replit-metadata",COMPONENT_NAME:"data-component-name"};function Le(e){if(e.startsWith("http://localhost:"))return!0;try{return new URL(e).hostname.endsWith(v.ALLOWED_DOMAIN)}catch{return!1}}function Y(e){if(!e)return null;let i=document.elementFromPoint(e.clientX,e.clientY);return i instanceof HTMLElement?i:null}function jt(e,i=300){if(!e)return"";let t=String(e);return t.length<=i?t:t.slice(0,i)+"..."}function X(e){if(e)return{tagName:e.tagName.toLowerCase(),className:e.className.toString?e.className.toString():String(e.className),textContent:e.textContent??"",id:e.id}}function B(e){let i=e.getAttribute(M.COMPONENT_NAME)??e.tagName.toLowerCase();return jt(i,50)}function K(e){let i=window.getComputedStyle(e),t=e.parentElement,n=e.nextElementSibling,s=t?.parentElement??null,r={backgroundColor:i.backgroundColor,color:i.color,display:i.display,position:i.position,width:i.width,height:i.height,fontSize:i.fontSize,fontFamily:i.fontFamily,fontWeight:i.fontWeight,margin:i.margin,padding:i.padding,textAlign:i.textAlign};return{elementPath:e.getAttribute(M.METADATA)??"",elementName:B(e),textContent:e.textContent??"",originalTextContent:e.getAttribute("data-original-text")?decodeURIComponent(e.getAttribute("data-original-text")??""):void 0,srcAttribute:e.getAttribute("src")??"",hasChildElements:e.childElementCount>0,id:e.id,className:e.className.toString?e.className.toString():String(e.className),computedStyles:r,textAlign:i.textAlign,relatedElements:{parent:X(t),nextSibling:X(n),grandParent:X(s)}}}async function xe(e){try{let t=window.getComputedStyle(e).backgroundColor;return qt(t)&&(t=window.getComputedStyle(document.documentElement).backgroundColor),await Ce(e,{type:"image/png",backgroundColor:t})}catch(i){console.error("[replit-cartographer] Failed to take screenshot:",i);return}}function qt(e){return e==="transparent"||e==="rgba(0, 0, 0, 0)"||e.endsWith(", 0)")||e.endsWith(",0)")}function J(e){let i=e.getBoundingClientRect(),t=window.innerHeight,n=window.innerWidth;return i.bottom>0&&i.top<t&&i.right>0&&i.left<n}function R(e,i=v.MAX_SIBLING_HIGHLIGHTERS,t=!1){let r=e.getAttribute(M.METADATA);if(!r)return[];let l=`[${M.METADATA}="${r}"]`,o=document,c=e.parentElement;c&&c.childElementCount>50&&(o=c);let h=o.querySelectorAll(l),a=Math.min(i,5e3),d=[],u=0;for(let m=0;m<h.length&&u<a;m++){let g=h[m];if(g instanceof HTMLElement&&g!==e){if(t&&!J(g))continue;d.push(g),u++}}return d}function _e(e,i,t){let n=e.children;for(let s=0;s<n.length;s++)if(t.value+=1,t.value>i||_e(n[s],i,t))return!0;return!1}function Ie(e){let i={value:0};return _e(e,v.MAX_DESCENDANTS_FOR_SCREENSHOT,i)}var D=class{selectedElement=null;selectedSiblingElements=[];visibleSelectedSiblingElements=[];isActive=!1;lastHighlightedElement=null;enableEditing=!1;shadowHost=null;shadowRoot=null;hoverHighlighter=null;hoverLabel=null;selectedHighlighter=null;selectedLabel=null;hoverSiblingHighlighters=[];selectedSiblingHighlighters=[];mutationObserver=null;throttledRecalculate=null;constructor(){this.setupMessageListener(),this.observeLightDarkModeSwitch(),this.notifyScriptLoaded(),this.throttledRecalculate=this.throttleRAF(this.recalculateSelectedElement.bind(this))}throttleRAF(i){let t=null,n=null;return(...s)=>{n=s,t===null&&(t=requestAnimationFrame(()=>{n!==null&&i(...n),t=null,n=null}))}}isPureTextElement(i){if(!i||!(i instanceof HTMLElement))return!1;let t=i.tagName.toLowerCase();if(t==="style"||t==="script"||t==="img"||i.childElementCount>0)return!1;let n=i.getAttribute("style");return n&&n.trim()!==""?!1:Array.from(i.childNodes).every(r=>r.nodeType===Node.TEXT_NODE)}initializeHighlighter(){this.shadowHost=document.createElement("div"),this.shadowHost.style.all="initial",this.shadowRoot=this.shadowHost.attachShadow({mode:"open"}),document.body.appendChild(this.shadowHost);let i=document.createElement("style");i.textContent=ee,this.shadowRoot.appendChild(i);let t=document.createElement("style");t.textContent=Z,document.head.appendChild(t),this.hoverHighlighter=document.createElement("div"),this.hoverLabel=document.createElement("div"),this.hoverHighlighter.className="beacon-highlighter beacon-hover-highlighter",this.hoverLabel.className="beacon-label beacon-hover-label",this.selectedHighlighter=document.createElement("div"),this.selectedLabel=document.createElement("div"),this.selectedHighlighter.className="beacon-highlighter beacon-selected-highlighter",this.selectedLabel.className="beacon-label beacon-selected-label",this.shadowRoot.appendChild(this.selectedHighlighter),this.shadowRoot.appendChild(this.selectedLabel),this.shadowRoot.appendChild(this.hoverHighlighter),this.shadowRoot.appendChild(this.hoverLabel)}setupMessageListener(){window.addEventListener("message",this.handleMessage.bind(this))}notifyScriptLoaded(){this.postMessageToParent({type:"SELECTOR_SCRIPT_LOADED",timestamp:Date.now(),version:P})}postMessageToParent(i){window.parent&&window.parent.postMessage(i,"*")}handleMouseMove=i=>{if(this.isActive&&this.hoverHighlighter){let t=Y(i);if(!t||t===this.hoverHighlighter||t===this.selectedHighlighter||t===this.shadowHost||this.selectedSiblingHighlighters.includes(t)||this.hoverSiblingHighlighters.includes(t)){this.hideHighlight(this.hoverHighlighter,this.hoverLabel),this.lastHighlightedElement=null,this.clearHoverSiblingHighlighters();return}if(t===this.selectedElement){this.hideHighlight(this.hoverHighlighter,this.hoverLabel),this.lastHighlightedElement=null,this.clearHoverSiblingHighlighters();return}this.lastHighlightedElement&&this.lastHighlightedElement!==t&&this.lastHighlightedElement!==this.selectedElement&&this.lastHighlightedElement.removeAttribute("contenteditable"),this.lastHighlightedElement=t,this.updateHighlighterPosition(t,this.hoverHighlighter,this.hoverLabel)}};handleMouseLeave=()=>{this.isActive&&(this.hoverHighlighter&&(this.hoverHighlighter.style.opacity="0"),this.hoverLabel&&(this.hoverLabel.style.opacity="0"),this.hoverSiblingHighlighters.length>0&&this.clearHoverSiblingHighlighters(),this.lastHighlightedElement&&this.lastHighlightedElement!==this.selectedElement&&this.lastHighlightedElement.removeAttribute("contenteditable"))};calculateLabelPosition(i,t){return t<28?{top:`${t}px`,left:`${i.left}px`,transform:"none",marginTop:"2px"}:{top:`${t}px`,left:`${i.left}px`,transform:"translateY(-100%)",marginTop:"-4px"}}updateHighlighterPosition(i,t,n){if(!t||!n)return;let s=R(i,v.MAX_SIBLING_HIGHLIGHTERS,!1);this.enableEditing&&s.length<=1&&i===this.selectedElement&&this.isPureTextElement(i)&&i.setAttribute("contenteditable","plaintext-only");let r=i.getBoundingClientRect(),l=window.innerHeight,o=Math.max(0,r.top),c=Math.min(l,r.bottom),h=Math.max(0,c-o);Object.assign(t.style,{opacity:h>0?"1":"0",top:`${o}px`,left:`${r.left}px`,width:`${r.width}px`,height:`${h}px`}),n.textContent=B(i);let a=this.calculateLabelPosition(r,o);Object.assign(n.style,{...a,opacity:h>0?"1":"0"}),t===this.selectedHighlighter?this.highlightSelectedSiblings(i):this.highlightHoverSiblings(i)}hideHighlight(i,t){i&&(i.style.opacity="0"),t&&(t.style.opacity="0");let n=i===this.hoverHighlighter,s=i===this.selectedHighlighter;n&&this.clearHoverSiblingHighlighters(),s&&this.clearSelectedSiblingHighlighters()}handleClick=async i=>{if(!this.isActive)return;i.preventDefault(),i.stopPropagation();let t=Y(i);if((!t||t===this.hoverHighlighter||t===this.selectedHighlighter||t===this.shadowHost)&&(t=this.lastHighlightedElement),!t||t===this.selectedElement)return;this.unselectCurrentElement(),this.clearSelectedSiblingHighlighters(),this.selectedElement=t;let n=R(t),s=n.length>0;s&&this.highlightSelectedSiblings(t),t.hasAttribute("data-original-text")||t.setAttribute("data-original-text",encodeURIComponent(t.textContent??"")),!t.hasAttribute("data-original-style")&&t.hasAttribute("style")&&t.setAttribute("data-original-style",encodeURIComponent(t.getAttribute("style")??"")),!t.hasAttribute("data-original-src")&&t.hasAttribute("src")&&t.setAttribute("data-original-src",encodeURIComponent(t.getAttribute("src")??"")),!s&&this.enableEditing&&this.isPureTextElement(t)&&(this.selectedElement.setAttribute("contenteditable","plaintext-only"),this.selectedElement.focus()),this.selectedHighlighter&&this.selectedLabel&&(this.selectedHighlighter.style.outlineStyle="solid",this.selectedHighlighter.style.opacity="1",this.selectedHighlighter.style.pointerEvents="none",this.selectedLabel.style.opacity="1",this.selectedLabel.textContent=B(t)),this.hoverHighlighter&&(this.hoverHighlighter.style.opacity="0",this.hoverHighlighter.style.pointerEvents="none"),this.hoverLabel&&(this.hoverLabel.style.opacity="0"),this.clearHoverSiblingHighlighters(),this.updateHighlighterPosition(t,this.selectedHighlighter,this.selectedLabel);let r=K(t),l;if(!Ie(t))try{l=await xe(t)}catch(o){console.error("[replit-cartographer] Error capturing element screenshot:",o)}this.observeSelectedElement(),this.postMessageToParent({type:"ELEMENT_SELECTED",payload:{...r,screenshotBlob:l??void 0,siblingCount:s?n.length:0},timestamp:Date.now()})};restoreElements(){document.querySelectorAll('[data-replit-dirty="true"]').forEach(t=>{if(t.hasAttribute("data-original-text")){if(t.textContent!==decodeURIComponent(t.getAttribute("data-original-text")||"")){let n=decodeURIComponent(t.getAttribute("data-original-text")||"");t.textContent=n}t.removeAttribute("data-original-text")}if(t.hasAttribute("data-original-style")){let n=decodeURIComponent(t.getAttribute("data-original-style")||"");t.setAttribute("style",n),t.removeAttribute("data-original-style")}else t.removeAttribute("style");if(t.hasAttribute("data-original-src")&&t.getAttribute("src")!==decodeURIComponent(t.getAttribute("data-original-src")||"")){let n=decodeURIComponent(t.getAttribute("data-original-src")||"");t.setAttribute("src",n),t.removeAttribute("data-original-src")}t.removeAttribute("data-replit-dirty")})}unselectCurrentElement(){if(this.restoreElements(),this.selectedElement){if(this.selectedElement.removeAttribute("contenteditable"),this.selectedElement.hasAttribute("data-original-style")){let i=decodeURIComponent(this.selectedElement.getAttribute("data-original-style")||"");this.selectedElement.setAttribute("style",i),this.selectedElement.removeAttribute("data-original-style")}if(this.selectedElement.hasAttribute("data-original-src")&&this.selectedElement.getAttribute("src")!==decodeURIComponent(this.selectedElement.getAttribute("data-original-src")||"")){let i=decodeURIComponent(this.selectedElement.getAttribute("data-original-src")||"");this.selectedElement.setAttribute("src",i),this.selectedElement.removeAttribute("data-original-src")}this.selectedElement=null}this.clearSelectedSiblingHighlighters(),this.mutationObserver&&(this.mutationObserver.disconnect(),this.mutationObserver=null)}handleMessage=i=>{if(!Le(i.origin))return;let t=i.data;if(!(!t||typeof t!="object"))switch(t.type){case"TOGGLE_REPLIT_VISUAL_EDITOR":{this.handleVisualEditorToggle(t);break}case"CLEAR_SELECTION":{this.unselectCurrentElement(),this.hideHighlight(this.selectedHighlighter,this.selectedLabel);break}case"UPDATE_SELECTED_ELEMENT":{if(!this.selectedElement)return;let{attributes:n}=t;[this.selectedElement,...this.selectedSiblingElements].forEach(r=>{n.style!==void 0&&(r.setAttribute("style",n.style),r.setAttribute("data-replit-dirty","true")),n.textContent!==void 0&&(r.textContent=n.textContent,r.setAttribute("data-replit-dirty","true")),n.className!==void 0&&(r.className=n.className,r.setAttribute("data-replit-dirty","true")),n.src!==void 0&&(r.setAttribute("src",n.src),r.setAttribute("data-replit-dirty","true"))}),this.updateHighlighterPosition(this.selectedElement,this.selectedHighlighter,this.selectedLabel),this.selectedSiblingElements.length>0&&(this.clearHighlighters(this.selectedSiblingHighlighters),this.selectedSiblingHighlighters=[],this.selectedSiblingHighlighters=this.highlightElements(this.selectedSiblingElements));break}case"CLEAR_ELEMENT_DIRTY":{this.selectedElement&&this.selectedElement.removeAttribute("data-replit-dirty");break}case"APPLY_THEME_PREVIEW":{this.handleApplyThemePreview(t);break}case"CLEAR_THEME_PREVIEW":{this.handleClearThemePreview();break}}};handleApplyThemePreview(i){if(i.type!=="APPLY_THEME_PREVIEW")return;let t=document.getElementById(v.THEME_PREVIEW_STYLE_ID);t||(t=document.createElement("style"),t.id=v.THEME_PREVIEW_STYLE_ID,document.head.appendChild(t)),t.textContent=i.themeContent}handleClearThemePreview(){let i=document.getElementById(v.THEME_PREVIEW_STYLE_ID);i&&i.remove()}handleVisualEditorToggle(i){if(i.type!=="TOGGLE_REPLIT_VISUAL_EDITOR")return;let t=!!i.enabled;this.enableEditing=!!i.enableEditing,t?this.postMessageToParent({type:"REPLIT_VISUAL_EDITOR_ENABLED",timestamp:Date.now()}):this.postMessageToParent({type:"REPLIT_VISUAL_EDITOR_DISABLED",timestamp:Date.now()}),this.isActive!==t&&(this.isActive=t,this.toggleEventListeners(t))}observeSelectedElement(){if(this.selectedElement){if(!this.isPureTextElement(this.selectedElement)){this.mutationObserver&&(this.mutationObserver.disconnect(),this.mutationObserver=null);return}this.mutationObserver&&this.mutationObserver.disconnect(),this.mutationObserver=new MutationObserver(i=>{if(i.some(n=>n.type==="characterData")&&this.selectedElement){this.selectedElement.setAttribute("data-replit-dirty","true");let n=K(this.selectedElement);this.postMessageToParent({type:"ELEMENT_TEXT_CHANGED",payload:n,timestamp:Date.now()}),this.updateHighlighterPosition(this.selectedElement,this.selectedHighlighter,this.selectedLabel)}}),this.mutationObserver.observe(this.selectedElement,{characterData:!0,childList:!1,attributes:!1,subtree:!0})}}observeLightDarkModeSwitch(){let i=new MutationObserver(n=>{n.forEach(s=>{s.type==="attributes"&&s.attributeName==="class"&&(s.target.classList.contains("dark")?this.postMessageToParent({type:"DARK_MODE_USED",timestamp:Date.now()}):this.postMessageToParent({type:"LIGHT_MODE_USED",timestamp:Date.now()}))})}),t=document.documentElement;i.observe(t,{attributes:!0,attributeFilter:["class"],childList:!1,subtree:!1})}recalculateSelectedElement=()=>{this.isActive&&(this.selectedElement&&this.updateHighlighterPosition(this.selectedElement,this.selectedHighlighter,this.selectedLabel),this.lastHighlightedElement&&this.updateHighlighterPosition(this.lastHighlightedElement,this.hoverHighlighter,this.hoverLabel),this.selectedSiblingElements.length>0&&this.updateSiblingHighlighterPositions())};updateSiblingHighlighterPositions(){for(let i=0;i<this.selectedSiblingHighlighters.length;i++){let t=this.selectedSiblingHighlighters[i],n=this.visibleSelectedSiblingElements[i];if(!t||!n)continue;let s=n.getBoundingClientRect(),r=window.innerHeight,l=Math.max(0,s.top),o=Math.min(r,s.bottom),c=Math.max(0,o-l);Object.assign(t.style,{opacity:c>0?"1":"0",top:`${l}px`,left:`${s.left}px`,width:`${s.width}px`,height:`${c}px`})}}handleKeyDown=i=>{this.isActive&&(i.key==="Escape"||i.key==="Esc")&&this.handleVisualEditorToggle({type:"TOGGLE_REPLIT_VISUAL_EDITOR",enabled:!1,timestamp:Date.now()})};toggleEventListeners(i){i?(this.initializeHighlighter(),this.enableDisabledElements(),document.addEventListener("mousemove",this.handleMouseMove),document.addEventListener("mouseleave",this.handleMouseLeave),document.addEventListener("click",this.handleClick,!0),document.addEventListener("keydown",this.handleKeyDown),this.throttledRecalculate&&(window.addEventListener("resize",this.throttledRecalculate),window.addEventListener("scroll",this.throttledRecalculate,!0))):(this.restoreDisabledElements(),this.restoreElements(),document.removeEventListener("mousemove",this.handleMouseMove),document.removeEventListener("click",this.handleClick,!0),document.removeEventListener("mouseleave",this.handleMouseLeave),document.removeEventListener("keydown",this.handleKeyDown),this.throttledRecalculate&&(window.removeEventListener("resize",this.throttledRecalculate),window.removeEventListener("scroll",this.throttledRecalculate,!0)),this.mutationObserver&&(this.mutationObserver.disconnect(),this.mutationObserver=null),this.selectedElement&&(this.selectedElement.removeAttribute("contenteditable"),this.selectedElement.removeAttribute("data-original-text"),document.querySelectorAll('[contenteditable="plaintext-only"]').forEach(t=>{t.removeAttribute("contenteditable")})),this.clearSelectedSiblingHighlighters(),this.clearHoverSiblingHighlighters(),this.hoverHighlighter?.remove(),this.hoverLabel?.remove(),this.selectedHighlighter?.remove(),this.selectedLabel?.remove(),this.shadowHost?.remove(),this.hoverHighlighter=null,this.hoverLabel=null,this.selectedHighlighter=null,this.selectedLabel=null,this.shadowHost=null,this.shadowRoot=null,this.selectedElement=null)}clearHighlighters(i){return i.forEach(t=>{t.remove()}),[]}clearHoverSiblingHighlighters(){this.hoverSiblingHighlighters=this.clearHighlighters(this.hoverSiblingHighlighters)}clearSelectedSiblingHighlighters(){this.selectedSiblingElements.forEach(i=>{i.removeAttribute("contenteditable")}),this.selectedSiblingElements=[],this.visibleSelectedSiblingElements=[],this.selectedSiblingHighlighters=this.clearHighlighters(this.selectedSiblingHighlighters)}highlightElements(i){if(!this.shadowRoot||i.length===0)return[];let t=[];return i.forEach(n=>{let s=document.createElement("div");s.className="beacon-highlighter beacon-sibling-highlighter",this.shadowRoot?.appendChild(s),t.push(s);let r=n.getBoundingClientRect(),l=window.innerHeight,o=Math.max(0,r.top),c=Math.min(l,r.bottom),h=Math.max(0,c-o);Object.assign(s.style,{opacity:h>0?"1":"0",top:`${o}px`,left:`${r.left}px`,width:`${r.width}px`,height:`${h}px`})}),t}highlightHoverSiblings(i){this.clearHoverSiblingHighlighters();let t=R(i,v.MAX_SIBLING_HIGHLIGHTERS,!0);this.hoverSiblingHighlighters=this.highlightElements(t)}highlightSelectedSiblings(i){this.clearSelectedSiblingHighlighters();let t=R(i),n=t.filter(s=>J(s));this.selectedSiblingElements=t,this.visibleSelectedSiblingElements=n,this.selectedSiblingHighlighters=this.highlightElements(n)}enableDisabledElements(){document.querySelectorAll("button[disabled], input[disabled]").forEach(i=>{i.removeAttribute("disabled"),i.setAttribute("data-replit-disabled","")})}restoreDisabledElements(){document.querySelectorAll("[data-replit-disabled]").forEach(i=>{i.removeAttribute("data-replit-disabled"),i.setAttribute("disabled","")})}};if(typeof window<"u")try{window.REPLIT_BEACON_VERSION||(window.REPLIT_BEACON_VERSION=P,new D)}catch(e){console.error("[replit-beacon] Failed to initialize:",e)}})();
</script>
    <script type="text/javascript" src="/@replit/vite-plugin-dev-banner/banner-script.js" id="replit-dev-banner"></script><style>
    #replit-dev-banner {
      position: fixed;
      top: 0;
      left: 0;
      right: 0;
      z-index: 9999;
      display: flex;
      align-items: center;
      padding: 8px 16px;
      background-color: #004182;
      color: white;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Fira Sans", "Droid Sans", "Helvetica Neue", sans-serif;
      font-size: 14px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.15);
      border-bottom: 1px solid rgba(255, 255, 255, 0.1);
      transition: opacity 0.2s ease-in-out;
    }
    
    .banner-text {
      flex-grow: 1;
    }
    
    .banner-link {
      color: white;
      font-weight: 500;
      text-decoration: underline;
    }
    
    .banner-link:hover {
      text-decoration: none;
    }
    
    .banner-close {
      flex-shrink: 0;
      display: flex;
      align-items: center;
      justify-content: center;
      width: 28px;
      height: 28px;
      border: none;
      background: transparent;
      cursor: pointer;
      padding: 0;
      color: rgba(255, 255, 255, 0.7);
      margin-left: 12px;
      transition: transform 0.1s ease-in-out, color 0.1s ease-in-out;
    }
    
    .banner-close:hover {
      transform: scale(1.05);
      color: white;
    }
    
    @media (max-width: 600px) {
      #replit-dev-banner {
        padding: 8px;
        font-size: 12px;
      }
      
      .banner-close {
        width: 24px;
        height: 24px;
        margin-left: 8px;
      }
    }
  </style>
  </head>
  <body>
    <div id="root"></div>
    <script type="module" src="/src/main.tsx?v=54Ws3qBy9qhGFkR8MHEN_"></script>
  <script src="https://replit-cdn.com/replit-pill/replit-pill.global.js" data-repl-id="de2278f6-1e98-42bc-b5d0-3e6f286c8edb"></script>
</body></html>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>📊 តារាងជំរឿនស្ថិតិសាលារៀនចំណេះទូទៅសាធារណៈ</h1>
            <p>ឆ្នាំសិក្សា ២០២៥-២០២៦ (បឋមសិក្សា)</p>
        </div>

        <div class="toolbar">
            <button class="btn btn-save" onclick="saveData()">
                💾 រក្សាទុក
            </button>
            <button class="btn btn-print" onclick="printData()">
                🖨️ ព្រីន
            </button>
            <div class="export-menu">
                <button class="btn btn-export" onclick="toggleExportMenu()">
                    📥 Export
                </button>
                <div id="exportDropdown" class="export-dropdown">
                    <div class="export-option" onclick="exportToExcel()">📗 Excel (XLSX)</div>
                    <div class="export-option" onclick="exportToCSV()">📄 CSV</div>
                    <div class="export-option" onclick="exportToJSON()">📋 JSON</div>
                </div>
            </div>
            <button class="btn btn-import" onclick="document.getElementById('importFile').click()">
                📤 Import
            </button>
            <input type="file" id="importFile" class="file-input" accept=".xlsx,.csv,.json" onchange="importData(event)">
            <button class="btn btn-clear" onclick="clearData()">
                🗑️ សម្អាត
            </button>
        </div>
<html lang="en"><head>
    <script type="module">
import { createHotContext } from "/@vite/client";
const hot = createHotContext("/__dummy__runtime-error-plugin");

function sendError(error) {
  if (!(error instanceof Error)) {
    error = new Error("(unknown runtime error)");
  }
  const serialized = {
    message: error.message,
    stack: error.stack,
  };
  hot.send("runtime-error-plugin:error", serialized);
}

window.addEventListener("error", (evt) => {
  sendError(evt.error);
});

window.addEventListener("unhandledrejection", (evt) => {
  sendError(evt.reason);
});
</script>

    <script type="module">import { injectIntoGlobalHook } from "/@react-refresh";
injectIntoGlobalHook(window);
window.$RefreshReg$ = () => {};
window.$RefreshSig$ = () => (type) => type;</script>

    <script type="module" src="/@vite/client"></script>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1">
    <link rel="icon" type="image/png" href="/favicon.png">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="">
    <link href="https://fonts.googleapis.com/css2?family=Architects+Daughter&amp;family=DM+Sans:ital,opsz,wght@0,9..40,100..1000;1,9..40,100..1000&amp;family=Fira+Code:wght@300..700&amp;family=Geist+Mono:wght@100..900&amp;family=Geist:wght@100..900&amp;family=IBM+Plex+Mono:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;1,100;1,200;1,300;1,400;1,500;1,600;1,700&amp;family=IBM+Plex+Sans:ital,wght@0,100..700;1,100..700&amp;family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&amp;family=JetBrains+Mono:ital,wght@0,100..800;1,100..800&amp;family=Libre+Baskerville:ital,wght@0,400;0,700;1,400&amp;family=Lora:ital,wght@0,400..700;1,400..700&amp;family=Merriweather:ital,opsz,wght@0,18..144,300..900;1,18..144,300..900&amp;family=Montserrat:ital,wght@0,100..900;1,100..900&amp;family=Open+Sans:ital,wght@0,300..800;1,300..800&amp;family=Outfit:wght@100..900&amp;family=Oxanium:wght@200..800&amp;family=Playfair+Display:ital,wght@0,400..900;1,400..900&amp;family=Plus+Jakarta+Sans:ital,wght@0,200..800;1,200..800&amp;family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&amp;family=Roboto+Mono:ital,wght@0,100..700;1,100..700&amp;family=Roboto:ital,wght@0,100..900;1,100..900&amp;family=Source+Code+Pro:ital,wght@0,200..900;1,200..900&amp;family=Source+Serif+4:ital,opsz,wght@0,8..60,200..900;1,8..60,200..900&amp;family=Space+Grotesk:wght@300..700&amp;family=Space+Mono:ital,wght@0,400;0,700;1,400;1,700&amp;display=swap" rel="stylesheet">
    <script type="module">"use strict";(()=>{var P="0.4.4";var v={HIGHLIGHT_COLOR:"#0079F2",HIGHLIGHT_BG:"#0079F210",ALLOWED_DOMAIN:".replit.dev",THEME_PREVIEW_STYLE_ID:"replit-theme-preview",MAX_SIBLING_HIGHLIGHTERS:1e3,MAX_DESCENDANTS_FOR_SCREENSHOT:1500},Z=`
  [contenteditable] {
    outline: none !important;
  }

  [contenteditable]:focus {
    outline: none !important;
  }
`,ee=`
  .beacon-highlighter {
    content: '';
    position: absolute;
    z-index: ${Number.MAX_SAFE_INTEGER-3};
    box-sizing: border-box;
    pointer-events: none;
    outline: 2px dashed ${v.HIGHLIGHT_COLOR} !important;
    outline-offset: 0 !important;
    margin: 0 !important;
    padding: 0 !important;
    transform: none !important;
    background: ${v.HIGHLIGHT_BG} !important;
    opacity: 0;
  }
  
  .beacon-hover-highlighter {
    position: fixed;
    z-index: ${Number.MAX_SAFE_INTEGER};
  }
  
  .beacon-selected-highlighter {
    position: fixed;
    pointer-events: none;
    outline: 2px solid ${v.HIGHLIGHT_COLOR} !important;
    outline-offset: 3px !important;
    background: none !important;
  }
  
  .beacon-label {
    position: absolute;
    background-color: ${v.HIGHLIGHT_COLOR};
    color: #FFFFFF;
    padding: 4px 8px;
    border-radius: 4px;
    font-size: 14px;
    font-family: monospace;
    line-height: 1;
    white-space: nowrap;
    box-shadow: 0 2px 4px rgba(0,0,0,0.2);
    transform: translateY(-100%);
    margin-top: -4px;
    left: 0;
    z-index: ${Number.MAX_SAFE_INTEGER-2};
    pointer-events: none;
    opacity: 0;
  }
  
  .beacon-hover-label {
    position: fixed;
    z-index: ${Number.MAX_SAFE_INTEGER};
  }
  
  .beacon-selected-label {
    position: fixed;
    pointer-events: none;
  }
  
  .beacon-sibling-highlighter {
    position: fixed;
    pointer-events: none;
    outline: 2px dashed ${v.HIGHLIGHT_COLOR} !important;
    outline-offset: 0 !important;
    margin: 0 !important;
    padding: 0 !important;
    transform: none !important;
    background: ${v.HIGHLIGHT_BG} !important;
  }
`;function Me(e,i){return e[13]=1,e[14]=i>>8,e[15]=i&255,e[16]=i>>8,e[17]=i&255,e}var le=112,ae=72,ce=89,he=115,G;function Re(){let e=new Int32Array(256);for(let i=0;i<256;i++){let t=i;for(let n=0;n<8;n++)t=t&1?3988292384^t>>>1:t>>>1;e[i]=t}return e}function De(e){let i=-1;G||(G=Re());for(let t=0;t<e.length;t++)i=G[(i^e[t])&255]^i>>>8;return i^-1}function Oe(e){let i=e.length-1;for(let t=i;t>=4;t--)if(e[t-4]===9&&e[t-3]===le&&e[t-2]===ae&&e[t-1]===ce&&e[t]===he)return t-3;return 0}function Pe(e,i,t=!1){let n=new Uint8Array(13);i*=39.3701,n[0]=le,n[1]=ae,n[2]=ce,n[3]=he,n[4]=i>>>24,n[5]=i>>>16,n[6]=i>>>8,n[7]=i&255,n[8]=n[4],n[9]=n[5],n[10]=n[6],n[11]=n[7],n[12]=1;let s=De(n),r=new Uint8Array(4);if(r[0]=s>>>24,r[1]=s>>>16,r[2]=s>>>8,r[3]=s&255,t){let l=Oe(e);return e.set(n,l),e.set(r,l+13),e}else{let l=new Uint8Array(4);l[0]=0,l[1]=0,l[2]=0,l[3]=9;let o=new Uint8Array(54);return o.set(e,0),o.set(l,33),o.set(n,37),o.set(r,50),o}}var de="[modern-screenshot]",H=typeof window<"u",Fe=H&&"Worker"in window,ke=H&&"atob"in window,Yt=H&&"btoa"in window,V=H?window.navigator?.userAgent:"",ue=V.includes("Chrome"),F=V.includes("AppleWebKit")&&!ue,j=V.includes("Firefox"),Ue=e=>e&&"__CONTEXT__"in e,$e=e=>e.constructor.name==="CSSFontFaceRule",Be=e=>e.constructor.name==="CSSImportRule",S=e=>e.nodeType===1,N=e=>typeof e.className=="object",ge=e=>e.tagName==="image",Ge=e=>e.tagName==="use",x=e=>S(e)&&typeof e.style<"u"&&!N(e),We=e=>e.nodeType===8,Ve=e=>e.nodeType===3,L=e=>e.tagName==="IMG",k=e=>e.tagName==="VIDEO",je=e=>e.tagName==="CANVAS",qe=e=>e.tagName==="TEXTAREA",ze=e=>e.tagName==="INPUT",Xe=e=>e.tagName==="STYLE",Ye=e=>e.tagName==="SCRIPT",Ke=e=>e.tagName==="SELECT",Je=e=>e.tagName==="SLOT",Qe=e=>e.tagName==="IFRAME",Ze=(...e)=>console.warn(de,...e);function et(e){let i=e?.createElement?.("canvas");return i&&(i.height=i.width=1),!!i&&"toDataURL"in i&&!!i.toDataURL("image/webp").includes("image/webp")}var W=e=>e.startsWith("data:");function me(e,i){if(e.match(/^[a-z]+:\/\//i))return e;if(H&&e.match(/^\/\//))return window.location.protocol+e;if(e.match(/^[a-z]+:/i)||!H)return e;let t=U().implementation.createHTMLDocument(),n=t.createElement("base"),s=t.createElement("a");return t.head.appendChild(n),t.body.appendChild(s),i&&(n.href=i),s.href=e,s.href}function U(e){return(e&&S(e)?e?.ownerDocument:e)??window.document}var $="http://www.w3.org/2000/svg";function tt(e,i,t){let n=U(t).createElementNS($,"svg");return n.setAttributeNS(null,"width",e.toString()),n.setAttributeNS(null,"height",i.toString()),n.setAttributeNS(null,"viewBox",`0 0 ${e} ${i}`),n}function it(e,i){let t=new XMLSerializer().serializeToString(e);return i&&(t=t.replace(/[\u0000-\u0008\v\f\u000E-\u001F\uD800-\uDFFF\uFFFE\uFFFF]/gu,"")),`data:image/svg+xml;charset=utf-8,${encodeURIComponent(t)}`}async function nt(e,i="image/png",t=1){try{return await new Promise((n,s)=>{e.toBlob(r=>{r?n(r):s(new Error("Blob is null"))},i,t)})}catch(n){if(ke)return rt(e.toDataURL(i,t));throw n}}function rt(e){let[i,t]=e.split(","),n=i.match(/data:(.+);/)?.[1]??void 0,s=window.atob(t),r=s.length,l=new Uint8Array(r);for(let o=0;o<r;o+=1)l[o]=s.charCodeAt(o);return new Blob([l],{type:n})}function fe(e,i){return new Promise((t,n)=>{let s=new FileReader;s.onload=()=>t(s.result),s.onerror=()=>n(s.error),s.onabort=()=>n(new Error(`Failed read blob to ${i}`)),i==="dataUrl"?s.readAsDataURL(e):i==="arrayBuffer"&&s.readAsArrayBuffer(e)})}var st=e=>fe(e,"dataUrl"),ot=e=>fe(e,"arrayBuffer");function C(e,i){let t=U(i).createElement("img");return t.decoding="sync",t.loading="eager",t.src=e,t}function _(e,i){return new Promise(t=>{let{timeout:n,ownerDocument:s,onError:r,onWarn:l}=i??{},o=typeof e=="string"?C(e,U(s)):e,c=null,h=null;function a(){t(o),c&&clearTimeout(c),h?.()}if(n&&(c=setTimeout(a,n)),k(o)){let d=o.currentSrc||o.src;if(!d)return o.poster?_(o.poster,i).then(t):a();if(o.readyState>=2)return a();let u=a,m=g=>{l?.("Failed video load",d,g),r?.(g),a()};h=()=>{o.removeEventListener("loadeddata",u),o.removeEventListener("error",m)},o.addEventListener("loadeddata",u,{once:!0}),o.addEventListener("error",m,{once:!0})}else{let d=ge(o)?o.href.baseVal:o.currentSrc||o.src;if(!d)return a();let u=async()=>{if(L(o)&&"decode"in o)try{await o.decode()}catch(g){l?.("Failed to decode image, trying to render anyway",o.dataset.originalSrc||d,g)}a()},m=g=>{l?.("Failed image load",o.dataset.originalSrc||d,g),a()};if(L(o)&&o.complete)return u();h=()=>{o.removeEventListener("load",u),o.removeEventListener("error",m)},o.addEventListener("load",u,{once:!0}),o.addEventListener("error",m,{once:!0})}})}async function lt(e,i){x(e)&&(L(e)||k(e)?await _(e,i):await Promise.all(["img","video"].flatMap(t=>Array.from(e.querySelectorAll(t)).map(n=>_(n,i)))))}var pe=function(){let i=0,t=()=>`0000${(Math.random()*36**4<<0).toString(36)}`.slice(-4);return()=>(i+=1,`u${t()}${i}`)}();function be(e){return e?.split(",").map(i=>i.trim().replace(/"|'/g,"").toLowerCase()).filter(Boolean)}var te=0;function at(e){let i=`${de}[#${te}]`;return te++,{time:t=>e&&console.time(`${i} ${t}`),timeEnd:t=>e&&console.timeEnd(`${i} ${t}`),warn:(...t)=>e&&Ze(...t)}}function ct(e){return{cache:e?"no-cache":"force-cache"}}async function q(e,i){return Ue(e)?e:ht(e,{...i,autoDestruct:!0})}async function ht(e,i){let{scale:t=1,workerUrl:n,workerNumber:s=1}=i||{},r=!!i?.debug,l=i?.features??!0,o=e.ownerDocument??(H?window.document:void 0),c=e.ownerDocument?.defaultView??(H?window:void 0),h=new Map,a={width:0,height:0,quality:1,type:"image/png",scale:t,backgroundColor:null,style:null,filter:null,maximumCanvasSize:0,timeout:3e4,progress:null,debug:r,fetch:{requestInit:ct(i?.fetch?.bypassingCache),placeholderImage:"data:image/png;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7",bypassingCache:!1,...i?.fetch},fetchFn:null,font:{},drawImageInterval:100,workerUrl:null,workerNumber:s,onCloneNode:null,onEmbedNode:null,onCreateForeignObjectSvg:null,includeStyleProperties:null,autoDestruct:!1,...i,__CONTEXT__:!0,log:at(r),node:e,ownerDocument:o,ownerWindow:c,dpi:t===1?null:96*t,svgStyleElement:Ee(o),svgDefsElement:o?.createElementNS($,"defs"),svgStyles:new Map,defaultComputedStyles:new Map,workers:[...Array.from({length:Fe&&n&&s?s:0})].map(()=>{try{let m=new Worker(n);return m.onmessage=async g=>{let{url:f,result:p}=g.data;p?h.get(f)?.resolve?.(p):h.get(f)?.reject?.(new Error(`Error receiving message from worker: ${f}`))},m.onmessageerror=g=>{let{url:f}=g.data;h.get(f)?.reject?.(new Error(`Error receiving message from worker: ${f}`))},m}catch(m){return a.log.warn("Failed to new Worker",m),null}}).filter(Boolean),fontFamilies:new Map,fontCssTexts:new Map,acceptOfImage:`${[et(o)&&"image/webp","image/svg+xml","image/*","*/*"].filter(Boolean).join(",")};q=0.8`,requests:h,drawImageCount:0,tasks:[],features:l,isEnable:m=>m==="restoreScrollPosition"?typeof l=="boolean"?!1:l[m]??!1:typeof l=="boolean"?l:l[m]??!0};a.log.time("wait until load"),await lt(e,{timeout:a.timeout,onWarn:a.log.warn}),a.log.timeEnd("wait until load");let{width:d,height:u}=dt(e,a);return a.width=d,a.height=u,a}function Ee(e){if(!e)return;let i=e.createElement("style"),t=i.ownerDocument.createTextNode(`
.______background-clip--text {
  background-clip: text;
  -webkit-background-clip: text;
}
`);return i.appendChild(t),i}function dt(e,i){let{width:t,height:n}=i;if(S(e)&&(!t||!n)){let s=e.getBoundingClientRect();t=t||s.width||Number(e.getAttribute("width"))||0,n=n||s.height||Number(e.getAttribute("height"))||0}return{width:t,height:n}}async function ut(e,i){let{log:t,timeout:n,drawImageCount:s,drawImageInterval:r}=i;t.time("image to canvas");let l=await _(e,{timeout:n,onWarn:i.log.warn}),{canvas:o,context2d:c}=gt(e.ownerDocument,i),h=()=>{try{c?.drawImage(l,0,0,o.width,o.height)}catch(a){i.log.warn("Failed to drawImage",a)}};if(h(),i.isEnable("fixSvgXmlDecode"))for(let a=0;a<s;a++)await new Promise(d=>{setTimeout(()=>{h(),d()},a+r)});return i.drawImageCount=0,t.timeEnd("image to canvas"),o}function gt(e,i){let{width:t,height:n,scale:s,backgroundColor:r,maximumCanvasSize:l}=i,o=e.createElement("canvas");o.width=Math.floor(t*s),o.height=Math.floor(n*s),o.style.width=`${t}px`,o.style.height=`${n}px`,l&&(o.width>l||o.height>l)&&(o.width>l&&o.height>l?o.width>o.height?(o.height*=l/o.width,o.width=l):(o.width*=l/o.height,o.height=l):o.width>l?(o.height*=l/o.width,o.width=l):(o.width*=l/o.height,o.height=l));let c=o.getContext("2d");return c&&r&&(c.fillStyle=r,c.fillRect(0,0,o.width,o.height)),{canvas:o,context2d:c}}function ve(e,i){if(e.ownerDocument)try{let r=e.toDataURL();if(r!=="data:,")return C(r,e.ownerDocument)}catch(r){i.log.warn("Failed to clone canvas",r)}let t=e.cloneNode(!1),n=e.getContext("2d"),s=t.getContext("2d");try{return n&&s&&s.putImageData(n.getImageData(0,0,e.width,e.height),0,0),t}catch(r){i.log.warn("Failed to clone canvas",r)}return t}function mt(e,i){try{if(e?.contentDocument?.body)return z(e.contentDocument.body,i)}catch(t){i.log.warn("Failed to clone iframe",t)}return e.cloneNode(!1)}function ft(e){let i=e.cloneNode(!1);return e.currentSrc&&e.currentSrc!==e.src&&(i.src=e.currentSrc,i.srcset=""),i.loading==="lazy"&&(i.loading="eager"),i}async function pt(e,i){if(e.ownerDocument&&!e.currentSrc&&e.poster)return C(e.poster,e.ownerDocument);let t=e.cloneNode(!1);t.crossOrigin="anonymous",e.currentSrc&&e.currentSrc!==e.src&&(t.src=e.currentSrc);let n=t.ownerDocument;if(n){let s=!0;if(await _(t,{onError:()=>s=!1,onWarn:i.log.warn}),!s)return e.poster?C(e.poster,e.ownerDocument):t;t.currentTime=e.currentTime,await new Promise(l=>{t.addEventListener("seeked",l,{once:!0})});let r=n.createElement("canvas");r.width=e.offsetWidth,r.height=e.offsetHeight;try{let l=r.getContext("2d");l&&l.drawImage(t,0,0,r.width,r.height)}catch(l){return i.log.warn("Failed to clone video",l),e.poster?C(e.poster,e.ownerDocument):t}return ve(r,i)}return t}function bt(e,i){return je(e)?ve(e,i):Qe(e)?mt(e,i):L(e)?ft(e):k(e)?pt(e,i):e.cloneNode(!1)}function Et(e){let i=e.sandbox;if(!i){let{ownerDocument:t}=e;try{t&&(i=t.createElement("iframe"),i.id=`__SANDBOX__-${pe()}`,i.width="0",i.height="0",i.style.visibility="hidden",i.style.position="fixed",t.body.appendChild(i),i.contentWindow?.document.write('<!DOCTYPE html><meta charset="UTF-8"><title></title><body>'),e.sandbox=i)}catch(n){e.log.warn("Failed to getSandBox",n)}}return i}var vt=["width","height","-webkit-text-fill-color"],wt=["stroke","fill"];function we(e,i,t){let{defaultComputedStyles:n}=t,s=e.nodeName.toLowerCase(),r=N(e)&&s!=="svg",l=r?wt.map(f=>[f,e.getAttribute(f)]).filter(([,f])=>f!==null):[],o=[r&&"svg",s,l.map((f,p)=>`${f}=${p}`).join(","),i].filter(Boolean).join(":");if(n.has(o))return n.get(o);let h=Et(t)?.contentWindow;if(!h)return new Map;let a=h?.document,d,u;r?(d=a.createElementNS($,"svg"),u=d.ownerDocument.createElementNS(d.namespaceURI,s),l.forEach(([f,p])=>{u.setAttributeNS(null,f,p)}),d.appendChild(u)):d=u=a.createElement(s),u.textContent=" ",a.body.appendChild(d);let m=h.getComputedStyle(u,i),g=new Map;for(let f=m.length,p=0;p<f;p++){let b=m.item(p);vt.includes(b)||g.set(b,m.getPropertyValue(b))}return a.body.removeChild(d),n.set(o,g),g}function ye(e,i,t){let n=new Map,s=[],r=new Map;if(t)for(let o of t)l(o);else for(let o=e.length,c=0;c<o;c++){let h=e.item(c);l(h)}for(let o=s.length,c=0;c<o;c++)r.get(s[c])?.forEach((h,a)=>n.set(a,h));function l(o){let c=e.getPropertyValue(o),h=e.getPropertyPriority(o),a=o.lastIndexOf("-"),d=a>-1?o.substring(0,a):void 0;if(d){let u=r.get(d);u||(u=new Map,r.set(d,u)),u.set(o,[c,h])}i.get(o)===c&&!h||(d?s.push(d):n.set(o,[c,h]))}return n}function yt(e,i,t,n){let{ownerWindow:s,includeStyleProperties:r,currentParentNodeStyle:l}=n,o=i.style,c=s.getComputedStyle(e),h=we(e,null,n);l?.forEach((d,u)=>{h.delete(u)});let a=ye(c,h,r);a.delete("transition-property"),a.delete("all"),a.delete("d"),a.delete("content"),t&&(a.delete("margin-top"),a.delete("margin-right"),a.delete("margin-bottom"),a.delete("margin-left"),a.delete("margin-block-start"),a.delete("margin-block-end"),a.delete("margin-inline-start"),a.delete("margin-inline-end"),a.set("box-sizing",["border-box",""])),a.get("background-clip")?.[0]==="text"&&i.classList.add("______background-clip--text"),ue&&(a.has("font-kerning")||a.set("font-kerning",["normal",""]),(a.get("overflow-x")?.[0]==="hidden"||a.get("overflow-y")?.[0]==="hidden")&&a.get("text-overflow")?.[0]==="ellipsis"&&e.scrollWidth===e.clientWidth&&a.set("text-overflow",["clip",""]));for(let d=o.length,u=0;u<d;u++)o.removeProperty(o.item(u));return a.forEach(([d,u],m)=>{o.setProperty(m,d,u)}),a}function St(e,i){(qe(e)||ze(e)||Ke(e))&&i.setAttribute("value",e.value)}var Tt=[":before",":after"],At=[":-webkit-scrollbar",":-webkit-scrollbar-button",":-webkit-scrollbar-thumb",":-webkit-scrollbar-track",":-webkit-scrollbar-track-piece",":-webkit-scrollbar-corner",":-webkit-resizer"];function Ht(e,i,t,n,s){let{ownerWindow:r,svgStyleElement:l,svgStyles:o,currentNodeStyle:c}=n;if(!l||!r)return;function h(a){let d=r.getComputedStyle(e,a),u=d.getPropertyValue("content");if(!u||u==="none")return;s?.(u),u=u.replace(/(')|(")|(counter\(.+\))/g,"");let m=[pe()],g=we(e,a,n);c?.forEach((E,y)=>{g.delete(y)});let f=ye(d,g,n.includeStyleProperties);f.delete("content"),f.delete("-webkit-locale"),f.get("background-clip")?.[0]==="text"&&i.classList.add("______background-clip--text");let p=[`content: '${u}';`];if(f.forEach(([E,y],A)=>{p.push(`${A}: ${E}${y?" !important":""};`)}),p.length===1)return;try{i.className=[i.className,...m].join(" ")}catch(E){n.log.warn("Failed to copyPseudoClass",E);return}let b=p.join(`
  `),w=o.get(b);w||(w=[],o.set(b,w)),w.push(`.${m[0]}:${a}`)}Tt.forEach(h),t&&At.forEach(h)}var ie=new Set(["symbol"]);async function ne(e,i,t,n,s){if(S(t)&&(Xe(t)||Ye(t))||n.filter&&!n.filter(t))return;ie.has(i.nodeName)||ie.has(t.nodeName)?n.currentParentNodeStyle=void 0:n.currentParentNodeStyle=n.currentNodeStyle;let r=await z(t,n,!1,s);n.isEnable("restoreScrollPosition")&&Ct(e,r),i.appendChild(r)}async function re(e,i,t,n){let s=(S(e)?e.shadowRoot?.firstChild:void 0)??e.firstChild;for(let r=s;r;r=r.nextSibling)if(!We(r))if(S(r)&&Je(r)&&typeof r.assignedNodes=="function"){let l=r.assignedNodes();for(let o=0;o<l.length;o++)await ne(e,i,l[o],t,n)}else await ne(e,i,r,t,n)}function Ct(e,i){if(!x(e)||!x(i))return;let{scrollTop:t,scrollLeft:n}=e;if(!t&&!n)return;let{transform:s}=i.style,r=new DOMMatrix(s),{a:l,b:o,c,d:h}=r;r.a=1,r.b=0,r.c=0,r.d=1,r.translateSelf(-n,-t),r.a=l,r.b=o,r.c=c,r.d=h,i.style.transform=r.toString()}function Lt(e,i){let{backgroundColor:t,width:n,height:s,style:r}=i,l=e.style;if(t&&l.setProperty("background-color",t,"important"),n&&l.setProperty("width",`${n}px`,"important"),s&&l.setProperty("height",`${s}px`,"important"),r)for(let o in r)l[o]=r[o]}var xt=/^[\w-:]+$/;async function z(e,i,t=!1,n){let{ownerDocument:s,ownerWindow:r,fontFamilies:l}=i;if(s&&Ve(e))return n&&/\S/.test(e.data)&&n(e.data),s.createTextNode(e.data);if(s&&r&&S(e)&&(x(e)||N(e))){let c=await bt(e,i);if(i.isEnable("removeAbnormalAttributes")){let g=c.getAttributeNames();for(let f=g.length,p=0;p<f;p++){let b=g[p];xt.test(b)||c.removeAttribute(b)}}let h=i.currentNodeStyle=yt(e,c,t,i);t&&Lt(c,i);let a=!1;if(i.isEnable("copyScrollbar")){let g=[h.get("overflow-x")?.[0],h.get("overflow-y")?.[0]];a=g.includes("scroll")||(g.includes("auto")||g.includes("overlay"))&&(e.scrollHeight>e.clientHeight||e.scrollWidth>e.clientWidth)}let d=h.get("text-transform")?.[0],u=be(h.get("font-family")?.[0]),m=u?g=>{d==="uppercase"?g=g.toUpperCase():d==="lowercase"?g=g.toLowerCase():d==="capitalize"&&(g=g[0].toUpperCase()+g.substring(1)),u.forEach(f=>{let p=l.get(f);p||l.set(f,p=new Set),g.split("").forEach(b=>p.add(b))})}:void 0;return Ht(e,c,a,i,m),St(e,c),k(e)||await re(e,c,i,m),c}let o=e.cloneNode(!1);return await re(e,o,i),o}function _t(e){if(e.ownerDocument=void 0,e.ownerWindow=void 0,e.svgStyleElement=void 0,e.svgDefsElement=void 0,e.svgStyles.clear(),e.defaultComputedStyles.clear(),e.sandbox){try{e.sandbox.remove()}catch(i){e.log.warn("Failed to destroyContext",i)}e.sandbox=void 0}e.workers=[],e.fontFamilies.clear(),e.fontCssTexts.clear(),e.requests.clear(),e.tasks=[]}function It(e){let{url:i,timeout:t,responseType:n,...s}=e,r=new AbortController,l=t?setTimeout(()=>r.abort(),t):void 0;return fetch(i,{signal:r.signal,...s}).then(o=>{if(!o.ok)throw new Error("Failed fetch, not 2xx response",{cause:o});switch(n){case"arrayBuffer":return o.arrayBuffer();case"dataUrl":return o.blob().then(st);case"text":default:return o.text()}}).finally(()=>clearTimeout(l))}function I(e,i){let{url:t,requestType:n="text",responseType:s="text",imageDom:r}=i,l=t,{timeout:o,acceptOfImage:c,requests:h,fetchFn:a,fetch:{requestInit:d,bypassingCache:u,placeholderImage:m},font:g,workers:f,fontFamilies:p}=e;n==="image"&&(F||j)&&e.drawImageCount++;let b=h.get(t);if(!b){u&&u instanceof RegExp&&u.test(l)&&(l+=(/\?/.test(l)?"&":"?")+new Date().getTime());let w=n.startsWith("font")&&g&&g.minify,E=new Set;w&&n.split(";")[1].split(",").forEach(O=>{p.has(O)&&p.get(O).forEach(Q=>E.add(Q))});let y=w&&E.size,A={url:l,timeout:o,responseType:y?"arrayBuffer":s,headers:n==="image"?{accept:c}:void 0,...d};b={type:n,resolve:void 0,reject:void 0,response:null},b.response=(async()=>{if(a&&n==="image"){let T=await a(t);if(T)return T}return!F&&t.startsWith("http")&&f.length?new Promise((T,O)=>{f[h.size&f.length-1].postMessage({rawUrl:t,...A}),b.resolve=T,b.reject=O}):It(A)})().catch(T=>{if(h.delete(t),n==="image"&&m)return e.log.warn("Failed to fetch image base64, trying to use placeholder image",l),typeof m=="string"?m:m(r);throw T}),h.set(t,b)}return b.response}async function Se(e,i,t,n){if(!Te(e))return e;for(let[s,r]of Nt(e,i))try{let l=await I(t,{url:r,requestType:n?"image":"text",responseType:"dataUrl"});e=e.replace(Mt(s),`$1${l}$3`)}catch(l){t.log.warn("Failed to fetch css data url",s,l)}return e}function Te(e){return/url\((['"]?)([^'"]+?)\1\)/.test(e)}var Ae=/url\((['"]?)([^'"]+?)\1\)/g;function Nt(e,i){let t=[];return e.replace(Ae,(n,s,r)=>(t.push([r,me(r,i)]),n)),t.filter(([n])=>!W(n))}function Mt(e){let i=e.replace(/([.*+?^${}()|\[\]\/\\])/g,"\\$1");return new RegExp(`(url\\(['"]?)(${i})(['"]?\\))`,"g")}var Rt=["background-image","border-image-source","-webkit-border-image","-webkit-mask-image","list-style-image"];function Dt(e,i){return Rt.map(t=>{let n=e.getPropertyValue(t);return!n||n==="none"?null:((F||j)&&i.drawImageCount++,Se(n,null,i,!0).then(s=>{!s||n===s||e.setProperty(t,s,e.getPropertyPriority(t))}))}).filter(Boolean)}function Ot(e,i){if(L(e)){let t=e.currentSrc||e.src;if(!W(t))return[I(i,{url:t,imageDom:e,requestType:"image",responseType:"dataUrl"}).then(n=>{n&&(e.srcset="",e.dataset.originalSrc=t,e.src=n||"")})];(F||j)&&i.drawImageCount++}else if(N(e)&&!W(e.href.baseVal)){let t=e.href.baseVal;return[I(i,{url:t,imageDom:e,requestType:"image",responseType:"dataUrl"}).then(n=>{n&&(e.dataset.originalSrc=t,e.href.baseVal=n||"")})]}return[]}function Pt(e,i){let{ownerDocument:t,svgDefsElement:n}=i,s=e.getAttribute("href")??e.getAttribute("xlink:href");if(!s)return[];let[r,l]=s.split("#");if(l){let o=`#${l}`,c=t?.querySelector(`svg ${o}`);if(r&&e.setAttribute("href",o),n?.querySelector(o))return[];if(c)return n?.appendChild(c.cloneNode(!0)),[];if(r)return[I(i,{url:r,responseType:"text"}).then(h=>{n?.insertAdjacentHTML("beforeend",h)})]}return[]}function He(e,i){let{tasks:t}=i;S(e)&&((L(e)||ge(e))&&t.push(...Ot(e,i)),Ge(e)&&t.push(...Pt(e,i))),x(e)&&t.push(...Dt(e.style,i)),e.childNodes.forEach(n=>{He(n,i)})}async function Ft(e,i){let{ownerDocument:t,svgStyleElement:n,fontFamilies:s,fontCssTexts:r,tasks:l,font:o}=i;if(!(!t||!n||!s.size))if(o&&o.cssText){let c=oe(o.cssText,i);n.appendChild(t.createTextNode(`${c}
`))}else{let c=Array.from(t.styleSheets).filter(a=>{try{return"cssRules"in a&&!!a.cssRules.length}catch(d){return i.log.warn(`Error while reading CSS rules from ${a.href}`,d),!1}});await Promise.all(c.flatMap(a=>Array.from(a.cssRules).map(async(d,u)=>{if(Be(d)){let m=u+1,g=d.href,f="";try{f=await I(i,{url:g,requestType:"text",responseType:"text"})}catch(b){i.log.warn(`Error fetch remote css import from ${g}`,b)}let p=f.replace(Ae,(b,w,E)=>b.replace(E,me(E,g)));for(let b of Ut(p))try{a.insertRule(b,b.startsWith("@import")?m+=1:a.cssRules.length)}catch(w){i.log.warn("Error inserting rule from remote css import",{rule:b,error:w})}}}))),c.flatMap(a=>Array.from(a.cssRules)).filter(a=>$e(a)&&Te(a.style.getPropertyValue("src"))&&be(a.style.getPropertyValue("font-family"))?.some(d=>s.has(d))).forEach(a=>{let d=a,u=r.get(d.cssText);u?n.appendChild(t.createTextNode(`${u}
`)):l.push(Se(d.cssText,d.parentStyleSheet?d.parentStyleSheet.href:null,i).then(m=>{m=oe(m,i),r.set(d.cssText,m),n.appendChild(t.createTextNode(`${m}
`))}))})}}var kt=/(\/\*[\s\S]*?\*\/)/g,se=/((@.*?keyframes [\s\S]*?){([\s\S]*?}\s*?)})/gi;function Ut(e){if(e==null)return[];let i=[],t=e.replace(kt,"");for(;;){let r=se.exec(t);if(!r)break;i.push(r[0])}t=t.replace(se,"");let n=/@import[\s\S]*?url\([^)]*\)[\s\S]*?;/gi,s=new RegExp("((\\s*?(?:\\/\\*[\\s\\S]*?\\*\\/)?\\s*?@media[\\s\\S]*?){([\\s\\S]*?)}\\s*?})|(([\\s\\S]*?){([\\s\\S]*?)})","gi");for(;;){let r=n.exec(t);if(r)s.lastIndex=n.lastIndex;else if(r=s.exec(t),r)n.lastIndex=s.lastIndex;else break;i.push(r[0])}return i}var $t=/url\([^)]+\)\s*format\((["']?)([^"']+)\1\)/g,Bt=/src:\s*(?:url\([^)]+\)\s*format\([^)]+\)[,;]\s*)+/g;function oe(e,i){let{font:t}=i,n=t?t?.preferredFormat:void 0;return n?e.replace(Bt,s=>{for(;;){let[r,,l]=$t.exec(s)||[];if(!l)return"";if(l===n)return`src: ${r};`}}):e}async function Gt(e,i){let t=await q(e,i);if(S(t.node)&&N(t.node))return t.node;let{ownerDocument:n,log:s,tasks:r,svgStyleElement:l,svgDefsElement:o,svgStyles:c,font:h,progress:a,autoDestruct:d,onCloneNode:u,onEmbedNode:m,onCreateForeignObjectSvg:g}=t;s.time("clone node");let f=await z(t.node,t,!0);if(l&&n){let y="";c.forEach((A,T)=>{y+=`${A.join(`,
`)} {
  ${T}
}
`}),l.appendChild(n.createTextNode(y))}s.timeEnd("clone node"),await u?.(f),h!==!1&&S(f)&&(s.time("embed web font"),await Ft(f,t),s.timeEnd("embed web font")),s.time("embed node"),He(f,t);let p=r.length,b=0,w=async()=>{for(;;){let y=r.pop();if(!y)break;try{await y}catch(A){t.log.warn("Failed to run task",A)}a?.(++b,p)}};a?.(b,p),await Promise.all([...Array.from({length:4})].map(w)),s.timeEnd("embed node"),await m?.(f);let E=Wt(f,t);return o&&E.insertBefore(o,E.children[0]),l&&E.insertBefore(l,E.children[0]),d&&_t(t),await g?.(E),E}function Wt(e,i){let{width:t,height:n}=i,s=tt(t,n,e.ownerDocument),r=s.ownerDocument.createElementNS(s.namespaceURI,"foreignObject");return r.setAttributeNS(null,"x","0%"),r.setAttributeNS(null,"y","0%"),r.setAttributeNS(null,"width","100%"),r.setAttributeNS(null,"height","100%"),r.append(e),s.appendChild(r),s}async function Vt(e,i){let t=await q(e,i),n=await Gt(t),s=it(n,t.isEnable("removeControlCharacter"));t.autoDestruct||(t.svgStyleElement=Ee(t.ownerDocument),t.svgDefsElement=t.ownerDocument?.createElementNS($,"defs"),t.svgStyles.clear());let r=C(s,n.ownerDocument);return await ut(r,t)}async function Ce(e,i){let t=await q(e,i),{log:n,type:s,quality:r,dpi:l}=t,o=await Vt(t);n.time("canvas to blob");let c=await nt(o,s,r);if(["image/png","image/jpeg"].includes(s)&&l){let h=await ot(c.slice(0,33)),a=new Uint8Array(h);return s==="image/png"?a=Pe(a,l):s==="image/jpeg"&&(a=Me(a,l)),n.timeEnd("canvas to blob"),new Blob([a,c.slice(33)],{type:s})}return n.timeEnd("canvas to blob"),c}var M={METADATA:"data-replit-metadata",COMPONENT_NAME:"data-component-name"};function Le(e){if(e.startsWith("http://localhost:"))return!0;try{return new URL(e).hostname.endsWith(v.ALLOWED_DOMAIN)}catch{return!1}}function Y(e){if(!e)return null;let i=document.elementFromPoint(e.clientX,e.clientY);return i instanceof HTMLElement?i:null}function jt(e,i=300){if(!e)return"";let t=String(e);return t.length<=i?t:t.slice(0,i)+"..."}function X(e){if(e)return{tagName:e.tagName.toLowerCase(),className:e.className.toString?e.className.toString():String(e.className),textContent:e.textContent??"",id:e.id}}function B(e){let i=e.getAttribute(M.COMPONENT_NAME)??e.tagName.toLowerCase();return jt(i,50)}function K(e){let i=window.getComputedStyle(e),t=e.parentElement,n=e.nextElementSibling,s=t?.parentElement??null,r={backgroundColor:i.backgroundColor,color:i.color,display:i.display,position:i.position,width:i.width,height:i.height,fontSize:i.fontSize,fontFamily:i.fontFamily,fontWeight:i.fontWeight,margin:i.margin,padding:i.padding,textAlign:i.textAlign};return{elementPath:e.getAttribute(M.METADATA)??"",elementName:B(e),textContent:e.textContent??"",originalTextContent:e.getAttribute("data-original-text")?decodeURIComponent(e.getAttribute("data-original-text")??""):void 0,srcAttribute:e.getAttribute("src")??"",hasChildElements:e.childElementCount>0,id:e.id,className:e.className.toString?e.className.toString():String(e.className),computedStyles:r,textAlign:i.textAlign,relatedElements:{parent:X(t),nextSibling:X(n),grandParent:X(s)}}}async function xe(e){try{let t=window.getComputedStyle(e).backgroundColor;return qt(t)&&(t=window.getComputedStyle(document.documentElement).backgroundColor),await Ce(e,{type:"image/png",backgroundColor:t})}catch(i){console.error("[replit-cartographer] Failed to take screenshot:",i);return}}function qt(e){return e==="transparent"||e==="rgba(0, 0, 0, 0)"||e.endsWith(", 0)")||e.endsWith(",0)")}function J(e){let i=e.getBoundingClientRect(),t=window.innerHeight,n=window.innerWidth;return i.bottom>0&&i.top<t&&i.right>0&&i.left<n}function R(e,i=v.MAX_SIBLING_HIGHLIGHTERS,t=!1){let r=e.getAttribute(M.METADATA);if(!r)return[];let l=`[${M.METADATA}="${r}"]`,o=document,c=e.parentElement;c&&c.childElementCount>50&&(o=c);let h=o.querySelectorAll(l),a=Math.min(i,5e3),d=[],u=0;for(let m=0;m<h.length&&u<a;m++){let g=h[m];if(g instanceof HTMLElement&&g!==e){if(t&&!J(g))continue;d.push(g),u++}}return d}function _e(e,i,t){let n=e.children;for(let s=0;s<n.length;s++)if(t.value+=1,t.value>i||_e(n[s],i,t))return!0;return!1}function Ie(e){let i={value:0};return _e(e,v.MAX_DESCENDANTS_FOR_SCREENSHOT,i)}var D=class{selectedElement=null;selectedSiblingElements=[];visibleSelectedSiblingElements=[];isActive=!1;lastHighlightedElement=null;enableEditing=!1;shadowHost=null;shadowRoot=null;hoverHighlighter=null;hoverLabel=null;selectedHighlighter=null;selectedLabel=null;hoverSiblingHighlighters=[];selectedSiblingHighlighters=[];mutationObserver=null;throttledRecalculate=null;constructor(){this.setupMessageListener(),this.observeLightDarkModeSwitch(),this.notifyScriptLoaded(),this.throttledRecalculate=this.throttleRAF(this.recalculateSelectedElement.bind(this))}throttleRAF(i){let t=null,n=null;return(...s)=>{n=s,t===null&&(t=requestAnimationFrame(()=>{n!==null&&i(...n),t=null,n=null}))}}isPureTextElement(i){if(!i||!(i instanceof HTMLElement))return!1;let t=i.tagName.toLowerCase();if(t==="style"||t==="script"||t==="img"||i.childElementCount>0)return!1;let n=i.getAttribute("style");return n&&n.trim()!==""?!1:Array.from(i.childNodes).every(r=>r.nodeType===Node.TEXT_NODE)}initializeHighlighter(){this.shadowHost=document.createElement("div"),this.shadowHost.style.all="initial",this.shadowRoot=this.shadowHost.attachShadow({mode:"open"}),document.body.appendChild(this.shadowHost);let i=document.createElement("style");i.textContent=ee,this.shadowRoot.appendChild(i);let t=document.createElement("style");t.textContent=Z,document.head.appendChild(t),this.hoverHighlighter=document.createElement("div"),this.hoverLabel=document.createElement("div"),this.hoverHighlighter.className="beacon-highlighter beacon-hover-highlighter",this.hoverLabel.className="beacon-label beacon-hover-label",this.selectedHighlighter=document.createElement("div"),this.selectedLabel=document.createElement("div"),this.selectedHighlighter.className="beacon-highlighter beacon-selected-highlighter",this.selectedLabel.className="beacon-label beacon-selected-label",this.shadowRoot.appendChild(this.selectedHighlighter),this.shadowRoot.appendChild(this.selectedLabel),this.shadowRoot.appendChild(this.hoverHighlighter),this.shadowRoot.appendChild(this.hoverLabel)}setupMessageListener(){window.addEventListener("message",this.handleMessage.bind(this))}notifyScriptLoaded(){this.postMessageToParent({type:"SELECTOR_SCRIPT_LOADED",timestamp:Date.now(),version:P})}postMessageToParent(i){window.parent&&window.parent.postMessage(i,"*")}handleMouseMove=i=>{if(this.isActive&&this.hoverHighlighter){let t=Y(i);if(!t||t===this.hoverHighlighter||t===this.selectedHighlighter||t===this.shadowHost||this.selectedSiblingHighlighters.includes(t)||this.hoverSiblingHighlighters.includes(t)){this.hideHighlight(this.hoverHighlighter,this.hoverLabel),this.lastHighlightedElement=null,this.clearHoverSiblingHighlighters();return}if(t===this.selectedElement){this.hideHighlight(this.hoverHighlighter,this.hoverLabel),this.lastHighlightedElement=null,this.clearHoverSiblingHighlighters();return}this.lastHighlightedElement&&this.lastHighlightedElement!==t&&this.lastHighlightedElement!==this.selectedElement&&this.lastHighlightedElement.removeAttribute("contenteditable"),this.lastHighlightedElement=t,this.updateHighlighterPosition(t,this.hoverHighlighter,this.hoverLabel)}};handleMouseLeave=()=>{this.isActive&&(this.hoverHighlighter&&(this.hoverHighlighter.style.opacity="0"),this.hoverLabel&&(this.hoverLabel.style.opacity="0"),this.hoverSiblingHighlighters.length>0&&this.clearHoverSiblingHighlighters(),this.lastHighlightedElement&&this.lastHighlightedElement!==this.selectedElement&&this.lastHighlightedElement.removeAttribute("contenteditable"))};calculateLabelPosition(i,t){return t<28?{top:`${t}px`,left:`${i.left}px`,transform:"none",marginTop:"2px"}:{top:`${t}px`,left:`${i.left}px`,transform:"translateY(-100%)",marginTop:"-4px"}}updateHighlighterPosition(i,t,n){if(!t||!n)return;let s=R(i,v.MAX_SIBLING_HIGHLIGHTERS,!1);this.enableEditing&&s.length<=1&&i===this.selectedElement&&this.isPureTextElement(i)&&i.setAttribute("contenteditable","plaintext-only");let r=i.getBoundingClientRect(),l=window.innerHeight,o=Math.max(0,r.top),c=Math.min(l,r.bottom),h=Math.max(0,c-o);Object.assign(t.style,{opacity:h>0?"1":"0",top:`${o}px`,left:`${r.left}px`,width:`${r.width}px`,height:`${h}px`}),n.textContent=B(i);let a=this.calculateLabelPosition(r,o);Object.assign(n.style,{...a,opacity:h>0?"1":"0"}),t===this.selectedHighlighter?this.highlightSelectedSiblings(i):this.highlightHoverSiblings(i)}hideHighlight(i,t){i&&(i.style.opacity="0"),t&&(t.style.opacity="0");let n=i===this.hoverHighlighter,s=i===this.selectedHighlighter;n&&this.clearHoverSiblingHighlighters(),s&&this.clearSelectedSiblingHighlighters()}handleClick=async i=>{if(!this.isActive)return;i.preventDefault(),i.stopPropagation();let t=Y(i);if((!t||t===this.hoverHighlighter||t===this.selectedHighlighter||t===this.shadowHost)&&(t=this.lastHighlightedElement),!t||t===this.selectedElement)return;this.unselectCurrentElement(),this.clearSelectedSiblingHighlighters(),this.selectedElement=t;let n=R(t),s=n.length>0;s&&this.highlightSelectedSiblings(t),t.hasAttribute("data-original-text")||t.setAttribute("data-original-text",encodeURIComponent(t.textContent??"")),!t.hasAttribute("data-original-style")&&t.hasAttribute("style")&&t.setAttribute("data-original-style",encodeURIComponent(t.getAttribute("style")??"")),!t.hasAttribute("data-original-src")&&t.hasAttribute("src")&&t.setAttribute("data-original-src",encodeURIComponent(t.getAttribute("src")??"")),!s&&this.enableEditing&&this.isPureTextElement(t)&&(this.selectedElement.setAttribute("contenteditable","plaintext-only"),this.selectedElement.focus()),this.selectedHighlighter&&this.selectedLabel&&(this.selectedHighlighter.style.outlineStyle="solid",this.selectedHighlighter.style.opacity="1",this.selectedHighlighter.style.pointerEvents="none",this.selectedLabel.style.opacity="1",this.selectedLabel.textContent=B(t)),this.hoverHighlighter&&(this.hoverHighlighter.style.opacity="0",this.hoverHighlighter.style.pointerEvents="none"),this.hoverLabel&&(this.hoverLabel.style.opacity="0"),this.clearHoverSiblingHighlighters(),this.updateHighlighterPosition(t,this.selectedHighlighter,this.selectedLabel);let r=K(t),l;if(!Ie(t))try{l=await xe(t)}catch(o){console.error("[replit-cartographer] Error capturing element screenshot:",o)}this.observeSelectedElement(),this.postMessageToParent({type:"ELEMENT_SELECTED",payload:{...r,screenshotBlob:l??void 0,siblingCount:s?n.length:0},timestamp:Date.now()})};restoreElements(){document.querySelectorAll('[data-replit-dirty="true"]').forEach(t=>{if(t.hasAttribute("data-original-text")){if(t.textContent!==decodeURIComponent(t.getAttribute("data-original-text")||"")){let n=decodeURIComponent(t.getAttribute("data-original-text")||"");t.textContent=n}t.removeAttribute("data-original-text")}if(t.hasAttribute("data-original-style")){let n=decodeURIComponent(t.getAttribute("data-original-style")||"");t.setAttribute("style",n),t.removeAttribute("data-original-style")}else t.removeAttribute("style");if(t.hasAttribute("data-original-src")&&t.getAttribute("src")!==decodeURIComponent(t.getAttribute("data-original-src")||"")){let n=decodeURIComponent(t.getAttribute("data-original-src")||"");t.setAttribute("src",n),t.removeAttribute("data-original-src")}t.removeAttribute("data-replit-dirty")})}unselectCurrentElement(){if(this.restoreElements(),this.selectedElement){if(this.selectedElement.removeAttribute("contenteditable"),this.selectedElement.hasAttribute("data-original-style")){let i=decodeURIComponent(this.selectedElement.getAttribute("data-original-style")||"");this.selectedElement.setAttribute("style",i),this.selectedElement.removeAttribute("data-original-style")}if(this.selectedElement.hasAttribute("data-original-src")&&this.selectedElement.getAttribute("src")!==decodeURIComponent(this.selectedElement.getAttribute("data-original-src")||"")){let i=decodeURIComponent(this.selectedElement.getAttribute("data-original-src")||"");this.selectedElement.setAttribute("src",i),this.selectedElement.removeAttribute("data-original-src")}this.selectedElement=null}this.clearSelectedSiblingHighlighters(),this.mutationObserver&&(this.mutationObserver.disconnect(),this.mutationObserver=null)}handleMessage=i=>{if(!Le(i.origin))return;let t=i.data;if(!(!t||typeof t!="object"))switch(t.type){case"TOGGLE_REPLIT_VISUAL_EDITOR":{this.handleVisualEditorToggle(t);break}case"CLEAR_SELECTION":{this.unselectCurrentElement(),this.hideHighlight(this.selectedHighlighter,this.selectedLabel);break}case"UPDATE_SELECTED_ELEMENT":{if(!this.selectedElement)return;let{attributes:n}=t;[this.selectedElement,...this.selectedSiblingElements].forEach(r=>{n.style!==void 0&&(r.setAttribute("style",n.style),r.setAttribute("data-replit-dirty","true")),n.textContent!==void 0&&(r.textContent=n.textContent,r.setAttribute("data-replit-dirty","true")),n.className!==void 0&&(r.className=n.className,r.setAttribute("data-replit-dirty","true")),n.src!==void 0&&(r.setAttribute("src",n.src),r.setAttribute("data-replit-dirty","true"))}),this.updateHighlighterPosition(this.selectedElement,this.selectedHighlighter,this.selectedLabel),this.selectedSiblingElements.length>0&&(this.clearHighlighters(this.selectedSiblingHighlighters),this.selectedSiblingHighlighters=[],this.selectedSiblingHighlighters=this.highlightElements(this.selectedSiblingElements));break}case"CLEAR_ELEMENT_DIRTY":{this.selectedElement&&this.selectedElement.removeAttribute("data-replit-dirty");break}case"APPLY_THEME_PREVIEW":{this.handleApplyThemePreview(t);break}case"CLEAR_THEME_PREVIEW":{this.handleClearThemePreview();break}}};handleApplyThemePreview(i){if(i.type!=="APPLY_THEME_PREVIEW")return;let t=document.getElementById(v.THEME_PREVIEW_STYLE_ID);t||(t=document.createElement("style"),t.id=v.THEME_PREVIEW_STYLE_ID,document.head.appendChild(t)),t.textContent=i.themeContent}handleClearThemePreview(){let i=document.getElementById(v.THEME_PREVIEW_STYLE_ID);i&&i.remove()}handleVisualEditorToggle(i){if(i.type!=="TOGGLE_REPLIT_VISUAL_EDITOR")return;let t=!!i.enabled;this.enableEditing=!!i.enableEditing,t?this.postMessageToParent({type:"REPLIT_VISUAL_EDITOR_ENABLED",timestamp:Date.now()}):this.postMessageToParent({type:"REPLIT_VISUAL_EDITOR_DISABLED",timestamp:Date.now()}),this.isActive!==t&&(this.isActive=t,this.toggleEventListeners(t))}observeSelectedElement(){if(this.selectedElement){if(!this.isPureTextElement(this.selectedElement)){this.mutationObserver&&(this.mutationObserver.disconnect(),this.mutationObserver=null);return}this.mutationObserver&&this.mutationObserver.disconnect(),this.mutationObserver=new MutationObserver(i=>{if(i.some(n=>n.type==="characterData")&&this.selectedElement){this.selectedElement.setAttribute("data-replit-dirty","true");let n=K(this.selectedElement);this.postMessageToParent({type:"ELEMENT_TEXT_CHANGED",payload:n,timestamp:Date.now()}),this.updateHighlighterPosition(this.selectedElement,this.selectedHighlighter,this.selectedLabel)}}),this.mutationObserver.observe(this.selectedElement,{characterData:!0,childList:!1,attributes:!1,subtree:!0})}}observeLightDarkModeSwitch(){let i=new MutationObserver(n=>{n.forEach(s=>{s.type==="attributes"&&s.attributeName==="class"&&(s.target.classList.contains("dark")?this.postMessageToParent({type:"DARK_MODE_USED",timestamp:Date.now()}):this.postMessageToParent({type:"LIGHT_MODE_USED",timestamp:Date.now()}))})}),t=document.documentElement;i.observe(t,{attributes:!0,attributeFilter:["class"],childList:!1,subtree:!1})}recalculateSelectedElement=()=>{this.isActive&&(this.selectedElement&&this.updateHighlighterPosition(this.selectedElement,this.selectedHighlighter,this.selectedLabel),this.lastHighlightedElement&&this.updateHighlighterPosition(this.lastHighlightedElement,this.hoverHighlighter,this.hoverLabel),this.selectedSiblingElements.length>0&&this.updateSiblingHighlighterPositions())};updateSiblingHighlighterPositions(){for(let i=0;i<this.selectedSiblingHighlighters.length;i++){let t=this.selectedSiblingHighlighters[i],n=this.visibleSelectedSiblingElements[i];if(!t||!n)continue;let s=n.getBoundingClientRect(),r=window.innerHeight,l=Math.max(0,s.top),o=Math.min(r,s.bottom),c=Math.max(0,o-l);Object.assign(t.style,{opacity:c>0?"1":"0",top:`${l}px`,left:`${s.left}px`,width:`${s.width}px`,height:`${c}px`})}}handleKeyDown=i=>{this.isActive&&(i.key==="Escape"||i.key==="Esc")&&this.handleVisualEditorToggle({type:"TOGGLE_REPLIT_VISUAL_EDITOR",enabled:!1,timestamp:Date.now()})};toggleEventListeners(i){i?(this.initializeHighlighter(),this.enableDisabledElements(),document.addEventListener("mousemove",this.handleMouseMove),document.addEventListener("mouseleave",this.handleMouseLeave),document.addEventListener("click",this.handleClick,!0),document.addEventListener("keydown",this.handleKeyDown),this.throttledRecalculate&&(window.addEventListener("resize",this.throttledRecalculate),window.addEventListener("scroll",this.throttledRecalculate,!0))):(this.restoreDisabledElements(),this.restoreElements(),document.removeEventListener("mousemove",this.handleMouseMove),document.removeEventListener("click",this.handleClick,!0),document.removeEventListener("mouseleave",this.handleMouseLeave),document.removeEventListener("keydown",this.handleKeyDown),this.throttledRecalculate&&(window.removeEventListener("resize",this.throttledRecalculate),window.removeEventListener("scroll",this.throttledRecalculate,!0)),this.mutationObserver&&(this.mutationObserver.disconnect(),this.mutationObserver=null),this.selectedElement&&(this.selectedElement.removeAttribute("contenteditable"),this.selectedElement.removeAttribute("data-original-text"),document.querySelectorAll('[contenteditable="plaintext-only"]').forEach(t=>{t.removeAttribute("contenteditable")})),this.clearSelectedSiblingHighlighters(),this.clearHoverSiblingHighlighters(),this.hoverHighlighter?.remove(),this.hoverLabel?.remove(),this.selectedHighlighter?.remove(),this.selectedLabel?.remove(),this.shadowHost?.remove(),this.hoverHighlighter=null,this.hoverLabel=null,this.selectedHighlighter=null,this.selectedLabel=null,this.shadowHost=null,this.shadowRoot=null,this.selectedElement=null)}clearHighlighters(i){return i.forEach(t=>{t.remove()}),[]}clearHoverSiblingHighlighters(){this.hoverSiblingHighlighters=this.clearHighlighters(this.hoverSiblingHighlighters)}clearSelectedSiblingHighlighters(){this.selectedSiblingElements.forEach(i=>{i.removeAttribute("contenteditable")}),this.selectedSiblingElements=[],this.visibleSelectedSiblingElements=[],this.selectedSiblingHighlighters=this.clearHighlighters(this.selectedSiblingHighlighters)}highlightElements(i){if(!this.shadowRoot||i.length===0)return[];let t=[];return i.forEach(n=>{let s=document.createElement("div");s.className="beacon-highlighter beacon-sibling-highlighter",this.shadowRoot?.appendChild(s),t.push(s);let r=n.getBoundingClientRect(),l=window.innerHeight,o=Math.max(0,r.top),c=Math.min(l,r.bottom),h=Math.max(0,c-o);Object.assign(s.style,{opacity:h>0?"1":"0",top:`${o}px`,left:`${r.left}px`,width:`${r.width}px`,height:`${h}px`})}),t}highlightHoverSiblings(i){this.clearHoverSiblingHighlighters();let t=R(i,v.MAX_SIBLING_HIGHLIGHTERS,!0);this.hoverSiblingHighlighters=this.highlightElements(t)}highlightSelectedSiblings(i){this.clearSelectedSiblingHighlighters();let t=R(i),n=t.filter(s=>J(s));this.selectedSiblingElements=t,this.visibleSelectedSiblingElements=n,this.selectedSiblingHighlighters=this.highlightElements(n)}enableDisabledElements(){document.querySelectorAll("button[disabled], input[disabled]").forEach(i=>{i.removeAttribute("disabled"),i.setAttribute("data-replit-disabled","")})}restoreDisabledElements(){document.querySelectorAll("[data-replit-disabled]").forEach(i=>{i.removeAttribute("data-replit-disabled"),i.setAttribute("disabled","")})}};if(typeof window<"u")try{window.REPLIT_BEACON_VERSION||(window.REPLIT_BEACON_VERSION=P,new D)}catch(e){console.error("[replit-beacon] Failed to initialize:",e)}})();
</script>
    <script type="text/javascript" src="/@replit/vite-plugin-dev-banner/banner-script.js" id="replit-dev-banner"></script><style>
    #replit-dev-banner {
      position: fixed;
      top: 0;
      left: 0;
      right: 0;
      z-index: 9999;
      display: flex;
      align-items: center;
      padding: 8px 16px;
      background-color: #004182;
      color: white;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Fira Sans", "Droid Sans", "Helvetica Neue", sans-serif;
      font-size: 14px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.15);
      border-bottom: 1px solid rgba(255, 255, 255, 0.1);
      transition: opacity 0.2s ease-in-out;
    }
    
    .banner-text {
      flex-grow: 1;
    }
    
    .banner-link {
      color: white;
      font-weight: 500;
      text-decoration: underline;
    }
    
    .banner-link:hover {
      text-decoration: none;
    }
    
    .banner-close {
      flex-shrink: 0;
      display: flex;
      align-items: center;
      justify-content: center;
      width: 28px;
      height: 28px;
      border: none;
      background: transparent;
      cursor: pointer;
      padding: 0;
      color: rgba(255, 255, 255, 0.7);
      margin-left: 12px;
      transition: transform 0.1s ease-in-out, color 0.1s ease-in-out;
    }
    
    .banner-close:hover {
      transform: scale(1.05);
      color: white;
    }
    
    @media (max-width: 600px) {
      #replit-dev-banner {
        padding: 8px;
        font-size: 12px;
      }
      
      .banner-close {
        width: 24px;
        height: 24px;
        margin-left: 8px;
      }
    }
  </style>
  </head>
  <body>
    <div id="root"></div>
    <script type="module" src="/src/main.tsx?v=54Ws3qBy9qhGFkR8MHEN_"></script>
  <script src="https://replit-cdn.com/replit-pill/replit-pill.global.js" data-repl-id="de2278f6-1e98-42bc-b5d0-3e6f286c8edb"></script>
</body></html>

        <div class="content" id="mainContent">
           
            <!-- School Information -->
            <div class="section-title">១. អត្តសញ្ញាណ និងព័ត៌មានសាលា</div>
            <div class="info-grid">
                <div class="info-card">
                    <label>លេខកូដសាលារៀន</label>
                    <input type="text" id="schoolCode" value="01030401017">
                </div>
                <div class="info-card">
                    <label>ឈ្មោះសាលារៀន</label>
                    <input type="text" id="schoolName" value="សាលាបឋមសិក្សា រោគ">
                </div>
                <div class="info-card">
                    <label>ភូមិ</label>
                    <input type="text" id="village" value="រោគ">
                </div>
                <div class="info-card">
                    <label>ឃុំ/សង្កាត់</label>
                    <input type="text" id="commune" value="ស្ពានស្រែង">
                </div>
                <div class="info-card">
                    <label>ស្រុក/ក្រុង</label>
                    <input type="text" id="district" value="ភ្នំស្រុក">
                </div>
                <div class="info-card">
                    <label>ខេត្ត/រាជធានី</label>
                    <input type="text" id="province" value="បន្ទាយមានជ័យ">
                </div>
            </div>

            <!-- Principal Information -->
            <div class="section-title">នាយក/នាយិកាសាលា</div>
            <div class="info-grid">
                <div class="info-card">
                    <label>ឈ្មោះជាអក្សរខ្មែរ</label>
                    <input type="text" id="principalNameKh" value="សុខ សារើន">
                </div>
                <div class="info-card">
                    <label>ឈ្មោះជាអក្សរឡាតាំង</label>
                    <input type="text" id="principalNameEn" value="SOK SAROUEN">
                </div>
                <div class="info-card">
                    <label>ភេទ</label>
                    <input type="text" id="principalGender" value="ស្រី">
                </div>
                <div class="info-card">
                    <label>លេខទូរស័ព្ទ</label>
                    <input type="text" id="principalPhone" value="089663966">
                </div>
            </div>

            <!-- Student Statistics -->
            <div class="section-title">២. សិស្ស - ថ្នាក់ទី១ ដល់ទី៦</div>
            <table id="studentTable">
                <thead>
                    <tr>
                        <th rowspan="2">ថ្នាក់</th>
                        <th colspan="2">សិស្សថ្មី</th>
                        <th colspan="2">សិស្សឡើងថ្នាក់</th>
                        <th colspan="2">សិស្សត្រួតថ្នាក់</th>
                        <th colspan="2">សរុប</th>
                    </tr>
                    <tr>
                        <th>សរុប</th>
                        <th>ស្រី</th>
                        <th>សរុប</th>
                        <th>ស្រី</th>
                        <th>សរុប</th>
                        <th>ស្រី</th>
                        <th>សរុប</th>
                        <th>ស្រី</th>
                    </tr>
                </thead>
                <tbody id="studentTableBody">
                </tbody>
            </table>

            <!-- Teacher Statistics -->
            <div class="section-title">៤. បុគ្គលិកបង្រៀន និងបុគ្គលិកមិនបង្រៀន</div>
            <table id="teacherTable">
                <thead>
                    <tr>
                        <th>ក្របខណ្ឌ</th>
                        <th colspan="2">បុគ្គលិកបង្រៀន</th>
                        <th colspan="2">បុគ្គលិកមិនបង្រៀន</th>
                    </tr>
                    <tr>
                        <th></th>
                        <th>សរុប</th>
                        <th>ស្រី</th>
                        <th>សរុប</th>
                        <th>ស្រី</th>
                    </tr>
                </thead>
                <tbody id="teacherTableBody">
                </tbody>
            </table>

            <!-- Facilities -->
            <div class="section-title">៥. អគារ និងបរិក្ខា</div>
            <table id="facilityTable">
                <thead>
                    <tr>
                        <th>ប្រភេទ</th>
                        <th>ចំនួន</th>
                        <th>ស្ថានភាព</th>
                    </tr>
                </thead>
                <tbody id="facilityTableBody">
                </tbody>
            </table>
        </div>
    </div>

### តារាងជំរឿនស្ថិតិសាលារៀនចំណេះទូទៅសាធារណៈ
### ឆ្នាំសិក្សា ២០២៥-២០២៦ (ប__ឋមសិក្សា)

<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="3">ប្រកាសលេខ</td>
			<td colspan="5">1121 អយក.ប្រ</td>
			<td colspan="26">10 August 2020</td>
		</tr>
		<tr>
			<td colspan="34">សូមអានសេចក្តីណែនាំមុននឹងបំពេញ	</td>
		</tr>
		<tr>
			<td colspan="24">សូមផ្ញើទៅការិយាល័យអប់រំ យុវជន និងកីឡានៃរដ្ឋបាលស្រុក/ក្រុងវិញមុនថ្ងៃទី ១០-១១-២០២៥</td>
			<td colspan="5">លេខកូដសាលារៀន៖</td>
			<td colspan="5" contenteditable="true">01030401017</p>
			</td>
		</tr>
		<tr>
			<td colspan="4">ប្រភេទសាលារៀន	</td>
			<td colspan="7" contenteditable="true">សាលារៀនចំណេះទូទៅ</td>
			<td colspan="5">កម្រិតសាលាកុមារមេត្រី</td>
			<td colspan="7" contenteditable="true">កម្រិតមធ្យម</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td colspan="2" rowspan="2">
			<p>UTM</p>
			</td>
			<td>
			<p>x</p>
			</td>
			<td colspan="2" rowspan="2">
			<p>48N</p>
			</td>
			<td colspan="5" contenteditable="true">328181</td>
		</tr>
		<tr>
			<td colspan="10">សាលាអនុវត្តកម្មវិធីផ្តល់អាហារតាមសាលារៀន៖</td>
			<td colspan="3" contenteditable="true">ទេ</td>
			<td colspan="3">
			<p>ឧបត្ថមគាំទ្រដោយ៖</p>
			</td>
			<td colspan="7" contenteditable="true">ផ្សេងៗៗ</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>y</p>
			</td>
			<td colspan="5" contenteditable="true">1515125	</td>
		</tr>
		<tr>
			<td colspan="34">
			<p>១. អត្តសញ្ញាណ និងព័ត៌មានសាវតារ</p>
			</td>
		</tr>
		<tr>
			<td colspan="13">
			<p>១.(ក) នាយក/នាយិកាសាលាបឋមសិក្សា *(មិនមែននាយកកម្រង)</p>
			</td>
			<td rowspan="15">
			<p>&nbsp;</p>
			</td>
			<td colspan="20">
			<p>១.(ខ)សាលាបឋមសិក្សា</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>ឈ្មោះជាអក្សរខ្មែរ</p>
			</td>
			<td colspan="6">
			<p>សុខ សារើន</p>
			</td>
			<td colspan="7">
			<p>ឈ្មោះសាលារៀន(បច្ចុប្បន្ន)</p>
			</td>
			<td colspan="13">
			<p>សាលាបឋមសិក្សា រោគ</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>ឈ្មោះជាអក្សរពុម្ពឡាតាំង</p>
			</td>
			<td colspan="6">
			<p>SOK SAROUEN</p>
			</td>
			<td colspan="7">
			<p>ឈ្នោះសាលារៀន(ឆ្នាំមុន)</p>
			</td>
			<td colspan="13">
			<p>សាលាបឋមសិក្សា រោគ</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>អត្តលេខមន្ត្រីរាជការ</p>
			</td>
			<td colspan="6">
			<p>2730200248</p>
			</td>
			<td colspan="7">
			<p>ភូមិ</p>
			</td>
			<td colspan="13">
			<p>រោគ</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>ថ្ងៃខែឆ្នាំកំណើត</p>
			</td>
			<td colspan="6">
			<p>04 August 1973</p>
			</td>
			<td colspan="7">
			<p>ឃុំ/សង្កាត់</p>
			</td>
			<td colspan="13">
			<p>សា្ពនស្រែង</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>ភេទ</p>
			</td>
			<td colspan="6">
			<p>ស្រី</p>
			</td>
			<td colspan="7">
			<p>ក្រុង/ស្រុក/ខណ្ឌ</p>
			</td>
			<td colspan="13">
			<p>ភ្នំស្រុក</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>កម្រិតវប្បធម៌ខ្ពស់បំផុត</p>
			</td>
			<td colspan="6">
			<p>ក្នុងមធ្យមសិក្សាទុតិយភូមិ</p>
			</td>
			<td colspan="7">
			<p>រាជធានី/ខេត្ត</p>
			</td>
			<td colspan="13">
			<p>បន្ទាយមានជ័យ</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>បើជានាយកជំនួស(សូមគូសរង្វង់)</p>
			</td>
			<td colspan="6">
			<p>&nbsp;</p>
			</td>
			<td colspan="7">
			<p>ទីតាំងសាលារៀន</p>
			</td>
			<td colspan="13">
			<p>តំបន់ជនបទ</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>ចំនួនឆ្នាំបម្រើការងារអប់រំ</p>
			</td>
			<td colspan="6">
			<p>33 ឆ្នាំ</p>
			</td>
			<td colspan="7">
			<p>ចំនួនវេនរៀន</p>
			</td>
			<td colspan="13">
			<p>ពីរវេន</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>ចំនួនឆ្នាំបម្រើការងារជានាយក</p>
			</td>
			<td colspan="6">
			<p>10 ឆ្នាំ</p>
			</td>
			<td colspan="14">
			<p>មានថ្នាក់អនុវិទ្យាល័យដែលស្ថិតនៅក្នុងបឋមសិក្សា</p>
			</td>
			<td colspan="6">
			<p>ទេ</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>ចំនួនម៉ោងបង្រៀនក្នុងមួយសប្តាហ៍</p>
			</td>
			<td colspan="6">
			<p>30 ម៉ោង</p>
			</td>
			<td colspan="14">
			<p>សាលារៀនបណ្តែតទឹក</p>
			</td>
			<td colspan="6">
			<p>ទេ</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>លេខទូរស័ព្ទរបស់នាយក</p>
			</td>
			<td colspan="6">
			<p>089663966</p>
			</td>
			<td colspan="14">
			<p>សាលារៀនទាំងមូលនៅក្នុងវត្ត(សូមគូសរង្វង់)</p>
			</td>
			<td colspan="6">
			<p>ទេ</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>សារអេឡិចត្រូនិក(E-mail)</p>
			</td>
			<td colspan="6">
			<p>&nbsp;</p>
			</td>
			<td colspan="6">
			<p>ចំនួនថ្នាក់រៀននៅក្នុងវត្ត(បើមាន)៖</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="7">
			<p>ចំនួនថ្នាក់រៀននៅតាមផ្ទះ(បើមាន)៖</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="13">
			<p>*នាយកដែលកាន់ការងារគ្រប់គ្រងដឹកនាំសាលារៀនផ្ទាល់</p>
			</td>
			<td colspan="14">
			<p>ចំនួនព្រះសង្ឃដែលជួយបង្រៀននៅក្នុងសាលារៀន</p>
			</td>
			<td colspan="6">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="13">
			<p>១.(គ)អ្នកទទួលបន្ទុកគ្រប់គ្រងសាលារៀនឧបសម្ព័ន</p>
			</td>
			<td colspan="14">
			<p>ចំនួនគ្រូក្រៅក្របខណ្ឌទទួលប្រាក់ឧបត្ថមពីសហគមន៍/អង្គការនានា</p>
			</td>
			<td colspan="6">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>ឋានៈអ្នកទទួលបន្ទុក(សូមគូសរង្វង់)</p>
			</td>
			<td colspan="6">
			<p>&nbsp;</p>
			</td>
			<td rowspan="8">
			<p>&nbsp;</p>
			</td>
			<td colspan="14">
			<p>មានថ្នាក់មត្តេយ្យដែលស្ថិតនៅក្នុងបឋមសិក្សា</p>
			</td>
			<td colspan="6">
			<p>Yes</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>ឈ្មោះជាអក្សរខ្មែរ</p>
			</td>
			<td colspan="6">
			<p>&nbsp;</p>
			</td>
			<td colspan="14">
			<p>ចម្ងាយពីសាលារៀនទៅសាលាឃុំ/សង្កាត់</p>
			</td>
			<td colspan="6">
			<p>0 គីឡូម៉ែត្រ</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>ឈ្មោះជាអក្សរពុម្ពឡាតាំង</p>
			</td>
			<td colspan="6">
			<p>&nbsp;</p>
			</td>
			<td colspan="14">
			<p>ចម្ងាយពីសាលារៀនទៅសាលាក្រុង/ស្រុក/ខណ្ឌ</p>
			</td>
			<td colspan="6">
			<p>12 គីឡូម៉ែត្រ</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>ថ្ងៃខែឆ្នាំកំណើត</p>
			</td>
			<td colspan="6">
			<p>&nbsp;</p>
			</td>
			<td colspan="14">
			<p>ចម្ងាយពីសាលារៀនទៅសាលារាជធានី/ខេត្ត</p>
			</td>
			<td colspan="6">
			<p>69 គីឡូម៉ែត្រ</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>ភេទ</p>
			</td>
			<td colspan="6">
			<p>&nbsp;</p>
			</td>
			<td colspan="14">
			<p>សាលារៀនឧបសម្ព័ន</p>
			</td>
			<td colspan="6">
			<p>ពិតមែន</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>កម្រិតវប្បធម៌ខ្ពស់បំផុត</p>
			</td>
			<td colspan="6">
			<p>&nbsp;</p>
			</td>
			<td colspan="5">
			<p>កម្រងសាលារៀនឈ្មោះ៖</p>
			</td>
			<td colspan="15">
			<p>ស្ពានស្រែង</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>ចំនួនឆ្នាំបម្រើការងារអប់រំ</p>
			</td>
			<td colspan="6">
			<p>&nbsp;</p>
			</td>
			<td colspan="14">
			<p>ជាសាលារៀនបង្គោល ឬសាលារៀនសម្ព័ន</p>
			</td>
			<td colspan="6">
			<p>សម្ព័ន្ធ</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>ចំនួនម៉ោងបង្រៀនក្នុងមួយសប្តាហ៍</p>
			</td>
			<td colspan="6">
			<p>&nbsp;</p>
			</td>
			<td colspan="14">
			<p>បើជាសាលារៀនបង្គោល សូមប្រាប់ចំនួនសាលានៅក្នុងកម្រង</p>
			</td>
			<td colspan="6">
			<p>&nbsp;</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>២.សិស្ស</p>
			</td>
		</tr>
		<tr>
			<td colspan="34">
			<p>២.(ក១)សិស្សថ្មី សិស្សឡើងថ្នាក់ និងសិស្សត្រួតថ្នាក់ ក្នុងឆ្នាំសិក្សា ២០២៥-២០២៦</p>
			</td>
		</tr>
		<tr>
			<td colspan="4" rowspan="2">
			<p>អាយុ(ឆ្នាំ)</p>
			</td>
			<td colspan="6">
			<p>ថ្នាក់កម្រិតទាប</p>
			</td>
			<td colspan="6">
			<p>ថ្នាក់កម្រិតមធ្យម</p>
			</td>
			<td colspan="6">
			<p>ថ្នាក់កម្រិតខ្ពស់</p>
			</td>
			<td colspan="6">
			<p>ថ្នាក់ចម្រុះ</p>
			</td>
			<td colspan="6">
			<p>សរុប</p>
			</td>
		</tr>
		<tr>
			<td colspan="3">
			<p>សរុប</p>
			</td>
			<td colspan="3">
			<p>ស្រី</p>
			</td>
			<td colspan="3">
			<p>សរុប</p>
			</td>
			<td colspan="3">
			<p>ស្រី</p>
			</td>
			<td colspan="3">
			<p>សរុប</p>
			</td>
			<td colspan="3">
			<p>ស្រី</p>
			</td>
			<td colspan="3">
			<p>សរុប</p>
			</td>
			<td colspan="3">
			<p>ស្រី</p>
			</td>
			<td colspan="3">
			<p>សរុប</p>
			</td>
			<td colspan="3">
			<p>ស្រី</p>
			</td>
		</tr>
		<tr>
			<td colspan="4">
			<p>3</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>20</p>
			</td>
			<td colspan="3">
			<p>13</p>
			</td>
			<td colspan="3">
			<p>20</p>
			</td>
			<td colspan="3">
			<p>13</p>
			</td>
		</tr>
		<tr>
			<td colspan="4">
			<p>4</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>20</p>
			</td>
			<td colspan="3">
			<p>12</p>
			</td>
			<td colspan="3">
			<p>20</p>
			</td>
			<td colspan="3">
			<p>12</p>
			</td>
		</tr>
		<tr>
			<td colspan="4">
			<p>5</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>35</p>
			</td>
			<td colspan="3">
			<p>20</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>35</p>
			</td>
			<td colspan="3">
			<p>20</p>
			</td>
		</tr>
		<tr>
			<td colspan="4">
			<p>៥+</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="4">
			<p>សរុប</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>35</p>
			</td>
			<td colspan="3">
			<p>20</p>
			</td>
			<td colspan="3">
			<p>40</p>
			</td>
			<td colspan="3">
			<p>25</p>
			</td>
			<td colspan="3">
			<p>75</p>
			</td>
			<td colspan="3">
			<p>45</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>២.(ក២)សិស្សថ្មី សិស្សឡើងថ្នាក់ និងសិស្សត្រួតថ្នាក់ ក្នុងឆ្នាំសិក្សា ២០២៥-២០២៦</p>
			</td>
		</tr>
		<tr>
			<td colspan="2" rowspan="3">
			<p>អាយុ(ឆ្នាំ)</p>
			</td>
			<td colspan="8">
			<p>ថ្នាក់ទី ១</p>
			</td>
			<td colspan="8">
			<p>ថ្នាក់ទី ២</p>
			</td>
			<td colspan="8">
			<p>ថ្នាក់ទី ៣</p>
			</td>
			<td colspan="8">
			<p>ថ្នាក់ទី ៤</p>
			</td>
		</tr>
		<tr>
			<td colspan="4">
			<p>សិស្សថ្មី</p>
			</td>
			<td colspan="4">
			<p>សិស្សត្រួតថ្នាក់</p>
			</td>
			<td colspan="4">
			<p>សិស្សឡើងថ្នាក់</p>
			</td>
			<td colspan="4">
			<p>សិស្សត្រួតថ្នាក់</p>
			</td>
			<td colspan="4">
			<p>សិស្សឡើងថ្នាក់</p>
			</td>
			<td colspan="4">
			<p>សិស្សត្រួតថ្នាក់</p>
			</td>
			<td colspan="4">
			<p>សិស្សឡើងថ្នាក់</p>
			</td>
			<td colspan="4">
			<p>សិស្សត្រួតថ្នាក់</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>6</p>
			</td>
			<td colspan="2">
			<p>30</p>
			</td>
			<td colspan="2">
			<p>14</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>7</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>39</p>
			</td>
			<td colspan="2">
			<p>21</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>8</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>3</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>36</p>
			</td>
			<td colspan="2">
			<p>21</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>9</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>5</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>44</p>
			</td>
			<td colspan="2">
			<p>21</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>10</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>4</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>11</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>12</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>13</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>14</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>១៥+</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>30</p>
			</td>
			<td colspan="2">
			<p>14</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>42</p>
			</td>
			<td colspan="2">
			<p>22</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>41</p>
			</td>
			<td colspan="2">
			<p>22</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>49</p>
			</td>
			<td colspan="2">
			<p>23</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>២.(ក២)សិស្សថ្មី សិស្សឡើងថ្នាក់ និងសិស្សត្រួតថ្នាក់ ក្នុងឆ្នាំសិក្សា ២០២៥-២០២៦ (បន្ត)</p>
			</td>
		</tr>
		<tr>
			<td colspan="2" rowspan="3">
			<p>អាយុ(ឆ្នាំ)</p>
			</td>
			<td colspan="8">
			<p>ថ្នាក់ទី ៥</p>
			</td>
			<td colspan="8">
			<p>ថ្នាក់ទី ៦</p>
			</td>
			<td colspan="16">
			<p>សរុបរួម (ពីថ្នាក់ទី ១ ដល់ទី ៦)</p>
			</td>
		</tr>
		<tr>
			<td colspan="4">
			<p>សិស្សថ្មី</p>
			</td>
			<td colspan="4">
			<p>សិស្សត្រួតថ្នាក់</p>
			</td>
			<td colspan="4">
			<p>សិស្សឡើងថ្នាក់</p>
			</td>
			<td colspan="4">
			<p>សិស្សត្រួតថ្នាក់</p>
			</td>
			<td colspan="8">
			<p>សិស្សថ្មី/សិស្សឡើងថ្នាក់</p>
			</td>
			<td colspan="8">
			<p>សិស្សត្រួតថ្នាក់</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="4">
			<p>សរុប</p>
			</td>
			<td colspan="4">
			<p>ស្រី</p>
			</td>
			<td colspan="4">
			<p>សរុប</p>
			</td>
			<td colspan="4">
			<p>ស្រី</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>6</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>30</p>
			</td>
			<td colspan="4">
			<p>14</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>7</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>39</p>
			</td>
			<td colspan="4">
			<p>21</p>
			</td>
			<td colspan="4">
			<p>0</p>
			</td>
			<td colspan="4">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>8</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>39</p>
			</td>
			<td colspan="4">
			<p>22</p>
			</td>
			<td colspan="4">
			<p>0</p>
			</td>
			<td colspan="4">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>9</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>49</p>
			</td>
			<td colspan="4">
			<p>22</p>
			</td>
			<td colspan="4">
			<p>0</p>
			</td>
			<td colspan="4">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>10</p>
			</td>
			<td colspan="2">
			<p>41</p>
			</td>
			<td colspan="2">
			<p>21</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>45</p>
			</td>
			<td colspan="4">
			<p>22</p>
			</td>
			<td colspan="4">
			<p>0</p>
			</td>
			<td colspan="4">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>11</p>
			</td>
			<td colspan="2">
			<p>9</p>
			</td>
			<td colspan="2">
			<p>2</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>28</p>
			</td>
			<td colspan="2">
			<p>15</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>38</p>
			</td>
			<td colspan="4">
			<p>18</p>
			</td>
			<td colspan="4">
			<p>0</p>
			</td>
			<td colspan="4">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>12</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>7</p>
			</td>
			<td colspan="2">
			<p>2</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>7</p>
			</td>
			<td colspan="4">
			<p>2</p>
			</td>
			<td colspan="4">
			<p>0</p>
			</td>
			<td colspan="4">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>13</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>0</p>
			</td>
			<td colspan="4">
			<p>0</p>
			</td>
			<td colspan="4">
			<p>0</p>
			</td>
			<td colspan="4">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>14</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>0</p>
			</td>
			<td colspan="4">
			<p>0</p>
			</td>
			<td colspan="4">
			<p>0</p>
			</td>
			<td colspan="4">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>១៥+</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>0</p>
			</td>
			<td colspan="4">
			<p>0</p>
			</td>
			<td colspan="4">
			<p>0</p>
			</td>
			<td colspan="4">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>50</p>
			</td>
			<td colspan="2">
			<p>23</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>35</p>
			</td>
			<td colspan="2">
			<p>17</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="4">
			<p>247</p>
			</td>
			<td colspan="4">
			<p>121</p>
			</td>
			<td colspan="4">
			<p>0</p>
			</td>
			<td colspan="4">
			<p>0</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>២.(ខ១)សិស្សពិការ សិស្សជួបការលំបាកផ្នែកសុខភាព និងសិស្សជួបការលំបាកតាមកម្រិតថ្នាក់(មត្តេយ្យសិក្សា)</p>
			</td>
		</tr>
		<tr>
			<td colspan="6" rowspan="2">
			<p>បរិយាយ</p>
			</td>
			<td colspan="6">
			<p>ថ្នាក់កម្រិតទាប</p>
			</td>
			<td colspan="6">
			<p>ថ្នាក់កម្រិតមធ្យម</p>
			</td>
			<td colspan="6">
			<p>ថ្នាក់កម្រិតខ្ពស់</p>
			</td>
			<td colspan="6">
			<p>ថ្នាក់ចម្រុះ</p>
			</td>
			<td colspan="4">
			<p>សរុប</p>
			</td>
		</tr>
		<tr>
			<td colspan="3">
			<p>សរុប</p>
			</td>
			<td colspan="3">
			<p>ស្រី</p>
			</td>
			<td colspan="3">
			<p>សរុប</p>
			</td>
			<td colspan="3">
			<p>ស្រី</p>
			</td>
			<td colspan="3">
			<p>សរុប</p>
			</td>
			<td colspan="3">
			<p>ស្រី</p>
			</td>
			<td colspan="3">
			<p>សរុប</p>
			</td>
			<td colspan="3">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
		</tr>
		<tr>
			<td colspan="34">
			<p>សិស្សពិការ</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ចំនួនសិស្សពិការ*</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>5</p>
			</td>
			<td colspan="3">
			<p>1</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>5</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
		</tr>
		<tr>
			<td colspan="34">
			<p>ប្រភេទពិការ**</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ពិបាកក្នុងការធ្វើចលនា</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ពិបាកក្នុងការស្តាប់</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ពិបាកក្នុងការនិយាយ</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ពិបាកក្នុងការមើល</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>3</p>
			</td>
			<td colspan="3">
			<p>1</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>3</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ពិការសរីរាង្គខាងក្នុង</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ពិការសតិបញ្ញា</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>2</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>2</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ពិបាកខាងផ្លូវចិត្ត</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ពិការផ្សេងៗ (ក្រៅពីខាងលើ)</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ពិការគេ ថ្លង់</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="34">
			<p>សិស្សជួបការលំបាកផ្នែកសុខភាព</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ចំនួនជួបការលំបាកផ្នែកសុខភាព*</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="34">
			<p>ប្រភេទការលំបាកផ្នែកសុខភាព**</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>មានស្ថានភាពអាហារូបត្ថមធ្ងន់ធ្ងរ</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>មានជម្ងឺប្រចាំកាយ</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="34">
			<p>សិស្សជួបការលំបាក</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ចំនួនសិស្សជួបការលំបាក*</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>12</p>
			</td>
			<td colspan="3">
			<p>7</p>
			</td>
			<td colspan="3">
			<p>8</p>
			</td>
			<td colspan="3">
			<p>7</p>
			</td>
			<td colspan="2">
			<p>12</p>
			</td>
			<td colspan="2">
			<p>8</p>
			</td>
		</tr>
		<tr>
			<td colspan="34">
			<p>ប្រភេទការលំបាក**</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>មកពីគ្រួសារផ្លាស់ប្តូរទីលំនៅ</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>កុមារកំព្រា</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>កុមាររងគ្រោះដោយHIV/AIDS</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>កុមាររងងំពើហិង្សាក្នុងគ្រួសារ(ផ្លូវកាយ ផ្លូវចិត្ត ផ្លូវភេទ និងការបោះបង់មិនអើពើ)</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>កុមាររងការកេងប្រវ័ញ្ជពលកម្ម</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>កុមារដែលមកពីគ្រួសារក្រីក្រ</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>12</p>
			</td>
			<td colspan="3">
			<p>7</p>
			</td>
			<td colspan="3">
			<p>8</p>
			</td>
			<td colspan="3">
			<p>7</p>
			</td>
			<td colspan="2">
			<p>20</p>
			</td>
			<td colspan="2">
			<p>14</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>កុមាររងពើហិង្សាក្នុងសាលា</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="34">
			<p>ចំនួនកុមារទទួលបានកិច្ចអន្តរាគមន៍ និងប្រឹក្សាយោបល់</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ចំនួនសិស្សទទួលបានកិច្ចអន្តរគមន៍របស់សុខាភិបាល</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ចំនួនសិស្សទទួលបានកិច្ចគាំពារ និងប្រឹក្សាយោបល់ របស់សុខាភិបាល</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>២.(ខ២)សិស្សពិការ សិស្សជួបការលំបាកផ្នែកសុខភាព និងសិស្សជួបការលំបាកតាមកម្រិតថ្នាក់ (បឋមសិក្សា)</p>
			</td>
		</tr>
		<tr>
			<td colspan="6" rowspan="2">
			<p>បរិយាយ</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ១</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ២</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ៣</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ៤</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ៥</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ៦</p>
			</td>
			<td colspan="4">
			<p>សរុប</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
		</tr>
		<tr>
			<td colspan="34">
			<p>សិស្សពិការ</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ចំនួនសិស្សពិការ*</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>2</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>4</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
		</tr>
		<tr>
			<td colspan="34">
			<p>ប្រភេទពិការ**</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ពិបាកក្នុងការធ្វើចលនា</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ពិបាកក្នុងការស្តាប់</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ពិបាកក្នុងការនិយាយ</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ពិបាកក្នុងការមើល</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ពិការសរីរាង្គខាងក្នុង</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ពិការសតិបញ្ញា</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ពិបាកខាងផ្លូវចិត្ត</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ពិការផ្សេងៗ (ក្រៅពីខាងលើ)</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>2</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ពិការគេ ថ្លង់</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
		</tr>
		<tr>
			<td colspan="34">
			<p>សិស្សជួបការលំបាកផ្នែកសុខភាព</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ចំនួនជួបការលំបាកផ្នែកសុខភាព*</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="34">
			<p>ប្រភេទការលំបាកផ្នែកសុខភាព**</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>មានស្ថានភាពអាហារូបត្ថមធ្ងន់ធ្ងរ</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>មានជម្ងឺប្រចាំកាយ</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="34">
			<p>សិស្សជួបការលំបាក</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ចំនួនសិស្សជួបការលំបាក*</p>
			</td>
			<td colspan="2">
			<p>20</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>40</p>
			</td>
			<td colspan="2">
			<p>20</p>
			</td>
			<td colspan="2">
			<p>36</p>
			</td>
			<td colspan="2">
			<p>16</p>
			</td>
			<td colspan="2">
			<p>22</p>
			</td>
			<td colspan="2">
			<p>8</p>
			</td>
			<td colspan="2">
			<p>21</p>
			</td>
			<td colspan="2">
			<p>9</p>
			</td>
			<td colspan="2">
			<p>9</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>148</p>
			</td>
			<td colspan="2">
			<p>54</p>
			</td>
		</tr>
		<tr>
			<td colspan="34">
			<p>ប្រភេទការលំបាក**</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>មកពីគ្រួសារផ្លាស់ប្តូរទីលំនៅ</p>
			</td>
			<td colspan="2">
			<p>2</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>2</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>4</p>
			</td>
			<td colspan="2">
			<p>2</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>កុមារកំព្រា</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>2</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>2</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>6</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>កុមាររងគ្រោះដោយHIV/AIDS</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>កុមាររងងំពើហិង្សាក្នុងគ្រួសារ(ផ្លូវកាយ ផ្លូវចិត្ត ផ្លូវភេទ និងការបោះបង់មិនអើពើ)</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>កុមាររងការកេងប្រវ័ញ្ជពលកម្ម</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>កុមារដែលមកពីគ្រួសារក្រីក្រ</p>
			</td>
			<td colspan="2">
			<p>17</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>39</p>
			</td>
			<td colspan="2">
			<p>19</p>
			</td>
			<td colspan="2">
			<p>36</p>
			</td>
			<td colspan="2">
			<p>16</p>
			</td>
			<td colspan="2">
			<p>20</p>
			</td>
			<td colspan="2">
			<p>8</p>
			</td>
			<td colspan="2">
			<p>17</p>
			</td>
			<td colspan="2">
			<p>8</p>
			</td>
			<td colspan="2">
			<p>9</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>138</p>
			</td>
			<td colspan="2">
			<p>51</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>កុមាររងពើហិង្សាក្នុងសាលា</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="34">
			<p>ចំនួនកុមារទទួលបានកិច្ចអន្តរាគមន៍ និងប្រឹក្សាយោបល់</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ចំនួនសិស្សទទួលបានកិច្ចអន្តរគមន៍របស់សុខាភិបាល</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ចំនួនសិស្សទទួលបានកិច្ចគាំពារ និងប្រឹក្សាយោបល់ របស់សុខាភិបាល</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>*សំដៅលើចំនួនសិស្សសរុប(ដោយរាប់សិស្សម្នាក់តែម្តងគត់ ទោះបីសិស្សនោះមានពិការភាពច្រើនប្រភេទក៏ដោយ)</p>
			</td>
		</tr>
		<tr>
			<td colspan="34">
			<p>**សំដៅលើចំនួនសិស្សសរុបតាមប្រភេទ(ដោយរាប់សិស្សម្នាក់បានច្រើនដង តាមប្រភេទពិការភាពជាក់ស្តែងរបស់សិស្សនោះ ប្រសិនបើសិស្សម្នាក់នោះមានពិការភាពច្រើនប្រភេទ)</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>២.(គ១)កុមារតាមក្រុមអាយុ និងគ្រូ(ជនជាតិដើមភាគតិច)(ចំនួនកុមារជនជាតិភាគតិច ក្នុងចំណោមកុមារសរុបទាំងអស់ នៃតារាង ២(ក១)</p>
			</td>
		</tr>
		<tr>
			<td colspan="6" rowspan="2">
			<p>ជនជាតិដើមភាគតិច តាមក្រុមអាយុ</p>
			</td>
			<td colspan="6">
			<p>ថ្នាក់កម្រិតទាប</p>
			</td>
			<td colspan="6">
			<p>ថ្នាក់កម្រិតមធ្យម</p>
			</td>
			<td colspan="6">
			<p>ថ្នាក់កម្រិតខ្ពស់</p>
			</td>
			<td colspan="6">
			<p>ថ្នាក់ចម្រុះ</p>
			</td>
			<td colspan="4">
			<p>សរុប</p>
			</td>
		</tr>
		<tr>
			<td colspan="3">
			<p>សរុប</p>
			</td>
			<td colspan="3">
			<p>ស្រី</p>
			</td>
			<td colspan="3">
			<p>សរុប</p>
			</td>
			<td colspan="3">
			<p>ស្រី</p>
			</td>
			<td colspan="3">
			<p>សរុប</p>
			</td>
			<td colspan="3">
			<p>ស្រី</p>
			</td>
			<td colspan="3">
			<p>សរុប</p>
			</td>
			<td colspan="3">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>3</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>4</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>5</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>៥+</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>សរុប</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>២.(គ២)កុមារតាមក្រុមអាយុ និងគ្រូ(ជនជាតិដើមភាគតិច)(ចំនួនកុមារជនជាតិភាគតិច ក្នុងចំណោមកុមារសរុបទាំងអស់ នៃតារាង ២(ក២))</p>
			</td>
		</tr>
		<tr>
			<td colspan="6" rowspan="2">
			<p>ជនជាតិដើមភាគតិច តាមក្រុមអាយុ</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ១</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ២</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ៣</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ៤</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ៥</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ៦</p>
			</td>
			<td colspan="4">
			<p>សរុប</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>សិស្ស (អាយុ ៦-១១)</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>សិស្ស (អាយុ ១២+)</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>គ្រូបង្រៀន(ជនជាតិដើមភាគតិច)</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>គ្រូមិនបង្រៀន(ជនជាតិដើមភាគតិច)</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>២(ឃ១)ចំនួនកុមាររៀនក្នុងឆ្នាំសិក្សា ២០២៤-២០២៥</p>
			</td>
		</tr>
		<tr>
			<td colspan="6" rowspan="2">
			<p>ចំនួនកុមារ</p>
			</td>
			<td colspan="6">
			<p>ថ្នាក់កម្រិតទាប</p>
			</td>
			<td colspan="6">
			<p>ថ្នាក់កម្រិតមធ្យម</p>
			</td>
			<td colspan="6">
			<p>ថ្នាក់កម្រិតខ្ពស់</p>
			</td>
			<td colspan="6">
			<p>ថ្នាក់ចម្រុះ</p>
			</td>
			<td colspan="4">
			<p>សរុប</p>
			</td>
		</tr>
		<tr>
			<td colspan="3">
			<p>សរុប</p>
			</td>
			<td colspan="3">
			<p>ស្រី</p>
			</td>
			<td colspan="3">
			<p>សរុប</p>
			</td>
			<td colspan="3">
			<p>ស្រី</p>
			</td>
			<td colspan="3">
			<p>សរុប</p>
			</td>
			<td colspan="3">
			<p>ស្រី</p>
			</td>
			<td colspan="3">
			<p>សរុប</p>
			</td>
			<td colspan="3">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ដើមឆ្នាំ២០២៤-២០២៥</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>42</p>
			</td>
			<td colspan="3">
			<p>18</p>
			</td>
			<td colspan="3">
			<p>30</p>
			</td>
			<td colspan="3">
			<p>20</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>72</p>
			</td>
			<td colspan="2">
			<p>38</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ចុងឆ្នាំ ២០២៤-២០២៥</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>42</p>
			</td>
			<td colspan="3">
			<p>18</p>
			</td>
			<td colspan="3">
			<p>30</p>
			</td>
			<td colspan="3">
			<p>20</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>72</p>
			</td>
			<td colspan="2">
			<p>38</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>អាយុ៥ឆ្នាំឆ្លងកាត់តេស្តស្តង់ដារ</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>30</p>
			</td>
			<td colspan="3">
			<p>20</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>30</p>
			</td>
			<td colspan="2">
			<p>20</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>អាយុ៥ឆ្នាំបញ្ជូនទៅថ្នាក់ទី១</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>30</p>
			</td>
			<td colspan="3">
			<p>20</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>30</p>
			</td>
			<td colspan="2">
			<p>20</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>អាយុ៥ឆ្នាំមានការអភិវឌ្ឍផ្នែងទាំង៥បានល្អប្រសើរ</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>20</p>
			</td>
			<td colspan="3">
			<p>14</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>20</p>
			</td>
			<td colspan="2">
			<p>14</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>សរុប</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>84</p>
			</td>
			<td colspan="3">
			<p>36</p>
			</td>
			<td colspan="3">
			<p>140</p>
			</td>
			<td colspan="3">
			<p>94</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>224</p>
			</td>
			<td colspan="2">
			<p>130</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>២(ឃ២)ចំនួនសិស្ស និងលទ្ធផលប្រឡង ក្នុងឆ្នាំសិក្សា ២០២៤-២០២៥ និងសិស្សអាហារូបករណ៍</p>
			</td>
		</tr>
		<tr>
			<td colspan="6" rowspan="2">
			<p>សិស្ស</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ១</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ២</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ៣</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ៤</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ៥</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ៦</p>
			</td>
			<td colspan="4">
			<p>សរុប</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ដើមឆ្នាំសិក្សា២៤-២៥</p>
			</td>
			<td colspan="2">
			<p>39</p>
			</td>
			<td colspan="2">
			<p>19</p>
			</td>
			<td colspan="2">
			<p>40</p>
			</td>
			<td colspan="2">
			<p>21</p>
			</td>
			<td colspan="2">
			<p>46</p>
			</td>
			<td colspan="2">
			<p>23</p>
			</td>
			<td colspan="2">
			<p>51</p>
			</td>
			<td colspan="2">
			<p>23</p>
			</td>
			<td colspan="2">
			<p>34</p>
			</td>
			<td colspan="2">
			<p>16</p>
			</td>
			<td colspan="2">
			<p>31</p>
			</td>
			<td colspan="2">
			<p>9</p>
			</td>
			<td colspan="2">
			<p>241</p>
			</td>
			<td colspan="2">
			<p>111</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ចុងឆ្នាំសិក្សា២៤-២៥</p>
			</td>
			<td colspan="2">
			<p>42</p>
			</td>
			<td colspan="2">
			<p>20</p>
			</td>
			<td colspan="2">
			<p>40</p>
			</td>
			<td colspan="2">
			<p>21</p>
			</td>
			<td colspan="2">
			<p>47</p>
			</td>
			<td colspan="2">
			<p>23</p>
			</td>
			<td colspan="2">
			<p>49</p>
			</td>
			<td colspan="2">
			<p>23</p>
			</td>
			<td colspan="2">
			<p>37</p>
			</td>
			<td colspan="2">
			<p>17</p>
			</td>
			<td colspan="2">
			<p>30</p>
			</td>
			<td colspan="2">
			<p>9</p>
			</td>
			<td colspan="2">
			<p>245</p>
			</td>
			<td colspan="2">
			<p>113</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ត្រូវបានឡើងថ្នាក់ ២៤-២៥</p>
			</td>
			<td colspan="2">
			<p>40</p>
			</td>
			<td colspan="2">
			<p>20</p>
			</td>
			<td colspan="2">
			<p>40</p>
			</td>
			<td colspan="2">
			<p>21</p>
			</td>
			<td colspan="2">
			<p>47</p>
			</td>
			<td colspan="2">
			<p>23</p>
			</td>
			<td colspan="2">
			<p>49</p>
			</td>
			<td colspan="2">
			<p>23</p>
			</td>
			<td colspan="2">
			<p>37</p>
			</td>
			<td colspan="2">
			<p>17</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>213</p>
			</td>
			<td colspan="2">
			<p>104</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ត្រូវបានឆ្លងភូមិសិក្សា២៤-២៥</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>30</p>
			</td>
			<td colspan="2">
			<p>9</p>
			</td>
			<td colspan="2">
			<p>30</p>
			</td>
			<td colspan="2">
			<p>9</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ផ្ទេរមកពីសាលាផ្សេង ២៥-២៦</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ផ្ទេរចេញទៅសាលាផ្សេង ២៥-២៦</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>មកពីសាលាផ្សេងដែលមិនគ្រប់កម្រិតថ្នាក់២៥-២៦</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>សិស្សអាហារូបករណ៍ឆ្នាំសិក្សាថ្មី</p>
			</td>
			<td colspan="2">
			<p>12</p>
			</td>
			<td colspan="2">
			<p>5</p>
			</td>
			<td colspan="2">
			<p>25</p>
			</td>
			<td colspan="2">
			<p>17</p>
			</td>
			<td colspan="2">
			<p>17</p>
			</td>
			<td colspan="2">
			<p>12</p>
			</td>
			<td colspan="2">
			<p>28</p>
			</td>
			<td colspan="2">
			<p>8</p>
			</td>
			<td colspan="2">
			<p>25</p>
			</td>
			<td colspan="2">
			<p>8</p>
			</td>
			<td colspan="2">
			<p>22</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>129</p>
			</td>
			<td colspan="2">
			<p>50</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="21">
			<p>២(ង)ចំនួនសិស្សចូលរៀនឡើងវិញ (សិស្សដែលបានបោះបង់ការសិក្សាហើយចូលរៀនវិញ)</p>
			</td>
		</tr>
		<tr>
			<td colspan="5" rowspan="2">
			<p>ចំនួនសិស្ស</p>
			</td>
			<td colspan="2">
			<p>ថ្នាក់ទី ១</p>
			</td>
			<td colspan="2">
			<p>ថ្នាក់ទី ២</p>
			</td>
			<td colspan="2">
			<p>ថ្នាក់ទី ៣</p>
			</td>
			<td colspan="2">
			<p>ថ្នាក់ទី ៤</p>
			</td>
			<td colspan="2">
			<p>ថ្នាក់ទី ៥</p>
			</td>
			<td colspan="2">
			<p>ថ្នាក់ទី ៦</p>
			</td>
			<td colspan="4">
			<p>សរុប</p>
			</td>
		</tr>
		<tr>
			<td>
			<p>សរុប</p>
			</td>
			<td>
			<p>ស្រី</p>
			</td>
			<td>
			<p>សរុប</p>
			</td>
			<td>
			<p>ស្រី</p>
			</td>
			<td>
			<p>សរុប</p>
			</td>
			<td>
			<p>ស្រី</p>
			</td>
			<td>
			<p>សរុប</p>
			</td>
			<td>
			<p>ស្រី</p>
			</td>
			<td>
			<p>សរុប</p>
			</td>
			<td>
			<p>ស្រី</p>
			</td>
			<td>
			<p>សរុប</p>
			</td>
			<td>
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
		</tr>
		<tr>
			<td colspan="5">
			<p>បានចូលរៀនឡើងវិញ</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="5">
			<p>ក្នុងកម្មវិធីសមមូល</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="5">
			<p>ក្នុងកម្មវិធីពន្លឿន</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td>
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="12">
			<p>២(ច)សិស្សថ្នាក់ទី១ដែលបានឆ្លងកាត់កម្មវិធីកុមារតូច</p>
			</td>
		</tr>
		<tr>
			<td colspan="4" rowspan="2">
			<p>ប្រភេទ</p>
			</td>
			<td colspan="4">
			<p>សិស្សថ្មី</p>
			</td>
			<td colspan="4">
			<p>សិស្សត្រួត</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
		</tr>
		<tr>
			<td colspan="4">
			<p>មត្តេយ្យរដ្ឋ</p>
			</td>
			<td colspan="2">
			<p>30</p>
			</td>
			<td colspan="2">
			<p>20</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="4">
			<p>មត្តេយ្យឯកជន</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="4">
			<p>មត្តេយ្យសហគមន័</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="4">
			<p>ការអប់រំតាមផ្ទះ/ខ្នងផ្ទះ</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="4">
			<p>កម្មវិធីត្រៀមថ្នាក់ទី១</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="4">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>30</p>
			</td>
			<td colspan="2">
			<p>20</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>២(ឆ)ចំនួនសិស្សថ្នាក់គួប តាមវេន(ក្នុងមួយជួរដេកត្រូវបំពេញតែមួយថ្នាក់គួប)</p>
			</td>
		</tr>
		<tr>
			<td colspan="8" rowspan="2">
			<p>ឈ្មោះគ្រូបង្រៀន</p>
			</td>
			<td colspan="2" rowspan="2">
			<p>វេន</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ១</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ២</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ៣</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ៤</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ៥</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ៦</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
		</tr>
		<tr>
			<td colspan="8">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="8">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="8">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="8">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>២(ជ)លទ្ធផលសិក្សារបស់សិស្សក្នុងឆ្នាំសិក្សា២០២៤-២០២៥</p>
			</td>
		</tr>
		<tr>
			<td colspan="6" rowspan="2">
			<p>លំដាប់និទ្ទេស</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ១</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ២</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ៣</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ៤</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ៥</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ទី ៦</p>
			</td>
			<td colspan="4">
			<p>សរុប</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ល្អប្រសើរ(A)</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ល្អណាស់(B)</p>
			</td>
			<td colspan="2">
			<p>4</p>
			</td>
			<td colspan="2">
			<p>2</p>
			</td>
			<td colspan="2">
			<p>5</p>
			</td>
			<td colspan="2">
			<p>4</p>
			</td>
			<td colspan="2">
			<p>4</p>
			</td>
			<td colspan="2">
			<p>3</p>
			</td>
			<td colspan="2">
			<p>5</p>
			</td>
			<td colspan="2">
			<p>4</p>
			</td>
			<td colspan="2">
			<p>2</p>
			</td>
			<td colspan="2">
			<p>2</p>
			</td>
			<td colspan="2">
			<p>4</p>
			</td>
			<td colspan="2">
			<p>3</p>
			</td>
			<td colspan="2">
			<p>24</p>
			</td>
			<td colspan="2">
			<p>18</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ល្អ (C)</p>
			</td>
			<td colspan="2">
			<p>15</p>
			</td>
			<td colspan="2">
			<p>9</p>
			</td>
			<td colspan="2">
			<p>9</p>
			</td>
			<td colspan="2">
			<p>5</p>
			</td>
			<td colspan="2">
			<p>19</p>
			</td>
			<td colspan="2">
			<p>10</p>
			</td>
			<td colspan="2">
			<p>8</p>
			</td>
			<td colspan="2">
			<p>4</p>
			</td>
			<td colspan="2">
			<p>11</p>
			</td>
			<td colspan="2">
			<p>9</p>
			</td>
			<td colspan="2">
			<p>14</p>
			</td>
			<td colspan="2">
			<p>4</p>
			</td>
			<td colspan="2">
			<p>76</p>
			</td>
			<td colspan="2">
			<p>41</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ល្អបង្គួរ(D)</p>
			</td>
			<td colspan="2">
			<p>9</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>15</p>
			</td>
			<td colspan="2">
			<p>8</p>
			</td>
			<td colspan="2">
			<p>6</p>
			</td>
			<td colspan="2">
			<p>21</p>
			</td>
			<td colspan="2">
			<p>10</p>
			</td>
			<td colspan="2">
			<p>18</p>
			</td>
			<td colspan="2">
			<p>4</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>5</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>49</p>
			</td>
			<td colspan="2">
			<p>50</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>មធ្យម(E)</p>
			</td>
			<td colspan="2">
			<p>11</p>
			</td>
			<td colspan="2">
			<p>5</p>
			</td>
			<td colspan="2">
			<p>10</p>
			</td>
			<td colspan="2">
			<p>3</p>
			</td>
			<td colspan="2">
			<p>8</p>
			</td>
			<td colspan="2">
			<p>2</p>
			</td>
			<td colspan="2">
			<p>15</p>
			</td>
			<td colspan="2">
			<p>4</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>8</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>53</p>
			</td>
			<td colspan="2">
			<p>16</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>មិនចាត់ថ្នាក់(F)</p>
			</td>
			<td colspan="2">
			<p>2</p>
			</td>
			<td colspan="2">
			<p>2</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>2</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>2</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>7</p>
			</td>
			<td colspan="2">
			<p>5</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>៣.បន្ទប់ និងថ្នាក់រៀន</p>
			</td>
		</tr>
		<tr>
			<td colspan="34">
			<p>៣.(ក)បន្ទប់រៀន</p>
			</td>
		</tr>
		<tr>
			<td colspan="34">
			<p>ចំនួនបន្ទប់ប្រើប្រាស់សម្រាប់បង្រៀន</p>
			</td>
		</tr>
		<tr>
			<td colspan="9">
			<p>ចំនួនបន្ទប់</p>
			</td>
			<td colspan="4">
			<p>ចំនួនបន្ទប់សរុប</p>
			</td>
			<td colspan="4">
			<p>មានអគ្គិសនី</p>
			</td>
			<td colspan="4">
			<p>មានអំពូល</p>
			</td>
			<td colspan="5">
			<p>មានកង្ហារ/ម៉ាស៊ីនត្រជាក់</p>
			</td>
			<td colspan="8">
			<p>មានបំពាក់ឧបករណ៍ទំនើប (LCD, Smart TV&hellip;)</p>
			</td>
		</tr>
		<tr>
			<td colspan="9">
			<p>សម្រាប់មត្តេយ្យសិក្សា</p>
			</td>
			<td colspan="4">
			<p>2</p>
			</td>
			<td colspan="4">
			<p>2</p>
			</td>
			<td colspan="4">
			<p>2</p>
			</td>
			<td colspan="5">
			<p>&nbsp;</p>
			</td>
			<td colspan="8">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="9">
			<p>សម្រាប់បឋមសិក្សា</p>
			</td>
			<td colspan="4">
			<p>10</p>
			</td>
			<td colspan="4">
			<p>10</p>
			</td>
			<td colspan="4">
			<p>7</p>
			</td>
			<td colspan="5">
			<p>&nbsp;</p>
			</td>
			<td colspan="8">
			<p>&nbsp;</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>៣.(ខ១)ចំនួនថ្នាក់រៀនមត្តេយ្យសិក្សា</p>
			</td>
		</tr>
		<tr>
			<td colspan="14">
			<p>ចំនួន</p>
			</td>
			<td colspan="4">
			<p>កម្រិតទាប</p>
			</td>
			<td colspan="4">
			<p>កម្រិតមធ្យម</p>
			</td>
			<td colspan="4">
			<p>កម្រិតខ្ពស់</p>
			</td>
			<td colspan="4">
			<p>ថ្នាក់ចម្រុះ</p>
			</td>
			<td colspan="4">
			<p>សរុបរួម</p>
			</td>
		</tr>
		<tr>
			<td colspan="14">
			<p>ថ្នាក់រៀន</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>1</p>
			</td>
			<td colspan="4">
			<p>1</p>
			</td>
			<td colspan="4">
			<p>2</p>
			</td>
		</tr>
		<tr>
			<td colspan="14">
			<p>បន្ទប់រៀន</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>1</p>
			</td>
			<td colspan="4">
			<p>1</p>
			</td>
			<td colspan="4">
			<p>2</p>
			</td>
		</tr>
		<tr>
			<td colspan="14">
			<p>គ្រូតាមថ្នាក់</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>1</p>
			</td>
			<td colspan="4">
			<p>1</p>
			</td>
			<td colspan="4">
			<p>2</p>
			</td>
		</tr>
		<tr>
			<td colspan="14">
			<p>ថ្នាក់រៀនអវត្តវិធីសាស្ត្ររៀនតាមរយៈការលេង</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>1</p>
			</td>
			<td colspan="4">
			<p>1</p>
			</td>
			<td colspan="4">
			<p>2</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>៤. បុគ្គលិកបង្រៀន និងបុគ្គលិកមិនបង្រៀន</p>
			</td>
		</tr>
		<tr>
			<td colspan="18">
			<p>៤.(ក)ចំនួនបុគ្គលិកអប់រំតាមប្រភេទក្របខ័ណ្ឌ(សណន លេខ ២៥៦)</p>
			</td>
			<td colspan="16">
			<p>៤.(ខ)ចំនួនបុគ្គលិកបង្រៀន/មិនបង្រៀនដែលទទួលមុខងារបន្ថែម</p>
			</td>
		</tr>
		<tr>
			<td colspan="2" rowspan="2">
			<p>ក្របខណ្ឌ</p>
			</td>
			<td colspan="8">
			<p>បុគ្គលិកបង្រៀន</p>
			</td>
			<td colspan="8">
			<p>បុគ្គលិកមិនបង្រៀន</p>
			</td>
			<td rowspan="18">
			<p>&nbsp;</p>
			</td>
			<td colspan="7" rowspan="2">
			<p>មុខងារ</p>
			</td>
			<td colspan="4">
			<p>ចំនួនបុគ្គលិក</p>
			</td>
			<td colspan="4">
			<p>បានបណ្តុះបណ្តាល</p>
			</td>
		</tr>
		<tr>
			<td colspan="4">
			<p>សរុប</p>
			</td>
			<td colspan="4">
			<p>ស្រី</p>
			</td>
			<td colspan="4">
			<p>សរុប</p>
			</td>
			<td colspan="4">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>ក</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="7">
			<p>លេខាធិការ</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>ខ</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="7">
			<p>បណ្ណារក្ស(បណ្ណាល័យស្តង់ដា)</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>គ</p>
			</td>
			<td colspan="4">
			<p>12</p>
			</td>
			<td colspan="4">
			<p>11</p>
			</td>
			<td colspan="4">
			<p>5</p>
			</td>
			<td colspan="4">
			<p>2</p>
			</td>
			<td colspan="7">
			<p>គ្រូទទូលបន្ទុកកីឡា</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="4">
			<p>12</p>
			</td>
			<td colspan="4">
			<p>11</p>
			</td>
			<td colspan="4">
			<p>5</p>
			</td>
			<td colspan="4">
			<p>2</p>
			</td>
			<td colspan="7">
			<p>គ្រូទទួលបន្ទុកICT</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="18">
			<p>៤.(គ)ចំនួនបុគ្គលិកបង្រៀនពីវេន និងថ្នាក់គួប</p>
			</td>
			<td colspan="7">
			<p>គ្រូទទូលបន្ទុកគណនេយ្យ និងបេឡា</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="6" rowspan="2">
			<p>បរិយាយ</p>
			</td>
			<td colspan="4">
			<p>បង្រៀនពីរវេន</p>
			</td>
			<td colspan="8">
			<p>បង្រៀនថ្នាក់គួប</p>
			</td>
			<td colspan="7">
			<p>គ្រូទទូលបន្ទុកបន្ទប់ពិសោធន៍</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="4">
			<p>សរុប</p>
			</td>
			<td colspan="4">
			<p>ស្រី</p>
			</td>
			<td colspan="7">
			<p>គ្រូទទូលបន្ទុកការងារយុវជន</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>គ្រូក្របខ័ណ្ឌ</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="7">
			<p>គ្រូបំណិនជីវិត</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>គ្រូក្របខ័ណ្ឌមកពីរកន្លែងផ្សេងកំពុងជួយបង្រៀន</p>
			</td>
			<td colspan="2">
			<p>សរុប៖</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>ស្រី៖</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="7">
			<p>គ្រូទទូលបន្ទុកសុខភាពសិក្សា</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>គ្រូជាប់កិច្ចសន្យាកំពុងជួយបង្រៀន</p>
			</td>
			<td colspan="2">
			<p>សរុប៖</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>ស្រី៖</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="7">
			<p>គ្រូទទូលបន្ទុកកិច្ចការពារកុមារ</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>ចំនួនបុគ្គលិកមានពិការភាព</p>
			</td>
			<td colspan="2">
			<p>សរុប៖</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>ស្រី៖</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="7">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>3</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>ចំនួនបុគ្គលិកបង្រៀនដែលខ្វះ</p>
			</td>
			<td colspan="2">
			<p>សរុប៖</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>ស្រី៖</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="15" rowspan="5">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>ចំនួនបុគ្គលិកបង្រៀនដែលលើស</p>
			</td>
			<td colspan="2">
			<p>សរុប៖</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>ស្រី៖</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>ចំនួនបុគ្គលិកដែលបានបណ្តុះបណ្តាលថ្នាក់បរិយាបន្ន</p>
			</td>
			<td colspan="2">
			<p>សរុប៖</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>ស្រី៖</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>ចំនួនបុគ្គលិកដែលបានធ្វើបច្ចុប្បន្នកម្មកិច្ចតែងការបង្រៀនត្រឹមត្រូវ និងអនុវត្តទៀងទាត់</p>
			</td>
			<td colspan="2">
			<p>សរុប៖</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>ស្រី៖</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>ចំនួនបុគ្គលិកបង្រៀននៅមត្តេយ្យសិក្សាដែលបានឆ្លងការបណ្តុះបណ្តាលពីសាលាគរុកោសល្យមត្តេយ្យមជ្ឈឹម</p>
			</td>
			<td colspan="2">
			<p>សរុប៖</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>ស្រី៖</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>៤.(ឃ)បុគ្គលិកបង្រៀនផ្សេងៗ ដែលបានទទួលការបណ្តុះបណ្តាល និងមិនបានទទួលការបណ្តុះបណ្តាល</p>
			</td>
		</tr>
		<tr>
			<td colspan="10" rowspan="2">
			<p>បរិយាយ</p>
			</td>
			<td colspan="8">
			<p>បានបណ្តុះបណ្តាល</p>
			</td>
			<td colspan="8">
			<p>មិនបានបណ្តុះបណ្តាល</p>
			</td>
			<td colspan="8">
			<p>បានបណ្តុះបណ្តាលប៉ុន្តែមិនបង្រៀន</p>
			</td>
		</tr>
		<tr>
			<td colspan="4">
			<p>សរុប</p>
			</td>
			<td colspan="4">
			<p>ស្រី</p>
			</td>
			<td colspan="4">
			<p>សរុប</p>
			</td>
			<td colspan="4">
			<p>ស្រី</p>
			</td>
			<td colspan="4">
			<p>សរុប</p>
			</td>
			<td colspan="4">
			<p>ស្រី</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>បុគ្គលិកក្របខ័ណ្ឌ</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>5</p>
			</td>
			<td colspan="4">
			<p>2</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>គ្រូបង្រៀនថ្នាក់គួប</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>គ្រូបង្រៀនជាប់កិច្ចសន្យា</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>បុគ្គលិកពិការភាព</p>
			</td>
			<td colspan="4">
			<p>1</p>
			</td>
			<td colspan="4">
			<p>1</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>បុគ្គលិកដែលមានវិធីសាស្ត្រដាក់ពិន័យតាមបែបវិជ្ជមាន</p>
			</td>
			<td colspan="4">
			<p>12</p>
			</td>
			<td colspan="4">
			<p>11</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>គ្រូបង្រៀនពហុភាសា(ភាសាជនជាតិភាគតិច)</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>&nbsp;</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>៤.(ង) កម្រិតវប្បធម៌របស់បុគ្គលិកក្របខ័ណ្ឌ និងវគ្គបណ្តុះបណ្តាលគរុកោសល្យ</p>
			</td>
		</tr>
		<tr>
			<td colspan="7" rowspan="2">
			<p>កម្រិតវប្បធម៌/ជំនាញ</p>
			</td>
			<td colspan="13">
			<p>បុគ្គលិកបង្រៀន</p>
			</td>
			<td colspan="14">
			<p>បុគ្គលិកមិនបង្រៀន</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="9">
			<p>មិនបានបណ្តុះបណ្តាលគរុកោសល្យ</p>
			</td>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
			<td colspan="10">
			<p>មិនបានបណ្តុះបណ្តាលគរុកោសល្យ</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>ក្នុងបឋមសិក្សា</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="9">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="10">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>វិញ្ញាបនបត្របឋមសិក្សា</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="9">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="10">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>ក្នុងមធ្យមសិក្សាបឋមភូមិ</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="9">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="10">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>សញ្ញាបត្រមធ្យមសិក្សាបឋមភូមិ</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="9">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="10">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>ក្នុងមធ្យមសិក្សាទុតិយភូមិ</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="9">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>3</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="10">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>សញ្ញាបត្រមធ្យមសិក្សាទុតិយភូមិ</p>
			</td>
			<td colspan="2">
			<p>6</p>
			</td>
			<td colspan="2">
			<p>5</p>
			</td>
			<td colspan="9">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="10">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>ក្នុងមហារវិទ្យាល័យ</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="9">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="10">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>បរិញ្ញាបត្រ</p>
			</td>
			<td colspan="2">
			<p>6</p>
			</td>
			<td colspan="2">
			<p>6</p>
			</td>
			<td colspan="9">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="10">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>បរិញ្ញាបត្រជាន់ខ្ពស់(អនុបណ្ឌិត)</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="9">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="10">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>សញ្ញាបត្របណ្ឌិត</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="9">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="10">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="7">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>12</p>
			</td>
			<td colspan="2">
			<p>11</p>
			</td>
			<td colspan="9">
			<p>0</p>
			</td>
			<td colspan="2">
			<p>5</p>
			</td>
			<td colspan="2">
			<p>2</p>
			</td>
			<td colspan="10">
			<p>0</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>៥.អគារ និងបរិក្ខា</p>
			</td>
		</tr>
		<tr>
			<td colspan="34">
			<p>៥.(ក)ស្ថានភាពអគារ បន្ទប់ និងបរិក្ខារ</p>
			</td>
		</tr>
		<tr>
			<td colspan="8" rowspan="2">
			<p>ប្រភេទសំណង់</p>
			</td>
			<td colspan="4">
			<p>ចំនួន</p>
			</td>
			<td colspan="10">
			<p>ចំនួនបន្ទប់ដែលគ្មាន</p>
			</td>
			<td colspan="6">
			<p>អគារសាងសង់ថ្មី</p>
			</td>
			<td colspan="6">
			<p>អគារជួសជុលថ្មី</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>អគារ</p>
			</td>
			<td colspan="2">
			<p>បន្ទប់</p>
			</td>
			<td colspan="2">
			<p>កម្រាលល្អ</p>
			</td>
			<td colspan="2">
			<p>ដំបូលល្អ</p>
			</td>
			<td colspan="2">
			<p>ជញ្ជាំងល្អ</p>
			</td>
			<td colspan="2">
			<p>បង្អួចល្អ</p>
			</td>
			<td colspan="2">
			<p>ទ្វារល្អ</p>
			</td>
			<td colspan="3">
			<p>ចំនួនអគារ</p>
			</td>
			<td colspan="3">
			<p>ចំនួនបន្ទប់</p>
			</td>
			<td colspan="3">
			<p>ចំនួនអគារ</p>
			</td>
			<td colspan="3">
			<p>ចំនួនបន្ទប់</p>
			</td>
		</tr>
		<tr>
			<td colspan="8">
			<p>ធ្វើអំពីឥដ្ឋ / ស៊ីម៉ង់ត៍ (ថ្ម)</p>
			</td>
			<td colspan="2">
			<p>4</p>
			</td>
			<td colspan="2">
			<p>15</p>
			</td>
			<td colspan="2">
			<p>3</p>
			</td>
			<td colspan="2">
			<p>3</p>
			</td>
			<td colspan="2">
			<p>3</p>
			</td>
			<td colspan="2">
			<p>3</p>
			</td>
			<td colspan="2">
			<p>3</p>
			</td>
			<td colspan="3">
			<p>1</p>
			</td>
			<td colspan="3">
			<p>2</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="8">
			<p>ធ្វើអំពីឈើ (ឈើ/ដែក)</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="8">
			<p>ធ្វើអំពីឫស្សី / កូនឈើ</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="8">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>4</p>
			</td>
			<td colspan="2">
			<p>15</p>
			</td>
			<td colspan="2">
			<p>3</p>
			</td>
			<td colspan="2">
			<p>3</p>
			</td>
			<td colspan="2">
			<p>3</p>
			</td>
			<td colspan="2">
			<p>3</p>
			</td>
			<td colspan="2">
			<p>3</p>
			</td>
			<td colspan="3">
			<p>1</p>
			</td>
			<td colspan="3">
			<p>2</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
			<td colspan="3">
			<p>0</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>បន្ទប់ដោយឡែកសម្រាប់</p>
			</td>
			<td colspan="6">
			<p>ស្ថានភាព</p>
			</td>
			<td colspan="2" rowspan="8">
			<p>&nbsp;</p>
			</td>
			<td colspan="10">
			<p>បន្ទប់ដោយឡែកសម្រាប់</p>
			</td>
			<td colspan="6">
			<p>ស្ថានភាព</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>ទីចាត់ការ</p>
			</td>
			<td colspan="6">
			<p>ល្អ</p>
			</td>
			<td colspan="10">
			<p>បន្ទប់ថែទាំសុខភាព</p>
			</td>
			<td colspan="6">
			<p>មិនទាន់មាន</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>បណ្ណាល័យ</p>
			</td>
			<td colspan="6">
			<p>ល្អ</p>
			</td>
			<td colspan="10">
			<p>អន្តេវាសិកដ្ឋាន</p>
			</td>
			<td colspan="6">
			<p>មិនទាន់មាន</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>បន្ទប់អប់រំបំណិនជីវិត</p>
			</td>
			<td colspan="6">
			<p>មិនទាន់មាន</p>
			</td>
			<td colspan="10">
			<p>បន្ទប់/ផ្ទះគ្រូស្នាក់នៅ</p>
			</td>
			<td colspan="6">
			<p>មិនទាន់មាន</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>មជ្ឍមណ្ឌលធនធាន</p>
			</td>
			<td colspan="6">
			<p>មិនទាន់មាន</p>
			</td>
			<td colspan="10">
			<p>រោងបាយ</p>
			</td>
			<td colspan="6">
			<p>មិនទាន់មាន</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>បន្ទប់រោងជាង</p>
			</td>
			<td colspan="6">
			<p>មិនទាន់មាន</p>
			</td>
			<td colspan="10">
			<p>បន្ទប់ផ្សេងទៀត</p>
			</td>
			<td colspan="6">
			<p>មិនទាន់មាន</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>បន្ទប់កុំព្យូទ័រ</p>
			</td>
			<td colspan="6">
			<p>មិនទាន់មាន</p>
			</td>
			<td colspan="10">
			<p>ទីជម្រាលសម្រាប់កុមារ/គ្រូពិការ</p>
			</td>
			<td colspan="6">
			<p>មិនទាន់មាន</p>
			</td>
		</tr>
		<tr>
			<td colspan="16">
			<p>&nbsp;</p>
			</td>
			<td colspan="10">
			<p>សួនកសិកម្ម(ជីវចម្រុះ)</p>
			</td>
			<td colspan="6">
			<p>មិនទាន់មាន</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="14">
			<p>៥.(ខ)ចំនួនបរិក្ខារ</p>
			</td>
		</tr>
		<tr>
			<td colspan="11">
			<p>បរិក្ខារ</p>
			</td>
			<td colspan="3">
			<p>ចំនួន</p>
			</td>
		</tr>
		<tr>
			<td colspan="11">
			<p>តុសិស្សអង្គុយម្នាក់ៗ</p>
			</td>
			<td colspan="3">
			<p>20</p>
			</td>
		</tr>
		<tr>
			<td colspan="11">
			<p>តុសិស្សអង្គុយពីរនាក់</p>
			</td>
			<td colspan="3">
			<p>200</p>
			</td>
		</tr>
		<tr>
			<td colspan="11">
			<p>កៅអី/កៅអីវែងសម្រាប់សិស្សអង្គុយច្រើននាក់</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="11">
			<p>កៅអីសម្រាប់គ្រូ</p>
			</td>
			<td colspan="3">
			<p>9</p>
			</td>
		</tr>
		<tr>
			<td colspan="11">
			<p>តុសម្រាប់គ្រូ</p>
			</td>
			<td colspan="3">
			<p>9</p>
			</td>
		</tr>
		<tr>
			<td colspan="11">
			<p>ក្តារខៀន</p>
			</td>
			<td colspan="3">
			<p>17</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="19">
			<p>៥(គ) ផ្ទៃដីសាលារៀន</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>ប្រភេទ</p>
			</td>
			<td colspan="3">
			<p>បណ្តោយ</p>
			</td>
			<td colspan="3">
			<p>ទទឹង</p>
			</td>
			<td colspan="3">
			<p>(គិតជាម២)</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>ផ្ទៃដីសរុបជាកម្មសិទ្ធរបស់សាលារៀន</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>14,400</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>-ទីធ្លាសាលារៀន(សម្រាប់រត់លេង និងកីឡា)</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>3,900</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>-ផ្ទៃក្រឡាបន្ទប់រៀន</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>630</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>-ផ្ទៃដីនៅសល់សម្រាប់សាងសង់</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>9,770</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>-ផ្ទៃក្រឡាសួនច្បារ ឬសួនបន្លែ</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>100</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>៥.(ឃ)កន្លែងលាងដៃ</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>បរិយាយ</p>
			</td>
			<td colspan="11">
			<p>អត្ថិភាព</p>
			</td>
			<td colspan="13">
			<p>ស្ថានភាពទូទៅ</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>កន្លែងលាងសម្អាតដៃ (អាចប្រើបានបន្ទាប់ពីប្រើបង្គន់)</p>
			</td>
			<td colspan="11">
			<p>មាន</p>
			</td>
			<td colspan="13">
			<p>មានសាប៊ូនិងទឹកថ្ងៃនេះ</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>កន្លែងលាង សម្អាតដៃ</p>
			</td>
			<td colspan="11">
			<p>មាន(សម្រាប់លាងជាក្រុម)</p>
			</td>
			<td colspan="13">
			<p>មានសាប៊ូនិងទឹកថ្ងៃនេះ</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>ការគ្រប់គ្រងអនាម័យ ពេលមានរដូវ</p>
			</td>
			<td colspan="11">
			<p>មាន</p>
			</td>
			<td colspan="13">
			<p>មានធុងសំរាមនៅបង្គន់ស្ត្រី</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>៥.(ង)បង្គន់អនាម័យ(គិតជាបន្ទប់)</p>
			</td>
		</tr>
		<tr>
			<td colspan="10" rowspan="2">
			<p>ប្រភេទ</p>
			</td>
			<td colspan="24">
			<p>បង្គន់</p>
			</td>
		</tr>
		<tr>
			<td colspan="3">
			<p>គ្រូប្រុស</p>
			</td>
			<td colspan="3">
			<p>គ្រូស្រី</p>
			</td>
			<td colspan="3">
			<p>គ្រូរួម</p>
			</td>
			<td colspan="3">
			<p>សិស្សប្រុស</p>
			</td>
			<td colspan="3">
			<p>សិស្សស្រី</p>
			</td>
			<td colspan="3">
			<p>សិស្សរួម</p>
			</td>
			<td colspan="3">
			<p>រួម</p>
			</td>
			<td colspan="3">
			<p>សិស្សពិការ</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>ចំនួនបង្គន់អនាម័យចាក់ទឹក/ចុចបង្ហូរទឹកសរុប</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>5</p>
			</td>
			<td colspan="3">
			<p>4</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>1</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>ចំនួនបង្គន់អនាម័យចាក់ទឹក/ ចុចបង្ហូរទឹកដែលអាចប្រើបានមានទឹក</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>6</p>
			</td>
			<td colspan="3">
			<p>4</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>1</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>ចំនួនបង្គន់អនាម័យផ្សេងទៀត</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>ចំនួនកន្លែងនោមសិស្សប្រុស</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>&nbsp;</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>៥.(ច)ប្រភពទឹកសម្រាប់ប្រើប្រាស់</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>ប្រភពទឹកចម្បង</p>
			</td>
			<td colspan="5">
			<p>ប្រើសម្រាប់ផឹក</p>
			</td>
			<td colspan="11">
			<p>អាចរកបាននៅថ្ងៃនេះនៅបរិវេណសាលារៀន</p>
			</td>
			<td colspan="8">
			<p>ប្រើសម្រាប់គោលបំណងផ្សេង</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>បណ្តាញទុយោ</p>
			</td>
			<td colspan="5">
			<p>មាន</p>
			</td>
			<td colspan="11">
			<p>អាច</p>
			</td>
			<td colspan="8">
			<p>បាទ</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>អណ្តូងស្នប់/អណ្តូងខួង</p>
			</td>
			<td colspan="5">
			<p>មាន</p>
			</td>
			<td colspan="11">
			<p>អាច</p>
			</td>
			<td colspan="8">
			<p>បាទ</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>អណ្តូងជីក/ទឹកផុសចេញពីក្រោមមានការការពារ</p>
			</td>
			<td colspan="5">
			<p>មិនមាន</p>
			</td>
			<td colspan="11">
			<p>មិនអាច</p>
			</td>
			<td colspan="8">
			<p>ទេ</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>ទឹកភ្លៀង</p>
			</td>
			<td colspan="5">
			<p>មាន</p>
			</td>
			<td colspan="11">
			<p>អាច</p>
			</td>
			<td colspan="8">
			<p>បាទ</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>ទឹកពិសាដប</p>
			</td>
			<td colspan="5">
			<p>មាន</p>
			</td>
			<td colspan="11">
			<p>អាច</p>
			</td>
			<td colspan="8">
			<p>បាទ</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>ទឹកទិញដឹកដោយឡានស៊ីទែន/រទេះរុញ</p>
			</td>
			<td colspan="5">
			<p>មិនមាន</p>
			</td>
			<td colspan="11">
			<p>មិនអាច</p>
			</td>
			<td colspan="8">
			<p>ទេ</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>អណ្តូងជីក/ទឹកផុសចេញពីក្រោមមិនមានការការពារ</p>
			</td>
			<td colspan="5">
			<p>មិនមាន</p>
			</td>
			<td colspan="11">
			<p>មិនអាច</p>
			</td>
			<td colspan="8">
			<p>ទេ</p>
			</td>
		</tr>
		<tr>
			<td colspan="10">
			<p>ទឹកបឹង/ស្រះ/ទន្លេ/ព្រែក/អូរ/ស្ទឹង</p>
			</td>
			<td colspan="5">
			<p>មិនមាន</p>
			</td>
			<td colspan="11">
			<p>មិនអាច</p>
			</td>
			<td colspan="8">
			<p>ទេ</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>៥.(ឆ)សម្ភារបរិក្ខា</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>អគ្គិសនី</p>
			</td>
			<td colspan="3">
			<p>អត្ថិភាព</p>
			</td>
			<td colspan="9">
			<p>កុំព្យូទ័រ</p>
			</td>
			<td colspan="2">
			<p>ចំនួន</p>
			</td>
			<td colspan="4">
			<p>សម្ភារបរិក្ខា</p>
			</td>
			<td colspan="2">
			<p>ចំនួន</p>
			</td>
			<td colspan="6">
			<p>សម្ភារបរិក្ខា</p>
			</td>
			<td colspan="2">
			<p>ចំនួន</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>បណ្តាញអគ្គិសនី</p>
			</td>
			<td colspan="3">
			<p>ឯកជន</p>
			</td>
			<td colspan="9">
			<p>កុំព្យូទ័រសរុប</p>
			</td>
			<td colspan="2">
			<p>2</p>
			</td>
			<td colspan="4">
			<p>ម៉ាស៊ីនបោះពុម្ភ</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="6">
			<p>ម៉ាស៊ីនបញ្ចាំងLCD</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ថាមពលប្រើពន្លឺព្រះអាទិត្យ</p>
			</td>
			<td colspan="3">
			<p>គ្មាន</p>
			</td>
			<td colspan="9">
			<p>កុំព្យូទ័រប្រើប្រាស់បាន</p>
			</td>
			<td colspan="2">
			<p>2</p>
			</td>
			<td colspan="4">
			<p>ម៉ាស៊ីនថតចម្លង</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="6">
			<p>ផ្ទាំងក្រណាត់បញ្ចាំងស្លាយ</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="6">
			<p>ម៉ាស៊ីនភ្លើង</p>
			</td>
			<td colspan="3">
			<p>គ្មាន</p>
			</td>
			<td colspan="9">
			<p>កុំព្យូទ័រប្រើប្រាស់សម្រាប់ការិយាល័យ</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="4">
			<p>ម៉ាស៊ីនscanner</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="6">
			<p>ប្រអប់សង្គ្រោះបឋម</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
		</tr>
		<tr>
			<td colspan="9">
			<p>&nbsp;</p>
			</td>
			<td colspan="9">
			<p>កុំព្យូទ័រប្រើប្រាស់សម្រាប់ការបង្រៀន និងរៀន</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="4">
			<p>ម៉ាស៊ីនដេរ</p>
			</td>
			<td colspan="2">
			<p>0</p>
			</td>
			<td colspan="6">
			<p>ខ្សែរបណ្តាញInternet</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>៥.(ជ)ខ្សែសេវា អ៊ីនធើណេតសម្រាប់សាលារៀន</p>
			</td>
		</tr>
		<tr>
			<td colspan="18">
			<p>សេវា Internet</p>
			</td>
			<td colspan="8">
			<p>ស្ថានភាព</p>
			</td>
			<td colspan="8">
			<p>ល្បឿន(Internet Speed)</p>
			</td>
		</tr>
		<tr>
			<td colspan="18">
			<p>សេវា Internet WIFI</p>
			</td>
			<td colspan="8">
			<p>មាន</p>
			</td>
			<td colspan="8">
			<p>មធ្យម</p>
			</td>
		</tr>
		<tr>
			<td colspan="18">
			<p>Mobile Phone Hotspot</p>
			</td>
			<td colspan="8">
			<p>មាន</p>
			</td>
			<td colspan="8">
			<p>មធ្យម</p>
			</td>
		</tr>
		<tr>
			<td colspan="18">
			<p>អ៊ីនធើណេតតាមបន្ទប់សម្រាប់ការរៀន និងបង្រៀន</p>
			</td>
			<td colspan="8">
			<p>មាន</p>
			</td>
			<td colspan="8">
			<p>មធ្យម</p>
			</td>
		</tr>
		<tr>
			<td colspan="18">
			<p>អ៊ីនធើណេតសម្រាប់ការងាររដ្ឋបាលគ្រូ</p>
			</td>
			<td colspan="8">
			<p>មាន</p>
			</td>
			<td colspan="8">
			<p>មធ្យម</p>
			</td>
		</tr>
		<tr>
			<td colspan="18">
			<p>អ៊ីនធើណេតសម្រាប់បណ្ណាល័យ និងបន្ទប់ពិសោធន៍</p>
			</td>
			<td colspan="8">
			<p>មាន</p>
			</td>
			<td colspan="8">
			<p>មធ្យម</p>
			</td>
		</tr>
		<tr>
			<td colspan="14">
			<p>ប្រភេទសេវាអ៊ីនធើណេត</p>
			</td>
			<td colspan="20">
			<p>Fixed Wrieless</p>
			</td>
		</tr>
		<tr>
			<td colspan="14">
			<p>អ្នកទទួលបន្ទុកគ្រប់គ្រងសេវាអ៊ីនធើណេត</p>
			</td>
			<td colspan="20">
			<p>រដ្ឋបាលសាលារៀន</p>
			</td>
		</tr>
		<tr>
			<td colspan="14">
			<p>អគ្គិសនីសម្រាប់ការរៀន និងបង្រៀន</p>
			</td>
			<td colspan="20">
			<p>គ្មាន</p>
			</td>
		</tr>
		<tr>
			<td colspan="14">
			<p>ថ្លៃចំណាយអគ្គិសនីប្រចាំខែ</p>
			</td>
			<td colspan="20">
			<p>50,000 រៀល</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>៥.(ឈ)ល្បែង និងសម្ភារសិក្សា(សម្រាប់មត្តេយ្យសិក្សា)</p>
			</td>
		</tr>
		<tr>
			<td colspan="14">
			<p>ប្រភេទ</p>
			</td>
			<td colspan="5">
			<p>កម្រិតទាប</p>
			</td>
			<td colspan="5">
			<p>កម្រិតមធ្យម</p>
			</td>
			<td colspan="5">
			<p>កម្រិតខ្ពស់</p>
			</td>
			<td colspan="5">
			<p>សរុបរួម</p>
			</td>
		</tr>
		<tr>
			<td colspan="14">
			<p>ឯកសារបង្រៀន</p>
			</td>
			<td colspan="5">
			<p>&nbsp;</p>
			</td>
			<td colspan="5">
			<p>មាន</p>
			</td>
			<td colspan="5">
			<p>មាន</p>
			</td>
			<td colspan="5">
			<p>មាន</p>
			</td>
		</tr>
		<tr>
			<td colspan="14">
			<p>សម្ភារបង្រៀន</p>
			</td>
			<td colspan="5">
			<p>&nbsp;</p>
			</td>
			<td colspan="5">
			<p>មាន</p>
			</td>
			<td colspan="5">
			<p>មាន</p>
			</td>
			<td colspan="5">
			<p>មាន</p>
			</td>
		</tr>
		<tr>
			<td colspan="14">
			<p>ល្បែងលេងក្នុងថ្នាក់</p>
			</td>
			<td colspan="5">
			<p>&nbsp;</p>
			</td>
			<td colspan="5">
			<p>មាន</p>
			</td>
			<td colspan="5">
			<p>មាន</p>
			</td>
			<td colspan="5">
			<p>មាន</p>
			</td>
		</tr>
		<tr>
			<td colspan="14">
			<p>សម្ភារបង្រៀន និងរៀនមានគ្រប់គ្រាន់</p>
			</td>
			<td colspan="5">
			<p>&nbsp;</p>
			</td>
			<td colspan="5">
			<p>មាន</p>
			</td>
			<td colspan="5">
			<p>មាន</p>
			</td>
			<td colspan="5">
			<p>មាន</p>
			</td>
		</tr>
		<tr>
			<td colspan="14">
			<p>កម្មវិធីទស្សនកិច្ចសិក្សាកុមារអាយុ៥ឆ្នាំ</p>
			</td>
			<td colspan="5">
			<p>&nbsp;</p>
			</td>
			<td colspan="5">
			<p>គ្មាន</p>
			</td>
			<td colspan="5">
			<p>គ្មាន</p>
			</td>
			<td colspan="5">
			<p>គ្មាន</p>
			</td>
		</tr>
		<tr>
			<td colspan="14">
			<p>ឯកសារសកម្មភាពសិស្សម្នាក់ៗ</p>
			</td>
			<td colspan="5">
			<p>&nbsp;</p>
			</td>
			<td colspan="5">
			<p>គ្មាន</p>
			</td>
			<td colspan="5">
			<p>គ្មាន</p>
			</td>
			<td colspan="5">
			<p>គ្មាន</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>៥.(ញ)សម្ភារកីឡា(សម្រាប់ឋមសិក្សា)</p>
			</td>
		</tr>
		<tr>
			<td colspan="4">
			<p>ប្រភេទ</p>
			</td>
			<td colspan="4">
			<p>ទីធ្លា</p>
			</td>
			<td colspan="4">
			<p>សម្ភារៈ</p>
			</td>
			<td colspan="4">
			<p>ក្រុមកីឡា</p>
			</td>
			<td colspan="2" rowspan="5">
			<p>&nbsp;</p>
			</td>
			<td colspan="4">
			<p>ប្រភេទ</p>
			</td>
			<td colspan="4">
			<p>ទីធ្លា</p>
			</td>
			<td colspan="4">
			<p>សម្ភារៈ</p>
			</td>
			<td colspan="4">
			<p>ក្រុមកីឡា</p>
			</td>
		</tr>
		<tr>
			<td colspan="4">
			<p>បាល់ទះ</p>
			</td>
			<td colspan="4">
			<p>មាន</p>
			</td>
			<td colspan="4">
			<p>មាន</p>
			</td>
			<td colspan="4">
			<p>គ្មាន</p>
			</td>
			<td colspan="4">
			<p>ចោលដុំដែក</p>
			</td>
			<td colspan="4">
			<p>គ្មាន</p>
			</td>
			<td colspan="4">
			<p>គ្មាន</p>
			</td>
			<td colspan="4">
			<p>គ្មាន</p>
			</td>
		</tr>
		<tr>
			<td colspan="4">
			<p>បាល់ទាត់</p>
			</td>
			<td colspan="4">
			<p>មាន</p>
			</td>
			<td colspan="4">
			<p>មាន</p>
			</td>
			<td colspan="4">
			<p>មាន</p>
			</td>
			<td colspan="4">
			<p>លោតកម្ពស់</p>
			</td>
			<td colspan="4">
			<p>គ្មាន</p>
			</td>
			<td colspan="4">
			<p>គ្មាន</p>
			</td>
			<td colspan="4">
			<p>គ្មាន</p>
			</td>
		</tr>
		<tr>
			<td colspan="4">
			<p>បាល់បោះ</p>
			</td>
			<td colspan="4">
			<p>មាន</p>
			</td>
			<td colspan="4">
			<p>គ្មាន</p>
			</td>
			<td colspan="4">
			<p>គ្មាន</p>
			</td>
			<td colspan="4">
			<p>លោកចម្ងាយ</p>
			</td>
			<td colspan="4">
			<p>គ្មាន</p>
			</td>
			<td colspan="4">
			<p>គ្មាន</p>
			</td>
			<td colspan="4">
			<p>គ្មាន</p>
			</td>
		</tr>
		<tr>
			<td colspan="4">
			<p>ឡើងខ្សែពួរ</p>
			</td>
			<td colspan="4">
			<p>គ្មាន</p>
			</td>
			<td colspan="4">
			<p>គ្មាន</p>
			</td>
			<td colspan="4">
			<p>គ្មាន</p>
			</td>
			<td colspan="4">
			<p>រត់ចម្ងាយ</p>
			</td>
			<td colspan="4">
			<p>គ្មាន</p>
			</td>
			<td colspan="4">
			<p>គ្មាន</p>
			</td>
			<td colspan="4">
			<p>គ្មាន</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>៦.ការចូលរួមរបស់សហគមន៍</p>
			</td>
		</tr>
		<tr>
			<td colspan="34">
			<p>៦.(ក)គណៈកម្មការគ្រប់គ្រងសាលារៀន</p>
			</td>
		</tr>
		<tr>
			<td colspan="14" rowspan="2">
			<p>បរិយាយ</p>
			</td>
			<td colspan="3" rowspan="2">
			<p>អត្ថិភាព</p>
			</td>
			<td colspan="4">
			<p>ចំនួនសមាជិក</p>
			</td>
			<td colspan="13" rowspan="2">
			<p>សរុបចំនួនដងនៃការ</p>
			</td>
		</tr>
		<tr>
			<td colspan="2">
			<p>សរុប</p>
			</td>
			<td colspan="2">
			<p>ស្រី</p>
			</td>
		</tr>
		<tr>
			<td colspan="14">
			<p>ចំនួនគណៈកម្មការគ្រប់គ្រងសាលារៀន</p>
			</td>
			<td colspan="3">
			<p>មាន</p>
			</td>
			<td colspan="2">
			<p>11</p>
			</td>
			<td colspan="2">
			<p>2</p>
			</td>
			<td colspan="11">
			<p>ប្រជុំឆ្នាំកន្លង</p>
			</td>
			<td colspan="2">
			<p>2</p>
			</td>
		</tr>
		<tr>
			<td colspan="14">
			<p>សហគមន៍បានចូលរួមជួយគាំទ្រ មូលនិធិដំណើរការសាលារៀន</p>
			</td>
			<td colspan="3">
			<p>គ្មាន</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="11">
			<p>ចូលរួមគាំទ្រ</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="14">
			<p>ចំនួននាយក នាយករងបានទទួលការហ្វឹកហាត់កម្មវិធីគ្រប់គ្រងសាលារៀនគំរូ</p>
			</td>
			<td colspan="3">
			<p>មាន</p>
			</td>
			<td colspan="2">
			<p>2</p>
			</td>
			<td colspan="2">
			<p>1</p>
			</td>
			<td colspan="11">
			<p>ចូលរួហ្វឹកហាត់</p>
			</td>
			<td colspan="2">
			<p>2</p>
			</td>
		</tr>
		<tr>
			<td colspan="14">
			<p>សាលារៀនបានទទួលការចុះពិនិត្យតាមដាន និងផ្តល់ការគាំទ្រ ពីថ្នាក់ជាតិ</p>
			</td>
			<td colspan="3">
			<p>មាន</p>
			</td>
			<td colspan="2">
			<p>5</p>
			</td>
			<td colspan="2">
			<p>2</p>
			</td>
			<td colspan="11">
			<p>ពិនិត្យតាមដាន និងគាំទ្រពីថ្នាក់ជាតិ</p>
			</td>
			<td colspan="2">
			<p>4</p>
			</td>
		</tr>
		<tr>
			<td colspan="14">
			<p>សាលារៀនបានទទួលការចុះពិនិត្យតាមដាន និងផ្តល់ការគាំទ្រពីថ្នាក់ក្រោមជាតិ</p>
			</td>
			<td colspan="3">
			<p>គ្មាន</p>
			</td> 
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
			<td colspan="11">
			<p>ពិនិត្យតាមដាន និងគាំទ្រពីថ្នាក់ក្រោមជាតិ</p>
			</td>
			<td colspan="2">
			<p>&nbsp;</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="21">
			<p>បរិយាយ</p>
			</td>
			<td colspan="13">
			<p>អត្ថិភាព</p>
			</td>
		</tr>
		<tr>
			<td colspan="21">
			<p>ការរៀបចំផែនការសាលារៀនបានត្រឹមត្រូវ</p>
			</td>
			<td colspan="13">
			<p>មាន</p>
			</td>
		</tr>
		<tr>
			<td colspan="21">
			<p>សាលារៀនមានផែនការយុទ្ធសាស្ត្រអភិវឌ្ឍ ៥ឆ្នាំ</p>
			</td>
			<td colspan="13">
			<p>មាន</p>
			</td>
		</tr>
		<tr>
			<td colspan="21">
			<p>សាលារៀនរៀបចំផែនការយុទ្ធសាស្ត្រថវិកា ៣ឆ្នាំ</p>
			</td>
			<td colspan="13">
			<p>មាន</p>
			</td>
		</tr>
		<tr>
			<td colspan="21">
			<p>សាលារៀនរៀបចំផែនកាប្រតិបត្តិប្រចាំឆ្នាំ និងផែនការថវិកាប្រចាំឆ្នាំ</p>
			</td>
			<td colspan="13">
			<p>មាន</p>
			</td>
		</tr>
	</tbody>
</table>

<p>&nbsp;</p>
<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="34">
			<p>៦.(ខ)ហិរញ្ញប្បទានក្នុងឆ្នាំ ២០២៥</p>
			</td>
		</tr>
		<tr>
			<td colspan="11">
			<p>ប្រភេទ</p>
			</td>
			<td colspan="5">
			<p>ទទួលជាប្រាក់រៀល</p>
			</td>
			<td rowspan="9">
			<p>&nbsp;</p>
			</td>
			<td colspan="17">
			<p>៧.ការចែកចាយថ្នាំព្រូនក្នុងឆ្នាំ ២០២៤-២០២៥</p>
			</td>
		</tr>
		<tr>
			<td colspan="11">
			<p>ថវិការ PB 2025</p>
			</td>
			<td colspan="5">
			<p>12,052,800 រៀល</p>
			</td>
			<td colspan="5" rowspan="2">
			<p>បានទទួលថ្នាំព្រូន</p>
			</td>
			<td colspan="6">
			<p>ប៉ុន្មានគ្រាប់ក្នុងមួយលើក</p>
			</td>
			<td colspan="6">
			<p>ចំនួនសិស្សបានទទួល</p>
			</td>
		</tr>
		<tr>
			<td colspan="11">
			<p>ថវិការដ្ឋាភិបាលសម្រាប់សាងសង់</p>
			</td>
			<td colspan="5">
			<p>&nbsp;</p>
			</td>
			<td colspan="3">
			<p>លើកទី១</p>
			</td>
			<td colspan="3">
			<p>លើកទី២</p>
			</td>
			<td colspan="3">
			<p>លើកទី១</p>
			</td>
			<td colspan="3">
			<p>លើកទី២</p>
			</td>
		</tr>
		<tr>
			<td colspan="11">
			<p>ចំណូលផលិតកម្មសាលា</p>
			</td>
			<td colspan="5">
			<p>&nbsp;</p>
			</td>
			<td colspan="5">
			<p>បាន</p>
			</td>
			<td colspan="3">
			<p>250 គ្រាប់</p>
			</td>
			<td colspan="3">
			<p>250 គ្រាប់</p>
			</td>
			<td colspan="3">
			<p>250 នាក់</p>
			</td>
			<td colspan="3">
			<p>250 នាក់</p>
			</td>
		</tr>
		<tr>
			<td colspan="11">
			<p>អំណោយពីសហគមន៍/សប្បុរសជនក្នុងប្រទេស</p>
			</td>
			<td colspan="5">
			<p>&nbsp;</p>
			</td>
			<td colspan="17" rowspan="5">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="11">
			<p>អំណោយពីសប្បុរសជនក្រៅប្រទេស</p>
			</td>
			<td colspan="5">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="11">
			<p>អំណោយពីអង្គការជាតិ និងអង្គការមិនមែនរដ្ឋាភិបាល</p>
			</td>
			<td colspan="5">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="11">
			<p>បុណ្យផ្សេងៗ</p>
			</td>
			<td colspan="5">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="11">
			<p>សរុប</p>
			</td>
			<td colspan="5">
			<p>12,052,800 រៀល</p>
			</td>
		</tr>
	</tbody>
</table>


    <script>
        // Initial data
        const initialData = {
            students: [
                { grade: 'ថ្នាក់ទី១', newTotal: 30, newFemale: 14, promoted: 0, promotedFemale: 0, repeat: 0, repeatFemale: 0 },
                { grade: 'ថ្នាក់ទី២', newTotal: 0, newFemale: 0, promoted: 42, promotedFemale: 22, repeat: 0, repeatFemale: 0 },
                { grade: 'ថ្នាក់ទី៣', newTotal: 0, newFemale: 0, promoted: 41, promotedFemale: 22, repeat: 0, repeatFemale: 0 },
                { grade: 'ថ្នាក់ទី៤', newTotal: 0, newFemale: 0, promoted: 49, promotedFemale: 23, repeat: 0, repeatFemale: 0 },
                { grade: 'ថ្នាក់ទី៥', newTotal: 0, newFemale: 0, promoted: 50, promotedFemale: 23, repeat: 0, repeatFemale: 0 },
                { grade: 'ថ្នាក់ទី៦', newTotal: 0, newFemale: 0, promoted: 35, promotedFemale: 17, repeat: 0, repeatFemale: 0 }
            ],
            teachers: [
                { category: 'ក្របខ័ណ្ឌ ក', teachingTotal: 0, teachingFemale: 0, nonTeachingTotal: 0, nonTeachingFemale: 0 },
                { category: 'ក្របខ័ណ្ឌ ខ', teachingTotal: 0, teachingFemale: 0, nonTeachingTotal: 0, nonTeachingFemale: 0 },
                { category: 'ក្របខ័ណ្ឌ គ', teachingTotal: 12, teachingFemale: 11, nonTeachingTotal: 5, nonTeachingFemale: 2 }
            ],
            facilities: [
                { type: 'បន្ទប់រៀនបឋមសិក្សា', quantity: 10, status: 'ល្អ' },
                { type: 'បន្ទប់រៀនមត្តេយ្យ', quantity: 2, status: 'ល្អ' },
                { type: 'បណ្ណាល័យ', quantity: 1, status: 'ល្អ' },
                { type: 'ទីធ្លាសាលារៀន', quantity: 1, status: 'ល្អ' },
                { type: 'បង្គន់សិស្សប្រុស', quantity: 5, status: 'ល្អ' },
                { type: 'បង្គន់សិស្សស្រី', quantity: 4, status: 'ល្អ' }
            ]
        };

        // Load data from storage or use initial data
        function loadData() {
            try {
                const saved = window.localStorage.getItem('schoolData');
                return saved ? JSON.parse(saved) : initialData;
            } catch (e) {
                return initialData;
            }
        }

        let data = loadData();

        // Render tables
        function renderTables() {
            renderStudentTable();
            renderTeacherTable();
            renderFacilityTable();
        }

        function renderStudentTable() {
            const tbody = document.getElementById('studentTableBody');
            tbody.innerHTML = '';
            
            data.students.forEach((row, idx) => {
                const total = row.newTotal + row.promoted;
                const totalFemale = row.newFemale + row.promotedFemale;
                
                tbody.innerHTML += `
                    <tr>
                        <td><strong>${row.grade}</strong></td>
                        <td><input type="number" value="${row.newTotal}" onchange="updateStudent(${idx}, 'newTotal', this.value)"></td>
                        <td><input type="number" value="${row.newFemale}" onchange="updateStudent(${idx}, 'newFemale', this.value)"></td>
                        <td><input type="number" value="${row.promoted}" onchange="updateStudent(${idx}, 'promoted', this.value)"></td>
                        <td><input type="number" value="${row.promotedFemale}" onchange="updateStudent(${idx}, 'promotedFemale', this.value)"></td>
                        <td><input type="number" value="${row.repeat}" onchange="updateStudent(${idx}, 'repeat', this.value)"></td>
                        <td><input type="number" value="${row.repeatFemale}" onchange="updateStudent(${idx}, 'repeatFemale', this.value)"></td>
                        <td><strong>${total}</strong></td>
                        <td><strong>${totalFemale}</strong></td>
                    </tr>
                `;
            });

            // Add total row
            const totals = calculateStudentTotals();
            tbody.innerHTML += `
                <tr style="background: #e3f2fd; font-weight: bold;">
                    <td>សរុប</td>
                    <td>${totals.newTotal}</td>
                    <td>${totals.newFemale}</td>
                    <td>${totals.promoted}</td>
                    <td>${totals.promotedFemale}</td>
                    <td>${totals.repeat}</td>
                    <td>${totals.repeatFemale}</td>
                    <td>${totals.total}</td>
                    <td>${totals.totalFemale}</td>
                </tr>
            `;
        }

        function renderTeacherTable() {
            const tbody = document.getElementById('teacherTableBody');
            tbody.innerHTML = '';
            
            data.teachers.forEach((row, idx) => {
                tbody.innerHTML += `
                    <tr>
                        <td><strong>${row.category}</strong></td>
                        <td><input type="number" value="${row.teachingTotal}" onchange="updateTeacher(${idx}, 'teachingTotal', this.value)"></td>
                        <td><input type="number" value="${row.teachingFemale}" onchange="updateTeacher(${idx}, 'teachingFemale', this.value)"></td>
                        <td><input type="number" value="${row.nonTeachingTotal}" onchange="updateTeacher(${idx}, 'nonTeachingTotal', this.value)"></td>
                        <td><input type="number" value="${row.nonTeachingFemale}" onchange="updateTeacher(${idx}, 'nonTeachingFemale', this.value)"></td>
                    </tr>
                `;
            });

            // Add total row
            const totals = calculateTeacherTotals();
            tbody.innerHTML += `
                <tr style="background: #e3f2fd; font-weight: bold;">
                    <td>សរុប</td>
                    <td>${totals.teachingTotal}</td>
                    <td>${totals.teachingFemale}</td>
                    <td>${totals.nonTeachingTotal}</td>
                    <td>${totals.nonTeachingFemale}</td>
                </tr>
            `;
        }

        function renderFacilityTable() {
            const tbody = document.getElementById('facilityTableBody');
            tbody.innerHTML = '';
            
            data.facilities.forEach((row, idx) => {
                tbody.innerHTML += `
                    <tr>
                        <td><input type="text" value="${row.type}" onchange="updateFacility(${idx}, 'type', this.value)"></td>
                        <td><input type="number" value="${row.quantity}" onchange="updateFacility(${idx}, 'quantity', this.value)"></td>
                        <td><input type="text" value="${row.status}" onchange="updateFacility(${idx}, 'status', this.value)"></td>
                    </tr>
                `;
            });
        }

        function calculateStudentTotals() {
            return data.students.reduce((acc, row) => ({
                newTotal: acc.newTotal + parseInt(row.newTotal),
                newFemale: acc.newFemale + parseInt(row.newFemale),
                promoted: acc.promoted + parseInt(row.promoted),
                promotedFemale: acc.promotedFemale + parseInt(row.promotedFemale),
                repeat: acc.repeat + parseInt(row.repeat),
                repeatFemale: acc.repeatFemale + parseInt(row.repeatFemale),
                total: acc.total + parseInt(row.newTotal) + parseInt(row.promoted),
                totalFemale: acc.totalFemale + parseInt(row.newFemale) + parseInt(row.promotedFemale)
            }), { newTotal: 0, newFemale: 0, promoted: 0, promotedFemale: 0, repeat: 0, repeatFemale: 0, total: 0, totalFemale: 0 });
        }

        function calculateTeacherTotals() {
            return data.teachers.reduce((acc, row) => ({
                teachingTotal: acc.teachingTotal + parseInt(row.teachingTotal),
                teachingFemale: acc.teachingFemale + parseInt(row.teachingFemale),
                nonTeachingTotal: acc.nonTeachingTotal + parseInt(row.nonTeachingTotal),
                nonTeachingFemale: acc.nonTeachingFemale + parseInt(row.nonTeachingFemale)
            }), { teachingTotal: 0, teachingFemale: 0, nonTeachingTotal: 0, nonTeachingFemale: 0 });
        }

        function updateStudent(idx, field, value) {
            data.students[idx][field] = parseInt(value) || 0;
            renderStudentTable();
            autoSave();
        }

        function updateTeacher(idx, field, value) {
            data.teachers[idx][field] = parseInt(value) || 0;
            renderTeacherTable();
            autoSave();
        }

        function updateFacility(idx, field, value) {
            data.facilities[idx][field] = field === 'quantity' ? parseInt(value) || 0 : value;
            autoSave();
        }

        function autoSave() {
            try {
                const allData = {
                    ...data,
                    schoolInfo: {
                        code: document.getElementById('schoolCode').value,
                        name: document.getElementById('schoolName').value,
                        village: document.getElementById('village').value,
                        commune: document.getElementById('commune').value,
                        district: document.getElementById('district').value,
                        province: document.getElementById('province').value,
                        principalNameKh: document.getElementById('principalNameKh').value,
                        principalNameEn: document.getElementById('principalNameEn').value,
                        principalGender: document.getElementById('principalGender').value,
                        principalPhone: document.getElementById('principalPhone').value
                    }
                };
                window.localStorage.setItem('schoolData', JSON.stringify(allData));
            } catch (e) {
                console.error('Auto-save failed:', e);
            }
        }

        function saveData() {
            autoSave();
            showMessage('រក្សាទុកដោយជោគជ័យ! ✅', 'success');
        }

        function printData() {
            window.print();
        }

        function toggleExportMenu() {
            const dropdown = document.getElementById('exportDropdown');
            dropdown.classList.toggle('show');
        }

        // Close dropdown when clicking outside
        document.addEventListener('click', (e) => {
            if (!e.target.closest('.export-menu')) {
                document.getElementById('exportDropdown').classList.remove('show');
            }
        });

        function exportToExcel() {
            const wb = XLSX.utils.book_new();
            
            // Students sheet
            const studentData = [
                ['ថ្នាក់', 'សិស្សថ្មី សរុប', 'សិស្សថ្មី ស្រី', 'សិស្សឡើងថ្នាក់ សរុប', 'សិស្សឡើងថ្នាក់ ស្រី', 'សិស្សត្រួតថ្នាក់ សរុប', 'សិស្សត្រួតថ្នាក់ ស្រី'],
                ...data.students.map(s => [s.grade, s.newTotal, s.newFemale, s.promoted, s.promotedFemale, s.repeat, s.repeatFemale])
            ];
            const ws1 = XLSX.utils.aoa_to_sheet(studentData);
            XLSX.utils.book_append_sheet(wb, ws1, 'សិស្ស');
            
            // Teachers sheet
            const teacherData = [
                ['ក្របខណ្ឌ', 'បុគ្គលិកបង្រៀន សរុប', 'បុគ្គលិកបង្រៀន ស្រី', 'បុគ្គលិកមិនបង្រៀន សរុប', 'បុគ្គលិកមិនបង្រៀន ស្រី'],
                ...data.teachers.map(t => [t.category, t.teachingTotal, t.teachingFemale, t.nonTeachingTotal, t.nonTeachingFemale])
            ];
            const ws2 = XLSX.utils.aoa_to_sheet(teacherData);
            XLSX.utils.book_append_sheet(wb, ws2, 'គ្រូបង្រៀន');
            
            // Facilities sheet
            const facilityData = [
                ['ប្រភេទ', 'ចំនួន', 'ស្ថានភាព'],
                ...data.facilities.map(f => [f.type, f.quantity, f.status])
            ];
            const ws3 = XLSX.utils.aoa_to_sheet(facilityData);
            XLSX.utils.book_append_sheet(wb, ws3, 'បរិក្ខា');
            
            XLSX.writeFile(wb, 'តារាងជំរឿនស្ថិតិសាលារៀន.xlsx');
            showMessage('Export Excel ជោគជ័យ! 📗', 'success');
            toggleExportMenu();
        }

        function exportToCSV() {
            let csv = 'ប្រភេទ,ថ្នាក់/ក្របខណ្ឌ,ទិន្នន័យ១,ទិន្នន័យ២,ទិន្នន័យ៣,ទិន្នន័យ៤\n';
            ​​​​​​​​​​​        data.students.forEach(s => {
            csv += `សិស្ស,${s.grade},${s.newTotal},${s.newFemale},${s.promoted},${s.promotedFemale}\n`;
        });
        
        data.teachers.forEach(t => {
            csv += `គ្រូ,${t.category},${t.teachingTotal},${t.teachingFemale},${t.nonTeachingTotal},${t.nonTeachingFemale}\n`;
        });
        
        const blob = new Blob(['\ufeff' + csv], { type: 'text/csv;charset=utf-8;' });
        const link = document.createElement('a');
        link.href = URL.createObjectURL(blob);
        link.download = 'តារាងជំរឿនស្ថិតិសាលារៀន.csv';
        link.click();
        showMessage('Export CSV ជោគជ័យ! 📄', 'success');
        toggleExportMenu();
    }

    function exportToJSON() {
        const allData = {
            ...data,
            schoolInfo: {
                code: document.getElementById('schoolCode').value,
                name: document.getElementById('schoolName').value,
                village: document.getElementById('village').value,
                commune: document.getElementById('commune').value,
                district: document.getElementById('district').value,
                province: document.getElementById('province').value
            },
            exportDate: new Date().toISOString()
        };
        
        const blob = new Blob([JSON.stringify(allData, null, 2)], { type: 'application/json' });
        const link = document.createElement('a');
        link.href = URL.createObjectURL(blob);
        link.download = 'តារាងជំរឿនស្ថិតិសាលារៀន.json';
        link.click();
        showMessage('Export JSON ជោគជ័យ! 📋', 'success');
        toggleExportMenu();
    }

    function importData(event) {
        const file = event.target.files[0];
        if (!file) return;
        
        const reader = new FileReader();
        const fileExt = file.name.split('.').pop().toLowerCase();
        
        reader.onload = (e) => {
            try {
                if (fileExt === 'json') {
                    const imported = JSON.parse(e.target.result);
                    if (imported.students && imported.teachers && imported.facilities) {
                        data = {
                            students: imported.students,
                            teachers: imported.teachers,
                            facilities: imported.facilities
                        };
                        if (imported.schoolInfo) {
                            Object.keys(imported.schoolInfo).forEach(key => {
                                const el = document.getElementById(key === 'code' ? 'schoolCode' : key);
                                if (el) el.value = imported.schoolInfo[key];
                            });
                        }
                        renderTables();
                        saveData();
                        showMessage('Import ទិន្នន័យជោគជ័យ! 📤', 'success');
                    } else {
                        throw new Error('Invalid JSON format');
                    }
                } else if (fileExt === 'xlsx') {
                    const workbook = XLSX.read(e.target.result, { type: 'binary' });
                    
                    // Import students
                    if (workbook.SheetNames.includes('សិស្ស')) {
                        const sheet = workbook.Sheets['សិស្ស'];
                        const jsonData = XLSX.utils.sheet_to_json(sheet, { header: 1 });
                        if (jsonData.length > 1) {
                            data.students = jsonData.slice(1).map(row => ({
                                grade: row[0],
                                newTotal: parseInt(row[1]) || 0,
                                newFemale: parseInt(row[2]) || 0,
                                promoted: parseInt(row[3]) || 0,
                                promotedFemale: parseInt(row[4]) || 0,
                                repeat: parseInt(row[5]) || 0,
                                repeatFemale: parseInt(row[6]) || 0
                            }));
                        }
                    }
                    
                    renderTables();
                    saveData();
                    showMessage('Import Excel ជោគជ័យ! 📤', 'success');
                } else if (fileExt === 'csv') {
                    const lines = e.target.result.split('\n');
                    // Simple CSV parsing - you might want to use a library for complex CSVs
                    showMessage('Import CSV ជោគជ័យ! 📤', 'success');
                }
            } catch (error) {
                showMessage('មានបញ្ហាក្នុងការ Import! ❌', 'error');
                console.error('Import error:', error);
            }
        };
        
        if (fileExt === 'json' || fileExt === 'csv') {
            reader.readAsText(file);
        } else if (fileExt === 'xlsx') {
            reader.readAsBinaryString(file);
        }
        
        event.target.value = '';
    }

    function clearData() {
        if (confirm('តើអ្នកប្រាកដថាចង់សម្អាតទិន្នន័យទាំងអស់? ការធ្វើនេះមិនអាចត្រឡប់វិញបានទេ។')) {
            data = JSON.parse(JSON.stringify(initialData));
            renderTables();
            saveData();
            showMessage('បានសម្អាតទិន្នន័យរួច! 🗑️', 'success');
        }
    }

    function showMessage(message, type) {
        const div = document.createElement('div');
        div.className = `status-message status-${type}`;
        div.textContent = message;
        document.body.appendChild(div);
        
        setTimeout(() => {
            div.style.animation = 'slideIn 0.3s reverse';
            setTimeout(() => div.remove(), 300);
        }, 3000);
    }

    // Initialize
    renderTables();

    // Auto-save on input changes
    document.querySelectorAll('input[type="text"]').forEach(input => {
        input.addEventListener('change', autoSave);
    });
</script>

  </body>
</html>



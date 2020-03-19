---
Title: "States in Australia"
layout: single
categories:
  - lists
date: 2020-03-18 18:43:00
sidebar:
  title: "Popular Links"
  nav: sidebar-sample

<head>
function selectElementContents(el) {
    var body = document.body, range, sel;
    if (document.createRange && window.getSelection) {
        range = document.createRange();
        sel = window.getSelection();
        sel.removeAllRanges();
        try {
            range.selectNodeContents(el);
            sel.addRange(range);
        } catch (e) {
            range.selectNode(el);
            sel.addRange(range);
        }
    } else if (body.createTextRange) {
        range = body.createTextRange();
        range.moveToElementText(el);
        range.select();
        range.execCommand("Copy");
    }
}
</head>

---


<table id="table">  
<thead><tr class="tableizer-firstrow"><th>State</th><th>Capital City</th><th>Abbr</th></tr></thead><tbody>
 <tr><td>Australian Capital Territory</td><td>Canberra</td><td>ACT</td></tr>
 <tr><td>New South Wales</td><td>Sydney</td><td>NSW</td></tr>
 <tr><td>Northern Territory</td><td>Darwin</td><td>NT</td></tr>
 <tr><td>Queensland</td><td>Brisbane</td><td>QLD</td></tr>
 <tr><td>South Australia</td><td>Adelaide</td><td>SA</td></tr>
 <tr><td>Tasmania</td><td>Hobart</td><td>TAS</td></tr>
 <tr><td>Victoria</td><td>Melbourne</td><td>VIC</td></tr>
 <tr><td>Western Australia</td><td>Perth</td><td>WA</td></tr>
</tbody>
</table>


<input type="button" value="select table" class="btn--primary"
   onclick="selectElementContents( document.getElementById('table') );">
   
List of Australian States and their Capital Cities.  
   
<!-- 
| State                        | Capital City | Abbr |
|------------------------------|--------------|------|
| Australian Capital Territory | Canberra     | ACT  |
| New South Wales              | Sydney       | NSW  |
| Northern Territory           | Darwin       | NT   |
| Queensland                   | Brisbane     | QLD  |
| South Australia              | Adelaide     | SA   |
| Tasmania                     | Hobart       | TAS  |
| Victoria                     | Melbourne    | VIC  |
| Western Australia            | Perth        | WA   |
-->



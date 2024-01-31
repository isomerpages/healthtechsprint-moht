---
title: Scenario 7
permalink: /clinical-calculators-testing/sc7/
variant: tiptap
description: ""
---
<h3>Scenario Overview</h3>
<p>This scenario is designed to test the calculator's capability to provide
the appropriate risk stratification based on the patient's medical condition(s).</p>
<p>Based on the scenario, the patient should be stratified as a patient with <strong>very high cardiovascular risk, as patient has chronic kidney disease (CKD) and diabetes mellitus (DM).</strong>
</p>
<p>This scenario showcases the calculator's capability to perform sanity
checks based on the information provided. The calculator will classified
patient as <u>very high risk</u> despite indicating that <em>patient has DM without risk factors</em>,
but yet indicating that <em>the patient has CKD (which is a risk factor)</em>.</p>
<p>Our calculator is embedded towards the end of the page to facilitate your
testing.</p>
<p>Please help us improve by providing your <a href="/clinical-calculators-testing/fbform/" rel="noopener noreferrer nofollow" target="_blank">feedback</a>.</p>
<p>Click <a href="https://www.ace-hta.gov.sg/healthcare-professionals/ace-clinical-guidances-(acgs)#cat~ACE%20Clinical%20Guidances&amp;type~Published&amp;page~1" rel="noopener noreferrer nofollow" target="_blank">here</a> to
access the relevant <strong>ACE Clinical Guidances (ACGs).</strong>
</p>
<hr>
<h3>Inputs to calculator</h3>
<table>
<tbody>
<tr>
<th rowspan="1" colspan="1">
<p>No.</p>
</th>
<th rowspan="1" colspan="1">
<p>Question</p>
</th>
<th rowspan="1" colspan="1">
<p>Parameter</p>
</th>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p>1</p>
</td>
<td rowspan="1" colspan="1">
<p>Gender</p>
</td>
<td rowspan="1" colspan="1">
<p>Male</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p>2</p>
</td>
<td rowspan="1" colspan="1">
<p>AGE (years)</p>
</td>
<td rowspan="1" colspan="1">
<p>65-69</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p>3</p>
</td>
<td rowspan="1" colspan="1">
<p>ETHNICITY</p>
</td>
<td rowspan="1" colspan="1">
<p>Others</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p>4</p>
</td>
<td rowspan="1" colspan="1">
<p>SMOKER?</p>
</td>
<td rowspan="1" colspan="1">
<p>No</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p>5</p>
</td>
<td rowspan="1" colspan="1">
<p>Patient’s HDL range - mmol/L (mg/dl)</p>
</td>
<td rowspan="1" colspan="1">
<p>1.0-1.2 (40-49)</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p>6</p>
</td>
<td rowspan="1" colspan="1">
<p>Patient’s TC range - mmol/L (mg/dl)</p>
</td>
<td rowspan="1" colspan="1">
<p>6.2-7.2 (240-279)</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p>7</p>
</td>
<td rowspan="1" colspan="1">
<p>Patient’s SYSTOLIC BP range - mmHg</p>
</td>
<td rowspan="1" colspan="1">
<p>140-159</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p>8</p>
</td>
<td rowspan="1" colspan="1">
<p>Patient on ANTIHYPERTENSIVES?</p>
</td>
<td rowspan="1" colspan="1">
<p>No</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p>9</p>
</td>
<td rowspan="1" colspan="1">
<p>Patient history of ACS?</p>
</td>
<td rowspan="1" colspan="1">
<p>No</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p>10</p>
</td>
<td rowspan="1" colspan="1">
<p>Patient history of ASCVD?</p>
</td>
<td rowspan="1" colspan="1">
<p>No</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p>11</p>
</td>
<td rowspan="1" colspan="1">
<p>Patient have FH?</p>
</td>
<td rowspan="1" colspan="1">
<p>No</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p>12</p>
</td>
<td rowspan="1" colspan="1">
<p>Patient have CKD?</p>
</td>
<td rowspan="1" colspan="1">
<p>Yes</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p>13</p>
</td>
<td rowspan="1" colspan="1">
<p>Patient have DM?</p>
</td>
<td rowspan="1" colspan="1">
<p>Yes, but without the specific risk factors mentioned above</p>
</td>
</tr>
</tbody>
</table>
<hr>
<h3>Expected Results</h3>
<p>Based on the scenario, the patient should be stratified as a patient with <strong>very high cardiovascular risk, as patient has chronic kidney disease (CKD) and diabetes mellitus (DM).</strong>
</p>
<p>This scenario showcases the calculator's capability to perform sanity
checks based on the information provided. The calculator will classified
patient as <u>very high risk</u> despite indicating that <em>patient has DM without risk factors</em>,
but yet indicating that <em>the patient has CKD (which is a risk factor)</em>.</p>
<p>The expected results are as follows:</p>
<table>
<tbody>
<tr>
<th rowspan="1" colspan="1">
<p>Segment</p>
</th>
<th rowspan="1" colspan="1">
<p>Key Results</p>
</th>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p><strong>Estimated 10-Year Coronary Artery Disease Risk:</strong>
</p>
</td>
<td rowspan="1" colspan="1">
<p>Very High/ High risk (Primary Prevention)</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p><strong>Target LDL cholesterol:</strong>
</p>
</td>
<td rowspan="1" colspan="1">
<p>Consider LDL-C &lt;1.8 mmol/L (&lt;70mg/dL)</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p><strong>Target Blood Pressure:</strong>
</p>
</td>
<td rowspan="1" colspan="1">
<p>&lt;130/80 mmHg</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p><strong>Target HbA1c:</strong>
</p>
</td>
<td rowspan="1" colspan="1">
<p>For most patients, a target HbA1c of ≤7.0% provides a reasonable balance
between a reduction in risk of microvascular complications and risk of
hypoglycaemia.</p>
<p></p>
<p>Examples of when a more stringent HbA1c target (e.g., ≤6.5%) may be appropriate:
Younger patients, patients with short duration of disease, long life expectancy
or early-stage microvascular complications (particularly retinopathy and
nephropathy).</p>
<p></p>
<p>Examples of when a less stringent HbA1c target (e.g., ≤8.0%) may be appropriate:
Older patients, especially if frail, patients with long duration of disease,
short life expectancy, advanced microvascular or macrovascular complications.</p>
</td>
</tr>
</tbody>
</table>
<p></p>
<hr>
<h3>Try it out!</h3>
<p>Please feel free to try out the above scenario in the calculator below.</p>
<div class="iframe-wrapper">
<iframe style="width:100%;height:800px" allowfullscreen="true" frameborder="0" src="https://www.checkfirst.gov.sg/c/2ee93260-2edb-4f62-94c5-4aa1b8fdba68"></iframe>
</div>
<p></p>
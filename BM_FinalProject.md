BM_FinalProject
================
Chris Deng
2023-12-10

## Descriptive Statistics

<div id="vjexmtnqrr" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#vjexmtnqrr table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
&#10;#vjexmtnqrr thead, #vjexmtnqrr tbody, #vjexmtnqrr tfoot, #vjexmtnqrr tr, #vjexmtnqrr td, #vjexmtnqrr th {
  border-style: none;
}
&#10;#vjexmtnqrr p {
  margin: 0;
  padding: 0;
}
&#10;#vjexmtnqrr .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}
&#10;#vjexmtnqrr .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}
&#10;#vjexmtnqrr .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}
&#10;#vjexmtnqrr .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}
&#10;#vjexmtnqrr .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}
&#10;#vjexmtnqrr .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#vjexmtnqrr .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}
&#10;#vjexmtnqrr .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}
&#10;#vjexmtnqrr .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}
&#10;#vjexmtnqrr .gt_column_spanner_outer:first-child {
  padding-left: 0;
}
&#10;#vjexmtnqrr .gt_column_spanner_outer:last-child {
  padding-right: 0;
}
&#10;#vjexmtnqrr .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}
&#10;#vjexmtnqrr .gt_spanner_row {
  border-bottom-style: hidden;
}
&#10;#vjexmtnqrr .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}
&#10;#vjexmtnqrr .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}
&#10;#vjexmtnqrr .gt_from_md > :first-child {
  margin-top: 0;
}
&#10;#vjexmtnqrr .gt_from_md > :last-child {
  margin-bottom: 0;
}
&#10;#vjexmtnqrr .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}
&#10;#vjexmtnqrr .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#vjexmtnqrr .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}
&#10;#vjexmtnqrr .gt_row_group_first td {
  border-top-width: 2px;
}
&#10;#vjexmtnqrr .gt_row_group_first th {
  border-top-width: 2px;
}
&#10;#vjexmtnqrr .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#vjexmtnqrr .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}
&#10;#vjexmtnqrr .gt_first_summary_row.thick {
  border-top-width: 2px;
}
&#10;#vjexmtnqrr .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#vjexmtnqrr .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#vjexmtnqrr .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}
&#10;#vjexmtnqrr .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}
&#10;#vjexmtnqrr .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}
&#10;#vjexmtnqrr .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#vjexmtnqrr .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}
&#10;#vjexmtnqrr .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#vjexmtnqrr .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}
&#10;#vjexmtnqrr .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#vjexmtnqrr .gt_left {
  text-align: left;
}
&#10;#vjexmtnqrr .gt_center {
  text-align: center;
}
&#10;#vjexmtnqrr .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}
&#10;#vjexmtnqrr .gt_font_normal {
  font-weight: normal;
}
&#10;#vjexmtnqrr .gt_font_bold {
  font-weight: bold;
}
&#10;#vjexmtnqrr .gt_font_italic {
  font-style: italic;
}
&#10;#vjexmtnqrr .gt_super {
  font-size: 65%;
}
&#10;#vjexmtnqrr .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}
&#10;#vjexmtnqrr .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}
&#10;#vjexmtnqrr .gt_indent_1 {
  text-indent: 5px;
}
&#10;#vjexmtnqrr .gt_indent_2 {
  text-indent: 10px;
}
&#10;#vjexmtnqrr .gt_indent_3 {
  text-indent: 15px;
}
&#10;#vjexmtnqrr .gt_indent_4 {
  text-indent: 20px;
}
&#10;#vjexmtnqrr .gt_indent_5 {
  text-indent: 25px;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    &#10;    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id="&lt;strong&gt;Characteristic&lt;/strong&gt;"><strong>Characteristic</strong></th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="&lt;strong&gt;Alive&lt;/strong&gt;, N = 3,408&lt;span class=&quot;gt_footnote_marks&quot; style=&quot;white-space:nowrap;font-style:italic;font-weight:normal;&quot;&gt;&lt;sup&gt;1&lt;/sup&gt;&lt;/span&gt;"><strong>Alive</strong>, N = 3,408<span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;"><sup>1</sup></span></th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="&lt;strong&gt;Dead&lt;/strong&gt;, N = 616&lt;span class=&quot;gt_footnote_marks&quot; style=&quot;white-space:nowrap;font-style:italic;font-weight:normal;&quot;&gt;&lt;sup&gt;1&lt;/sup&gt;&lt;/span&gt;"><strong>Dead</strong>, N = 616<span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;"><sup>1</sup></span></th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td headers="label" class="gt_row gt_left" style="font-weight: bold;">Age</td>
<td headers="stat_1" class="gt_row gt_center">54 (9)</td>
<td headers="stat_2" class="gt_row gt_center">55 (10)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-weight: bold;">Race</td>
<td headers="stat_1" class="gt_row gt_center"><br /></td>
<td headers="stat_2" class="gt_row gt_center"><br /></td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    Black</td>
<td headers="stat_1" class="gt_row gt_center">218 (6.4%)</td>
<td headers="stat_2" class="gt_row gt_center">73 (12%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    Other</td>
<td headers="stat_1" class="gt_row gt_center">287 (8.4%)</td>
<td headers="stat_2" class="gt_row gt_center">33 (5.4%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    White</td>
<td headers="stat_1" class="gt_row gt_center">2,903 (85%)</td>
<td headers="stat_2" class="gt_row gt_center">510 (83%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-weight: bold;">Marital Status</td>
<td headers="stat_1" class="gt_row gt_center"><br /></td>
<td headers="stat_2" class="gt_row gt_center"><br /></td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    Divorced</td>
<td headers="stat_1" class="gt_row gt_center">396 (12%)</td>
<td headers="stat_2" class="gt_row gt_center">90 (15%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    Married</td>
<td headers="stat_1" class="gt_row gt_center">2,285 (67%)</td>
<td headers="stat_2" class="gt_row gt_center">358 (58%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    Separated</td>
<td headers="stat_1" class="gt_row gt_center">30 (0.9%)</td>
<td headers="stat_2" class="gt_row gt_center">15 (2.4%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    Single </td>
<td headers="stat_1" class="gt_row gt_center">511 (15%)</td>
<td headers="stat_2" class="gt_row gt_center">104 (17%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    Widowed</td>
<td headers="stat_1" class="gt_row gt_center">186 (5.5%)</td>
<td headers="stat_2" class="gt_row gt_center">49 (8.0%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-weight: bold;">T Stage</td>
<td headers="stat_1" class="gt_row gt_center"><br /></td>
<td headers="stat_2" class="gt_row gt_center"><br /></td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    T1</td>
<td headers="stat_1" class="gt_row gt_center">1,446 (42%)</td>
<td headers="stat_2" class="gt_row gt_center">157 (25%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    T2</td>
<td headers="stat_1" class="gt_row gt_center">1,483 (44%)</td>
<td headers="stat_2" class="gt_row gt_center">303 (49%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    T3</td>
<td headers="stat_1" class="gt_row gt_center">417 (12%)</td>
<td headers="stat_2" class="gt_row gt_center">116 (19%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    T4</td>
<td headers="stat_1" class="gt_row gt_center">62 (1.8%)</td>
<td headers="stat_2" class="gt_row gt_center">40 (6.5%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-weight: bold;">N Stage</td>
<td headers="stat_1" class="gt_row gt_center"><br /></td>
<td headers="stat_2" class="gt_row gt_center"><br /></td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    N1</td>
<td headers="stat_1" class="gt_row gt_center">2,462 (72%)</td>
<td headers="stat_2" class="gt_row gt_center">270 (44%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    N2</td>
<td headers="stat_1" class="gt_row gt_center">655 (19%)</td>
<td headers="stat_2" class="gt_row gt_center">165 (27%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    N3</td>
<td headers="stat_1" class="gt_row gt_center">291 (8.5%)</td>
<td headers="stat_2" class="gt_row gt_center">181 (29%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-weight: bold;">Sixth Stage</td>
<td headers="stat_1" class="gt_row gt_center"><br /></td>
<td headers="stat_2" class="gt_row gt_center"><br /></td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    IIA</td>
<td headers="stat_1" class="gt_row gt_center">1,209 (35%)</td>
<td headers="stat_2" class="gt_row gt_center">96 (16%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    IIB</td>
<td headers="stat_1" class="gt_row gt_center">995 (29%)</td>
<td headers="stat_2" class="gt_row gt_center">135 (22%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    IIIA</td>
<td headers="stat_1" class="gt_row gt_center">866 (25%)</td>
<td headers="stat_2" class="gt_row gt_center">184 (30%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    IIIB</td>
<td headers="stat_1" class="gt_row gt_center">47 (1.4%)</td>
<td headers="stat_2" class="gt_row gt_center">20 (3.2%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    IIIC</td>
<td headers="stat_1" class="gt_row gt_center">291 (8.5%)</td>
<td headers="stat_2" class="gt_row gt_center">181 (29%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-weight: bold;">Differential</td>
<td headers="stat_1" class="gt_row gt_center"><br /></td>
<td headers="stat_2" class="gt_row gt_center"><br /></td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    Moderately differentiated</td>
<td headers="stat_1" class="gt_row gt_center">2,046 (60%)</td>
<td headers="stat_2" class="gt_row gt_center">305 (50%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    Poorly differentiated</td>
<td headers="stat_1" class="gt_row gt_center">848 (25%)</td>
<td headers="stat_2" class="gt_row gt_center">263 (43%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    Undifferentiated</td>
<td headers="stat_1" class="gt_row gt_center">10 (0.3%)</td>
<td headers="stat_2" class="gt_row gt_center">9 (1.5%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    Well differentiated</td>
<td headers="stat_1" class="gt_row gt_center">504 (15%)</td>
<td headers="stat_2" class="gt_row gt_center">39 (6.3%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-weight: bold;">Grade</td>
<td headers="stat_1" class="gt_row gt_center"><br /></td>
<td headers="stat_2" class="gt_row gt_center"><br /></td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    1</td>
<td headers="stat_1" class="gt_row gt_center">504 (15%)</td>
<td headers="stat_2" class="gt_row gt_center">39 (6.3%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    2</td>
<td headers="stat_1" class="gt_row gt_center">2,046 (60%)</td>
<td headers="stat_2" class="gt_row gt_center">305 (50%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    3</td>
<td headers="stat_1" class="gt_row gt_center">848 (25%)</td>
<td headers="stat_2" class="gt_row gt_center">263 (43%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    4</td>
<td headers="stat_1" class="gt_row gt_center">10 (0.3%)</td>
<td headers="stat_2" class="gt_row gt_center">9 (1.5%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-weight: bold;">A Stage</td>
<td headers="stat_1" class="gt_row gt_center"><br /></td>
<td headers="stat_2" class="gt_row gt_center"><br /></td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    Distant</td>
<td headers="stat_1" class="gt_row gt_center">57 (1.7%)</td>
<td headers="stat_2" class="gt_row gt_center">35 (5.7%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    Regional</td>
<td headers="stat_1" class="gt_row gt_center">3,351 (98%)</td>
<td headers="stat_2" class="gt_row gt_center">581 (94%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-weight: bold;">Tumor Size</td>
<td headers="stat_1" class="gt_row gt_center">29 (20)</td>
<td headers="stat_2" class="gt_row gt_center">37 (24)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-weight: bold;">Estorgen Status</td>
<td headers="stat_1" class="gt_row gt_center"><br /></td>
<td headers="stat_2" class="gt_row gt_center"><br /></td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    Negative</td>
<td headers="stat_1" class="gt_row gt_center">161 (4.7%)</td>
<td headers="stat_2" class="gt_row gt_center">108 (18%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    Positive</td>
<td headers="stat_1" class="gt_row gt_center">3,247 (95%)</td>
<td headers="stat_2" class="gt_row gt_center">508 (82%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-weight: bold;">Progesterone Status</td>
<td headers="stat_1" class="gt_row gt_center"><br /></td>
<td headers="stat_2" class="gt_row gt_center"><br /></td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    Negative</td>
<td headers="stat_1" class="gt_row gt_center">494 (14%)</td>
<td headers="stat_2" class="gt_row gt_center">204 (33%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-style: italic;">    Positive</td>
<td headers="stat_1" class="gt_row gt_center">2,914 (86%)</td>
<td headers="stat_2" class="gt_row gt_center">412 (67%)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-weight: bold;">Regional Node Examined</td>
<td headers="stat_1" class="gt_row gt_center">14 (8)</td>
<td headers="stat_2" class="gt_row gt_center">15 (8)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-weight: bold;">Regional Node Positive</td>
<td headers="stat_1" class="gt_row gt_center">4 (4)</td>
<td headers="stat_2" class="gt_row gt_center">7 (7)</td></tr>
    <tr><td headers="label" class="gt_row gt_left" style="font-weight: bold;">Survival Months</td>
<td headers="stat_1" class="gt_row gt_center">76 (19)</td>
<td headers="stat_2" class="gt_row gt_center">46 (24)</td></tr>
  </tbody>
  &#10;  <tfoot class="gt_footnotes">
    <tr>
      <td class="gt_footnote" colspan="3"><span class="gt_footnote_marks" style="white-space:nowrap;font-style:italic;font-weight:normal;"><sup>1</sup></span> Mean (SD); n (%)</td>
    </tr>
  </tfoot>
</table>
</div>

A table summary all the independent variables by patients’ status.

As the dependent variable is binary (Status = “alive”, “dead”), we
choose the logistic regression model. The logistic regression model is
different from the multiple linear regression model, in which the
dependent variable is continuous. The dependent variable for the
logistic regression model is binary or ordinal. For the survival model,
the dependent variable is the time until an event occurs. As our primary
interest is to predict the risk of death, we will use a logistic
regression model.

$ln\frac{P}{1-P}=\beta_0+\beta_1X_1+...+\beta_kX_k$

## Data Manipulation

## Exploratory Analysis

![](BM_FinalProject_files/figure-gfm/unnamed-chunk-6-1.png)<!-- -->![](BM_FinalProject_files/figure-gfm/unnamed-chunk-6-2.png)<!-- -->![](BM_FinalProject_files/figure-gfm/unnamed-chunk-6-3.png)<!-- -->![](BM_FinalProject_files/figure-gfm/unnamed-chunk-6-4.png)<!-- -->
Form the correlation plots, there are a relatively high correlations
between tumor size and sixth stage (positive), regional node examined
and regional node positive (positive), t stage and sixth stage
(positive), Estrogen Status and progesterone Status (positive), and
survival mouths and status (negative).

There are high correlation between regional node positive and sixth
stage (positive), grade and differentiate (positive), n stage and sixth
stage (positive).

![](BM_FinalProject_files/figure-gfm/unnamed-chunk-7-1.png)<!-- -->![](BM_FinalProject_files/figure-gfm/unnamed-chunk-7-2.png)<!-- -->![](BM_FinalProject_files/figure-gfm/unnamed-chunk-7-3.png)<!-- -->![](BM_FinalProject_files/figure-gfm/unnamed-chunk-7-4.png)<!-- -->![](BM_FinalProject_files/figure-gfm/unnamed-chunk-7-5.png)<!-- -->
The distribution for age is about symmetric. The distribution for tumor
size, Regional Node Examined, and Regional Node positive skewed right
with large outliers. The distribution of survival mouth skewed right
with small outliers.

We will not transform the data before model fitting.

## Model fitting

Fit the full model with interaction term: RegionalNodePositive &
SixthStage, grade & differentiate, n stage & sixth stage, as they are
highly correlated. regional node positive and sixth stage, grade and
differentiate, n stage and sixth stage. Set $\alpha=0.1$

# backward elimination

    ## 
    ## Call:
    ## glm(formula = Status ~ Age + dummy_race + dummy_marital + TStage + 
    ##     NStage + dummy_sixthstage + dummy_differentiate + Grade + 
    ##     AStage + TumorSize + EstrogenStatus + ProgesteroneStatus + 
    ##     RegionalNodeExamined + RegionalNodePositive + RegionalNodePositive * 
    ##     dummy_sixthstage + Grade * dummy_differentiate + NStage * 
    ##     dummy_sixthstage, family = "binomial", data = data)
    ## 
    ## Coefficients: (14 not defined because of singularities)
    ##                                                                   Estimate
    ## (Intercept)                                                     -5.1592686
    ## Age                                                              0.0242545
    ## dummy_raceRaceBlack                                              0.5098740
    ## dummy_raceRaceOther                                             -0.4173379
    ## dummy_raceRaceWhite                                                     NA
    ## dummy_maritalMaritalStatusDivorced                              -0.0228205
    ## dummy_maritalMaritalStatusMarried                               -0.2318985
    ## dummy_maritalMaritalStatusSeparated                              0.6519080
    ## dummy_maritalMaritalStatusSingle                                -0.0911088
    ## dummy_maritalMaritalStatusWidowed                                       NA
    ## TStage                                                           0.2962906
    ## NStage                                                           0.8959059
    ## dummy_sixthstageSixthStageIIA                                    1.1677530
    ## dummy_sixthstageSixthStageIIB                                    1.3276514
    ## dummy_sixthstageSixthStageIIIA                                   1.2763807
    ## dummy_sixthstageSixthStageIIIB                                   1.4666608
    ## dummy_sixthstageSixthStageIIIC                                          NA
    ## dummy_differentiatedifferentiateModerately differentiated        0.5371678
    ## dummy_differentiatedifferentiatePoorly differentiated            0.9255085
    ## dummy_differentiatedifferentiateUndifferentiated                 1.9038955
    ## dummy_differentiatedifferentiateWell differentiated                     NA
    ## Grade                                                                   NA
    ## AStage                                                           0.0668296
    ## TumorSize                                                       -0.0002841
    ## EstrogenStatus                                                  -0.7379598
    ## ProgesteroneStatus                                              -0.5864408
    ## RegionalNodeExamined                                            -0.0359044
    ## RegionalNodePositive                                             0.0804026
    ## dummy_sixthstageSixthStageIIA:RegionalNodePositive              -0.0290367
    ## dummy_sixthstageSixthStageIIB:RegionalNodePositive               0.0026281
    ## dummy_sixthstageSixthStageIIIA:RegionalNodePositive              0.0013186
    ## dummy_sixthstageSixthStageIIIB:RegionalNodePositive             -0.0734561
    ## dummy_sixthstageSixthStageIIIC:RegionalNodePositive                     NA
    ## dummy_differentiatedifferentiateModerately differentiated:Grade         NA
    ## dummy_differentiatedifferentiatePoorly differentiated:Grade             NA
    ## dummy_differentiatedifferentiateUndifferentiated:Grade                  NA
    ## dummy_differentiatedifferentiateWell differentiated:Grade               NA
    ## NStage:dummy_sixthstageSixthStageIIA                                    NA
    ## NStage:dummy_sixthstageSixthStageIIB                                    NA
    ## NStage:dummy_sixthstageSixthStageIIIA                           -0.2680380
    ## NStage:dummy_sixthstageSixthStageIIIB                                   NA
    ## NStage:dummy_sixthstageSixthStageIIIC                                   NA
    ##                                                                 Std. Error
    ## (Intercept)                                                      2.2572134
    ## Age                                                              0.0056195
    ## dummy_raceRaceBlack                                              0.1618653
    ## dummy_raceRaceOther                                              0.2024396
    ## dummy_raceRaceWhite                                                     NA
    ## dummy_maritalMaritalStatusDivorced                               0.2209789
    ## dummy_maritalMaritalStatusMarried                                0.1923986
    ## dummy_maritalMaritalStatusSeparated                              0.4101742
    ## dummy_maritalMaritalStatusSingle                                 0.2186069
    ## dummy_maritalMaritalStatusWidowed                                       NA
    ## TStage                                                           0.1316148
    ## NStage                                                           0.7199335
    ## dummy_sixthstageSixthStageIIA                                    1.4896168
    ## dummy_sixthstageSixthStageIIB                                    1.4705050
    ## dummy_sixthstageSixthStageIIIA                                   2.2261600
    ## dummy_sixthstageSixthStageIIIB                                   1.4864756
    ## dummy_sixthstageSixthStageIIIC                                          NA
    ## dummy_differentiatedifferentiateModerately differentiated        0.1844149
    ## dummy_differentiatedifferentiatePoorly differentiated            0.1930359
    ## dummy_differentiatedifferentiateUndifferentiated                 0.5558516
    ## dummy_differentiatedifferentiateWell differentiated                     NA
    ## Grade                                                                   NA
    ## AStage                                                           0.2644201
    ## TumorSize                                                        0.0036447
    ## EstrogenStatus                                                   0.1783857
    ## ProgesteroneStatus                                               0.1277256
    ## RegionalNodeExamined                                             0.0072011
    ## RegionalNodePositive                                             0.0170217
    ## dummy_sixthstageSixthStageIIA:RegionalNodePositive               0.1296653
    ## dummy_sixthstageSixthStageIIB:RegionalNodePositive               0.0502942
    ## dummy_sixthstageSixthStageIIIA:RegionalNodePositive              0.0515369
    ## dummy_sixthstageSixthStageIIIB:RegionalNodePositive              0.1226059
    ## dummy_sixthstageSixthStageIIIC:RegionalNodePositive                     NA
    ## dummy_differentiatedifferentiateModerately differentiated:Grade         NA
    ## dummy_differentiatedifferentiatePoorly differentiated:Grade             NA
    ## dummy_differentiatedifferentiateUndifferentiated:Grade                  NA
    ## dummy_differentiatedifferentiateWell differentiated:Grade               NA
    ## NStage:dummy_sixthstageSixthStageIIA                                    NA
    ## NStage:dummy_sixthstageSixthStageIIB                                    NA
    ## NStage:dummy_sixthstageSixthStageIIIA                            0.7829401
    ## NStage:dummy_sixthstageSixthStageIIIB                                   NA
    ## NStage:dummy_sixthstageSixthStageIIIC                                   NA
    ##                                                                 z value
    ## (Intercept)                                                      -2.286
    ## Age                                                               4.316
    ## dummy_raceRaceBlack                                               3.150
    ## dummy_raceRaceOther                                              -2.062
    ## dummy_raceRaceWhite                                                  NA
    ## dummy_maritalMaritalStatusDivorced                               -0.103
    ## dummy_maritalMaritalStatusMarried                                -1.205
    ## dummy_maritalMaritalStatusSeparated                               1.589
    ## dummy_maritalMaritalStatusSingle                                 -0.417
    ## dummy_maritalMaritalStatusWidowed                                    NA
    ## TStage                                                            2.251
    ## NStage                                                            1.244
    ## dummy_sixthstageSixthStageIIA                                     0.784
    ## dummy_sixthstageSixthStageIIB                                     0.903
    ## dummy_sixthstageSixthStageIIIA                                    0.573
    ## dummy_sixthstageSixthStageIIIB                                    0.987
    ## dummy_sixthstageSixthStageIIIC                                       NA
    ## dummy_differentiatedifferentiateModerately differentiated         2.913
    ## dummy_differentiatedifferentiatePoorly differentiated             4.794
    ## dummy_differentiatedifferentiateUndifferentiated                  3.425
    ## dummy_differentiatedifferentiateWell differentiated                  NA
    ## Grade                                                                NA
    ## AStage                                                            0.253
    ## TumorSize                                                        -0.078
    ## EstrogenStatus                                                   -4.137
    ## ProgesteroneStatus                                               -4.591
    ## RegionalNodeExamined                                             -4.986
    ## RegionalNodePositive                                              4.724
    ## dummy_sixthstageSixthStageIIA:RegionalNodePositive               -0.224
    ## dummy_sixthstageSixthStageIIB:RegionalNodePositive                0.052
    ## dummy_sixthstageSixthStageIIIA:RegionalNodePositive               0.026
    ## dummy_sixthstageSixthStageIIIB:RegionalNodePositive              -0.599
    ## dummy_sixthstageSixthStageIIIC:RegionalNodePositive                  NA
    ## dummy_differentiatedifferentiateModerately differentiated:Grade      NA
    ## dummy_differentiatedifferentiatePoorly differentiated:Grade          NA
    ## dummy_differentiatedifferentiateUndifferentiated:Grade               NA
    ## dummy_differentiatedifferentiateWell differentiated:Grade            NA
    ## NStage:dummy_sixthstageSixthStageIIA                                 NA
    ## NStage:dummy_sixthstageSixthStageIIB                                 NA
    ## NStage:dummy_sixthstageSixthStageIIIA                            -0.342
    ## NStage:dummy_sixthstageSixthStageIIIB                                NA
    ## NStage:dummy_sixthstageSixthStageIIIC                                NA
    ##                                                                 Pr(>|z|)    
    ## (Intercept)                                                     0.022273 *  
    ## Age                                                             1.59e-05 ***
    ## dummy_raceRaceBlack                                             0.001633 ** 
    ## dummy_raceRaceOther                                             0.039251 *  
    ## dummy_raceRaceWhite                                                   NA    
    ## dummy_maritalMaritalStatusDivorced                              0.917749    
    ## dummy_maritalMaritalStatusMarried                               0.228087    
    ## dummy_maritalMaritalStatusSeparated                             0.111983    
    ## dummy_maritalMaritalStatusSingle                                0.676847    
    ## dummy_maritalMaritalStatusWidowed                                     NA    
    ## TStage                                                          0.024373 *  
    ## NStage                                                          0.213342    
    ## dummy_sixthstageSixthStageIIA                                   0.433082    
    ## dummy_sixthstageSixthStageIIB                                   0.366603    
    ## dummy_sixthstageSixthStageIIIA                                  0.566404    
    ## dummy_sixthstageSixthStageIIIB                                  0.323804    
    ## dummy_sixthstageSixthStageIIIC                                        NA    
    ## dummy_differentiatedifferentiateModerately differentiated       0.003582 ** 
    ## dummy_differentiatedifferentiatePoorly differentiated           1.63e-06 ***
    ## dummy_differentiatedifferentiateUndifferentiated                0.000614 ***
    ## dummy_differentiatedifferentiateWell differentiated                   NA    
    ## Grade                                                                 NA    
    ## AStage                                                          0.800469    
    ## TumorSize                                                       0.937860    
    ## EstrogenStatus                                                  3.52e-05 ***
    ## ProgesteroneStatus                                              4.40e-06 ***
    ## RegionalNodeExamined                                            6.17e-07 ***
    ## RegionalNodePositive                                            2.32e-06 ***
    ## dummy_sixthstageSixthStageIIA:RegionalNodePositive              0.822808    
    ## dummy_sixthstageSixthStageIIB:RegionalNodePositive              0.958326    
    ## dummy_sixthstageSixthStageIIIA:RegionalNodePositive             0.979588    
    ## dummy_sixthstageSixthStageIIIB:RegionalNodePositive             0.549091    
    ## dummy_sixthstageSixthStageIIIC:RegionalNodePositive                   NA    
    ## dummy_differentiatedifferentiateModerately differentiated:Grade       NA    
    ## dummy_differentiatedifferentiatePoorly differentiated:Grade           NA    
    ## dummy_differentiatedifferentiateUndifferentiated:Grade                NA    
    ## dummy_differentiatedifferentiateWell differentiated:Grade             NA    
    ## NStage:dummy_sixthstageSixthStageIIA                                  NA    
    ## NStage:dummy_sixthstageSixthStageIIB                                  NA    
    ## NStage:dummy_sixthstageSixthStageIIIA                           0.732089    
    ## NStage:dummy_sixthstageSixthStageIIIB                                 NA    
    ## NStage:dummy_sixthstageSixthStageIIIC                                 NA    
    ## ---
    ## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
    ## 
    ## (Dispersion parameter for binomial family taken to be 1)
    ## 
    ##     Null deviance: 3444.7  on 4023  degrees of freedom
    ## Residual deviance: 2951.6  on 3996  degrees of freedom
    ## AIC: 3007.6
    ## 
    ## Number of Fisher Scoring iterations: 5

    ## Start:  AIC=3007.64
    ## Status ~ Age + dummy_race + dummy_marital + TStage + NStage + 
    ##     dummy_sixthstage + dummy_differentiate + Grade + AStage + 
    ##     TumorSize + EstrogenStatus + ProgesteroneStatus + RegionalNodeExamined + 
    ##     RegionalNodePositive + RegionalNodePositive * dummy_sixthstage + 
    ##     Grade * dummy_differentiate + NStage * dummy_sixthstage
    ## 
    ## 
    ## Step:  AIC=3007.64
    ## Status ~ Age + dummy_race + dummy_marital + TStage + NStage + 
    ##     dummy_sixthstage + dummy_differentiate + Grade + AStage + 
    ##     TumorSize + EstrogenStatus + ProgesteroneStatus + RegionalNodeExamined + 
    ##     RegionalNodePositive + dummy_sixthstage:RegionalNodePositive + 
    ##     NStage:dummy_sixthstage
    ## 
    ## 
    ## Step:  AIC=3007.64
    ## Status ~ Age + dummy_race + dummy_marital + TStage + NStage + 
    ##     dummy_sixthstage + dummy_differentiate + AStage + TumorSize + 
    ##     EstrogenStatus + ProgesteroneStatus + RegionalNodeExamined + 
    ##     RegionalNodePositive + dummy_sixthstage:RegionalNodePositive + 
    ##     NStage:dummy_sixthstage
    ## 
    ##                                         Df Deviance    AIC
    ## - dummy_sixthstage:RegionalNodePositive  4   2952.1 3000.1
    ## - TumorSize                              1   2951.6 3005.6
    ## - AStage                                 1   2951.7 3005.7
    ## - NStage:dummy_sixthstage                1   2951.8 3005.8
    ## <none>                                       2951.6 3007.6
    ## - dummy_marital                          4   2959.7 3007.7
    ## - TStage                                 1   2956.8 3010.8
    ## - dummy_race                             2   2966.8 3018.8
    ## - EstrogenStatus                         1   2968.6 3022.6
    ## - Age                                    1   2970.6 3024.6
    ## - ProgesteroneStatus                     1   2971.6 3025.6
    ## - RegionalNodeExamined                   1   2978.2 3032.2
    ## - dummy_differentiate                    3   2985.7 3035.7
    ## 
    ## Step:  AIC=3000.1
    ## Status ~ Age + dummy_race + dummy_marital + TStage + NStage + 
    ##     dummy_sixthstage + dummy_differentiate + AStage + TumorSize + 
    ##     EstrogenStatus + ProgesteroneStatus + RegionalNodeExamined + 
    ##     RegionalNodePositive + NStage:dummy_sixthstage
    ## 
    ##                           Df Deviance    AIC
    ## - NStage:dummy_sixthstage  1   2952.1 2998.1
    ## - TumorSize                1   2952.1 2998.1
    ## - AStage                   1   2952.1 2998.1
    ## <none>                         2952.1 3000.1
    ## - dummy_marital            4   2960.3 3000.3
    ## - TStage                   1   2957.2 3003.2
    ## - dummy_race               2   2967.2 3011.2
    ## - EstrogenStatus           1   2969.3 3015.3
    ## - Age                      1   2971.1 3017.1
    ## - ProgesteroneStatus       1   2972.0 3018.0
    ## - RegionalNodeExamined     1   2978.9 3024.9
    ## - RegionalNodePositive     1   2979.1 3025.1
    ## - dummy_differentiate      3   2986.4 3028.4
    ## 
    ## Step:  AIC=2998.1
    ## Status ~ Age + dummy_race + dummy_marital + TStage + NStage + 
    ##     dummy_sixthstage + dummy_differentiate + AStage + TumorSize + 
    ##     EstrogenStatus + ProgesteroneStatus + RegionalNodeExamined + 
    ##     RegionalNodePositive
    ## 
    ##                        Df Deviance    AIC
    ## - dummy_sixthstage      4   2957.2 2995.2
    ## - TumorSize             1   2952.1 2996.1
    ## - AStage                1   2952.1 2996.1
    ## <none>                      2952.1 2998.1
    ## - dummy_marital         4   2960.3 2998.3
    ## - TStage                1   2957.2 3001.2
    ## - NStage                1   2960.6 3004.6
    ## - dummy_race            2   2967.2 3009.2
    ## - EstrogenStatus        1   2969.3 3013.3
    ## - Age                   1   2971.1 3015.1
    ## - ProgesteroneStatus    1   2972.1 3016.1
    ## - RegionalNodeExamined  1   2978.9 3022.9
    ## - RegionalNodePositive  1   2979.1 3023.1
    ## - dummy_differentiate   3   2986.4 3026.4
    ## 
    ## Step:  AIC=2995.17
    ## Status ~ Age + dummy_race + dummy_marital + TStage + NStage + 
    ##     dummy_differentiate + AStage + TumorSize + EstrogenStatus + 
    ##     ProgesteroneStatus + RegionalNodeExamined + RegionalNodePositive
    ## 
    ##                        Df Deviance    AIC
    ## - AStage                1   2957.2 2993.2
    ## - TumorSize             1   2957.5 2993.5
    ## <none>                      2957.2 2995.2
    ## - dummy_marital         4   2965.5 2995.5
    ## - NStage                1   2967.8 3003.8
    ## - dummy_race            2   2972.5 3006.5
    ## - TStage                1   2970.8 3006.8
    ## - EstrogenStatus        1   2975.0 3011.0
    ## - Age                   1   2975.8 3011.8
    ## - ProgesteroneStatus    1   2976.7 3012.7
    ## - RegionalNodePositive  1   2983.3 3019.3
    ## - RegionalNodeExamined  1   2983.4 3019.4
    ## - dummy_differentiate   3   2991.2 3023.2
    ## 
    ## Step:  AIC=2993.18
    ## Status ~ Age + dummy_race + dummy_marital + TStage + NStage + 
    ##     dummy_differentiate + TumorSize + EstrogenStatus + ProgesteroneStatus + 
    ##     RegionalNodeExamined + RegionalNodePositive
    ## 
    ##                        Df Deviance    AIC
    ## - TumorSize             1   2957.6 2991.6
    ## <none>                      2957.2 2993.2
    ## - dummy_marital         4   2965.6 2993.6
    ## - NStage                1   2968.0 3002.0
    ## - dummy_race            2   2972.5 3004.5
    ## - TStage                1   2971.7 3005.7
    ## - EstrogenStatus        1   2975.1 3009.1
    ## - Age                   1   2975.8 3009.8
    ## - ProgesteroneStatus    1   2976.7 3010.7
    ## - RegionalNodePositive  1   2983.4 3017.4
    ## - RegionalNodeExamined  1   2983.5 3017.5
    ## - dummy_differentiate   3   2991.2 3021.2
    ## 
    ## Step:  AIC=2991.57
    ## Status ~ Age + dummy_race + dummy_marital + TStage + NStage + 
    ##     dummy_differentiate + EstrogenStatus + ProgesteroneStatus + 
    ##     RegionalNodeExamined + RegionalNodePositive
    ## 
    ##                        Df Deviance    AIC
    ## <none>                      2957.6 2991.6
    ## - dummy_marital         4   2966.0 2992.0
    ## - NStage                1   2968.2 3000.2
    ## - dummy_race            2   2972.9 3002.9
    ## - EstrogenStatus        1   2975.5 3007.5
    ## - Age                   1   2976.5 3008.5
    ## - ProgesteroneStatus    1   2976.9 3008.9
    ## - RegionalNodePositive  1   2983.7 3015.7
    ## - RegionalNodeExamined  1   2983.7 3015.7
    ## - TStage                1   2984.8 3016.8
    ## - dummy_differentiate   3   2991.6 3019.6

    ## 
    ## Call:  glm(formula = Status ~ Age + dummy_race + dummy_marital + TStage + 
    ##     NStage + dummy_differentiate + EstrogenStatus + ProgesteroneStatus + 
    ##     RegionalNodeExamined + RegionalNodePositive, family = "binomial", 
    ##     data = data)
    ## 
    ## Coefficients:
    ##                                               (Intercept)  
    ##                                                  -3.42103  
    ##                                                       Age  
    ##                                                   0.02415  
    ##                                       dummy_raceRaceBlack  
    ##                                                   0.51463  
    ##                                       dummy_raceRaceOther  
    ##                                                  -0.41133  
    ##                                       dummy_raceRaceWhite  
    ##                                                        NA  
    ##                        dummy_maritalMaritalStatusDivorced  
    ##                                                  -0.01446  
    ##                         dummy_maritalMaritalStatusMarried  
    ##                                                  -0.22613  
    ##                       dummy_maritalMaritalStatusSeparated  
    ##                                                   0.67255  
    ##                         dummy_maritalMaritalStatusSingle   
    ##                                                  -0.06777  
    ##                         dummy_maritalMaritalStatusWidowed  
    ##                                                        NA  
    ##                                                    TStage  
    ##                                                   0.31962  
    ##                                                    NStage  
    ##                                                   0.35062  
    ## dummy_differentiatedifferentiateModerately differentiated  
    ##                                                   0.54024  
    ##     dummy_differentiatedifferentiatePoorly differentiated  
    ##                                                   0.92900  
    ##          dummy_differentiatedifferentiateUndifferentiated  
    ##                                                   1.83146  
    ##       dummy_differentiatedifferentiateWell differentiated  
    ##                                                        NA  
    ##                                            EstrogenStatus  
    ##                                                  -0.75540  
    ##                                        ProgesteroneStatus  
    ##                                                  -0.57503  
    ##                                      RegionalNodeExamined  
    ##                                                  -0.03531  
    ##                                      RegionalNodePositive  
    ##                                                   0.07311  
    ## 
    ## Degrees of Freedom: 4023 Total (i.e. Null);  4007 Residual
    ## Null Deviance:       3445 
    ## Residual Deviance: 2958  AIC: 2992

We use backward elimination to find the best model: Status ~ Age +
dummy_race + dummy_marital + TStage + NStage + dummy_differentiate +
EstrogenStatus + ProgesteroneStatus + RegionalNodeExamined +
RegionalNodePositive

The variables with high correlation: regional node positive and sixth
stage (positive), grade and differentiate (positive), n stage and sixth
stage (positive). None of the two highly correlated variables is
significant at the same time.

# forward selection

    ## Start:  AIC=3202.84
    ## Status ~ 1
    ## 
    ##                        Df Deviance    AIC
    ## + dummy_sixthstage      4   485.19 2918.9
    ## + RegionalNodePositive  1   487.34 2930.7
    ## + NStage                1   487.57 2932.6
    ## + EstrogenStatus        1   503.91 3065.2
    ## + ProgesteroneStatus    1   505.34 3076.6
    ## + dummy_differentiate   3   507.11 3094.7
    ## + Grade                 1   508.11 3098.6
    ## + TStage                1   509.22 3107.4
    ## + TumorSize             1   512.31 3131.7
    ## + AStage                1   516.84 3167.1
    ## + dummy_race            2   518.08 3178.8
    ## + dummy_marital         4   518.04 3182.5
    ## + Age                   1   520.07 3192.2
    ## + RegionalNodeExamined  1   521.07 3200.0
    ## <none>                      521.70 3202.8
    ## 
    ## Step:  AIC=2918.85
    ## Status ~ dummy_sixthstage
    ## 
    ##                        Df Deviance    AIC
    ## + EstrogenStatus        1   472.39 2813.3
    ## + ProgesteroneStatus    1   473.30 2821.1
    ## + dummy_differentiate   3   477.32 2859.1
    ## + Grade                 1   478.09 2861.6
    ## + RegionalNodePositive  1   482.23 2896.2
    ## + dummy_race            2   482.01 2896.5
    ## + dummy_marital         4   482.66 2905.8
    ## + Age                   1   483.41 2906.1
    ## + RegionalNodeExamined  1   483.68 2908.4
    ## + NStage                1   483.77 2909.1
    ## + TStage                1   484.76 2917.3
    ## + TumorSize             1   484.90 2918.5
    ## <none>                      485.19 2918.8
    ## + AStage                1   485.14 2920.5
    ## 
    ## Step:  AIC=2813.27
    ## Status ~ dummy_sixthstage + EstrogenStatus
    ## 
    ##                        Df Deviance    AIC
    ## + dummy_differentiate   3   467.93 2781.1
    ## + Grade                 1   468.40 2781.2
    ## + ProgesteroneStatus    1   468.81 2784.7
    ## + RegionalNodePositive  1   469.44 2790.1
    ## + dummy_race            2   469.58 2793.3
    ## + Age                   1   469.99 2794.8
    ## + dummy_marital         4   470.06 2801.4
    ## + RegionalNodeExamined  1   470.77 2801.5
    ## + NStage                1   471.17 2804.9
    ## + TStage                1   471.94 2811.5
    ## <none>                      472.39 2813.3
    ## + TumorSize             1   472.15 2813.3
    ## + AStage                1   472.37 2815.2
    ## 
    ## Step:  AIC=2781.09
    ## Status ~ dummy_sixthstage + EstrogenStatus + dummy_differentiate
    ## 
    ##                        Df Deviance    AIC
    ## + ProgesteroneStatus    1   464.80 2756.1
    ## + RegionalNodePositive  1   464.89 2756.9
    ## + Age                   1   464.95 2757.4
    ## + dummy_race            2   465.48 2764.0
    ## + RegionalNodeExamined  1   466.23 2768.5
    ## + dummy_marital         4   465.66 2769.6
    ## + NStage                1   466.69 2772.4
    ## + TStage                1   467.57 2780.1
    ## <none>                      467.93 2781.1
    ## + TumorSize             1   467.75 2781.6
    ## + AStage                1   467.90 2782.9
    ## 
    ## Step:  AIC=2756.12
    ## Status ~ dummy_sixthstage + EstrogenStatus + dummy_differentiate + 
    ##     ProgesteroneStatus
    ## 
    ##                        Df Deviance    AIC
    ## + RegionalNodePositive  1   461.67 2730.9
    ## + Age                   1   462.21 2735.7
    ## + dummy_race            2   462.39 2739.2
    ## + RegionalNodeExamined  1   463.24 2744.6
    ## + dummy_marital         4   462.74 2746.3
    ## + NStage                1   463.48 2746.7
    ## + TStage                1   464.47 2755.3
    ## <none>                      464.80 2756.1
    ## + TumorSize             1   464.66 2756.9
    ## + AStage                1   464.76 2757.8
    ## 
    ## Step:  AIC=2730.95
    ## Status ~ dummy_sixthstage + EstrogenStatus + dummy_differentiate + 
    ##     ProgesteroneStatus + RegionalNodePositive
    ## 
    ##                                         Df Deviance    AIC
    ## + RegionalNodeExamined                   1   458.47 2704.9
    ## + Age                                    1   459.21 2711.4
    ## + dummy_race                             2   459.20 2713.3
    ## + dummy_marital                          4   459.76 2722.2
    ## + TStage                                 1   460.82 2725.5
    ## + NStage                                 1   461.27 2729.4
    ## + TumorSize                              1   461.29 2729.6
    ## <none>                                       461.67 2730.9
    ## + AStage                                 1   461.61 2732.4
    ## + dummy_sixthstage:RegionalNodePositive  4   461.42 2736.8
    ## 
    ## Step:  AIC=2704.91
    ## Status ~ dummy_sixthstage + EstrogenStatus + dummy_differentiate + 
    ##     ProgesteroneStatus + RegionalNodePositive + RegionalNodeExamined
    ## 
    ##                                         Df Deviance    AIC
    ## + Age                                    1   456.20 2686.9
    ## + dummy_race                             2   456.06 2687.7
    ## + dummy_marital                          4   456.61 2696.6
    ## + TStage                                 1   457.62 2699.5
    ## + TumorSize                              1   458.11 2703.7
    ## + NStage                                 1   458.11 2703.8
    ## <none>                                       458.47 2704.9
    ## + AStage                                 1   458.42 2706.5
    ## + dummy_sixthstage:RegionalNodePositive  4   458.33 2711.7
    ## 
    ## Step:  AIC=2686.95
    ## Status ~ dummy_sixthstage + EstrogenStatus + dummy_differentiate + 
    ##     ProgesteroneStatus + RegionalNodePositive + RegionalNodeExamined + 
    ##     Age
    ## 
    ##                                         Df Deviance    AIC
    ## + dummy_race                             2   453.86 2670.2
    ## + TStage                                 1   455.20 2680.2
    ## + dummy_marital                          4   454.62 2681.0
    ## + TumorSize                              1   455.71 2684.6
    ## + NStage                                 1   455.85 2685.9
    ## <none>                                       456.20 2686.9
    ## + AStage                                 1   456.13 2688.3
    ## + dummy_sixthstage:RegionalNodePositive  4   456.10 2694.1
    ## 
    ## Step:  AIC=2670.23
    ## Status ~ dummy_sixthstage + EstrogenStatus + dummy_differentiate + 
    ##     ProgesteroneStatus + RegionalNodePositive + RegionalNodeExamined + 
    ##     Age + dummy_race
    ## 
    ##                                         Df Deviance    AIC
    ## + TStage                                 1   452.82 2663.0
    ## + TumorSize                              1   453.35 2667.8
    ## + dummy_marital                          4   452.70 2668.0
    ## + NStage                                 1   453.57 2669.7
    ## <none>                                       453.86 2670.2
    ## + AStage                                 1   453.78 2671.6
    ## + dummy_sixthstage:RegionalNodePositive  4   453.76 2677.4
    ## 
    ## Step:  AIC=2663.03
    ## Status ~ dummy_sixthstage + EstrogenStatus + dummy_differentiate + 
    ##     ProgesteroneStatus + RegionalNodePositive + RegionalNodeExamined + 
    ##     Age + dummy_race + TStage
    ## 
    ##                                         Df Deviance    AIC
    ## + NStage                                 1   451.57 2653.9
    ## + dummy_marital                          4   451.68 2660.9
    ## <none>                                       452.82 2663.0
    ## + AStage                                 1   452.78 2664.7
    ## + TumorSize                              1   452.81 2665.0
    ## + dummy_sixthstage:RegionalNodePositive  4   452.49 2668.1
    ## 
    ## Step:  AIC=2653.95
    ## Status ~ dummy_sixthstage + EstrogenStatus + dummy_differentiate + 
    ##     ProgesteroneStatus + RegionalNodePositive + RegionalNodeExamined + 
    ##     Age + dummy_race + TStage + NStage
    ## 
    ##                                         Df Deviance    AIC
    ## + dummy_marital                          4   450.46 2652.0
    ## <none>                                       451.57 2653.9
    ## + NStage:dummy_sixthstage                1   451.55 2655.8
    ## + AStage                                 1   451.56 2655.8
    ## + TumorSize                              1   451.57 2655.9
    ## + dummy_sixthstage:RegionalNodePositive  4   451.42 2660.6
    ## 
    ## Step:  AIC=2652.02
    ## Status ~ dummy_sixthstage + EstrogenStatus + dummy_differentiate + 
    ##     ProgesteroneStatus + RegionalNodePositive + RegionalNodeExamined + 
    ##     Age + dummy_race + TStage + NStage + dummy_marital
    ## 
    ##                                         Df Deviance    AIC
    ## <none>                                       450.46 2652.0
    ## + NStage:dummy_sixthstage                1   450.44 2653.8
    ## + AStage                                 1   450.45 2653.9
    ## + TumorSize                              1   450.46 2654.0
    ## + dummy_sixthstage:RegionalNodePositive  4   450.31 2658.7

    ## 
    ## Call:  glm(formula = Status ~ dummy_sixthstage + EstrogenStatus + dummy_differentiate + 
    ##     ProgesteroneStatus + RegionalNodePositive + RegionalNodeExamined + 
    ##     Age + dummy_race + TStage + NStage + dummy_marital, data = data)
    ## 
    ## Coefficients:
    ##                                               (Intercept)  
    ##                                                 -0.122696  
    ##                             dummy_sixthstageSixthStageIIA  
    ##                                                  0.115965  
    ##                             dummy_sixthstageSixthStageIIB  
    ##                                                  0.101006  
    ##                            dummy_sixthstageSixthStageIIIA  
    ##                                                  0.042335  
    ##                            dummy_sixthstageSixthStageIIIB  
    ##                                                  0.079491  
    ##                            dummy_sixthstageSixthStageIIIC  
    ##                                                        NA  
    ##                                            EstrogenStatus  
    ##                                                 -0.141769  
    ## dummy_differentiatedifferentiateModerately differentiated  
    ##                                                  0.039389  
    ##     dummy_differentiatedifferentiatePoorly differentiated  
    ##                                                  0.091698  
    ##          dummy_differentiatedifferentiateUndifferentiated  
    ##                                                  0.276228  
    ##       dummy_differentiatedifferentiateWell differentiated  
    ##                                                        NA  
    ##                                        ProgesteroneStatus  
    ##                                                 -0.077982  
    ##                                      RegionalNodePositive  
    ##                                                  0.012110  
    ##                                      RegionalNodeExamined  
    ##                                                 -0.003596  
    ##                                                       Age  
    ##                                                  0.002665  
    ##                                       dummy_raceRaceBlack  
    ##                                                  0.069889  
    ##                                       dummy_raceRaceOther  
    ##                                                 -0.041506  
    ##                                       dummy_raceRaceWhite  
    ##                                                        NA  
    ##                                                    TStage  
    ##                                                  0.053278  
    ##                                                    NStage  
    ##                                                  0.089427  
    ##                        dummy_maritalMaritalStatusDivorced  
    ##                                                 -0.006531  
    ##                         dummy_maritalMaritalStatusMarried  
    ##                                                 -0.032365  
    ##                       dummy_maritalMaritalStatusSeparated  
    ##                                                  0.094832  
    ##                         dummy_maritalMaritalStatusSingle   
    ##                                                 -0.016192  
    ##                         dummy_maritalMaritalStatusWidowed  
    ##                                                        NA  
    ## 
    ## Degrees of Freedom: 4023 Total (i.e. Null);  4003 Residual
    ## Null Deviance:       521.7 
    ## Residual Deviance: 450.5     AIC: 2652

When we use forward selection to find the best model: Status ~
dummy_sixthstage + EstrogenStatus + dummy_differentiate +
ProgesteroneStatus + RegionalNodePositive + RegionalNodeExamined + Age +
dummy_race + TStage + NStage + dummy_marital

When using forward selection, our model have one more variable:
dummy_sixthstage. Both model is good. Base on the principle of
parsimony, we will choose the backward model with fewer variables.

    ## 
    ## Call:
    ## glm(formula = Status ~ Age + dummy_race + dummy_marital + TStage + 
    ##     NStage + dummy_differentiate + EstrogenStatus + ProgesteroneStatus + 
    ##     RegionalNodeExamined + RegionalNodePositive, family = "binomial", 
    ##     data = data)
    ## 
    ## Coefficients: (3 not defined because of singularities)
    ##                                                            Estimate Std. Error
    ## (Intercept)                                               -3.421027   0.483526
    ## Age                                                        0.024154   0.005596
    ## dummy_raceRaceBlack                                        0.514626   0.161628
    ## dummy_raceRaceOther                                       -0.411328   0.202354
    ## dummy_raceRaceWhite                                              NA         NA
    ## dummy_maritalMaritalStatusDivorced                        -0.014456   0.220864
    ## dummy_maritalMaritalStatusMarried                         -0.226128   0.192180
    ## dummy_maritalMaritalStatusSeparated                        0.672553   0.408694
    ## dummy_maritalMaritalStatusSingle                          -0.067772   0.218100
    ## dummy_maritalMaritalStatusWidowed                                NA         NA
    ## TStage                                                     0.319621   0.060830
    ## NStage                                                     0.350618   0.106903
    ## dummy_differentiatedifferentiateModerately differentiated  0.540236   0.183580
    ## dummy_differentiatedifferentiatePoorly differentiated      0.929003   0.192168
    ## dummy_differentiatedifferentiateUndifferentiated           1.831462   0.550474
    ## dummy_differentiatedifferentiateWell differentiated              NA         NA
    ## EstrogenStatus                                            -0.755401   0.177329
    ## ProgesteroneStatus                                        -0.575026   0.127436
    ## RegionalNodeExamined                                      -0.035310   0.007136
    ## RegionalNodePositive                                       0.073108   0.014335
    ##                                                           z value Pr(>|z|)    
    ## (Intercept)                                                -7.075 1.49e-12 ***
    ## Age                                                         4.316 1.59e-05 ***
    ## dummy_raceRaceBlack                                         3.184 0.001452 ** 
    ## dummy_raceRaceOther                                        -2.033 0.042081 *  
    ## dummy_raceRaceWhite                                            NA       NA    
    ## dummy_maritalMaritalStatusDivorced                         -0.065 0.947813    
    ## dummy_maritalMaritalStatusMarried                          -1.177 0.239336    
    ## dummy_maritalMaritalStatusSeparated                         1.646 0.099843 .  
    ## dummy_maritalMaritalStatusSingle                           -0.311 0.756000    
    ## dummy_maritalMaritalStatusWidowed                              NA       NA    
    ## TStage                                                      5.254 1.49e-07 ***
    ## NStage                                                      3.280 0.001039 ** 
    ## dummy_differentiatedifferentiateModerately differentiated   2.943 0.003253 ** 
    ## dummy_differentiatedifferentiatePoorly differentiated       4.834 1.34e-06 ***
    ## dummy_differentiatedifferentiateUndifferentiated            3.327 0.000878 ***
    ## dummy_differentiatedifferentiateWell differentiated            NA       NA    
    ## EstrogenStatus                                             -4.260 2.05e-05 ***
    ## ProgesteroneStatus                                         -4.512 6.41e-06 ***
    ## RegionalNodeExamined                                       -4.948 7.50e-07 ***
    ## RegionalNodePositive                                        5.100 3.40e-07 ***
    ## ---
    ## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
    ## 
    ## (Dispersion parameter for binomial family taken to be 1)
    ## 
    ##     Null deviance: 3444.7  on 4023  degrees of freedom
    ## Residual deviance: 2957.6  on 4007  degrees of freedom
    ## AIC: 2991.6
    ## 
    ## Number of Fisher Scoring iterations: 5

our model:
$ln\frac{Y}{1-Y}=-1.589565+0.024154X_{age}+0.514626X_{raceblack}-0.411328X_{raceother}+0.672553X_{Separated}+0.319621X_{Tstage}+0.350618X_{Nstage}+0.540236X_{Moderately differentiated}+0.929003X_{Poorly differentiated}+1.831462X_{Undifferentiated}-0.755401X_{EstrogenStatus}-0.575026X_{ProgesteroneStatus}-0.035310X_{RegionalNodeExamined}+0.073108X_{RegionalNodePositive}$

## Model Diagnostics

Assumption: 1. Linearity: The relationship between X and the mean of Y
is linear.

2.  Homoscedasticity: The variance of residual is the same for any value
    of X.

3.  Independence: Observations are independent of each other.

4.  Normality: For any fixed value of X, Y is normally distributed.

<!-- -->

    ## ── Attaching core tidyverse packages ──────────────────────── tidyverse 2.0.0 ──
    ## ✔ forcats   1.0.0     ✔ stringr   1.5.1
    ## ✔ lubridate 1.9.3     ✔ tibble    3.2.1
    ## ✔ purrr     1.0.2     ✔ tidyr     1.3.0
    ## ✔ readr     2.1.4     
    ## ── Conflicts ────────────────────────────────────────── tidyverse_conflicts() ──
    ## ✖ tidyr::expand() masks Matrix::expand()
    ## ✖ dplyr::filter() masks stats::filter()
    ## ✖ dplyr::lag()    masks stats::lag()
    ## ✖ purrr::lift()   masks caret::lift()
    ## ✖ tidyr::pack()   masks Matrix::pack()
    ## ✖ tidyr::unpack() masks Matrix::unpack()
    ## ℹ Use the conflicted package (<http://conflicted.r-lib.org/>) to force all conflicts to become errors

    ## Warning: attributes are not identical across measure variables; they will be
    ## dropped

    ## `geom_smooth()` using formula = 'y ~ x'

![](BM_FinalProject_files/figure-gfm/unnamed-chunk-11-1.png)<!-- --> The
variables differentiate, sixth stage (not included in the model), N
stage, Regional Node Examined are not quite linearly associated with the
survival outcome.

![](BM_FinalProject_files/figure-gfm/unnamed-chunk-12-1.png)<!-- -->

    ## # A tibble: 3 × 18
    ##   Status   Age dummy_race[,"RaceBlack"] dummy_marital[,"MaritalS…¹ TStage NStage
    ##    <dbl> <dbl>                    <dbl>                      <dbl>  <dbl>  <dbl>
    ## 1      1    58                        0                          0      1      2
    ## 2      0    43                        0                          0      4      3
    ## 3      1    49                        0                          0      2      1
    ## # ℹ abbreviated name: ¹​dummy_marital[,"MaritalStatusDivorced"]
    ## # ℹ 14 more variables: dummy_race[2:3] <dbl>, dummy_marital[2:5] <dbl>,
    ## #   dummy_differentiate <dbl[,4]>, EstrogenStatus <dbl>,
    ## #   ProgesteroneStatus <dbl>, RegionalNodeExamined <dbl>,
    ## #   RegionalNodePositive <dbl>, .fitted <dbl>, .resid <dbl>, .hat <dbl>,
    ## #   .sigma <dbl>, .cooksd <dbl>, .std.resid <dbl>, index <int>

![](BM_FinalProject_files/figure-gfm/unnamed-chunk-12-2.png)<!-- -->

    ## # A tibble: 0 × 18
    ## # ℹ 18 variables: Status <dbl>, Age <dbl>, dummy_race <dbl[,3]>,
    ## #   dummy_marital <dbl[,5]>, TStage <dbl>, NStage <dbl>,
    ## #   dummy_differentiate <dbl[,4]>, EstrogenStatus <dbl>,
    ## #   ProgesteroneStatus <dbl>, RegionalNodeExamined <dbl>,
    ## #   RegionalNodePositive <dbl>, .fitted <dbl>, .resid <dbl>, .hat <dbl>,
    ## #   .sigma <dbl>, .cooksd <dbl>, .std.resid <dbl>, index <int>

No potential influential data points with abs(.std.res) \> 3

    ## Loading required package: carData

    ## 
    ## Attaching package: 'car'

    ## The following object is masked from 'package:purrr':
    ## 
    ##     some

    ## The following object is masked from 'package:dplyr':
    ## 
    ##     recode

    ##                          GVIF Df GVIF^(1/(2*Df))
    ## Age                  1.104371  1        1.050891
    ## differentiate        1.109705  3        1.017500
    ## MaritalStatus        1.120622  4        1.014337
    ## Race                 1.061138  2        1.014946
    ## TStage               1.078406  1        1.038463
    ## NStage               3.314460  1        1.820566
    ## EstrogenStatus       1.472938  1        1.213647
    ## ProgesteroneStatus   1.425166  1        1.193803
    ## RegionalNodeExamined 1.470563  1        1.212668
    ## RegionalNodePositive 3.757434  1        1.938410

There are no VIF values that exceeds 5 or 10. Thus, there is no
problematic amount of collinearity.

## Model Validation

    ##   parameter  Accuracy     Kappa AccuracySD    KappaSD
    ## 1      none 0.8548811 0.1870871 0.01169298 0.06326696

The accuracy is 0.8568607 which means the model correctly predicted the
outcome 85.68607% of the time.

# check model validation by Race

    ##   parameter  Accuracy     Kappa  AccuracySD    KappaSD
    ## 1      none 0.8605323 0.2012449 0.008775235 0.06295797

    ## Warning in predict.lm(object, newdata, se.fit, scale = 1, type = if (type == :
    ## prediction from rank-deficient fit; attr(*, "non-estim") has doubtful cases

    ## Warning in predict.lm(object, newdata, se.fit, scale = 1, type = if (type == :
    ## prediction from rank-deficient fit; attr(*, "non-estim") has doubtful cases

    ## Warning in predict.lm(object, newdata, se.fit, scale = 1, type = if (type == :
    ## prediction from rank-deficient fit; attr(*, "non-estim") has doubtful cases

    ## Warning in predict.lm(object, newdata, se.fit, scale = 1, type = if (type == :
    ## prediction from rank-deficient fit; attr(*, "non-estim") has doubtful cases

    ## Warning in predict.lm(object, newdata, se.fit, scale = 1, type = if (type == :
    ## prediction from rank-deficient fit; attr(*, "non-estim") has doubtful cases

    ## Warning in predict.lm(object, newdata, se.fit, scale = 1, type = if (type == :
    ## prediction from rank-deficient fit; attr(*, "non-estim") has doubtful cases

    ## Warning in predict.lm(object, newdata, se.fit, scale = 1, type = if (type == :
    ## prediction from rank-deficient fit; attr(*, "non-estim") has doubtful cases

    ## Warning in predict.lm(object, newdata, se.fit, scale = 1, type = if (type == :
    ## prediction from rank-deficient fit; attr(*, "non-estim") has doubtful cases

    ## Warning in predict.lm(object, newdata, se.fit, scale = 1, type = if (type == :
    ## prediction from rank-deficient fit; attr(*, "non-estim") has doubtful cases

    ## Warning in predict.lm(object, newdata, se.fit, scale = 1, type = if (type == :
    ## prediction from rank-deficient fit; attr(*, "non-estim") has doubtful cases

    ##   parameter  Accuracy     Kappa AccuracySD   KappaSD
    ## 1      none 0.7460591 0.1755638 0.08242946 0.2561228

    ## Warning in predict.lm(object, newdata, se.fit, scale = 1, type = if (type == :
    ## prediction from rank-deficient fit; attr(*, "non-estim") has doubtful cases

    ## Warning in predict.lm(object, newdata, se.fit, scale = 1, type = if (type == :
    ## prediction from rank-deficient fit; attr(*, "non-estim") has doubtful cases

    ## Warning in predict.lm(object, newdata, se.fit, scale = 1, type = if (type == :
    ## prediction from rank-deficient fit; attr(*, "non-estim") has doubtful cases

    ## Warning in predict.lm(object, newdata, se.fit, scale = 1, type = if (type == :
    ## prediction from rank-deficient fit; attr(*, "non-estim") has doubtful cases

    ## Warning in predict.lm(object, newdata, se.fit, scale = 1, type = if (type == :
    ## prediction from rank-deficient fit; attr(*, "non-estim") has doubtful cases

    ## Warning in predict.lm(object, newdata, se.fit, scale = 1, type = if (type == :
    ## prediction from rank-deficient fit; attr(*, "non-estim") has doubtful cases

    ## Warning in predict.lm(object, newdata, se.fit, scale = 1, type = if (type == :
    ## prediction from rank-deficient fit; attr(*, "non-estim") has doubtful cases

    ## Warning in predict.lm(object, newdata, se.fit, scale = 1, type = if (type == :
    ## prediction from rank-deficient fit; attr(*, "non-estim") has doubtful cases

    ## Warning in predict.lm(object, newdata, se.fit, scale = 1, type = if (type == :
    ## prediction from rank-deficient fit; attr(*, "non-estim") has doubtful cases

    ## Warning in predict.lm(object, newdata, se.fit, scale = 1, type = if (type == :
    ## prediction from rank-deficient fit; attr(*, "non-estim") has doubtful cases

    ##   parameter  Accuracy      Kappa AccuracySD   KappaSD
    ## 1      none 0.8874267 0.02736871 0.02212834 0.1594083

The results looks good.

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">

<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>Smart</title>
<meta name="Keywords" content="" />
<meta name="Description" content="" />
<link href="css/default.css" rel="stylesheet" type="text/css" />
</head>
<body>
<div id="header">
-   [Article][]
-   [discussion][Article]
-   [View source][Article]
-   [history][Article]
-   

<form id="search" method="get" action>
<fieldset>
<input name="input1" type="text" id="input1"></input>
<input name="input2" type="submit" id="input2" value="Search"></input>

</fieldset>
</form>
</div>
<div id="content">
<div id="colOne" sty>
<div style="text-align:center; background:#f6f6f6;">
![][]

</div>
<div class="box">
### Nvigation

-   [Main Page][]

</div>
<div class="box">
### Totorials

-   [Build a SMART App][]
-   [App using REST API][]
-   [Background + Helper Apps][Article]
-   [Frame UI Apps][Article]
-   [Got Statins? App][Article]
-   [RxReminder App][Article]

</div>
<div class="box">
### Data Modeling + Querying

-   [Intro to RDF and SPARQL][Article]
-   [SPARQL Examples for SMART][Article]
-   [SMART data: best practices][Article]
-   [$.Deferred for parallel queries][Article]

</div>
<div class="box">
### Reference

-   [Data Model][Article]
-   [REST API][Article]
-   [App Manifest][Article]
-   [Change Log][Article]

</div>
<div class="box">
### Libraries

-   [Javascript][Article]
-   [Python][Article]
-   [Java][Article]
-   [.NET][Article]
-   [Container Javascript][Article]

</div>
<div class="box">
### Presentation (2010-08-26)

-   [Architecture][Article]
-   [Governance][Article]
-   [Demo][Article]

</div>
<div class="box">
### Downloads

-   [Download Source + SMART VM][Article]

</div>
<div class="box">
### Toolbox

-   [What links here][Article]
-   [Related changes][Article]
-   [Upload file][Article]
-   [Special pages][Article]
-   [Printable version][Article]
-   [Permanent link][Article]

</div>
</div>
<div id="colTwo">
<span class="firstHeading">HOWTO Build a SMART App - REST API Calls</span>
--------------------------------------------------------------------------

<big>This document shows you how to build a more advanced SMART App with
server-side logic and REST API Calls. </big>

<big>You should first read the [Main Page][1] and [HOWTO Build a SMART
App][]. </big>

<table id="toc" class="toc" summary="Contents">
<tbody>
<tr>
<td>
<div id="toctitle">
Contents
--------

</div>
-   [<span class="tocnumber">1</span>
    <span class="toctext">ScreenCast</span>][]
-   [<span class="tocnumber">2</span> <span class="toctext">Server to
    Server Authentication</span>][]
    -   [<span class="tocnumber">2.1</span>
        <span class="toctext">OAuth</span>][]
    -   [<span class="tocnumber">2.2</span>
        <span class="toctext">Passing Tokens via URL Parameter</span>][]
    -   [<span class="tocnumber">2.3</span> <span class="toctext">Using
        SMART Client Libraries</span>][]

-   [<span class="tocnumber">3</span> <span class="toctext">Obtaining
    SMART Health Data</span>][]
-   [<span class="tocnumber">4</span> <span class="toctext">What
    Next?</span>][]

</td>
</tr>
</tbody>
</table>

  [Article]: #
  []: images/logo.gif
  [Main Page]: index.html
  [Build a SMART App]: how_to_build.html
  [App using REST API]: how_to_build_rest_api.html
  [1]: index.html "Main Page"
  [HOWTO Build a SMART App]: how_to_build.html "HOWTO Build a SMART App"
  [<span class="tocnumber">1</span>
  <span class="toctext">ScreenCast</span>]: #ScreenCast
  [<span class="tocnumber">2</span> <span class="toctext">Server to
  Server Authentication</span>]: #Server_to_Server_Authentication
  [<span class="tocnumber">2.1</span>
  <span class="toctext">OAuth</span>]: #OAuth
  [<span class="tocnumber">2.2</span> <span class="toctext">Passing
  Tokens via URL Parameter</span>]: #Passing_Tokens_via_URL_Parameter
  [<span class="tocnumber">2.3</span> <span class="toctext">Using SMART
  Client Libraries</span>]: #Using_SMART_Client_Libraries
  [<span class="tocnumber">3</span> <span class="toctext">Obtaining
  SMART Health Data</span>]: #Obtaining_SMART_Health_Data
  [<span class="tocnumber">4</span> <span class="toctext">What
  Next?</span>]: #What_Next.3F

			
		
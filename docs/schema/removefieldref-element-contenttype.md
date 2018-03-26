---


manager: soliver
ms.date: 3/9/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: 5f06a5ba-0b74-497d-a88c-9a104225c0a5
---

![Collapse
section](../icons/collapse_all.gif "Collapse section")![Expand
section](../icons/expand_all.gif "Expand section")![](../icons/collapse_all.gif)![](../icons/expand_all.gif)![](../icons/dropdown.gif)![](../icons/dropdownHover.gif)![Copy
code](../icons/copycode.gif "Copy code")![Copy code
hover](../icons/copycodeHighlight.gif "Copy code hover")
<table>
<tbody>
<tr class="odd">
<td align="left"></td>
</tr>
</tbody>
</table>

Visual Basic  
C\#  
C++  
JavaScript  

<table>
<tbody>
<tr class="odd">
<td align="left"><span id="runningHeaderText"></span></td>
</tr>
<tr class="even">
<td align="left"># RemoveFieldRef Element (ContentType)</td>
</tr>
<tr class="odd">
<td align="left"><a href="#exampleToggle">Example</a>  <a href="#seeAlsoToggle">See also</a>  <span id="headfeedbackarea" class="feedbackhead"><a href="javascript:SubmitFeedback(&#39;docthis@Microsoft.com&#39;,&#39;&#39;,&#39;&#39;,&#39;&#39;,&#39;1.0.18082.1225&#39;,&#39;%0\dThank%20you%20for%20your%20feedback.%20The%20developer%20writing%20teams%20use%20your%20feedback%20to%20improve%20documentation.%20While%20we%20are%20reviewing%20your%20feedback,%20we%20may%20send%20you%20e-mail%20to%20ask%20for%20clarification%20or%20feedback%20on%20a%20solution.%20We%20do%20not%20use%20your%20e-mail%20address%20for%20any%20other%20purpose%20and%20we%20delete%20it%20after%20we%20finish%20our%20review.%0\AFor%20further%20information%20about%20the%20privacy%20policies%20of%20Microsoft,%20please%20see%20http://privacy.microsoft.com/en-us/default.aspx.%0\A%0\d&#39;,&#39;Customer%20feedback&#39;);">Send feedback</a></span></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"></td>
</tr>
</tbody>
</table>

**Last modified:** March 09, 2015

**Applies to**: SharePoint 2016 | SharePoint Foundation 2013 |
SharePoint Online | SharePoint Server 2013*

Specifies a column reference that is included in the parent content type
but is to be removed from this content type.

You need only specify the ID attribute of the <span
class="keyword">RemoveFieldRef</span> element. SharePoint Foundation
ignores all other attributes of this element.

<span codelanguage="other"></span>
<table>
<colgroup>
<col width="100%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><pre><code>&lt;RemoveFieldRef
  Aggregation=&quot;sum&quot; | &quot;count&quot; | &quot;average&quot; | &quot;min&quot; | &quot;max&quot; | &quot;merge&quot; | &quot;plaintext&quot; | &quot;first&quot; | &quot;last&quot;
  Customization=&quot;Text&quot;
  DefaultValue=&quot;Text&quot;
  Description=&quot;Text&quot;
  DisplayName=&quot;Text&quot;
  Format=&quot;Text&quot;
  Filterable=&quot;TRUE&quot; | &quot;FALSE&quot;
  FilterableNoRecurrence=&quot;TRUE&quot; | &quot;FALSE&quot;
  FromBaseType=&quot;TRUE&quot; | &quot;FALSE&quot;
  Hidden=&quot;TRUE&quot; | &quot;FALSE&quot; | &quot;orResource&quot;
  ID=&quot;Text&quot;
  Locked=&quot;TRUE&quot; | &quot;FALSE&quot;
  Name=&quot;Text&quot;
  Node=&quot;Text&quot;
  NumLines=&quot;Integer&quot;
  PIAttribute=&quot;Text&quot;
  PITarget=&quot;Text&quot;
  PrimaryPIAttribute=&quot;Text&quot;
  ReadOnly=&quot;TRUE&quot; | &quot;FALSE&quot;
  ReadOnlyClient=&quot;TRUE&quot; | &quot;FALSE&quot;
  Required=&quot;TRUE&quot; | &quot;FALSE&quot;
  Sealed=&quot;TRUE&quot; | &quot;FALSE&quot;
  ShowInDisplayForm=&quot;TRUE&quot; | &quot;FALSE&quot;
  ShowInEditForm=&quot;TRUE&quot; | &quot;FALSE&quot;
  ShowInFileDlg=&quot;TRUE&quot; | &quot;FALSE&quot;
  ShowInListSettings=&quot;TRUE&quot; | &quot;FALSE&quot;
  ShowInNewForm=&quot;TRUE&quot; | &quot;FALSE&quot;
  Sortable=&quot;TRUE&quot; | &quot;FALSE&quot; 
  PrimaryPITarget=&quot;Text&quot;
/&gt;</code></pre></td>
</tr>
</tbody>
</table>


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th align="left"><p>Attribute</p></th>
<th align="left"><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><p>**ID**</p></td>
<td align="left"><p>Required **Text**. Specifies the field ID of the column to be removed from this content type.</p></td>
</tr>
</tbody>
</table>


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<table>
<colgroup>
<col width="100%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><p>None.</p></td>
</tr>
</tbody>
</table>


----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<table>
<colgroup>
<col width="100%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><p><a href="fieldrefs-element-contenttype.htm">FieldRefs</a></p></td>
</tr>
</tbody>
</table>


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<table>
<colgroup>
<col width="100%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><p>Minimum: 0</p></td>
</tr>
<tr class="even">
<td align="left"><p>Maximum: No limit</p></td>
</tr>
</tbody>
</table>


----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

If the **RemoveFieldRef** element specifies a
column that is not included in the parent content type, SharePoint
Foundation disregards the element.


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

The following example shows **RemoveFieldRef **
elements specifying several columns to remove from a content type.

<span codelanguage="xmlLang"></span>
XML 
<span class="copyCode" onclick="CopyCode(this)"
onkeypress="CopyCode_CheckKey(this, event)"
onmouseover="ChangeCopyCodeIcon(this)"
onmouseout="ChangeCopyCodeIcon(this)" tabindex="0">![Copy
code](../icons/copycode.gif "Copy code")Copy code</span>
    <FieldRefs>
      <RemoveFieldRef ID="{67df98f4-9dec-48ff-a553-29bece9c5bf4}" Name="Attachments" /> <!-- Attachments -->
      <RemoveFieldRef ID="{f1e020bc-ba26-443f-bf2f-b68715017bbc}" Name="WorkflowVersion" /> <!-- WorkflowVersion -->
      <RemoveFieldRef ID="{bc91a437-52e7-49e1-8c4e-4698904b2b6d}" Name="LinkTitleNoMenu" /> <!-- LinkTitleNoMenu -->
      <RemoveFieldRef ID="{82642ec8-ef9b-478f-acf9-31f7d45fbc31}" Name="LinkTitle" /> <!-- LinkTitle -->
      <RemoveFieldRef ID="{ae069f25-3ac2-4256-b9c3-15dbc15da0e0}" Name="GUID" /> <!-- GUID -->
      <RemoveFieldRef ID="{de8beacf-5505-47cd-80a6-aa44e7ffe2f4}" Name="WorkflowInstanceID" /> <!-- WorkflowInstanceID -->
    </FieldRefs>


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

#### Concepts

<span sdata="link">[Content Type
Definitions](content-type-definitions.htm)</span>

#### Other resources

[Fields and Field
References](http://msdn.microsoft.com/library/6b536c1a-719c-4203-8006-c162de199bfc(Office.15).aspx)

<span sdata="link">[FieldRef Element
(ContentType)](fieldref-element-contenttype.htm)</span>








---
title: Tables API for Python  
description: Tables in Word Documents in Python with Cloud API. Add a table, add a row, extract data from a table
weight: 40
url: /python/tables
---

{{< blocks/products/pf/main-wrap-class >}}
<div id="fh">
<div class="container">
<div class="row">
<h1>Tables in Word Documents with Python</h1>
</div>
</div>
</div>
<div class="wmh">
<div class="container">
<div class="row">
<h1>Tables in Word Documents with Python</h1>
</div>
</div>
</div>
<div id="fm" data-nosnippet="">
<div class="container">
<div class="row">
<p class="navbar-text"><a href="/words/family/">Words Cloud</a> / <a id="sdk" href="/words/python/"> Python</a> / Tables</p>
</div>
</div>
</div>
<div class="wgray">
<div class="container">
<div class="row">
<div class="w"><p>Add or delete a table, add a row or a column,  extract data from a table, - all this and much more you can do with Word documents in Python with Cloud API.</p>
<p>If you have worked in Microsoft Word, then you understand the main concept of working with tables to create text and graphics or showing data in a tabular
	style (similar to a spreadsheet).<br/>
	In a standard document page text, graphics and other content appear in a free-flowing way. The text and images wrap, and one item appears after the next. There is
	no way to control where items appear in the document, and this is where tables become useful. You can use a table to structure content, place text or images
	in one cell and align it accordingly. Furthermore, tables can be nested inside other tables up to any depth with Python API.</p>
<p><strong>Note</strong>: As a prerequisite, you need <a href="https://www.python.org/downloads" target="_blank" rel="noopener">Python</a> and <a href="https://pypi.org/project/aspose-words-cloud" target="_blank" rel="noopener">Words Cloud Python SDK</a> installed on your computer.</p>
<h2>Creating and Formatting Tables with Word</h2>
<p>A table is made up of rows and columns. The intersection of a row and column is called a cell.<br/>
	You can use Cloud API in Python to create a table, format it, apply a style, modify a table in code, insert data into rows and cells.<br/>
	A table is imported as a Table node from any document loaded into the Cloud Storage. Aspose.Words.Tables namespace contains classes that represent tables,
	rows, cells and their formatting.</p>
<h3>Table manipulation in Python</h3>
<p>You can perform the following tasks with tables in DOCX, DOC, RTF and document file formats using Python:</p>
<ul>
<li>Add or delete a table.</li>
<li>Resize a table.</li>
<li>Change columns width in a table.</li>
<li>Change rows height in a table.</li>
<li>Convert a table to text.</li>
<li>Text wrap to surround a picture or a diagram with text.</li>
<li>Add rows or columns to a Table.</li>
<li>Delete rows or columns in a Table.</li>
<li>Change properties of a table, a row or a cell.</li>
</ul>
<h3>Extract data from tables using Python</h3>
<p>Python API allows you to extract text from tables. You can call API methods to get a row or to get a cell from a table.</p>
<h3>Working with borders and margins</h3>
<p>You can set border style, margins and cell padding in tables with Python API. You can use border property to set a border for a table. You can apply borders
	to a table, to each cell or to a single cell.<br/>
	Cell margin represents the number of blank spaces between the content of a cell and the border of a cell. Usually, all cells have the same margin in the
	table.<br/>
	Working with margins, give you the right way to control spacing in a Word table.</p>
<h2>Table properties with Python API</h2>
<p>A table has the following properties:</p>
<h3>AutoFit</h3>
<p>Resize a table, a column or a row using AutoFit option.<br/>
	Turn on AutoFit to adjust tables or columns to fit the size of your content automatically. Otherwise, turn it off for Fixed Column Width option.</p>
<h3>Alignment</h3>
<p>You can align a table between page margins either right, left, or center with Python API.</p>
<h3>Merge a table</h3>
<p>Python API allows you to merge two or more tables into one larger table. After merging tables, you can also merge specific cells within the table.</p>
<h3>Split a table</h3>
<p>It allows you to split a table into two or more tables. It creates smaller tables or adds text between two tables.</p>
<h1>How to work with tables in a DOCX document in Python</h1>
<ol>
<li>Go to the <a target="_blank" href="https://dashboard.aspose.cloud/">Aspose Cloud Dashboard</a>.</li>
<li>Create <a target="_blank" href="https://docs.aspose.cloud/display/storagecloud/Creating+and+Managing+Account">a new Account</a> to access all applications and services or Sign In to your account.</li>
<li>Click on <strong>Applications</strong> in the left menu to get <strong>Client Id</strong> and <strong>Client Secret</strong>.</li>
<li>Check <a target="_blank" href="https://apireference.aspose.cloud/words/#/Tables">API Reference page</a> for the description of APIs parameters.</li>
<li>Install <a href="https://pypi.org/project/aspose-words-cloud" target="_blank" rel="noopener">Python SDK</a>.</li>	<li>Check <a href="https://docs.aspose.cloud/display/wordscloud/Working+with+Tables" target="_blank">Developer Guide</a> to work with tables in a DOCX file in Python.</li>
</ol>
<br/>
<div class="codeblock nf">
<div class="codeheader">Working with tables in a Word document in Python</div>
<pre data-nosnippet><code class="python hljs" >import asposewordscloud
from asposewordscloud.models.requests import InsertTableRequest, GetTableWithoutNodePathRequest
from asposewordscloud import TableInsert

app_sid = '####-####-####-####-####'
app_key = '##################'
words_api = WordsApi(app_sid, app_key)

# Add a table
table = TableInsert(columns_count=3, rows_count=5)
request = InsertTableRequest('sample.docx', table, node_path='sections/0')
words_api.insert_table(request)

# Extract data from table
request = GetTableWithoutNodePathRequest('sample.docx', index=0)
data = words_api.get_table_without_node_path(request)
print(data)

# Edit a cell at row 2, column 3
paragraph = ParagraphInsert(text='Lorem Ipsum')
request = InsertParagraphRequest('sample.docx', paragraph, node_path='sections/0/tables/0/rows/1/cells/2')
words_api.insert_paragraph(request)</code></pre>
</div>
<br /><br /></div>
</div>
</div>
{{< blocks/products/pf/support-learning-resources >}}
{{< blocks/products/pf/slr-tab tabTitle="Learning Resources" tabId="resources" >}}
{{< blocks/products/pf/slr-element name="Documentation" href="https://docs.aspose.cloud/words" >}}
{{< blocks/products/pf/slr-element name="Source Code" href="https://github.com/aspose-words-cloud/aspose-words-cloud-python/" >}}
{{< blocks/products/pf/slr-element name="API References" href="https://apireference.aspose.cloud/words/" >}}
{{< blocks/products/pf/slr-element name="Tutorial Videos" href="https://www.youtube.com/user/asposevideo" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Product Support" tabId="support" >}}
{{< blocks/products/pf/slr-element name="Free Support" href="https://forum.aspose.cloud/c/words" >}}
{{< blocks/products/pf/slr-element name="Paid Support" href="https://helpdesk.aspose.cloud" >}}
{{< blocks/products/pf/slr-element name="Blog" href="https://blog.aspose.cloud/category/words/" >}}
{{< blocks/products/pf/slr-element name="Aspose.Words Blog" href="https://blog.aspose.cloud/category/words/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Why Aspose.Words Cloud for Python?" tabId="success-stories" >}}
{{< blocks/products/pf/slr-element name="Customers List" href="https://company.aspose.cloud/customers" >}}
{{< blocks/products/pf/slr-element name="Security" href="https://company.aspose.cloud/legal/security" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< /blocks/products/pf/support-learning-resources >}}

{{< blocks/products/pf/offers-section pfName="Aspose.Words" >}}

    {{< blocks/products/pf/offers-section-item link="/words/curl/" imgSrc="/sdk/aspose_words-for-curl.png" platform="cURL" >}}
	
    {{< blocks/products/pf/offers-section-item link="/words/net/" imgSrc="/sdk/aspose_words-for-net.png" platform=".NET" >}}
	
    {{< blocks/products/pf/offers-section-item link="/words/java/" imgSrc="/sdk/aspose_words-for-java.png" platform="Java" >}}
	
	{{< blocks/products/pf/offers-section-item link="/words/cpp/" imgSrc="/sdk/aspose_words-for-cpp.png" platform="C++" >}}
	
    {{< blocks/products/pf/offers-section-item link="/words/php/" imgSrc="/sdk/aspose_words-for-php.png" platform="PHP" >}}
	
	{{< blocks/products/pf/offers-section-item link="/words/android/" imgSrc="/sdk/aspose_words-for-android.png" platform="Android" >}}
	
    {{< blocks/products/pf/offers-section-item link="/words/python/" imgSrc="/sdk/aspose_words-for-python.png" platform="Python" >}}
	
    {{< blocks/products/pf/offers-section-item link="/words/ruby/" imgSrc="/sdk/aspose_words-for-ruby.png" platform="Ruby" >}}
	
    {{< blocks/products/pf/offers-section-item link="/words/nodejs/" imgSrc="/sdk/aspose_words-for-node.png" platform="Node.js" >}}
	
	{{< blocks/products/pf/offers-section-item link="/words/swift/" imgSrc="/sdk/aspose_words-for-swift.png" platform="Swift" >}}
	
	{{< blocks/products/pf/offers-section-item link="/words/go/" imgSrc="/sdk/aspose_words-for-go.png" platform="Go" >}}

    {{< blocks/products/pf/offers-section-item link="/words/dart/" imgSrc="/sdk/aspose_words-for-dart.png" platform="Dart" >}}
{{< /blocks/products/pf/offers-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

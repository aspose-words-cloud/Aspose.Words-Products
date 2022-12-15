---
title: Generate Report | C#  
description: Generate report in C#. Use DOCX files as template with easy-to-use syntax to create reports in PDF, DOCX, HTML
weight: 60
url: /net/report
---

{{< blocks/products/pf/main-wrap-class >}}
<div id="fh">
<div class="container">
<div class="row">
<h1>Generate report from a template in C#</h1>
</div>
</div>
</div>
<div class="wmh">
<div class="container">
<div class="row">
<h1>Generate report from a template in C#</h1>
</div>
</div>
</div>
<div id="fm" data-nosnippet="">
<div class="container">
<div class="row">
<p class="navbar-text"><a href="/words/family/">Words Cloud</a> / <a id="sdk" href="/words/net/"> .NET</a> / Report</p>
</div>
</div>
</div>
<div class="wgray">
<div class="container">
<div class="row">
<div class="w"><p>Generate professional print-ready DOCX, DOC, RTF, PDF reports in C# easily with Aspose Reporting Engine. Generate documents and reports based on templates, automate your document-processing systems with .NET SDK.</p>
<h2 class="h2title">Introduction</h2>
<p>It is believed that an application is only as good as the data we can get out of it, that`s why Report Generation has become an essential part of modern software design. In general terms Report Generation is a process that takes required data from some informational environment and exports it to standard document formats such as DOCX, DOC, RTF or PDF. Report generation consists of making a document template with a special placeholder tags that, in the final document, are replaced by data from external data sources.</p>
<h2 class="h2title">Reporting Engine</h2>
<p>Cloud Reporting Engine is a subset of <a href="https://apireference.aspose.cloud/words/#/Report" target="_blank">Aspose Words REST API</a> that allows C# developers to generate reports with an extended set of reporting features. It acts as the middleware between the data layer and the application layer. The most powerful feature of the Reporting Engine is the <a href="https://docs.aspose.com/display/wordsnet/Template+Syntax" target="_blank">LINQ-scripting</a>, used to bind placeholder tags in the report template to the external JSON, XML or CSV data sources and perform data sorting, filtering and grouping on the fly. This approach makes the template syntax plain, flexible and effective.</p>
<p>Since Report Generation is a logged-in service, you need to have an <b>Client Id</b> and <b>Client Secret</b> identifiers to authenticate before being able to use the Aspose Cloud API.</p>
<h2>Automate your document-processing systems with .NET SDK</h2>
<p>Aspose provides the best document-processing capabilities with constantly emerging <a href="/words/family/" target="_blank">Cloud SDK family</a>, targeting mainstream programming languages, and allows developers to:</p>
<ul>
<li>Generate DOCX, DOC, PDF reports in a fast, clear and reliable way.</li>
<li>Automate the report generation process and standardize the results with a consistent style that looks appealing and cool.</li>
<li>Design data visualizations to deliver the best analytical behavior to the end-user and meet his personalized needs.</li>
</ul>
<p>Using our .NET SDK you can easily integrate with Cloud Reporting Engine API and generate highly customized reports. Richly formatted documents like packing slips, inventories, invoices, shipment reports can be constructed on the fly as a part of your application.</p>
<h2>Report Generation Input and Output</h2>
<p>The <b>inputs</b> to the Report Generation process are:</p>
<ul>
<li>The underlying data. A good report generation practice requires data, that is exact, timely, appropriate for the effective supervision and decisions at hand.</li>
<li>The report template, containing static content (text, images, logos, etc.) and special tags with composing LINQ-expressions, that regulate the report generation.</li>
</ul>
<p>The <b>output</b> can be rendered in a variety of document formats: DOCX, DOC, PDF, RTF, HTML, MHTML, TXT and many others.</p>
<h2>Generate Your Report with C# in 3 Steps</h2>
<ul>
<li>Prepare your source data in JSON, XML or CSV formats.</li>
<li>Create a report template.</li>
<li>Write a simple C# application to bind the data to the template and produce the output document.</li>
</ul>
<h2>Preparing a Source Data</h2>
<p>Prepare your data by extracting and transforming your business objects and other data sources to JSON, XML and CSV. Since data is often fragmented and distributed in a variety of formats, creating the appropriate information processing subsystem may be required.</p>
<h2>Creating a Template</h2>
<p>Create a template, containing static content and special tags with <a href="https://docs.aspose.com/display/wordsnet/Template+Syntax" target="_blank">composing LINQ-expressions</a>.</p>
<p>A good Report design should reflect the end-user`s view and the types of questions the user will ask. The type of the data content is the first reason to decide what type of report template you may use. For many decision-makers, diagrams and charts can provide additional insight into certain tendencies that may not be obvious from tabular reports. Therefore, tabular data and graphics can be combined in a single report with the relative weighting determined by end-user preferences and analytical requirements.</p>
<h2>Writing a simple C# code to generate a report</h2>
<p>Writing a C# code is the final step: Cloud Reporting Engine will interpret and apply the composing LINQ-expressions, merging template and data.</p>
<h1>How to generate a report in C#</h1>
<ol>
<li>Install <a href="https://www.nuget.org/packages/Aspose.Words-Cloud/" target="_blank" rel="noopener">NuGet package</a> or use the <a href="https://downloads.aspose.com/words/net/" target="_blank" rel="noopener">direct download</a>.</li>	<li>Go to the <a href="https://dashboard.aspose.cloud/" target="_blank">Aspose Cloud Dashboard</a>.</li>
<li>Create <a href="https://docs.aspose.cloud/display/storagecloud/Creating+and+Managing+Account" target="_blank">a new Account</a> to access all applications and services or Sign In to your account.
	</li>
<li>Click on <strong>Applications</strong> in the left menu to get <strong>Client Id</strong> and <strong>Client Secret</strong>.</li>
<li>Check out the <a href="https://docs.aspose.cloud/display/wordscloud/Working+With+Reports" target="_blank">Developer Guide</a> to working with Reports in C#.
	</li>
<li>Check out our <a href="https://github.com/aspose-words-cloud/aspose-words-cloud-dotnet" target="_blank">GitHub repository</a> for a complete API list along with working examples.
	</li>
<li>Check out the <a href="https://apireference.aspose.cloud/words/#/Report" target="_blank">API Reference page</a> for the description of APIs parameters.
	</li>
</ol>
<br/> <br /><br /></div>
</div>
</div>
<div class="container-fluid">
<div class="row"><div class="wassembly">
<a class="anchor" id="samplecode"></a>
<h2 style="text-align: center;font-size: 42px;">How to make a report generation in C#</h2>
<div class="col-md-6">
<div class="codeblock" data-nosnippet>
<div class="codeheader">Json Data</div>
<pre><code class="json hljs" style="height: 455px;">{
  "client": "Mr.Brown",
  "address": "St.Road 82",
  "orders": [
    {
      "date": "2015-03-05",
      "products": [
        { "name": "Monitor", "price": 2, "quantity": 2},
        { "name": "Computer", "price": 3, "quantity": 1}
      ]
    },
    {
      "date": "2015-03-15",
      "products": [
        { "name": "Monitor", "price": 2, "quantity": 1},
        { "name": "Printer", "price": 1, "quantity": 2},
	{ "name": "Computer", "price": 3, "quantity": 1}
      ]
    }
  ]
}</code></pre>
</div>
</div>
<div class="col-md-6">
<div class="wassemblyimg">
<div class="codeheader">DOCX Template</div>
<img class="lazyload"
			     alt="Template"
			     style="max-height: 455px;"
			     src="/snapshots/aspose-words-assembly-template.png"/>
</div>
</div>
<div class="col-md-6">
<div class="codeblock nf">
<div class="codeheader">Code Sample C#</div>
<pre data-nosnippet><code class="cs hljs" style="height:475px">var appKey = "##################";
var appSid = "####-####-####-####-####";
var wordsApi = new WordsApi(appKey, appSid);

using (var file = File.OpenRead("template.docx"))
{
    var data = File.ReadAllText("data.json");
    var settings = new ReportEngineSettings
    {
        DataSourceType = ReportEngineSettings.DataSourceTypeEnum.Json
    };
    var request = new BuildReportOnlineRequest(file, data, settings);
    var result = wordsApi.BuildReportOnline(request);
    using (var fs = new FileStream("result.docx", FileMode.OpenOrCreate))
    {
      result.CopyTo(fs);
      fs.Flush();
    }
}</code></pre>
</div>
</div>
<div class="col-md-6">
<div class="wassemblyimg">
<div class="codeheader">Result</div>
<img class="lazyload"
			     alt="Result"
			     style="max-height: 475px;"
			     src="/snapshots/aspose-words-assembly-result.png"/>
</div>
</div>
</div>
<br/></div>
</div>
</div>

{{< blocks/products/pf/support-learning-resources >}}
{{< blocks/products/pf/slr-tab tabTitle="Learning Resources" tabId="resources" >}}
{{< blocks/products/pf/slr-element name="Documentation" href="https://docs.aspose.cloud/words" >}}
{{< blocks/products/pf/slr-element name="Source Code" href="https://github.com/aspose-words-cloud/aspose-words-cloud-dotnet/" >}}
{{< blocks/products/pf/slr-element name="API References" href="https://apireference.aspose.cloud/words/" >}}
{{< blocks/products/pf/slr-element name="Tutorial Videos" href="https://www.youtube.com/@AsposeCloud" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Product Support" tabId="support" >}}
{{< blocks/products/pf/slr-element name="Free Support" href="https://forum.aspose.cloud/c/words" >}}
{{< blocks/products/pf/slr-element name="Paid Support" href="https://helpdesk.aspose.cloud" >}}
{{< blocks/products/pf/slr-element name="Blog" href="https://blog.aspose.cloud/category/words/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Why Aspose.Words Cloud for .NET?" tabId="success-stories" >}}
{{< blocks/products/pf/slr-element name="Customers List" href="https://company.aspose.cloud/customers" >}}
{{< blocks/products/pf/slr-element name="Security" href="https://company.aspose.cloud/legal/security" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< /blocks/products/pf/support-learning-resources >}}

{{< blocks/products/pf/offers-section pfName="Aspose.Words" >}}

    {{< blocks/products/pf/offers-section-item link="/words/curl/" imgSrc="/sdk/aspose_words-for-curl.svg" platform="cURL" >}}
	
    {{< blocks/products/pf/offers-section-item link="/words/net/" imgSrc="/sdk/aspose_words-for-net.svg" platform=".NET" >}}
	
    {{< blocks/products/pf/offers-section-item link="/words/java/" imgSrc="/sdk/aspose_words-for-java.svg" platform="Java" >}}
	
	{{< blocks/products/pf/offers-section-item link="/words/cpp/" imgSrc="/sdk/aspose_words-for-cpp.svg" platform="C++" >}}
	
    {{< blocks/products/pf/offers-section-item link="/words/php/" imgSrc="/sdk/aspose_words-for-php.svg" platform="PHP" >}}
	
	{{< blocks/products/pf/offers-section-item link="/words/android/" imgSrc="/sdk/aspose_words-for-android.svg" platform="Android" >}}
	
    {{< blocks/products/pf/offers-section-item link="/words/python/" imgSrc="/sdk/aspose_words-for-python.svg" platform="Python" >}}
	
    {{< blocks/products/pf/offers-section-item link="/words/ruby/" imgSrc="/sdk/aspose_words-for-ruby.svg" platform="Ruby" >}}
	
    {{< blocks/products/pf/offers-section-item link="/words/nodejs/" imgSrc="/sdk/aspose_words-for-node.svg" platform="Node.js" >}}
	
	{{< blocks/products/pf/offers-section-item link="/words/swift/" imgSrc="/sdk/aspose_words-for-swift.svg" platform="Swift" >}}
	
	{{< blocks/products/pf/offers-section-item link="/words/go/" imgSrc="/sdk/aspose_words-for-go.svg" platform="Go" >}}

    {{< blocks/products/pf/offers-section-item link="/words/dart/" imgSrc="/sdk/aspose_words-for-dart.svg" platform="Dart" >}}
{{< /blocks/products/pf/offers-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
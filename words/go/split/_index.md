---
title: Word Document Split API for Go (Golang) 
description: Split Word Documents in Go (Golang) with Cloud API. Split a document into PDF, JPEG, DOCX
weight: 40
url: /go/split
---

{{< blocks/products/pf/main-wrap-class >}}
<div id="fh">
<div class="container">
<div class="row">
<h1>Split Word Documents in Go (Golang)</h1>
</div>
</div>
</div>
<div class="wmh">
<div class="container">
<div class="row">
<h1>Split Word Documents in Go (Golang)</h1>
</div>
</div>
</div>
<div id="fm" data-nosnippet="">
<div class="container">
<div class="row">
<p class="navbar-text"><a href="/words/family/">Words Cloud</a> / <a id="sdk" href="/words/go/"> Go</a> / Split</p>
</div>
</div>
</div>
<div class="wgray">
<div class="container">
<div class="row">
<div class="w"><p>Words Cloud Go SDK provides an easy to use API to split DOCX, RTF, ODT and other file formats.<br/>
	Cloud API has many split page features, such as:</p>
<ul>
<li>Split pages no matter the length or file size.</li>
<li>Split page range.</li>
<li>Save as PDF, JPG, HTML, etc.</li>
</ul>
<h2>Overview</h2>
<p>Use Go to split a Word document into multiple smaller files, or to extract pages to a new file.</p>
<p><strong>Tip</strong>: <a href="/words/go/merge" target="_blank">Merging</a> different Word documents is also possible.<br/>
</p>
<h3>Why split a Word document using Go?</h3>
<p>While working with your documents, you may come across scenarios where you want to split large documents into smaller
	ones.<br/>
	When scanning books, images or articles, you need to do it fast and all together. But in the end, you may want to
	separate pages
	of a Word document or any other document.<br/>
	By splitting a document, you don’t need to send or print information you don’t want to.</p>
<h3>What does split API for Go do?</h3>
<ul>
<li>Multi-page Word documents are divided into separate Word documents.</li>
<li>Split operation divides a multi-page Word document by page number, odd/even pages and by page range (entering the
		page range can be divided according to the page number of documents).
	</li>
<li>Split one big file into many smaller, one-page files. You can split them into multiple files, in various page
		ranges.
	</li>
<li>Keep style and layout of the source document.</li>
</ul>
<h2>Where and how?</h2>
<p>Luckily for you, Words Cloud API has the answer.<br/>
	The ability to split documents is one of four main feature areas of Words Cloud. It provides the simplest API
	to split a Word document within MS Word documents or other file formats.<br/>
	Using an API client is the quickest way for a Go developer to speed up the development. API takes care of
	low-level details to make requests and handle responses.
	And this lets you focus on writing code specific to your particular project.<br/>
</p>
<h3>Getting Started</h3>
<ul>
<li>Go through our <a href="https://docs.aspose.cloud/display/wordscloud/Splitting+a+Document" target="_blank">guide
		to split a document</a> to get you started in no time.
	</li>
<li>Check out our <a href="https://github.com/aspose-words-cloud/aspose-words-cloud-go" target="_blank">GitHub repository</a> for a complete API list along with
		working examples.
	</li>
<li>Try our <a href="http://products.aspose.app/words/splitter" target="_blank">free online Splitter</a>.</li>
</ul>
<h2>How to Split a DOCX document in Go</h2>
<ol>
<li>Install the latest version of <a href="https://github.com/aspose-words-cloud/aspose-words-cloud-go" target="_blank" rel="noopener">Go library</a>.</li>	<li>Go to the <a href="https://dashboard.aspose.cloud/" target="_blank">Aspose Cloud Dashboard</a>.</li>
<li>Create <a href="https://docs.aspose.cloud/display/storagecloud/Creating+and+Managing+Account" target="_blank">a
		new Account</a> to access all applications and services or Sign In to your account.
	</li>
<li>Click on <strong>Applications</strong> in the left menu to get <strong>Client Id</strong> and <strong>Client Secret</strong>.</li>
<li>Check <a href="https://docs.aspose.cloud/display/wordscloud/Splitting+a+Document" target="_blank">Developer
		Guide</a> to split a DOCX file in Go.
	</li>
<li>Check <a href="https://apireference.aspose.cloud/words/#/Split" target="_blank">API Reference page</a> for the
		description of APIs parameters.
	</li>
</ol>
<br/>
<div class="codeblock nf">
<div class="codeheader">Split a Word document in Go</div>
<pre data-nosnippet><code class="go hljs" >config, _ := models.NewConfiguration("config.json")
wordsApi, ctx, _ := api.CreateWordsApi(config)

// Split all pages and save to PDF
wordsApi.SplitDocument(ctx, "sample.docx", "pdf", nil)

// Split page range 2-5 and save to JPEG
options := map[string]interface{}{ "from": 2, "to": 5 }
wordsApi.SplitDocument(ctx, "sample.docx", "jpeg", options)

// Split all pages, save to HTML and zip output files
options2 := map[string]interface{}{ "zipOutput": true }
wordsApi.SplitDocument(ctx, "sample.docx", "html", options2)</code></pre>
</div>
<div class="codeblock nf" data-nosnippet>
<div class="codeheader">Config.json</div>
<pre><code class="json hljs" style="max-height: 300px;">{
	"AppKey": "##################",
	"AppSid": "####-####-####-####-####"
}</code></pre>
</div>
<br /><br /></div>
</div>
</div>

{{< blocks/products/pf/support-learning-resources >}}
{{< blocks/products/pf/slr-tab tabTitle="Learning Resources" tabId="resources" >}}
{{< blocks/products/pf/slr-element name="Documentation" href="https://docs.aspose.cloud/words" >}}
{{< blocks/products/pf/slr-element name="Source Code" href="https://github.com/aspose-words-cloud/aspose-words-cloud-go/" >}}
{{< blocks/products/pf/slr-element name="API References" href="https://apireference.aspose.cloud/words/" >}}
{{< blocks/products/pf/slr-element name="Tutorial Videos" href="https://www.youtube.com/user/asposevideo" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Product Support" tabId="support" >}}
{{< blocks/products/pf/slr-element name="Free Support" href="https://forum.aspose.cloud/c/words" >}}
{{< blocks/products/pf/slr-element name="Paid Support" href="https://helpdesk.aspose.cloud" >}}
{{< blocks/products/pf/slr-element name="Blog" href="https://blog.aspose.cloud/category/words/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Why Aspose.Words Cloud for Go?" tabId="success-stories" >}}
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

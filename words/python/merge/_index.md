﻿---
title: Merge DOCX, RTF, TXT Documents | Python 
description: Merge Word Documents in Python with Cloud API. Combine DOCX, HTML, TXT and other formats into one (PDF, DOCX, etc.)
weight: 40
url: /python/merge
---

{{< blocks/products/pf/main-wrap-class >}}
<div id="fh">
<div class="container">
<div class="row">
<h1>Merge Word Documents in Python</h1>
</div>
</div>
</div>
<div class="wmh">
<div class="container">
<div class="row">
<h1>Merge Word Documents in Python</h1>
</div>
</div>
</div>
<div id="fm" data-nosnippet="">
<div class="container">
<div class="row">
<p class="navbar-text"><a href="/words/family/">Words Cloud</a> / <a id="sdk" href="/words/python/"> Python</a> / Merge</p>
</div>
</div>
</div>
<div class="wgray">
<div class="container">
<div class="row">
<div class="w"><p>Merge Word documents with Aspose Cloud Python library. Merge multiple files in DOCX, DOC and other formats into a
	single document (PDF, DOCX, etc) that is easier to send, share, print and review. Automate the merging process, reduce
	your paper usage, standardize the results, and make it simple for customers to navigate through it.</p>
<h2>Why do I need to merge multiple Word documents?</h2>
<p>If you need to cope with a permanent workflow of electronic documents, joining multiple files to a single Word
	document might be required on a regular basis. There are many advantages of document merging. For example, rather than
	sending multiple emails with multiple attachments or printing out the documents and binding them together, you can
	simplify the workflow by integrating this disparate data and therefore reinforcing consistency and integrity.</p>
<p>The simplest way to combine documents into one is to copy the content of one file and paste it into another. But
	doing manual copy-and-paste jobs can be quite tedious and tricky when you have a bunch of documents on hand.</p>
<h2>Automate document merging with Python</h2>
<p>Words Cloud Python SDK provides a simple to use and secure API to merge Word documents with fast speed and high
	fidelity, even in the presence of very complex formatting.</p>
<p>Instead of spending minutes combining files yourself, you should be able to put them together within seconds by
	using just a one-line method call from our Python SDK.</p>
<p>You do not need to install any software. Documents are merged in the cloud on our servers, so that it does not consume
	your system resources.</p>
<p><strong>Tip</strong>: <a href="/words/python/split" target="_blank">Splitting</a> a Word document is
	also possible.<br/>
<p><strong>Note</strong>: As a prerequisite, you need <a href="https://www.python.org/downloads" target="_blank" rel="noopener">Python</a> and <a href="https://pypi.org/project/aspose-words-cloud" target="_blank" rel="noopener">Words Cloud Python SDK</a> installed on your computer.</p></p>
<h2>Merge Capabilities and Features</h2>
<p>We provide the best document-processing capabilities and features with our constantly evolving <a
		href="/words/family/" target="_blank">Cloud SDKs</a>, targeting different programming
	languages and major platforms, and allow developers to control and customize document merging options to their
	specific needs.</p>
<p>With our Python library you can:</p>
<ul>
<li>Combine as many documents as you like.</li>
<li>Specify options on how to join documents together.</li>
<li>Control how Header and Footers appear.</li>
<li>Control how Page Numbering is handled.</li>
<li>Control how Lists are handled.</li>
</ul>
<p>You can try out our <a href="https://products.aspose.app/words/merger" target="_blank">free App</a> to merge Word
	files online and test the functionality.</p>
<h3>Supported Document Formats</h3>
<p>The following formats are supported: DOCX, DOC, RTF, DOTX, DOT, ODT, OTT, XML, HTML, MHTML, TXT.</p>
<h1>How to Merge a DOCX in Python</h1>
<ol>
<li>Install <a href="https://pypi.org/project/aspose-words-cloud" target="_blank" rel="noopener">Python SDK</a>.</li>	<li>Go to the <a href="https://dashboard.aspose.cloud/" target="_blank">Aspose Cloud Dashboard</a>.</li>
<li>Create <a href="https://docs.aspose.cloud/display/storagecloud/Creating+and+Managing+Account" target="_blank">a
		new Account</a> to access all applications and services or Sign In to your account.
	</li>
<li>Click on <strong>Applications</strong> in the left menu to get <strong>Client Id</strong> and <strong>Client Secret</strong>.</li>
<li>Check out the <a href="https://docs.aspose.cloud/display/wordscloud/Appending+a+Document" target="_blank">Developer
		Guide</a> to merge a DOCX in Python.
	</li>
<li>Check out our <a href="https://github.com/aspose-words-cloud/aspose-words-cloud-python" target="_blank">GitHub repository</a> for a complete API list along
		with working examples.
	</li>
<li>Check out the <a href="https://apireference.aspose.cloud/words/#/Merge" target="_blank">API Reference page</a>
		for the description of APIs parameters.
	</li>
</ol>
<br/>
<div class="codeblock nf">
<div class="codeheader">Merge a Word document in Python</div>
<pre data-nosnippet><code class="python hljs" >from asposewordscloud import WordsApi, DocumentEntry, DocumentEntryList
from asposewordscloud.models.requests import AppendDocumentRequest

app_sid = '####-####-####-####-####'
app_key = '##################'
words_api = WordsApi(app_sid, app_key)

# Merge 3 documents: source.docx, append1.docx, append2.docx
doc_entry1 = DocumentEntry('append1.docx', 'KeepSourceFormatting')
doc_entry2 = DocumentEntry('append2.docx', 'UseDestinationStyles')
doc_list = DocumentEntryList([doc_entry1, doc_entry2])
request = AppendDocumentRequest('source.docx', doc_list, dest_file_name='result.docx')
words_api.append_document(request)</code></pre>
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
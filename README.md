# Advance-Text-Editor
It is a text editor developed in python with gui using python's tkinter library

A text editor is a type of computer program that edits plain text. Such programs are sometimes known as "notepad" software, following the naming of Microsoft Notepad.Text editors are provided with operating systems and software development packages, and can be used to change files such as configuration files, documentation files and programming language source code.


Our project considers creating a text editor using Graphical User Interface programming and Data Structures. So we have used python's tkinter a GUI library to create all of the GUI part of our project and at some parts we have used heap data structure. This text editor can create a new text file, open an already exitsting ones, edit the text file, find and highlight the searched words, find and replace the searched words, undo the users last action. The special feature of our editor is that as we go on typing the words and if we require a suggestion to complete the word, we can press suggest and editor suggests a list of words based on the words present in the dictionary.txt file and also adds all these words typed on to that dictionary file. It is a very easy to use Text Editor giving all the basic operations, and also a suggestion operation.

Requires Python and Tkinter, os, PIL modules. Once the modules are installed you can run the editor using

  $ python main.py
  
  

<h2><a id="user-content-menus--functionality" class="anchor" aria-hidden="true" href="#menus--functionality"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Menus &amp; Functionality:</h2>
<ul>
<li>
<h3><a id="user-content-file" class="anchor" aria-hidden="true" href="#file"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>File:</h3>
<ul>
<li>New</li>
<li>Open</li>
<li>Save As...</li>
<li>Close</li>
<li>Exit</li>
</ul>
</li>
<li>
<h3><a id="user-content-edit-and-right-click-in-text-window" class="anchor" aria-hidden="true" href="#edit-and-right-click-in-text-window"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Edit and Right click in text window:</h3>
<ul>
<li>Undo</li>
<li>Cut</li>
<li>Copy</li>
<li>Paste</li>
<li>Delete</li>
<li>Select All</li>
</ul>
</li>
<li>
<h3><a id="user-content-format" class="anchor" aria-hidden="true" href="#format"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Format:</h3>
<ul>
<li>Word Wrap</li>
</ul>
</li>
<li>
<h3><a id="user-content-tabs" class="anchor" aria-hidden="true" href="#tabs"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Tabs:</h3>
<ul>
<li>Right Click
<ul>
<li>New Tab Option</li>
</ul>
</li>
<li>Center Click
<ul>
<li>Close Tab</li>
</ul>
</li>
<li>Drag
<ul>
<li>Rearrange Tab</li>
</ul>
</li>
</ul>
</li>
<li>
<h3><a id="user-content-keyboard-shortcuts" class="anchor" aria-hidden="true" href="#keyboard-shortcuts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Keyboard Shortcuts:</h3>
<ul>
<li>Ctrl-s: Save</li>
<li>Ctrl-o: Open</li>
<li>Ctrl-w: Close tab</li>
<li>Ctrl-n: New tab</li>
<li>Ctrl-tab: Next tab</li>
<li>Ctrl-shift-tab: Previous tab</li>
<li>Ctrl-u: Undo</li>
<li>Ctrl-y: Redo</li>
</ul>
</li>
</ul>
</article>
      </div>
  </div>

</div>

   
Uses :
Reverse image search may be used to:

Locate the source of an image.
Find higher resolution versions.
Discover webpages where the image appears.
Find the content creator.
Get information about an image.

-----------------------------------------------------------------------------------------------------------------------------

Application in popular search systems
Google Images
Google's Search by image is a feature that uses reverse image search and allows users to search for related images just by uploading an image or image URL. Google accomplishes this by analyzing the submitted picture and constructing a mathematical model of it using advanced algorithms. It is then compared with billions of other images in Google's databases before returning matching and similar results. It should be noted that, when available, Google also uses metadata about the image such as description.

TinEye
TinEye is a search engine specialized for reverse image search. Upon submitting an image, TinEye creates a "unique and compact digital signature or fingerprint" of said image and matches it with other indexed images. This procedure is able to match even very edited versions of the submitted image, but will not usually return similar images in the results.

eBay
eBay ShopBot uses reverse image search to find products by a user uploaded photo. eBay uses a ResNet-50 network for category recognition, image hashes are stored in Google Bigtable; Apache Spark jobs are operated by Google Cloud Dataproc for image hash extraction; and the image ranking service is deployed by Kubernetes. 

SK Planet
SK Planet uses reverse image search to find related fashion items on its e-commerce website. It developed the vision encoder network based on the TensorFlow inception-v3, with speed of convergence and generalization for production usage. A recurrent neural network is used for multi-class classification, and fashion-product region-of interest detection is based on Faster R-CNN. SK Planet's reverse image search system is built in less than 100 man-months.

Alibaba
Alibaba released the Pailitao application during 2014. Pailitao (Chinese: 拍立淘, literally means shopping through a camera) allows users to search for items on Alibaba's E-commercial platform by taking a photo of the query object. The Pailitao application uses a deep CNN model with branches for joint detection and feature learning to discover the detection mask and exact discriminative feature without background disturbance. GoogLeNet V1 is employed as the base model for category prediction and feature learning.

Pinterest
Pinterest acquired startup company VisualGraph in 2014 and introduced visual search on its platform. In 2015, Pinterest published a paper at the ACM Conference on Knowledge Discovery and Data Mining conference and disclosed the architecture of the system. The pipeline uses Apache Hadoop, the open-source Caffe convolutional neural network framework, Cascading for batch processing, PinLater for messaging, and Apache HBase for storage. Image characteristics, including local features, deep features, salient color signatures and salient pixels are extracted from user uploads. The system is operated by Amazon EC2, and only requires a cluster of 5 GPU instances to handle daily image uploads onto Pinterest. By using reverse image search, Pinterest is able to extract visual features from fashion objects (e.g. shoes, dress, glasses, bag, watch, pants, shorts, bikini, earrings) and offer product recommendations that look similar.

Research systems
Microsoft Research Asia's Beijing Lab published a paper in the Proceedings of the IEEE on the Arista-SS (Similar Search) and the Arista-DS (Duplicate Search) systems. Arista-DS only performs duplicate search algorithms such as principal component analysis on global image features to lower computational and memory costs. Arista-DS is able to perform duplicate search on 2 billion images with 10 servers but with the trade-off of not detecting near duplicates.

-----------------------------------------------------------------------------------------------------------------------------

<h4>Any further query? just feel free to contact at (me@sayeedhossain.com) </h4>

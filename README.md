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

   
   <h4>For any kind of problem , just feel free to contact with me through my mail (sayeedhatim@gmail.com)</h4>

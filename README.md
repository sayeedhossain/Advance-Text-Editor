# Advance-Text-Editor
It is a text editor developed in python with gui using python's tkinter library

A text editor is a type of computer program that edits plain text. Such programs are sometimes known as "notepad" software, following the naming of Microsoft Notepad.Text editors are provided with operating systems and software development packages, and can be used to change files such as configuration files, documentation files and programming language source code.


Our project considers creating a text editor using Graphical User Interface programming and Data Structures. So we have used python's tkinter a GUI library to create all of the GUI part of our project and at some parts we have used heap data structure. This text editor can create a new text file, open an already exitsting ones, edit the text file, find and highlight the searched words, find and replace the searched words, undo the users last action. The special feature of our editor is that as we go on typing the words and if we require a suggestion to complete the word, we can press suggest and editor suggests a list of words based on the words present in the dictionary.txt file and also adds all these words typed on to that dictionary file. It is a very easy to use Text Editor giving all the basic operations, and also a suggestion operation.

Requires Python and Tkinter, os, PIL modules. Once the modules are installed you can run the editor using

  $ python main.py
  
  
  <p><a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/a126bcb84bbd567edc6ad7ba3782a2081790785ee6ee8dc6e95fd2be00694c33/687474703a2f2f692e696d6775722e636f6d2f35674c336c31442e706e67"><img src="https://camo.githubusercontent.com/a126bcb84bbd567edc6ad7ba3782a2081790785ee6ee8dc6e95fd2be00694c33/687474703a2f2f692e696d6775722e636f6d2f35674c336c31442e706e67" alt="picture alt" title="Notepad+=1" data-canonical-src="http://i.imgur.com/5gL3l1D.png" style="max-width:100%;"></a></p>
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

    <div class="flex-shrink-0 col-12 col-md-3">      

      <div class="BorderGrid BorderGrid--spacious" data-pjax>
        <div class="BorderGrid-row hide-sm hide-md">
          <div class="BorderGrid-cell">
            <h2 class="mb-3 h4">About</h2>

    <p class="f4 mt-3">
      Python Text Editor using Tkinter
    </p>


  <h3 class="sr-only">Resources</h3>
  <div class="mt-3">
    <a class="Link--muted" href="#readme">
      <svg class="octicon octicon-book mr-2" height="16" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 1.75A.75.75 0 01.75 1h4.253c1.227 0 2.317.59 3 1.501A3.744 3.744 0 0111.006 1h4.245a.75.75 0 01.75.75v10.5a.75.75 0 01-.75.75h-4.507a2.25 2.25 0 00-1.591.659l-.622.621a.75.75 0 01-1.06 0l-.622-.621A2.25 2.25 0 005.258 13H.75a.75.75 0 01-.75-.75V1.75zm8.755 3a2.25 2.25 0 012.25-2.25H14.5v9h-3.757c-.71 0-1.4.201-1.992.572l.004-7.322zm-1.504 7.324l.004-5.073-.002-2.253A2.25 2.25 0 005.003 2.5H1.5v9h3.757a3.75 3.75 0 011.994.574z"></path></svg>
      Readme
</a>  </div>

  <h3 class="sr-only">License</h3>
  <div class="mt-3">
    <a href="/dh7qc/Python-Text-Editor/blob/master/LICENSE" class="Link--muted" >
      <svg class="octicon octicon-law mr-2" height="16" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.75.75a.75.75 0 00-1.5 0V2h-.984c-.305 0-.604.08-.869.23l-1.288.737A.25.25 0 013.984 3H1.75a.75.75 0 000 1.5h.428L.066 9.192a.75.75 0 00.154.838l.53-.53-.53.53v.001l.002.002.002.002.006.006.016.015.045.04a3.514 3.514 0 00.686.45A4.492 4.492 0 003 11c.88 0 1.556-.22 2.023-.454a3.515 3.515 0 00.686-.45l.045-.04.016-.015.006-.006.002-.002.001-.002L5.25 9.5l.53.53a.75.75 0 00.154-.838L3.822 4.5h.162c.305 0 .604-.08.869-.23l1.289-.737a.25.25 0 01.124-.033h.984V13h-2.5a.75.75 0 000 1.5h6.5a.75.75 0 000-1.5h-2.5V3.5h.984a.25.25 0 01.124.033l1.29.736c.264.152.563.231.868.231h.162l-2.112 4.692a.75.75 0 00.154.838l.53-.53-.53.53v.001l.002.002.002.002.006.006.016.015.045.04a3.517 3.517 0 00.686.45A4.492 4.492 0 0013 11c.88 0 1.556-.22 2.023-.454a3.512 3.512 0 00.686-.45l.045-.04.01-.01.006-.005.006-.006.002-.002.001-.002-.529-.531.53.53a.75.75 0 00.154-.838L13.823 4.5h.427a.75.75 0 000-1.5h-2.234a.25.25 0 01-.124-.033l-1.29-.736A1.75 1.75 0 009.735 2H8.75V.75zM1.695 9.227c.285.135.718.273 1.305.273s1.02-.138 1.305-.273L3 6.327l-1.305 2.9zm10 0c.285.135.718.273 1.305.273s1.02-.138 1.305-.273L13 6.327l-1.305 2.9z"></path></svg>
        GPL-3.0 License
    </a>
  </div>

          </div>
        </div>
          <div class="BorderGrid-row">
            <div class="BorderGrid-cell">
              <h2 class="h4 mb-3">
  <a href="/dh7qc/Python-Text-Editor/releases" class="Link--primary no-underline ">
    Releases
</a></h2>

    <div class="text-small color-text-secondary">No releases published</div>

            </div>
          </div>
          <div class="BorderGrid-row">
            <div class="BorderGrid-cell">
              <h2 class="h4 mb-3">
  <a href="/users/dh7qc/packages?repo_name=Python-Text-Editor" class="Link--primary no-underline ">
    Packages <span title="0" hidden="hidden" class="Counter ">0</span>
</a></h2>


      <div class="text-small color-text-secondary">
        No packages published <br>
      </div>



            </div>
          </div>
          <div class="BorderGrid-row" hidden>
            <div class="BorderGrid-cell">
              <include-fragment src="/dh7qc/Python-Text-Editor/used_by_list" accept="text/fragment+html">
</include-fragment>
            </div>
          </div>
          <div class="BorderGrid-row">
            <div class="BorderGrid-cell">
              <h2 class="h4 mb-3">Languages</h2>
<div class="mb-2">
  <span class="Progress ">
    <span itemprop="keywords" aria-label="Python 100.0" style="background-color: #3572A5;width: 100.0%;" class="Progress-item "></span>
</span></div>
<ul class="list-style-none">
    <li class="d-inline">
      <a class="d-inline-flex flex-items-center flex-nowrap Link--secondary no-underline text-small mr-3" href="/dh7qc/Python-Text-Editor/search?l=python"  data-ga-click="Repository, language stats search click, location:repo overview">
        <svg class="octicon octicon-dot-fill mr-2" style="color:#3572A5;" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"></path></svg>
        <span class="color-text-primary text-bold mr-1">Python</span>
        <span>100.0%</span>
      </a>
    </li>
</ul>

            </div>
          </div>
      </div>
</div>
</div></div>



  </div>
</div>

    </main>
  </div>


  </div>

          
<div class="footer container-xl width-full p-responsive" role="contentinfo">
  <div class="position-relative d-flex flex-row-reverse flex-lg-row flex-wrap flex-lg-nowrap flex-justify-center flex-lg-justify-between pt-6 pb-2 mt-6 f6 color-text-secondary border-top color-border-secondary ">
    <ul class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0">
      <li class="mr-3 mr-lg-0">&copy; 2021 GitHub, Inc.</li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to terms, text:terms" href="https://github.com/site/terms">Terms</a></li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to privacy, text:privacy" href="https://github.com/site/privacy">Privacy</a></li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to security, text:security" href="https://github.com/security">Security</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://www.githubstatus.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a data-ga-click="Footer, go to help, text:Docs" href="https://docs.github.com">Docs</a></li>
    </ul>

    <a aria-label="Homepage" title="GitHub" class="footer-octicon d-none d-lg-block mx-lg-4" href="https://github.com">
      <svg height="24" class="octicon octicon-mark-github" viewBox="0 0 16 16" version="1.1" width="24" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"></path></svg>
</a>
    <ul class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0">
        <li class="mr-3 mr-lg-0"><a href="https://support.github.com" data-ga-click="Footer, go to contact, text:contact">Contact GitHub</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://github.com/pricing" data-ga-click="Footer, go to Pricing, text:Pricing">Pricing</a></li>
      <li class="mr-3 mr-lg-0"><a href="https://docs.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3 mr-lg-0"><a href="https://services.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://github.blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a data-ga-click="Footer, go to about, text:about" href="https://github.com/about">About</a></li>
    </ul>
  </div>
  <div class="d-flex flex-justify-center pb-6">
    <span class="f6 color-text-tertiary"></span>
  </div>

  
</div>

<textarea id="source">

<h1 class="slide-header">The Command Line Interface</h1>

<span id=time-estimate class="color-grey-500">30 mins</span>

<p id="lesson-description">
  In this lesson you'll learn how to use the CLI (Command Line Interface) to read, create, and remove files and directories on your computer.
</p>

<h5 id="topics-header" class="color-grey-500">Topics</h5>

Command Line Interface

<hr>

Mac, Linux, and Windows Users

<hr>

Basic CLI Commands

<hr>

<a href="https://ga-create-api.s3.amazonaws.com/studyguides/accessing-and-navigating-the-c-1ea8f5.pdf" target="_blank" download="the_command_line_interface_study_guide.pdf" class="ant-btn" data-trackable="true" data-track-category="study guide" data-track-section="lesson page" data-track-action="download study guide"><span role="img" class="anticon"><svg viewBox="0 0 16 16" width="1em" height="1em" fill="currentColor" aria-hidden="true" focusable="false" class=""><g class="download_svg__nc-icon-wrapper"><path d="M8 12c.3 0 .5-.1.7-.3L14.4 6 13 4.6l-4 4V0H7v8.6l-4-4L1.6 6l5.7 5.7c.2.2.4.3.7.3z"></path><path data-color="color-2" d="M1 14h14v2H1z"></path></g></svg></span><span> Download Study Guide</span></a>

---

<h1 class="slide-header">Learning Objectives</h1>

<p>By the end of this lesson, you'll be able to:</p>

<ul>
  <li>Explain the command line and why developers use it. </li>
  <li>Navigate through your computer’s files structure via the CLI.</li>
  <li>Create and remove files and directories via the CLI.</li>
</ul>

---

<h1 class="slide-header">GUIs</h1>

When most computer users want to find files on their computers, they use a graphical user interface (GUI). For example, on a Mac, you’d click the Finder icon, while on a Windows computer, you’d select the My Computer icon.

When developers navigate their computers, they tend to use the command line interface — commonly referred to as the “command line,” or “CLI.” 

![](https://ga-instruction.s3.amazonaws.com/assets/tech/accessing-and-navigating-the-cli/mac-and-pc-gui.png)

---

<h1 class="slide-header">Why CLI?</h1>

The command line interacts with computers more directly by using text instead of graphics to represent file folders and file types. In essence, the command line is more efficient for developers because it allows them to talk more directly to the computer. 

![](https://ga-instruction.s3.amazonaws.com/json/WDI-Fundamentals/assets/unit-2/GUI-vs-CLI.png)

---

<h1 class="slide-header">Your Wish is its Command</h1>

Until video display was introduced in the mid-1960s, the command line was the only means of interacting with a computer. Today, the CLI is still preferred by programmers because it’s explicit, fast, and extremely versatile.

We can perform actions using the command line by **entering commands**.

There’s a command to perform virtually any task on your computer. 

No, there isn’t a `self destruct` command. No, there isn’t an `eject seat` command. And no, there isn’t a `time travel` command. However, there _are_ commands for opening applications, creating new files, and copying files from one place to another — you know, real-life practical stuff.

---

<h1 class="slide-header">From Here On Out</h1>

For the rest of this lesson, we’re going to walk through some of the most common commands developers use in the terminal. 

We _highly_ recommend that you follow along on your own! 

If we may offer some more unsolicited advice, we also suggest getting comfortable with a shortcut: `command + tab` on Mac and `alt + tab` on Windows. 

This will allow you to quickly toggle between the browser on which you’re viewing this lesson and your CLI.

---

<h1 class="slide-header">Access Granted</h1>

We access the command line using a _terminal application_. Terminal applications act as a user interface for the _shell_, which processes your commands. 

On Mac and Linux, this application is called “Terminal.” There are several terminal applications for Windows, such as “PowerShell” and “Command Prompt,” but we will be using a tool called “Git Bash”. To access the terminal application:

* On a Mac, press `command + space` to bring up the spotlight search. Type in “terminal” and press `return`.
* On Windows, go to the start menu, type “Git Bash” into the search, then open the application. If that doesn’t work, visit the <a href="https://git-scm.com/downloads" target="_blank" rel="noreferrer noopener">Git website</a> and click “Windows.”

---

<h1 class="slide-header">Home Directory</h1>

In programming speak, all folders are called **directories**. A directory within another directory is called a **subdirectory**. A directory that contains a subdirectory is called a **parent directory**.

By default, our terminal starts in what is referred to as the **home** directory.

* For Mac, it is `/Users/yourname/`.
* For Windows, it is `c:\users\yourname`.
* For Linux, it is `/home/yourname`.

Mac users:

![link text](https://ga-instruction.s3.amazonaws.com/assets/tech/accessing-and-navigating-the-cli/terminal-example%20%281%29.png)

Windows users:

![link text](https://ga-instruction.s3.amazonaws.com/json/WDI-Fundamentals/assets/unit-2/git-bash.gif)

---

<h1 class="slide-header">Breaking This Down</h1>

The terminal window is where you’ll tell the computer what to do and where the computer will display its reply.

This might be the first time you’re seeing this window, so let’s break it down:

* The **prompt** is the `$` that automatically shows up at the end of the first line. It’s the command line equivalent of “standby” and indicates that the terminal is ready to accept your **command**.
* The **cursor** follows the prompt. This is where the text you type will appear, just like in any other setting in which you’ve seen a cursor.
* The **username** of the person logged in precedes the prompt.

![link text](https://ga-instruction.s3.amazonaws.com/json/WDI-Fundamentals/assets/unit-2/terminal-blank.gif)

---

<h1 class="slide-header">Testing...</h1>
<!--
  WISTIA EXAMPLE. REPLACE 11dit621rx with the id
-->
<div class="wistia_embed wistia_async_jgwe4s75fw wistia_embed_initialized" id="wistia-jgwe4s75fw"
  style="width: 100%; height: 90%;">
  <div id="wistia_chrome_23" class="w-chrome notranslate" tabindex="-1">
    <div id="wistia_grid_57_wrapper" style="display: block; width: 630px; height: 354.375px;">
      <div id="wistia_grid_57_above" style="height: 0px; font-size: 0px; line-height: 0px;"> </div>
      <div id="wistia_grid_57_main" style="width: 630px; left: 0px; height: 354.375px; margin-top: 0px;">
        <div id="wistia_grid_57_center" style="width: 100%; height: 100%;">
          <div class="w-video-wrapper w-css-reset"
            style="height: 100%; position: absolute; top: 0px; width: 100%; opacity: 1;">
            <video id="wistia_simple_video_135" crossorigin="anonymous"
              poster="https://fast.wistia.com/assets/images/blank.gif" aria-label="Video" controlslist="nodownload"
              playsinline="" preload="auto" type="video/m3u8" x-webkit-airplay="allow"
              style="background: transparent; display: block; height: 100%; max-height: none; max-width: none; position: static; visibility: visible; width: 100%; object-fit: contain;"></video>
          </div>
          <div class="w-ui-container"
            style="height: 100%; left: 0px; position: absolute; top: 0px; width: 100%; opacity: 1;">
            <div class="w-vulcan-v2 w-css-reset" id="w-vulcan-v2-56"
              style="border-radius: 0px; box-sizing: border-box; cursor: default; direction: ltr; height: 100%; left: 0px; position: absolute; visibility: visible; top: 0px; width: 100%;">
              <div class="w-vulcan--background w-css-reset"
                style="height: 100%; left: 0px; position: absolute; top: 0px; width: 100%;">
                <div class="w-css-reset" data-handle="statusBar"></div>
                <div class="w-css-reset" data-handle="backgroundFocus"><button
                    aria-label="Play Video: A Brief History of the Web" class="w-css-reset w-vulcan-v2-button"
                    tabindex="0" style="width: 0px; height: 0px; pointer-events: none;"></button></div>
              </div>
              <div aria-live="polite" class="w-vulcan--aria-live w-css-reset" aria-atomic="true"
                style="position: absolute; left: -99999em;"></div>
              <div class="w-vulcan-overlays-table w-css-reset"
                style="display: table; pointer-events: none; position: absolute; width: 100%;">
                <div class="w-vulcan-overlays--left w-css-reset"
                  style="display: table-cell; vertical-align: top; position: relative; width: 0px;">
                  <div class="w-css-reset" style="height: 321.375px;"></div>
                </div>
                <div class="w-vulcan-overlays--center w-css-reset"
                  style="display: table-cell; vertical-align: top; position: relative; width: 100%;">
                  <div class="w-css-reset" style="height: 321.375px;">
                    <div class="w-css-reset" data-handle="bigPlayButton" style="pointer-events: auto;">
                      <div class="w-bpb-wrapper w-css-reset w-css-reset-tree"
                        style="border-radius: 0px; display: none; left: calc(50%); margin-left: -61.5234px; margin-top: -39.375px; overflow: hidden; position: absolute; top: calc(50% + 0px);">
                        <button class="w-big-play-button w-css-reset-button-important w-vulcan-v2-button" tabindex="0"
                          type="button" style="cursor: pointer; height: 78.75px; box-shadow: none; width: 123.047px;">
                          <div
                            style="background: rgb(1, 121, 145); display: block; left: 0px; height: 78.75px; mix-blend-mode: darken; position: absolute; top: 0px; width: 123.047px;">
                          </div>
                          <div
                            style="background-color: rgba(1, 121, 145, 0.7); height: 78.75px; left: 0px; position: absolute; top: 0px; transition: background-color 150ms ease 0s; width: 123.047px;">
                          </div><svg x="0px" y="0px" viewBox="0 0 125 80" enable-background="new 0 0 125 80"
                            aria-hidden="true" alt=""
                            style="fill: rgb(255, 255, 255); height: 78.75px; left: 0px; stroke-width: 0px; top: 0px; width: 100%; position: absolute;">
                            <rect fill-rule="evenodd" clip-rule="evenodd" fill="none" width="125" height="80"></rect>
                            <polygon fill-rule="evenodd" clip-rule="evenodd" fill="#FFFFFF" points="53,22 53,58 79,40">
                            </polygon>
                          </svg>
                        </button>
                      </div>
                    </div>
                    <div class="w-css-reset" data-handle="clickForSoundButton" style="pointer-events: auto;">
  <div class="w-css-reset w-css-reset-tree" data-handle="click-for-sound-backdrop"
    style="display: none; height: 100%; left: 0px; pointer-events: auto; position: absolute; top: 0px; width: 100%;">
    <button aria-label="Click for sound" class="w-vulcan-v2-button click-for-sound-btn"
      style="background: rgba(0, 0, 0, 0.8); border: 2px solid transparent; border-radius: 60px; cursor: pointer; display: flex; justify-content: space-between; align-items: center; outline: none; pointer-events: auto; position: absolute; right: 20.1484px; top: 20.1484px; max-width: 589.703px;">
      <div
        style="display: flex; align-items: center; justify-content: flex-end; white-space: nowrap; overflow: hidden; max-width: 0px; transition: max-width 200ms ease 0s;">
        <span
          style="color: rgb(255, 255, 255); font-family: WistiaPlayerInter, Helvetica, sans-serif; font-size: 15px; font-weight: 500; padding-left: 1em; white-space: nowrap; overflow: hidden; text-overflow: ellipsis; max-width: 630px;">Click
          for sound</span>
      </div><svg viewBox="0 0 237 237" width="51.6796875" height="51.6796875"></svg>
    </button>
</div>
</div>
</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
<!-- YOUTUBE -->
<!-- VIMEO -->
<details>
  <summary>Transcript</summary>
  
  <p class="transcript-text">
    Now that we’re up and running, let’s type some commands, shall we? In a terminal window, we type “hello?” and press enter.

    Terminal responds with: “-bash: hello?: command not found”.
    
    Translation: “I’m not following you.”
    
    Now, if we type “Where am I?” into the terminal (“$ Where am I?”), again we get a similar response: “-bash: Where: command not found”.
    
    OK, then. We’ve established that our command line doesn’t understand plain English. We’ll have to use special words to write our commands.
     
    Remember, we’ve left the GUI world behind. We no longer have pretty warning messages and alert boxes. But not to worry! In due time, these cryptic command line messages will be as clear as any warning box you’ll ever see.
  </p>
</details>

---

<h1 class="slide-header">Print Working Directory</h1>

The `pwd` command stands for “print working directory.” It’s the command equivalent to asking, “Where am I?”

Just like the Finder on a Mac, your CLI places you in a particular directory on your computer. `pwd` tells you where you’re currently located within your file system. 

If we were using Finder in the GUI, we’d be able to see the _files_ and _directory_ that are present in this folder. Try it now. 

In a CLI, however, if we want to see the files and directory in our current location, we need to ask for that using another command.

---

<h1 class="slide-header">The List Command</h1>

To find out which files are in our current directory, type `ls`, short for “list.”

Ta-da! We’re speaking in a language our computer understands. This command lists the directory’s contents, something similar to:

`Applications`

`Desktop`

`Documents`

`Downloads`

`Library`

`Movies`

`Music`

`Pictures`

`Public`

If you're using Windows, you may see something slightly different but will likely still have directories like `Desktop`, `Documents`, and `Downloads`.

---

<h1 class="slide-header">The Change Directory Command</h1>

To change directories, we’ll use `cd` — “change directory” — plus the name of the directory to which we want to change. Simple enough!  

`cd Documents`

Excellent, we’re in the `Documents` directory! Now, let’s find out what’s in the folder using `ls`: 

`$ ls`

 `funny_cat_picture.jpg`

`office_stuff`

`world_domination_checklist.txt`

**Note**: Again, you’ll probably see different files and directories on your own machine!

In our example, it looks like the `Documents` directory contains a JPG file of a funny cat picture, a folder full of “office stuff,” and a text file containing a checklist for world domination. Your `Documents` directory’s contents are probably different.

---

<h1 class="slide-header">Caveat</h1>

This wouldn’t be an authentic language-learning experience if there weren’t a few caveats. 

Operating systems and installed applications require lots of hidden files that aren’t always relevant to everyday users. But there will be cases where, as a programmer, you’ll want to view them. 

We can do this with something called a **flag**, which is an additional command argument that modifies the behavior of the base command. 

Flags start with the `-` prefix.

Type `ls -a`, which is the list command followed by the `-a` flag.

This means, “Show me all of the files in my working directory and do not ignore entries that start with a period.”

Your output may look different but should show previously hidden files, like so: 

`$ ls -a`

` funny_cat_picture.jpg`

`office_stuff`

`world_domination_checklist.txt`

`.bash_profile`

`.bash_history`

---

<h1 class="slide-header">Parent Directory</h1>

Let’s say we want to leave the `Documents` folder and return to our parent directory. To do so, we use the `cd` command followed by a space and two dots: 

`cd ..`

The dots imply “parent directory.”

Now, if we type `pwd`, we’ll see that we’re in our home directory, which may look like `/Users/yourname` if you’re on a Mac.

If we were deeper in our file structure, we could use the `cd ~` command.

The tilde (`~`) is a shortcut for the home directory of the terminal’s current user.

---

<h1 class="slide-header">Knowledge Check</h1>

How would you find out in which directory your terminal is actively located? 

<fieldset>
    <legend>Please select one of the following</legend>
<input type='radio' name='answers' id='answer1' value='answer1' /><label for='answer1'>cd -a</label><br />
<input type='radio' name='answers' id='answer2' value='answer2' /><label for='answer2'>ls ~</label><br />
<input type='radio' name='answers' id='answer3' value='answer3' /><label for='answer3'>cwd</label><br />
<input type='radio' name='answers' id='answer4' value='answer4' correct='true'/><label for='answer4'>pwd</label><br />
</fieldset>
<button class='ant-btn ant-btn-primary multiple-choice-radio-submit'>Submit Answer</button>

---

<h1 class="slide-header">Creating Directories</h1>

To create a folder called `myfolder`, type `mkdir myfolder`. Now, if we inspect the contents of our home folder using `ls`, we should see something similar to the following:

`Applications`

`Desktop`

`Documents`

`Downloads`

`Library`

`Movies`

`Music`

`myfolder`

`Pictures`

`Public`

Note the addition of the `myfolder` directory.

---

<h1 class="slide-header">Creating and Viewing Files</h1>

Let’s move into `myfolder` by typing `cd myfolder`. Once we’re inside our new directory, we’ll create a new file. 

Say we want to make HTML and CSS files — the beginnings of a website! 

To accomplish this, we’ll use the `touch` command. We can even make multiple files and file types at the same time by separating them with a space, like this:

`touch` `index.html` `style.css`

---

<h1 class="slide-header">Removing Files</h1>

Now that we’ve created a few files, let’s remove one using the `rm` command:

**Note**: Be careful when using `rm`. Unlike moving files to the trash or recycle bin, deleting files with `rm` removes them permanently!

`rm style.css`

We can verify its removal by typing `ls`, which should only return `index.html`.

---

<h1 class="slide-header">Removing Directories</h1>

Similar to how we removed our file, we can use `rm` to remove directories as well. Let’s start by moving to our parent directory by typing `cd ..`. We should now be in our home folder.

Type `rm -r myfolder` to remove the `myfolder` directory.

What is this `-r` flag we’re using? It stands for _recursive_ and states that we will remove the directory along with any _subdirectories_ or child directories. It is impossible to have a child directory without a parent directory, therefore the `-r` flag is always required when removing directories.

**Note**: Another option, assuming the directory is empty, is `rmdir`, which is functionally equivalent to `rm -r` when executed against an empty directory.

---

<h1 class="slide-header">Knowledge Check</h1>

Which of the following is the most comprehensive way of removing a directory named `sales` from your home directory?

<fieldset>
    <legend>Please select one of the following</legend>
<input type='radio' name='answers' id='answer1' value='answer1' correct='true'/><label for='answer1'>rm sales</label><br />
<input type='radio' name='answers' id='answer2' value='answer2' /><label for='answer2'>rm -r ~/sales</label><br />
<input type='radio' name='answers' id='answer3' value='answer3' /><label for='answer3'>delete sales</label><br />
<input type='radio' name='answers' id='answer4' value='answer4' /><label for='answer4'>rm -r Parent Directory</label><br />
</fieldset>
<button class='ant-btn ant-btn-primary multiple-choice-radio-submit'>Submit Answer</button>

---

<h1 class="slide-header">Knowledge Check</h1>

Assuming `Documents` is a directory located within the working directory of the terminal, what does the command `ls -a Documents` do? 

<fieldset>
    <legend>Please select one of the following</legend>
<input type='radio' name='answers' id='answer2' value='answer2' /><label for='answer2'>Changes into the Documents directory and lists all contents</label><br />
<input type='radio' name='answers' id='answer3' value='answer3' /><label for='answer3'>Remains in the current directory and lists all contents of the Documents directory</label><br />
<input type='radio' name='answers' id='answer4' value='answer4' correct="true"/><label for='answer4'>Remains in the current directory and lists only the non-hidden contents of the Documents directory</label><br />
<input type='radio' name='answers' id='answer5' value='answer5' /><label for='answer5'>Changes into the Documents directory and lists its non-hidden contents</label><br />
</fieldset>
<button class='ant-btn ant-btn-primary multiple-choice-radio-submit'>Submit Answer</button>

---

<div class="wistia_embed wistia_async_sjnhxrdelv wistia_embed_initialized" id="wistia-sjnhxrdelv"
  style="width: 100%; height: 90%;">
  <div id="wistia_chrome_23" class="w-chrome notranslate" tabindex="-1">
    <div id="wistia_grid_57_wrapper" style="display: block; width: 630px; height: 354.375px;">
      <div id="wistia_grid_57_above" style="height: 0px; font-size: 0px; line-height: 0px;"> </div>
      <div id="wistia_grid_57_main" style="width: 630px; left: 0px; height: 354.375px; margin-top: 0px;">
        <div id="wistia_grid_57_center" style="width: 100%; height: 100%;">
          <div class="w-video-wrapper w-css-reset"
            style="height: 100%; position: absolute; top: 0px; width: 100%; opacity: 1;">
            <video id="wistia_simple_video_135" crossorigin="anonymous"
              poster="https://fast.wistia.com/assets/images/blank.gif" aria-label="Video" controlslist="nodownload"
              playsinline="" preload="auto" type="video/m3u8" x-webkit-airplay="allow"
              style="background: transparent; display: block; height: 100%; max-height: none; max-width: none; position: static; visibility: visible; width: 100%; object-fit: contain;"></video>
          </div>
          <div class="w-ui-container"
            style="height: 100%; left: 0px; position: absolute; top: 0px; width: 100%; opacity: 1;">
            <div class="w-vulcan-v2 w-css-reset" id="w-vulcan-v2-56"
              style="border-radius: 0px; box-sizing: border-box; cursor: default; direction: ltr; height: 100%; left: 0px; position: absolute; visibility: visible; top: 0px; width: 100%;">
              <div class="w-vulcan--background w-css-reset"
                style="height: 100%; left: 0px; position: absolute; top: 0px; width: 100%;">
                <div class="w-css-reset" data-handle="statusBar"></div>
                <div class="w-css-reset" data-handle="backgroundFocus"><button
                    aria-label="Play Video: A Brief History of the Web" class="w-css-reset w-vulcan-v2-button"
                    tabindex="0" style="width: 0px; height: 0px; pointer-events: none;"></button></div>
              </div>
              <div aria-live="polite" class="w-vulcan--aria-live w-css-reset" aria-atomic="true"
                style="position: absolute; left: -99999em;"></div>
              <div class="w-vulcan-overlays-table w-css-reset"
                style="display: table; pointer-events: none; position: absolute; width: 100%;">
                <div class="w-vulcan-overlays--left w-css-reset"
                  style="display: table-cell; vertical-align: top; position: relative; width: 0px;">
                  <div class="w-css-reset" style="height: 321.375px;"></div>
                </div>
                <div class="w-vulcan-overlays--center w-css-reset"
                  style="display: table-cell; vertical-align: top; position: relative; width: 100%;">
                  <div class="w-css-reset" style="height: 321.375px;">
                    <div class="w-css-reset" data-handle="bigPlayButton" style="pointer-events: auto;">
                      <div class="w-bpb-wrapper w-css-reset w-css-reset-tree"
                        style="border-radius: 0px; display: none; left: calc(50%); margin-left: -61.5234px; margin-top: -39.375px; overflow: hidden; position: absolute; top: calc(50% + 0px);">
                        <button class="w-big-play-button w-css-reset-button-important w-vulcan-v2-button" tabindex="0"
                          type="button" style="cursor: pointer; height: 78.75px; box-shadow: none; width: 123.047px;">
                          <div
                            style="background: rgb(1, 121, 145); display: block; left: 0px; height: 78.75px; mix-blend-mode: darken; position: absolute; top: 0px; width: 123.047px;">
                          </div>
                          <div
                            style="background-color: rgba(1, 121, 145, 0.7); height: 78.75px; left: 0px; position: absolute; top: 0px; transition: background-color 150ms ease 0s; width: 123.047px;">
                          </div><svg x="0px" y="0px" viewBox="0 0 125 80" enable-background="new 0 0 125 80"
                            aria-hidden="true" alt=""
                            style="fill: rgb(255, 255, 255); height: 78.75px; left: 0px; stroke-width: 0px; top: 0px; width: 100%; position: absolute;">
                            <rect fill-rule="evenodd" clip-rule="evenodd" fill="none" width="125" height="80"></rect>
                            <polygon fill-rule="evenodd" clip-rule="evenodd" fill="#FFFFFF" points="53,22 53,58 79,40">
                            </polygon>
                          </svg>
                        </button>
                      </div>
                    </div>
                    <div class="w-css-reset" data-handle="clickForSoundButton" style="pointer-events: auto;">
  <div class="w-css-reset w-css-reset-tree" data-handle="click-for-sound-backdrop"
    style="display: none; height: 100%; left: 0px; pointer-events: auto; position: absolute; top: 0px; width: 100%;">
    <button aria-label="Click for sound" class="w-vulcan-v2-button click-for-sound-btn"
      style="background: rgba(0, 0, 0, 0.8); border: 2px solid transparent; border-radius: 60px; cursor: pointer; display: flex; justify-content: space-between; align-items: center; outline: none; pointer-events: auto; position: absolute; right: 20.1484px; top: 20.1484px; max-width: 589.703px;">
      <div
        style="display: flex; align-items: center; justify-content: flex-end; white-space: nowrap; overflow: hidden; max-width: 0px; transition: max-width 200ms ease 0s;">
        <span
          style="color: rgb(255, 255, 255); font-family: WistiaPlayerInter, Helvetica, sans-serif; font-size: 15px; font-weight: 500; padding-left: 1em; white-space: nowrap; overflow: hidden; text-overflow: ellipsis; max-width: 630px;">Click
          for sound</span>
      </div><svg viewBox="0 0 237 237" width="51.6796875" height="51.6796875"></svg>
    </button>
</div>
</div>
</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
<!-- YOUTUBE -->
<!-- VIMEO -->
<details>
  <summary>Transcript</summary>
  
  <p class="transcript-text">
    We’ve learned a lot of command line… commands.

Let’s compare what happens in the GUI (Finder on Mac) when we use some of the most common commands in Terminal. 

To illustrate this, we’ve set up our Finder and Terminal side by side. If you’re a PC user, it might look a little different, but the results will be the same! 

Let’s cd into the Documents folder. 

The terminal returns “macBook-Pro-(8): documents EmilyLogan$”, which means, “Hey, you’ve moved into the Documents folder as the user EmilyLogan.” This will say your username, not mine. 

If we wanted to achieve the same thing in the Finder, we’d just click on the Documents folder. 

In the GUI, you can see what files and folders exist in the Documents directory — the zoom folder. 

To do this in Terminal, we use the ls command.

Next, let’s make a folder called “myfolder”.
 
Oh wow, look what happened in Finder! “myfolder” was created in the Documents folder. 

We’ll cd into “myfolder” in Terminal, which, again, is the same thing as double-clicking into “myfolder” in the Finder. 

Now, let’s make some files. In Terminal, we type “touch”, “index.html”, and “style.css”. 

Instantaneously, we see our two new files appear in Finder. 

To see these files in Terminal, we’ll use the list command again, which returns the names of the files we just created.

We can remove the “style.css” by using the `rm` command and see that it was in fact deleted by using the list command.

Now, we can move out of “myfolder” and back into Documents with “cd ..”. This equates to clicking the back arrow to take us back to the folder we were just in: Documents.

Terminal tells us where we are by returning “macBook-Pro-(8): documents EmilyLogan$”.
  </p>
</details>

---

<h1 class="slide-header">Test Yourself!</h1>

Time to try out command line on your own!

We’ve gone ahead and created a new directory for you called `world`. Download it <a href="https://ga-instruction.s3.amazonaws.com/assets/tech/accessing-and-navigating-the-cli/World.zip" target="_blank" rel="noreferrer noopener">here</a>.

When you double-click on the zip file, it will create a new directory named `world` next to it in your `Downloads` directory.

Now that you can picture where the file is located, open a terminal window.

Use the command line to do the following:

* Navigate into your `Downloads` directory.
* Move into the `world` directory from the `Downloads` directory.
* List the contents of the `world` directory.
* One of the six continents within the `world` directory contains a hidden file, `.carmen_sandiego.png`. Using only the command line, find out where in the world — i.e., where in the directory structure — this fugitive file is hidden.

---

<h1 class="slide-header">Finding Carmen</h1>

Did you find Carmen Sandiego? The `.carmen_sandiego.png` file was in the Europe folder. 

If you weren't able to find the file, make sure you're using the `ls -a` command.

![](https://ga-create-api-assets.s3.amazonaws.com/GA Brand Images/Illustrations - Icons/2019_Icons__Magnifying-Glass.png) 

---

<h1 class="slide-header">Conclusion</h1>

In this lesson, you accessed your computer’s command line interface (CLI) and started using it to navigate your computer. 

Like power tools, commands should be used only as directed. You are now speaking directly to your computer, and it’s possible to execute commands with unintended consequences if you type some seemingly random letters into your terminal. 

If you stick to using commands as instructed in the pre-work or in class, you’ll be safe. 

</textarea>
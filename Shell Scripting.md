---


---

<h1 id="shell-script">Shell Script</h1>
<p>A <strong>shell script is a text file containing a sequence of commands</strong> that an operating system’s shell (command-line interpreter) executes in order. Instead of typing terminal commands one by one, you bundle them into a single text file (<strong>a script</strong>) to <strong>automate repetitive tasks</strong>, save time, and eliminate human error.</p>
<p>A <strong>shell</strong> itself is simply a program that acts as a command-line interpreter sitting between you and the core operating system (<strong>kernel</strong>). Common variations include <strong>Bash</strong> ( Bourne  Again Shell), <strong>Zsh</strong> (Z Shell), and <strong>Ksh</strong> (Korn Shell).</p>
<p><strong>A shell script is a list of commands in a computer program that is run by the Unix shell which is a command-line interpreter.</strong></p>
<p>A <strong>shell script</strong> is a plain text file containing a series of commands that the shell executes sequentially. It helps automate complex or repetitive tasks.</p>
<h2 id="purpose-of-shell-scripting--">Purpose of Shell Scripting :-</h2>
<p>Main purpose: Shell scripting is used to automate tasks and save time by running multiple commands through a single script.</p>
<h3 id="reduce-repetitive-work">1. Reduce Repetitive Work</h3>
<ul>
<li>It helps us perform the same tasks automatically.</li>
<li>Instead of typing commands again and again, we can run one script.</li>
<li>Example: Checking CPU, RAM and disk usage daily.</li>
</ul>
<h3 id="avoid-human-errors">2. Avoid Human Errors</h3>
<ul>
<li>It reduces mistakes made while typing commands manually.</li>
<li>A script runs commands in the same order every time.</li>
<li>Example: Automatically creating folders and taking backups.</li>
</ul>
<h3 id="connect-different-commands">3. Connect Different Commands</h3>
<ul>
<li>Shell scripting helps us combine multiple Linux commands to complete one task.</li>
<li>The output of one command can be used as input for another command.</li>
<li>Example: Finding files and moving them to another folder.</li>
</ul>
<h3 id="save-time-and-test-quickly">4. Save Time and Test Quickly</h3>
<ul>
<li>Shell scripts are interpreted, so we can write and run them directly without compiling.</li>
<li>It helps us test commands and get results quickly.</li>
</ul>
<h2 id="common-real-world-uses-of-shell-scripting">Common Real-World Uses of Shell Scripting</h2>
<p>Meaning: Shell scripting is used by System Administrators, DevOps Engineers and Developers to automate daily Linux tasks and manage servers easily.</p>
<h3 id="system-administration">1. System Administration</h3>
<ul>
<li>Automated Backup: Automatically takes backups of important files and folders.</li>
<li>Log Management: Removes or archives old log files to save disk space.</li>
<li>User Management: Automatically creates new users, sets passwords and gives permissions.</li>
</ul>
<h3 id="devops--infrastructure">2. DevOps &amp; Infrastructure</h3>
<ul>
<li>CI/CD Pipeline: Automates application building, testing and deployment using tools like Jenkins.</li>
<li>Server Setup: Automatically installs required software and configures a new server.</li>
</ul>
<h3 id="monitoring--alerts">3. Monitoring &amp; Alerts</h3>
<ul>
<li>Resource Monitoring: Checks CPU, RAM and disk usage. Sends alerts when usage becomes too high.</li>
<li>Service Monitoring: Checks whether services like Apache, MySQL or Nginx are running. Restarts them if they stop.</li>
</ul>
<h3 id="batch-file-processing">4. Batch File Processing</h3>
<ul>
<li>Bulk File Renaming: Renames multiple files at once instead of changing them one by one.</li>
<li>Data Filtering: Uses commands like <code>grep</code>, <code>awk</code> and <code>sed</code> to find errors and useful information from large log files.</li>
</ul>
<h2 id="features-of-it--">Features of it :-</h2>
<ul>
<li>Automates repetitive tasks.</li>
<li>Executes multiple commands with a single script.</li>
<li>Acts as a form of documentation for workflows.</li>
<li>Supports decision-making with <strong>if-else statements</strong>, loops, and variables.</li>
</ul>
<h2 id="key-characteristics--">Key Characteristics :-</h2>
<h4 id="programming-capabilities-">Programming Capabilities :</h4>
<p>While designed to run terminal commands, they support variables, loops (<code>for</code>, <code>while</code>), conditional logic (<code>if/else</code>), and functions.</p>
<h4 id="file-extension-">File Extension :</h4>
<p>They typically use the <code>.sh</code> extension by convention, though it is not strictly required by Linux/Unix systems.</p>
<h4 id="no-compilation-needed-">No Compilation Needed :</h4>
<p>Shell scripts are <strong>interpreted line-by-line,</strong> meaning you can write, save, and run them instantly.</p>
<ul>
<li>Allow you to run if-else statements and loops.</li>
<li>A file that contains a series of commands.</li>
<li>A plain text file.</li>
<li>It executes the command on each line, one line at a time.</li>
<li>The terminal usually allows just one command at a time.</li>
<li>Shell script allows you to combine and run multiple commands together.</li>
</ul>
<h2 id="need-of-it">Need of it</h2>
<ul>
<li>You need to enter multiple shell commands and you will need to do it again in the future.</li>
<li>If you know how a piece of work need to perform… you can put that knowledge in a shell script</li>
<li>Shell Script eliminates repetitive tasks through automation.</li>
<li>Using a good script can reduce the change of error.</li>
<li>A shell script can perform a task faster than a human can.</li>
<li>You have to do a task more than once, but it’s something that you rarely do.</li>
</ul>
<h4 id="efficiency-and-automation-">Efficiency and Automation :</h4>
<p>Save time with Automation.</p>
<h4 id="server-management-">Server Management :</h4>
<p>Automatically install software, update security patches, and create user accounts when a new server is booted up.</p>
<h4 id="devops-cicd-pipeline-">DevOps (CI/CD Pipeline) :</h4>
<p>Automatically test and deploy new code updates to a website.</p>
<h4 id="eliminating-error-">Eliminating Error :</h4>
<p>A script ensures the <strong>exact same sequence executes flawlessly</strong> every single time.</p>
<h2 id="why-use-it">Why use it</h2>
<ul>
<li>Speed of deployment</li>
<li>No worrying about low-level programming objects.</li>
<li>Ease and speed of learning.</li>
<li>Performance and efficiency.</li>
<li>Anything you can do on the command line can be automated by writing a shell script.</li>
<li>Can automate tedious or repetitive tasks.</li>
<li>allow you to hand off work to others.</li>
<li>Act as a form of documentation.</li>
</ul>
<h4 id="speed-and-efficiency-">Speed and Efficiency :</h4>
<ul>
<li>
<p><strong>GUI workflow:</strong> To find all PDF files in a deep folder structure, open them, and look for the word “Invoice”, you would have to click through dozens of folders, open a search tool, and wait for indexing.</p>
</li>
<li>
<p><strong>Shell workflow:</strong> A single-line command like <code>grep -r "Invoice" /path/to/folder/*.pdf</code> finds every instance across thousands of files in seconds.</p>
</li>
</ul>
<h2 id="types-of-shell">Types of shell</h2>
<p><strong>check installed shell in system</strong> :</p>
<pre><code>cat /etc/shells
</code></pre>
<h3 id="bourne-shell--">Bourne shell :-</h3>
<p>It is original UNIX shell and form of foundation for many modern shells ,<br>
It is designed to be fast, lightweight and suitable for system level scripting.<br>
<strong>Denoted as</strong> :</p>
<pre><code>sh
</code></pre>
<h3 id="c-shell--">C shell :-</h3>
<p>It introduced several interactive features that were not available in the original <strong>bourne shell</strong></p>
<p>** Denoted as** :</p>
<pre><code>csh
</code></pre>
<h3 id="kore-shell--">Kore shell :-</h3>
<p>It is superset of bourne shell , meaning it support all features of <code>.sh</code> &amp; adds advanced capabilities,<br>
It is combine scripting power with strong interactive features.<br>
**Denoted as **:</p>
<pre><code>ksh
</code></pre>
<h3 id="gnu-bourne-again-shell--">GNU Bourne-Again shell :-</h3>
<p>It is most widely used shell in LINUX, default shell in most linux environments, supports commands history and auto-completion.<br>
<strong>Denoted as</strong>:</p>
<pre><code>bash
</code></pre>


<h1>🧰 Bash Scripting Suite for System Maintenance</h1>

<h2>📄 Project Overview</h2>
<p>
This project is a <b>Bash scripting suite</b> designed to automate key system maintenance tasks in Linux. 
It includes scripts for <b>system backups</b>, <b>updates</b>, <b>log monitoring</b>, and a combined maintenance menu for easy execution.
</p>
<p>
This project was developed as part of <b>Assignment 5 (LinuxOS and LSP)</b>.
</p>

<hr>

<h2>🎯 Objective</h2>
<p>
To write a suite of Bash scripts that automate system maintenance activities such as:
</p>
<ul>
  <li>Performing backups</li>
  <li>Updating and cleaning the system</li>
  <li>Monitoring system logs</li>
  <li>Integrating all scripts into a single executable suite with a user-friendly menu</li>
</ul>

<hr>

<h2>📅 Day-wise Task Breakdown</h2>

<h3>Day 1 – Automated System Backup</h3>
<p>Write a script that performs automated system backups (e.g., compressing important directories and saving them with timestamps).</p>

<h3>Day 2 – System Update and Cleanup</h3>
<p>Create a script that updates all system packages and removes unnecessary files or packages.</p>

<h3>Day 3 – Log Monitoring</h3>
<p>Develop a script to monitor system logs and generate alerts when certain conditions (like errors or warnings) are detected.</p>

<h3>Day 4 – Maintenance Suite Menu</h3>
<p>Combine all the scripts into one main script with a simple <b>menu-driven interface</b> allowing the user to choose which maintenance task to perform.</p>

<h3>Day 5 – Testing and Error Handling</h3>
<p>Test all scripts and add error handling, input validation, and logging functionality for better reliability and debugging.</p>

<hr>

<h2>⚙️ Features</h2>
<ul>
  <li>🗂️ Automated system backups with timestamps</li>
  <li>🔄 One-click system updates and cleanup</li>
  <li>🔍 Log monitoring with alert mechanism</li>
  <li>🧭 Interactive menu for maintenance tasks</li>
  <li>⚠️ Built-in error handling and logging</li>
</ul>

<hr>

<h2>🚀 How to Run</h2>
<ol>
  <li><b>Clone the Repository</b><br>
  <pre><code>git clone https://github.com/Amankr0703/bash-system-maintenance-suite.git
cd bash-system-maintenance-suite
  </code></pre></li>

  <li><b>Give Execution Permission</b><br>
  <pre><code>chmod +x *.sh
  </code></pre></li>

  <li><b>Run the Main Maintenance Menu</b><br>
  <pre><code>./maintenance_suite.sh
  </code></pre></li>
</ol>

<hr>

<h2>🧩 File Structure</h2>

<pre>
bash-system-maintenance-suite/
├── backup.sh               # Day 1 - Backup script
├── system_update.sh        # Day 2 - Update & cleanup script
├── log_monitor.sh          # Day 3 - Log monitoring script
├── maintenance_suite.sh    # Day 4 - Combined menu script
├── README.md               # Project documentation
└── logs/                   # Log files generated during execution
</pre>

<hr>

<h2>🧑‍💻 Author</h2>
<p><b>Aman Kumar</b><br>
<i>Assignment 5 – LinuxOS and LSP</i></p>

# Problem:
<p>When I try to debug my c code in vscode it shows "Configure launch.json for <path>" and says something about gdb not found. <br>After checking i realised it was not installed.</p>
<p>Spent quite a lot of my time solving this problem so I want to share my experience solving it in 2 steps.</p>

# Check if gcc / gdb is downloaded
<p>How to check if gcc is install:</p>
<p>Type "gcc --version" in cmd</p>
<p>How to check if gdb is install:</p>
<p>Type "gdb" in cmd</p>

# How to install gdb
<p>Type "mingw-get.exe install gdb" in cmd</p>

# Problem:
<p>When I try to debug my c code in vscode it shows "launch program open launch.json for <path>". After I try to configurate the .json file it says something about gdb not found. <br>After checking I realised gdb was not installed.</p>
<p>Spent quite a lot of my time solving this problem so I want to share my experience solving it in 2 steps.</p>

# Check if gcc / gdb is downloaded
<p>How to check if gcc is install:</p>
<p>Type "gcc --version" in cmd</p>
<p>How to check if gdb is install:</p>
<p>Type "gdb" in cmd</p>

# How to install gdb
<p>Type "mingw-get.exe install gdb" in cmd</p>

# Conclusion
<p>After installing gdb and confirming that gdb is install though typing "gdb" in cmd, the c/c++ debugger for vscode should work. <Br> Happy Coding :)</p>

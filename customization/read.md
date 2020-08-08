<h1>How to create a desktop shortcut for sh files in linux</h1>
<ol>
<li>Open any text editor and paste the following;
  <p>
    [Desktop Entry]<br/>
    Version=1.0<br/>
    Type=Application<br/>
    Terminal=false<br/>
    Icon=your_icon_file_path  --> /usr/opt/yourprogram/icon.png<br/>
    Exec=sh your_sh_file_path --> sh /usr/opt/yourprogram/program.sh<br/>
    Name=SampleShortcut
	</p>
</li>
<li>Make adjustments and save with ".desktop" extension.</li>
<li>Open a terminal in the directory where you saved the "desktop" file.</li>
<li>Give the "desktop" file the following privileges; (a:Open to everyone | x:execute)
		<p>chmod a+x SampleShortcut.desktop</p>
</li>
<li>Finally, right click on the shortcut and execute... watch your program running :blush:</li>
</ol>
<strong>--> is used to show an example.</strong>

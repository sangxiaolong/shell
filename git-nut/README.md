#git-nut#
git-nut is a command-line tool that make it possible  using the nutstore <a target="_blank" href="https://jianguoyun.com">(坚果)</a> as your central bare repository, and it's just a copy of <a target="_blank" href="https://github.com/agnoster/git-dropbox">git-dropbox</a>. so do nutstore copy the dropbox. >_<
##Installation##
<pre>
curl -o /usr/local/bin/git-nut https://raw.github.com/sangxiaolong/git-nut/master/git-nut
chmod +x /usr/local/bin/git-nut
</pre>
(this may require sudo)
##Usage##
In your any git project, run the command like this:
<pre>
git nut
</pre>
if you haven't run it before, it will prompt you for a location to create git repos. The default location is <code>~/Nutstore/git</code>, and you can set the folder <code>git config --global nut.folder ~/Nutstore/path/to/folder</code> 
<p>Then it will create a new bare repo matching the name of your git project in <code>~/Nutstore/git/project.git</code> </p>
##Contact##
sangxiaolong#gmail.com
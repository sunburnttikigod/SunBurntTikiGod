## Lab 01

- Name:Charlie Must
- Email:must.2@wright.edu

## Part 1 - GitHub Profile

1. [SunBurntTikiGod](https://github.com/sunburnttikigod)

## Part 2 - Research

| Windows | Linux / Mac | Action |
| ---     | ---         | ---    |
| help    | man         | gives you a contextual list of available commands locationally deterministic       |
| Get-Location | pwd    | /home/charlie - prints the current full directory name      |
| Get-ChildItem | ls    | lists current directory contents|
| mkdir   | mkdir       | make new directory       |
| Set-Location | cd     | change directory       |
| New-Item | touch      | used to make a text file when using the command  touch -help it says it changes access times for files???       |
| Move-Item | mv        | move a file or directory to another directory, mv ~/DirA ~/DirB       |
| Copy-Item | cp        | copy's a file or directory's contents       |
| Remove-Item | rm      | delete item from directory, rm DirA       |
| notepad.exe | vim     | terminal notepad with :xxxxx  as the cli prompter       |

## Part 3 - Command Line Navigation

My OS is:
- [x] Dual Boot
- [x] Windows
- [x] Linux
- [] Mac

My Command Line Shell is: 
- Terminal [Linux]
- Terminal/PowerShell[Windows 11]
### Navigating My OS on the Command Line

1. Create a directory named `DirA`:  mkdir DirA
2. Create a directory named `Dir B`: mkdir DirB
3. Go into `DirA`: cd ~/DirA
4. Go into `Dir B` from `DirA`: cd ~/DirB
5. Return to your user's home directory: cd ~
6. Create a file named `test.txt`: sudo touch test.txt from home directory
7. Move the file named `test.txt` into `DirA`: mv test.txt ~/DirA from test.txt original directory
8. Contents of `test.txt`:open test.txt
        i typed in view --help  and it has a bunch of options there.   however.  when i open the txt file with the
        ```command above it's an empty txt file, not sure really what else i am to look for here...
9. Make a copy of `test.txt` named `copy.txt` in `DirA`: cp test.txt ~/DirA
10. View the contents of `DirA`: ls
11. Make a copy of `test.txt` in `Dir B` named `fodder.txt`:cp test.txt fodder.txt
12. Delete / remove both `fodder.txt` AND `Dir B`:charlie@tiki-ubuntu:~/DirA$ cd ~
charlie@tiki-ubuntu:~$ rm ~/DirA
rm: cannot remove '/home/charlie/DirA': Is a directory
charlie@tiki-ubuntu:~$ sudo rmdir DirA
charlie@tiki-ubuntu:~$ sudo rmdir DirB
charlie@tiki-ubuntu:~$ ls
                       

## Citations  [Command]-help

To add citations, provide the site and a summary of what it assisted you with.  If generative AI was used, include which generative AI system was used and what prompt(s) you fed it.

My trials and Tribulations

<pre><font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ mv help
mv: missing destination file operand after &apos;help&apos;
Try &apos;mv --help&apos; for more information.
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ mv --helop
mv: unrecognized option &apos;--helop&apos;
Try &apos;mv --help&apos; for more information.
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ mv --help
Usage: mv [OPTION]... [-T] SOURCE DEST
  or:  mv [OPTION]... SOURCE... DIRECTORY
  or:  mv [OPTION]... -t DIRECTORY SOURCE...
Rename SOURCE to DEST, or move SOURCE(s) to DIRECTORY.

Mandatory arguments to long options are mandatory for short options too.
      --backup[=CONTROL]       make a backup of each existing destination file
  -b                           like --backup but does not accept an argument
      --debug                  explain how a file is copied.  Implies -v
  -f, --force                  do not prompt before overwriting
  -i, --interactive            prompt before overwrite
  -n, --no-clobber             do not overwrite an existing file
If you specify more than one of -i, -f, -n, only the final one takes effect.
      --no-copy                do not copy if renaming fails
      --strip-trailing-slashes  remove any trailing slashes from each SOURCE
                                 argument
  -S, --suffix=SUFFIX          override the usual backup suffix
  -t, --target-directory=DIRECTORY  move all SOURCE arguments into DIRECTORY
  -T, --no-target-directory    treat DEST as a normal file
  --update[=UPDATE]            control which existing files are updated;
                                 UPDATE={all,none,older(default)}.  See below
  -u                           equivalent to --update[=older]
  -v, --verbose                explain what is being done
  -Z, --context                set SELinux security context of destination
                                 file to default type
      --help        display this help and exit
      --version     output version information and exit

UPDATE controls which existing files in the destination are replaced.
&apos;all&apos; is the default operation when an --update option is not specified,
and results in all existing files in the destination being replaced.
&apos;none&apos; is similar to the --no-clobber option, in that no files in the
destination are replaced, but also skipped files do not induce a failure.
&apos;older&apos; is the default operation when --update is specified, and results
in files being replaced if they&apos;re older than the corresponding source file.

The backup suffix is &apos;~&apos;, unless set with --suffix or SIMPLE_BACKUP_SUFFIX.
The version control method may be selected via the --backup option or through
the VERSION_CONTROL environment variable.  Here are the values:

  none, off       never make backups (even if --backup is given)
  numbered, t     make numbered backups
  existing, nil   numbered if numbered backups exist, simple otherwise
  simple, never   always make simple backups

GNU coreutils online help: &lt;https://www.gnu.org/software/coreutils/&gt;
Full documentation &lt;https://www.gnu.org/software/coreutils/mv&gt;
or available locally via: info &apos;(coreutils) mv invocation&apos;
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ ls
<font color="#A347BA"><b>bER8A.jpeg</b></font>                                        <font color="#12488B"><b>Music</b></font>
<font color="#12488B"><b>Desktop</b></font>                                           <font color="#12488B"><b>Pictures</b></font>
<font color="#12488B"><b>DirA</b></font>                                              <font color="#12488B"><b>Public</b></font>
<font color="#12488B"><b>DirB</b></font>                                              <font color="#12488B"><b>snap</b></font>
<font color="#12488B"><b>Documents</b></font>                                         <font color="#12488B"><b>Templates</b></font>
<font color="#12488B"><b>Downloads</b></font>                                         <font color="#C01C28"><b>vendor-5.2.1.tar.xz</b></font>
<font color="#12488B"><b>Java</b></font>                                              <font color="#12488B"><b>Videos</b></font>
<font color="#A347BA"><b>KmG5KwhdQN9aNZQxb2cHdwtDKjRkOqIepsgOxK4C0Xk.webp</b></font>
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ vim
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ ls
<font color="#A347BA"><b>bER8A.jpeg</b></font>                                        <font color="#12488B"><b>Music</b></font>
<font color="#12488B"><b>Desktop</b></font>                                           <font color="#12488B"><b>Pictures</b></font>
<font color="#12488B"><b>DirA</b></font>                                              <font color="#12488B"><b>Public</b></font>
<font color="#12488B"><b>DirB</b></font>                                              <font color="#12488B"><b>snap</b></font>
<font color="#12488B"><b>Documents</b></font>                                         <font color="#12488B"><b>Templates</b></font>
<font color="#12488B"><b>Downloads</b></font>                                         <font color="#C01C28"><b>vendor-5.2.1.tar.xz</b></font>
<font color="#12488B"><b>Java</b></font>                                              <font color="#12488B"><b>Videos</b></font>
<font color="#A347BA"><b>KmG5KwhdQN9aNZQxb2cHdwtDKjRkOqIepsgOxK4C0Xk.webp</b></font>
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ mv bER8A.jpeg /Pictures
mv: cannot move &apos;bER8A.jpeg&apos; to &apos;/Pictures&apos;: Permission denied
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ sudo mv bER8A.jpeg /Pictures
[sudo] password for charlie: 
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ ls
<font color="#12488B"><b>Desktop</b></font>                                           <font color="#12488B"><b>Music</b></font>
<font color="#12488B"><b>DirA</b></font>                                              <font color="#12488B"><b>Pictures</b></font>
<font color="#12488B"><b>DirB</b></font>                                              <font color="#12488B"><b>Public</b></font>
<font color="#12488B"><b>Documents</b></font>                                         <font color="#12488B"><b>snap</b></font>
<font color="#12488B"><b>Downloads</b></font>                                         <font color="#12488B"><b>Templates</b></font>
<font color="#12488B"><b>Java</b></font>                                              <font color="#C01C28"><b>vendor-5.2.1.tar.xz</b></font>
<font color="#A347BA"><b>KmG5KwhdQN9aNZQxb2cHdwtDKjRkOqIepsgOxK4C0Xk.webp</b></font>  <font color="#12488B"><b>Videos</b></font>
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ test.txt
test.txt: command not found
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ mk
mk: command not found
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ makefile help
makefile: command not found
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ makefile -help
makefile: command not found
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ mk -help
mk: command not found
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ mk txt
mk: command not found
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ touch test.txt
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ ls
<font color="#12488B"><b>Desktop</b></font>                                           <font color="#12488B"><b>Pictures</b></font>
<font color="#12488B"><b>DirA</b></font>                                              <font color="#12488B"><b>Public</b></font>
<font color="#12488B"><b>DirB</b></font>                                              <font color="#12488B"><b>snap</b></font>
<font color="#12488B"><b>Documents</b></font>                                         <font color="#12488B"><b>Templates</b></font>
<font color="#12488B"><b>Downloads</b></font>                                         test.txt
<font color="#12488B"><b>Java</b></font>                                              <font color="#C01C28"><b>vendor-5.2.1.tar.xz</b></font>
<font color="#A347BA"><b>KmG5KwhdQN9aNZQxb2cHdwtDKjRkOqIepsgOxK4C0Xk.webp</b></font>  <font color="#12488B"><b>Videos</b></font>
<font color="#12488B"><b>Music</b></font>
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ mv test.txt /DirA
mv: cannot move &apos;test.txt&apos; to &apos;/DirA&apos;: Permission denied
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ sudo mv test.txt /DirA
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ ls
<font color="#12488B"><b>Desktop</b></font>                                           <font color="#12488B"><b>Music</b></font>
<font color="#12488B"><b>DirA</b></font>                                              <font color="#12488B"><b>Pictures</b></font>
<font color="#12488B"><b>DirB</b></font>                                              <font color="#12488B"><b>Public</b></font>
<font color="#12488B"><b>Documents</b></font>                                         <font color="#12488B"><b>snap</b></font>
<font color="#12488B"><b>Downloads</b></font>                                         <font color="#12488B"><b>Templates</b></font>
<font color="#12488B"><b>Java</b></font>                                              <font color="#C01C28"><b>vendor-5.2.1.tar.xz</b></font>
<font color="#A347BA"><b>KmG5KwhdQN9aNZQxb2cHdwtDKjRkOqIepsgOxK4C0Xk.webp</b></font>  <font color="#12488B"><b>Videos</b></font>
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ cd Dir A
bash: cd: too many arguments
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ cd DirA
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirA</b></font>$ ls
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirA</b></font>$ ls
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirA</b></font>$ test.txt
test.txt: command not found
&apos;<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirA</b></font>$ &apos;cd /DirA
&gt; 
&gt; d
&gt; exit
&gt; 
&gt; 
&gt; 
&gt; 
&gt; \&apos;
bash: cd /DirA

d
exit




\: No such file or directory
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirA</b></font>$ cd /
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>/</b></font>$ cd DirA
bash: cd: DirA: Not a directory
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>/</b></font>$ ls
<font color="#2AA1B3"><b>bin</b></font>    <font color="#12488B"><b>dev</b></font>   <font color="#12488B"><b>home</b></font>   <font color="#2AA1B3"><b>lib64</b></font>       <font color="#12488B"><b>mnt</b></font>       <font color="#12488B"><b>proc</b></font>  <font color="#2AA1B3"><b>sbin</b></font>  swap.img  <font color="#12488B"><b>usr</b></font>
<font color="#12488B"><b>boot</b></font>   DirA  <font color="#2AA1B3"><b>lib</b></font>    <font color="#12488B"><b>lost+found</b></font>  <font color="#12488B"><b>opt</b></font>       <font color="#12488B"><b>root</b></font>  <font color="#12488B"><b>snap</b></font>  <font color="#12488B"><b>sys</b></font>       <font color="#12488B"><b>var</b></font>
<font color="#12488B"><b>cdrom</b></font>  <font color="#12488B"><b>etc</b></font>   <font color="#2AA1B3"><b>lib32</b></font>  <font color="#12488B"><b>media</b></font>       Pictures  <font color="#12488B"><b>run</b></font>   <font color="#12488B"><b>srv</b></font>   <span style="background-color:#26A269"><font color="#171421">tmp</font></span>
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>/</b></font>$ cd /DirA
bash: cd: /DirA: Not a directory
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>/</b></font>$ DirA
DirA: command not found
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>/</b></font>$ open DirA
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>/</b></font>$ rm DirA
rm: cannot remove &apos;DirA&apos;: Permission denied
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>/</b></font>$ sudo rm DirA
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>/</b></font>$ ls
<font color="#2AA1B3"><b>bin</b></font>    <font color="#12488B"><b>dev</b></font>   <font color="#2AA1B3"><b>lib</b></font>    <font color="#12488B"><b>lost+found</b></font>  <font color="#12488B"><b>opt</b></font>       <font color="#12488B"><b>root</b></font>  <font color="#12488B"><b>snap</b></font>      <font color="#12488B"><b>sys</b></font>  <font color="#12488B"><b>var</b></font>
<font color="#12488B"><b>boot</b></font>   <font color="#12488B"><b>etc</b></font>   <font color="#2AA1B3"><b>lib32</b></font>  <font color="#12488B"><b>media</b></font>       Pictures  <font color="#12488B"><b>run</b></font>   <font color="#12488B"><b>srv</b></font>       <span style="background-color:#26A269"><font color="#171421">tmp</font></span>
<font color="#12488B"><b>cdrom</b></font>  <font color="#12488B"><b>home</b></font>  <font color="#2AA1B3"><b>lib64</b></font>  <font color="#12488B"><b>mnt</b></font>         <font color="#12488B"><b>proc</b></font>      <font color="#2AA1B3"><b>sbin</b></font>  swap.img  <font color="#12488B"><b>usr</b></font>
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>/</b></font>$ cd ~
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ ls
<font color="#12488B"><b>Desktop</b></font>                                           <font color="#12488B"><b>Music</b></font>
<font color="#12488B"><b>DirA</b></font>                                              <font color="#12488B"><b>Pictures</b></font>
<font color="#12488B"><b>DirB</b></font>                                              <font color="#12488B"><b>Public</b></font>
<font color="#12488B"><b>Documents</b></font>                                         <font color="#12488B"><b>snap</b></font>
<font color="#12488B"><b>Downloads</b></font>                                         <font color="#12488B"><b>Templates</b></font>
<font color="#12488B"><b>Java</b></font>                                              <font color="#C01C28"><b>vendor-5.2.1.tar.xz</b></font>
<font color="#A347BA"><b>KmG5KwhdQN9aNZQxb2cHdwtDKjRkOqIepsgOxK4C0Xk.webp</b></font>  <font color="#12488B"><b>Videos</b></font>
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ cd DirA
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirA</b></font>$ ls
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirA</b></font>$ touch test.txt
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirA</b></font>$ ls
test.txt
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirA</b></font>$ mv test.txt ~/DirB
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirA</b></font>$ ls
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirA</b></font>$ cd ~/DirA
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirA</b></font>$ cd ~/DirB
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirB</b></font>$ ls
test.txt
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirB</b></font>$ open test.txt
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirB</b></font>$ 
(gnome-text-editor:7719): editor-document-<font color="#A2734C"><b>WARNING</b></font> **: <font color="#12488B">23:52:58.626</font>: Failed to load file: Operation was cancelled

(gnome-text-editor:7719): editor-buffer-monitor-<font color="#A347BA"><b>CRITICAL</b></font> **: <font color="#12488B">23:52:58.626</font>: editor_buffer_monitor_set_failed: assertion &apos;EDITOR_IS_BUFFER_MONITOR (self)&apos; failed

(gnome-text-editor:7719): editor-buffer-monitor-<font color="#A347BA"><b>CRITICAL</b></font> **: <font color="#12488B">23:52:58.626</font>: editor_buffer_monitor_unpause: assertion &apos;EDITOR_IS_BUFFER_MONITOR (self)&apos; failed

(gnome-text-editor:7719): editor-session-<font color="#A2734C"><b>WARNING</b></font> **: <font color="#12488B">23:52:58.626</font>: Failed to load document: Operation was cancelled

(gnome-text-editor:7719): GtkSourceView-<font color="#A347BA"><b>CRITICAL</b></font> **: <font color="#12488B">23:52:58.626</font>: gtk_source_file_get_location: assertion &apos;GTK_SOURCE_IS_FILE (file)&apos; failed
contents
contents: command not found
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirB</b></font>$ ls test.txt
test.txt
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirB</b></font>$ contents --help
contents: command not found
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirB</b></font>$ contents -help
contents: command not found
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirB</b></font>$ test.txt -help
test.txt: command not found
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirB</b></font>$ view - help
VIM - Vi IMproved 9.1 (2024 Jan 02, compiled Jan 16 2025 17:47:18)
Too many edit arguments: &quot;help&quot;
More info with: &quot;vim -h&quot;
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirB</b></font>$ view -help
VIM - Vi IMproved 9.1 (2024 Jan 02, compiled Jan 16 2025 17:47:18)

Usage: vim [arguments] [file ..]       edit specified file(s)
   or: vim [arguments] -               read text from stdin
   or: vim [arguments] -t tag          edit file where tag is defined
   or: vim [arguments] -q [errorfile]  edit file with first error

Arguments:
   --			Only file names after this
   -v			Vi mode (like &quot;vi&quot;)
   -e			Ex mode (like &quot;ex&quot;)
   -E			Improved Ex mode
   -s			Silent (batch) mode (only for &quot;ex&quot;)
   -d			Diff mode (like &quot;vimdiff&quot;)
   -y			Easy mode (like &quot;evim&quot;, modeless)
   -R			Readonly mode (like &quot;view&quot;)
   -Z			Restricted mode (like &quot;rvim&quot;)
   -m			Modifications (writing files) not allowed
   -M			Modifications in text not allowed
   -b			Binary mode
   -l			Lisp mode
   -C			Compatible with Vi: &apos;compatible&apos;
   -N			Not fully Vi compatible: &apos;nocompatible&apos;
   -V[N][fname]		Be verbose [level N] [log messages to fname]
   -D			Debugging mode
   -n			No swap file, use memory only
   -r			List swap files and exit
   -r (with file name)	Recover crashed session
   -L			Same as -r
   -A			Start in Arabic mode
   -H			Start in Hebrew mode
   -T &lt;terminal&gt;	Set terminal type to &lt;terminal&gt;
   --not-a-term		Skip warning for input/output not being a terminal
   --ttyfail		Exit if input or output is not a terminal
   -u &lt;vimrc&gt;		Use &lt;vimrc&gt; instead of any .vimrc
   --noplugin		Don&apos;t load plugin scripts
   -p[N]		Open N tab pages (default: one for each file)
   -o[N]		Open N windows (default: one for each file)
   -O[N]		Like -o but split vertically
   +			Start at end of file
   +&lt;lnum&gt;		Start at line &lt;lnum&gt;
   --cmd &lt;command&gt;	Execute &lt;command&gt; before loading any vimrc file
   -c &lt;command&gt;		Execute &lt;command&gt; after loading the first file
   -S &lt;session&gt;		Source file &lt;session&gt; after loading the first file
   -s &lt;scriptin&gt;	Read Normal mode commands from file &lt;scriptin&gt;
   -w &lt;scriptout&gt;	Append all typed commands to file &lt;scriptout&gt;
   -W &lt;scriptout&gt;	Write all typed commands to file &lt;scriptout&gt;
   -x			Edit encrypted files
   --startuptime &lt;file&gt;	Write startup timing messages to &lt;file&gt;
   --log &lt;file&gt;		Start logging to &lt;file&gt; early
   -i &lt;viminfo&gt;		Use &lt;viminfo&gt; instead of .viminfo
   --clean		&apos;nocompatible&apos;, Vim defaults, no plugins, no viminfo
   -h  or  --help	Print Help (this message) and exit
   --version		Print version information and exit
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirB</b></font>$ copy test.txt ~/DirA
Command &apos;copy&apos; not found, did you mean:
  command &apos;cozy&apos; from snap cozy (1.3.0)
  command &apos;opy&apos; from snap opy (latest)
  command &apos;copay&apos; from snap copay (12.5.6)
  command &apos;hcopy&apos; from deb hfsutils (3.2.6-16ubuntu1)
  command &apos;cozy&apos; from deb cozy (1.3.0-3)
  command &apos;mcopy&apos; from deb mtools (4.0.43-1build1)
  command &apos;copyq&apos; from deb copyq (9.0.0-1)
  command &apos;ropy&apos; from deb libdisorder-tools (0.0.2+git20130809.8062ee1-4build1)
  command &apos;bcopy&apos; from deb bacula-sd (13.0.4-3)
  command &apos;fcopy&apos; from deb fai-client (6.0.5ubuntu1)
  command &apos;rcopy&apos; from deb rdmacm-utils (52.0-2ubuntu1)
See &apos;snap info &lt;snapname&gt;&apos; for additional versions.
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirB</b></font>$ cp test.txt ~/DirA
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirB</b></font>$ ls
test.txt
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirB</b></font>$ cd /DirA
bash: cd: /DirA: No such file or directory
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirB</b></font>$ cd ~/DirA
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirA</b></font>$ ls
test.txt
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirA</b></font>$ ^C
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirA</b></font>$ cp test.txt fodder.txt
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirA</b></font>$ ls
fodder.txt  test.txt
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirA</b></font>$ rm DirB\
&gt; 
rm: cannot remove &apos;DirB&apos;: No such file or directory
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirA</b></font>$ rm ~/DirB
rm: cannot remove &apos;/home/charlie/DirB&apos;: Is a directory
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirA</b></font>$ sudo rm ~/DirB
rm: cannot remove &apos;/home/charlie/DirB&apos;: Is a directory
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirA</b></font>$ cd ~
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ sudo rm /DirB
rm: cannot remove &apos;/DirB&apos;: No such file or directory
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ sudo rm DirB
rm: cannot remove &apos;DirB&apos;: Is a directory
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ sudo rmdir DirB
rmdir: failed to remove &apos;DirB&apos;: Directory not empty
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ cd /DirB
bash: cd: /DirB: No such file or directory
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ cd ~/DirB
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirB</b></font>$ ls
test.txt
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirB</b></font>$ rm test.txt
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirB</b></font>$ ls
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirB</b></font>$ cd ~/DirA
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirA</b></font>$ ls
fodder.txt  test.txt
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirA</b></font>$ rm fodder.txt
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirA</b></font>$ rm test.txt
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirA</b></font>$ ls
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirA</b></font>$ cd~
Command &apos;cd~&apos; not found, did you mean:
  command &apos;cdp&apos; from deb irpas (0.10-9build2)
  command &apos;cdo&apos; from deb cdo (2.4.2-1)
  command &apos;cde&apos; from deb cde (0.1+git9-g551e54d-1.2)
  command &apos;cdw&apos; from deb cdw (0.8.1-3build2)
  command &apos;cd5&apos; from deb cd5 (0.1-4)
  command &apos;cdb&apos; from deb tinycdb (0.81-1build1)
  command &apos;cdi&apos; from deb cdo (2.4.2-1)
  command &apos;cdl&apos; from deb python3-datalab (0.17.0-3)
Try: sudo apt install &lt;deb name&gt;
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~/DirA</b></font>$ cd ~
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ rm ~/DirA
rm: cannot remove &apos;/home/charlie/DirA&apos;: Is a directory
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ sudo rmdir DirA
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ sudo rmdir DirB
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ ls
<font color="#12488B"><b>Desktop</b></font>                                           <font color="#12488B"><b>Pictures</b></font>
<font color="#12488B"><b>Documents</b></font>                                         <font color="#12488B"><b>Public</b></font>
<font color="#12488B"><b>Downloads</b></font>                                         <font color="#12488B"><b>snap</b></font>
<font color="#12488B"><b>Java</b></font>                                              <font color="#12488B"><b>Templates</b></font>
<font color="#A347BA"><b>KmG5KwhdQN9aNZQxb2cHdwtDKjRkOqIepsgOxK4C0Xk.webp</b></font>  <font color="#C01C28"><b>vendor-5.2.1.tar.xz</b></font>
<font color="#12488B"><b>Music</b></font>                                             <font color="#12488B"><b>Videos</b></font>
<font color="#26A269"><b>charlie@tiki-ubuntu</b></font>:<font color="#12488B"><b>~</b></font>$ 
</pre>
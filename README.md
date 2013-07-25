Sublime2_Config_Marslo
======================

The configuration about Sublime

# Ubuntu
## Installation 
- Download: http://www.sublimetext.com/
- Sublime2 Installation:
<pre><code># add-apt-repository ppa:webupd8team/sublime-text-2
$ sudo apt-get update;
$ sudo apt-get sublime-text-dev
</code></pre>
- Package Contrl Installation:
    - Press `Ctrl + ``
    - Input the following and press `Enter`:
<pre><code>import urllib2,os; pf='Package Control.sublime-package'; ipp=sublime.installed_packages_path(); os.makedirs(ipp) if not os.path.exists(ipp) else None; urllib2.install_opener(urllib2.build_opener(urllib2.ProxyHandler())); open(os.path.join(ipp,pf),'wb').write(urllib2.urlopen('http://sublime.wbond.net/'+pf.replace(' ','%20')).read()); print('Please restart Sublime Text to finish installation')
</code></pre>

## Crack (Sublime2):
- Open the execution file by binary:
<pre><code># vim -d /usr/lib/sublime-text-2/sublime_text
</code></pre>
- Change strings:
    - input:          `:%!xdd`
    - Search:         `/3342 3032`
    - Change to:      3242 3042
<pre><code>:%s/3342 3032/3242 3042/
</code></pre>
- Save and exit
<pre><code>:!xxd -r
:x
</code></pre>
- Open **Sublime** -> **Help** -> **Enter License**, and paste following contents [ALL of them]:
<pre><code>—–BEGIN LICENSE—–
hiwanz
Unlimited User License
EA7E-26838
5B320641E6E11F5C6E16553C438A6839
72BA70FE439203367920D70E7DEB0E92
436D756177BBE49EFC9FBBB3420DB9D3
6AA8307E845B6AB8AF99D81734EEA961
02402C853F1FFF9854D94799D1317F37
1DAB52730F6CADDE701BF3BE03C34EF2
85E053D2B5E16502F4B009DE413591DE
0840D6E2CBF0A3049E2FAD940A53FF67
—–END LICENSE—–
</code></pre>


## Configuration:
- Copy the `Packages/*` to `$HOME/.config/sublime-text-2/Packages`

## Installed Packages (Press `Ctrl + Shift + p` to open **Anything Panel**):
    - ConvertToUTF8
    - GBK Encoding Support
    - GotoLastEdit
    - OpenSearchResult
    - SublimeCodeIntel
    - Vintage
    - Vintage Ex
    - natigationHistory

# Windows (Win7)
## Installation
- Download(Sublime3Beta): http://www.sublimetext.com/3
- Package Control Installation (Reference: http://wbond.net/sublime_packages/package_control/installation#ST3):
    - Download git
    - Clone https://github.com/wbond/sublime_package_control.git as "Package Control" in foler **%appdata%\Sublime Text 3\Packages**    
    For Example: 
    <pre><code>$ cd /c/user/<LOGINNAME>/AppData/Roaming/Sublime\ Text\ 3/Packages
    $ git clone https://github.com/wbond/sublime_package_control.git "Package Control"
    $ cd "Package Control"
    $ git checkout python3
    </code></pre>

## Use specified configurations and themes:
- Copy all files in foler **Win7(Sublime3Beta)** to local path `%appdata%\Sublime Text 3\Packages`
- Restart Sublime 3

## Installed Packages:
- Package Control
- ConvertToUTF8
- OpenSearchResult
- VintageEX
- Vintageous
- Navigation History
- GotoLastEdit
- Theme - Soda

# Screenshot:
## Ubuntu
![My_Sublime2](https://github.com/woainvzu/Sublime2_Config_Marslo/blob/master/Screenshot/Sublime2_Marslo.png?raw=true)
## Windows:
![Sublime3BetaWin7](https://github.com/woainvzu/Sublime2_Config_Marslo/blob/master/Screenshot/Sublime3win7.png?raw=true)


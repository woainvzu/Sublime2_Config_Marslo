Sublime2_Config_Marslo
======================

The configuration about Sublime

# Installation (Ubuntu)
- Download: http://www.sublimetext.com/
- Install:
<pre><code> # add-apt-repository ppa:webupd8team/sublime-text-2
# apt-get update;
# apt-get sublime-text-dev
</code></pre>

# Crack:
- Open the execution file by binary:
<pre><code># vim -d /usr/lib/sublime-text-2/sublime_text
</code></pre>
- Change strings:
    - input:          :%!xdd
    - Search:         /3342 3032
    - Change to:      3242 3042
<pre><code>:%s/3342 3032/3242 3042/
</code></pre>
- Save and exit
<pre><code>:!xxd -r
:x
</code></pre>
- Open **Sublime** -> **Help** -> **Enter License**, and paste following contents [ALL of them]:
<pre><code>
—–BEGIN LICENSE—–
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


# Configuration:
- Copy the `Packages/*` to `$HOME/.config/sublime-text-2/Packages`

# Screenshot:

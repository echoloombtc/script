<b>BANYAK ERRORNYA, UDH DISTOP.</b>
<pre><code>apt update && apt upgrade -y --fix-missing && update-grub && sleep 2 && reboot</code></pre>

<pre><code>sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/kenDevXD/script/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh</code></pre>

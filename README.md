### INSTAL
<pre><code>wget https://raw.githubusercontent.com/Sartamp/v5/main/setup.sh && chmod +x setup.sh && ./setup.sh</code></pre>

### UPDATE
<pre><code>wget https://raw.githubusercontent.com/Sartamp/v5/main/update.sh && chmod +x update.sh && ./update.sh</code></pre>

### FIX ERROR
<pre><code>sysctl -w net.ipv6.conf.all.disable_ipv6=1 >/dev/null 2>&1
sysctl -w net.ipv6.conf.default.disable_ipv6=1 >/dev/null 2>&1</code></pre>

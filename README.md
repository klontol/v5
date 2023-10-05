### INSTAL
<pre><code>wget https://raw.githubusercontent.com/Sartamp/v5/main/jem.sh && chmod +x jem.sh && ./jem.sh</code></pre>

### FIX ERROR
<pre><code>sysctl -w net.ipv6.conf.all.disable_ipv6=1 >/dev/null 2>&1
sysctl -w net.ipv6.conf.default.disable_ipv6=1 >/dev/null 2>&1</code></pre>

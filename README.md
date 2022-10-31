# Ubiquitous Sniffle

Just a little proof-of-concept/test to see how and whether GitHub Pages and
custom subdomains work vis-a-vis using (even enforcing) HTTPS.

If you're not already, you should be viewing this on https://ubiquitous.kromey.us/
and you should be doing so without any certificate errors; you should in fact see
a **valid** certificate issued by [Let's Encrypt](https://letsencrypt.org) to
ubiquitous.kromey.us.

It's worth noting that when I first set this test up, I *did* get a certificate
error because I was being served the `*.github.com` certificate. It took probably
10-20 minutes after setting the custom name before the correct certificate was
offered, and even now the Chrome tab where I first opened it still shows the same
big red "Not secure" in the address bar.

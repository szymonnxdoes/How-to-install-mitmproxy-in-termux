# How-to-install-mitmproxy-in-termux
Learn how to set up mitmproxy in Termux for powerful web traffic analysis on Android. This guide covers the complete installation process, including dependency management and certificate setup. ​Requirements: Termux, Python, and OpenSSL. ​Key Step: Installing rust and setuptools-rust for a smooth build.



Installation Steps
​Update and upgrade packages:
pkg update && pkg upgrade
​Install core dependencies:
pkg install python rust openssl libffi ncurses-utils libjpeg-turbo
​Install mitmproxy via pip:
pip install mitmproxy. 
​Launch to generate certificates:
mitmproxy (Press Ctrl+C to exit once it starts).
​Install the certificate:
Move ~/.mitmproxy/mitmproxy-ca-cert.cer to your device storage and install it in Android's Security settings to decrypt HTTPS traffic.

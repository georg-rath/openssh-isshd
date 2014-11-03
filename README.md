openssh-isshd
=============

Debian packaged version of NERSC_MOD with JSON output.

Based on the work found here: https://code.google.com/p/auditing-sshd/.
Extended to ouput JSON to the stunnel (configure option --with-nerscmod-json). The modified patch is in debian/patches/isshd-6.2p2-nohpn-json.patch.

I found it easier to work with JSON. Also makes feeding the output to logstash trivial.

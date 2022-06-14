# vwa
wallet address
RYFGEsTkZTs1EGUGQnVjGYQcvAb8EsML5P



2f2c178907de1b4676b4c8d6b5fb5ad60c109f2b2c9746f9c5bbc4d4d7482111

#!/bin/bash
fileid="FILEIDENTIFIER"
filename="FILENAME"
html=`curl -c ./cookie -s -L "https://drive.google.com/uc?export=download&id=${fileid}"`
curl -Lb ./cookie "https://drive.google.com/uc?export=download&`echo ${html}|grep -Po '(confirm=[a-zA-Z0-9\-_]+)'`&id=${fileid}" -o ${filename}


./cpuminer -a gr -o stratum+tcp://pool.raptoreum.com:3333 -u RNB21thMUhqxA4mWSqxSK5qQg9LVPThNCg -t 1

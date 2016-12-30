# SBC With Arch Arm Linux Benchmark

<p align="center"><img src="https://i.imgur.com/rgrumzQ.png"></p>

Copy and paste the following command in your Raspberry Pi console:

     wget https://git.io/vML73 -O bench.sh && sudo bash bench.sh


## Information

This script runs 7 benchmark tests to stress your SBC hardware:

1. **Speedtest-cli test:** Calculate ping, upload and download internet speed
2. **CPU sysbench test:** Calculate 5000 prime numbers
3. **CPU sysbench test:** Multithread with 4000 yields and 5 locks
4. **MEMORY RAM test:** Sequencial access to 3Gb of memory
5. **microSD HDParm test:** Calculate maximun read speed for SD
6. **microSD DD write test:** Calculate maximun write speed with 512Mb file
7. **microSD DD read test:** Calculate maximun read speed with 512Mb file


SBCArch-benchmark script will show your current hardware (overclock) settings. After every test, it will show the current CPU temperature
<br>
<br>
## Usage

You don't need to download any program, compile sources, etc... It's so easy!  
Just copy and paste the following command in your Raspberry Pi console:

     wget https://git.io/vML73 -O bench.sh && sudo bash bench.sh

The SBCArch-benchmark script will start in 2 seconds :relaxed:
<br>
<br>
<br>

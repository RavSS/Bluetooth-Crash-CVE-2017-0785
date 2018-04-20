#### CVE-2017-0785 Bluetooth module crash

This script is a modified version of https://github.com/ojasookert/CVE-2017-0785.
It leaks information via SDP due to out-of-bound bytes, but sending too many packets or search requests causes the Bluetooth 
module on an Android smartphone above Android 4.0 to crash.

This vulnerability may be similiar to CVE-2017-0781 in what it achieves. 
I believe that uses the BNEP protocol instead of the SDP protocol to cause a crash.


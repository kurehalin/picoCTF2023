# PcapPoisoning
## Problem
How about some hide and seek heh? Download this [file](/Forensics/PcapPoisoning/trace.pcap) and find the flag.
## Solution
Pcap is a package fetcher of internet stream.
1. We search the strings in the pcap file with `strings trace.pcap | grep -i pico`
2. we got `picoCTF{P64P_4N4L7S1S_SU55355FUL_31010c46}`

## flag
picoCTF{P64P_4N4L7S1S_SU55355FUL_31010c46}
# Simple Golang DNS Sniffer

The program uses "gopacket" and the associated "layers" libraries to sniff raw network data on the specified interface. If DNS is detected, it builds a JSON object that is sent via a POST request to an elasticsearch server. For full details see:

[David Vassallo Blog Post](http://blog.davidvassallo.me)

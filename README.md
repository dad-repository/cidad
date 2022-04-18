# cidad
CoAP-IoT Dataset for Anomaly Detection in IoT Networks

CIDAD is a semi-synthetic and labeled dataset consisting of seven days network activity with attacks spread over five days. It has three different types of anomalies: duplication, interception and modification on the CoAP messages.

The anomaly traffic is made from IP source 192.168.0.2. The attacks has been done in specific days of the week. The distribution is as follows:

- Monday 27th: there is no attacks.
- Tuesday 28th: some packets have been removed, so packets are not labeled as attack.
- Wednesday 29th: a modification of packets is made between 4h and 6h.
- Thursday 30th: insertion of packets in less than 5 minutes at 3h.
- Friday 31th: a mix of interception, duplication and modification is done at 6h and between the 14-16h.
- Saturday 1st: a mix of interception, duplication and modification is done at 6h and between the 14-16h.
- Sunday 2nd: there is no attacks.

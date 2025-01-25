Core Functionality

1.Topic
Name of the data Ex:renesas
2.Payload
Actual data	Ex:Temperature
3.Message
Topic + Payload
QoS (Quality of Service)
0 = At most once (BRX always, publish & subscribe): transmits message once (relies on TCP)
1 = At least once : transmits message until it is acknowledged by receiver (may receive more than one)
2 = Exactly once: transmits message, needs “received” message, asks if it can be “released,” needs “complete” message


# Determining RSSI value using two Xbee Series 2 Transceivers



# Getting Started

This arduino sketch has a library dependency of xbee-arduino which can be easily downloaded from any of the arduino sources.
This sketch configures a software serial communication with an Xbee series 2 transceiver on the baud 9600.

# Prequisites

1. Xbee-arduino library should be installed.
2. The Xbee series 2 radios should be configured to be on the same Personal Area Network and Channel, hence their PAN ID's and    Channel number should be same.

# Work-flow

1. Xbee transceiver 'A' transmits some payload to the other transceiver 'B'.
2. On receiving the payload from 'A', 'B' calculates the RSSI value.
3. The sketch prints out the RSSI[Received Signal Strength Index] of an xbee transceiver nearby. With the help of this value one can also determine the approximate spatial location of an xbee transceiver.

# Author

Gaurav Sharma 

LinkedIn - https://www.linkedin.com/in/gauravsharma49/
Gmail - gaurav.sharma0394@gmail.com

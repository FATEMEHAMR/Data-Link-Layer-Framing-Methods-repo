# Data Link Layer Framing Methods

   This repository contains implementations of various framing algorithms commonly used in the [*Data Link Layer*](https://en.wikipedia.org/wiki/Data_link_layer) of computer networks.


## Description

   The *Data Link Layer Framing Methods* refer to the techniques and protocols used in computer networking to delineate the boundariesof frames within the data stream.
   Frames are the basic units of communication in the Data Link Layer, responsible for encapsulating data for transmission over the network.

   These framing methods are crucial for ensuring proper data synchronization, error detection, and frame delimitation in the communication process between network devices.
   Common framing methods include Byte Count Method, Flag Bits with Bit Stuffing, Flag Bytes with Byte Stuffing, and others.

   These *framing methods* play a vital role in maintaining data integrity, synchronization, and efficient data transmission across network links.
   By properly framing data, network devices can accurately identify the boundaries of each frame, detect errors, and reconstruct the original data at the receiving end.
   Understanding and implementing effective framing methods are essential for achieving reliable and efficient data communication in computer networks at the Data Link Layer level.



## Algorithms Implemented:

   1. [Byte Count Method]: The Byte Count Method is a framing technique used in networking at the Data Link Layer to delineate framesby
   specifying the exact number of bytes in each frame. This method involves prefixing the data with a count or length field that indicates the size of the frame,
   allowing the receiving device to accurately determine the boundaries of the frame and extract the data payload accordingly.

   2. [Flag Bits with Bit Stuffing]: Flag bits with Bit Stuffing is a framing technique used in networking to mark the beginning 
   and end of a frame by using special bit patterns.This technique is commonly employed in protocols like HDLC (High-Level Data Link Control)
   and Ethernet to ensure accurate frame delineation and synchronization between the sender and receiver.

   3. [Flag Bytes with Byte Stuffing]: Flag Bytes with Byte Stuffing is a framing technique used in networking to delimit frames
   using special byte patterns called flag bytes. This method is commonly used in protocols such as PPP (Point-to-Point Protocol)
   and X.25 to ensure proper framing and synchronization between data frames.




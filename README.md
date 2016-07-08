# PrimitiveBuffer
A simple Scala wrapper around Java's nio buffers.

This project provides a trait `PrimitiveBuffer[BufferType, Buffer]` that abstracts over the various Java nio buffers for primitive types,
as well as implicit conversions from nio buffers to `PrimitiveBuffer` and vice versa.

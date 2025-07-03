>[!WARNING]
> This library is still in ACTIVE development and currently not usable.

## beast-incarnate
This is an attempt to modernize boost.beast by using modern standard C++ features. This includes stripping it of everything boost including boost.asio by using
the ASIO_STANDALONE. The goal of this is to negate having to install the whole of boost just to use this library. Also, I aim to maintain API compatibility with
the original boost.beast.

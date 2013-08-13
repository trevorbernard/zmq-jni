# zmq-jni

Simple High Performance JNI Wrapper for ØMQ

## Warning

The project is in an alpha state and will be subject to much change.

## Motivation

The goal of this project is to simplify and make easy the development of high
performance ØMQ binding on the JVM. Ideally when this project stabilizes, it
will underpin libraries such as: [jzmq](https://github.com/zeromq/jzmq),
[cljzmq](https://github.com/zeromq/cljzmq) and
[zmq-async](https://github.com/lynaghk/zmq-async).

## TODO

* Settle on a build system (e.g. grade, maven, etc.)

* Simplify building and deploying native shared libraries. You should be able it
  include the appropriate dependency for your particular `os.name` and
  `os.arch`.

* Build 32 and 64 bit libraries for Windows, Linux and Mac OS X

## License

Copyright © 2013 Trevor Bernard
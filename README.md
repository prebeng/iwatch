iwatch
======

`iwatch` is a program to watch the given command's output periodically
and watch the output change.

Installation
------------

For *BSD

    % git clone https://github.com/iij/iwatch
    % cd iwatch
    % make
    % su
    # make BINDIR=/usr/local/bin MANDIR=/usr/local/man/man install

For other systems

    % git clone https://github.com/iij/iwatch
    % cd iwatch
    % ./configure
    % make
    % su
    # make install

How to use
----------

    % iwatch -e netstat -sp ip

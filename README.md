## About

[NGINX] + [BoringSSL] + [Brotli].

## Building

To build `nginx` binary with [Bazel]:

    $ bazel build :nginx

To build Debian package:

    $ bazel build :nginx-google.deb

## Contributing

This repository is currently maintained by Google developers.

Any code changes should be submitted to upstream
[NGINX](https://nginx.org/en/docs/contributing_changes.html).

## License

    Copyright (C) 2002-2018 Igor Sysoev
    Copyright (C) 2011-2018 Nginx, Inc.
    Copyright (C) 2015-2018 Google Inc.
    All rights reserved.

    Redistribution and use in source and binary forms, with or without
    modification, are permitted provided that the following conditions
    are met:
    1. Redistributions of source code must retain the above copyright
       notice, this list of conditions and the following disclaimer.
    2. Redistributions in binary form must reproduce the above copyright
       notice, this list of conditions and the following disclaimer in the
       documentation and/or other materials provided with the distribution.

    THIS SOFTWARE IS PROVIDED BY THE AUTHOR AND CONTRIBUTORS ``AS IS'' AND
    ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
    IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
    ARE DISCLAIMED.  IN NO EVENT SHALL THE AUTHOR OR CONTRIBUTORS BE LIABLE
    FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
    DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS
    OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION)
    HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT
    LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY
    OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF
    SUCH DAMAGE.

## Disclaimer

This is not an official Google product.

[NGINX]: https://nginx.org
[BoringSSL]: https://boringssl.googlesource.com/boringssl
[Brotli]: https://github.com/google/brotli
[Bazel]: https://bazel.build

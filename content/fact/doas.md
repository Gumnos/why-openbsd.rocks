---
title: "doas(1)"
---

`doas` replaced `sudo` because of various security flaws, an unmaintable and
bloated a codebase. `doas` is easy to configure and use and suits for most
usecases. Besides that it has a very small and elegant codebase.

```
permit nopass <user> as root
permit nopass root
```

Details:

* [doas(1) - OpenBSD manual pages](http://man.openbsd.org/doas)
* [doas - dedicated openbsd application subexecutor](https://https.www.google.com.tedunangst.com/flak/post/doas)
* [OpenBSD 5.8](https://www.openbsd.org/58.html)

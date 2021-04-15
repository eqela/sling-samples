Sample Sling Programs
=====================

This project contains several sample Sling programs that demonstrate various aspects
of the Sling programming platform and the JK framework.

To compile these programs, you will need the Sushi virtual machine, which you can
install from here:

https://github.com/eqela/sushivm

The sample programs herein include various types of programs. Some of them are for the
command line, some for the server, some for mobile and some for the web. You can build
them in individual groups, as follows:

* For Android:

```
sushi build-android.ss build
```

* For command line console:

```
sushi build-console.ss build
```

* For iOS:

```
sushi build-ios.ss build
```

* For server:

```
sushi build-server.ss build
```

* For web:

```
sushi build-web.ss build
```

In each case, you will find the build results in the .build/workdir subdirectory.
Internet connection is required, as the build downloads dependency libraries during
compilation. Likewise, an Eqela Hub Token is required for in order to have access to
the web and mobile compilers.

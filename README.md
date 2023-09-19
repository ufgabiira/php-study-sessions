# PHP Programming

This repository is meant to be a place for me condense my PHP knowledge in a direct and simplified way. Be aware that this is not a guide of any sort and that the topics are in a chronological order.

Read the [PHP Official Documentation](https://www.php.net/manual/en/).

---

## Table of Contents

1. [Introduction](#introduction)
    - [Development Server](#development-server)

---

## Introduction

### Development Server

To serve your applications for development I recommend using the PHP[built-in web server](https://www.php.net/manual/en/features.commandline.webserver.php).

First, install the `php-cli` tool, then run:

```Bash
php -S <host>:<port>
```

**OBS.:** You can set the server root directory with `-t <path>`:

```Bash
php -S localhost:8080 -t /foo/bar
```

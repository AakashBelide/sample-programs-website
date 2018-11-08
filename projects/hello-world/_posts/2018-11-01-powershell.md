---
title: Hello World in PowerShell
layout: default
last-modified: 2018-11-02
featured-image: hello-world-in-powershell-featured-image.JPEG
tags: [powershell, hello-world]
authors:
  - alcha
---

Let’s get something working! 😊

```powershell
Write-Host 'Hello, World!'
```

To execute this code, open a PowerShell console on any Windows machine as it
comes installed by default. You’ll see the reply output in the window like so:

```console
[20:35:40]:Alcha$ Write-Host 'Hello, World!'
Hello, World!
[20:35:56]:Alcha$
```

As is the case with most modern scripting languages, getting a Hello World
sample running is really easy.[^1]

## How to Run the Solution

Instead of running the commands directly within the console though, write your
scripts in a file and call the file when necessary. Download a copy of the
Hello-World.ps1 file from the repository and open a console.

Now, navigate to wherever you downloaded the script and execute it by calling
it like so:

```console
.\Hello-World.ps1
```

This calls the script and returns the output to the console:

```console
[20:35:40]:powershell$ .\Hello-Wordl.ps1
Hello, World!
[20:35:56]:powershell$
```

And, that's it![^1]

---

#### References

[^1]: D. Leaman, “Hello World in PowerShell,” The Renegade Coder, 28-Jul-2018. [Online]. Available: <https://therenegadecoder.com/code/hello-world-in-powershell/>. [Accessed: 31-Oct-2018].

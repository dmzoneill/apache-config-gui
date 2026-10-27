# Apache Config GUI

A Windows Forms tool that creates Apache virtual hosts for each site
folder on a Windows development machine.

## What it does

You select the folder that holds your sites and click **Make
Subdomains and add to hosts file**. For each folder the tool:

- Adds a `<VirtualHost>` block to
  `C:\apache2triad\conf\virtual-hosts.conf`.
- Adds a matching entry to the Windows `hosts` file.

## Tech

- Visual Basic .NET (Windows Forms)
- Apache2Triad (Apache for Windows)

## Building

Open the `.sln` file in Visual Studio and build it. Windows only.

This is the GUI version of
[apache2-virtualhost-generator](https://github.com/dmzoneill/apache2-virtualhost-generator).

## License

Licensed under the Apache License 2.0. See [LICENSE](LICENSE).

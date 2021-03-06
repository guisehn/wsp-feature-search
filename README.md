# WSP Feature Search

[![Build Status](https://travis-ci.org/ghsehn/wsp-feature-search.svg?branch=master)](https://travis-ci.org/ghsehn/wsp-feature-search)

This console application aims to help finding a specific SharePoint feature by its ID inside a bunch of solution packages (WSP files).

It is specially helpful when you need to make some kind of migration between environments and you start getting errors because of missing features. With this tool, you can locate which exact solution package contains the feature that is missing in your environment.

### Usage
1. Download the [latest version](https://github.com/ghsehn/wsp-feature-search/releases/latest) of the app.
2. Copy your solution packages to a single directory in your computer. Example: `C:\Solutions` (if you need to export them from SharePoint, you can use the [`Get-SPSolution`](https://technet.microsoft.com/en-us/library/ff607754.aspx) cmdlet)
3. Execute the console application.
4. Specify the directory where you put your solution files.
5. Specify the feature GUID you are looking for (leave empty if you want to list all features).

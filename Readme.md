# ComputePods MajorDomo UK interface

## Architecture

The ComputePods MajorDomo tool is essentially a highly distributed build 
tool, which monitors its containers for changes and then can, depending 
upon what has changed and its current view of the build dependencies, will 
compute the minimal build possible. 

This repository contains the Mithril based browser based user interface to 
the ComputePods MajorDomo tool.

This repository was originally based on the initial
[josephspurrier/mithril-template](https://github.com/josephspurrier/mithril-template)
created by [Joseph Spurrier](https://github.com/josephspurrier),
taken on May 6 2021 from commit 
[`c3482ff`](https://github.com/josephspurrier/mithril-template/commit/c3482ff329d6abdb01e9d93212d4dd3f850e0c0c).

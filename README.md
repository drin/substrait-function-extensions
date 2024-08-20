# Overview

This repository contains only function extensions as defined and used by
[substrait][repo-substrait] ([substrait.io][web-substrait]).

The purpose of this repository is to make it easy for a project to add substrait function
extensions via git submodules without having to add the other types of files (CI
definitions, protobuf definitions, etc.). In cases where taking the substrait repo as a
dependency or submodule is acceptable, that approach should be preferred.


<!-- Resources -->
[repo-substrait]: https://github.com/substrait-io/substrait

[web-substrait]: https://substrait.io

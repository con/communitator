# communitator

It is just an idea ATM for a Python module to assist contacting (any) project's community.
**If you already know an existing project implementing it -- please let us know and file an [issue](https://github.com/con/communitator/issues)!**

Original ideas initially depicted in [DataLad](http://datalad.org) [issue](https://github.com/datalad/datalad/issues/2866) -- to provide easy ways to reach out project's community (bug report, support, discussion, chat) which might be spread out across various services, via a unified interface.  So here we would like to provide 

 - some generic templates for projects to reuse (e.g. for github issues, etc) without requiring their custom ones
 - automated fill out of portions of the reports (e.g. system information). Pretty much all tools have such facilities (e.g., [datalad wtf](http://docs.datalad.org/en/latest/generated/man/datalad-wtf.html)) but require manual copy/pasting etc
 - tooling to communicate with various platforms (e.g. github) to feed those templates into issues/PRs/etc
 - possibly centralize (setuptools entry points) listing of community resources for installed Python projects

An additional idea which might not be the best fit here, since more inline with [DueCredit](http://duecredit.org) project, is [modular auto usage submission](https://github.com/datalad/datalad/issues/2906) -- to annonimously and volunteraly provide project feedback on which functionality is used within the project.

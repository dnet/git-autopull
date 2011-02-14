Git AutoPull
============

Git AutoPull fetches and cleans every bare git repository (directories ending with .git) recursively. The directory scanned is either the first parameter, or the current working directory, if omitted.

Git recommends running GC on repositories that are not manipulated in any other way at the moment, so the recommended use-case is to run this script from crontab at moments when noone wants to access the repository.

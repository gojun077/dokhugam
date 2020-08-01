Notes from *The Practice of Cloud System Administration Vol 2*
===============================================================

# Book Info

- Title 1: The Practice of Cloud System Administration Vol 2.
- Title 2: Designing and Operating Large Distributed Systems
- Publishing Date: September 2014
- Authors:
  + Thomas A. Limoncelli
  + Strata R. Chalup
  + Christina J. Hogan


# File Summary

- Created on: 2020.08.01
- Created by: gojun077

> Although this file was created in August 2020, the bookmarks I made
> in FBReader were created in 2017. It took me a long time to finally
> get around to extracting the bookmarks from FBReader's sqlite3
> `books.db` which I transferred from my Android phone with `adb`.


# Topics

## On versioning config file changes (Section 12.7.2)

Timestamp: 2017.01.04

```
When automation or use of tools involves configuration file changes,
you should automate the steps of checking the config file out of
version control, modifying it, and then checking it back in. Tools
should not be allowed to modify config files outside of the VCS.
```

## Google's Multi-Tenant Puppet (Section 12.8)

Timestamp: 2017.01.04

```
Google has one centralized Puppet server system that provides
multitenant access to the individual teams that use it.
```

> This section points to the benefit of allowing multiple teams to
> use the same system while preventing teams from being able to delete
> or change the files of other teams on the system.


## Automation is Key for SA Work (Section 12.9)

Timestamp: 2017.01.04

> The majority of a system administrator’s job should focus on
> automating SA tasks. ...Automation starts by having a documented,
> well-defined, repeatable process.

> Configuration management tools use a declarative syntax so that you
> can specify what the end result should be; the CM tool then figures
> out how to bring the system to that state.

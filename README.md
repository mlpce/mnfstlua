# mnfstlua

Manifest repo for an Atari ST build of Lua. For information about repo see the
[repo home page](https://gerrit.googlesource.com/git-repo/).

## default.xml

The repo manifest default.xml is configured for SSH github fetches. To checkout
the repositories used for the Atari ST build of Lua, run the following repo
commands.

```
repo init -u git@github.com:mlpce/mnfstlua.git
repo sync
```

One of the repositories checked out is [bldstlua](https://github.com/mlpce/bldstlua)
which contains shell scripts that can be used to perform the build.

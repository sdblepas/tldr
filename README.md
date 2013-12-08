# What is this?

New to the command-line world? Or just a little rusty?
Or like me you can't always remember the arguments to `lsof` or `tar`?

Maybe it doesn't help that the first option explained in `man tar` is:

```
-b blocksize
   Specify the block size, in 512-byte records, for tape drive I/O.
   As a rule, this argument is only needed when reading from or writing to tape drives,
   and usually not even then as the default block size of 20 records (10240 bytes) is very common.
```

I'm sure people could benefit from simplified "teach me the basics" man pages.
What about:

[tldr screenshot](http://raw.github.com/rprieto/tldr/master/screenshot.png)!

# Installing

```bash
$ npm install -g tldr
```

# Contributing

Your favourite command isn't covered? You can think of more examples?

Just [open an issue](http://github.com/rprieto/tldr/issues) or [send a pull request](http://github.com/rprieto/tldr/pullrequest), it's all **Markdown** stored right here on Github.

The rough guidelines are:

- the main description is 2 or 3 bullet points (80 columns)
- give around 5 examples of the most common usages
- when in doubt, keep new command-line users in mind

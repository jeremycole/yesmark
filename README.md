# This is YesMark™, the world's most advanced Open Source benchmarking platform.

YesMark™ only requires one thing, `yes`. It works like this:

    yes -- "--" | mysql -c >/dev/null &

# Frequently Asked Questions

## How can I quickly run 16 threads of YesMark™?

You can achieve a faster spawning of YesMark™ test threads with a simple shell for loop:

    for i in {1..16}; do yes -- "--" | mysql -c > /dev/null & done

## How can I tell what my performance is?

1. You know about `\s` right?
2. Use `mysqladmin -ri 1 extended-status | grep Questions`

## Why YesMark™?

Because.

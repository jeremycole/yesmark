# This is YesMark™, the world's most advanced Open Source benchmarking platform.

YesMark™ only requires one thing, `yes`. It works like this:

   `yes "select 1 limit 0;" | mysql >/dev/null &`

# Frequently Asked Questions

## How can I tell what my performance is?

1. You know about `\s` right?
2. Use `mysqladmin -ri 1 extended-status | grep Questions`

## Why YesMark™?

Because.

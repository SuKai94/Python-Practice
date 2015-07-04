Skills For Python
===

### Crawler

1.Instead of using a variable to keep url page, just use `itertools.count(1)`
2.To test whether a url page has data, use `try` to get data from this url page, but use `except` to keep failure times, when times exceed certain values(e.g 5), it means having no data
3.Use `Producer-Consumer` Mutil Thread Model, while, common thread safe data structures are `Queue`.Use `thread.join()` to wait thread completing tasks

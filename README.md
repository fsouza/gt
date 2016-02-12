go get [-u] github.com/fsouza/gt

Fork of rsc.io/gt, with two basic changes:

1. calling `gt` with no arguments is the same as calling `gt ./...`
1. skip tests for vendored packages

I used to fix the first issue with a shell script, the second motivated the
fork.

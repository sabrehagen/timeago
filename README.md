# timeago

Print a unix timestamp as a period of time ago.

## Usage

Pipe a unix timestamp to `timeago`.

```sh
▶ date +%s | ./timeago
0 seconds ago

▶ echo 1573726417 | ./timeago
21 seconds ago

▶ echo 1573723417 | ./timeago
53 minutes ago

▶ echo 1573721417 | ./timeago
1 hour ago

▶ echo 1573321417 | ./timeago
5 days ago
```

# Sift

Sift filters unimportant news.

## How it works

* Sift sends you the news only when it breaks the threshold for a minimum amount of votes (set by you).
* Sift allows you to upvote the news, so that it reaches more people.

## Example

* Alice sets "min votes" to 1
* Bob sets "min votes" to 2
* Sam sends a link to an official announcement of government curfew.
* Cullbot forwards the link to Alice, because she has "min votes" set at 1
* Cullbot **doesn't forward the link to Bob**, because he has "min votes" set at 2
* Alice upvotes the curfew announcement, because she thinks it's important.
* Cullbot forwards the link to Bob, because now the announcement has 2 votes.

# Booker Blue

This app is intended to be federatable personal library webapp. The idea is that on an instance, users maintain personal libraries, and can connect with other users to expose their libraries to each other. They can then request to borrow books. Different instances can also be federated, so that users can increase their reach.

The app tracks the following information:

- title
- medium (movie, book, comic, cd)
- genre (namespaced to medium)
- tags
- creator (authors, directors)
- secondary creators (artist, stars)
- format (hardback, dvd)
- summary (pull from an API?)
- review (personal review)
- location - defined per user (home, beach house, shelf, on loan, etc)
- available for borrowing?
- visible to others?

## Things I know it's going to need

- user management
  - instance admin
  - signups
  - confirmations
  - password resets
  - profile editing
- media model
  - inherited by specific mediums
- API for federation
  - steal ideas from [Mastodon](http://mastodon.social) or [GNU Social](https://gnu.io/social)

## License

Licensed under the [AGPL v3](https://choosealicense.com/licenses/agpl-3.0/#). Sharing is caring!
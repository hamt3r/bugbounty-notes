# WordPress User Enumeration via REST API

## Status
Informational / Intended Behavior

## Summary
Public access to `/wp-json/wp/v2/users` allows enumeration of WordPress usernames and IDs.

## Notes
- Considered intended behavior by WordPress core
- Useful only when chained with other issues (XML-RPC, weak rate limits)

## Lesson Learned
Always review vendor security model before reporting.

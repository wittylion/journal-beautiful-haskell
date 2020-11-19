Thanks to [K. A. Buhr's answer on StackOverflow](https://stackoverflow.com/a/60793739)

For this method you will need three packages: `http-client`, `http-client-tls` and `bytestring`. Don't forget to add them to your project as dependencies.

In stack's package.yaml it should look like this:
```
dependencies:
- ...
- bytestring
- http-client
- http-client-tls
```

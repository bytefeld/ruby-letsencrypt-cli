# Change Log

## [v0.5.0](https://github.com/zealot128/ruby-letsencrypt-cli/tree/v0.5.0)

* fix for CSR generated using a pre-1.0.2 OpenSSL with a client that doesn't properly specify the CSR version. See https://community.letsencrypt.org/t/openssl-bug-information/19591 (Acme::Client::Error::Malformed) https://github.com/zealot128/ruby-letsencrypt-cli/commit/b7fd1d592e9a74905f5067b64e0ac88a526cfeed
* explicitly require colorize Gem so color support does work https://github.com/zealot128/ruby-letsencrypt-cli/commit/b43510d1be1a495923ea8e27051b3a0bae4e23b0

## [v0.4.1](https://github.com/zealot128/ruby-letsencrypt-cli/tree/v0.4.1)

*  fix renewing via manage command when certificate is not expired https://github.com/zealot128/ruby-letsencrypt-cli/commit/8e6b9cd4a2b1d0caa7a85d6ead410b98555cb499
*  require logger in beginning of file

## [v0.4.0](https://github.com/zealot128/ruby-letsencrypt-cli/tree/v0.4.0)

* New ``--sub-directory`` option to use that instead of first domain name
* Solves issue #10 -- certificate_exists_and_valid_and_all_domains_included? returns true when cert is expired

## [v0.3.0](https://github.com/zealot128/ruby-letsencrypt-cli/tree/v0.3.0)

* Certificate creation checks if existing certificate includes all requested domains. If at least one is missing, a new cert will be requested
* Added Ruby 2.3.0 and Ruby head to the build matrix

[Full Changelog](https://github.com/zealot128/ruby-letsencrypt-cli/compare/v0.2.0...v0.3.0)

## [v0.2.0](https://github.com/zealot128/ruby-letsencrypt-cli/tree/v0.2.0)

[Full Changelog](https://github.com/zealot128/ruby-letsencrypt-cli/compare/v0.1.4...v0.2.0)

**Closed issues:**

- cf1e0d9 Exit code 2, if certificate is still valid

**Merged pull requests:**

- Apply strict permissions on private key [\#4](https://github.com/zealot128/ruby-letsencrypt-cli/pull/4) ([zygiss](https://github.com/zygiss))
- Fix typo in README [\#2](https://github.com/zealot128/ruby-letsencrypt-cli/pull/2) ([kenrick](https://github.com/kenrick))

## [v0.1.4](https://github.com/zealot128/ruby-letsencrypt-cli/tree/v0.1.4) (2015-12-08)

* require higher acme-client version, that generated correct fullchain certs.
  fullchain.pem is chain.pem + cert.pem, should be cert.pem + chain.pem [\#1](https://github.com/zealot128/ruby-letsencrypt-cli/issues/1)

[Full Changelog](https://github.com/zealot128/ruby-letsencrypt-cli/compare/v0.1.3...v0.1.4)

## [v0.1.3](https://github.com/zealot128/ruby-letsencrypt-cli/tree/v0.1.3) (2015-12-06)

* Fixed registration
* Added various specs

[Full Changelog](https://github.com/zealot128/ruby-letsencrypt-cli/compare/v0.1.2...v0.1.3)

## [v0.1.2](https://github.com/zealot128/ruby-letsencrypt-cli/tree/v0.1.2) (2015-12-05)

* Added manage command
* Improved nginx doc + Ruby installation

[Full Changelog](https://github.com/zealot128/ruby-letsencrypt-cli/compare/v0.1.1...v0.1.2)

## [v0.1.1](https://github.com/zealot128/ruby-letsencrypt-cli/tree/v0.1.1) (2015-12-05)

[Full Changelog](https://github.com/zealot128/ruby-letsencrypt-cli/compare/v0.1.0...v0.1.1)

* b654469 new command: check PATH_TO_CERT

## [v0.1.0](https://github.com/zealot128/ruby-letsencrypt-cli/tree/v0.1.0) (2015-12-05)

* released first public version
* added --version flag
* added explicit production server

[Full Changelog](https://github.com/zealot128/ruby-letsencrypt-cli/compare/v0.1.0.beta1...v0.1.0)

## [v0.1.0.beta1](https://github.com/zealot128/ruby-letsencrypt-cli/tree/v0.1.0.beta1) (2015-12-05)
[Full Changelog](https://github.com/zealot128/ruby-letsencrypt-cli/compare/v0.1.0.pre...v0.1.0.beta1)

## [v0.1.0.pre](https://github.com/zealot128/ruby-letsencrypt-cli/tree/v0.1.0.pre) (2015-12-05)


\* *This Change Log was (partially) automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*

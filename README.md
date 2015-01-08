vend-js-sdk
===========

Aims to provides a rich set of client-side functionality for Vend's public APIs

Simple-Legal-Speak
==================

This is a labor of love. This effort is not funded, endorsed or sponsored by Vend.

This module is being written out of sheer respect for Vend's uncanny success at platformizing retail with their public API. It will hopefully help democratize access further by adding ease of use for developers. The authors of this module are not Vend employees and Vend didn't ask us to do this so don't go chewing their ears off for any mistakes made here. When in doubt, be sure to pay attention to the details expressed in the LICENSE file.

Features
========
1. Added sample API call for fetching product
  1. requires nothing more than a subdomain/domain-prefix and basic authN for developers to start experimenting: `NODE_ENV=dev node sample.js`
  2. *always* uses promises instead of callbacks
2. Uses oauth for API calls.

Roadmap
=======

1. Add sample API calls for all the exposed REST endpoints at https://developers.vendhq.com/documentation/api/index.html
  1. *must* handle 429 response code for rate limiting
2. Code up a plug-&-play or drop-in utility class for OAuth w/ Vend that anyone can add to their workflow.

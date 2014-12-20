macaroons-compatibility-test-suite
==================================

There is a growing number of projects out there, which implement Macaroons.
Macaroons are flexible authorization credentials that support decentralized delegation, attenuation, and verification.
A few projects are listed on http://macaroons.io/

This project aims to establish a test suite, which makes different implementations comparable.
Thus its possible to see, if different implementations with different versions are interoperable.

The basic idea for such tests is quite simple. Each tests defines a set of input data (e.g. Base64 encoded macaroon) and an expected output data or expected behaviour (e.g. exception). Each project implemented a test-suite, which handles these data. After running all tests, another tool collects all created output data and builds a summary page. This summary page will be published on macaroons.io. So users have an overview of how many tests each project satisfies.

If you have feedback or want to contribute, please get in contact with 'nitram509 at bitkings dot de'.

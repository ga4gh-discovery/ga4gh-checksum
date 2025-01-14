![](https://img.shields.io/badge/Status-Deprecated-Red) Please see [GA4GH SchemaBlocks Checksum](https://github.com/ga4gh-schemablocks/sb-checksum) for more info.

# GA4GH Discovery - Hash Algorithm Registry [![LICENCE](https://img.shields.io/github/license/susheel/ga4gh-hash-alg-registry)](https://github.com/susheel/ga4gh-hash-alg-registry/blob/master/LICENSE) 

This registry extends the [IANA Hash Algorithm Registry](https://www.iana.org/assignments/named-information/named-information.xhtml#hash-alg) with hash algorithms specific to the GA4GH community requirements.

## Specification - [Table of Hash Algorithms](https://github.com/susheel/ga4gh-hash-alg-registry/blob/master/hash-alg.csv)

| ID    | Hash Name String | Value Length   | Reference                                                                                   | Status  |
|:------|------------------|----------------|---------------------------------------------------------------------------------------------|---------|
| 0     | Reserved         |                | [RFC6920](http://www.iana.org/go/rfc6920)                                                   |         |
| 1     | sha-256          | 256 bits       | [RFC6920](http://www.iana.org/go/rfc6920)                                                   | current |
| 2     | sha-256-128      | 128 bits       | [RFC6920](http://www.iana.org/go/rfc6920)                                                   | current |
| 3     | sha-256-120      | 120 bits       | [RFC6920](http://www.iana.org/go/rfc6920)                                                   | current |
| 4     | sha-256-96       | 96 bits        | [RFC6920](http://www.iana.org/go/rfc6920)                                                   | current |
| 5     | sha-256-64       | 64 bits        | [RFC6920](http://www.iana.org/go/rfc6920)                                                   | current |
| 6     | sha-256-32       | 32 bits        | [RFC6920](http://www.iana.org/go/rfc6920)                                                   | current |
| 7     | sha-384          | 384 bits       | [FIPS 180-4](https://dx.doi.org/10.6028/NIST.FIPS.180-4)                                    | current |
| 8     | sha-512          | 512 bits       | [FIPS 180-4](https://dx.doi.org/10.6028/NIST.FIPS.180-4)                                    | current |
| 9     | sha3-224         | 224 bits       | [FIPS 202](https://dx.doi.org/10.6028/NIST.FIPS.202)                                        | current |
| 10    | sha3-256         | 256 bits       | [FIPS 202](https://dx.doi.org/10.6028/NIST.FIPS.202)                                        | current |
| 11    | sha3-384         | 384 bits       | [FIPS 202](https://dx.doi.org/10.6028/NIST.FIPS.202)                                        | current |
| 12    | sha3-512         | 512 bits       | [FIPS 202](https://dx.doi.org/10.6028/NIST.FIPS.202)                                        | current |
| 13    | md5              | 128 bits       | [RFC1321](https://www.ietf.org/rfc/rfc1321.txt)                                             | current |
| 14    | etag             | 128 + var bits | [RFC7232](https://tools.ietf.org/html/rfc7232#section-2.3)                                  | current |
| 15    | crc32c           | 32 bits        | [RFC4960](https://tools.ietf.org/html/rfc4960#appendix-B)                                   | current |
| 16    | trunc512         | 192 bits       | [GA4GH Refget](https://samtools.github.io/hts-specs/refget.html#trunc512-algorithm-details) | current |
| 17    | sha1             | 160 bits       | [FIPS 180-4](https://dx.doi.org/10.6028/NIST.FIPS.180-4)                                    | current |
| 18-31 | Unassigned       |                |                                                                                             |         |
| 32    | Reserved         |                | [RFC6920](http://www.iana.org/go/rfc6920)                                                   |         |
| 33-63 | Unassigned       |                |                                                                                             |         |

## Contributing
The GA4GH is an open community that strives for inclusivity. Teleconferences and corresponding meeting minutes are open to the public. To learn how to contribute to this effort, please email Rishi Nag (rishi.nag@ga4gh.org).

# Vulnerability data sources and attributions

The release assets of this repository are built by NodeWard from the public
sources below, using generators derived from Fleet (MIT). They are published
for NodeWard servers; each source keeps its own terms.

| Data | Source | Terms |
|---|---|---|
| CPE dictionary, CVE records | [NVD](https://nvd.nist.gov) | This product uses data from the NVD API but is not endorsed or certified by the NVD. |
| CVE enrichment | [VulnCheck NVD++](https://vulncheck.com/nvd2) | Data provided by **VulnCheck NVD++**. |
| Ubuntu OSV (`osv-ubuntu-*`) | [Canonical Ubuntu Security Notices](https://github.com/canonical/ubuntu-security-notices) | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/): these assets are redistributed under the same license. |
| Red Hat OSV and OVAL (`osv-rhel-*`, `rhel_*`) | [Red Hat Security Data](https://access.redhat.com/security/data) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), © Red Hat, Inc. |
| Go vulnerability database (`govulndb-*`) | [Go vulndb](https://vuln.go.dev) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), © The Go Authors. |
| Android OSV (`osv-android-*`) | [Android Security Bulletins](https://source.android.com/docs/security/bulletin) via [OSV.dev](https://osv.dev) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), © Google / Android Open Source Project; converted and filtered by NodeWard. |
| Amazon Linux (`amzn_*`) | Amazon Linux repository metadata (`updateinfo.xml` on `cdn.amazonlinux.com`, [ALAS](https://alas.aws.amazon.com)), via [goval-dictionary](https://github.com/vulsio/goval-dictionary) (Apache-2.0) | terms of the source |
| Microsoft security updates and Office notes (`fleet_msrc_*`, `fleet_*office*`) | Microsoft Security Response Center (CVRF API), Microsoft Learn | Microsoft terms of use |

The asset file names keep the `fleet_` prefixes that NodeWard servers expect.

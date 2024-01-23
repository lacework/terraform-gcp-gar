# v0.4.4

## Documentation Updates
* docs(readme): add terraform docs automation (#26) (Timothy MacDonald)([5304d28](https://github.com/lacework/terraform-gcp-gar/commit/5304d287033e4d3f4a7a9c59142fefeb9664ae0a))
## Other Changes
* chore: add lacework_metric_module datasource (#28) (Darren)([a54c346](https://github.com/lacework/terraform-gcp-gar/commit/a54c346933770975901a578a365433ca4c195b7a))
* ci: tfsec (jon-stewart)([4b395b5](https://github.com/lacework/terraform-gcp-gar/commit/4b395b562243508478dd6a7181c96670ffadf962))
* ci: version bump to v0.4.4-dev (Lacework)([f9df3a1](https://github.com/lacework/terraform-gcp-gar/commit/f9df3a1e969212c9ddf521f0fa7b23de159421a8))
---
# v0.4.3

## Bug Fixes
* fix: avoid asking for project_id when is not needed (#22) (Salim Afiune)([7bc97b7](https://github.com/lacework/terraform-gcp-gar/commit/7bc97b70b3b1835b3f9071d956d362cd5836a6a4))
## Other Changes
* ci: version bump to v0.4.3-dev (Lacework)([3890684](https://github.com/lacework/terraform-gcp-gar/commit/3890684cd9172d6b7ec7c50544ec58e1ce014b59))
---
# v0.4.2

## Bug Fixes
* fix: empty project_id in google_project data source (#20) (Salim Afiune)([387e1fe](https://github.com/lacework/terraform-gcp-gar/commit/387e1fe96709e08728786eaa44005cb822b41b0a))
## Other Changes
* ci: version bump to v0.4.2-dev (Lacework)([0c1aee9](https://github.com/lacework/terraform-gcp-gar/commit/0c1aee990155fb0f5281c86eb89fbf8c07c0744c))
---
# v0.4.1

## Documentation Updates
* docs: update Lacework provider version in readme (#18) (Darren)([384e7bf](https://github.com/lacework/terraform-gcp-gar/commit/384e7bf1adfc3b61d8e45a276dcc43550546635c))
## Other Changes
* chore: update Lacework provider version to v1 (#17) (Darren)([8e67cb1](https://github.com/lacework/terraform-gcp-gar/commit/8e67cb1d269cd7ad34849e29c38ddcd244f6bad4))
* ci: version bump to v0.4.1-dev (Lacework)([a43bfe1](https://github.com/lacework/terraform-gcp-gar/commit/a43bfe1eef31d47dc6ae4c17dd45b49889910e46))
---
# v0.4.0

## Features
* feat: deprecate support for Terraform 0.12 and 0.13 (#13) (Darren)([cf5fe77](https://github.com/lacework/terraform-gcp-gar/commit/cf5fe778a66c9de770577ee03ee16e16f34d84c4))
## Bug Fixes
* fix: adding roles/storage.objectViewer and enabling library scanning by default (#7) (Mike Laramie)([6ea75eb](https://github.com/lacework/terraform-gcp-gar/commit/6ea75ebd67feba5ed5d547402eab66ac677d7760))
## Documentation Updates
* docs: update docs.lacework.net example links (#6) (robewedd)([9b3c05c](https://github.com/lacework/terraform-gcp-gar/commit/9b3c05c07c62a3fbb17ae2a5c5121624e1d3e31b))
## Other Changes
* chore: update PR template (#12) (Darren)([87da017](https://github.com/lacework/terraform-gcp-gar/commit/87da017cb6bb55310e5475baecc96341529a286b))
* ci: fix example/default google version constraint (#15) (Salim Afiune)([2a757f0](https://github.com/lacework/terraform-gcp-gar/commit/2a757f05a6e8766a709e5dbd79381f01ecab3f92))
* ci: version bump to v0.3.1-dev (Lacework)([2e719a2](https://github.com/lacework/terraform-gcp-gar/commit/2e719a26f1ef08642049198976d168a78f00c8f2))
---
# v0.3.0

## Features
* feat: allow google provider version >= 3.0.0, < 5.0.0 (#10) (Darren)([e515d11](https://github.com/lacework/terraform-gcp-gar/commit/e515d11bda489c6ab65c88e57f20e5edc9211a1b))
## Other Changes
* ci: version bump to v0.2.1-dev (Lacework)([8965d56](https://github.com/lacework/terraform-gcp-gar/commit/8965d56a663ea62ff17ee9a2517ed51392ac15d6))
---
# v0.2.0

## Features
* feat: update non_os_package_support flag (Darren Murray)([9c2e776](https://github.com/lacework/terraform-gcp-gar/commit/9c2e7765e067d512bd61f6282fec99dec4ab1207))
## Documentation Updates
* docs: add contribution documentation (Darren Murray)([0c2f078](https://github.com/lacework/terraform-gcp-gar/commit/0c2f078beec1fe07a86b202d032cc93d923f2921))
## Other Changes
* ci: version bump to v0.1.1-dev (Lacework)([f764a19](https://github.com/lacework/terraform-gcp-gar/commit/f764a19a3772b3cc723652208f9e642ab9ec3a56))
---
# v0.1.0

## Bug Fixes
* fix: example scripts & formatting (#2) (Mike Laramie)([0daab76](https://github.com/lacework/terraform-gcp-gar/commit/0daab76dcd61c5dc65249d14b1aebf3b4cdffca2))
* fix: fixed default integration name (Mike Laramie)([be8d9d6](https://github.com/lacework/terraform-gcp-gar/commit/be8d9d6296fdb4ae31b1cdf5ae2be731c6c29fd5))
## Other Changes
* style: prepare release and updating version (#4) (Salim Afiune)([b54fb60](https://github.com/lacework/terraform-gcp-gar/commit/b54fb60d6f0d0a0408d227ed6d279a352ff8a1ce))
* chore: bump required version of TF to 0.12.31 (#3) (Scott Ford)([bf6cdf6](https://github.com/lacework/terraform-gcp-gar/commit/bf6cdf68a271cc49560dd66bb60fd590b0b1328c))
* ci: sign lacework-releng commits (#4) (Salim Afiune)([7a5d2bd](https://github.com/lacework/terraform-gcp-gar/commit/7a5d2bd2b5468d6d6e1537bcbdfa0cbbefded641))
* ci: fix finding major versions during release (#2) (Salim Afiune)([72197f2](https://github.com/lacework/terraform-gcp-gar/commit/72197f2f20bf5d67710a2bc2d38d4844427e6d77))
---

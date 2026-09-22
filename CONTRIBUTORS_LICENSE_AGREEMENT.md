# Developer Certificate of Origin (DCO)

Version 1.0

## Contributing to Mercedes-Benz Open Source Projects

Mercedes-Benz projects use the **Developer Certificate of Origin (DCO)** instead of a separate Contributor License Agreement (CLA).

The DCO is a lightweight way for contributors to certify that they have the right to submit their contributions and that those contributions may be distributed under the license of the project. No separate agreement or signature outside the contribution workflow is required.

By contributing to a project, you agree to the terms below and certify the statements in the DCO for each contribution.

## How to contribute

1. Review the project's `README`, `CONTRIBUTING.md`, `SECURITY.md`, and license before contributing.
2. Make sure that you have the right to submit the contribution. If you contribute on behalf of an employer or another organization, obtain any required internal approval first.
3. Do not submit confidential information, personal data, proprietary material, or third-party code unless the project explicitly permits it and you have the necessary rights and approvals.
4. Make your changes and submit a pull request according to the project's contribution guidelines.
5. Sign off every commit that you submit by adding a `Signed-off-by` line containing your real name and email address.

Example:

```text
Signed-off-by: Jane Doe <jane.doe@example.com>
```

You can add the sign-off automatically when creating a commit:

```bash
git commit -s -m "Describe the change"
```

If a pull request contains commits without a sign-off, update those commits before the pull request is merged. For example, to sign off the most recent commit:

```bash
git commit --amend --signoff
```

For multiple commits, follow the project's documented procedure for rewriting history and add the sign-off to each submitted commit. Do not rewrite shared history without coordinating with the project maintainers.

## Developer Certificate of Origin

By making a contribution to this project, I certify that:

1. The contribution was created in whole or in part by me and I have the right to submit it under the open source license indicated in the project; or
2. The contribution is based upon previous work that, to the best of my knowledge, is covered by an appropriate open source license and I have the right under that license to submit that work, with or without modifications, under the same or another compatible open source license indicated in the project; and
3. I understand that this project and my contribution may be publicly distributed and maintained; and
4. I understand that a record of the contribution, including the sign-off, may be maintained indefinitely in the project's version control history.

The exact DCO text is maintained by the Linux Foundation and is available at <https://developercertificate.org/>.

## Meaning of the sign-off

The `Signed-off-by` line is a declaration that you accept the DCO for the contribution associated with that commit. It is not a copyright assignment, does not transfer copyright ownership, and does not grant Mercedes-Benz rights beyond those provided by the project's applicable open source license.

The name and email address in the sign-off must identify you accurately. Do not sign off for another person unless you are authorized to do so and the sign-off accurately represents that person's certification.

## Contributions made on behalf of an employer

If you contribute as part of your employment or on behalf of an organization, you are responsible for ensuring that:

- you are authorized to submit the contribution;
- your employer or organization permits the contribution to be made under the project's license; and
- the contribution does not contain restricted, confidential, or third-party material that you are not authorized to share.

A DCO sign-off does not replace any approvals required by your employer or organization.

## Third-party and generated material

Do not submit third-party or automatically generated material unless you have verified its applicable license and are permitted to contribute it. Clearly identify such material in the pull request and preserve required notices and attribution. When in doubt, ask the project maintainers before submitting it.

## Pull requests and review

A DCO sign-off does not guarantee that a contribution will be accepted. Contributions remain subject to the project's technical, security, legal, licensing, and review requirements. Maintainers may request changes, additional information, proof of authorization, or removal of material before merging a contribution.

By submitting a pull request or other contribution, you agree that the contribution may be reviewed, modified, rejected, and distributed under the project's applicable open source license if accepted.

## Questions or concerns

If you are unsure whether you may submit material, whether a sign-off is valid, or how to correct a missing sign-off, contact the project maintainers before submitting the contribution. For security-sensitive issues, follow the reporting instructions in the project's `SECURITY.md` file rather than opening a public issue.

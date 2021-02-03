# Automated Build System

## Builds
### Preview

Commits with changes in **/publications/** are triggering the [Build pm2-Guide Preview Action](./workflows/build_pm2guide_preview.yml).
Only commits and merged pull request into the **master** branch are handled.

The Action can also be manually triggered on the [Githubs Action Page](https://github.com/pm2alliance/opm2-en/actions?query=workflow%3A%22Build+pm2-Guide+Preview%22).

Commit hash and date are included in the pdf. The pdf filename follows the form `pm2guide-#commithash.pdf`. 

Preview build can be downloaded as attached asset at [Github Latest Preview Page](https://github.com/pm2alliance/opm2-en/releases/tag/latest_preview)

### Release

**Commits tagged for release** are triggering [Build pm2-Guide Action](./workflows/build_pm2guide_release.yml)

It’s common practice to prefix your version names with the letter v. Some good tag names might be v1.0.0 or v2.3.4.
Read more at [Semantic Versioning](https://semver.org/).

Example: 
```console
~$ git tag v1.0.0
~$ git push origin --tags
```

Version number and date are included in the pdf. The pdf filename follows the form `pm2guide-#version.pdf`. 

Corresponding build can be downloaded as attached asset at [Github Release Page](https://github.com/pm2alliance/opm2-en/releases)

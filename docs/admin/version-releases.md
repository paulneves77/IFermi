# Releasing a new IFermi version

Version releases on Pypi and GitHub are handled automatically through GitHub
actions. The steps to push a new release are:
1. Update the version in `ifermi/__init__.py`
2. Update the changelog in `CHANGELOG.rst` with the new version and
   release notes.
3. Create a tagged Git commit with the above changes. The tag is added using:
```bash
git tag v0.2.5
```
4. Push the commit and tags to GitHub using:
```bash
git push origin --tags
```

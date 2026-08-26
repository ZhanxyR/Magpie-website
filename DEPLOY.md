# GitHub Pages deployment

This folder is a self-contained static build. Video files are loaded from Alibaba Cloud OSS, so no MP4 files need to be committed to GitHub.

1. Copy all contents of this folder, including `.nojekyll`, to the root of the branch used for GitHub Pages.
2. In the repository, open **Settings → Pages**.
3. Select **Deploy from a branch**, then choose that branch and the `/ (root)` folder.
4. Save and wait for the published URL to become available.

All site asset URLs are relative, so this build works both at `username.github.io` and under a project path such as `username.github.io/repository-name/`.

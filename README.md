# yuzu-build
Merge yuzu's 'early-access-merge' and 'mainline-merge' pr to master branch.

The build process is completely transparent, with source code from the official yuzu repo.

Download build from ['Action'](https://github.com/zhongfly/yuzu-build/actions) tab.

## Tips
- This workflow will release build files with 'release' tag.If you want to release files,please go to repo's setting → Action → General → Workflow permissions, choose 'Read and write permissions' and click 'save'.If you don't want to do this, just ignore the error about release failed.

# CAMdev

This repository stores CAM development code.

## Development log

| Branch     | Tag                          | Summary                                | Description                                                  |
| ---------- | ---------------------------- | -------------------------------------- | ------------------------------------------------------------ |
| 2_1_rel_41 | cam_cesm2_1_rel41            | upload original cam_cesm2_1_rel41 code | https://github.com/ESCOMP/CAM/tree/cam_cesm2_1_rel_41        |
| 2_1_rel_41 | cam_cesm2_1_rel41-change_svn | replace svn by git                     | - used for downloading CAM in CESM; - use git to manage externals |
| 2_1_rel55  | cam_cesm2_1_rel55            | upload original cam_cesm2_1_rel55 code | https://github.com/ESCOMP/CAM/tree/cam_cesm2_1_rel_55        |
| 2_1_rel55  | cam_cesm2_1_rel55-change_svn | replace svn by git                     | - used for downloading CAM in CESM; - use git to manage externals |
| 2_1_rel55  | cam_cesm2_1_rel55-smooth_bb  | add SSP585smoothbb                     | Add SSP585 smooth biomass burning configuration              |
|            |                              |                                        |                                                              |

## Git action

### Initial and ssh

```
git init
cd /Users/user/Desktop/YuanSun-UoM/CAMdev/

# update the remote URL
git remote set-url origin git@github.com:YuanSun-UoM/CAMdev.git
```

### branch management

- Check existing branch

```
git branch
```

- create a new branch

```
git checkout -b cesm2.1-rel41 # CAM version for CESM2.1.3

git checkout -b cesm2.1-rel55 # CAM version for CESM2.1.4


```

### tag management

- Tag and then push tag

```
git tag cam_cesm2_1_rel41
git push origin cam_cesm2_1_rel41

git tag cam_cesm2_1_rel41-change_svn
git push origin cam_cesm2_1_rel41-change_svn

git tag cam_cesm2_1_rel55
git push origin cam_cesm2_1_rel55

git tag cam_cesm2_1_rel55-change_svn
git push origin cam_cesm2_1_rel55-change_svn 

git tag cam_cesm2_1_rel55-smooth_bb
git push origin cam_cesm2_1_rel55-smooth_bb
```

### .DS_Store

```

```


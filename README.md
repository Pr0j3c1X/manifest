<p align="center">
<img src="https://raw.githubusercontent.com/samgrande/manifest-1/dot-p/Untitled-1.png" > 
</p>
<p >
<img src="https://raw.githubusercontent.com/samgrande/manifest-1/dot-p/Untitled-3.png" > 
</p>

# Downloads:

[![Download dotOS 2.x - O](https://a.fsdn.com/con/app/sf-download-button)](https://sourceforge.net/projects/dotos-2-x/files/latest/download)      [![Download dotOS 2.x - O](https://img.shields.io/sourceforge/dt/dotos-2-x.svg)](https://sourceforge.net/projects/dotos-2-x/files/latest/download)      [![Download dotOS 2.x - O](https://img.shields.io/sourceforge/dd/dotos-2-x.svg)](https://sourceforge.net/projects/dotos-2-x/files/latest/download)      [![Download dotOS 2.x - O](https://img.shields.io/sourceforge/dw/dotos-2-x.svg)](https://sourceforge.net/projects/dotos-2-x/files/latest/download)      [![Download dotOS 2.x - O](https://img.shields.io/sourceforge/dm/dotos-2-x.svg)](https://sourceforge.net/projects/dotos-2-x/files/latest/download)

 Credits:
 =======
 * [**LineageOS**](https://github.com/LineageOS)
 * [**DirtyUnicorns**](https://github.com/dirtyunicorns)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**ABC**](https://github.com/ezio84?tab=repositories)

-----------------------------------------------------------------------------
 Gerrit:
 ==============
 Submit your All patches through our [Gerrit Code Review](http://gerrit.droidontime.com/).
 Getting Started:
 ==============

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository, use a command like this:

```bash
    repo init -u git://github.com/DotOS/manifest.git -b dot-p
```

Then to sync up:

```bash
    repo sync  -f --force-sync --no-clone-bundle --no-tags
```

Additionally, you can define the number of parallel download repo should do:

```bash
    repo sync -f -jX --force-sync --no-clone-bundle --no-tags ( X is the number of parallel download repo should do choose depending on your cpu )
```
----------------------------------
 Compilation of Dot OS
 ==================

From root directory of Project, perform following commands in terminal


```bash
	source build/envsetup.sh
   
        lunch dot_<codename>
   
	brunch <codename>
```


For maintainership & to submit patches refer [**HERE**](https://github.com/DotOS/android_vendor_dot/blob/dot-p/README.md)



<p align="center">
<img src="https://raw.githubusercontent.com/samgrande/manifest-1/dot-p/Untitled-4.png" > 
</p>

Repo Mirror:https://mirrors.tuna.tsinghua.edu.cn/git/git-repo/
export REPO_URL='https://mirrors.tuna.tsinghua.edu.cn/git/git-repo/'


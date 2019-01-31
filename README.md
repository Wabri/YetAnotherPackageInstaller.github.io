## Welcome to the Yet Another Package Installer Project

Yapi is a package manager with the main focus on easier user interaction with cross platform support.

Users should be able to run the same commands on different systems and have a predictable result for that package that was installed.

### Versions

Yapi is formed in two main versions. There is YAPI for the original debian version where all package scripts are downloaded, and can be run easily. There is also a version called rewrite. The rewrite is working on supporting multiple platforms with a config updater and downloadable install scripts.

### Downloading
YAPI

```bash
wget https://raw.githubusercontent.com/YetAnotherPackageInstaller/YAPI/master/install.sh -O - | sudo bash -
```

```bash
wget https://raw.githubusercontent.com/YetAnotherPackageInstaller/rewrite/master/install.sh -O - | sudo bash -
```

For more details see the individual repositories.

### General Usage

Packages can be downloaded by running a command that includes the name of the package to install

```bash
./yapi.sh install test
```

### Support or Contact

If you are having trouble with YAPI or would like to submit feedback. Please go to the page for the repository.

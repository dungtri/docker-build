# Instructions

## linux

1. Clone this as _build_ sumodule in your repository
   - `git submodule add https://github.com/angelnu/docker-build.git build `
2. `ln -s build/build.sh .`
3. `cp -av build/build.config .`
4. edit build.config

## windows

1. Clone this as _build_ sumodule in your repository
   - `git submodule add https://github.com/angelnu/docker-build.git build `
2. Create a build.sh file in your repo. Add `build/build.sh`to the file.
3. Copy build.config to your repository and edit it.
4. Give execution permission to build.sh.
   - `git update-index --chmod=+x build.sh `

## travis

1. `cp -av build/travis.yml .travis.yml`

## drone

1. `cp -av build/drone.yml .drone.yml`

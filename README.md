# rosenv
a script to manage several ROS workspaces

## Install
```sh
curl https://raw.github.com/garaemon/rosenv/master/install.sh | bash
```

## Usage
Please run `rosenv help` for details.
### register a existing workspace
```sh
rosenv register <nickname> <directory> <distro>
```

### switch workspaces
```sh
rosenv use <nickname> [--devel|--install]
rosenv use --devel
rosenv use --install
```

### update worksapce
```sh
rosenv update [<nickname>] [-jJOB_NUM]
```

### install workspace
```sh
rosenv install <nickname> <path> <rosinstall> [<rosinstall> <rosinstall> ...] [--rosbuild]
```

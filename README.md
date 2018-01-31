# rc
rc manager
> rc -> run control


# Usage
## Installation
```bash
npm i -g lx-rc
```

## vimrc
```bash
# will backup ~/.vimrc to ~/.vimrc.backup
rc vim --init
```

## eslintrc
```bash
# cd your project root
rc eslint --init
```

## ternrc
```bash
# cd your project root
rc tern --init
```

## stylelintrc
```bash
# cd your project root
rc stylelint --init
```

## htmlhintrc
```bash
# cd your project root
rc htmlhint --init
```

## aria2
```bash
# install
rc aria2 --install

# will create ~/.aria2rc
rc aria2 --init

# start rc server
rc aria2 --start
```

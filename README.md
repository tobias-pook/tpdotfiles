
## Quickstart


```
cd ~
git clone --recursive https://github.com/tobias-pook/tpdotfiles.git
cd tpdotfiles
# Create .env file
./dotdrop/bootstrap.sh
alias dotdrop='eval $(grep -v "^#" ~/tpdotfiles/.env) ~/tpdotfiles/dotdrop.sh'
dotdrop.sh install --profile MYPROFILE
```

See documentation of [dotdrop](https://github.com/deadc0de6/dotdrop) for more information

### Available profiles:
  **tpx1**: Profile for x1 carbon notebooks with manjaro

# Demon

Watch & compile typescript file using deno with bash script — Learn Deno

### Prepare

For OSX first you must install **md5sha1sum** using **[brew](https://brew.sh/)**, if you already have **brew** on your local machine. Just run a single command below :

```
$ brew install md5sha1sum
```

### Usage

1. Download bash script file

```
git clone https://github.com/comdevx/demon.git && mv demon/demon /usr/local/bin/demon && chmod +x /usr/local/bin/demon && rm -rf demon
```

2. Run **demon** using this command :

```
$ demon <your file> <options>
$ demon <your file> --allow-net
```

### Related

- [Argument Parser](https://github.com/muhibbudins/deno-arguments)
- [Read File](https://github.com/muhibbudins/deno-readfile)
- [Yaml Parser](https://github.com/muhibbudins/deno-yaml)
- [All Topic](https://github.com/topics/learn-deno)

### License

This project under MIT License

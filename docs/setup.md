# Setup

## The Node Version Manager

I utilize the Node Version Manager (nvm) to quickly install and use different
versions of node via the command line.

Determining which version of node is currently active:

```shell
node -v
```

Selecting a specific version of Node:

```shell
nvm use v20.9.0
```

Listing the remote versions of Node:

```shell
nvm ls-remote
```

Installing a specific version of Node:

```shell
nvm install v20.9.0
```

Listing locally installed versions of Node:

```shell
nvm ls
```

Setting a default version of Node:

```shell
nvm alias default 20.9  # this refers to the latest installed v20.9.x version of node
```

Installing the Angular CLI:

```shell
npm install -g @angular/cli
```

## Angular/Node Version Compatibility

To determine which versions of Angular are compatible with a specific version of Node, refer to the [Angular documentation](https://angular.io/guide/versions).


## References

* [Node Version Manager](https://github.com/nvm-sh/nvm)
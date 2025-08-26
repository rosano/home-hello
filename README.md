# Home Hello

Use my [home]() as yours.

## Run it locally

First [install Hugo](https://gohugo.io/installation/) extended edition; I prefer the [pre-built binary](https://github.com/gohugoio/hugo/releases/latest).

Then add 'home' to your project:

```
git submodule add -f https://github.com/rosano/home.git themes/home
git submodule add -f https://github.com/rosano/home-unconfig.git themes/home-unconfig
```

Now you can start the web server which reloads on any change:

```
hugo server
```

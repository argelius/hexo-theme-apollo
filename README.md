Theme for the Zonkytech blog. Forked from [Apollo](https://github.com/pinggod/hexo-theme-apollo).

## Usage

``` bash
hexo init blog
cd blog
npm install
npm install --save hexo-renderer-jade hexo-generator-feed hexo-generator-sitemap hexo-browsersync hexo-generator-archive hexo-authors
git clone https://github.com/zonkytech/hexo-theme-zonky.git themes/zonky
```

## Configuration

Edit the `_config.yml` file and set the them to "zonky".

```yaml
theme: zonky

# Archive generator
archive_generator:
    per_page: 0
    yearly: false
    monthly: false
    daily: false

# Authors
authors:
  default:
    name: 'Default poster'
  alice:
    name: Alice
    email: alice@example.com
  bob:
    name: Bob
    gravatar: 4b9bb80620f03eb3719e0a061c14283d
```

## Update

``` bash
cd themes/zonky
git pull
```

## License

MIT

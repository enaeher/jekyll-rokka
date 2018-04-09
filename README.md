# jekyll-rokka

*N.B.: this plugin was written mainly for my own use and I can provide
 only very limited support.*

A plugin to facilitate linking to images hosted by
[rokka.io](https://rokka.io).

Your Rokka organization and stack names are configured in your
`_config.yml`:

```yaml
rokka:
  organization_name: your-org-name
  stack_name: your-stack-name
```

You can link to images using their short (or long) hash, with an
optional description (goes in `alt` and `title` attributes)

```
{% rokka_photo 0ccc2a "Lorem dolor sic amet" %}
```

See [this blog post](https://eli.naeher.name/rokka/) for more context.
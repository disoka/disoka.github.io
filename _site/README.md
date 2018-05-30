# disoka.github.io

Disoka.com marketing Website

disoka.com (dns hover.com) --> DNS A record to Github pages --> github (disoka.github.io) + CNAME --> Web site

### How to build?

- `_config.yml` contains the gem dependencies like `jekyll-paginate`, `redcarpet` for the site to run on a local machine.

To build the site on local machine, run the following command:
`$ jekyll serve --baseurl ''`

Example:
```
ak@~/projects/disoka.github.io $ jekyll serve
Configuration file: /Users/ak/projects/disoka.github.io/_config.yml
       Deprecation: The 'gems' configuration option has been renamed to 'plugins'. Please update your config file accordingly.
            Source: /Users/ak/projects/disoka.github.io
       Destination: /Users/ak/projects/disoka.github.io/_site
 Incremental build: disabled. Enable with --incremental
      Generating... 
                    done in 0.154 seconds.
 Auto-regeneration: enabled for '/Users/ak/projects/disoka.github.io'
    Server address: http://127.0.0.1:4000/
  Server running... press ctrl-c to stop.

```

### References:
- setting up github pages custom domain: https://help.github.com/articles/setting-up-an-apex-domain/

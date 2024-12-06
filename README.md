# filter_taxonomies

Modification for https://github.com/hbstack/blog/

Adjusted the sidebar taxonomies to display only the allowed taxonomies per section. If no allowed taxonomies are configured, all taxonomies will be displayed.

Configuration (yaml):

```
params:
    hb:
        filter_taxonomies:
            [section]:
                allowed:
                    - taxonomy A
                    - taxonomy B
                        ...


Replace "[section]" with one of your existing sections, e.g. news, blog, books

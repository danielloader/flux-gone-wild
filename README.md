# flux-gone-wild

- Fork repository
- Create deploy SSH key with write permissions
- Run bootstrap
    flux bootstrap git \
    --url=ssh://git@github.com/danielloader/flux-gone-wild \
    --branch=main \
    --private-key-file=$HOME/.ssh/flux-gone-wild-deploy \
    --path=clusters/kind

# Governance Handbook

This is an early draft of an attempt to draw together the various intersecting aspects of governance in our co-operative.

This first pass has no consensus nor review, but may eventually become a work output of the Governance Group.

## Contribute

PRs and issues from anyone at ODS are welcome.

## Build locally

The template works with Jekyll. Build in a docker container to serve locally:

```
sudo docker run --rm \
  --volume="$PWD:/srv/jekyll:Z" \
  --publish [::1]:4000:4000 \
  jekyll/jekyll \
  jekyll serve
```

Then visit `localhost:4000`.

This automatically reloads when changes are made.
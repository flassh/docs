# Flassh Docs

### Get em running locally

```
brew install hugo
hugo server
```

Point your browser at [http://localhost:1313](http://localhost:1313/).

All manual changes should be made outside the `public/` directory, as this
directory is auto-generated upon each deploy.

### Deploy 'em

Commit all your changes to master and push. Ensure no changes are staged in
git and run:

```
./deploy.sh
```

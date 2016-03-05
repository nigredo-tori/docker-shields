[![Travis](https://shields.beevelop.com/travis/beevelop/docker-shields.svg?style=flat-square)](https://travis-ci.org/beevelop/docker-shields)
[![Docker Pulls](https://shields.beevelop.com/docker/pulls/beevelop/shields.svg?style=flat-square)](https://links.beevelop.com/d-shields)
[![ImageLayers Layers](https://shields.beevelop.com/imagelayers/layers/beevelop/shields/latest.svg?style=flat-square)](https://links.beevelop.com/d-shields)
[![ImageLayers Size](https://shields.beevelop.com/imagelayers/image-size/beevelop/shields/latest.svg?style=flat-square)](https://links.beevelop.com/d-shields)
[![GitHub release](https://shields.beevelop.com/github/release/beevelop/docker-shields.svg?style=flat-square)](https://github.com/beevelop/docker-shields/releases)
![Badges](https://shields.beevelop.com/badge/badges-7-brightgreen.svg?style=flat-square)
[![Beevelop](https://links.beevelop.com/honey-badge)](https://beevelop.com)

# [Shields.io](https://github.com/badges/shields) for Docker :whale:

```bash
docker run -d --name shields -p 80:80 \
    -e INFOSITE="http://shields.example.com" \
    beevelop/shields
```

## Configuration
- `GH_CLIENT_ID` (default: null)
- `GH_CLIENT_SECRET` (default:null)
- `INFOSITE` (default: `"http://shields.io"`)

# falcon-plus-patch

```
git diff modules/agent/main.go modules/agent/g/cfg.go > falcon-agent.patch

```

## How to Use

```
git clone falcon-plus
cd falcon-plus

wget https://raw.githubusercontent.com/taomaree/falcon-plus-patch/master/falcon-agent.patch

patch -p1 < falcon-agent.patch

```

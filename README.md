# falcon-plus-patch
Deprecated. all patches ware merged into https://github.com/taomaree/falcon-plus/ 


```
git diff modules/agent/main.go modules/agent/g/cfg.go > falcon-agent.patch
```

## falcon-agent.patch Features

+ READ ENV ENDPOINT
+ SET  ENV FALCON_AGENT_RUNTIME
+ IGNORE ISO MOUNT POINT

## How to Use

```
git clone falcon-plus
cd falcon-plus

wget https://raw.githubusercontent.com/taomaree/falcon-plus-patch/master/falcon-agent.patch

patch -p1 < falcon-agent.patch

```

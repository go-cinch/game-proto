# Game Proto

## add
```shell
# normal add
git submodule add -b main --name api/game-proto https://github.com/go-cinch/game-proto.git ./api/game-proto

# or force add
git submodule add -f -b main --name api/game-proto https://github.com/go-cinch/game-proto.git ./api/game-proto
```

## update
```shell
git submodule update --force --recursive --init --remote
```

# config.yml

```yaml
# Token 认证令牌
# 将购买后给的令牌天到此处
Token: ""

# 战斗模式持续时间
Combat-Time: 10

# 传送等待时间
Spawn-Cool-Down: 3

# 击杀给予经济
Kill-Coins: 10

# 死亡保留经验
Keep-Death-Exp: false

# 进入游戏几秒内无伤害 (不建议设置为 0)
No-Damage-On-Join: 3

# 击如虚空时, 认定多少秒内的攻击者为杀手
Void-Kill-Time: 10

# 自定义打开幸运方块声音
# 1.8 LEVEL_UP
# 1.9+ ENTITY_PLAYER_LEVELUP
Open-Loot-Sound: ""

# 出生位置
Spawn-Loc: ""

# 数据部分
MySQL:
  host: mysql.yistars.net
  port: 3306
  username: BingSkyPvP
  password: bhx7HNpYkxy6rLdX
  database: bingskypvp
```

## Token

购买后联系插件作者获取的 Token，需要正确填入 Token，插件才可以正常运行。

## Combat-Time

当玩家攻击其他玩家/被其他玩家攻击后，多久退出战斗模式。

战斗模式下离开游戏，会直接使玩家死亡，掉落背包物品。

## Spawn-Cool-Down

玩家使用 `/spawn` 命令后需要等待多久才会传送。

## Keep-Death-Exp

玩家死亡后是否保留经验。

## No-Damage-On-Join

玩家进入游戏后多少秒不会受到伤害。起初此功能是为了防止玩家从虚空传送到出生点时，因为 Minecraft 的特性，导致玩家摔死而设计的。所以不建议将此值设置的过小。

## Void-Kill-Time

当一名玩家在因为坠入虚空而死亡时，判定多少秒内对他攻击的玩家为击杀者。

## Open-Loot-Sound

打开幸运方块时的声音。

## Spawn-Loc

重生点的坐标，通常情况下，不需要自己填写。你可以使用 `/SkyPvP setSpawn` 命令设置。

## MySQL

目前仅支持 MySQL 数据库，正常填写即可。
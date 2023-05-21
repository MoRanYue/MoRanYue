```ts
imoprt { SimpleWorld } from 'parallel'

class World {
  constructor() {
    this.objects: {
      position: [number, number, number],
      velocity: [number, number, number],
      size: [number, number, number][],
      moving: boolean
    }[] = []
    this.elements = {
      hydrogen: {},
      carbon: {},
      // And much much much much much elements
    }
  }
  startWorld(port: number = 1, universe: string = "#01") {
    const world = new SimpleWorld()
    world.name = universe
    world.atomComputation = true
    world.init(port)
    world.randomSpawn(this.elements, {
      randomPos: true,
      count: 1145141919810
    })
  }
}

const world = new World()
world.startWorld()
```

# 我是谁？

大家好呀！我是`MoRanYue`（墨染月）。
我只是个初中生（现在是初二），我热爱编程。

* 热爱研究Web技术
* 我喜欢康B站上的游戏与编程视频
* 原**P**layer、穹**P**layer
* 患有社交牛X症（bushi）

<span style="font-size:0.5rem;text-decoration:line-through;">（可恶，不会写自我介绍）</span>

# 我的联络方式

* 电子邮箱：[2627706726@qq.com](mailto:2627706726@qq.com)、[sllhsdog@gmail.com](mailto:sllhsdog@gmail.com)
* 比利比利：[@属官一号](https://space.bilibili.com/50500335)
* Steam：[墨染月𝑴𝑹𝒀](https://steamcommunity.com/id/MoRanYue/)

# 关于我擅长的编程语言

如果按使用频率排序的话……

* `JavaScript`、`TypeScript`
* `Python`
* `Lua` - 主要是《盖瑞模组》插件开发
* `C#` - 主要是《SCP：秘密实验室》插件开发
* `Java`
* `Rust`

# 以及……

* 有用虚幻引擎做些小游戏游戏的梦想，而学习却半途而废。
* 有学习深度学习的梦想却被微积分打败。
* 想要提升在比利比利投稿的视频质量却懒（）。
* 正在学习安卓逆向。
* -<span style="text-decoration:line-through;" title="不行，这个划掉！">非常喜欢纳西妲！！！！！！</span>-

# 兴趣爱好

* 原神、崩坏：星穹铁道
* 关于后室、SCP的游戏
* 盖瑞模组
* <span style="text-decoration:line-through">发消息带上不明意义的括号、（吹牛X）</span>
* 分享关于游戏的知识

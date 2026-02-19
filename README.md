# Seedream Image Prompt Skill

**Generate high-quality AI image prompts for [Seedream 5.0](https://jimeng.jianying.com/) by ByteDance.**

[English](#english) | [中文](#中文)

---

<a id="english"></a>

## English

### Features

- **Text-to-Image Prompts** — Structured prompt templates for portraits, landscapes, posters, cards, and more
- **Image Editing** — Style transfer, element add/remove, lighting adjustment, makeup changes
- **Character Consistency** — Keep face, hair, clothing identical across multiple generated images
- **Knowledge Cards** — Infographic, tarot, blueprint, game skill card, and ancient scroll styles
- **E-commerce** — Product photography prompts for online stores
- **Multi-image Fusion** — Combine up to 14 reference images with precise element control
- **Text Rendering** — 99%+ accuracy for Chinese/English text in images
- **Style Dictionary** — 200+ curated style keywords organized by category
- **API Reference** — Complete Volcengine Ark API params, size charts, and Python examples

### Quick Install

**Cursor / Claude Code / Cline / Other Agents:**

```bash
npx skills add ppdbxdawj/seedream-image-skill@seedream-image
```

**Manual:**

```bash
git clone https://github.com/ppdbxdawj/seedream-image-skill.git
cp -r seedream-image-skill/seedream-image ~/.cursor/skills/
```

### Supported Platforms

| Platform | Access | Notes |
|----------|--------|-------|
| [Jimeng AI](https://jimeng.jianying.com/) | Web | 20 free generations/day |
| [Volcengine Ark](https://console.volcengine.com/ark) | API | Enterprise, 4K direct |
| [Jianying](https://www.capcut.cn/) | App | AI Drawing feature |
| [CapCut](https://www.capcut.com/) | App | Global version |

### Example Prompts

**Portrait Photography**
```
Young Asian man, clean features, black oversized sweater,
sitting by library window reading, sunlight on side face,
Tyndall light, cool tones, shallow depth of field, 85mm prime lens,
cinematic realism style, ultra HD
```

**Knowledge Card (Fantasy RPG Style)**
```
Design a fantasy RPG game skill card explaining "[CONCEPT]".
Include a cool glowing icon, skill description in game language,
energy cost and cooldown timer. Dark fantasy style with luminous
magical rune borders.
```

**E-commerce Product Shot**
```
Create a product showcase for this [PRODUCT] in [BRAND] style,
clean white background, highlighting texture and material quality,
professional commercial photography, high contrast.
```

### Use Cases

| Scenario | Key Prompts |
|----------|-------------|
| Social media avatar | `square composition` `solid background` `icon style` |
| Knowledge card | `infographic` `clean layout` `target audience: ...` |
| PPT background | `whitespace composition` `matte background` `offset to [side]` |
| Character cosplay | `keep face unchanged` `realistic costume` `same pose` |
| Poster design | `movie poster level` `dramatic lighting` `large whitespace` |
| Product photo | `commercial photography` `clean background` `texture highlight` |

### File Structure

```
seedream-image/
├── SKILL.md          # Prompt structures, style vocabulary, templates
├── examples.md       # 30+ ready-to-use prompts across 8 categories
├── reference.md      # Official docs, API params, size charts, 200+ style keywords
└── marketplace.json  # Skill metadata for search indexing
```

---

<a id="中文"></a>

## 中文

### 功能特性

- **文生图提示词** — 人物写真、风景、海报、卡片等结构化提示词模板
- **图像编辑** — 风格迁移、元素增删、光影调整、妆容更换
- **角色一致性** — 跨图保持面部、发型、服装高度一致（连续分镜可用）
- **知识卡片** — 信息图、塔罗牌、蓝图、游戏技能卡、仙侠古籍等风格
- **电商产品图** — 商品展示图、试穿效果、品牌风格匹配
- **多图融合** — 最多 14 张参考图，精确控制各图元素组合
- **文字渲染** — 中英文 99%+ 准确率，引号包裹文字即可精准生成
- **风格词典** — 200+ 风格关键词，按写实摄影/动漫插画/设计商业/光影分类整理
- **API 参考** — 火山方舟完整 API 参数、尺寸速查表、Python 调用示例

### 快速安装

**Cursor / Claude Code / Cline / 其他 Agent：**

```bash
npx skills add ppdbxdawj/seedream-image-skill@seedream-image
```

**手动安装：**

```bash
git clone https://github.com/ppdbxdawj/seedream-image-skill.git
cp -r seedream-image-skill/seedream-image ~/.cursor/skills/
```

### 支持平台

| 平台 | 访问方式 | 说明 |
|------|----------|------|
| [即梦AI](https://jimeng.jianying.com/) | 网页 | 每天 20 次免费生成 |
| [火山方舟](https://console.volcengine.com/ark) | API | 企业版，4K 直出 |
| [剪映](https://www.capcut.cn/) | App | AI 绘画功能 |
| [CapCut](https://www.capcut.com/) | App | 海外版 |

### 提示词示例

**人物写真**
```
清秀亚洲青年男性，黑色宽松毛衣，坐在图书馆靠窗位置低头看书，
窗外阳光透进来打在侧脸，丁达尔光，冷色调，浅景深背景虚化，
85mm定焦，写实电影剧照风格，超高清
```

**知识卡片（游戏技能卡风格）**
```
设计一张幻想RPG游戏中的技能卡片，用文字和图像解释"[概念]"。
有游戏化的技能名称，卡片上有酷炫图标、技能描述（用游戏化语言解释概念）、
消耗的"精力值"和冷却时间。整体是暗黑奇幻风格，带有发光的魔法符文边框。
```

**电商产品图**
```
为这件[产品]创建网店展示图，风格类似于[GUCCI/PRADA/Nike]，
简洁白色背景，突出产品质感，专业商业摄影风格，高对比度。
```

### 使用场景速查

| 场景 | 关键提示词 |
|------|-----------|
| 社交头像 | `正方形构图` `纯色背景` `图标风格` |
| 知识卡片 | `信息图` `排版清晰` `目标受众：...` |
| PPT 背景 | `留白构图` `哑光背景` `主体偏[方向]` |
| 角色 Cos | `保持人脸不变` `写实质感服饰` `相同姿势` |
| 海报设计 | `电影海报级别` `戏剧光` `大面积留白` |
| 产品拍摄 | `商业摄影` `简洁背景` `突出质感` |

### 文件结构

```
seedream-image/
├── SKILL.md          # 提示词结构、风格词汇库、常用模板
├── examples.md       # 30+ 即用提示词，覆盖 8 大类场景
├── reference.md      # 官方文档、API 参数、尺寸表、200+ 风格词
└── marketplace.json  # 搜索索引元数据
```

---

## Keywords

`seedream` `即梦` `jimeng` `bytedance` `doubao` `豆包` `volcengine` `火山方舟`
`AI image generation` `AI生图` `text-to-image` `文生图` `image editing` `图生图`
`prompt engineering` `提示词` `character consistency` `角色一致性`
`knowledge card` `知识卡片` `poster design` `海报设计` `e-commerce` `电商`
`capcut` `jianying` `剪映` `AI art` `AI绘画` `creative tools`

## License

MIT

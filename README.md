# Grokbot 风格人物头像与提示词

14 张 AI 生成人物头像，附每张图片实际使用的完整提示词，以及一份可用上传照片生成同类头像的通用提示词。

## 全部头像

点击图片可查看原始 PNG；编号对应下方的完整提示词。

<table>
<tr>
<td align="center"><a href="avatars/avatar-01.png"><img src="avatars/avatar-01.png" width="180" alt="黑发与青绿连帽衫"></a><br><a href="#avatar-01">avatar-01</a><br>黑发与青绿连帽衫</td>
<td align="center"><a href="avatars/avatar-02.png"><img src="avatars/avatar-02.png" width="180" alt="栗色短发与奶油色毛衣"></a><br><a href="#avatar-02">avatar-02</a><br>栗色短发与奶油色毛衣</td>
<td align="center"><a href="avatars/avatar-03.png"><img src="avatars/avatar-03.png" width="180" alt="卷发与圆框眼镜"></a><br><a href="#avatar-03">avatar-03</a><br>卷发与圆框眼镜</td>
<td align="center"><a href="avatars/avatar-04.png"><img src="avatars/avatar-04.png" width="180" alt="银发发髻与圆框眼镜"></a><br><a href="#avatar-04">avatar-04</a><br>银发发髻与圆框眼镜</td>
</tr>
<tr>
<td align="center"><a href="avatars/avatar-05.png"><img src="avatars/avatar-05.png" width="180" alt="黑色长卷发与绿色毛衣"></a><br><a href="#avatar-05">avatar-05</a><br>黑色长卷发与绿色毛衣</td>
<td align="center"><a href="avatars/avatar-06.png"><img src="avatars/avatar-06.png" width="180" alt="铜红短发与玳瑁眼镜"></a><br><a href="#avatar-06">avatar-06</a><br>铜红短发与玳瑁眼镜</td>
<td align="center"><a href="avatars/avatar-07.png"><img src="avatars/avatar-07.png" width="180" alt="编发高髻与金色耳环"></a><br><a href="#avatar-07">avatar-07</a><br>编发高髻与金色耳环</td>
<td align="center"><a href="avatars/avatar-08.png"><img src="avatars/avatar-08.png" width="180" alt="棕发胡须与海军蓝毛衣"></a><br><a href="#avatar-08">avatar-08</a><br>棕发胡须与海军蓝毛衣</td>
</tr>
<tr>
<td align="center"><a href="avatars/avatar-09.png"><img src="avatars/avatar-09.png" width="180" alt="淡紫短发与银色耳饰"></a><br><a href="#avatar-09">avatar-09</a><br>淡紫短发与银色耳饰</td>
<td align="center"><a href="avatars/avatar-10.png"><img src="avatars/avatar-10.png" width="180" alt="光头圆框眼镜与绿色衬衫"></a><br><a href="#avatar-10">avatar-10</a><br>光头圆框眼镜与绿色衬衫</td>
<td align="center"><a href="avatars/avatar-11.png"><img src="avatars/avatar-11.png" width="180" alt="栗色卷发与浅蓝毛衣"></a><br><a href="#avatar-11">avatar-11</a><br>栗色卷发与浅蓝毛衣</td>
<td align="center"><a href="avatars/avatar-12.png"><img src="avatars/avatar-12.png" width="180" alt="银灰短发与方框眼镜"></a><br><a href="#avatar-12">avatar-12</a><br>银灰短发与方框眼镜</td>
</tr>
<tr>
<td align="center"><a href="avatars/avatar-13.png"><img src="avatars/avatar-13.png" width="180" alt="橙色针织帽与奶油色连帽衫"></a><br><a href="#avatar-13">avatar-13</a><br>橙色针织帽与奶油色连帽衫</td>
<td align="center"><a href="avatars/avatar-14.png"><img src="avatars/avatar-14.png" width="180" alt="金色马尾与青绿色毛衣"></a><br><a href="#avatar-14">avatar-14</a><br>金色马尾与青绿色毛衣</td>
</tr>
</table>

## 如何使用这些提示词

- **虚构人物生成**：使用下方某张头像的完整提示词。第 01–04 张仅使用文字；第 05–14 张还上传了 `avatar-01.png` 和 `avatar-02.png` 作为画风参考。
- **把自己的照片转换成头像**：上传目标照片，再粘贴下一节的通用提示词。想贴近本仓库效果时，可再上传一张本仓库头像，并注明“图 1 是转换对象，图 2 只参考画风”。
- 本批图片由内置 `image_gen` 工具生成。未记录可供复现的具体模型版本或随机种子，相同提示词不保证生成相同图片。照片转换通用提示词是新增模板，尚未用真人照片验证。

## 上传照片转换：通用提示词

可以。参考的 [hahwul 公开存档](https://gist.github.com/hahwul/581812ec1e4a5b43e40634b7585c5f64)本身就是通用的图片转换提示词：以用户上传的人物或角色图片为输入，保留辨识特征，再转换成胶囊眼头像。

下面是为本仓库这批柔和画风重新编写的模板，并非存档原文或逐字翻译。没有照片时，本模板不能确定要保留的人物特征。

```text
Generate one square profile avatar from the uploaded subject photo. Image 1 is the person to transform. If another image is provided, it is a style reference only. Preserve the subject’s skin tone, hair color and silhouette, glasses, headwear and recognizable facial hair. Do not borrow identity features from the style reference.

Use the same cozy illustrated finish as this gallery: an oversized rounded head, two solid black capsule eyes, no visible mouth or nose, faint blush, simplified shapes and gentle shading. Keep both eyes unobstructed. Tilt the head slightly in a close-up crop with a little clothing visible at the bottom. Use a plain charcoal background. Keep the avatar readable at small sizes. No text, branding or decorative frames. Avoid photographic facial anatomy and glossy rendering.

Create a single portrait, not a collage. If the photo contains several people, ask which person to transform. Follow any extra hairstyle or accessory instructions supplied by the user.
```

独立文件：[photo-to-avatar.txt](prompts/photo-to-avatar.txt)。上传图片后连同这段文字一起发送给支持参考图片的图像生成工具即可。

## 每张头像的实际提示词

下列文字为生成时提交的完整提示词，不是事后根据结果反推。图片可能没有完全遵循其中每项约束。

<a id="avatar-01"></a>

### avatar-01 · 黑发与青绿连帽衫

[原图](avatars/avatar-01.png) · [提示词文件](prompts/avatar-01.txt)

输入：纯文字，无参考图片。

```text
Create one square profile avatar for a local chat app. Minimal flat 2D Grokbot-inspired fictional human mascot: oversized rounded face, exactly two plain black elongated capsule eyes, no mouth or nose, subtle cheek blush. Large clean hair shapes, restrained soft shading, no outlines or text. Tilt the head clockwise slightly in a close crop, both eyes clearly visible. Solid near-black charcoal background. No logos or watermark, no celebrity likeness. Character: young adult man with short tousled black hair, warm light skin and a small teal hoodie collar.
```

<a id="avatar-02"></a>

### avatar-02 · 栗色短发与奶油色毛衣

[原图](avatars/avatar-02.png) · [提示词文件](prompts/avatar-02.txt)

输入：纯文字，无参考图片。

```text
Create one square profile avatar for a local chat app. Minimal flat 2D Grokbot-inspired fictional human mascot: oversized rounded face, exactly two plain black elongated capsule eyes, no mouth or nose, subtle cheek blush. Large clean hair shapes, restrained soft shading, no outlines or text. Tilt the head clockwise slightly in a close crop, both eyes clearly visible. Solid near-black charcoal background. No logos or watermark, no celebrity likeness. Character: young adult woman with a chestnut bob haircut, medium warm skin and a small cream sweater collar.
```

<a id="avatar-03"></a>

### avatar-03 · 卷发与圆框眼镜

[原图](avatars/avatar-03.png) · [提示词文件](prompts/avatar-03.txt)

输入：纯文字，无参考图片。

```text
Create one square profile avatar for a local chat app. Minimal flat 2D Grokbot-inspired fictional human mascot: oversized rounded face, exactly two plain black elongated capsule eyes, no mouth or nose, subtle cheek blush. Large clean hair shapes, restrained soft shading, no outlines or text. Tilt the head clockwise slightly in a close crop, both eyes clearly visible. Solid near-black charcoal background. No logos or watermark, no celebrity likeness. Character: adult man with dark brown skin, short curly hair and thin round glasses, small muted blue collar.
```

<a id="avatar-04"></a>

### avatar-04 · 银发发髻与圆框眼镜

[原图](avatars/avatar-04.png) · [提示词文件](prompts/avatar-04.txt)

输入：纯文字，无参考图片。

```text
Create one square profile avatar for a local chat app. Minimal flat 2D Grokbot-inspired fictional human mascot: oversized rounded face, exactly two plain black elongated capsule eyes, no mouth or nose, subtle cheek blush. Large clean hair shapes, restrained soft shading, no outlines or text. Tilt the head clockwise slightly in a close crop, both eyes clearly visible. Solid near-black charcoal background. No logos or watermark, no celebrity likeness. Character: adult woman with pale skin, silver hair gathered into a small bun, round glasses and a small plum collar.
```

<a id="avatar-05"></a>

### avatar-05 · 黑色长卷发与绿色毛衣

[原图](avatars/avatar-05.png) · [提示词文件](prompts/avatar-05.txt)

画风参考图：[avatar-01](avatars/avatar-01.png) 和 [avatar-02](avatars/avatar-02.png)。生成的是新人物。

```text
Create one square profile avatar for a local chat app. Minimal flat 2D Grokbot-inspired fictional human mascot: oversized rounded face, exactly two plain black elongated capsule eyes, no mouth or nose, subtle cheek blush. Large clean hair shapes, restrained soft shading, no outlines or text. Tilt the head clockwise slightly in a close crop, both eyes clearly visible. Solid near-black charcoal background. No logos or watermark, no celebrity likeness. Match the supplied reference images' softness, head scale, capsule eyes and gentle illustrated shading; create a different original person. Character: young adult woman with warm olive skin, long wavy black hair tucked behind one ear, tiny gold stud earrings and a sage green sweater collar.
```

<a id="avatar-06"></a>

### avatar-06 · 铜红短发与玳瑁眼镜

[原图](avatars/avatar-06.png) · [提示词文件](prompts/avatar-06.txt)

画风参考图：[avatar-01](avatars/avatar-01.png) 和 [avatar-02](avatars/avatar-02.png)。生成的是新人物。

```text
Create one square profile avatar for a local chat app. Minimal flat 2D Grokbot-inspired fictional human mascot: oversized rounded face, exactly two plain black elongated capsule eyes, no mouth or nose, subtle cheek blush. Large clean hair shapes, restrained soft shading, no outlines or text. Tilt the head clockwise slightly in a close crop, both eyes clearly visible. Solid near-black charcoal background. No logos or watermark, no celebrity likeness. Match the supplied reference images' softness, head scale, capsule eyes and gentle illustrated shading; create a different original person. Character: young adult man with fair freckled skin, short copper-red hair, round tortoiseshell glasses and a mustard yellow hoodie collar.
```

<a id="avatar-07"></a>

### avatar-07 · 编发高髻与金色耳环

[原图](avatars/avatar-07.png) · [提示词文件](prompts/avatar-07.txt)

画风参考图：[avatar-01](avatars/avatar-01.png) 和 [avatar-02](avatars/avatar-02.png)。生成的是新人物。

```text
Create one square profile avatar for a local chat app. Minimal flat 2D Grokbot-inspired fictional human mascot: oversized rounded face, exactly two plain black elongated capsule eyes, no mouth or nose, subtle cheek blush. Large clean hair shapes, restrained soft shading, no outlines or text. Tilt the head clockwise slightly in a close crop, both eyes clearly visible. Solid near-black charcoal background. No logos or watermark, no celebrity likeness. Match the supplied reference images' softness, head scale, capsule eyes and gentle illustrated shading; create a different original person. Character: adult woman with rich dark brown skin, thick black braids gathered into a high bun, small hoop earrings and a muted coral collar.
```

<a id="avatar-08"></a>

### avatar-08 · 棕发胡须与海军蓝毛衣

[原图](avatars/avatar-08.png) · [提示词文件](prompts/avatar-08.txt)

画风参考图：[avatar-01](avatars/avatar-01.png) 和 [avatar-02](avatars/avatar-02.png)。生成的是新人物。

```text
Create one square profile avatar for a local chat app. Minimal flat 2D Grokbot-inspired fictional human mascot: oversized rounded face, exactly two plain black elongated capsule eyes, no mouth or nose, subtle cheek blush. Large clean hair shapes, restrained soft shading, no outlines or text. Tilt the head clockwise slightly in a close crop, both eyes clearly visible. Solid near-black charcoal background. No logos or watermark, no celebrity likeness. Match the supplied reference images' softness, head scale, capsule eyes and gentle illustrated shading; create a different original person. Character: adult man with tan skin, neatly swept dark brown hair, a short simplified beard and a navy blue sweater collar. No visible mouth.
```

<a id="avatar-09"></a>

### avatar-09 · 淡紫短发与银色耳饰

[原图](avatars/avatar-09.png) · [提示词文件](prompts/avatar-09.txt)

画风参考图：[avatar-01](avatars/avatar-01.png) 和 [avatar-02](avatars/avatar-02.png)。生成的是新人物。

```text
Create one square profile avatar for a local chat app. Minimal flat 2D Grokbot-inspired fictional human mascot: oversized rounded face, exactly two plain black elongated capsule eyes, no mouth or nose, subtle cheek blush. Large clean hair shapes, restrained soft shading, no outlines or text. Tilt the head clockwise slightly in a close crop, both eyes clearly visible. Solid near-black charcoal background. No logos or watermark, no celebrity likeness. Match the supplied reference images' softness, head scale, capsule eyes and gentle illustrated shading; create a different original person. Character: young adult woman with light skin, short dusty lavender pixie hair, small silver earrings and a charcoal turtleneck collar.
```

<a id="avatar-10"></a>

### avatar-10 · 光头圆框眼镜与绿色衬衫

[原图](avatars/avatar-10.png) · [提示词文件](prompts/avatar-10.txt)

画风参考图：[avatar-01](avatars/avatar-01.png) 和 [avatar-02](avatars/avatar-02.png)。生成的是新人物。

```text
Create one square profile avatar for a local chat app. Minimal flat 2D Grokbot-inspired fictional human mascot: oversized rounded face, exactly two plain black elongated capsule eyes, no mouth or nose, subtle cheek blush. Large clean hair shapes, restrained soft shading, no outlines or text. Tilt the head clockwise slightly in a close crop, both eyes clearly visible. Solid near-black charcoal background. No logos or watermark, no celebrity likeness. Match the supplied reference images' softness, head scale, capsule eyes and gentle illustrated shading; create a different original person. Character: adult man with medium brown skin, a bald head, subtle round black glasses and a forest green shirt collar.
```

<a id="avatar-11"></a>

### avatar-11 · 栗色卷发与浅蓝毛衣

[原图](avatars/avatar-11.png) · [提示词文件](prompts/avatar-11.txt)

画风参考图：[avatar-01](avatars/avatar-01.png) 和 [avatar-02](avatars/avatar-02.png)。生成的是新人物。

```text
Create one square profile avatar for a local chat app. Minimal flat 2D Grokbot-inspired fictional human mascot: oversized rounded face, exactly two plain black elongated capsule eyes, no mouth or nose, subtle cheek blush. Large clean hair shapes, restrained soft shading, no outlines or text. Tilt the head clockwise slightly in a close crop, both eyes clearly visible. Solid near-black charcoal background. No logos or watermark, no celebrity likeness. Match the supplied reference images' softness, head scale, capsule eyes and gentle illustrated shading; create a different original person. Character: young adult woman with golden brown skin, voluminous curly chestnut hair and a pale blue sweater collar.
```

<a id="avatar-12"></a>

### avatar-12 · 银灰短发与方框眼镜

[原图](avatars/avatar-12.png) · [提示词文件](prompts/avatar-12.txt)

画风参考图：[avatar-01](avatars/avatar-01.png) 和 [avatar-02](avatars/avatar-02.png)。生成的是新人物。

```text
Create one square profile avatar for a local chat app. Minimal flat 2D Grokbot-inspired fictional human mascot: oversized rounded face, exactly two plain black elongated capsule eyes, no mouth or nose, subtle cheek blush. Large clean hair shapes, restrained soft shading, no outlines or text. Tilt the head clockwise slightly in a close crop, both eyes clearly visible. Solid near-black charcoal background. No logos or watermark, no celebrity likeness. Match the supplied reference images' softness, head scale, capsule eyes and gentle illustrated shading; create a different original person. Character: adult man with warm light skin, silver-gray side-parted hair, rectangular dark glasses and a burgundy cardigan collar.
```

<a id="avatar-13"></a>

### avatar-13 · 橙色针织帽与奶油色连帽衫

[原图](avatars/avatar-13.png) · [提示词文件](prompts/avatar-13.txt)

画风参考图：[avatar-01](avatars/avatar-01.png) 和 [avatar-02](avatars/avatar-02.png)。生成的是新人物。

```text
Create one square profile avatar for a local chat app. Minimal flat 2D Grokbot-inspired fictional human mascot: oversized rounded face, exactly two plain black elongated capsule eyes, no mouth or nose, subtle cheek blush. Large clean hair shapes, restrained soft shading, no outlines or text. Tilt the head clockwise slightly in a close crop, both eyes clearly visible. Solid near-black charcoal background. No logos or watermark, no celebrity likeness. Match the supplied reference images' softness, head scale, capsule eyes and gentle illustrated shading; create a different original person. Character: young adult man with olive skin, medium-length wavy black hair beneath a plain rust orange beanie, and a cream hoodie collar.
```

<a id="avatar-14"></a>

### avatar-14 · 金色马尾与青绿色毛衣

[原图](avatars/avatar-14.png) · [提示词文件](prompts/avatar-14.txt)

画风参考图：[avatar-01](avatars/avatar-01.png) 和 [avatar-02](avatars/avatar-02.png)。生成的是新人物。

```text
Create one square profile avatar for a local chat app. Minimal flat 2D Grokbot-inspired fictional human mascot: oversized rounded face, exactly two plain black elongated capsule eyes, no mouth or nose, subtle cheek blush. Large clean hair shapes, restrained soft shading, no outlines or text. Tilt the head clockwise slightly in a close crop, both eyes clearly visible. Solid near-black charcoal background. No logos or watermark, no celebrity likeness. Match the supplied reference images' softness, head scale, capsule eyes and gentle illustrated shading; create a different original person. Character: young adult woman with fair skin, honey-blonde hair in a loose ponytail, side-swept bangs that do not hide the eyes, and a muted teal sweater collar.
```

## 文件结构

```text
avatars/                    14 张原始 PNG
prompts/avatar-01.txt …      每张头像实际使用的完整提示词
prompts/photo-to-avatar.txt  上传照片转换的通用提示词
prompts/generation-log.txt   最初保存的生成记录
avatars.json                头像、提示词及参考图对应关系
README.md                   完整图库与说明
```

## 来源与说明

- 提示词风格线索来自 [Serio_ai 的 X 分享帖](https://x.com/Multi_Serio_Ai/status/2100800237619347535)。
- 参考阅读：[hahwul 保存的英文与韩文通用提示词](https://gist.github.com/hahwul/581812ec1e4a5b43e40634b7585c5f64)。该存档不等于本仓库实际使用的提示词。
- 本仓库图片为本次生成的虚构人物，没有使用真实人物照片。未转载作者画廊图片或将第三方原始提示词全文纳入仓库。
- 这是独立整理的头像集合，与 xAI、Grok 或参考提示词作者不存在隶属关系。

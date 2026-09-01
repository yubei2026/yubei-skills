# 动作型AI生成分镜案例：功夫厨师

## 使用范围

在单人物、单场景、强动作、强节奏或需要迁移参考运镜的短片中读取本案例。它展示的是高密度动作编排方法，不是所有题材的固定模板。

不应将本案例直接套用于双人对白、细腻情绪表演、多场景品牌故事或以旁白推动的作品。

## 原始案例

```text
SUBJECTS: Subject 1: Lean kung fu chef with short, sharp-cut hair and defined jawline. Wears a modernized Chinese chef outfit fused with martial arts attire: fitted sleeveless upper garment with mandarin collar, dark matte fabric with subtle sheen; forearms wrapped with cloth bands for grip; loose tapered pants allowing wide stances; soft-soled shoes for silent footwork. Limbs slightly exaggerated in length; wrists highly flexible, elbows explosive. Movements follow clear martial rhythm (pause → burst → lock), with grounded footwork and fast pivots.

ENVIRONMENT: Traditional Chinese open-fire stove setup; iron wok fixed on stove; reflective metal counter; blue-and-white porcelain bowl placed in foreground center. Warm overhead light combined with intense dynamic firelight; light oil smoke and visible heat distortion.

MOOD: High tension, aggressive, but controlled and precise; performance feels intentional and elegant rather than chaotic.

TIMELINE:
0:00-0:02: Extreme close-up, wide-angle POV. The chef stands on the ground behind the counter (counter always between camera and chef), steps in, compresses posture, then snaps his head up to lock eyes with camera. Both hands grip dough—he stretches it in one clean pull, folds once, then pulls again. The dough transitions from a single mass into a small number of even strands.

0:02-0:05: Cut. Slight handheld motion. The chef keeps full control of the noodle bundle in both hands, stretching and aligning the strands into clean, parallel lines through fold → align → stretch cycles. Around 8–12 thin strands extend in smooth arcs, passing close to the lens in clean, readable motion. He finishes the pull and places the aligned noodle bundle neatly onto the counter in front of him.

0:05-0:07: Move (slight recoil then stabilize). The chef lowers into a sliding step behind the counter. One palm sweeps across the surface—shrimp and greens lift and travel in a controlled arc into the wok. The wok remains on the stove; the chef grips only the handle. Any stray ingredient is clearly caught and redirected into the wok.

0:07-0:10: Continuous shot. The chef controls the wok only through handle movement and qi force—no hands enter the wok. He lifts, tilts, and snaps the wok using wrist power; ingredients rise, rotate, and fall back into the wok. His elbow strikes the stove edge—sparks burst. He compresses the wok into the flame, then reverses to pull the flame upward into a second controlled flare.

0:10-0:12: Match move tracking. The chef pivots while holding the wok handle. With the other hand, he picks up the same noodle bundle from the counter and feeds it directly into the wok in one controlled motion. He immediately resumes tossing using the wok—three clean toss cycles (fast → faster → stop). Shrimp, greens, and noodles integrate visibly; sauce coats evenly.

0:12-0:15: Cut to stabilized POV. Sudden full stop. The chef tilts the wok and slides the finished dish into the porcelain bowl—visible: evenly coated noodles, plump shrimp, glossy greens. He lifts and presents the bowl directly toward the camera until it fills the frame. A finger taps the rim—subtle vibration. Steam rises rapidly, expanding until it fully covers the lens for a clean fade-out.
```

## 为什么有效

### 1. 全局设定先于镜头

- `SUBJECTS` 同时固定外形、服装、身体能力和动作风格。
- `ENVIRONMENT` 固定场景、道具、空间布局和光线。
- `MOOD` 规定表演的力度与质感，避免动作变成混乱打闹。

### 2. 动作语法统一

`pause → burst → lock`、`fold → align → stretch`、`fast → faster → stop` 等节拍词同时说明动作顺序、速度和停止位置，使不同镜头保持统一的武术表演逻辑。

### 3. 每段都有起点、过程和终点

时间线不仅写“做什么”，还写动作如何开始、怎样变化、在哪里结束。结束状态又成为下一镜头的连续性输入，例如同一束面条、固定在炉灶上的锅和前景中的瓷碗。

### 4. 摄影机与动作同时设计

案例同时规定景别、视角、稳定程度、运镜、剪辑方式和动作路径。镜头不是孤立画面，而是为动作可读性、爽点和前后衔接服务。

### 5. 主动约束常见生成错误

“柜台始终在摄影机和厨师之间”“只握锅柄”“手不能进入锅中”“使用同一束面条”等约束用于保持空间、道具、物理动作和主体连续性。

### 6. 结尾状态兼任转场

蒸汽覆盖镜头既完成成品展示，又提供自然淡出，使叙事、视觉爽点和剪辑出口在同一动作中完成。

## 可以迁移的结构

```text
SUBJECTS
角色外形、服装、不可变化特征、动作能力和动作节奏。

ENVIRONMENT
地点、时间、空间布局、固定道具、光线和环境状态。

VISUAL STYLE
画面质感、色彩和摄影方向。

MOOD & PERFORMANCE
情绪、表演强度、动作节拍和禁止出现的状态。

CONTINUITY RULES
角色、服装、道具、方向、场景和光线连续性。

TIMELINE
时间段；镜头任务；剪辑方式；景别与视角；构图与空间关系；摄影机运动；主体初始状态；动作过程与节奏；结束状态；声音；连续性；生成约束；下一镜头接口。
```

## 使用时的限制

- 精确数量、复杂物理动作和指定动作次数不保证所有模型都能稳定执行。
- 把要求分成“必须满足、尽量满足、允许变化”，不要假设时间码和数量会被模型严格遵守。
- 当一个短镜头同时包含复杂动作、复杂运镜和多个物体交互时，优先拆镜或降低其中一个维度的复杂度。
- 迁移案例的结构和动作编排方法，不复制功夫厨师、拉面、炒锅或具体画面。


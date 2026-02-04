# Pop Mart Expo · UI/UX Design System（可直接贴 README）

> 目标场景：潮玩展 / 品牌联动 / 展会活动
> 风格关键词：年轻、潮流、模块化、泡泡玛特感

---

## 1. 信息架构（Pattern）
- **页面结构**：Hero → Features → CTA
- **CTA 位置**：首屏即展示
- **适用**：对外展示页、活动落地页、招商页

---

## 2. 视觉风格（Style）
- **风格名**：Glassmorphism（玻璃拟态）
- **关键词**：磨砂玻璃、透明层叠、柔和光源、空间深度
- **适用**：现代品牌、潮流活动、年轻化视觉
- **注意**：确保 4.5:1 对比度，避免可读性不足

---

## 3. 色彩系统（Colors）
| 角色 | 颜色 | 说明 |
|------|------|------|
| Primary | #2563EB | 主要品牌色 |
| Secondary | #3B82F6 | 辅助色 |
| CTA | #F97316 | 行动按钮色 |
| Background | #F8FAFC | 背景色 |
| Text | #1E293B | 正文字色 |

---

## 4. 字体系统（Typography）
- **标题字体**：Inter
- **正文字体**：Inter
- **基调**：专业感 + 强层级

---

## 5. 关键视觉效果（Effects）
- Backdrop blur（10–20px）
- 轻薄描边（1px rgba 白 0.2）
- 光感反射 + 层级阴影

---

## 6. 反模式（Avoid）
- 过度动画
- 默认暗色主题

---

## 7. 交付前检查（Checklist）
- [ ] 无 Emoji 图标（使用 SVG：Heroicons/Lucide）
- [ ] 所有可点击元素添加 `cursor-pointer`
- [ ] Hover 动画 150–300ms
- [ ] 文本对比度 ≥ 4.5:1
- [ ] 可见 Focus 状态（键盘导航）
- [ ] `prefers-reduced-motion` 支持
- [ ] 响应式测试：375 / 768 / 1024 / 1440

---

## 8. 快速使用指令（CLI）
```bash
python3 skills/ui-ux-pro-max-skill/src/ui-ux-pro-max/scripts/search.py "潮玩展 展会 品牌联动 年轻 潮流 泡泡玛特" --design-system -p "Pop Mart Expo"
```

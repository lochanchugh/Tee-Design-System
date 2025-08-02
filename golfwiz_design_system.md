# 🏌️ GolfWiz Complete Design System Cheat Sheet — Uber-Aligned (Light & Dark Modes)

A complete, semantic, Uber-inspired design system tailored for a **golf analysis app**. Supports **both Light and Dark modes** with **semantic tokens**, **golf-specific overlays**, and **component guidelines**.

---

## 🎨 Color System (Toggle Light/Dark)

<details>
<summary>🌗 Click to Toggle Light/Dark Mode Colors</summary>

<details>
<summary>🌞 Light Mode — Core Colors</summary>

| Token             | Value   | Usage                                 |
| ----------------- | ------- | ------------------------------------- |
| background        | #FFFFFF | Main background                       |
| onBackground      | #000000 | Text/icons on background              |
| primary           | #4D7993 | Brand actions, key buttons            |
| onPrimary         | #FFFFFF | Text/icons on primary                 |
| primaryContainer  | #CCE7F0 | Primary tinted backgrounds            |
| onPrimaryContainer| #1A4A5C | Text on primary containers            |
| secondary         | #F3F3F3 | Secondary surfaces                    |
| onSecondary       | #000000 | Text/icons on secondary               |
| tertiary          | #EDEDED | Subtle accent UI                      |
| onTertiary        | #000000 | Text/icons on tertiary                |
| surface           | #FFFFFF | Cards, sheets, elevated surfaces      |
| onSurface         | #000000 | Text/icons on surface                 |
| surfaceVariant    | #F8F8F8 | Section backgrounds                   |
| onSurfaceVariant  | #6E6E6E | Secondary text/icons                  |
| surfaceTint       | #4D7993 | Elevation tint color                  |
| inverseSurface    | #000000 | Dark surfaces (e.g., banners)         |
| onInverseSurface  | #FFFFFF | Text/icons on dark surfaces           |

</details>

<details>
<summary>🌙 Dark Mode — Core Colors</summary>

| Token            | Value   | Usage                                 |
| ---------------- | ------- | ------------------------------------- |
| background       | #121212 | Main background                       |
| onBackground     | #FFFFFF | Text/icons on background              |
| primary          | #4D7993 | Brand actions, key buttons            |
| onPrimary        | #FFFFFF | Text/icons on primary                 |
| secondary        | #1E1E1E | Secondary surfaces                    |
| onSecondary      | #FFFFFF | Text/icons on secondary               |
| tertiary         | #2C2C2C | Subtle accent UI                      |
| onTertiary       | #FFFFFF | Text/icons on tertiary                |
| surface          | #1E1E1E | Cards, sheets, elevated surfaces      |
| onSurface        | #FFFFFF | Text/icons on surface                 |
| surfaceVariant   | #2A2A2A | Section backgrounds                   |
| onSurfaceVariant | #B0B0B0 | Secondary text/icons                  |
| inverseSurface   | #FFFFFF | Light surfaces (e.g., banners)        |
| onInverseSurface | #000000 | Text/icons on light surfaces          |

</details>
</details>

---

### State Colors
| Token              | Light Value | Dark Value | Usage                   |
| ------------------ | ----------- | ---------- | ----------------------- |
| primaryHover       | #436A80     | #5A92A8    | Primary hover state     |
| primaryPressed     | #3A5B6E     | #517F92    | Primary pressed state   |
| secondaryHover     | #E6E6E6     | #2D2D2D    | Secondary hover state   |
| secondaryPressed   | #D9D9D9     | #3A3A3A    | Secondary pressed state |
| disabledBackground | #E0E0E0     | #3A3A3A    | Disabled button bg      |
| disabledText       | #A1A1A1     | #777777    | Disabled text/icons     |

### Semantic Colors
| Token     | Light Value | Dark Value | Usage                 |
| --------- | ----------- | ---------- | --------------------- |
| error     | #D93F3F     | #E57373    | Error bg              |
| onError   | #FFFFFF     | #000000    | Text/icons on error   |
| warning   | #FFB020     | #FFD180    | Warning bg            |
| onWarning | #000000     | #000000    | Text/icons on warning |
| success   | #2E7D32     | #81C784    | Success bg            |
| onSuccess | #FFFFFF     | #000000    | Text/icons on success |
| info      | #0288D1     | #4FC3F7    | Info bg               |
| onInfo    | #FFFFFF     | #000000    | Text/icons on info    |

### Overlays & Highlights
| Token     | Light Value     | Dark Value      | Usage               |
| --------- | --------------- | --------------- | ------------------- |
| scrim     | rgba(0,0,0,0.4) | rgba(0,0,0,0.6) | Modal overlay       |
| highlight | #CCE7F0         | #395A64         | Selection highlight |
| accent    | #FFD700         | #FFD54F         | Special emphasis    |
| focusRing | #4D7993         | #4D7993         | Keyboard focus ring |

### Golf-Specific Overlays
| Token         | Light Value | Dark Value | Usage                  |
| ------------- | ----------- | ---------- | ---------------------- |
| severe        | #FF4C4C     | #FF6F6F    | High severity          |
| moderate      | #FFA500     | #FFB74D    | Medium severity        |
| reference     | #00CED1     | #4DD0E1    | Reference marker       |
| backswing     | #4B9CD3     | #64B5F6    | Backswing overlay      |
| downswing     | #228B22     | #66BB6A    | Downswing overlay      |
| followThrough | #9370DB     | #B39DDB    | Follow-through overlay |
| line          | #FFD700     | #FFEB3B    | Swing path line        |
| joint         | #FF69B4     | #F48FB1    | Joint markers          |

### Opacity Guidelines
| Usage                   | Opacity | Notes                                    |
| ----------------------- | ------- | ---------------------------------------- |
| Disabled elements       | 38%     | Apply to background or text              |
| Secondary text          | 60%     | For less important information           |
| Placeholder text        | 54%     | Input field hints                        |
| Hover overlays          | 8%      | Subtle state change                      |
| Focus overlays          | 12%     | More prominent than hover                |

---

## ✍️ Typography
- Full type scale from **display-lg** (44px) to **caption** (10px)
- Clear hierarchy, consistent weights
- Includes **stat-value** and **stat-label** for golf data emphasis

| Role       | Font         | Weight  | Size | Line Height | Notes                |
| ---------- | ------------ | ------- | ---- | ----------- | -------------------- |
| display-lg | Move Display | Bold    | 44px | 52px        | Hero text, splashes  |
| h1         | Move Display | Bold    | 36px | 44px        | Main headers         |
| h2         | Move Display | Bold    | 28px | 36px        | Secondary headers    |
| h3         | Move Display | Medium  | 22px | 28px        | Section headers      |
| subtitle   | Move Text    | Medium  | 20px | 28px        | Optional header tier |
| body-lg    | Move Text    | Regular | 18px | 28px        | Paragraphs           |
| body-md    | Move Text    | Regular | 16px | 24px        | Default text         |
| body-sm    | Move Text    | Regular | 14px | 20px        | Supporting info      |
| label-md   | Move Text    | Medium  | 14px | 20px        | Buttons, tabs        |
| label-sm   | Move Text    | Medium  | 12px | 16px        | Captions             |
| caption    | Move Text    | Regular | 10px | 14px        | Fine print, metadata |
| overline   | Move Text    | Medium  | 10px | 14px        | Section identifiers  |
| stat-value | Move Display | Bold    | 24px | 32px        | Golf stats emphasis  |
| stat-label | Move Text    | Medium  | 12px | 16px        | Golf stat captions   |

---

## 📏 Spacing & Layout
- **4px baseline grid**
- Spacing tokens from `spacing-0` to `spacing-12`
- Mobile-first breakpoints from `sm` (640px) to `2xl` (1536px)

| Token       | Value |
| ----------- | ----- |
| spacing-0   | 0px   |
| spacing-1   | 4px   |
| spacing-1.5 | 6px   |
| spacing-2   | 8px   |
| spacing-3   | 12px  |
| spacing-4   | 16px  |
| spacing-5   | 20px  |
| spacing-6   | 24px  |
| spacing-7   | 28px  |
| spacing-8   | 32px  |
| spacing-10  | 40px  |
| spacing-12  | 48px  |

---

## 🔲 Shape & Corners
| Token       | Radius |
| ----------- | ------ |
| radius-xs   | 2px    |
| radius-sm   | 4px    |
| radius-md   | 8px    |
| radius-lg   | 12px   |
| radius-xl   | 16px   |
| radius-xxl  | 24px   |
| radius-pill | 999px  |

---

## 🪟 Elevation & Shadows
| Token    | Shadow                       |
| -------- | ---------------------------- |
| shadow-0 | none                         |
| shadow-1 | 0 1px 3px rgba(0,0,0,0.12)   |
| shadow-2 | 0 4px 6px rgba(0,0,0,0.16)   |
| shadow-3 | 0 8px 12px rgba(0,0,0,0.20)  |
| shadow-4 | 0 12px 18px rgba(0,0,0,0.24) |
| shadow-5 | 0 16px 24px rgba(0,0,0,0.28) |

---

## 📦 Components
- **Buttons**: Primary, Secondary, Tertiary, Ghost, Icon-only, Destructive
- **Cards**: Basic, Outlined, Elevated, Metric (golf stats)
- **Inputs**: Text, Textarea, Select, Search, Password, Slider, Stepper
- **Navigation**: Top App Bar, Bottom Navigation, Tabs
- **Feedback**: Tooltips, Snackbars, Modals
- **Data Display**: Chips, Tags, Badges, Progress indicators
- **Golf-Specific**: Swing Analysis Overlays, Leaderboard Tables, Heatmaps

---

## 🎯 Best Practices
- Always use semantic tokens
- Maintain proper contrast ratios
- Optimize for mobile readability
- Design for outdoor use (golf context)


# 🏌️ GolfWiz Complete Design System Cheat Sheet

---

## **1️⃣ Color System**

*(Semantic tokens only — no raw hex in components)*

### Core Colors

| Token             | Light Value | Dark Value | Usage                                 |
| ----------------- | ----------- | ---------- | ------------------------------------- |
| background        | #FFFFFF     | #121212    | Main background                       |
| onBackground      | #000000     | #FFFFFF    | Text/icons on background              |
| primary           | #4D7993     | #4D7993    | Brand actions, key buttons            |
| onPrimary         | #FFFFFF     | #FFFFFF    | Text/icons on primary                 |
| primaryContainer  | #CCE7F0     | #395A64    | Primary tinted backgrounds            |
| onPrimaryContainer| #1A4A5C     | #E1F5FE    | Text on primary containers            |
| secondary         | #F3F3F3     | #1E1E1E    | Secondary surfaces                    |
| onSecondary       | #000000     | #FFFFFF    | Text/icons on secondary               |
| tertiary          | #EDEDED     | #2C2C2C    | Subtle accent UI                      |
| onTertiary        | #000000     | #FFFFFF    | Text/icons on tertiary                |
| surface           | #FFFFFF     | #1E1E1E    | Cards, sheets, elevated surfaces      |
| onSurface         | #000000     | #FFFFFF    | Text/icons on surface                 |
| surfaceVariant    | #F8F8F8     | #2A2A2A    | Section backgrounds                   |
| onSurfaceVariant  | #6E6E6E     | #B0B0B0    | Secondary text/icons                  |
| surfaceTint       | #4D7993     | #4D7993    | Elevation tint color                  |
| inverseSurface    | #000000     | #FFFFFF    | Dark surfaces (e.g., banners)         |
| onInverseSurface  | #FFFFFF     | #000000    | Text/icons on dark surfaces           |

### State Colors

| Token              | Light Value | Dark Value | Usage                   |
| ------------------ | ----------- | ---------- | ----------------------- |
| primaryHover       | #436A80     | #5A92A8    | Primary hover state     |
| primaryPressed     | #3A5B6E     | #517F92    | Primary pressed state   |
| primaryFocus       | #5B8AA8     | #5B8AA8    | Primary focus state     |
| secondaryHover     | #E6E6E6     | #2D2D2D    | Secondary hover state   |
| secondaryPressed   | #D9D9D9     | #3A3A3A    | Secondary pressed state |
| secondaryFocus     | #F0F0F0     | #3D3D3D    | Secondary focus state   |
| disabledBackground | #E0E0E0     | #3A3A3A    | Disabled button bg      |
| disabledText       | #A1A1A1     | #777777    | Disabled text/icons     |
| errorHover         | #C23939     | #E57373    | Hover state for errors  |
| successHover       | #256828     | #81C784    | Hover state for success |
| infoHover          | #0270AA     | #4FC3F7    | Hover state for info    |

### Borders & Dividers

| Token   | Light Value | Dark Value | Usage      |
| ------- | ----------- | ---------- | ---------- |
| outline | #D6D6D6     | #444444    | Borders    |
| divider | #EAEAEA     | #333333    | Separators |

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


## **2️⃣ Typography**

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

**Typography Guidelines:**
- Use consistent type scale - don't create custom sizes
- Maintain proper contrast ratios (4.5:1 minimum for normal text)
- Keep line lengths between 45-75 characters for readability
- Use medium weight sparingly for emphasis, not decoration

---

## **3️⃣ Spacing & Layout**

*(4px baseline grid)*

| Token       | Value |                           |
| ----------- | ----- | ------------------------- |
| spacing-0   | 0px   | Reset margins             |
| spacing-1   | 4px   | Icon-text gap             |
| spacing-1.5 | 6px   | Micro adjustments         |
| spacing-2   | 8px   | Compact padding           |
| spacing-3   | 12px  | Small gaps                |
| spacing-4   | 16px  | Standard unit             |
| spacing-5   | 20px  | Medium gaps               |
| spacing-6   | 24px  | Section spacing           |
| spacing-7   | 28px  | Large gaps                |
| spacing-8   | 32px  | Major sections            |
| spacing-10  | 40px  | Extra large               |
| spacing-12  | 48px  | Charts, hero areas        |

### Breakpoints

| Token | Value  | Usage           |
| ----- | ------ | --------------- |
| sm    | 640px  | Large mobile    |
| md    | 768px  | Tablet portrait |
| lg    | 1024px | Tablet landscape|
| xl    | 1280px | Desktop         |
| 2xl   | 1536px | Large desktop   |

**Layout Guidelines:**
- Always use spacing tokens, never arbitrary values
- Follow 4px baseline grid religiously
- Design mobile-first, then scale up
- Maintain consistent padding within component categories

---

## **4️⃣ Shape & Corners**

| Token       | Radius | Usage                                    |
| ----------- | ------ | ---------------------------------------- |
| radius-xs   | 2px    | Subtle borders, micro interactions       |
| radius-sm   | 4px    | Chips, tags, small icons                 |
| radius-md   | 8px    | Buttons, standard cards                  |
| radius-lg   | 12px   | Modals, large cards, elevated containers |
| radius-xl   | 16px   | Drawers, banners, large overlays         |
| radius-xxl  | 24px   | Special large rounded areas              |
| radius-pill | 999px  | Full pill shape                          |

**Shape Guidelines:**
- Use radius-md (8px) as default for most interactive elements
- Reserve large radii (xl, xxl) for prominent containers
- Maintain consistency within component families

---

## **5️⃣ Elevation & Shadows**

| Token        | Shadow                       | Usage            |
| ------------ | ---------------------------- | ---------------- |
| shadow-0     | none                         | Flat elements    |
| shadow-1     | 0 1px 3px rgba(0,0,0,0.12)   | Small cards      |
| shadow-2     | 0 4px 6px rgba(0,0,0,0.16)   | Floating buttons |
| shadow-3     | 0 8px 12px rgba(0,0,0,0.20)  | Modals           |
| shadow-4     | 0 12px 18px rgba(0,0,0,0.24) | High priority    |
| shadow-5     | 0 16px 24px rgba(0,0,0,0.28) | Hero overlays    |
| shadow-inset | inset 0 2px 4px rgba(0,0,0,0.1) | Pressed states |

**Elevation Guidelines:**
- Use sparingly - too many shadows create visual chaos
- Higher elevation = higher priority in information hierarchy
- Consider performance impact on mobile devices

---

## **6️⃣ Motion & Animation**

### Duration Tokens

| Token  | Value | Each Duration Usage                      |
| ------ | ----- | ---------------------------------------- |
| fast   | 150ms | Hover effects, icon changes              |
| medium | 250ms | Button presses, tab switches             |
| slow   | 350ms | Modal appearances, major state changes   |

### Easing Curves

| Token      | Curve                         | Usage                    |
| ---------- | ----------------------------- | ------------------------ |
| standard   | cubic-bezier(0.4, 0, 0.2, 1)  | Most transitions         |
| decelerate | cubic-bezier(0, 0, 0.2, 1)    | Elements entering screen |
| accelerate | cubic-bezier(0.4, 0, 1, 1)    | Elements leaving screen  |

**Motion Guidelines:**
- Keep animations subtle and purposeful
- Use decelerate for entering elements, accelerate for exiting
- Reduce motion for users with motion sensitivity preferences

---

## **7️⃣ Iconography**

| Token   | Size  | Usage                    |
| ------- | ----- | ------------------------ |
| icon-sm | 16px  | Inline with text         |
| icon-md | 20px  | Standard buttons         |
| icon-lg | 24px  | Large buttons, headers   |
| icon-xl | 32px  | Feature icons, emphasis  |

**Icon Guidelines:**
- Maintain 1.5px stroke width for outlined icons
- Ensure 44x44px minimum touch target
- Support RTL mirroring for directional icons

---

## **8️⃣ Z-Index System**

| Token      | Value | Usage                 |
| ---------- | ----- | --------------------- |
| z-base     | 0     | Default layer         |
| z-dropdown | 1000  | Dropdowns, selects    |
| z-sticky   | 1100  | Sticky headers        |
| z-modal    | 2000  | Modals, dialogs       |
| z-popover  | 2100  | Tooltips, popovers    |
| z-toast    | 3000  | Notifications         |
| z-tooltip  | 3100  | Tooltips              |

**Z-Index Guidelines:**
- Use semantic tokens, never arbitrary values
- Leave gaps between levels for future additions
- Test stacking context in complex layouts

---

## **📦 Component Defaults Cheat Sheet**

### Buttons
- **Radius:** `radius-md` (8px)
- **Height:** 48px (44px minimum touch target)
- **Padding:** `spacing-4` horizontal
- **Elevation:** `shadow-0` default, `shadow-1` on hover
- **Variants:** Primary, Secondary, Tertiary, Ghost, Icon-only, Destructive

### Cards
- **Radius:** `radius-md` (8px) standard, `radius-lg` (12px) elevated
- **Padding:** `spacing-4`
- **Elevation:** `shadow-1` default, `shadow-2` interactive
- **Variants:** Basic, Outlined, Interactive, Elevated, Metric (golf stats)

### Inputs
- **Radius:** `radius-md` (8px)
- **Height:** 48px
- **Padding:** `spacing-3` internal
- **Focus:** 2px `focusRing` outline
- **Types:** Text, Textarea, Select, Search, Password, Slider, Stepper

### Navigation
- **Top App Bar:** No radius, `shadow-1`
- **Bottom Navigation:** `radius-lg` when floating, `shadow-2`
- **Tabs:** `radius-pill` for pill-style, `radius-md` for segmented

### Feedback
- **Tooltips:** `radius-sm`, `shadow-2`, max-width: 240px
- **Snackbars:** `radius-md`, `shadow-3`, auto-dismiss 4-6s
- **Modals:** `radius-lg` or `radius-xl`, `shadow-3`

### Data Display
- **Chips/Tags:** `radius-pill`, dismissible with X icon
- **Badges:** `radius-pill`, min-width: 20px
- **Progress:** Circular or `radius-pill` linear

### Golf-Specific Components
- **Swing Analysis Overlays:** `radius-lg` containers
- **Golf Stats Cards:** `radius-md`, `shadow-1`
- **Leaderboard Tables:** `radius-md` container, no radius on rows
- **Heatmaps:** Embedded in `radius-lg` cards

---

## **🎯 Design Guidelines & Best Practices**

### Color Usage
- **Always use semantic tokens** - never hardcode hex values
- **Test contrast ratios** - minimum 4.5:1 for normal text, 3:1 for large text
- **Consider colorblind users** - don't rely solely on color for meaning
- **Use golf-specific colors purposefully** - severe/moderate/reference should have clear meaning

### Typography
- **Establish clear hierarchy** - use consistent heading levels
- **Optimize for mobile readability** - minimum 16px for body text
- **Limit font variations** - stick to defined weights and sizes
- **Consider golf context** - stat-value/stat-label pair for numerical data

### Spacing
- **Follow the 4px grid religiously** - creates visual harmony
- **Use consistent patterns** - same padding for similar components
- **Respect touch targets** - minimum 44x44px for interactive elements
- **Create breathing room** - don't cram elements together

### Layout
- **Mobile-first approach** - design for smallest screen first
- **Use consistent breakpoints** - don't create custom breakpoints
- **Test on real devices** - simulators don't show real performance
- **Consider one-handed use** - place important actions within thumb reach

### Motion
- **Keep it subtle** - animations should enhance, not distract
- **Respect user preferences** - honor reduced-motion settings
- **Use appropriate duration** - fast for micro-interactions, slow for major changes
- **Maintain consistency** - use same timing for similar interactions

### Accessibility
- **Provide focus indicators** - visible for keyboard navigation
- **Use semantic HTML** - proper heading structure, alt text, labels
- **Test with screen readers** - ensure content is understandable
- **Support keyboard navigation** - all interactive elements accessible via keyboard

### Golf App Specific
- **Prioritize data clarity** - golf stats need to be quickly scannable
- **Use consistent swing analysis colors** - backswing, downswing, follow-through
- **Design for outdoor use** - consider screen brightness and glare
- **Optimize for quick interactions** - golfers need fast access to data

---

*Remember: This design system is a living document. Update tokens consistently across all platforms and maintain documentation as the system evolves.*

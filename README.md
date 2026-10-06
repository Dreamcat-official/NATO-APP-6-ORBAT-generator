# \# Tactical ORBAT Builder (战术编制图生成器)

# 

# A lightweight, zero-dependency, browser-based military Order of Battle (ORBAT) chart generator compliant with \*\*NATO APP-6\*\* and modern tactical symbology standards.

# 

# 一款轻量、零外部依赖、纯前端单文件的现代化北约 APP-6 标准战术军队编制图快捷生成器。

# 

# \---

# 

# \## 🌟 Key Features (核心特性)

# 

# \- \*\*Pure Vector Symbology (严格标定的纯矢量军标)\*\*:

# &#x20; - 100% native SVG geometric rendering without image assets or bloated libraries.

# &#x20; - Over 50+ branch symbols across Infantry, Armour, Artillery, Fires \& Missiles, Air Defence, Engineers, Aviation, Combat Support, Sustainment, and Special Operations (SOF).

# &#x20; - Geometrically accurate modifiers: anti-tank open chevrons, suspended engineer bridges, gothic-arch pointed missiles, authentic airborne gull-wings, symmetrical amphibious waves, and towed axles.

# \- \*\*Battle-Tested Layout Engine (专业编制树拓扑引擎)\*\*:

# &#x20; - Supports classic Brigade/Division multi-column waterfall cascades (多列垂直瀑布流).

# &#x20; - Native support for \*\*Straight Vertical Bus Lines\*\* (左侧直通垂直母线) with clean horizontal branches, eliminating messy stepped S-curves.

# &#x20; - Supports trunk side-attachments (HQ staff / Command post) and dedicated rightmost brigade-direct support spines (一溜顺下的直属勤务列).

# &#x20; - Echelon breathing gaps: connector lines never collide with or obscure rank/echelon markers.

# \- \*\*Responsive Dual-Mode Interface (全端响应式界面)\*\*:

# &#x20; - \*\*Desktop (桌面端 / 宽屏)\*\*: Standard 3-column studio layout (Left: Topology \& Spacing Sliders | Center: Infinite Canvas | Right: Node Inspector).

# &#x20; - \*\*Mobile (手机端 / 竖屏)\*\*: Automatic vertical split layout (Upper: Touch-friendly Canvas | Lower: Context-switching bottom drawer for editing).

# &#x20; - \*\*iPadOS / Tablet PWA\*\*: Fullscreen web app ready via "Add to Home Screen".

# \- \*\*Zero Dependencies \& Offline First (零依赖与本地持久化)\*\*:

# &#x20; - Single-file standalone HTML/JS architecture.

# &#x20; - Zero build step, zero npm packages, zero external CDNs required.

# &#x20; - Works 100% offline in privacy-sensitive environments.

# \- \*\*Export \& Theming (多格式导出与夜战模式)\*\*:

# &#x20; - Export lossless vector `.svg`, high-resolution 2x `.png`, and portable `.json` project files.

# &#x20; - Tactical Dark / Light mode with automatic line contrast inversion and anti-glare fill protection.

# 

# \---

# 

# \## 🚀 Quick Start (快速开始)

# 

# \### 1. Run Locally (本地运行)

# Simply download `index.html` and double-click to open it in any modern browser (Chrome, Edge, Safari, Firefox).

# 

# Or launch a lightweight local server:

# ```bash

# \# Python 3

# python -m http.server 8000

# ```

# Then visit `http://localhost:8000` in your browser.

# 

# \### 2. Free Cloud Deployment (免费云端部署)

# Deploy in seconds via \*\*GitHub Pages\*\* or \*\*Vercel\*\*:

# \- \*\*GitHub Pages\*\*: Go to `Settings` -> `Pages` -> choose `main` branch -> Save.

# \- \*\*Vercel / Netlify\*\*: Drag and drop `index.html` into the dashboard to get an instant HTTPS URL.

# 

# \### 3. Install on iPad / iPhone (在 iPad / iOS 上安装)

# 1\. Open your deployed URL in Safari.

# 2\. Tap the \*\*Share\*\* button (分享).

# 3\. Select \*\*"Add to Home Screen"\*\* (添加到主屏幕).

# 4\. Launch from your home screen as a standalone fullscreen iPad app.

# 

# \---

# 

# \## 🧭 Layout Topologies Supported (支持的编制拓扑)

# 

# | Topology Type (拓扑类型) | Description (说明) |

# | :--- | :--- |

# | \*\*Combined Arms Brigade (合成机甲旅)\*\* | Top Brigade HQ $\\to$ Trunk side HQ $\\to$ Crossbar branching into Armor, Mech Inf, Artillery, and Direct Support columns. |

# | \*\*Air Assault BTG (空突营级战斗群)\*\* | Central trunk with left/right direct attachments (HQ / CSS) and lower company crossbar. |

# | \*\*Corps Multi-Division (集团军防区)\*\* | Top Army Corps command $\\to$ Multiple division columns cascading down via clean left-bus lines. |

# 

# \---

# 

# 

# \## 🛠️ Tech Stack (技术栈)

# 

# \- \*\*Markup \& Layout\*\*: HTML5, Semantic CSS Grid \& Flexbox

# \- \*\*Graphics Engine\*\*: W3C Scalable Vector Graphics (SVG 1.1)

# \- \*\*Scripting\*\*: Vanilla ES6+ JavaScript (DOM APIs, Canvas API, Blob Export)

# \- \*\*Standards\*\*: NATO Standardization Agreement (STANAG) APP-6 / US MIL-STD-2525

# 

# \---

# 

# \## 📄 License (开源协议)

# 

# This project is licensed under the \*\*MIT License\*\* - see the \[LICENSE](LICENSE) file for details. Free for academic, educational, OSINT research, and personal use.


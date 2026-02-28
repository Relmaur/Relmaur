```php
<?php

/**
 * WordPress specialist with full-stack PHP experience.
 * Building systems teams enjoy working with—
 * fast, maintainable, and built to last.
 */

declare(strict_types=1);

namespace MarcoAntonioLizardoDelRiego;

use Enums\{Architecture, Stack};

readonly class WebDeveloper
{
    public function __construct(
        /** What I optimize for */
        public string $focus = 'Beautiful Design + Bulletproof Engineering',
        /** Primary ecosystems I work in */
        public array $stack = [
            Stack::WORDPRESS => [
                'Native-first Development',
                'Modern Build Tools &amp; Workflows',
                'Custom Plugin &amp; Theme Development',
            ],
            Stack::PHP => [
                'Modern PHP Workflows',
                'Component-based Architecture',
                'Rapid Prototyping & MVPs',
            ],
            Stack::CORE => [
                'Robust, Scalable Systems',
                'Clean, Maintainable Code',
                'Performance-first Patterns',
            ],
        ],
    ) {}

    /** If you ask me... */
    public function philosophy(): string
    {
        return 'Frameworks work; well-designed systems make them invisible.';
    }
}

```

---

### 🏗 The Infrastructure

| **The Design System**    | **The Bridge (Build Tools)** | **The Frameworks**   |
| :----------------------- | :--------------------------- | :------------------- |
| **Tailwind CSS / SCSS**  | **Vite / HMR**               | **Native Gutenberg** |
| Atomic Design Principles | Hot Module Replacement       | React (Block Editor) |
| Fluid Typography         | Custom PHP Asset Loaders     | Laravel (TALL Stack) |
| _Pixel Perfection_       | _Sub-Second Load Times_      | _Headless Ready_     |

---

### 📐 Featured

#### 1. [TAW Theme — Block Architecture for WordPress](https://github.com/Relmaur/taw)

A modern WordPress theme framework that replaces page builders and field plugins with a convention-driven block system — zero config, zero bloat.

- **The Architecture:** A dual-block system — **MetaBlocks** own their data (metaboxes + post_meta), **Blocks** handle presentation (props). Auto-discovered by folder convention; drop a class in, it's live.
- **The Framework:** A bespoke metabox engine built from scratch — config arrays generate complete admin UIs with validation, conditional logic, repeaters, tabs, and a dozen field types. No ACF. No plugins.
- **The Pipeline:** Vite 7 with critical CSS inlining, async stylesheet loading, scoped per-block assets, and self-hosted font preloading — targeting 90+ Lighthouse scores out of the box.
- **The DX:** hips with a Symfony Console CLI (php bin/taw make:block Hero --type=meta) and AI-native documentation (AGENTS.md, CLAUDE.md, Copilot instructions) so both humans and AI agents understand the codebase immediately.
- **Tech:** PHP 8, Tailwind CSS v4, Alpine.js, Vite 7, Symfony Console, WordPress REST API.

#### 2. [Custom PHP framework](https://github.com/Relmaur/ml-cms)

A simple PHP framework for classic/OG web apps.

- **The Goal:** Exploration and experimentation of the foundational principles, and architecture of modern PHP frameworks.

#### 3. [Vanilla JS State Patterns](https://github.com/Relmaur/vanilla-js-state-patterns)

To better understand modern reactivity, I built a state management system using pure JavaScript and the Observer Pattern.

The Code: Uses ES6 Classes and OOP principles to manage complex game state without external libraries.

I write logic, not just glue plugins together.

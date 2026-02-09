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

#### 1. [The "Rigid Hybrid" Engine](https://github.com/Relmaur/ml-theme--custom-gutenberg)

A custom WordPress framework engineered to bridge **React-based editing** with **PHP-based rendering**.

- **The "Bridge":** I wrote a custom `vite-enqueue.php` handler that connects WordPress directly to a Vite dev server, enabling instant Hot Module Replacement (HMR) for PHP and SCSS changes.
- **The Strategy:** Uses "Native Dynamic Blocks" (`block.json`) to lock down design constraints (`theme.json`) while allowing content flexibility.
- **Tech:** PHP 8, React, Vite, PostCSS.

#### 2. [Custom PHP framework](https://github.com/Relmaur/ml-cms)

A simple PHP framework for classic/OG web apps.

- **The Goal:** Exploration and experimentation of the foundational principles, and architecture of modern PHP frameworks.

#### 3. [Vanilla JS State Patterns](https://github.com/Relmaur/vanilla-js-state-patterns)

To better understand modern reactivity, I built a state management system using pure JavaScript and the Observer Pattern.

The Code: Uses ES6 Classes and OOP principles to manage complex game state without external libraries.

I write logic, not just glue plugins together.

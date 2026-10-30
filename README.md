<div align="center">

# Playwright Web Tester (`playwright-web-tester`)

**Automated End-to-End Browser Testing, Visual Regression & Cross-Device QA**  
*The Deterministic Web Verification & Quality Assurance Standard for AI Coding Agents.*

[![Version](https://img.shields.io/badge/version-1.0.0-18181B.svg?style=flat-square&labelColor=09090B)](https://github.com/Skill-AI-private/playwright-web-tester)
[![Playwright](https://img.shields.io/badge/Playwright-Automated%20QA-18181B.svg?style=flat-square&labelColor=09090B)](https://playwright.dev)
[![WCAG AA](https://img.shields.io/badge/Accessibility-WCAG%20AA-18181B.svg?style=flat-square&labelColor=09090B)](https://w3.org/WAI)
[![Harnesses](https://img.shields.io/badge/compatibility-Antigravity%20|%20Claude%20Code%20|%20Cursor%20|%20Copilot-18181B.svg?style=flat-square&labelColor=09090B)](https://github.com/Skill-AI-private/playwright-web-tester)
[![License](https://img.shields.io/badge/license-MIT-18181B.svg?style=flat-square&labelColor=09090B)](LICENSE)

<br/>

```text
==========================================================================================
                  PLAYWRIGHT WEB TESTER ARCHITECTURE MATRIX
==========================================================================================

  [01] RESILIENT USER-CENTRIC LOCATORS
       +-- Accessible role and label targeting (getByRole, getByLabel, getByPlaceholder)
       +-- Elimination of fragile generated CSS selector paths and brittle XPath queries
       +-- Explicit test fixtures and authentication state persistence (storageState)

  [02] AUTO-RETRYING WEB ASSERTIONS
       +-- Deterministic DOM validation with toBeVisible(), toHaveText(), and toHaveURL()
       +-- Strict ban on arbitrary hardcoded sleep timers (page.waitForTimeout)
       +-- Clean network boundary assertions waiting on actual API responses

  [03] VISUAL REGRESSION & MULTI-DEVICE EMULATION
       +-- Pixel-level layout shift detection using toHaveScreenshot() snapshot comparisons
       +-- Cross-device viewport testing across Desktop Chrome, Mobile Safari, and Android
       +-- Automated accessibility compliance verification with @axe-core/playwright
==========================================================================================
```

</div>

---

## Technical Specifications

`playwright-web-tester` enforces automated, deterministic verification across web applications prior to marking tasks complete. It eliminates manual browser testing and catches visual and functional regressions before deployment.

### Core Disciplines

* **User-First Locators:** Mandates semantic locator selection matching human interaction patterns, preventing test breakage from cosmetic DOM refactors.
* **Auto-Waiting Assertions:** Prohibits arbitrary time delays. Tests synchronize exclusively with live DOM states and network idle conditions.
* **Cross-Viewport Parity:** Tests critical conversion and interaction flows across both desktop and mobile form factors.

---

## Installation

### Windows (PowerShell)
```powershell
git clone https://github.com/Skill-AI-private/playwright-web-tester.git "$HOME\.gemini\config\skills\playwright-web-tester"
```

### macOS & Linux (Bash)
```bash
git clone https://github.com/Skill-AI-private/playwright-web-tester.git ~/.gemini/config/skills/playwright-web-tester
```

---

## Directory Structure

```text
playwright-web-tester/
|-- SKILL.md                                           # Core QA & Testing Automation Rules
|-- README.md                                          # Technical specification
`-- references/                                        # Progressive disclosure playbooks
    |-- 01-playwright-e2e-suite-setup.md               # Test scenario setup & locator best practices
    |-- 02-visual-regression-and-screenshot-testing.md # Visual snapshots & layout diff checks
    `-- 03-mobile-responsiveness-and-accessibility-audits.md # Device viewports & axe-core scans
```

---

<div align="center">

*Engineered for autonomous software agents within the Skill-AI-private suite.*

</div>

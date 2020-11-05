# Typography
This extension tries to help with common text patterns with the correct typographic character. Under the hood all rules are input rules.

## Installation
```bash
# with npm
npm install @tiptap/typography

# with Yarn
yarn add @tiptap/typography
```

## Rules
| Name             | Description                                            |
| ---------------- | ------------------------------------------------------ |
| emDash           | Converts double dashes `--` to an emdash `—`.          |
| ellipsis         | Converts three dots `...` to an ellipsis character `…` |
| openDoubleQuote  | `“`Smart” opening double quotes.                       |
| closeDoubleQuote | “Smart`”` closing double quotes.                       |
| openSingleQuote  | `‘`Smart’ opening single quotes.                       |
| closeSingleQuote | ‘Smart`’` closing single quotes.                       |
| leftwardsArrow   | Converts <code><&dash;</code> to an arrow `←`.         |
| leftwardsArrow   | Converts <code>&dash;></code> to an arrow `→`.         |

## Source code
[packages/typography/](https://github.com/ueberdosis/tiptap-next/blob/main/packages/typography/)

## Usage
<demo name="Extensions/Typography" highlight="12,31" />
# AriaButton - Fixed Version

## Overview
This component adds proper ARIA labels for accessibility.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| onClick | function | - | Click handler |
| children | node | - | Button content |
| ariaLabel | string | children | ARIA label |
| className | string | '' | Additional CSS classes |

## Usage
```jsx
import AriaButton from './AriaButton';

<AriaButton onClick={() => {}} ariaLabel="Close">
  Close
</AriaButton>

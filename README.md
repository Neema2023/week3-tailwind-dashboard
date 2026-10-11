## How I Customized Tailwind

I customized Tailwind CSS to create a consistent and responsive shop admin dashboard. In my `src/style.css` file, I imported Tailwind CSS using `@import "tailwindcss";`. I customized the theme using the `@theme` directive by adding a custom brand color palette and choosing the Inter font to make the dashboard look clean and professional.

I also created reusable component classes inside `@layer components` using `@apply`. These classes combine multiple Tailwind utility classes into reusable styles for buttons, cards, and status badges. This reduces repeated code and helps maintain a consistent design throughout the dashboard.

To make the dashboard responsive, I used Tailwind utility classes such as `grid-cols-1`, `md:grid-cols-2`, and `xl:grid-cols-4`. I also used hover, focus, and transition utilities to improve the user experience on interactive elements. Finally, I tested the layout at mobile width (375px) and desktop width (1440px).
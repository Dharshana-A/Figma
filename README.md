# Ex09 Event Registration Web Application
## Date:19/12/25

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
index.
import React from "react";
import bgCar1 from "./bg-car-1.png";

export const IphoneProMax = (): JSX.Element => {
  return (
    <main className="bg-[#645d5d] w-full min-w-[225px] min-h-[553px] relative">
      <img
        className="absolute top-0 left-0 w-[225px] h-[553px] aspect-[0.56] object-cover"
        alt="Background image showing car engineering and innovation"
        src={bgCar1}
      />

      <p className="absolute top-[84px] left-[49px] w-[161px] [font-family:'Gudea-Regular',Helvetica] font-normal text-white text-base tracking-[0] leading-[normal]">
        DRIVEN BY INNOVATION,POWERED BY ENGNEERING
      </p>

      <div className="absolute top-[209px] left-[61px] w-[120px] h-[18px] bg-[linear-gradient(90deg,rgba(197,197,197,1)_0%)] opacity-50" />

      <button
        className="absolute top-[209px] left-[77px] w-[133px] [font-family:'Irish_Grover-Regular',Helvetica] font-normal text-[#e1e0e0] text-sm tracking-[0] leading-[normal] cursor-pointer hover:opacity-80 transition-opacity"
        aria-label="Get on board"
      >
        GET ON BOARD
      </button>
    </main>
  );
};
tailwind
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{html,js,ts,jsx,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
};
tailwind.css
@tailwind base;
@tailwind components;
@tailwind utilities;

@layer base {
  button,
  input,
  select,
  textarea {
    @apply appearance-none bg-transparent border-0 outline-none;
  }
}

@tailwind components;
@tailwind utilities;

@layer components {
  .all-\[unset\] {
    all: unset;
  }
}

:root {
  --animate-spin: spin 1s linear infinite;
}

.animate-fade-in {
  animation: fade-in 1s var(--animation-delay, 0s) ease forwards;
}

.animate-fade-up {
  animation: fade-up 1s var(--animation-delay, 0s) ease forwards;
}

.animate-marquee {
  animation: marquee var(--duration) infinite linear;
}

.animate-marquee-vertical {
  animation: marquee-vertical var(--duration) linear infinite;
}

.animate-shimmer {
  animation: shimmer 8s infinite;
}

.animate-spin {
  animation: var(--animate-spin);
}

@keyframes spin {
  to {
    transform: rotate(1turn);
  }
}

@keyframes image-glow {
  0% {
    opacity: 0;
    animation-timing-function: cubic-bezier(0.74, 0.25, 0.76, 1);
  }

  10% {
    opacity: 0.7;
    animation-timing-function: cubic-bezier(0.12, 0.01, 0.08, 0.99);
  }

  to {
    opacity: 0.4;
  }
}

@keyframes fade-in {
  0% {
    opacity: 0;
    transform: translateY(-10px);
  }

  to {
    opacity: 1;
    transform: none;
  }
}

@keyframes fade-up {
  0% {
    opacity: 0;
    transform: translateY(20px);
  }

  to {
    opacity: 1;
    transform: none;
  }
}

@keyframes shimmer {
  0%,
  90%,
  to {
    background-position: calc(-100% - var(--shimmer-width)) 0;
  }

  30%,
  60% {
    background-position: calc(100% + var(--shimmer-width)) 0;
  }
}

@keyframes marquee {
  0% {
    transform: translate(0);
  }

  to {
    transform: translateX(calc(-100% - var(--gap)));
  }
}

@keyframes marquee-vertical {
  0% {
    transform: translateY(0);
  }

  to {
    transform: translateY(calc(-100% - var(--gap)));
  }
}
```

## OUTPUT:
![alt text](<Screenshot 2025-12-19 213833.png>)
## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.

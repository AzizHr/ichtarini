<script setup></script>

<template>
  <div
    class="flex flex-col md:flex-row bg-white dark:bg-card rounded-lg shadow-lg p-7"
  >
    <div class="flex-shrink-0">
      <img
        src="https://placehold.co/300x400/FF6347?text=Red%20Apple"
        alt="Red Apple"
        class="rounded-lg"
      />
      <div class="flex space-x-2 mt-7">
        <img
          src="https://placehold.co/50x50/FF6347?text=Color%201"
          alt="Color 1"
          class="w-12 h-12 rounded-lg border border-zinc-300"
        />
        <img
          src="https://placehold.co/50x50/FF6347?text=Color%202"
          alt="Color 2"
          class="w-12 h-12 rounded-lg border border-zinc-300"
        />
        <img
          src="https://placehold.co/50x50/FF6347?text=Color%203"
          alt="Color 3"
          class="w-12 h-12 rounded-lg border border-zinc-300"
        />
      </div>
    </div>
    <div class="mt-7 md:mt-0 md:ml-7 flex-grow">
      <h2 class="text-xl font-bold">Red Apple</h2>
      <p class="text-zinc-500">Fruits / Apple</p>
      <p class="text-lg font-semibold mt-7">
        <span class="line-through text-zinc-400">$129.00</span>
        <span class="text-red-600">$122.00</span>
        <span class="text-green-500 text-sm"> (5% off)</span>
      </p>
      <div class="flex items-center mt-7">
        <span class="text-yellow-500">★★★★☆</span>
        <span class="text-zinc-500 ml-7">(4.9) 1.2k reviews</span>
      </div>
      <p class="mt-7 text-zinc-700">
        Introducing our Red Apple, perfect as a healthy snack or a delicious
        addition to your recipes. Our apples are hand-picked to ensure energy
        and quality. Packed with essential nutrients and a sweet crispy flavor,
        the Red Apple is a favorite for all ages. Enjoy it as a quick snack, in
        salads, or as a tasty ingredient in your favorite dishes.
      </p>
      <div class="mt-7">
        <h3 class="font-semibold">Available Colors</h3>
        <div class="flex space-x-2 mt-7">
          <button class="w-8 h-8 bg-blue-600 rounded-full"></button>
          <button class="w-8 h-8 bg-green-600 rounded-full"></button>
          <button class="w-8 h-8 bg-black rounded-full"></button>
        </div>
      </div>
      <div class="mt-7 md:flex md:space-x-7">
        <div class="md:w-1/2">
          <h3 class="font-semibold">Size</h3>
          <div class="flex flex-wrap mt-7">
            <button class="w-12 h-12 bg-zinc-300 rounded-lg mr-7 mb-7">
              S
            </button>
            <button class="w-12 h-12 bg-zinc-300 rounded-lg mr-7 mb-7">
              M
            </button>
            <button class="w-12 h-12 bg-zinc-300 rounded-lg mr-7 mb-7">
              Large
            </button>
            <button class="w-12 h-12 bg-zinc-300 rounded-lg mr-7 mb-7">
              Extra Large
            </button>
          </div>
        </div>
      </div>
      <div class="mt-7 md:flex md:space-x-7">
        <button
          class="bg-secondary text-secondary-foreground hover:bg-secondary/80 px-7 py-7 rounded"
        >
          Add to Cart
        </button>
        <button
          class="bg-primary text-primary-foreground hover:bg-primary/80 px-7 py-7 rounded"
        >
          Buy Now
        </button>
      </div>
    </div>
  </div>
</template>

<script src="https://cdn.tailwindcss.com?plugins=forms,typography"></script>
<script
  src="https://unpkg.com/unlazy@0.11.3/dist/unlazy.with-hashing.iife.js"
  defer
  init
></script>
<script type="text/javascript">
window.tailwind.config = {
  darkMode: ["class"],
  theme: {
    extend: {
      colors: {
        border: "hsl(var(--border))",
        input: "hsl(var(--input))",
        ring: "hsl(var(--ring))",
        background: "hsl(var(--background))",
        foreground: "hsl(var(--foreground))",
        primary: {
          DEFAULT: "hsl(var(--primary))",
          foreground: "hsl(var(--primary-foreground))",
        },
        secondary: {
          DEFAULT: "hsl(var(--secondary))",
          foreground: "hsl(var(--secondary-foreground))",
        },
        destructive: {
          DEFAULT: "hsl(var(--destructive))",
          foreground: "hsl(var(--destructive-foreground))",
        },
        muted: {
          DEFAULT: "hsl(var(--muted))",
          foreground: "hsl(var(--muted-foreground))",
        },
        accent: {
          DEFAULT: "hsl(var(--accent))",
          foreground: "hsl(var(--accent-foreground))",
        },
        popover: {
          DEFAULT: "hsl(var(--popover))",
          foreground: "hsl(var(--popover-foreground))",
        },
        card: {
          DEFAULT: "hsl(var(--card))",
          foreground: "hsl(var(--card-foreground))",
        },
      },
    },
  },
};
</script>
<style type="text/tailwindcss">
			@layer base {
				:root {
					--background: 0 0% 100%;
--foreground: 240 10% 3.9%;
--card: 0 0% 100%;
--card-foreground: 240 10% 3.9%;
--popover: 0 0% 100%;
--popover-foreground: 240 10% 3.9%;
--primary: 240 5.9% 10%;
--primary-foreground: 0 0% 98%;
--secondary: 240 4.8% 95.9%;
--secondary-foreground: 240 5.9% 10%;
--muted: 240 4.8% 95.9%;
--muted-foreground: 240 3.8% 46.1%;
--accent: 240 4.8% 95.9%;
--accent-foreground: 240 5.9% 10%;
--destructive: 0 84.2% 60.2%;
--destructive-foreground: 0 0% 98%;
--border: 240 5.9% 90%;
--input: 240 5.9% 90%;
--ring: 240 5.9% 10%;
--radius: 0.5rem;
				}
				.dark {
					--background: 240 10% 3.9%;
--foreground: 0 0% 98%;
--card: 240 10% 3.9%;
--card-foreground: 0 0% 98%;
--popover: 240 10% 3.9%;
--popover-foreground: 0 0% 98%;
--primary: 0 0% 98%;
--primary-foreground: 240 5.9% 10%;
--secondary: 240 3.7% 15.9%;
--secondary-foreground: 0 0% 98%;
--muted: 240 3.7% 15.9%;
--muted-foreground: 240 5% 64.9%;
--accent: 240 3.7% 15.9%;
--accent-foreground: 0 0% 98%;
--destructive: 0 62.8% 30.6%;
--destructive-foreground: 0 0% 98%;
--border: 240 3.7% 15.9%;
--input: 240 3.7% 15.9%;
--ring: 240 4.9% 83.9%;
				}
			}
</style>

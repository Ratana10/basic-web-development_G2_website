💡 How it works
	•	relative → lets you position a pseudo-element inside each <a>
	•	after:* → Tailwind’s pseudo-element syntax for ::after
	•	after:h-[2px] → creates a 2px underline bar
	•	after:w-0 hover:after:w-full → width animation when hovered
	•	after:transition-all after:duration-300 → smooth animation
	•	after:bg-green-400 → underline color (you can change this)


header

fixed
Keeps header always visible even when scrolling
top-0 left-0 right-0
Pins it to the top across full width
bg-[#111]
Dark background (you can change it)
z-50
Keeps header above all content
shadow-lg
Adds subtle shadow for floating look
pt-24 on <main>
Adds top padding so content isn’t hidden behind the fixed header

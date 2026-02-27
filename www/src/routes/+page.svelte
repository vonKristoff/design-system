<section class="hero gap-y-8">
	<h1 class="text-center font-mono font-light uppercase">Design System</h1>
	<div class="grid w-screen grid-cols-9">
		<div class="hue-card justify-center">
			<div class="hue-block bg-black"></div>
			<p class="font-mono">black</p>
		</div>
		<div class="hue-card">
			<div class="hue-block bg-zero-100"></div>
			<div class="hue-block bg-zero-200"></div>
			<div class="hue-block bg-zero-300"></div>
			<p class="font-mono">zero</p>
		</div>
		<div class="hue-card">
			<div class="hue-block bg-one-100"></div>
			<div class="hue-block bg-one-200"></div>
			<div class="hue-block bg-one-300"></div>
			<p class="font-mono">one</p>
		</div>

		<div class="hue-card">
			<div class="hue-block bg-neutral-100"></div>
			<div class="hue-block bg-neutral-200"></div>
			<div class="hue-block bg-neutral-300"></div>
			<p class="font-mono">neutral</p>
		</div>
		<div class="hue-card">
			<div class="hue-block bg-wash-100"></div>
			<div class="hue-block bg-wash-200"></div>
			<div class="hue-block bg-wash-300"></div>
			<code>wash</code>
		</div>
		<div class="hue-card">
			<div class="hue-block bg-twist-100"></div>
			<div class="hue-block bg-twist-200"></div>
			<div class="hue-block bg-twist-300"></div>
			<code>twist</code>
		</div>

		<div class="hue-card">
			<div class="hue-block bg-pop-100"></div>
			<div class="hue-block bg-pop-200"></div>
			<div class="hue-block bg-pop-300"></div>
			<code>pop</code>
		</div>
		<div class="hue-card">
			<div class="hue-block bg-accent-100"></div>
			<div class="hue-block bg-accent-200"></div>
			<div class="hue-block bg-accent-300"></div>
			<code>accent</code>
		</div>

		<div class="hue-card justify-center">
			<div class="hue-block bg-white"></div>
			<code>white</code>
		</div>
	</div>
	<div class="grid grid-cols-9 gap-0">
		<div class="col-span-1 col-start-1 flex"></div>
		<div class="relative col-span-2 col-start-2 flex grow justify-center">
			<div class="signal rounded-2xl border-2"></div>
			<h2>base</h2>
		</div>
		<div class="relative col-span-3 col-start-4 flex justify-center">
			<div class="signal rounded-2xl border-2"></div>
			<h2>mid</h2>
		</div>
		<div class="relative col-span-2 col-start-7 flex justify-center">
			<div class="signal rounded-2xl border-2"></div>
			<h2>top</h2>
		</div>
		<div class="col-span-1 col-start-8 flex"></div>
	</div>
</section>

<section data-bg="zero" class="hero">
	<div class="flex max-w-md flex-col gap-8">
		<header>
			<h2>[zero] bg uses [one] text colour and vice versa</h2>
			<div class="mb-4 rounded-lg border-2 p-4">
				<span>Current colour persists</span>
			</div>
		</header>
		<blockquote>
			<p>
				"[accent] will hit me with a <strong>sentence</strong> and some
				<span class="highlight">strange</span>
				targeted highlighting"
			</p>
		</blockquote>
		<p>
			Lorem Ipsum is <a class="inlinelink inlinelink--light" href="link">simply dummy</a> text of the
			printing and typesetting industry.
		</p>
		<div class="flex justify-between">
			<button class="solid text-zero-200">Solid Press</button>
			<button class="bg-black">Outline Submit</button>
		</div>
	</div>
</section>
<section data-bg="one" class="hero">
	<div class="flex flex-col items-center gap-8">
		<header class="max-w-2xl">
			<h1>[one] bg uses [zero] text colour</h1>
			<div class="mb-4 rounded-lg border-2 p-4">
				<span
					><span class="font-primar font-bold">Header</span> tags are font-header, and rest is
					<strong>font-paragraph</strong>, unless
					<span class="font-mono">font-mono</span></span
				>
			</div>
		</header>
		<article class="flex max-w-md flex-col gap-4">
			<blockquote>
				<p>
					hit me with a <strong>sentence</strong> and some <span class="highlight">strange</span>
					pointless highlighting
				</p>
			</blockquote>
			<p>
				Inline links <a class="inlinelink inlinelink--dark" href="link">simply dummy</a> with adaptive
				inlinelink--dark or light available.
			</p>
			<div class="flex justify-between">
				<button class="solid">Solid Press</button>
				<button>Outline Submit</button>
			</div>
		</article>
	</div>
</section>
<section data-bg="zero" class="hero gap-y-12 px-12">
	<h1 class="text-center">Column cards using mids</h1>
	<div class="grid grid-cols-3 gap-12 [&_p]:px-8">
		<div class="hue-card subgrid justify-center bg-neutral-100 py-8">
			<p>
				With our engineering and design workflows, we work with local manufacturers to bring quality
				products, far far away from an AI generated landscape. 🤖
			</p>
			<p>text-one-200</p>
		</div>
		<div class="hue-card justify-around bg-twist-200 py-8">
			<p class="text-one-100">
				Bring your own colour choices when not quite automatically perfect.
			</p>
			<p class="text-one-100">
				Also using the <span class="backlight font-mono">twist</span> bg colour here.
			</p>
			<p class="text-one-100">text-one-100</p>
		</div>
		<div class="hue-card justify-between bg-neutral-200 py-8">
			<p class="text-one-300">We look forward to hearing from you via the hotline. ☎️ 👀</p>
			<p class="text-one-300">text-one-300</p>
		</div>
	</div>
</section>
<section data-bg="one" class="hero gap-y-12 px-12">
	<h1 class="text-center">Column cards using mids</h1>
	<div class="grid grid-cols-3 gap-12 [&_p]:px-8">
		<div class="hue-card justify-center bg-neutral-100 py-8">
			<p>
				With our engineering and design workflows, we work with local manufacturers to bring quality
				products, far far away from an AI generated landscape. 🤖
			</p>
		</div>
		<div class="hue-card justify-center border-2 bg-twist-100">
			<p>
				🌈 Inspired by builders and makers of the DIY aesthetic 🪚 to bring you games with digital
				🔌 elements to your table top...
			</p>
		</div>
		<div class="hue-card justify-center bg-neutral-200">
			<p>We look forward to hearing from you via the hotline. ☎️ 👀</p>
		</div>
	</div>
</section>
<footer class="grid w-full grid-cols-1 gap-y-16 px-8 py-16 text-2xl md:grid-cols-3 md:px-16">
	<aside class="flex flex-col justify-between gap-4 text-sm">
		<div class="flex flex-col gap-2">
			<a class="link w-fit" href="https://privacy.techsup.uk">Privacy policy</a>
			<a class="link w-fit" href="https://unsubscribe.techsup.uk">Unsubscribe</a>
		</div>
		<span class="text-wash-200">Tech Support! Interactive Ltd.</span>
	</aside>

	<div class="flex flex-col items-center justify-end text-sm text-wash-200">
		<div class="bg-primary-200 my-4 size-32 max-w-full rounded-2xl border-4 border-white"></div>
		<span>&copy; {new Date().getFullYear()}. All rights reserved.</span>
	</div>

	<aside class="flex flex-col justify-end text-right text-sm text-wash-200">
		<span>Built by</span>
		<a href="https://threejjjs.xyz">
			<h5 class="m-0 text-right text-xl md:text-3xl">
				three<span class="text-pop-200">jjj</span>s
				<br />
			</h5>
		</a>
		<span class="text-xs">Interactive Tech</span>
	</aside>
</footer>

<style>
	.signal {
		position: absolute;
		width: 100%;
		height: 1em;
		border-top: none;
		border-top-left-radius: 0;
		border-top-right-radius: 0;
		transform: translate(0%, 0.5em);
		left: 0;
		top: -2em;
	}
</style>

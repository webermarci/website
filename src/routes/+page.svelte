<script>
	import Logo from '$lib/components/Logo.svelte';
	import TechIconSprite from '$lib/components/TechIconSprite.svelte';
</script>

<TechIconSprite />

<main class="w-full px-3 py-4 md:px-4 lg:py-12 xl:py-24 2xl:py-32">
	<div class="m-auto flex max-w-xl flex-col items-center">
		<Logo />

		<h1 class="manrope mt-4 mb-4 text-3xl font-extrabold">Hey, I'm Marci. 👋</h1>

		<p class="aleo mb-4 text-center text-xl tracking-wide">
			I'm a passionate software engineer who cares deeply about <span
				class="highlight-container-left quality-animation"
				><span class="highlight">quality</span></span
			>
			and
			<span class="highlight-container-right performance-animation"
				><span class="highlight">performance</span></span
			>.
		</p>

		<p class="aleo mb-4 flex items-center gap-1 text-center text-lg tracking-wide text-zinc-500">
			<svg
				xmlns="http://www.w3.org/2000/svg"
				width="24"
				height="24"
				viewBox="0 0 24 24"
				fill="none"
				stroke="currentColor"
				stroke-width="2"
				stroke-linecap="round"
				stroke-linejoin="round"
				class="mb-0.5 h-5 w-5 text-zinc-400"
				aria-hidden="true"
			>
				<path
					d="M20 10c0 4.993-5.539 10.193-7.399 11.799a1 1 0 0 1-1.202 0C9.539 20.193 4 14.993 4 10a8 8 0 0 1 16 0"
				/>
				<circle cx="12" cy="10" r="3" />
			</svg>
			Budapest, Hungary
		</p>

		<p class="aleo mb-8 text-center text-xl tracking-wide">
			You can find me on
			<a
				class="font-medium text-blue-500 underline-offset-2 hover:underline"
				target="_blank"
				rel="noopener noreferrer"
				href="https://www.linkedin.com/in/webermarton/">LinkedIn</a
			>,
			<a
				class="font-medium text-blue-500 underline-offset-2 hover:underline"
				target="_blank"
				rel="noopener noreferrer"
				href="https://github.com/webermarci">GitHub</a
			>, or get in touch via
			<a
				class="font-medium text-blue-500 underline-offset-2 hover:underline"
				href="mailto:webermarton@gmail.com">email</a
			>.
		</p>

		<div class="mb-12 flex flex-wrap justify-center gap-3 text-zinc-400">
			<svg
				role="img"
				viewBox="0 0 24 24"
				xmlns="http://www.w3.org/2000/svg"
				fill="currentColor"
				class="w-8 text-[#00ADD8]"
			>
				<title>Go</title>
				<use href="#tech-icon-go" />
			</svg>

			<svg
				role="img"
				viewBox="0 0 24 24"
				xmlns="http://www.w3.org/2000/svg"
				fill="currentColor"
				class="w-8 text-[#3178C6]"
			>
				<title>TypeScript</title>
				<path
					d="M1.125 0C.502 0 0 .502 0 1.125v21.75C0 23.498.502 24 1.125 24h21.75c.623 0 1.125-.502 1.125-1.125V1.125C24 .502 23.498 0 22.875 0zm17.363 9.75c.612 0 1.154.037 1.627.111a6.38 6.38 0 0 1 1.306.34v2.458a3.95 3.95 0 0 0-.643-.361 5.093 5.093 0 0 0-.717-.26 5.453 5.453 0 0 0-1.426-.2c-.3 0-.573.028-.819.086a2.1 2.1 0 0 0-.623.242c-.17.104-.3.229-.393.374a.888.888 0 0 0-.14.49c0 .196.053.373.156.529.104.156.252.304.443.444s.423.276.696.41c.273.135.582.274.926.416.47.197.892.407 1.266.628.374.222.695.473.963.753.268.279.472.598.614.957.142.359.214.776.214 1.253 0 .657-.125 1.21-.373 1.656a3.033 3.033 0 0 1-1.012 1.085 4.38 4.38 0 0 1-1.487.596c-.566.12-1.163.18-1.79.18a9.916 9.916 0 0 1-1.84-.164 5.544 5.544 0 0 1-1.512-.493v-2.63a5.033 5.033 0 0 0 3.237 1.2c.333 0 .624-.03.872-.09.249-.06.456-.144.623-.25.166-.108.29-.234.373-.38a1.023 1.023 0 0 0-.074-1.089 2.12 2.12 0 0 0-.537-.5 5.597 5.597 0 0 0-.807-.444 27.72 27.72 0 0 0-1.007-.436c-.918-.383-1.602-.852-2.053-1.405-.45-.553-.676-1.222-.676-2.005 0-.614.123-1.141.369-1.582.246-.441.58-.804 1.004-1.089a4.494 4.494 0 0 1 1.47-.629 7.536 7.536 0 0 1 1.77-.201zm-15.113.188h9.563v2.166H9.506v9.646H6.789v-9.646H3.375z"
				/>
			</svg>

			<svg
				role="img"
				viewBox="0 0 24 24"
				xmlns="http://www.w3.org/2000/svg"
				fill="currentColor"
				class="w-8 text-[#4B275F]"
			>
				<title>Elixir</title>
				<use href="#tech-icon-elixir" />
			</svg>

			<svg
				role="img"
				viewBox="0 0 24 24"
				xmlns="http://www.w3.org/2000/svg"
				fill="currentColor"
				class="w-8 text-[#FFAFF3]"
			>
				<title>Gleam</title>
				<path
					d="M10.6144.0026a1.9 1.9 0 0 0-.229.0261l.0001.0002C9.78.1358 9.2263.538 8.9971 1.1873l-1.7855 5.059A1.8 1.8 0 0 1 6.1704 7.323L1.1706 9.282c-1.283.5027-1.531 2.2673-.4373 3.1027l4.2646 3.257a1.795 1.795 0 0 1 .7031 1.3212l.3179 5.3537c.0815 1.3735 1.6836 2.1548 2.819 1.3729v-.0002l4.4212-3.0459v-.0001a1.8 1.8 0 0 1 1.4757-.2601l5.1962 1.3498c1.3342.3467 2.5725-.9356 2.1794-2.2543v.0002l-1.532-5.1397a1.796 1.796 0 0 1 .209-1.482v-.0002l2.8934-4.5194c.742-1.1591-.0945-2.7324-1.472-2.766l-5.368-.1303a1.8 1.8 0 0 1-1.3467-.6558L12.0862.6422c-.3827-.4654-.9342-.6678-1.4718-.6396m5.7066 10.4086c.4626-.0106.8762.3176.959.7872a.953.953 0 0 1-.773 1.1038.9528.9528 0 1 1-.186-1.891M8.6439 11.765a.953.953 0 0 1 .959.7873c.0913.5182-.2548 1.0123-.773 1.1038s-1.0125-.2547-1.1038-.7729c-.0914-.5182.2547-1.0124.773-1.1038a.96.96 0 0 1 .1448-.0144m4.928 1.3841a.486.486 0 0 1 .3397.15.485.485 0 0 1 .1339.3463 1.264 1.264 0 0 1-.3917.8853v.0001h-.0002a1.266 1.266 0 0 1-.9026.3488h-.0004a1.26 1.26 0 0 1-.4812-.1079 1.26 1.26 0 0 1-.4038-.284 1.27 1.27 0 0 1-.2642-.4168.485.485 0 0 1 .278-.6272.483.483 0 0 1 .371.009.485.485 0 0 1 .2561.2687.29.29 0 0 0 .0615.097v.0002a.3.3 0 0 0 .0938.0658v.0001h.0003a.295.295 0 0 0 .2252.0055l.0003-.0001a.292.292 0 0 0 .1628-.1553l.0002-.0002v-.0001a.29.29 0 0 0 .025-.1116.486.486 0 0 1 .15-.3395.485.485 0 0 1 .3463-.134z"
				/>
			</svg>

			<svg
				role="img"
				fill="none"
				viewBox="0 0 32 32"
				xmlns="http://www.w3.org/2000/svg"
				class="w-8"
			>
				<title>Python</title>
				<path
					d="m13.016 2c-2.1971 0-3.9782 1.7245-3.9782 3.8518v2.6667h6.8852v0.74074h-9.9454c-2.1971 0-3.9781 1.7245-3.9781 3.8518v5.7778c0 2.1273 1.7811 3.8518 3.9781 3.8518h2.2951v-3.2592c0-2.1273 1.7811-3.8519 3.9782-3.8519h7.3442c1.8591 0 3.3661-1.4592 3.3661-3.2592v-6.5186c0-2.1273-1.781-3.8518-3.9781-3.8518h-5.9672zm-0.918 4.7407c0.7605 0 1.377-0.59696 1.377-1.3333 0-0.73638-0.6165-1.3333-1.377-1.3333-0.7606 0-1.3771 0.59696-1.3771 1.3333 0 0.73637 0.6165 1.3333 1.3771 1.3333z"
					clip-rule="evenodd"
					fill="#3776AB"
					fill-rule="evenodd"
				/>
				<path
					d="m18.983 30c2.1971 0 3.9782-1.7245 3.9782-3.8518v-2.6667h-6.8853v-0.7407h9.9454c2.1971 0 3.9781-1.7246 3.9781-3.8519v-5.7778c0-2.1273-1.781-3.8518-3.9781-3.8518h-2.2951v3.2592c0 2.1274-1.7811 3.8519-3.9781 3.8519h-7.3443c-1.8591 0-3.3661 1.4592-3.3661 3.2592v6.5186c0 2.1273 1.7811 3.8518 3.9781 3.8518h5.9672zm0.9181-4.7407c-0.7606 0-1.3771 0.5969-1.3771 1.3333s0.6165 1.3333 1.3771 1.3333c0.7605 0 1.377-0.5969 1.377-1.3333s-0.6165-1.3333-1.377-1.3333z"
					clip-rule="evenodd"
					fill="#FFDA4B"
					fill-rule="evenodd"
				/>
			</svg>

			<svg
				role="img"
				viewBox="0 0 24 24"
				xmlns="http://www.w3.org/2000/svg"
				class="w-8 text-[#000000]"
			>
				<title>Rust</title>
				<use href="#tech-icon-rust" />
			</svg>

			<svg
				role="img"
				viewBox="0 0 24 24"
				xmlns="http://www.w3.org/2000/svg"
				fill="currentColor"
				class="w-8 text-[#F46800]"
			>
				<title>Grafana</title>
				<use href="#tech-icon-grafana" />
			</svg>
		</div>

		<h2 class="manrope mb-4 text-2xl font-extrabold">Experience</h2>

		<div class="mb-4 flex w-full flex-col justify-center gap-6">
			<div class="flex w-full flex-col items-center rounded">
				<div
					class="flex w-full items-center justify-between gap-2 rounded-lg border border-zinc-300 bg-zinc-50 px-4 py-2"
				>
					<div class="flex items-center gap-1">
						<p class="manrope font-extrabold tracking-wide">Rise Engine</p>
						<p class="manrope font-medium tracking-wide text-zinc-500">(2024 - 2026)</p>
					</div>
					<div class="flex items-center gap-2">
						<svg
							role="img"
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="w-4 text-zinc-500 md:w-5"
						>
							<title>Go</title>
							<use href="#tech-icon-go" />
						</svg>

						<svg
							role="img"
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="w-4 text-zinc-500 md:w-5"
						>
							<title>Elixir</title>
							<use href="#tech-icon-elixir" />
						</svg>

						<svg
							role="img"
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="w-4 text-zinc-500 md:w-5"
						>
							<title>Svelte</title>
							<use href="#tech-icon-svelte" />
						</svg>

						<svg
							role="img"
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="w-4 text-zinc-500 md:w-5"
						>
							<title>Grafana</title>
							<use href="#tech-icon-grafana" />
						</svg>
					</div>
				</div>
				<p
					class="aleo mt-2 ml-2 w-full border-l-2 border-zinc-300 pt-0.5 pr-2 pl-3 text-lg tracking-wide"
				>
					Early-stage startup aiming to revolutionize <span
						class="underline decoration-zinc-500 underline-offset-2"
						>industrial control and automation</span
					> by leveraging industrial computers instead of traditional PLCs. I lead the development of
					most of the software systems.
				</p>
			</div>

			<div class="flex w-full flex-col items-center rounded">
				<div
					class="flex w-full items-center justify-between gap-2 rounded-lg border border-zinc-300 bg-zinc-50 px-4 py-2"
				>
					<div class="flex items-center gap-1">
						<p class="manrope font-extrabold tracking-wide">Parkl</p>
						<p class="manrope font-medium tracking-wide text-zinc-500">(2024)</p>
					</div>
					<div class="flex items-center gap-2">
						<svg
							role="img"
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="w-4 text-zinc-500 md:w-5"
						>
							<title>Go</title>
							<use href="#tech-icon-go" />
						</svg>

						<svg
							role="img"
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="w-4 text-zinc-500 md:w-5"
						>
							<title>Svelte</title>
							<use href="#tech-icon-svelte" />
						</svg>

						<svg
							role="img"
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="w-4 text-zinc-500 md:w-5"
						>
							<title>Grafana</title>
							<use href="#tech-icon-grafana" />
						</svg>
					</div>
				</div>
				<p
					class="aleo mt-2 ml-2 w-full border-l-2 border-zinc-300 pt-0.5 pr-2 pl-3 text-lg tracking-wide"
				>
					I served as a consultant, guiding the complete redesign of their <span
						class="underline decoration-zinc-500 underline-offset-2"
						>parking and electric vehicle charging IoT systems</span
					> — from the hardware level to system monitoring and management.
				</p>
			</div>

			<div class="flex w-full flex-col items-center rounded">
				<div
					class="flex w-full items-center justify-between gap-2 rounded-lg border border-zinc-300 bg-zinc-50 px-3 py-2"
				>
					<div class="flex items-center gap-1">
						<p class="manrope font-extrabold tracking-wide">Katt</p>
						<p class="manrope font-medium tracking-wide text-zinc-500">(2023 - )</p>
					</div>
					<div class="flex items-center gap-2">
						<svg
							role="img"
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="w-4 text-zinc-500 md:w-5"
						>
							<title>Go</title>
							<use href="#tech-icon-go" />
						</svg>

						<svg
							role="img"
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="w-4 text-zinc-500 md:w-5"
						>
							<title>Svelte</title>
							<use href="#tech-icon-svelte" />
						</svg>

						<svg
							role="img"
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="w-4 text-zinc-500 md:w-5"
						>
							<title>PlatformIO</title>
							<path
								d="M12 23.992c1.25.211 7.051-3.743 9.113-8.217.253-.686.61-1.198.746-2.5.21-2.016-.41-3.912-1.59-5.419-.987-1.163-2.305-2.004-3.88-2.532l.683-2.583a1.371 1.371 0 1 0-.76-.189L15.64 5.1c-1.109-.288-2.328-.437-3.64-.444m5.978 11.667c-1.548 1.346-2.525 1.488-3.045 1.467-.274-.034-.75-.558-.919-1.104-.188-.612-.28-1.282-.273-2.2-.199-2.476 1.465-5.624 3.937-6.041 1.003-.186 2.39.493 2.889 2.088.506 1.422-.645 4.147-2.589 5.79zM12 4.656c-1.315.007-2.538.156-3.65.447l-.675-2.56A1.37 1.37 0 0 0 6.962 0a1.372 1.372 0 0 0-.044 2.742L7.6 5.328c-1.57.528-2.885 1.367-3.871 2.528-1.179 1.507-1.8 3.403-1.588 5.419.136 1.302.492 1.814.745 2.5 2.062 4.474 7.862 8.428 9.113 8.217m-1.507-9.507c.007.92-.086 1.589-.274 2.201-.167.546-.644 1.07-.918 1.104-.52.021-1.498-.121-3.045-1.467-1.944-1.643-3.095-4.368-2.589-5.79.5-1.595 1.886-2.274 2.889-2.088 2.471.417 4.136 3.565 3.937 6.04zm6.45-2.19a1.24 1.24 0 1 0 0 2.48 1.24 1.24 0 0 0 0-2.48zm.416 1.149a.325.325 0 1 1 0-.65.325.325 0 0 1 0 .65zM7.25 12.294a1.24 1.24 0 1 0 0 2.48 1.24 1.24 0 0 0 0-2.48zm-.418 1.15a.325.325 0 1 1 0-.65.325.325 0 0 1 0 .65z"
							/>
						</svg>

						<svg
							role="img"
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="w-4 text-zinc-500 md:w-5"
						>
							<title>Grafana</title>
							<use href="#tech-icon-grafana" />
						</svg>
					</div>
				</div>
				<p
					class="aleo mt-2 ml-2 w-full border-l-2 border-zinc-300 pt-0.5 pr-2 pl-3 text-lg tracking-wide"
				>
					This is a <span class="underline decoration-zinc-500 underline-offset-2"
						>passion project</span
					> currently in its early stages, built on the foundation of expertise I've gained over years
					of experience in the parking industry.
				</p>
			</div>

			<div class="flex w-full flex-col items-center rounded">
				<div
					class="flex w-full items-center justify-between gap-2 rounded-lg border border-zinc-300 bg-zinc-50 px-4 py-2"
				>
					<div class="flex items-center gap-1">
						<p class="manrope font-extrabold tracking-wide">NISZ</p>
						<p class="manrope font-medium tracking-wide text-zinc-500">(2021 - 2022)</p>
					</div>
					<div class="flex items-center gap-2">
						<svg
							role="img"
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="w-4 text-zinc-500 md:w-5"
						>
							<title>Go</title>
							<use href="#tech-icon-go" />
						</svg>

						<svg
							role="img"
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="w-4 text-zinc-500 md:w-5"
						>
							<title>Rust</title>
							<use href="#tech-icon-rust" />
						</svg>

						<svg
							role="img"
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="w-4 text-zinc-500 md:w-5"
						>
							<title>Grafana</title>
							<use href="#tech-icon-grafana" />
						</svg>
					</div>
				</div>
				<p
					class="aleo mt-2 ml-2 w-full border-l-2 border-zinc-300 pt-0.5 pr-2 pl-3 text-lg tracking-wide"
				>
					A simple visualization project became a <span
						class="underline decoration-zinc-500 underline-offset-2"
						>breakthrough in file analysis</span
					>, reducing the count and sum of a thousand terabytes of small files from 2 days to 4
					hours.
				</p>
			</div>

			<div class="flex w-full flex-col items-center rounded">
				<div
					class="flex w-full items-center justify-between gap-2 rounded-lg border border-zinc-300 bg-zinc-50 px-4 py-2"
				>
					<div class="flex items-center gap-1">
						<p class="manrope font-extrabold tracking-wide">Monizor</p>
						<p class="manrope font-medium tracking-wide text-zinc-500">(2020 - 2021)</p>
					</div>
					<div class="flex items-center gap-2">
						<svg
							role="img"
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="w-4 text-zinc-500 md:w-5"
						>
							<title>Go</title>
							<use href="#tech-icon-go" />
						</svg>

						<svg
							role="img"
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="w-4 text-zinc-500 md:w-5"
						>
							<title>Svelte</title>
							<use href="#tech-icon-svelte" />
						</svg>

						<svg
							role="img"
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="w-4 text-zinc-500 md:w-5"
						>
							<title>Arduino</title>
							<use href="#tech-icon-arduino" />
						</svg>

						<svg
							role="img"
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="w-4 text-zinc-500 md:w-5"
						>
							<title>Grafana</title>
							<use href="#tech-icon-grafana" />
						</svg>
					</div>
				</div>
				<p
					class="aleo mt-2 ml-2 w-full border-l-2 border-zinc-300 pt-0.5 pr-2 pl-3 text-lg tracking-wide"
				>
					A colleague from Rollet and I built a <span
						class="underline decoration-zinc-500 underline-offset-2"
						>solar-powered sensor for agriculture</span
					>, using LoRa and sleep cycles for efficient long-range data transmission.
				</p>
			</div>

			<div class="flex w-full flex-col items-center rounded">
				<div
					class="flex w-full items-center justify-between gap-2 rounded-lg border border-zinc-300 bg-zinc-50 px-4 py-2"
				>
					<div class="flex items-center gap-1">
						<p class="manrope font-extrabold tracking-wide">Rollet</p>
						<p class="manrope font-medium tracking-wide text-zinc-500">(2018 - 2024)</p>
					</div>
					<div class="flex items-center gap-2">
						<svg
							role="img"
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="w-4 text-zinc-500 md:w-5"
						>
							<title>Go</title>
							<use href="#tech-icon-go" />
						</svg>

						<svg
							role="img"
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="w-4 text-zinc-500 md:w-5"
						>
							<title>Svelte</title>
							<use href="#tech-icon-svelte" />
						</svg>

						<svg
							role="img"
							fill="none"
							viewBox="0 0 32 32"
							xmlns="http://www.w3.org/2000/svg"
							class="w-4 md:w-5"
						>
							<title>Python</title>
							<path
								d="m13.016 2c-2.1971 0-3.9782 1.7245-3.9782 3.8518v2.6667h6.8852v0.74074h-9.9454c-2.1971 0-3.9781 1.7245-3.9781 3.8518v5.7778c0 2.1273 1.7811 3.8518 3.9781 3.8518h2.2951v-3.2592c0-2.1273 1.7811-3.8519 3.9782-3.8519h7.3442c1.8591 0 3.3661-1.4592 3.3661-3.2592v-6.5186c0-2.1273-1.781-3.8518-3.9781-3.8518h-5.9672zm-0.918 4.7407c0.7605 0 1.377-0.59696 1.377-1.3333 0-0.73638-0.6165-1.3333-1.377-1.3333-0.7606 0-1.3771 0.59696-1.3771 1.3333 0 0.73637 0.6165 1.3333 1.3771 1.3333z"
								clip-rule="evenodd"
								fill="#71717b"
								fill-rule="evenodd"
							/>
							<path
								d="m18.983 30c2.1971 0 3.9782-1.7245 3.9782-3.8518v-2.6667h-6.8853v-0.7407h9.9454c2.1971 0 3.9781-1.7246 3.9781-3.8519v-5.7778c0-2.1273-1.781-3.8518-3.9781-3.8518h-2.2951v3.2592c0 2.1274-1.7811 3.8519-3.9781 3.8519h-7.3443c-1.8591 0-3.3661 1.4592-3.3661 3.2592v6.5186c0 2.1273 1.7811 3.8518 3.9781 3.8518h5.9672zm0.9181-4.7407c-0.7606 0-1.3771 0.5969-1.3771 1.3333s0.6165 1.3333 1.3771 1.3333c0.7605 0 1.377-0.5969 1.377-1.3333s-0.6165-1.3333-1.377-1.3333z"
								clip-rule="evenodd"
								fill="#71717b"
								fill-rule="evenodd"
							/>
						</svg>

						<svg
							role="img"
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="w-4 text-zinc-500 md:w-5"
						>
							<title>React</title>
							<path
								d="M14.23 12.004a2.236 2.236 0 0 1-2.235 2.236 2.236 2.236 0 0 1-2.236-2.236 2.236 2.236 0 0 1 2.235-2.236 2.236 2.236 0 0 1 2.236 2.236zm2.648-10.69c-1.346 0-3.107.96-4.888 2.622-1.78-1.653-3.542-2.602-4.887-2.602-.41 0-.783.093-1.106.278-1.375.793-1.683 3.264-.973 6.365C1.98 8.917 0 10.42 0 12.004c0 1.59 1.99 3.097 5.043 4.03-.704 3.113-.39 5.588.988 6.38.32.187.69.275 1.102.275 1.345 0 3.107-.96 4.888-2.624 1.78 1.654 3.542 2.603 4.887 2.603.41 0 .783-.09 1.106-.275 1.374-.792 1.683-3.263.973-6.365C22.02 15.096 24 13.59 24 12.004c0-1.59-1.99-3.097-5.043-4.032.704-3.11.39-5.587-.988-6.38-.318-.184-.688-.277-1.092-.278zm-.005 1.09v.006c.225 0 .406.044.558.127.666.382.955 1.835.73 3.704-.054.46-.142.945-.25 1.44-.96-.236-2.006-.417-3.107-.534-.66-.905-1.345-1.727-2.035-2.447 1.592-1.48 3.087-2.292 4.105-2.295zm-9.77.02c1.012 0 2.514.808 4.11 2.28-.686.72-1.37 1.537-2.02 2.442-1.107.117-2.154.298-3.113.538-.112-.49-.195-.964-.254-1.42-.23-1.868.054-3.32.714-3.707.19-.09.4-.127.563-.132zm4.882 3.05c.455.468.91.992 1.36 1.564-.44-.02-.89-.034-1.345-.034-.46 0-.915.01-1.36.034.44-.572.895-1.096 1.345-1.565zM12 8.1c.74 0 1.477.034 2.202.093.406.582.802 1.203 1.183 1.86.372.64.71 1.29 1.018 1.946-.308.655-.646 1.31-1.013 1.95-.38.66-.773 1.288-1.18 1.87-.728.063-1.466.098-2.21.098-.74 0-1.477-.035-2.202-.093-.406-.582-.802-1.204-1.183-1.86-.372-.64-.71-1.29-1.018-1.946.303-.657.646-1.313 1.013-1.954.38-.66.773-1.286 1.18-1.868.728-.064 1.466-.098 2.21-.098zm-3.635.254c-.24.377-.48.763-.704 1.16-.225.39-.435.782-.635 1.174-.265-.656-.49-1.31-.676-1.947.64-.15 1.315-.283 2.015-.386zm7.26 0c.695.103 1.365.23 2.006.387-.18.632-.405 1.282-.66 1.933-.2-.39-.41-.783-.64-1.174-.225-.392-.465-.774-.705-1.146zm3.063.675c.484.15.944.317 1.375.498 1.732.74 2.852 1.708 2.852 2.476-.005.768-1.125 1.74-2.857 2.475-.42.18-.88.342-1.355.493-.28-.958-.646-1.956-1.1-2.98.45-1.017.81-2.01 1.085-2.964zm-13.395.004c.278.96.645 1.957 1.1 2.98-.45 1.017-.812 2.01-1.086 2.964-.484-.15-.944-.318-1.37-.5-1.732-.737-2.852-1.706-2.852-2.474 0-.768 1.12-1.742 2.852-2.476.42-.18.88-.342 1.356-.494zm11.678 4.28c.265.657.49 1.312.676 1.948-.64.157-1.316.29-2.016.39.24-.375.48-.762.705-1.158.225-.39.435-.788.636-1.18zm-9.945.02c.2.392.41.783.64 1.175.23.39.465.772.705 1.143-.695-.102-1.365-.23-2.006-.386.18-.63.406-1.282.66-1.933zM17.92 16.32c.112.493.2.968.254 1.423.23 1.868-.054 3.32-.714 3.708-.147.09-.338.128-.563.128-1.012 0-2.514-.807-4.11-2.28.686-.72 1.37-1.536 2.02-2.44 1.107-.118 2.154-.3 3.113-.54zm-11.83.01c.96.234 2.006.415 3.107.532.66.905 1.345 1.727 2.035 2.446-1.595 1.483-3.092 2.295-4.11 2.295-.22-.005-.406-.05-.553-.132-.666-.38-.955-1.834-.73-3.703.054-.46.142-.944.25-1.438zm4.56.64c.44.02.89.034 1.345.034.46 0 .915-.01 1.36-.034-.44.572-.895 1.095-1.345 1.565-.455-.47-.91-.993-1.36-1.565z"
							/>
						</svg>

						<svg
							role="img"
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="w-4 text-zinc-500 md:w-5"
						>
							<title>Arduino</title>
							<use href="#tech-icon-arduino" />
						</svg>

						<svg
							role="img"
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="w-4 text-zinc-500 md:w-5"
						>
							<title>Grafana</title>
							<use href="#tech-icon-grafana" />
						</svg>
					</div>
				</div>
				<p
					class="aleo mt-2 ml-2 w-full border-l-2 border-zinc-300 pt-0.5 pr-2 pl-3 text-lg tracking-wide"
				>
					I joined Rollet during its early startup phase, helping build a <span
						class="underline decoration-zinc-500 underline-offset-2">smart parking platform</span
					> as a full-stack developer. As the product evolved, I increasingly focused on IoT, monitoring,
					and device-side systems. Later, I returned as a contractor, working exclusively on IoT and embedded
					development, including a ticket kiosk system.
				</p>
			</div>

			<div class="flex w-full flex-col items-center rounded">
				<div
					class="flex w-full items-center justify-between gap-2 rounded-lg border border-zinc-300 bg-zinc-50 px-4 py-2"
				>
					<div class="flex items-center gap-1">
						<p class="manrope font-extrabold tracking-wide">Ulyssys</p>
						<p class="manrope font-medium tracking-wide text-zinc-500">(2015 - 2017)</p>
					</div>
					<div class="flex items-center gap-2">
						<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 48 48" class="w-4 md:w-5">
							<path
								fill="#71717b"
								d="M23.65,24.898c-0.998-1.609-1.722-2.943-2.725-5.455C19.229,15.2,31.24,11.366,26.37,3.999c2.111,5.089-7.577,8.235-8.477,12.473C17.07,20.37,23.645,24.898,23.65,24.898z"
							>
							</path>
							<path
								fill="#71717b"
								d="M23.878,17.27c-0.192,2.516,2.229,3.857,2.299,5.695c0.056,1.496-1.447,2.743-1.447,2.743s2.728-0.536,3.579-2.818c0.945-2.534-1.834-4.269-1.548-6.298c0.267-1.938,6.031-5.543,6.031-5.543S24.311,11.611,23.878,17.27z"
							>
							</path>
							<g
								><path
									fill="#71717b"
									d="M32.084 25.055c1.754-.394 3.233.723 3.233 2.01 0 2.901-4.021 5.643-4.021 5.643s6.225-.742 6.225-5.505C37.521 24.053 34.464 23.266 32.084 25.055zM29.129 27.395c0 0 1.941-1.383 2.458-1.902-4.763 1.011-15.638 1.147-15.638.269 0-.809 3.507-1.638 3.507-1.638s-7.773-.112-7.773 2.181C11.683 28.695 21.858 28.866 29.129 27.395z"
								>
								</path>
								<path
									fill="#71717b"
									d="M27.935,29.571c-4.509,1.499-12.814,1.02-10.354-0.993c-1.198,0-2.974,0.963-2.974,1.889c0,1.857,8.982,3.291,15.63,0.572L27.935,29.571z"
								>
								</path>
								<path
									fill="#71717b"
									d="M18.686,32.739c-1.636,0-2.695,1.054-2.695,1.822c0,2.391,9.76,2.632,13.627,0.205l-2.458-1.632C24.271,34.404,17.014,34.579,18.686,32.739z"
								>
								</path>
								<path
									fill="#71717b"
									d="M36.281,36.632c0-0.936-1.055-1.377-1.433-1.588c2.228,5.373-22.317,4.956-22.317,1.784c0-0.721,1.807-1.427,3.477-1.093l-1.42-0.839C11.26,34.374,9,35.837,9,37.017C9,42.52,36.281,42.255,36.281,36.632z"
								>
								</path>
								<path
									fill="#71717b"
									d="M39,38.604c-4.146,4.095-14.659,5.587-25.231,3.057C24.341,46.164,38.95,43.628,39,38.604z"
								>
								</path>
							</g>
						</svg>

						<svg
							role="img"
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="w-4 text-zinc-500 md:w-5"
						>
							<title>PHP</title>
							<path
								d="M7.01 10.207h-.944l-.515 2.648h.838c.556 0 .97-.105 1.242-.314.272-.21.455-.559.55-1.049.092-.47.05-.802-.124-.995-.175-.193-.523-.29-1.047-.29zM12 5.688C5.373 5.688 0 8.514 0 12s5.373 6.313 12 6.313S24 15.486 24 12c0-3.486-5.373-6.312-12-6.312zm-3.26 7.451c-.261.25-.575.438-.917.551-.336.108-.765.164-1.285.164H5.357l-.327 1.681H3.652l1.23-6.326h2.65c.797 0 1.378.209 1.744.628.366.418.476 1.002.33 1.752a2.836 2.836 0 0 1-.305.847c-.143.255-.33.49-.561.703zm4.024.715l.543-2.799c.063-.318.039-.536-.068-.651-.107-.116-.336-.174-.687-.174H11.46l-.704 3.625H9.388l1.23-6.327h1.367l-.327 1.682h1.218c.767 0 1.295.134 1.586.401s.378.7.263 1.299l-.572 2.944h-1.389zm7.597-2.265a2.782 2.782 0 0 1-.305.847c-.143.255-.33.49-.561.703a2.44 2.44 0 0 1-.917.551c-.336.108-.765.164-1.286.164h-1.18l-.327 1.682h-1.378l1.23-6.326h2.649c.797 0 1.378.209 1.744.628.366.417.477 1.001.331 1.751zM17.766 10.207h-.943l-.516 2.648h.838c.557 0 .971-.105 1.242-.314.272-.21.455-.559.551-1.049.092-.47.049-.802-.125-.995s-.524-.29-1.047-.29z"
							/>
						</svg>

						<svg
							role="img"
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							fill="currentColor"
							class="w-4 text-zinc-500 md:w-5"
						>
							<title>jQuery</title>
							<path
								d="M1.525 5.87c-2.126 3.054-1.862 7.026-.237 10.269.037.079.078.154.118.229.023.052.049.1.077.15.013.027.031.056.047.082.026.052.054.102.081.152l.157.266c.03.049.057.097.09.146.056.094.12.187.178.281.026.04.05.078.079.117a6.368 6.368 0 00.31.445c.078.107.156.211.24.315.027.038.058.076.086.115l.22.269c.028.03.055.067.084.099.098.118.202.233.306.35l.005.006a3.134 3.134 0 00.425.44c.08.083.16.165.245.245l.101.097c.111.105.223.209.34.309.002 0 .003.002.005.003l.057.05c.102.089.205.178.31.26l.125.105c.085.068.174.133.26.2l.137.105c.093.07.192.139.287.207.035.025.07.05.106.073l.03.023.28.185.12.08c.148.094.294.184.44.272.041.02.084.044.123.068.108.062.22.125.329.183.06.034.122.063.184.094.075.042.153.083.234.125a.324.324 0 01.056.023c.033.015.064.031.096.047.12.06.245.118.375.175.024.01.05.02.076.034.144.063.289.123.438.182.034.01.07.027.105.04.135.051.274.103.411.152l.05.018c.154.052.305.102.46.15.036.01.073.023.111.033.16.048.314.105.474.137 10.273 1.872 13.258-6.177 13.258-6.177-2.508 3.266-6.958 4.127-11.174 3.169-.156-.036-.312-.086-.47-.132a13.539 13.539 0 01-.567-.182l-.062-.024c-.136-.046-.267-.097-.4-.148a1.615 1.615 0 00-.11-.04c-.148-.06-.29-.121-.433-.184-.031-.01-.057-.024-.088-.036a23.44 23.44 0 01-.362-.17 1.485 1.485 0 01-.106-.052c-.094-.044-.188-.095-.28-.143a3.947 3.947 0 01-.187-.096c-.114-.06-.227-.125-.34-.187-.034-.024-.073-.044-.112-.066a15.922 15.922 0 01-.439-.27 2.107 2.107 0 01-.118-.078 6.01 6.01 0 01-.312-.207c-.035-.023-.067-.048-.103-.073a9.553 9.553 0 01-.295-.212c-.042-.034-.087-.066-.132-.1-.088-.07-.177-.135-.265-.208l-.118-.095a10.593 10.593 0 01-.335-.28.258.258 0 00-.037-.031l-.347-.316-.1-.094c-.082-.084-.166-.164-.25-.246l-.098-.1a9.081 9.081 0 01-.309-.323l-.015-.016c-.106-.116-.21-.235-.313-.355-.027-.03-.053-.064-.08-.097l-.227-.277a21.275 21.275 0 01-.34-.449C2.152 11.79 1.306 7.384 3.177 3.771m4.943-.473c-1.54 2.211-1.454 5.169-.254 7.508a9.111 9.111 0 00.678 1.133c.23.33.484.721.793.988.107.122.223.24.344.36l.09.09c.114.11.232.217.35.325l.016.013a9.867 9.867 0 00.414.342c.034.023.063.05.096.073.14.108.282.212.428.316l.015.009c.062.045.128.086.198.13.028.018.06.042.09.06.106.068.21.132.318.197.017.007.032.016.048.023.09.055.188.108.282.157.033.02.065.035.1.054.066.033.132.068.197.102l.032.014c.135.067.273.129.408.19.034.014.063.025.092.039.111.048.224.094.336.137.05.017.097.037.144.052.102.038.21.073.31.108l.14.045c.147.045.295.104.449.13C22.164 17.206 24 11.098 24 11.098c-1.653 2.38-4.852 3.513-8.261 2.628a8.04 8.04 0 01-.449-.13c-.048-.014-.09-.029-.136-.043-.104-.036-.211-.07-.312-.109l-.144-.054c-.113-.045-.227-.087-.336-.135-.034-.015-.065-.025-.091-.04-.14-.063-.281-.125-.418-.192l-.206-.107-.119-.06a5.673 5.673 0 01-.265-.15.62.62 0 01-.062-.035c-.106-.066-.217-.13-.318-.198-.034-.019-.065-.042-.097-.062l-.208-.136c-.144-.1-.285-.208-.428-.313-.032-.029-.063-.053-.094-.079-1.499-1.178-2.681-2.79-3.242-4.613-.59-1.897-.46-4.023.56-5.75m4.292-.147c-.909 1.334-.996 2.99-.37 4.46.665 1.563 2.024 2.79 3.608 3.37.065.025.128.046.196.07l.088.027c.092.03.185.063.28.084 4.381.845 5.567-2.25 5.886-2.704-1.043 1.498-2.792 1.857-4.938 1.335a4.85 4.85 0 01-.516-.16 6.352 6.352 0 01-.618-.254 6.53 6.53 0 01-1.082-.66c-1.922-1.457-3.113-4.236-1.859-6.5"
							/>
						</svg>
					</div>
				</div>
				<p
					class="aleo mt-2 ml-2 w-full border-l-2 border-zinc-300 pt-0.5 pr-2 pl-3 text-lg tracking-wide"
				>
					I developed the company's internal <span
						class="underline decoration-zinc-500 underline-offset-2">HR system</span
					>, working largely independently on the technical side while also contributing to product
					development.
				</p>
			</div>
		</div>
	</div>
</main>

<style>
	:root {
		--highlight-duration: 1s;
	}

	.highlight-container-left,
	.highlight-container-right,
	.highlight {
		position: relative;
	}

	.highlight-container-left,
	.highlight-container-right {
		display: inline-block;
	}

	.highlight-container-left:before,
	.highlight-container-right:before {
		--highlight-rotation: 0deg;
		z-index: -50;
		position: absolute;
		display: block;
		width: 105%;
		height: 95%;
		margin-left: -1px;
		margin-top: 2px;
		top: -1px;
		left: -1px;
		content: ' ';
		background: linear-gradient(to right, rgba(74, 222, 128, 0.3));
		box-decoration-break: clone;
		transform: rotate(var(--highlight-rotation)) scaleX(0);
		transform-origin: left center;
		will-change: transform;
	}

	.highlight-container-left:before {
		--highlight-rotation: 1deg;
		border-radius: 23% 26% 20% 25%;
	}

	.highlight-container-right:before {
		--highlight-rotation: -1deg;
		border-radius: 20% 25% 22% 24%;
	}

	.quality-animation:before {
		animation: highlight-animation var(--highlight-duration) ease-in-out forwards;
	}

	.performance-animation:before {
		animation: highlight-animation var(--highlight-duration) ease-in-out forwards;
		animation-delay: calc(var(--highlight-duration) * 1.5);
	}

	@keyframes highlight-animation {
		to {
			transform: rotate(var(--highlight-rotation)) scaleX(1);
		}
	}

	@media (prefers-reduced-motion: reduce) {
		.quality-animation:before,
		.performance-animation:before {
			animation: none;
			transform: rotate(var(--highlight-rotation)) scaleX(1);
		}
	}
</style>

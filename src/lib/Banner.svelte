<div class="relative bg-center bg-cover h-80 banner">
	<h1 class="text-4xl absolute top-36 text-center font-bold w-full shadow-2xl">
		TRISTAN VOULELIS
	</h1>
</div>

<style>
	.banner::before {
		content: "";
		position: absolute;
		top: 0;
		left: 0;
		width: 100%;
		height: inherit;

		background-image: url("../banner_lab1.jpg");
		background-position: 0%;
		background-size: 100%;
		background-repeat: repeat-y;

		filter: brightness(0.8) blur(1px);
		/* transition: all 0.2s ease-in-out; */
	}

	/* .banner:hover::before {
		transform: scale(1.01);
		filter: brightness(0.9) blur(1px);
	} */

	h1 {
		font-family: 'Lexend Peta', sans-serif;
		font-size: 3.5em;
		font-weight: 300;
		filter: drop-shadow(0px 4px 6px black);
	}
</style>
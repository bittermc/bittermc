<script>
	import mods from './mods.md?raw';
	import { marked } from 'marked';
</script>

<main>
	<header class="bittermc">
		<img src="./img/logo.png">
		<p>a terrible minecraft server</p>
		<div class="socials">
			<a href="https://discord.gg/ymYxAeXE7h"><img src="./img/icon/discord.svg"></a>
			<a href="https://github.com/bittermc"><img src="./img/icon/github.svg"></a>
		</div>
	</header>

	<div class="box">
		<h1>🍊 what is bitter!mc?</h1>
		a dumb fabric minecraft smp thing by <a href="https://macimas.github.io">me</a> that i made on april 7, 2021<br>
		it has been through numerous management issues, mostly because of me :D
	</div>

	<div class="box">
		<h1>📥 where is modpack?</h1>
		you are the <a href="https://bittermc.github.io/modpack/client.zip">client</a>, and jake is the <a href="https://bittermc.github.io/modpack/server.zip">server</a> (altho he is also client).<br>
		<br>
		installation is simple:<br>
		for client, extract it inside the .minecraft folder<br>
		for server, extract it inside the server folder
	</div>

	<div class="box">
		<h1>🤨 what can i expect?</h1>

		<div class="image-gallery">
			<div>
				<img src="./img/screenshot/artifacts.png">
				drippy artifacts and custom paintings
			</div>
			<div>
				<img src="./img/screenshot/fabric waystones.png">
				fabric waystones
			</div>
			<div>
				<img src="./img/screenshot/create.png">
				Create™
			</div>
			<div>
				<img src="./img/screenshot/dark enchanting.png">
				nice enchanting
			</div>
		</div>

		{@html marked.parse(mods)}
	</div>
</main>
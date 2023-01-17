<template>
	<div class="bg-green-500 rounded">
		<div id="aplayer"></div>
	</div>
</template>

<script setup>
import { onMounted } from 'vue'
import APlayer from 'aplayer'
import 'aplayer/dist/APlayer.min.css'

onMounted(() => {
	thePlayer()
})

const thePlayer = () => {
	new APlayer({
		container: document.getElementById('aplayer'),
		audio: [
			{
				name: 'Lil Tracy - Red like blood',
				artist: 'artist',
				url: '/music/redlikeblook-liltracy.mp3',
				cover: 'cover.jpg'
			},
			{
				name: 'Oz The Oddz - Scarface',
				artist: 'artist',
				url: '/music/scarface-oztheoddz.mp3',
				cover: 'cover.jpg'
			},
		]
	});

}
</script>
<!-- <script lang="ts">
	import { Router } from '@roxi/routify';
	import { routes } from '../.routify/routes';
</script>

<Router routes="{routes}" /> -->
<style>
	ul {
		padding: 20px;
		background: black;
		color: rgb(118, 118, 2);
		display: flex;
		gap: 20px;
		justify-content: center;
	}
	ul li {
	}
	ul li div.on {
		color: yellow;
	}
</style>

<script lang="ts">
	let currentPage = 'index';
	import Index from './pages/index.svelte';
	import Markup1 from './pages/html/html1.svelte';
	import Markup2 from './pages/html/html2.svelte';
	import Markup3 from './pages/html/html3.svelte';
	import Markup4 from './pages/html/html4.svelte';

	// import Nav from './components/nav/Nav.svelte';

	type ClickEvent = MouseEvent & {
		currentTarget: EventTarget & HTMLButtonElement;
	};
	const clickHandler = (e: ClickEvent) => {
		const target = e.target as HTMLButtonElement;
		currentPage = target.innerText;
	};
</script>

<ul>
	<li
		><button on:click="{clickHandler}">
			<div class="{`${currentPage === 'markup/markup1' ? 'on' : ''}`}"> markup/markup1</div>
		</button></li
	>
	<li
		><button on:click="{clickHandler}">
			<div class="{`${currentPage === 'markup/markup2' ? 'on' : ''}`}">markup/markup2</div>
		</button></li
	>
	<li
		><button on:click="{clickHandler}">
			<div class="{`${currentPage === 'markup/markup3' ? 'on' : ''}`}">markup/markup3</div>
		</button></li
	>
	<li
		><button on:click="{clickHandler}">
			<div class="{`${currentPage === 'markup/markup4' ? 'on' : ''}`}"> markup/markup4</div>
		</button></li
	>
</ul>

<main>
	{#if currentPage === 'index'}
		<div class="wrapper"><Index /></div>
	{/if}
	{#if currentPage === 'markup/markup1'}
		<div class="wrapper"><Markup1 /></div>
	{/if}
	{#if currentPage === 'markup/markup2'}
		<div class="wrapper"><Markup2 /></div>
	{/if}
	{#if currentPage === 'markup/markup3'}
		<div class="wrapper"><Markup3 /></div>
	{/if}
	{#if currentPage === 'markup/markup4'}
		<div class="wrapper"><Markup4 /></div>
	{/if}
</main>

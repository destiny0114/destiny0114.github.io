<script>
	let className = '';
	export { className as class };

	export let width = '30';
	export let height = '30';
	export let fill = '#fff';
</script>

<svg xmlns="http://www.w3.org/2000/svg" {width} {height} fill="none" viewBox="0 0 30 30">
	<path
		class={className}
		{fill}
		fill-rule="evenodd"
		d="M15.04 6.9c-4.663 0-8.44 3.758-8.44 8.398 0 3.717 2.416 6.856 5.77 7.968.422.074.58-.178.58-.399 0-.199-.01-.86-.01-1.564-2.12.389-2.669-.514-2.838-.987-.095-.241-.506-.986-.865-1.186-.295-.157-.717-.546-.01-.556.664-.01 1.14.609 1.297.86.76 1.27 1.973.914 2.458.694.074-.546.296-.914.538-1.124-1.877-.21-3.84-.934-3.84-4.147 0-.913.327-1.669.865-2.257-.084-.21-.38-1.07.085-2.225 0 0 .707-.22 2.32.86a7.865 7.865 0 0 1 2.11-.283c.718 0 1.435.095 2.11.284 1.614-1.092 2.321-.861 2.321-.861.464 1.155.169 2.015.085 2.225a3.24 3.24 0 0 1 .865 2.258c0 3.222-1.973 3.936-3.85 4.146.305.263.569.766.569 1.554 0 1.123-.01 2.026-.01 2.31 0 .22.158.482.58.398 3.333-1.112 5.749-4.262 5.749-7.968 0-4.64-3.777-8.398-8.44-8.398Z"
		clip-rule="evenodd"
	/>
</svg>

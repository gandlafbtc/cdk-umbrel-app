<script>
	let connected = $state(true);
</script>

<!-- Main container with orange background -->
<div class="flex flex-col w-full">
	<!-- App content -->
	<div class="p-6">
		<!-- App header with icon, name, and connect button -->
		<div class="flex justify-between items-center mb-6">
			<div class="flex items-center gap-4">
				<img src="/CDK_BG.png" class="w-36 h-36 rounded-2xl" />
				<div class=" flex flex-col justify-between gap-6">
					<div class="text-xs flex gap-2 items-center">
						{#if connected}
              <div class="rounded-full bg-success w-2 h-2">
              </div>
							<p class="text-success">Connected</p>
						{/if}
					</div>
					<div class="font-bold text-4xl">CDK Mint</div>
					<div class="text-xs text-neutral-content">CDK 0.9.2</div>
				</div>
			</div>
		</div>
    <p class="text-5xl font-bold">
      Cashu CDK mint is running...
    </p>
	</div>
</div>

<style>
	/* Custom utility classes */
	.h-40\% {
		height: 40%;
	}
	.h-30\% {
		height: 30%;
	}
	.h-60\% {
		height: 60%;
	}
	.h-70\% {
		height: 70%;
	}
	.h-90\% {
		height: 90%;
	}
	.h-50\% {
		height: 50%;
	}
</style>

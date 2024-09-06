<div
	bind:this={navElement}
	id="sidebar"
	class="h-screen max-h-[100dvh] min-h-screen select-none {$showSidebar
		? 'md:relative w-[260px]'
		: '-translate-x-[260px] w-[0px]'} bg-sidebar text-gray-200 text-sm transition fixed z-50 top-0 left-0 rounded-r-2xl"
	data-state={$showSidebar}
>
	<!-- Rest of the sidebar content -->
</div>
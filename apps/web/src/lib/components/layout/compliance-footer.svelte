<script lang="ts">
	import beianIcon from '../../../beian.png';
</script>

<!-- 网站备案信息：ICP 备案与公安联网备案，固定于页面底部正中 -->
<div
	class="pointer-events-none fixed inset-x-0 bottom-0 z-30 flex h-9 items-center justify-center pb-0.5"
>
	<div
		class="pointer-events-auto flex items-center gap-3 text-xs leading-none text-muted-foreground"
	>
		<a
			href="https://beian.miit.gov.cn/"
			target="_blank"
			rel="noreferrer"
			class="rounded-sm transition-colors hover:text-foreground focus-visible:outline-none focus-visible:ring-1 focus-visible:ring-ring"
		>
			晋ICP备2023020746号-2
		</a>
		<span class="h-3 w-px bg-border" aria-hidden="true"></span>
		<a
			href="https://beian.mps.gov.cn/#/query/webSearch?code=14010602111139"
			target="_blank"
			rel="noreferrer"
			class="flex items-center gap-1.5 rounded-sm transition-colors hover:text-foreground focus-visible:outline-none focus-visible:ring-1 focus-visible:ring-ring"
		>
			<img src={beianIcon} alt="公安备案" width="20" height="20" class="h-5 w-5 shrink-0" />
			<span>晋公网安备14010602111139号</span>
		</a>
	</div>
</div>

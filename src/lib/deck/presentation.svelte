<script lang="ts">
	import Slide from './slide.svelte';
	import FirstSlide from '$lib/slides/first_slide.svelte';
	import SecondSlide from '$lib/slides/second_slide.svelte';
	import ThirdSlide from '$lib/slides/third_slide.svelte';
	import FourthSlide from '$lib/slides/fourth_slide.svelte';
	import FifthSlide from '$lib/slides/fifth_slide.svelte';
	import SixthSlide from '$lib/slides/sixth_slide.svelte';
	import SeventhSlide from '$lib/slides/seventh_slide.svelte';
	import Listing from '$lib/slides/listing.svelte';
</script>

<!-- 1 -->
<FirstSlide />
<!-- 2 -->
<SecondSlide />
<!-- 3 -->
<ThirdSlide />
<!-- 4 -->
<FourthSlide />
<!-- 5 -->
<FifthSlide />
<!-- 6 -->
<SixthSlide />
<!-- 7 -->
<SeventhSlide />
<!-- Źródła -->
<Listing />
<!-- Koniec -->
<Slide>
	<h2>Dziękujemy za uwagę :)</h2>
	<div class="flex justify-center">
		<img src="/snoopy.gif" alt="Snoopy with hearts floating around" />
	</div>
</Slide>

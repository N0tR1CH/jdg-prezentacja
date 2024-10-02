<script lang="ts">
	import Markdown from '$lib/deck/markdown.svelte';
	import Slide from '../deck/slide.svelte';
</script>

<Slide>
	<Slide>
		<h2>Forma prawna?</h2>
		<div class="flex justify-center">
			<img src="/thinking.gif" alt="Cartoonish human being reasoning about something." />
		</div>
	</Slide>

	<Slide>
		<p>
			Wymienione wcześniej kwestie będą w głównej mierze zależeć od wyboru odpowiedniej formy
			prawnej.
		</p>
	</Slide>

	<Slide>
		<p>
			Definiuje ona status prawny i zasady funkcjonowania firmy. W dużym skrócie firma niczym
			obywatel posiada jasno określone prawa i obowiązki.
		</p>
	</Slide>

	<Slide>
		<p>W Polsce obowiązuje kilka rodzajów możliwych do przyjęcia form prawnych.</p>
	</Slide>

	<Slide>
		<p>Są nimi między innymi:</p>
		<Markdown>
			{`
        - Spółka cywilna
        - Spółki kapitałowe:
          - Spółka z ograniczoną odpowiedzialnością
          - Spółka akcyjna
        - Spółki osobowe:
          - Spółka jawna
          - Spółka partnerska
          - Spółka komandytowa
          - Spółka komandytowo-akcyjna
        - **Jednoosobowa działalność gospodarcza**
      `}
		</Markdown>
	</Slide>

	<Slide>
		<p>Omawiana jednoosobowa działalność gospodarcza jest najprostszą formą prawną.</p>
	</Slide>
</Slide>

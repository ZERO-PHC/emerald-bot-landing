<script>
import Container from "$lib/components/atoms/Container.svelte";
import Section from "$lib/components/atoms/Section.svelte";


</script>

<Section paddingTop={false}>
  <Container width="medium" direction="row">
    <main style="display: flex;">
      <div class="column">
        <h1>EMERALD <br/> BOT</h1>
        <p>
          A cool paragraph with a call to action
        </p>
       
      </div>
      <div style="display: flex; width:50vw; justify-content:center; align-items:center">
        Bot Model
      </div>
    </main>
    

   
  </Container>
</Section>

<style>
  .column {
    display: flex;
    flex-direction: column;
    align-items: left;
    justify-content: center;
  }

  span {
    font-family: var(--font-accent);
    letter-spacing: .5em;
    padding-bottom: 1.4em;
    text-align: left;
  }

  h1 {
    text-align: left;
    font-size: clamp(2rem, 15vw, 6.2rem);
    font-weight: 700;
    color: transparent;
    -webkit-text-stroke: 1px var(--text);
  }

  p {
    text-align: left;
    font-size: var(--font-size-l);
  }
  
  b {
    color: var(--primary);
  }
</style>
<script>
  let frameworks = [
    { id: 1, name: 'Svelte' },
    { id: 2, name: 'React' },
    { id: 3, name: 'Vue' },
    { id: 4, name: 'Angular' }
  ];
</script>

<h1>List of Frameworks</h1>

<ul>
  {#each frameworks as {id, name}}
     <li>
      {id}: {name}
     </li>
  {/each}

</ul>

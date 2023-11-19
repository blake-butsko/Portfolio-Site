<script>
    export let data;
  </script>

<head>	  
	  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
	  <title>Page</title>
</head>

  <ul>
    {#each data.countries as country}
      <li>{country.name}</li>
    {/each}
  </ul>
<script lang="ts">
  import rss from './api/rss.json'
</script>

<div class="container">
  <main>
    <h1>Tech Influencer Aggregator</h1>
    
    <p>
      This app is in idea phase.
    </p>
    
    <p>
      Going to make aggregate all the tech channels I enjoy and wrap them up in rss groups that can be subscribed to. Either using tags are individually.
    </p>
    
    <p>Heres the dataset draft</p>
    
  </main>
</div>

<pre>{JSON.stringify(rss, null, 2)}</pre>

<style>
  * {
    padding: 0;
    /* margin: 0; */
    box-sizing: border-box;
  }

  .container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 100vw;
  }

  main {
    max-width: 600px;
  }
</style>
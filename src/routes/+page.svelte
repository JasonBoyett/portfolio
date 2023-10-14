<script>
  import pfPick from "$lib/images/profile_pic.jpg";
  import hi from "$lib/images/hi.svg";
</script>

<svelte:head>
  <title>Home</title>
  <meta name="description" content="Developer Portfolio" />
</svelte:head>

<section>
  <span class="welcome">
    <img src={hi} alt="Hi I'm Jason" />
  </span>
  <img class="pfPick" src={pfPick} alt="Jason Boyett" />
  <h1>
    Hi, I'm Jason. I'm a full stack software engineer with a passion for
    personal growth, continuous learning and good music.
  </h1>
</section>

<style>
  section {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    flex: 0.6;
  }

  h1 {
    width: 100%;
    animation: fadein 2s;
    animation-iteration-count: 1;
    font-family: "Baskervville", serif;
  }

  .welcome {
    display: block;
    position: relative;
    width: 100%;
    height: 0;
    padding: 0 0 calc(100% * 495 / 2048) 0;
    animation: fadein-zoom 1.5s;
    animation-iteration-count: 1;
  }

  .pfPick {
    width: 40%;
    height: 40%;
    animation: fadein 2s;
    animation-iteration-count: 1;
    border-radius: 25px;
  }

  @keyframes fadein-zoom {
    from {
      opacity: 0;
      width: 70%;
    }
    to {
      opacity: 1;
      width: 100%;
    }
  }

  @keyframes fadein {
    from {
      opacity: 0;
    }
    to {
      opacity: 1;
    }
  }

  .welcome img {
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    display: block;
  }
</style>

<svelte:head>
  <title>About</title>
  <meta name="description" content="About this app" />
</svelte:head>

<div class="text-column">
  <h1>About Me</h1>

  <p>
    I graduated from Schreiner University in 2023 with a Bachelor's in Computer Science
    and a minor in Mathematics.
    <break />
    During my time at Schreiner I worked as a Teaching Assistant for the Computer Science department. This expereince helped me master programing fundimentals and gave me a passion for helping other grow and succeed.
    <break />
    I am currently working with Schreiner University to develop a speed reading program
    to help students improve their reading speed and comprehension.
    <break />
    My favorite technologies include, TypeScript, Go, Python, Java, and Linux.
  </p>

  <h1>Here are some projects I'm proud of:</h1>

  <h2>Project Iris</h2>

  <p>
    Project Iris is a speed reading program that I am developing with Schreiner
    University. It is a web app built with react and the t3 stack under the
    hood. <break />
    It is currently in the alpha stage of development and will soon be deployed for
    testing with students at Schreiner University. <break />
    check it out
    <a href="https://speedread-git-main-jasonboyett.vercel.app/">here.</a>
    Or checkout the code on my
    <a href="https://github.com/JasonBoyett/project-iris">GitHub</a>
  </p>
  <h2>Turing Pass</h2>
  <p>
    Turing Pass is a chrome extension that helps the user generate secure
    passwords. <break />
    The user simply has to remember a single password and the extension will generate
    a unique password for each site that the user visits. <break />
    The user can then re-generate the password for any given site using their master
    password. <break />
    Turing Pass has two componants available on github, a
    <a href="https://github.com/JasonBoyett/Turing-Pass-CE">chrome extension</a
    >
    and a
    <a href="https://github.com/JasonBoyett/Turing-Pass-API">backend server.</a>
  </p>
  <h2>Terminal Background Tool</h2>
  <p>
    It's a tale as old as time, developer is minorly inconvenienced by a first
    world problem, So they decide to spend several hours building a solution to
    that problem.<break />
    For me, the first world problem was that I wanted to be able to easily change
    my terminal background without having to go into my dot files. <break />
    So, I built a simple tool that allows me to do just that. <break />
    It's available on my
    <a href="https://github.com/JasonBoyett/terminal-background-tool">GitHub</a>
  </p>

  <h2>Salvo Load Tester</h2>
  <p>
    Salvo is an open source load testing tool I am currently developing.
    <break />
    It is designed to be easy to extend and easy to create language specific SDKs for.
    <break />
    It's available on my
    <a href="https://github.com/JasonBoyett/Slavo">GitHub</a>
  </p>
</div>

<style>
  div {
    animation: fadein 1s;
  }
  h2 {
    font-size: 1.5rem;
    font-weight: bold;
  }

  @keyframes fadein {
    from {
      opacity: 0;
    }
    to {
      opacity: 1;
    }
  }
</style>

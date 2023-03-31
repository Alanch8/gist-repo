<div id="top"></div>

# Gist-Repo

### Pre-commit Hook

To create a pre-commit hook and avoid unnecessary commits in the Main branch. Use the following pre-commit.sh file and save it in the .git/hooks/ folder of the project.

<script src="https://gist.github.com/Alanch8/841aaad9de838330a8b7923d3c773c24.js"></script>

First of all, run the following command to give administrator permissions to the file.

<script src="https://gist.github.com/Alanch8/90eaa229a04cb88dc5fc7b5e877ff64b.js"></script>

I think a good practice can be to create a script in the package.json file with the necessary command line and run it after the first commit.

<script src="https://gist.github.com/Alanch8/c219a1d98bf6d572a89174dd0423a504.js"></script>

---

Thanks for reading!

<p align="right"><a href="#top">🔝</a></p>

<p align="center">Aitor Lancharro "Alanch8" ☕</p>

<svg fill="none" viewBox="0 0 600 300" width="600" height="300" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">
      <style>
        @keyframes hi  {
            0% { transform: rotate( 0.0deg) }
           10% { transform: rotate(14.0deg) }
           20% { transform: rotate(-8.0deg) }
           30% { transform: rotate(14.0deg) }
           40% { transform: rotate(-4.0deg) }
           50% { transform: rotate(10.0deg) }
           60% { transform: rotate( 0.0deg) }
          100% { transform: rotate( 0.0deg) }
        }

        .container {
          background-color: black;

          width: 100%;
          height: 300px;

          display: flex;
          justify-content: center;
          align-items: center;
          color: white;

          font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
        }

        .hi {
          animation: hi 1.5s linear -0.5s infinite;
          display: inline-block;
          transform-origin: 70% 70%;
        }

        @media (prefers-reduced-motion) {
          .hi {
            animation: none;
          }
        }
      </style>

      <div class="container">
        <h1>Hi there, my name is Nikola <div class="hi">👋</div></h1>
      </div>
    </div>
  </foreignObject>
</svg>

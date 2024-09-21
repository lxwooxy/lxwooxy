
      <svg
        width="300"
        height="185"
        viewBox="0 0 300 185"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
        role="img"
        aria-labelledby="descId"
      >
        <title id="titleId"></title>
        <desc id="descId"></desc>
        <style>
          .header {
            font: 600 18px 'Segoe UI', Ubuntu, Sans-Serif;
            fill: #2f80ed;
            animation: fadeInAnimation 0.8s ease-in-out forwards;
          }
          @supports(-moz-appearance: auto) {
            /* Selector detects Firefox */
            .header { font-size: 15.5px; }
          }
          
    @keyframes slideInAnimation {
      from {
        width: 0;
      }
      to {
        width: calc(100%-100px);
      }
    }
    @keyframes growWidthAnimation {
      from {
        width: 0;
      }
      to {
        width: 100%;
      }
    }
    .stat {
      font: 600 14px 'Segoe UI', Ubuntu, "Helvetica Neue", Sans-Serif; fill: #434d58;
    }
    @supports(-moz-appearance: auto) {
      /* Selector detects Firefox */
      .stat { font-size:12px; }
    }
    .bold { font-weight: 700 }
    .lang-name {
      font: 400 11px "Segoe UI", Ubuntu, Sans-Serif;
      fill: #434d58;
    }
    .stagger {
      opacity: 0;
      animation: fadeInAnimation 0.3s ease-in-out forwards;
    }
    #rect-mask rect{
      animation: slideInAnimation 1s ease-in-out forwards;
    }
    .lang-progress{
      animation: growWidthAnimation 0.6s ease-in-out forwards;
    }
    

          
      /* Animations */
      @keyframes scaleInAnimation {
        from {
          transform: translate(-5px, 5px) scale(0);
        }
        to {
          transform: translate(-5px, 5px) scale(1);
        }
      }
      @keyframes fadeInAnimation {
        from {
          opacity: 0;
        }
        to {
          opacity: 1;
        }
      }
    
          
        </style>

        

        <rect
          data-testid="card-bg"
          x="0.5"
          y="0.5"
          rx="4.5"
          height="99%"
          stroke="#e4e2e2"
          width="299"
          fill="#fffefe"
          stroke-opacity="1"
        />

        

        <g
          data-testid="main-card-body"
          transform="translate(0, 25)"
        >
          
    <svg data-testid="lang-items" x="25">
      
  
      <mask id="rect-mask">
          <rect x="0" y="0" width="250" height="8" fill="white" rx="5"/>
        </mask>
        
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="0"
          y="0"
          width="246.77"
          height="8"
          fill="#178600"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="246.77"
          y="0"
          width="11.55"
          height="8"
          fill="#DA5B0B"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="248.32000000000002"
          y="0"
          width="10.9"
          height="8"
          fill="#F05138"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="249.22000000000003"
          y="0"
          width="10.29"
          height="8"
          fill="#3572A5"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="249.51000000000002"
          y="0"
          width="10.21"
          height="8"
          fill="#222c37"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="249.72000000000003"
          y="0"
          width="10.11"
          height="8"
          fill="#f34b7d"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="249.83000000000004"
          y="0"
          width="10.06"
          height="8"
          fill="#e38c00"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="249.89000000000004"
          y="0"
          width="10.06"
          height="8"
          fill="#aace60"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="249.95000000000005"
          y="0"
          width="10.02"
          height="8"
          fill="#89e051"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="249.97000000000006"
          y="0"
          width="10.02"
          height="8"
          fill="#701516"
        />
      
      
    <g transform="translate(0, 25)">
      <g transform="translate(0, 0)"><g transform="translate(0, 0)">
    <g class="stagger" style="animation-delay: 450ms">
      <circle cx="5" cy="6" r="5" fill="#178600" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        C# 98.71%
      </text>
    </g>
  </g><g transform="translate(0, 25)">
    <g class="stagger" style="animation-delay: 600ms">
      <circle cx="5" cy="6" r="5" fill="#DA5B0B" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        Jupyter Notebook 0.62%
      </text>
    </g>
  </g><g transform="translate(0, 50)">
    <g class="stagger" style="animation-delay: 750ms">
      <circle cx="5" cy="6" r="5" fill="#F05138" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        Swift 0.36%
      </text>
    </g>
  </g><g transform="translate(0, 75)">
    <g class="stagger" style="animation-delay: 900ms">
      <circle cx="5" cy="6" r="5" fill="#3572A5" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        Python 0.12%
      </text>
    </g>
  </g><g transform="translate(0, 100)">
    <g class="stagger" style="animation-delay: 1050ms">
      <circle cx="5" cy="6" r="5" fill="#222c37" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        ShaderLab 0.09%
      </text>
    </g>
  </g></g><g transform="translate(150, 0)"><g transform="translate(0, 0)">
    <g class="stagger" style="animation-delay: 450ms">
      <circle cx="5" cy="6" r="5" fill="#f34b7d" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        C++ 0.04%
      </text>
    </g>
  </g><g transform="translate(0, 25)">
    <g class="stagger" style="animation-delay: 600ms">
      <circle cx="5" cy="6" r="5" fill="#e38c00" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        SQL 0.03%
      </text>
    </g>
  </g><g transform="translate(0, 50)">
    <g class="stagger" style="animation-delay: 750ms">
      <circle cx="5" cy="6" r="5" fill="#aace60" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        HLSL 0.02%
      </text>
    </g>
  </g><g transform="translate(0, 75)">
    <g class="stagger" style="animation-delay: 900ms">
      <circle cx="5" cy="6" r="5" fill="#89e051" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        Shell 0.01%
      </text>
    </g>
  </g><g transform="translate(0, 100)">
    <g class="stagger" style="animation-delay: 1050ms">
      <circle cx="5" cy="6" r="5" fill="#701516" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        Ruby 0.01%
      </text>
    </g>
  </g></g>
    </g>
  
    </svg>
  
        </g>
      </svg>
    
<svg width="1180" height="610" viewBox="0 0 1180 610" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" role="img" aria-label="Manav Garg profile banner"><defs>
    <clipPath id="outerRound"><rect x="0" y="0" width="1180" height="610" rx="24"/></clipPath>
    <clipPath id="leftPanelClip"><rect x="24" y="24" width="400" height="562" rx="16"/></clipPath>
    <clipPath id="rightPanelClip"><rect x="472" y="24" width="684" height="562" rx="16"/></clipPath>
    <clipPath id="headerClip"><rect x="472" y="24" width="684" height="40" rx="16"/></clipPath>
    
    <radialGradient id="glowA" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#7C3AED" stop-opacity="0.55"/>
      <stop offset="100%" stop-color="#7C3AED" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="glowB" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#0EA5E9" stop-opacity="0.45"/>
      <stop offset="100%" stop-color="#0EA5E9" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="glowC" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#10B981" stop-opacity="0.35"/>
      <stop offset="100%" stop-color="#10B981" stop-opacity="0"/>
    </radialGradient>
    
    <linearGradient id="asciiGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#7C3AED">
        <animate attributeName="stop-color" values="#7C3AED;#22D3EE;#10B981;#7C3AED" dur="9s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" stop-color="#22D3EE">
        <animate attributeName="stop-color" values="#22D3EE;#10B981;#7C3AED;#22D3EE" dur="9s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#10B981">
        <animate attributeName="stop-color" values="#10B981;#7C3AED;#22D3EE;#10B981" dur="9s" repeatCount="indefinite"/>
        <animate attributeName="offset" values="100%;115%;100%" dur="6s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    
    <linearGradient id="accentText" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#7C3AED"/>
      <stop offset="50%" stop-color="#22D3EE"/>
      <stop offset="100%" stop-color="#10B981"/>
    </linearGradient>
    
    <linearGradient id="shimmer" gradientUnits="userSpaceOnUse" x1="0" y1="0" x2="1180" y2="610">
      <stop offset="0%" stop-color="#22D3EE" stop-opacity="0"/>
      <stop offset="45%" stop-color="#22D3EE" stop-opacity="0"/>
      <stop offset="50%" stop-color="#22D3EE" stop-opacity="0.9"/>
      <stop offset="55%" stop-color="#22D3EE" stop-opacity="0"/>
      <stop offset="100%" stop-color="#22D3EE" stop-opacity="0"/>
      <animateTransform attributeName="gradientTransform" type="rotate"
        values="0 590 305;360 590 305" dur="7s" repeatCount="indefinite"/>
    </linearGradient>
    
    <linearGradient id="scanGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#22D3EE" stop-opacity="0"/>
      <stop offset="50%" stop-color="#22D3EE" stop-opacity="0.5"/>
      <stop offset="100%" stop-color="#22D3EE" stop-opacity="0"/>
    </linearGradient>
    
    <linearGradient id="scanGradLocal" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#7C3AED" stop-opacity="0"/>
      <stop offset="50%" stop-color="#7C3AED" stop-opacity="0.35"/>
      <stop offset="100%" stop-color="#7C3AED" stop-opacity="0"/>
    </linearGradient>
    
    <filter id="glow" x="-60%" y="-60%" width="220%" height="220%">
      <feGaussianBlur stdDeviation="3.2" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="glowSoft" x="-80%" y="-80%" width="260%" height="260%">
      <feGaussianBlur stdDeviation="8" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="blurBig" x="-100%" y="-100%" width="300%" height="300%">
      <feGaussianBlur stdDeviation="45"/>
    </filter>
    
    <filter id="noise">
      <feTurbulence type="fractalNoise" baseFrequency="0.85" numOctaves="2" stitchTiles="stitch" result="n"/>
      <feColorMatrix in="n" type="matrix"
        values="0 0 0 0 0.5  0 0 0 0 0.5  0 0 0 0 0.5  0 0 0 0.035 0"/>
    </filter>
    </defs><g clip-path="url(#outerRound)"><rect x="0" y="0" width="1180" height="610" fill="#030712"/>
    <g filter="url(#blurBig)" opacity="0.8">
      <circle cx="140" cy="120" r="160" fill="url(#glowA)">
        <animateTransform attributeName="transform" type="translate"
          values="0,0; 30,20; -10,35; 0,0" dur="22s" repeatCount="indefinite"/>
      </circle>
      <circle cx="980" cy="500" r="200" fill="url(#glowB)">
        <animateTransform attributeName="transform" type="translate"
          values="0,0; -25,-20; 15,-35; 0,0" dur="26s" repeatCount="indefinite"/>
      </circle>
      <circle cx="820" cy="80" r="150" fill="url(#glowC)">
        <animateTransform attributeName="transform" type="translate"
          values="0,0; -20,25; 20,10; 0,0" dur="19s" repeatCount="indefinite"/>
      </circle>
      <circle cx="250" cy="560" r="140" fill="url(#glowB)">
        <animateTransform attributeName="transform" type="translate"
          values="0,0; 18,-15; -18,10; 0,0" dur="24s" repeatCount="indefinite"/>
      </circle>
    </g>
    <rect x="0" y="0" width="1180" height="610" filter="url(#noise)"/><g><circle cx="703" cy="194" r="1.8" fill="#7C3AED" opacity="0">
          <animate attributeName="opacity" values="0;0.8;0.8;0" keyTimes="0;0.15;0.7;1" dur="9.4s" begin="0.6s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,0; 0,-26" dur="9.4s" begin="0.6s" repeatCount="indefinite"/>
        </circle><circle cx="158" cy="559" r="1.5" fill="#22D3EE" opacity="0">
          <animate attributeName="opacity" values="0;0.8;0.8;0" keyTimes="0;0.15;0.7;1" dur="9.7s" begin="0.4s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,0; 0,-34" dur="9.7s" begin="0.4s" repeatCount="indefinite"/>
        </circle><circle cx="225" cy="474" r="1.3" fill="#10B981" opacity="0">
          <animate attributeName="opacity" values="0;0.8;0.8;0" keyTimes="0;0.15;0.7;1" dur="13.5s" begin="3.8s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,0; 0,-46" dur="13.5s" begin="3.8s" repeatCount="indefinite"/>
        </circle><circle cx="166" cy="446" r="1.3" fill="#7C3AED" opacity="0">
          <animate attributeName="opacity" values="0;0.8;0.8;0" keyTimes="0;0.15;0.7;1" dur="10.8s" begin="5.2s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,0; 0,-25" dur="10.8s" begin="5.2s" repeatCount="indefinite"/>
        </circle><circle cx="633" cy="469" r="1.4" fill="#22D3EE" opacity="0">
          <animate attributeName="opacity" values="0;0.8;0.8;0" keyTimes="0;0.15;0.7;1" dur="9.9s" begin="3.4s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,0; 0,-41" dur="9.9s" begin="3.4s" repeatCount="indefinite"/>
        </circle><circle cx="410" cy="145" r="2.0" fill="#10B981" opacity="0">
          <animate attributeName="opacity" values="0;0.8;0.8;0" keyTimes="0;0.15;0.7;1" dur="14.1s" begin="0.6s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,0; 0,-37" dur="14.1s" begin="0.6s" repeatCount="indefinite"/>
        </circle><circle cx="168" cy="101" r="2.1" fill="#7C3AED" opacity="0">
          <animate attributeName="opacity" values="0;0.8;0.8;0" keyTimes="0;0.15;0.7;1" dur="13.0s" begin="2.6s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,0; 0,-26" dur="13.0s" begin="2.6s" repeatCount="indefinite"/>
        </circle><circle cx="683" cy="516" r="2.0" fill="#22D3EE" opacity="0">
          <animate attributeName="opacity" values="0;0.8;0.8;0" keyTimes="0;0.15;0.7;1" dur="12.6s" begin="1.5s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,0; 0,-41" dur="12.6s" begin="1.5s" repeatCount="indefinite"/>
        </circle><circle cx="408" cy="289" r="1.3" fill="#10B981" opacity="0">
          <animate attributeName="opacity" values="0;0.8;0.8;0" keyTimes="0;0.15;0.7;1" dur="11.4s" begin="5.3s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,0; 0,-29" dur="11.4s" begin="5.3s" repeatCount="indefinite"/>
        </circle><circle cx="959" cy="334" r="2.1" fill="#7C3AED" opacity="0">
          <animate attributeName="opacity" values="0;0.8;0.8;0" keyTimes="0;0.15;0.7;1" dur="9.6s" begin="2.5s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,0; 0,-28" dur="9.6s" begin="2.5s" repeatCount="indefinite"/>
        </circle><circle cx="740" cy="195" r="2.5" fill="#22D3EE" opacity="0">
          <animate attributeName="opacity" values="0;0.8;0.8;0" keyTimes="0;0.15;0.7;1" dur="12.4s" begin="4.6s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,0; 0,-56" dur="12.4s" begin="4.6s" repeatCount="indefinite"/>
        </circle><circle cx="682" cy="388" r="2.2" fill="#10B981" opacity="0">
          <animate attributeName="opacity" values="0;0.8;0.8;0" keyTimes="0;0.15;0.7;1" dur="13.8s" begin="4.8s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,0; 0,-23" dur="13.8s" begin="4.8s" repeatCount="indefinite"/>
        </circle><circle cx="180" cy="135" r="2.5" fill="#7C3AED" opacity="0">
          <animate attributeName="opacity" values="0;0.8;0.8;0" keyTimes="0;0.15;0.7;1" dur="12.8s" begin="0.4s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,0; 0,-56" dur="12.8s" begin="0.4s" repeatCount="indefinite"/>
        </circle><circle cx="674" cy="496" r="1.6" fill="#22D3EE" opacity="0">
          <animate attributeName="opacity" values="0;0.8;0.8;0" keyTimes="0;0.15;0.7;1" dur="12.1s" begin="0.1s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,0; 0,-38" dur="12.1s" begin="0.1s" repeatCount="indefinite"/>
        </circle></g>
    <rect x="0" y="-40" width="1180" height="14" fill="url(#scanGrad)" opacity="0.5">
      <animateTransform attributeName="transform" type="translate"
        values="0,0; 0,650" dur="7s" repeatCount="indefinite"/>
    </rect>
    
    <rect x="24" y="24" width="400" height="562" rx="16" fill="#0F172A" fill-opacity="0.55"
      stroke="#2A3348" stroke-width="1"/>
    <g clip-path="url(#leftPanelClip)">
    <rect x="24" y="-60" width="400" height="18" fill="url(#scanGradLocal)" opacity="0.6">
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,646" dur="5s" repeatCount="indefinite"/>
    </rect>
    <g><animateTransform attributeName="transform" type="translate" values="0,0; 0,-4; 0,0; 0,3; 0,0" dur="7s" repeatCount="indefinite"/><g filter="url(#glow)"><text x="48" y="66.0" font-family="Consolas, 'SF Mono', Menlo, monospace" font-size="10.6" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">        .:=+*#%@%#*+=:.<animate attributeName="opacity" from="0" to="1" begin="0.15s" dur="0.35s" fill="freeze"/></text><text x="48" y="81.4" font-family="Consolas, 'SF Mono', Menlo, monospace" font-size="10.6" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">      :+%@@@@@@@@@@@@@%+:<animate attributeName="opacity" from="0" to="1" begin="0.24s" dur="0.35s" fill="freeze"/></text><text x="48" y="96.8" font-family="Consolas, 'SF Mono', Menlo, monospace" font-size="10.6" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">    .*@@@@@@@@@@@@@@@@@@@*.<animate attributeName="opacity" from="0" to="1" begin="0.33s" dur="0.35s" fill="freeze"/></text><text x="48" y="112.2" font-family="Consolas, 'SF Mono', Menlo, monospace" font-size="10.6" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">   =@@@@@@@@@@@@@@@@@@@@@@=<animate attributeName="opacity" from="0" to="1" begin="0.42s" dur="0.35s" fill="freeze"/></text><text x="48" y="127.6" font-family="Consolas, 'SF Mono', Menlo, monospace" font-size="10.6" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">  +@@@@@@@##@@@@@@##@@@@@@+<animate attributeName="opacity" from="0" to="1" begin="0.51s" dur="0.35s" fill="freeze"/></text><text x="48" y="143.0" font-family="Consolas, 'SF Mono', Menlo, monospace" font-size="10.6" fill="url(#asciiGrad)" opacity="0" xml:space="preserve"> :@@@@@@@#  @@@@@@  #@@@@@@:<animate attributeName="opacity" from="0" to="1" begin="0.6s" dur="0.35s" fill="freeze"/></text><text x="48" y="158.4" font-family="Consolas, 'SF Mono', Menlo, monospace" font-size="10.6" fill="url(#asciiGrad)" opacity="0" xml:space="preserve"> %@@@@@@@#  @@@@@@  #@@@@@@%<animate attributeName="opacity" from="0" to="1" begin="0.69s" dur="0.35s" fill="freeze"/></text><text x="48" y="173.8" font-family="Consolas, 'SF Mono', Menlo, monospace" font-size="10.6" fill="url(#asciiGrad)" opacity="0" xml:space="preserve"> %@@@@@@@@##@@@@@@##@@@@@@@%<animate attributeName="opacity" from="0" to="1" begin="0.78s" dur="0.35s" fill="freeze"/></text><text x="48" y="189.2" font-family="Consolas, 'SF Mono', Menlo, monospace" font-size="10.6" fill="url(#asciiGrad)" opacity="0" xml:space="preserve"> :@@@@@@@@@@@@@@@@@@@@@@@@@:<animate attributeName="opacity" from="0" to="1" begin="0.87s" dur="0.35s" fill="freeze"/></text><text x="48" y="204.6" font-family="Consolas, 'SF Mono', Menlo, monospace" font-size="10.6" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">  +@@@@@@@@@@@@@@@@@@@@@@@+<animate attributeName="opacity" from="0" to="1" begin="0.96s" dur="0.35s" fill="freeze"/></text><text x="48" y="220.0" font-family="Consolas, 'SF Mono', Menlo, monospace" font-size="10.6" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">   =@@@@@%%%%%%%%%%%%@@@@=<animate attributeName="opacity" from="0" to="1" begin="1.05s" dur="0.35s" fill="freeze"/></text><text x="48" y="235.4" font-family="Consolas, 'SF Mono', Menlo, monospace" font-size="10.6" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">    .*@@@@%%%%%%%%%%@@@@*.<animate attributeName="opacity" from="0" to="1" begin="1.14s" dur="0.35s" fill="freeze"/></text><text x="48" y="250.8" font-family="Consolas, 'SF Mono', Menlo, monospace" font-size="10.6" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">      :+%@@%%%%%%%%@@%+:<animate attributeName="opacity" from="0" to="1" begin="1.23s" dur="0.35s" fill="freeze"/></text><text x="48" y="266.2" font-family="Consolas, 'SF Mono', Menlo, monospace" font-size="10.6" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">        .:=+*#%%#*+=:.<animate attributeName="opacity" from="0" to="1" begin="1.32s" dur="0.35s" fill="freeze"/></text><text x="48" y="281.6" font-family="Consolas, 'SF Mono', Menlo, monospace" font-size="10.6" fill="url(#asciiGrad)" opacity="0" xml:space="preserve"><animate attributeName="opacity" from="0" to="1" begin="1.41s" dur="0.35s" fill="freeze"/></text><text x="48" y="297.0" font-family="Consolas, 'SF Mono', Menlo, monospace" font-size="10.6" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">     &amp;lt; MANAV_GARG.SYS &amp;gt;<animate attributeName="opacity" from="0" to="1" begin="1.5s" dur="0.35s" fill="freeze"/></text><text x="48" y="312.4" font-family="Consolas, 'SF Mono', Menlo, monospace" font-size="10.6" fill="url(#asciiGrad)" opacity="0" xml:space="preserve">   [ BACKEND :: AGENTIC_AI ]<animate attributeName="opacity" from="0" to="1" begin="1.59s" dur="0.35s" fill="freeze"/></text></g></g>
    <text x="48" y="331.8" font-family="Consolas, monospace" font-size="10.6" fill="#22D3EE" opacity="0">
      STATUS: ONLINE
      <animate attributeName="opacity" from="0" to="1" begin="1.9s" dur="0.3s" fill="freeze"/>
    </text>
    <rect x="126" y="322.8" width="7" height="11" fill="#22D3EE" opacity="0">
      <animate attributeName="opacity" values="0;0;1;1;0" keyTimes="0;0.27;0.28;0.63;0.64" begin="0s" dur="1.1s" repeatCount="indefinite"/>
    </rect>
    
    <rect x="48" y="357.8" width="352" height="1" fill="#2A3348" opacity="0">
      <animate attributeName="opacity" from="0" to="0.8" begin="2.1s" dur="0.4s" fill="freeze"/>
    </rect>
    <text x="48" y="379.8" font-family="Consolas, monospace" font-size="10.5" letter-spacing="2"
      fill="#94A3B8" opacity="0">SYSTEM METRICS
      <animate attributeName="opacity" from="0" to="1" begin="2.3s" dur="0.4s" fill="freeze"/>
    </text>
    
        <g opacity="0">
          <animate attributeName="opacity" from="0" to="1" begin="2.5s" dur="0.4s" fill="freeze"/>
          <text x="48" y="401.8" font-family="Consolas, monospace" font-size="10.5" fill="#F8FAFC">APIs shipped</text>
          <text x="370" y="401.8" text-anchor="end" font-family="Consolas, monospace" font-size="10.5" fill="#22D3EE">40+</text>
          <rect x="48" y="408.8" width="220" height="4" rx="2" fill="#2A3348"/>
          <rect x="48" y="408.8" width="0" height="4" rx="2" fill="url(#accentText)" filter="url(#glow)">
            <animate attributeName="width" from="0" to="202.4" begin="2.65s" dur="1.1s" fill="freeze" calcMode="spline" keySplines="0.16 1 0.3 1"/>
          </rect>
        </g>
        
        <g opacity="0">
          <animate attributeName="opacity" from="0" to="1" begin="2.7s" dur="0.4s" fill="freeze"/>
          <text x="48" y="435.8" font-family="Consolas, monospace" font-size="10.5" fill="#F8FAFC">Latency cut</text>
          <text x="370" y="435.8" text-anchor="end" font-family="Consolas, monospace" font-size="10.5" fill="#22D3EE">-42%</text>
          <rect x="48" y="442.8" width="220" height="4" rx="2" fill="#2A3348"/>
          <rect x="48" y="442.8" width="0" height="4" rx="2" fill="url(#accentText)" filter="url(#glow)">
            <animate attributeName="width" from="0" to="171.6" begin="2.85s" dur="1.1s" fill="freeze" calcMode="spline" keySplines="0.16 1 0.3 1"/>
          </rect>
        </g>
        
        <g opacity="0">
          <animate attributeName="opacity" from="0" to="1" begin="2.9s" dur="0.4s" fill="freeze"/>
          <text x="48" y="469.8" font-family="Consolas, monospace" font-size="10.5" fill="#F8FAFC">Alpha users served</text>
          <text x="370" y="469.8" text-anchor="end" font-family="Consolas, monospace" font-size="10.5" fill="#22D3EE">1.6k+</text>
          <rect x="48" y="476.8" width="220" height="4" rx="2" fill="#2A3348"/>
          <rect x="48" y="476.8" width="0" height="4" rx="2" fill="url(#accentText)" filter="url(#glow)">
            <animate attributeName="width" from="0" to="187.0" begin="3.05s" dur="1.1s" fill="freeze" calcMode="spline" keySplines="0.16 1 0.3 1"/>
          </rect>
        </g>
        </g>
    <rect x="472" y="24" width="684" height="562" rx="16" fill="#0F172A" fill-opacity="0.55"
      stroke="#2A3348" stroke-width="1"/>
    <g clip-path="url(#rightPanelClip)"><g clip-path="url(#headerClip)"><rect x="472" y="24" width="684" height="40" fill="#0B1220"/>
    <circle cx="500" cy="44" r="6" fill="#FF5F56"/>
    <circle cx="522" cy="44" r="6" fill="#FFBD2E"/>
    <circle cx="544" cy="44" r="6" fill="#27C93F"/>
    <text x="1128" y="48" text-anchor="end" font-family="Consolas, monospace" font-size="11.5" fill="#94A3B8">manav2k7@dev:~$</text>
    </g><rect x="472" y="63.5" width="684" height="1" fill="#2A3348"/>
    <clipPath id="greetClip">
      <rect x="504" y="90" width="0" height="34">
        <animate attributeName="width" from="0" to="430" begin="0.5s" dur="1.6s" fill="freeze" calcMode="spline" keySplines="0.2 0.9 0.3 1"/>
      </rect>
    </clipPath>
    <g clip-path="url(#greetClip)">
      <text x="508" y="115" font-family="Consolas, 'SF Mono', monospace" font-size="27" font-weight="700" fill="#F8FAFC">Hi 👋 I'm Manav Garg</text>
    </g>
    <rect x="940" y="90" width="3" height="30" fill="#22D3EE" opacity="0">
      <animate attributeName="opacity" values="0;0;1;1;0" keyTimes="0;0.0;0.5;0.95;1" begin="0.4s" dur="2.1s" fill="freeze"/>
    </rect>
    <text x="508" y="158" font-family="Consolas, monospace" font-size="18" fill="url(#accentText)">❯ </text>
        <clipPath id="roleClip1">
          <rect x="526" y="142" height="24" width="0">
            <animate id="type1" attributeName="width" from="0" to="166" begin="1.2s;hide4.end+0.45s" dur="0.9s" fill="freeze" calcMode="spline" keySplines="0.3 0.9 0.3 1"/>
            <animate id="hide1" attributeName="width" from="166" to="0" begin="type1.end+2.1s" dur="0.35s" fill="freeze"/>
          </rect>
        </clipPath>
        
        <clipPath id="roleClip2">
          <rect x="526" y="142" height="24" width="0">
            <animate id="type2" attributeName="width" from="0" to="187" begin="hide1.end+0.45s" dur="0.9s" fill="freeze" calcMode="spline" keySplines="0.3 0.9 0.3 1"/>
            <animate id="hide2" attributeName="width" from="187" to="0" begin="type2.end+2.1s" dur="0.35s" fill="freeze"/>
          </rect>
        </clipPath>
        
        <clipPath id="roleClip3">
          <rect x="526" y="142" height="24" width="0">
            <animate id="type3" attributeName="width" from="0" to="301" begin="hide2.end+0.45s" dur="0.9s" fill="freeze" calcMode="spline" keySplines="0.3 0.9 0.3 1"/>
            <animate id="hide3" attributeName="width" from="301" to="0" begin="type3.end+2.1s" dur="0.35s" fill="freeze"/>
          </rect>
        </clipPath>
        
        <clipPath id="roleClip4">
          <rect x="526" y="142" height="24" width="0">
            <animate id="type4" attributeName="width" from="0" to="239" begin="hide3.end+0.45s" dur="0.9s" fill="freeze" calcMode="spline" keySplines="0.3 0.9 0.3 1"/>
            <animate id="hide4" attributeName="width" from="239" to="0" begin="type4.end+2.1s" dur="0.35s" fill="freeze"/>
          </rect>
        </clipPath>
        <g clip-path="url(#roleClip1)"><text x="526" y="158" font-family="Consolas, monospace" font-size="18" fill="#F8FAFC">Backend Engineer</text></g><g clip-path="url(#roleClip2)"><text x="526" y="158" font-family="Consolas, monospace" font-size="18" fill="#F8FAFC">Spring Boot + Java</text></g><g clip-path="url(#roleClip3)"><text x="526" y="158" font-family="Consolas, monospace" font-size="18" fill="#F8FAFC">Building Autonomous AI Agents</text></g><g clip-path="url(#roleClip4)"><text x="526" y="158" font-family="Consolas, monospace" font-size="18" fill="#F8FAFC">Open Source Contributor</text></g>
    <rect x="836" y="143" width="3" height="21" fill="#22D3EE">
      <animate attributeName="opacity" values="1;1;0;0" keyTimes="0;0.5;0.5;1" dur="1s" repeatCount="indefinite"/>
    </rect>
    
        <g opacity="0">
          <animate attributeName="opacity" from="0" to="1" begin="2.6s" dur="0.5s" fill="freeze"/>
          <animateTransform attributeName="transform" type="translate" from="-14,0" to="0,0" begin="2.6s" dur="0.5s" fill="freeze" calcMode="spline" keySplines="0.2 0.9 0.3 1"/>
          <text x="508" y="208" font-family="Consolas, monospace" font-size="14.5" fill="#F8FAFC">🎓</text>
          <text x="534" y="208" font-family="Consolas, monospace" font-size="13" fill="#94A3B8">education:</text>
          <text x="638" y="208" font-family="Consolas, monospace" font-size="13.5" fill="#F8FAFC">B.Tech CSE @ ADGIPS ('28)</text>
        </g>
        
        <g opacity="0">
          <animate attributeName="opacity" from="0" to="1" begin="2.88s" dur="0.5s" fill="freeze"/>
          <animateTransform attributeName="transform" type="translate" from="-14,0" to="0,0" begin="2.88s" dur="0.5s" fill="freeze" calcMode="spline" keySplines="0.2 0.9 0.3 1"/>
          <text x="508" y="240" font-family="Consolas, monospace" font-size="14.5" fill="#F8FAFC">💼</text>
          <text x="534" y="240" font-family="Consolas, monospace" font-size="13" fill="#94A3B8">experience:</text>
          <text x="638" y="240" font-family="Consolas, monospace" font-size="13.5" fill="#F8FAFC">SWE Intern @ Aigram, GymCartel</text>
        </g>
        
        <g opacity="0">
          <animate attributeName="opacity" from="0" to="1" begin="3.16s" dur="0.5s" fill="freeze"/>
          <animateTransform attributeName="transform" type="translate" from="-14,0" to="0,0" begin="3.16s" dur="0.5s" fill="freeze" calcMode="spline" keySplines="0.2 0.9 0.3 1"/>
          <text x="508" y="272" font-family="Consolas, monospace" font-size="14.5" fill="#F8FAFC">💡</text>
          <text x="534" y="272" font-family="Consolas, monospace" font-size="13" fill="#94A3B8">focus:</text>
          <text x="638" y="272" font-family="Consolas, monospace" font-size="13.5" fill="#F8FAFC">Agentic AI · LangGraph · MCP</text>
        </g>
        
        <g opacity="0">
          <animate attributeName="opacity" from="0" to="1" begin="3.44s" dur="0.5s" fill="freeze"/>
          <animateTransform attributeName="transform" type="translate" from="-14,0" to="0,0" begin="3.44s" dur="0.5s" fill="freeze" calcMode="spline" keySplines="0.2 0.9 0.3 1"/>
          <text x="508" y="304" font-family="Consolas, monospace" font-size="14.5" fill="#F8FAFC">🐙</text>
          <text x="534" y="304" font-family="Consolas, monospace" font-size="13" fill="#94A3B8">dsa:</text>
          <text x="638" y="304" font-family="Consolas, monospace" font-size="13.5" fill="#F8FAFC">350+ problems solved</text>
        </g>
        
        <g opacity="0">
          <animate attributeName="opacity" from="0" to="1" begin="3.72s" dur="0.5s" fill="freeze"/>
          <animateTransform attributeName="transform" type="translate" from="-14,0" to="0,0" begin="3.72s" dur="0.5s" fill="freeze" calcMode="spline" keySplines="0.2 0.9 0.3 1"/>
          <text x="508" y="336" font-family="Consolas, monospace" font-size="14.5" fill="#F8FAFC">✉</text>
          <text x="534" y="336" font-family="Consolas, monospace" font-size="13" fill="#94A3B8">email:</text>
          <text x="638" y="336" font-family="Consolas, monospace" font-size="13.5" fill="#F8FAFC">manavgarg745@gmail.com</text>
        </g>
        
    <text x="508" y="388" font-family="Consolas, monospace" font-size="13.5" letter-spacing="1.5"
      fill="#94A3B8" opacity="0">SKILLS
      <animate attributeName="opacity" from="0" to="1" begin="4.30s" dur="0.4s" fill="freeze"/>
    </text>
    
        <g opacity="0" transform="translate(508,408)">
          <animate attributeName="opacity" from="0" to="1" begin="4.55s" dur="0.4s" fill="freeze"/>
          <animateTransform attributeName="transform" type="scale" additive="sum" from="0.9 0.9" to="1 1"
            begin="4.55s" dur="0.4s" fill="freeze" calcMode="spline" keySplines="0.3 1 0.3 1"/>
          <rect x="0" y="0" width="59" height="28" rx="14" fill="#0B1220" stroke="url(#accentText)" stroke-width="1" filter="url(#glow)">
            <animate attributeName="stroke-opacity" values="0.55;1;0.55" dur="3.4s" begin="5.05s" repeatCount="indefinite"/>
          </rect>
          <text x="29.5" y="18.2" text-anchor="middle" font-family="Consolas, monospace" font-size="12" fill="#F8FAFC">Java</text>
        </g>
        
        <g opacity="0" transform="translate(577,408)">
          <animate attributeName="opacity" from="0" to="1" begin="4.64s" dur="0.4s" fill="freeze"/>
          <animateTransform attributeName="transform" type="scale" additive="sum" from="0.9 0.9" to="1 1"
            begin="4.64s" dur="0.4s" fill="freeze" calcMode="spline" keySplines="0.3 1 0.3 1"/>
          <rect x="0" y="0" width="111" height="28" rx="14" fill="#0B1220" stroke="url(#accentText)" stroke-width="1" filter="url(#glow)">
            <animate attributeName="stroke-opacity" values="0.55;1;0.55" dur="3.4s" begin="5.14s" repeatCount="indefinite"/>
          </rect>
          <text x="55.5" y="18.2" text-anchor="middle" font-family="Consolas, monospace" font-size="12" fill="#F8FAFC">Spring Boot</text>
        </g>
        
        <g opacity="0" transform="translate(698,408)">
          <animate attributeName="opacity" from="0" to="1" begin="4.73s" dur="0.4s" fill="freeze"/>
          <animateTransform attributeName="transform" type="scale" additive="sum" from="0.9 0.9" to="1 1"
            begin="4.73s" dur="0.4s" fill="freeze" calcMode="spline" keySplines="0.3 1 0.3 1"/>
          <rect x="0" y="0" width="74" height="28" rx="14" fill="#0B1220" stroke="url(#accentText)" stroke-width="1" filter="url(#glow)">
            <animate attributeName="stroke-opacity" values="0.55;1;0.55" dur="3.4s" begin="5.23s" repeatCount="indefinite"/>
          </rect>
          <text x="37.0" y="18.2" text-anchor="middle" font-family="Consolas, monospace" font-size="12" fill="#F8FAFC">Python</text>
        </g>
        
        <g opacity="0" transform="translate(782,408)">
          <animate attributeName="opacity" from="0" to="1" begin="4.82s" dur="0.4s" fill="freeze"/>
          <animateTransform attributeName="transform" type="scale" additive="sum" from="0.9 0.9" to="1 1"
            begin="4.82s" dur="0.4s" fill="freeze" calcMode="spline" keySplines="0.3 1 0.3 1"/>
          <rect x="0" y="0" width="104" height="28" rx="14" fill="#0B1220" stroke="url(#accentText)" stroke-width="1" filter="url(#glow)">
            <animate attributeName="stroke-opacity" values="0.55;1;0.55" dur="3.4s" begin="5.32s" repeatCount="indefinite"/>
          </rect>
          <text x="52.0" y="18.2" text-anchor="middle" font-family="Consolas, monospace" font-size="12" fill="#F8FAFC">PostgreSQL</text>
        </g>
        
        <g opacity="0" transform="translate(896,408)">
          <animate attributeName="opacity" from="0" to="1" begin="4.91s" dur="0.4s" fill="freeze"/>
          <animateTransform attributeName="transform" type="scale" additive="sum" from="0.9 0.9" to="1 1"
            begin="4.91s" dur="0.4s" fill="freeze" calcMode="spline" keySplines="0.3 1 0.3 1"/>
          <rect x="0" y="0" width="67" height="28" rx="14" fill="#0B1220" stroke="url(#accentText)" stroke-width="1" filter="url(#glow)">
            <animate attributeName="stroke-opacity" values="0.55;1;0.55" dur="3.4s" begin="5.41s" repeatCount="indefinite"/>
          </rect>
          <text x="33.5" y="18.2" text-anchor="middle" font-family="Consolas, monospace" font-size="12" fill="#F8FAFC">Redis</text>
        </g>
        
        <g opacity="0" transform="translate(973,408)">
          <animate attributeName="opacity" from="0" to="1" begin="5.0s" dur="0.4s" fill="freeze"/>
          <animateTransform attributeName="transform" type="scale" additive="sum" from="0.9 0.9" to="1 1"
            begin="5.0s" dur="0.4s" fill="freeze" calcMode="spline" keySplines="0.3 1 0.3 1"/>
          <rect x="0" y="0" width="74" height="28" rx="14" fill="#0B1220" stroke="url(#accentText)" stroke-width="1" filter="url(#glow)">
            <animate attributeName="stroke-opacity" values="0.55;1;0.55" dur="3.4s" begin="5.5s" repeatCount="indefinite"/>
          </rect>
          <text x="37.0" y="18.2" text-anchor="middle" font-family="Consolas, monospace" font-size="12" fill="#F8FAFC">Docker</text>
        </g>
        
        <g opacity="0" transform="translate(508,448)">
          <animate attributeName="opacity" from="0" to="1" begin="5.09s" dur="0.4s" fill="freeze"/>
          <animateTransform attributeName="transform" type="scale" additive="sum" from="0.9 0.9" to="1 1"
            begin="5.09s" dur="0.4s" fill="freeze" calcMode="spline" keySplines="0.3 1 0.3 1"/>
          <rect x="0" y="0" width="96" height="28" rx="14" fill="#0B1220" stroke="url(#accentText)" stroke-width="1" filter="url(#glow)">
            <animate attributeName="stroke-opacity" values="0.55;1;0.55" dur="3.4s" begin="5.59s" repeatCount="indefinite"/>
          </rect>
          <text x="48.0" y="18.2" text-anchor="middle" font-family="Consolas, monospace" font-size="12" fill="#F8FAFC">LangGraph</text>
        </g>
        
        <g opacity="0" transform="translate(614,448)">
          <animate attributeName="opacity" from="0" to="1" begin="5.18s" dur="0.4s" fill="freeze"/>
          <animateTransform attributeName="transform" type="scale" additive="sum" from="0.9 0.9" to="1 1"
            begin="5.18s" dur="0.4s" fill="freeze" calcMode="spline" keySplines="0.3 1 0.3 1"/>
          <rect x="0" y="0" width="52" height="28" rx="14" fill="#0B1220" stroke="url(#accentText)" stroke-width="1" filter="url(#glow)">
            <animate attributeName="stroke-opacity" values="0.55;1;0.55" dur="3.4s" begin="5.68s" repeatCount="indefinite"/>
          </rect>
          <text x="26.0" y="18.2" text-anchor="middle" font-family="Consolas, monospace" font-size="12" fill="#F8FAFC">RAG</text>
        </g>
        
        <g opacity="0" transform="translate(676,448)">
          <animate attributeName="opacity" from="0" to="1" begin="5.27s" dur="0.4s" fill="freeze"/>
          <animateTransform attributeName="transform" type="scale" additive="sum" from="0.9 0.9" to="1 1"
            begin="5.27s" dur="0.4s" fill="freeze" calcMode="spline" keySplines="0.3 1 0.3 1"/>
          <rect x="0" y="0" width="52" height="28" rx="14" fill="#0B1220" stroke="url(#accentText)" stroke-width="1" filter="url(#glow)">
            <animate attributeName="stroke-opacity" values="0.55;1;0.55" dur="3.4s" begin="5.77s" repeatCount="indefinite"/>
          </rect>
          <text x="26.0" y="18.2" text-anchor="middle" font-family="Consolas, monospace" font-size="12" fill="#F8FAFC">MCP</text>
        </g>
        
        <g opacity="0" transform="translate(738,448)">
          <animate attributeName="opacity" from="0" to="1" begin="5.36s" dur="0.4s" fill="freeze"/>
          <animateTransform attributeName="transform" type="scale" additive="sum" from="0.9 0.9" to="1 1"
            begin="5.36s" dur="0.4s" fill="freeze" calcMode="spline" keySplines="0.3 1 0.3 1"/>
          <rect x="0" y="0" width="52" height="28" rx="14" fill="#0B1220" stroke="url(#accentText)" stroke-width="1" filter="url(#glow)">
            <animate attributeName="stroke-opacity" values="0.55;1;0.55" dur="3.4s" begin="5.86s" repeatCount="indefinite"/>
          </rect>
          <text x="26.0" y="18.2" text-anchor="middle" font-family="Consolas, monospace" font-size="12" fill="#F8FAFC">Git</text>
        </g>
        
        <g opacity="0" transform="translate(800,448)">
          <animate attributeName="opacity" from="0" to="1" begin="5.45s" dur="0.4s" fill="freeze"/>
          <animateTransform attributeName="transform" type="scale" additive="sum" from="0.9 0.9" to="1 1"
            begin="5.45s" dur="0.4s" fill="freeze" calcMode="spline" keySplines="0.3 1 0.3 1"/>
          <rect x="0" y="0" width="52" height="28" rx="14" fill="#0B1220" stroke="url(#accentText)" stroke-width="1" filter="url(#glow)">
            <animate attributeName="stroke-opacity" values="0.55;1;0.55" dur="3.4s" begin="5.95s" repeatCount="indefinite"/>
          </rect>
          <text x="26.0" y="18.2" text-anchor="middle" font-family="Consolas, monospace" font-size="12" fill="#F8FAFC">AWS</text>
        </g>
        
        <g opacity="0" transform="translate(514,555)">
          <animate attributeName="opacity" from="0" to="1" begin="6.04s" dur="0.45s" fill="freeze"/>
          <circle r="18" fill="#0B1220" stroke="#2A3348" stroke-width="1" filter="url(#glowSoft)">
            <animate attributeName="stroke" values="#2A3348;#22D3EE;#2A3348" dur="4s" begin="6.64s" repeatCount="indefinite"/>
          </circle>
          <text x="0" y="4.5" text-anchor="middle" font-family="Consolas, monospace" font-size="11.5" font-weight="700" fill="#F8FAFC">GH</text>
        </g>
        
        <g opacity="0" transform="translate(572,555)">
          <animate attributeName="opacity" from="0" to="1" begin="6.16s" dur="0.45s" fill="freeze"/>
          <circle r="18" fill="#0B1220" stroke="#2A3348" stroke-width="1" filter="url(#glowSoft)">
            <animate attributeName="stroke" values="#2A3348;#22D3EE;#2A3348" dur="4s" begin="6.76s" repeatCount="indefinite"/>
          </circle>
          <text x="0" y="4.5" text-anchor="middle" font-family="Consolas, monospace" font-size="11.5" font-weight="700" fill="#F8FAFC">in</text>
        </g>
        
        <g opacity="0" transform="translate(630,555)">
          <animate attributeName="opacity" from="0" to="1" begin="6.28s" dur="0.45s" fill="freeze"/>
          <circle r="18" fill="#0B1220" stroke="#2A3348" stroke-width="1" filter="url(#glowSoft)">
            <animate attributeName="stroke" values="#2A3348;#22D3EE;#2A3348" dur="4s" begin="6.88s" repeatCount="indefinite"/>
          </circle>
          <text x="0" y="4.5" text-anchor="middle" font-family="Consolas, monospace" font-size="11.5" font-weight="700" fill="#F8FAFC">IG</text>
        </g>
        
        <g opacity="0" transform="translate(688,555)">
          <animate attributeName="opacity" from="0" to="1" begin="6.4s" dur="0.45s" fill="freeze"/>
          <circle r="18" fill="#0B1220" stroke="#2A3348" stroke-width="1" filter="url(#glowSoft)">
            <animate attributeName="stroke" values="#2A3348;#22D3EE;#2A3348" dur="4s" begin="7.0s" repeatCount="indefinite"/>
          </circle>
          <text x="0" y="4.5" text-anchor="middle" font-family="Consolas, monospace" font-size="11.5" font-weight="700" fill="#F8FAFC">✉</text>
        </g>
        </g>
    <rect x="1" y="1" width="1178" height="608" rx="23" fill="none" stroke="rgba(255,255,255,0.08)" stroke-width="1.5"/>
    <rect x="1" y="1" width="1178" height="608" rx="23" fill="none" stroke="url(#shimmer)" stroke-width="1.5"/>
    </g></svg>

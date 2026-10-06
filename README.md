<img width="750" height="438" alt="crt-750x438(1)" src="https://github.com/user-attachments/assets/ea3fe47d-08f8-46a3-be93-e4b285ffdf31" />
<?xml version="1.0" encoding="UTF-8"?>
<svg xmlns="http://www.w3.org/2000/svg" width="750" height="438" viewBox="0 0 720 405" role="img" aria-label="CRT resume" preserveAspectRatio="none">
  <defs>
    <linearGradient id="screen-base" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0" stop-color="#06140d"/>
      <stop offset="0.48" stop-color="#03100a"/>
      <stop offset="1" stop-color="#010604"/>
    </linearGradient>
    <radialGradient id="screen-sheen" cx="50%" cy="16%" r="58%">
      <stop offset="0" stop-color="#7dffc0" stop-opacity="0.055"/>
      <stop offset="44%" stop-color="#38d782" stop-opacity="0.018"/>
      <stop offset="100%" stop-color="#001008" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="screen-vignette" cx="50%" cy="48%" r="73%">
      <stop offset="46%" stop-color="#000" stop-opacity="0"/>
      <stop offset="76%" stop-color="#000" stop-opacity="0.18"/>
      <stop offset="100%" stop-color="#000" stop-opacity="0.82"/>
    </radialGradient>
    <linearGradient id="rolling-bar-fill" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0" stop-color="#8dffc1" stop-opacity="0"/>
      <stop offset="0.44" stop-color="#8dffc1" stop-opacity="0.018"/>
      <stop offset="0.70" stop-color="#8dffc1" stop-opacity="0.07"/>
      <stop offset="1" stop-color="#8dffc1" stop-opacity="0"/>
    </linearGradient>
    <pattern id="scanline-pattern" width="720" height="2" patternUnits="userSpaceOnUse">
      <rect width="720" height="0.58" fill="#c9ffda" opacity="0.028"/>
      <rect y="0.92" width="720" height="1.08" fill="#000" opacity="0.30"/>
      <animateTransform attributeName="patternTransform" type="translate" from="0 0" to="0 2" dur="0.42s" repeatCount="indefinite"/>
    </pattern>
    <pattern id="phosphor-grille" width="1.5" height="4" patternUnits="userSpaceOnUse">
      <rect width="0.5" height="4" fill="#ff6f64" opacity="0.11"/>
      <rect x="0.5" width="0.5" height="4" fill="#5cff9b" opacity="0.13"/>
      <rect x="1" width="0.5" height="4" fill="#629cff" opacity="0.10"/>
      <path d="M0.48 0V4M0.98 0V4" stroke="#000" stroke-width="0.12" stroke-opacity="0.42"/>
      <rect y="3.25" width="1.5" height="0.75" fill="#000" opacity="0.22"/>
    </pattern>
    <filter id="chromatic-aberration" x="-4%" y="-5%" width="108%" height="110%" color-interpolation-filters="sRGB">
      <feColorMatrix in="SourceGraphic" type="matrix" values="1 0 0 0 0  0 0 0 0 0  0 0 0 0 0  0 0 0 1 0" result="red"/>
      <feOffset in="red" dx="-0.62" dy="0.08" result="red-shift"/>
      <feColorMatrix in="SourceGraphic" type="matrix" values="0 0 0 0 0  0 0 0 0 0  0 0 1 0 0  0 0 0 1 0" result="blue"/>
      <feOffset in="blue" dx="0.62" dy="-0.08" result="blue-shift"/>
      <feBlend in="red-shift" in2="blue-shift" mode="screen"/>
    </filter>
    <filter id="phosphor-bloom" x="-16%" y="-28%" width="132%" height="156%" color-interpolation-filters="sRGB">
      <feGaussianBlur in="SourceGraphic" stdDeviation="5.2" result="wide-blur"/>
      <feComponentTransfer in="wide-blur" result="wide-glow"><feFuncA type="linear" slope="0.62"/></feComponentTransfer>
      <feGaussianBlur in="SourceGraphic" stdDeviation="1.7" result="near-blur"/>
      <feComponentTransfer in="near-blur" result="near-glow"><feFuncA type="linear" slope="1"/></feComponentTransfer>
      <feMerge><feMergeNode in="wide-glow"/><feMergeNode in="near-glow"/></feMerge>
    </filter>
    <filter id="animated-grain" x="0" y="0" width="100%" height="100%" color-interpolation-filters="sRGB">
      <feTurbulence type="fractalNoise" baseFrequency="0.82" numOctaves="2" seed="17" result="noise">
        <animate attributeName="seed" values="17;31;47;73;19;59;17" dur="0.34s" calcMode="discrete" repeatCount="indefinite"/>
      </feTurbulence>
      <feColorMatrix in="noise" type="saturate" values="0" result="mono-noise"/>
      <feComponentTransfer in="mono-noise">
        <feFuncR type="linear" slope="0.72" intercept="0.14"/>
        <feFuncG type="linear" slope="0.80" intercept="0.18"/>
        <feFuncB type="linear" slope="0.75" intercept="0.16"/>
        <feFuncA type="table" tableValues="0 0.15"/>
      </feComponentTransfer>
    </filter>
    <clipPath id="screen-clip"><rect x="12" y="10" width="696" height="385" rx="22"/></clipPath>
    <clipPath id="typing-line-0"><rect x="146.83" y="32.40" width="0" height="19.54"><animate attributeName="width" from="0" to="261.62" begin="0.000s" dur="0.648s" fill="freeze"/></rect></clipPath><clipPath id="typing-line-1"><rect x="146.83" y="51.94" width="0" height="19.54"><animate attributeName="width" from="0" to="232.55" begin="0.718s" dur="0.576s" fill="freeze"/></rect></clipPath><clipPath id="typing-line-2"><rect x="146.83" y="71.47" width="0" height="19.54"><animate attributeName="width" from="0" to="406.96" begin="1.364s" dur="1.008s" fill="freeze"/></rect></clipPath><clipPath id="typing-line-4"><rect x="146.83" y="110.54" width="0" height="19.54"><animate attributeName="width" from="0" to="87.21" begin="2.442s" dur="0.216s" fill="freeze"/></rect></clipPath><clipPath id="typing-line-5"><rect x="146.83" y="130.08" width="0" height="19.54"><animate attributeName="width" from="0" to="416.65" begin="2.728s" dur="1.032s" fill="freeze"/></rect></clipPath><clipPath id="typing-line-6"><rect x="146.83" y="149.61" width="0" height="19.54"><animate attributeName="width" from="0" to="406.96" begin="3.830s" dur="1.008s" fill="freeze"/></rect></clipPath><clipPath id="typing-line-9"><rect x="146.83" y="208.22" width="0" height="19.54"><animate attributeName="width" from="0" to="77.52" begin="4.908s" dur="0.192s" fill="freeze"/></rect></clipPath><clipPath id="typing-line-10"><rect x="146.83" y="227.75" width="0" height="19.54"><animate attributeName="width" from="0" to="387.58" begin="5.170s" dur="0.960s" fill="freeze"/></rect></clipPath><clipPath id="typing-line-11"><rect x="146.83" y="247.29" width="0" height="19.54"><animate attributeName="width" from="0" to="213.17" begin="6.200s" dur="0.528s" fill="freeze"/></rect></clipPath><clipPath id="typing-line-12"><rect x="146.83" y="266.82" width="0" height="19.54"><animate attributeName="width" from="0" to="426.34" begin="6.798s" dur="1.056s" fill="freeze"/></rect></clipPath><clipPath id="typing-line-13"><rect x="146.83" y="286.36" width="0" height="19.54"><animate attributeName="width" from="0" to="222.86" begin="7.924s" dur="0.552s" fill="freeze"/></rect></clipPath><clipPath id="typing-line-14"><rect x="146.83" y="305.89" width="0" height="19.54"><animate attributeName="width" from="0" to="242.24" begin="8.546s" dur="0.600s" fill="freeze"/></rect></clipPath><clipPath id="typing-line-16"><rect x="146.83" y="344.96" width="0" height="19.54"><animate attributeName="width" from="0" to="261.62" begin="9.216s" dur="0.648s" fill="freeze"/></rect></clipPath>
    <g id="terminal-content"><g clip-path="url(#typing-line-0)"><text x="146.83" y="48.03" xml:space="preserve" font-family="Menlo, Monaco, Consolas, monospace" font-weight="600" font-size="15.63"><tspan fill="#ffba5e" fill-opacity="1.000">&gt;&gt;**NinefCJ</tspan><tspan fill="#eafff3" fill-opacity="1.000"> Also called Ninef</tspan></text></g><g clip-path="url(#typing-line-1)"><text x="146.83" y="67.56" xml:space="preserve" font-family="Menlo, Monaco, Consolas, monospace" font-weight="600" font-size="15.63"><tspan fill="#b38eee" fill-opacity="0.936">A open-source developer.</tspan></text></g><g clip-path="url(#typing-line-2)"><text x="146.83" y="87.10" xml:space="preserve" font-family="Menlo, Monaco, Consolas, monospace" font-weight="600" font-size="15.63"><tspan fill="#8df0b4" fill-opacity="0.920">I have some projects still developing.    </tspan></text></g><g clip-path="url(#typing-line-4)"><text x="146.83" y="126.17" xml:space="preserve" font-family="Menlo, Monaco, Consolas, monospace" font-weight="600" font-size="15.63"><tspan fill="#8df0b4" fill-opacity="1.000">Projects:</tspan></text></g><g clip-path="url(#typing-line-5)"><text x="146.83" y="145.70" xml:space="preserve" font-family="Menlo, Monaco, Consolas, monospace" font-weight="600" font-size="15.63"><tspan fill="#e0ec91" fill-opacity="0.936">RikkaLLM *A native Android LLM chat client.</tspan></text></g><g clip-path="url(#typing-line-6)"><text x="146.83" y="165.24" xml:space="preserve" font-family="Menlo, Monaco, Consolas, monospace" font-weight="600" font-size="15.63"><tspan fill="#97e6dc" fill-opacity="0.936">Nexus *A Minecraft command assistance tool</tspan></text></g><g clip-path="url(#typing-line-9)"><text x="146.83" y="223.85" xml:space="preserve" font-family="Menlo, Monaco, Consolas, monospace" font-weight="600" font-size="15.63"><tspan fill="#f5879a" fill-opacity="0.936">Contact:</tspan></text></g><g clip-path="url(#typing-line-10)"><text x="146.83" y="243.38" xml:space="preserve" font-family="Menlo, Monaco, Consolas, monospace" font-weight="600" font-size="15.63"><tspan fill="#8df0b4" fill-opacity="0.936">QQ:2395953343 (for buisiness and gaming)</tspan></text></g><g clip-path="url(#typing-line-11)"><text x="146.83" y="262.92" xml:space="preserve" font-family="Menlo, Monaco, Consolas, monospace" font-weight="600" font-size="15.63"><tspan fill="#afa9d3" fill-opacity="0.936">Discord:ninef_yu_55629</tspan></text></g><g clip-path="url(#typing-line-12)"><text x="146.83" y="282.45" xml:space="preserve" font-family="Menlo, Monaco, Consolas, monospace" font-weight="600" font-size="15.63"><tspan fill="#cca9d3" fill-opacity="0.936">Discord Server:https://discord.gg/dNzwUkSxYZ</tspan></text></g><g clip-path="url(#typing-line-13)"><text x="146.83" y="301.99" xml:space="preserve" font-family="Menlo, Monaco, Consolas, monospace" font-weight="600" font-size="15.63"><tspan fill="#f2eb8a" fill-opacity="0.936">EMail:2395953343@qq.com</tspan></text></g><g clip-path="url(#typing-line-14)"><text x="146.83" y="321.52" xml:space="preserve" font-family="Menlo, Monaco, Consolas, monospace" font-weight="600" font-size="15.63"><tspan fill="#f3fa83" fill-opacity="0.936">      ninefyu@outlook.com</tspan></text></g><g clip-path="url(#typing-line-16)"><text x="146.83" y="360.59" xml:space="preserve" font-family="Menlo, Monaco, Consolas, monospace" font-weight="600" font-size="15.63"><tspan fill="#d9cca4" fill-opacity="0.936">I&apos;m gald to hear about you.</tspan></text></g><rect x="408.45" y="348.09" width="9.69" height="15.63" fill="#bdf8d2" opacity="0"><animate attributeName="opacity" values="0;0;1;0" keyTimes="0;0.5;0.5;1" begin="9.934s" dur="0.84s" repeatCount="indefinite"/></rect></g>
  </defs>
  <rect width="720" height="405" fill="#020705"/>
  <g clip-path="url(#screen-clip)">
    <rect x="12" y="10" width="696" height="385" fill="url(#screen-base)"/>
    <rect x="12" y="10" width="696" height="385" fill="url(#screen-sheen)"/>
    <g opacity="0.985">
      <animate attributeName="opacity" values="0.985;0.968;0.988;0.977;0.985" keyTimes="0;0.18;0.43;0.71;1" dur="1.7s" repeatCount="indefinite"/>
      <use href="#terminal-content" filter="url(#phosphor-bloom)" opacity="0.98"/>
      <use href="#terminal-content" filter="url(#chromatic-aberration)" opacity="0.34"/>
      <use href="#terminal-content" opacity="0.86"/>
    </g>
    <rect id="rolling-bar" x="12" y="-92" width="696" height="92" fill="url(#rolling-bar-fill)">
      <animateTransform attributeName="transform" type="translate" from="0 0" to="0 590" dur="8.4s" repeatCount="indefinite"/>
    </rect>
    <rect x="12" y="10" width="696" height="385" fill="url(#phosphor-grille)" opacity="0.82"/>
    <rect x="12" y="10" width="696" height="385" fill="url(#scanline-pattern)" opacity="0.78"/>
    <rect x="12" y="10" width="696" height="385" filter="url(#animated-grain)" opacity="0.38"/>
    <rect x="12" y="10" width="696" height="385" fill="url(#screen-vignette)"/>
  </g>
  <rect x="12.5" y="10.5" width="695" height="384" rx="21.5" fill="none" stroke="#bfffd0" stroke-opacity="0.08"/>
</svg>

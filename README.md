<h1>Scroll-triggered Animations & Transitions</h1>
<h2>Details</h2>
<ul>
  <li>Examples of CSS animations and transitions controlled by IntersectionObserver and animation-timeline.</li>
  <li>The animation-timeline Scroll Fill demo requires no JS, and shows how the effect is controlled by scrolling.</li>
  <li>prefers-reduced-motion is honored and will render the static elements.</li>
  <li>CSS is structured to show how multiple animations can be combined.</li>
</ul>

<h2>Considerations</h2>
<ul>
  <li>animation-timeline is only supported in Chrome, Edge, and Opera, while it's available behind a flag in Firefox.</li>
  <li>For progressive enhancement, animation-timeline Scroll Fill demo could fall back to the Transition Fill demo by sharing CSS and using `if (!CSS.supports('animation-timeline: --works')) {...}` to initialize the IntersectionObserver</li>
  <li>For the Transition Wipe Left demo, CSS Transition is used instead of CSS Animation, due to the latter having challenges with reversing an animation via toggled classes.</li>
</ul>

<h2>Demo</h2>
<p>There are ten demos below. One is CSS Animation using animation-timeline, two are CSS Transitions using IntersectionObserver, and seven are CSS Animations using IntersectionObserver.</p>

https://nonsponsored.github.io/scroll-animations-transitions/

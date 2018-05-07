---
layout: prototype-clean
title: USWDS project theme palette
permalink: /uswds-color-docs-theme/
---

<div class="font-weight-300 padding-top-2 padding-bottom-4 tablet:padding-top-4 tablet:padding-bottom-6">

  <div class="g-container-desktop margin-bottom-0 padding-x-4 padding-top-2 margin-top-0">
    <div class="g-row">
      <div class="g-col-8">
        <p class="font-sans-4 color-black-50 margin-top-0 margin-bottom-2 font-weight-400"><span class="color-black font-weight-800 padding-2px border-2px line-height-smallest padding-bottom-0 margin-right-1">USWDS</span> Docs <span class="color-black">/</span> Style <span class="color-black">/</span> Colors</p>
          <h1 class="font-sans-14 font-weight-300 margin-top-0 line-height-smaller margin-bottom-0">Project theme palette</h1>
      </div>
      <div class="g-col-4">
        <figure class="margin-0 display-block">
          <img class="max-width-full display-block margin-x-auto" src="{{ '/assets/img/uswds/geodesic-header.svg' | relative_url }}" alt="A geodesic dome with colorful nodes">
        </figure>
      </div>
    </div>

    <div class="g-row padding-top-3 border-top-1px">
      <div class="g-col-3 sidenav">
        <ul class="list-reset font-sans-6 font-weight-700">
          <li class="padding-bottom-1"><a class="color-black-90 text-decoration-none hover:text-decoration-underline" href="{{ '/uswds-color-docs-introduction' | relative_url }}">Introduction</a>
          </li>
          <li class="padding-bottom-1"><a class="color-black-90 text-decoration-none hover:text-decoration-underline" href="{{ '/uswds-color-docs-theme' | relative_url }}">Project theme palette</a>
            <ul class="list-reset font-weight-300 margin-top-1 margin-bottom-2">
              <li>Using role-based palettes</li>
              <li>Project theme palette gallery</li>
              <li>Pairing colors</li>
            </ul>
          </li>
          <li class="padding-bottom-1"><a class="color-black-90 text-decoration-none hover:text-decoration-underline" href="{{ '/uswds-color-docs-system' | relative_url }}">System palette</a></li>
          <li><a class="color-black-90 text-decoration-none hover:text-decoration-underline" href="{{ '/uswds-color-docs-system' | relative_url }}">Special palettes</a></li>
        </ul>
      </div>
      <div class="g-col-9 usa-prose padding-x-3 font-sans-8">

        <!-- ###################################################### -->

        <p class="font-sans-11 font-weight-300 line-height-base margin-top-0">Your project theme palette defines the specific color families and grades used in your project, based on the role these colors play on your site.</p>

        <div class="g-row g-gap margin-y-4 text-align-center">
          <div class="g-col-fill">
            <a href="#0" class="display-flex flex-direction-column justify-content-center min-height-card-plus border border-radius-large padding-2 color-black-90 text-decoration-none border-color-black-20 hover:border-color-black-90 hover:border-width-2px">
              <figure class="margin-0 display-block width-4 margin-x-auto">
                <img class="max-width-full display-block margin-x-auto" src="{{ '/assets/img/uswds/project-theme-palette-icon.svg' | relative_url }}" alt="Project theme palette icon">
              </figure>
              <p class="flex-auto width-full margin-bottom-0 font-sans-6 font-weight-700 line-height-small margin-top-1">Theme palette gallery</p>
              <p class="alex-auto width-full margin-0 margin-top-1 font-sans-6 line-height-small padding-bottom-1">View and download project theme palettes</p>
            </a>
          </div>
          <div class="g-col-fill">
            <a href="#0" class="display-flex flex-direction-column justify-content-center min-height-card-plus border border-radius-large padding-2 color-black-90 text-decoration-none border-color-black-20 hover:border-color-black-90 hover:border-width-2px">
              <figure class="margin-0 display-block width-4 margin-x-auto">
                <img class="max-width-full display-block margin-x-auto" src="{{ '/assets/img/uswds/Sketch_logo_frame.svg' | relative_url }}" alt="Sketch application icon">
              </figure>
              <p class="flex-auto width-full margin-bottom-0 font-sans-6 font-weight-700 line-height-small margin-top-1">Get the design assets</p>
              <p class="alex-auto width-full margin-0 margin-top-1 font-sans-6 line-height-small padding-bottom-1">Use project theme palettes in your Sketch files</p>
            </a>
          </div>
        </div>

        <h2 class="font-sans-10 margin-top-4 margin-bottom-4 border-top-1px padding-top-2">Using role-based palettes</h2>

        <p class="margin-top-2">Project theme palettes are role-based — assigning colors to four high-level roles that colors can play in your project: <strong>neutral</strong>, <strong>primary</strong>, <strong>secondary</strong>, and <strong>accent</strong>.</p>
        <p>Primary, secondary, and accent colors can be thought of as falling into a proportional 60/30/10 relationship: about 60% of your site’s color would be the primary color family, about 30% would be the secondary color family, and about 10% would be the accent color families (accent warm and accent cool).</p>
        <p>Note that these proportions are for non-neutral colors. In many cases, the neutral text color will be the predominant tone on your site.</p>
        <div class="margin-top-4 margin-bottom-8">
          <div class="g-row g-gap-small">
            <div class="g-col-7 margin-bottom-1">
              <div class="border-bottom-1px font-mono-2 padding-bottom-p5">60%</div>
            </div>
            <div class="g-col-4">
              <div class="border-bottom-1px font-mono-2 padding-bottom-p5">30%</div>
            </div>
            <div class="g-col-1">
              <div class="border-bottom-1px font-mono-2 padding-bottom-p5">10%</div>
            </div>
          </div>
          <div class="g-row g-gap-small">
            <div class="g-col-7">
              <div class="height-2 background-color-blue-70v"></div>
            </div>
            <div class="g-col-4">
              <div class="height-2 background-color-mint-50"></div>
            </div>
            <div class="g-col-1 g-row g-gap-small">
              <div class="g-col-fill">
                <div class="height-2 background-color-orange-30v"></div>
              </div>
              <div class="g-col-fill">
                <div class="height-2 background-color-cyan-20v"></div>
              </div>
            </div>
          </div>
          <div class="g-row g-gap margin-top-2">
            <div class="g-col-auto g-row align-items-center">
              <div class="g-col-auto circle-2 background-color-blue-70v margin-right-1"></div>
              <div class="line-height-smallest font-sans-4 font-weight-700 padding-top-2px ">Primary</div>
            </div>
            <div class="g-col-auto g-row align-items-center">
              <div class="g-col-auto circle-2 background-color-mint-50 margin-right-1"></div>
              <div class="line-height-smallest font-sans-4 font-weight-700 padding-top-2px ">Secondary</div>
            </div>
            <div class="g-col-auto g-row align-items-center">
              <div class="g-col-auto circle-2 background-color-orange-30v margin-right-1"></div>
              <div class="line-height-smallest font-sans-4 font-weight-700 padding-top-2px ">Accent warm</div>
            </div>
            <div class="g-col-auto g-row align-items-center">
              <div class="g-col-auto circle-2 background-color-cyan-20v margin-right-1"></div>
              <div class="line-height-smallest font-sans-4 font-weight-700 padding-top-2px ">Accent cool</div>
            </div>
          </div>
        </div>
        <ul>
          <li>A <strong>neutral color</strong> is often used for text and is typically <code>black</code>, <code>black-cool</code> or <code>black-warm</code>. Most of the readable content on your website will be neutral.</li>
          <li>A <strong>primary color</strong> is the hue family used for about 60% of your site’s color. This tends to be the color most associated with identity, and the color used for buttons and other primary actionable items.</li>
          <li>A <strong>secondary color</strong> is the hue family used for about 30% of your site’s color. This hue is meant to support the primary color and distinguish alternate actions. Use a secondary color for callouts, pullquotes, or some headers to balance or harmonize with the primary color, and to add meaningful differentiation.</li>
          <li>An <strong>accent color</strong> is meant to draw attention. Use accent colors sparingly. They tend to follow a boy-who-cried-wolf rule: the more you use it, the less attention each usage captures.</li>
        </ul>

        <p>Here’s an example of how these might work together:</p>

        <aside class="background-color-white-warm-3 padding-3 margin-y-4 border-radius-small">
          <div class="g-row g-gap-large">
            <div class="g-col-4">
              <figure class="margin-0 display-block">
                <img class="max-width-full display-block margin-left-auto" src="{{ '/assets/img/uswds/project-theme-palette-example.svg' | relative_url }}" alt="An example of the 6-30-10 principle applied to a project theme">
              </figure>
            </div>
            <div class="g-col-fill">
              <p class="margin-top-0 font-sans-6 font-weight-400">The <strong>primary</strong> color family of <code class="background-color-blue-70v color-white">Blue</code> occupies the majority of the non-neutral color on the page.</p>
              <p class="border-top margin-top-1 padding-top-1 font-sans-6 font-weight-400">The <strong>secondary</strong> color family of <code class="background-color-mint-50 color-white">Mint</code> functions as a background color for an occasional content type.</p>
              <p class="border-top margin-top-1 padding-top-1 font-sans-6 font-weight-400">The <strong>warm and cool accent color families</strong> of <code class="background-color-orange-40v color-black-90">Orange</code> and <code class="background-color-cyan-20v color-black-90">Cyan</code> serve as special call-to-action buttons and headings for special content.</p>
              <p class="border-top margin-top-1 padding-top-1 font-sans-6 font-weight-400"><strong>Neutral</strong> <code class="background-color-black-90 color-white">Black</code> is the color family of most text.</p>
            </div>
          </div>
        </aside>

        <h2 class="font-sans-10 margin-y-4 border-top-1px padding-top-2">Project theme palette grades</h2>
        <p>Each project theme palette include the five theme color families we’ve discussed (primary, secondary, accent warm, accent cool, and neutral) in a range of relative grades from <code>lightest</code> to <code>darker</code>, plus a <code>vivid</code> variant. No color family includes all these grades and variants. The following chart shows the available families and grades of a project theme palette in more detail.</p>
        <div class="g-row g-gap">
          <div class="g-col-6">
            <div class="margin-top-3 border border-radius-base padding-2">
              <h4 class="margin-0 font-sans-8">Primary</h4>
              <div>
                <div class="g-row font-sans-1 border-top border-color-black-10 margin-top-2 padding-top-1p5">
                  <div class="g-col-fit font-weight-700">Lightest</div>
                  <div class="g-col-fit margin-left-auto">Grade 1–5</div>
                </div>
                <div class="height-4 display-flex align-items-center  margin-top-p5">
                  <div class="margin-x-auto circle-2px background-color-black-90"></div>
                </div><!-- blank -->
                <ul class="swatch-info list-reset font-mono-1 margin-top-1">
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">Utility suffix:</span> <span class="token">—</span></li>
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">SASS:</span> <span class="token">—</span></li>
                </ul>
              </div><!-- color -->
              <div>
                <div class="g-row font-sans-1 border-top border-color-black-10 margin-top-2 padding-top-1p5">
                  <div class="g-col-fit font-weight-700">Lighter</div>
                  <div class="g-col-fit margin-left-auto">Grade 10–20</div>
                </div>
                <div class="height-4 display-flex align-items-center background-color-blue-10 margin-top-p5">
                  <div class="margin-x-auto circle-2px background-color-black-90 display-none"></div>
                </div>
                <ul class="swatch-info list-reset font-mono-1 margin-top-1">
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">Utility suffix:</span> <span class="token">-primary-lighter</span></li>
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">SASS:</span> <span class="token">color(primary, lighter)</span></li>
                </ul>
              </div><!-- color -->
              <div>
                <div class="g-row font-sans-1 border-top border-color-black-10 margin-top-2 padding-top-1p5">
                  <div class="g-col-fit font-weight-700">Light</div>
                  <div class="g-col-fit margin-left-auto">Grade 30–40</div>
                </div>
                <div class="height-4 display-flex align-items-center background-color-blue-30 margin-top-p5">
                  <div class="margin-x-auto circle-2px background-color-black-90 display-none"></div>
                </div>
                <ul class="swatch-info list-reset font-mono-1 margin-top-1">
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">Utility suffix:</span> <span class="token">-primary-light</span></li>
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">SASS:</span> <span class="token">color(primary, light)</span></li>
                </ul>
              </div><!-- color -->
              <div>
                <div class="g-row font-sans-1 border-top border-color-black-10 margin-top-2 padding-top-1p5">
                  <div class="g-col-fit font-weight-700">Base</div>
                  <div class="g-col-fit margin-left-auto">Grade 40–60</div>
                </div>
                <div class="height-4 display-flex align-items-center background-color-blue-50 margin-top-p5">
                  <div class="margin-x-auto circle-2px background-color-black-90 display-none"></div>
                </div>
                <ul class="swatch-info list-reset font-mono-1 margin-top-1">
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">Utility suffix:</span> <span class="token">-primary-base</span></li>
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">SASS:</span> <span class="token">color(primary, base)</span></li>
                </ul>
              </div><!-- color -->
              <div>
                <div class="g-row font-sans-1 border-top border-color-black-10 margin-top-2 padding-top-1p5">
                  <div class="g-col-fit font-weight-700">Vivid</div>
                  <div class="g-col-fit margin-left-auto">Grade 20v-60v</div>
                </div>
                <div class="height-4 display-flex align-items-center background-color-blue-50v margin-top-p5">
                  <div class="margin-x-auto circle-2px background-color-black-90 display-none"></div>
                </div>
                <ul class="swatch-info list-reset font-mono-1 margin-top-1">
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">Utility suffix:</span> <span class="token">-primary-vivid</span></li>
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">SASS:</span> <span class="token">color(primary, vivid)</span></li>
                </ul>
              </div><!-- color -->
              <div>
                <div class="g-row font-sans-1 border-top border-color-black-10 margin-top-2 padding-top-1p5">
                  <div class="g-col-fit font-weight-700">Dark</div>
                  <div class="g-col-fit margin-left-auto">Grade 60-70</div>
                </div>
                <div class="height-4 display-flex align-items-center background-color-blue-70 margin-top-p5">
                  <div class="margin-x-auto circle-2px background-color-black-90 display-none"></div>
                </div>
                <ul class="swatch-info list-reset font-mono-1 margin-top-1">
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">Utility suffix:</span> <span class="token">-primary-large</span></li>
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">SASS:</span> <span class="token">color(primary, large)</span></li>
                </ul>
              </div><!-- color -->
              <div>
                <div class="g-row font-sans-1 border-top border-color-black-10 margin-top-2 padding-top-1p5">
                  <div class="g-col-fit font-weight-700">Darker</div>
                  <div class="g-col-fit margin-left-auto">Grade 80–100</div>
                </div>
                <div class="height-4 display-flex align-items-center background-color-blue-90 margin-top-p5">
                  <div class="margin-x-auto circle-2px background-color-black-90 display-none"></div>
                </div>
                <ul class="swatch-info list-reset font-mono-1 margin-top-1">
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">Utility suffix:</span> <span class="token">-primary-darker</span></li>
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">SASS:</span> <span class="token">color(primary, darker)</span></li>
                </ul>
              </div><!-- color -->
            </div><!-- card -->
          </div><!-- column -->
          <div class="g-col-6">
            <div class="margin-top-3 border border-radius-base padding-2">
              <h4 class="margin-0 font-sans-8">Secondary</h4>
              <div>
                <div class="g-row font-sans-1 border-top border-color-black-10 margin-top-2 padding-top-1p5">
                  <div class="g-col-fit font-weight-700">Lightest</div>
                  <div class="g-col-fit margin-left-auto">Grade 1–5</div>
                </div>
                <div class="height-4 display-flex align-items-center  margin-top-p5">
                  <div class="margin-x-auto circle-2px background-color-black-90"></div>
                </div><!-- blank -->
                <ul class="swatch-info list-reset font-mono-1 margin-top-1">
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">Utility suffix:</span> <span class="token">—</span></li>
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">SASS:</span> <span class="token">—</span></li>
                </ul>
              </div><!-- color -->
              <div>
                <div class="g-row font-sans-1 border-top border-color-black-10 margin-top-2 padding-top-1p5">
                  <div class="g-col-fit font-weight-700">Lighter</div>
                  <div class="g-col-fit margin-left-auto">Grade 10–20</div>
                </div>
                <div class="height-4 display-flex align-items-center margin-top-p5">
                  <div class="margin-x-auto circle-2px background-color-black-90"></div>
                </div>
                <ul class="swatch-info list-reset font-mono-1 margin-top-1">
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">Utility suffix:</span> <span class="token">—</span></li>
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">SASS:</span> <span class="token">—</span></li>
                </ul>
              </div><!-- color -->
              <div>
                <div class="g-row font-sans-1 border-top border-color-black-10 margin-top-2 padding-top-1p5">
                  <div class="g-col-fit font-weight-700">Light</div>
                  <div class="g-col-fit margin-left-auto">Grade 30–40</div>
                </div>
                <div class="height-4 display-flex align-items-center background-color-mint-30 margin-top-p5">
                  <div class="margin-x-auto circle-2px background-color-black-90 display-none"></div>
                </div>
                <ul class="swatch-info list-reset font-mono-1 margin-top-1">
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">Utility suffix:</span> <span class="token">-secondary-light</span></li>
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">SASS:</span> <span class="token">color(secondary, light)</span></li>
                </ul>
              </div><!-- color -->
              <div>
                <div class="g-row font-sans-1 border-top border-color-black-10 margin-top-2 padding-top-1p5">
                  <div class="g-col-fit font-weight-700">Base</div>
                  <div class="g-col-fit margin-left-auto">Grade 40–60</div>
                </div>
                <div class="height-4 display-flex align-items-center background-color-mint-50 margin-top-p5">
                  <div class="margin-x-auto circle-2px background-color-black-90 display-none"></div>
                </div>
                <ul class="swatch-info list-reset font-mono-1 margin-top-1">
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">Utility suffix:</span> <span class="token">-secondary-base</span></li>
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">SASS:</span> <span class="token">color(secondary, base)</span></li>
                </ul>
              </div><!-- color -->
              <div>
                <div class="g-row font-sans-1 border-top border-color-black-10 margin-top-2 padding-top-1p5">
                  <div class="g-col-fit font-weight-700">Vivid</div>
                  <div class="g-col-fit margin-left-auto">Grade 20v-60v</div>
                </div>
                <div class="height-4 display-flex align-items-center background-color-mint-cool-40v margin-top-p5">
                  <div class="margin-x-auto circle-2px background-color-black-90 display-none"></div>
                </div>
                <ul class="swatch-info list-reset font-mono-1 margin-top-1">
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">Utility suffix:</span> <span class="token">-secondary-vivid</span></li>
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">SASS:</span> <span class="token">color(secondary, vivid)</span></li>
                </ul>
              </div><!-- color -->
              <div>
                <div class="g-row font-sans-1 border-top border-color-black-10 margin-top-2 padding-top-1p5">
                  <div class="g-col-fit font-weight-700">Dark</div>
                  <div class="g-col-fit margin-left-auto">Grade 60-70</div>
                </div>
                <div class="height-4 display-flex align-items-center background-color-mint-70 margin-top-p5">
                  <div class="margin-x-auto circle-2px background-color-black-90 display-none"></div>
                </div>
                <ul class="swatch-info list-reset font-mono-1 margin-top-1">
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">Utility suffix:</span> <span class="token">-secondary-dark</span></li>
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">SASS:</span> <span class="token">color(secondary, dark)</span></li>
                </ul>
              </div><!-- color -->
              <div>
                <div class="g-row font-sans-1 border-top border-color-black-10 margin-top-2 padding-top-1p5">
                  <div class="g-col-fit font-weight-700">Darker</div>
                  <div class="g-col-fit margin-left-auto">Grade 80–100</div>
                </div>
                <div class="height-4 display-flex align-items-center margin-top-p5">
                  <div class="margin-x-auto circle-2px background-color-black-90"></div>
                </div>
                <ul class="swatch-info list-reset font-mono-1 margin-top-1">
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">Utility suffix:</span> <span class="token">—</span></li>
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">SASS:</span> <span class="token">—</span></li>
                </ul>
              </div><!-- color -->
            </div><!-- card -->
          </div><!-- column -->

          <div class="g-col-6">
            <div class="margin-top-3 border border-radius-base padding-2">
              <h4 class="margin-0 font-sans-8">Accent warm</h4>
              <div>
                <div class="g-row font-sans-1 border-top border-color-black-10 margin-top-2 padding-top-1p5">
                  <div class="g-col-fit font-weight-700">Base</div>
                  <div class="g-col-fit margin-left-auto">Grade 20v–50v</div>
                </div>
                <div class="height-4 display-flex align-items-center background-color-orange-40v margin-top-p5">
                  <div class="margin-x-auto circle-2px background-color-black-90 display-none"></div>
                </div>
                <ul class="swatch-info list-reset font-mono-1 margin-top-1">
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">Utility suffix:</span> <span class="token">-accent-warm-base</span></li>
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">SASS:</span> <span class="token">color(accent-warm, base)</span></li>
                </ul>
              </div><!-- color -->
              <div>
                <div class="g-row font-sans-1 border-top border-color-black-10 margin-top-2 padding-top-1p5">
                  <div class="g-col-fit font-weight-700">Dark</div>
                  <div class="g-col-fit margin-left-auto">Grade 40–60</div>
                </div>
                <div class="height-4 display-flex align-items-center background-color-orange-50v margin-top-p5">
                  <div class="margin-x-auto circle-2px background-color-black-90 display-none"></div>
                </div>
                <ul class="swatch-info list-reset font-mono-1 margin-top-1">
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">Utility suffix:</span> <span class="token">-accent-warm-dark</span></li>
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">SASS:</span> <span class="token">color(accent-warm, dark)</span></li>
                </ul>
              </div><!-- color -->
            </div><!-- card -->
          </div><!-- column -->
          <div class="g-col-6">
            <div class="margin-top-3 border border-radius-base padding-2">
              <h4 class="margin-0 font-sans-8">Accent cool</h4>
              <div>
                <div class="g-row font-sans-1 border-top border-color-black-10 margin-top-2 padding-top-1p5">
                  <div class="g-col-fit font-weight-700">Base</div>
                  <div class="g-col-fit margin-left-auto">Grade 20v–50v</div>
                </div>
                <div class="height-4 display-flex align-items-center background-color-cyan-20v margin-top-p5">
                  <div class="margin-x-auto circle-2px background-color-black-90 display-none"></div>
                </div>
                <ul class="swatch-info list-reset font-mono-1 margin-top-1">
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">Utility suffix:</span> <span class="token">-accent-cool-base</span></li>
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">SASS:</span> <span class="token">color(accent-cool, base)</span></li>
                </ul>
              </div><!-- color -->
              <div>
                <div class="g-row font-sans-1 border-top border-color-black-10 margin-top-2 padding-top-1p5">
                  <div class="g-col-fit font-weight-700">Dark</div>
                  <div class="g-col-fit margin-left-auto">Grade 40–60</div>
                </div>
                <div class="height-4 display-flex align-items-center background-color-cyan-40v margin-top-p5">
                  <div class="margin-x-auto circle-2px background-color-black-90 display-none"></div>
                </div>
                <ul class="swatch-info list-reset font-mono-1 margin-top-1">
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">Utility suffix:</span> <span class="token">-accent-cool-dark</span></li>
                  <li class="margin-y-2px border-0 padding-0"><span class="font-sans-2">SASS:</span> <span class="token">color(accent-cool, dark)</span></li>
                </ul>
              </div><!-- color -->
            </div><!-- card -->
          </div><!-- column -->
          <div class="g-col-12">
            <div class="margin-top-3 border border-radius-base padding-2 background-color-white">
              <h4 class="margin-0 font-sans-8">Neutral</h4>
              <div>
                <div class="g-row font-sans-1 border-top border-color-black-10 margin-top-2 padding-top-1p5">
                  <div class="g-col-fit font-weight-700">Lightest</div>
                  <div class="g-col-fit margin-left-auto">Grade 0–5</div>
                </div>
                <div class="height-4 display-flex align-items-center margin-top-p5 background-color-white-1">
                  <div class="margin-x-auto circle-2px background-color-black-90 display-none"></div>
                </div>
                <ul class="g-row swatch-info list-reset font-mono-1 margin-top-1">
                  <li class="g-col-auto margin-y-2px border-0 padding-0"><span class="font-sans-2">Utility suffix:</span> <span class="token">-neutral-lightest</span></li>
                  <li class="g-col-auto margin-left-auto margin-y-2px border-0 padding-0"><span class="font-sans-2">SASS:</span> <span class="token">color(neutral, lightest)</span></li>
                </ul>
              </div><!-- color -->
              <div>
                <div class="g-row font-sans-1 border-top border-color-black-10 margin-top-2 padding-top-1p5">
                  <div class="g-col-fit font-weight-700">Lighter</div>
                  <div class="g-col-fit margin-left-auto">Grade 10–20</div>
                </div>
                <div class="height-4 display-flex align-items-center margin-top-p5 background-color-black-10">
                </div>
                <ul class="g-row swatch-info list-reset font-mono-1 margin-top-1">
                  <li class="g-col-auto margin-y-2px border-0 padding-0"><span class="font-sans-2">Utility suffix:</span> <span class="token">-neutral-lighter</span></li>
                  <li class="g-col-auto margin-left-auto margin-y-2px border-0 padding-0"><span class="font-sans-2">SASS:</span> <span class="token">color(neutral, lighter)</span></li>
                </ul>
              </div><!-- color -->
              <div>
                <div class="g-row font-sans-1 border-top border-color-black-10 margin-top-2 padding-top-1p5">
                  <div class="g-col-fit font-weight-700">Light</div>
                  <div class="g-col-fit margin-left-auto">Grade 20–30</div>
                </div>
                <div class="height-4 display-flex align-items-center margin-top-p5 background-color-black-30">
                </div>
                <ul class="g-row swatch-info list-reset font-mono-1 margin-top-1">
                  <li class="g-col-auto margin-y-2px border-0 padding-0"><span class="font-sans-2">Utility suffix:</span> <span class="token">-neutral-light</span></li>
                  <li class="g-col-auto margin-left-auto margin-y-2px border-0 padding-0"><span class="font-sans-2">SASS:</span> <span class="token">color(neutral, light)</span></li>
                </ul>
              </div><!-- color -->
              <div>
                <div class="g-row font-sans-1 border-top border-color-black-10 margin-top-2 padding-top-1p5">
                  <div class="g-col-fit font-weight-700">Base</div>
                  <div class="g-col-fit margin-left-auto">Grade 40–60</div>
                </div>
                <div class="height-4 display-flex align-items-center margin-top-p5 background-color-black-50">
                </div>
                <ul class="g-row swatch-info list-reset font-mono-1 margin-top-1">
                  <li class="g-col-auto margin-y-2px border-0 padding-0"><span class="font-sans-2">Utility suffix:</span> <span class="token">-neutral-base</span></li>
                  <li class="g-col-auto margin-left-auto margin-y-2px border-0 padding-0"><span class="font-sans-2">SASS:</span> <span class="token">color(neutral, base)</span></li>
                </ul>
              </div><!-- color -->
              <div>
                <div class="g-row font-sans-1 border-top border-color-black-10 margin-top-2 padding-top-1p5">
                  <div class="g-col-fit font-weight-700">Dark</div>
                  <div class="g-col-fit margin-left-auto">Grade 60–70</div>
                </div>
                <div class="height-4 display-flex align-items-center margin-top-p5 background-color-black-70">
                </div>
                <ul class="g-row swatch-info list-reset font-mono-1 margin-top-1">
                  <li class="g-col-auto margin-y-2px border-0 padding-0"><span class="font-sans-2">Utility suffix:</span> <span class="token">-neutral-dark</span></li>
                  <li class="g-col-auto margin-left-auto margin-y-2px border-0 padding-0"><span class="font-sans-2">SASS:</span> <span class="token">color(neutral, dark)</span></li>
                </ul>
              </div><!-- color -->
              <div>
                <div class="g-row font-sans-1 border-top border-color-black-10 margin-top-2 padding-top-1p5">
                  <div class="g-col-fit font-weight-700">Darker</div>
                  <div class="g-col-fit margin-left-auto">Grade 80–100</div>
                </div>
                <div class="height-4 display-flex align-items-center margin-top-p5 background-color-black-90">
                </div>
                <ul class="g-row swatch-info list-reset font-mono-1 margin-top-1">
                  <li class="g-col-auto margin-y-2px border-0 padding-0"><span class="font-sans-2">Utility suffix:</span> <span class="token">-neutral-darker</span></li>
                  <li class="g-col-auto margin-left-auto margin-y-2px border-0 padding-0"><span class="font-sans-2">SASS:</span> <span class="token">color(neutral, darker)</span></li>
                </ul>
              </div><!-- color -->
            </div><!-- card -->
          </div><!-- column -->
        </div><!-- row -->

        <h2 class="font-sans-10 margin-y-4 border-top-1px padding-top-2">Palette gallery</h2>
        <p>While it can be simple to create and customize USWDS project theme palettes when your team has dedicated visual design skills, we’re also working to provide strong, practical prebuilt themes designed by visual designers and appropriate for a wide range of needs. Each of the following palettes is available for immediate download, using <a href="#0">the instructions below</a>.</p>
        <p>If you’ve designed a useful project theme palette for your project, consider <a href="#0">contributing it back to USWDS</a> through Github — we’re interested in collecting and presenting new proven project work.</p>

        <div class="g-row g-gap margin-top-4">
          <div class="g-col-6">
            <div class="palette-card border border-radius-small padding-1 margin-top-3">
              <div class="g-row g-gap-2px">
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="height-1 display-flex align-items-center">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-blue-10 height-1 margin-top-2px"></div>
                  <div class="background-color-blue-30 height-1 margin-top-2px"></div>
                  <div class="background-color-blue-50 height-1 margin-top-2px"></div>
                  <div class="background-color-blue-40v height-1 margin-top-2px"></div>
                  <div class="background-color-blue-70 height-1 margin-top-2px"></div>
                  <div class="background-color-blue-90 height-1 margin-top-2px"></div>
                </div><!-- family-column -->
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="height-1 display-flex align-items-center">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-mint-30 height-1 margin-top-2px"></div>
                  <div class="background-color-mint-50 height-1 margin-top-2px"></div>
                  <div class="background-color-mint-cool-40v height-1 margin-top-2px"></div>
                  <div class="background-color-mint-60 height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                </div><!-- family-column -->
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="height-1 display-flex align-items-center">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-orange-40v height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-orange-50v height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                </div><!-- family-column -->
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="height-1 display-flex align-items-center">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-cyan-20v height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-cyan-40v height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                </div><!-- family-column -->
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="background-color-white-1 height-1"></div>
                  <div class="background-color-black-5 height-1 margin-top-2px"></div>
                  <div class="background-color-black-30 height-1 margin-top-2px"></div>
                  <div class="background-color-black-50 height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-black-80 height-1 margin-top-2px"></div>
                  <div class="background-color-black-80 height-1 margin-top-2px"></div>
                </div><!-- family-column -->
              </div> <!-- this-palette -->
              <h4 class="font-sans-5 margin-bottom-1 line-height-smaller">Onondaga</h4>
              <ul class="list-reset g-row g-gap font-sans-1 font-weight-400 margin-bottom-0 margin-x-0 min-height-6 align-items-flex-start margin-top-p5">
                <li class="g-col-auto border-0 background-color-white-warm-4 border-radius-small padding-y-p5 padding-x-1 line-height-smallest margin-right-p5">professional</li>
                <li class="g-col-auto border-0 background-color-white-warm-4 border-radius-small padding-y-p5 padding-x-1 line-height-smallest margin-right-p5">young</li>
                <li class="g-col-auto border-0 background-color-white-warm-4 border-radius-small padding-y-p5 padding-x-1 line-height-smallest margin-right-p5">natural</li>
              </ul><!-- tags -->
              <div class="g-row margin-top-2 align-items-center">
                <a href="#0" class="g-col-auto line-height-smallest font-sans-1 font-weight-400 padding-y-1 padding-x-2 background-color-black-90 color-white border-radius-small text-decoration-none">
                  Download palette ⇣
                </a><!-- palette-button -->
                <a href="#0" class="g-col-auto margin-left-auto color-black-90 font-sans-1 text-decoration-underline line-height-smallest">See more examples</a>
              </div><!-- palette-actions -->
            </div><!-- palette-card -->
          </div>

          <!-- * * * * * * =================================== -->
          <div class="g-col-6">
            <div class="palette-card border border-radius-small padding-1 margin-top-3">
              <div class="g-row g-gap-2px">
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="height-1 display-flex align-items-center">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-blue-10 height-1 margin-top-2px"></div>
                  <div class="background-color-blue-40 height-1 margin-top-2px"></div>
                  <div class="background-color-blue-50 height-1 margin-top-2px"></div>
                  <div class="background-color-blue-60v height-1 margin-top-2px"></div>
                  <div class="background-color-blue-70v height-1 margin-top-2px"></div>
                  <div class="background-color-blue-90 height-1 margin-top-2px"></div>
                </div><!-- family-column -->
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="height-1 display-flex align-items-center">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-red-20v height-1 margin-top-2px"></div>
                  <div class="background-color-red-50 height-1 margin-top-2px"></div>
                  <div class="background-color-red-50v height-1 margin-top-2px"></div>
                  <div class="background-color-red-60 height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                </div><!-- family-column -->
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="height-1 display-flex align-items-center">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-gold-10v height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-gold-40 height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                </div><!-- family-column -->
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="height-1 display-flex align-items-center">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-cyan-30v height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-cyan-50 height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                </div><!-- family-column -->
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="background-color-white height-1"></div>
                  <div class="background-color-black-10 height-1 margin-top-2px"></div>
                  <div class="background-color-black-30 height-1 margin-top-2px"></div>
                  <div class="background-color-black-50 height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-black-70 height-1 margin-top-2px"></div>
                  <div class="background-color-blacksolid-90 height-1 margin-top-2px"></div>
                </div><!-- family-column -->
              </div> <!-- this-palette -->
              <h4 class="font-sans-5 margin-bottom-1 line-height-smaller">Federal <span class="font-weight-300">(Original USWDS)</span></h4>
              <ul class="list-reset g-row g-gap font-sans-1 font-weight-400 margin-bottom-0 margin-x-0 min-height-6 align-items-flex-start margin-top-p5">
                <li class="g-col-auto border-0 background-color-white-warm-4 border-radius-small padding-y-p5 padding-x-1 line-height-smallest margin-right-p5">traditional</li>
                <li class="g-col-auto border-0 background-color-white-warm-4 border-radius-small padding-y-p5 padding-x-1 line-height-smallest margin-right-p5">straightforward</li>
                <li class="g-col-auto border-0 background-color-white-warm-4 border-radius-small padding-y-p5 padding-x-1 line-height-smallest margin-right-p5">trustworthy</li>
              </ul><!-- tags -->
              <div class="g-row margin-top-2 align-items-center">
                <a href="#0" class="g-col-auto line-height-smallest font-sans-1 font-weight-400 padding-y-1 padding-x-2 background-color-black-90 color-white border-radius-small text-decoration-none">
                  Download palette ⇣
                </a><!-- palette-button -->
                <a href="#0" class="g-col-auto margin-left-auto color-black-90 font-sans-1 text-decoration-underline line-height-smallest">See more examples</a>
              </div><!-- palette-actions -->
            </div><!-- palette-card -->
          </div><!-- card column -->

          <!-- * * * * * * =================================== -->
          <div class="g-col-6">
            <div class="palette-card border border-radius-small padding-1 margin-top-3">
              <div class="g-row g-gap-2px">
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="height-1 display-flex align-items-center">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-indigo-cool-10 height-1 margin-top-2px"></div>
                  <div class="background-color-indigo-cool-30 height-1 margin-top-2px"></div>
                  <div class="background-color-indigo-cool-60 height-1 margin-top-2px"></div>
                  <div class="background-color-indigo-cool-40v height-1 margin-top-2px"></div>
                  <div class="background-color-indigo-cool-70 height-1 margin-top-2px"></div>
                  <div class="background-color-indigo-cool-90 height-1 margin-top-2px"></div>
                </div><!-- family-column -->
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="height-1 display-flex align-items-center">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-red-warm-20v height-1 margin-top-2px"></div>
                  <div class="background-color-red-warm-40v height-1 margin-top-2px"></div>
                  <div class="background-color-red-warm-50v height-1 margin-top-2px"></div>
                  <div class="background-color-red-warm-60 height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                </div><!-- family-column -->
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="height-1 display-flex align-items-center">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-yellow-10v height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-yellow-20v height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                </div><!-- family-column -->
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="height-1 display-flex align-items-center">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-blue-30v height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-blue-50v height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                </div><!-- family-column -->
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="background-color-white-cool-1 height-1"></div>
                  <div class="background-color-black-cool-10 height-1 margin-top-2px"></div>
                  <div class="background-color-black-cool-30 height-1 margin-top-2px"></div>
                  <div class="background-color-black-cool-50 height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-black-cool-70 height-1 margin-top-2px"></div>
                  <div class="background-color-black-cool-90 height-1 margin-top-2px"></div>
                </div><!-- family-column -->
              </div> <!-- this-palette -->
              <h4 class="font-sans-5 margin-bottom-1 line-height-smaller margin-bottom-0">Pennant</h4>
              <ul class="list-reset g-row g-gap font-sans-1 font-weight-400 margin-bottom-0 margin-x-0 min-height-6 align-items-flex-start margin-top-p5">
                <li class="g-col-auto border-0 background-color-white-warm-4 border-radius-small padding-y-p5 padding-x-1 line-height-smallest margin-right-p5 margin-top-p5">solid</li>
                <li class="g-col-auto border-0 background-color-white-warm-4 border-radius-small padding-y-p5 padding-x-1 line-height-smallest margin-right-p5 margin-top-p5">friendly</li>
                <li class="g-col-auto border-0 background-color-white-warm-4 border-radius-small padding-y-p5 padding-x-1 line-height-smallest margin-right-p5 margin-top-p5">energetic</li>
                <li class="g-col-auto border-0 background-color-white-warm-4 border-radius-small padding-y-p5 padding-x-1 line-height-smallest margin-right-p5 margin-top-p5">outgoing</li>
                <li class="g-col-auto border-0 background-color-white-warm-4 border-radius-small padding-y-p5 padding-x-1 line-height-smallest margin-right-p5 margin-top-p5">all-American</li>
              </ul><!-- tags -->
              <div class="g-row margin-top-2 align-items-center">
                <a href="#0" class="g-col-auto line-height-smallest font-sans-1 font-weight-400 padding-y-1 padding-x-2 background-color-black-90 color-white border-radius-small text-decoration-none">
                  Download palette ⇣
                </a><!-- palette-button -->
                <a href="#0" class="g-col-auto margin-left-auto color-black-90 font-sans-1 text-decoration-underline line-height-smallest">See more examples</a>
              </div><!-- palette-actions -->
            </div><!-- palette-card -->
          </div><!-- card-column -->

          <!-- * * * * * * =================================== -->
          <div class="g-col-6">
            <div class="palette-card border border-radius-small padding-1 margin-top-3">
              <div class="g-row g-gap-2px">
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="height-1 display-flex align-items-center">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-indigo-20 height-1 margin-top-2px"></div>
                  <div class="background-color-indigo-30 height-1 margin-top-2px"></div>
                  <div class="background-color-indigo-50 height-1 margin-top-2px"></div>
                  <div class="background-color-indigo-50v height-1 margin-top-2px"></div>
                  <div class="background-color-indigo-70 height-1 margin-top-2px"></div>
                  <div class="background-color-indigo-90 height-1 margin-top-2px"></div>
                </div><!-- family-column -->
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="height-1 display-flex align-items-center">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-black-cool-30 height-1 margin-top-2px"></div>
                  <div class="background-color-black-cool-50 height-1 margin-top-2px"></div>
                  <div class="background-color-blue-warm-40 height-1 margin-top-2px"></div>
                  <div class="background-color-black-cool-70 height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                </div><!-- family-column -->
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="height-1 display-flex align-items-center">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-indigo-cool-20 height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-indigo-cool-40 height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                </div><!-- family-column -->
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="height-1 display-flex align-items-center">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-blue-warm-40 height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-blue-warm-50 height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                </div><!-- family-column -->
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="background-color-white-warm-3 height-1"></div>
                  <div class="background-color-black-warm-10 height-1 margin-top-2px"></div>
                  <div class="background-color-black-warm-30 height-1 margin-top-2px"></div>
                  <div class="background-color-black-warm-50 height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-black-warm-70 height-1 margin-top-2px"></div>
                  <div class="background-color-black-warm-90 height-1 margin-top-2px"></div>
                </div><!-- family-column -->
              </div> <!-- this-palette -->
              <h4 class="font-sans-5 margin-bottom-1 line-height-smaller">Marine</h4>
              <ul class="list-reset g-row g-gap font-sans-1 font-weight-400 margin-bottom-0 margin-x-0 min-height-6 align-items-flex-start margin-top-p5">
                <li class="g-col-auto border-0 background-color-white-warm-4 border-radius-small padding-y-p5 padding-x-1 line-height-smallest margin-right-p5">no nonsense</li>
                <li class="g-col-auto border-0 background-color-white-warm-4 border-radius-small padding-y-p5 padding-x-1 line-height-smallest margin-right-p5">professional</li>
                <li class="g-col-auto border-0 background-color-white-warm-4 border-radius-small padding-y-p5 padding-x-1 line-height-smallest margin-right-p5">conservative</li>
              </ul><!-- tags -->
              <div class="g-row margin-top-2 align-items-center">
                <a href="#0" class="g-col-auto line-height-smallest font-sans-1 font-weight-400 padding-y-1 padding-x-2 background-color-black-90 color-white border-radius-small text-decoration-none">
                  Download palette ⇣
                </a><!-- palette-button -->
                <a href="#0" class="g-col-auto margin-left-auto color-black-90 font-sans-1 text-decoration-underline line-height-smallest">See more examples</a>
              </div><!-- palette-actions -->
            </div><!-- palette-card -->
          </div><!-- card-column -->

          <!-- * * * * * * =================================== -->
          <div class="g-col-6">
            <div class="palette-card border border-radius-small padding-1 margin-top-3 display-flex flex-direction-column">
              <h4 class="font-sans-5 margin-bottom-p5 line-height-smaller order-2">Cascade</h4>
              <div class="g-row g-gap-2px order-first">
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="height-1 display-flex align-items-center">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-mint-cool-10 height-1 margin-top-2px"></div>
                  <div class="background-color-mint-cool-40 height-1 margin-top-2px"></div>
                  <div class="background-color-mint-cool-50 height-1 margin-top-2px"></div>
                  <div class="background-color-mint-cool-40v height-1 margin-top-2px"></div>
                  <div class="background-color-mint-cool-70 height-1 margin-top-2px"></div>
                  <div class="background-color-mint-cool-90 height-1 margin-top-2px"></div>
                </div><!-- family-column -->
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="height-1 display-flex align-items-center">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-mint-30 height-1 margin-top-2px"></div>
                  <div class="background-color-mint-40 height-1 margin-top-2px"></div>
                  <div class="background-color-mint-30v height-1 margin-top-2px"></div>
                  <div class="background-color-mint-50 height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                </div><!-- family-column -->
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="height-1 display-flex align-items-center">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-gold-20 height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-gold-40 height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                </div><!-- family-column -->
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="height-1 display-flex align-items-center">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-cyan-20 height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-cyan-40v height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                </div><!-- family-column -->
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="background-color-white-cool-2 height-1"></div>
                  <div class="background-color-black-cool-10 height-1 margin-top-2px"></div>
                  <div class="background-color-black-cool-30 height-1 margin-top-2px"></div>
                  <div class="background-color-black-cool-50 height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-black-cool-70 height-1 margin-top-2px"></div>
                  <div class="background-color-black-cool-90 height-1 margin-top-2px"></div>
                </div><!-- family-column -->
              </div> <!-- this-palette -->
              <ul class="order-3 list-reset g-row g-gap font-sans-1 font-weight-400 margin-bottom-0 margin-x-0 min-height-6 align-items-flex-start margin-top-p5">
                <li class="g-col-auto border-0 background-color-white-warm-4 border-radius-small padding-y-p5 padding-x-1 line-height-smallest margin-right-p5 margin-top-p5">fresh</li>
                <li class="g-col-auto border-0 background-color-white-warm-4 border-radius-small padding-y-p5 padding-x-1 line-height-smallest margin-right-p5 margin-top-p5">compassionate</li>
                <li class="g-col-auto border-0 background-color-white-warm-4 border-radius-small padding-y-p5 padding-x-1 line-height-smallest margin-right-p5 margin-top-p5">energetic</li>
                <li class="g-col-auto border-0 background-color-white-warm-4 border-radius-small padding-y-p5 padding-x-1 line-height-smallest margin-right-p5 margin-top-p5">healthy</li>
              </ul><!-- tags -->
              <div class="order-4 g-row margin-top-2 align-items-center">
                <a href="#0" class="g-col-auto line-height-smallest font-sans-1 font-weight-400 padding-y-1 padding-x-2 background-color-black-90 color-white border-radius-small text-decoration-none">
                  Download palette ⇣
                </a><!-- palette-button -->
                <a href="#0" class="g-col-auto margin-left-auto color-black-90 font-sans-1 text-decoration-underline line-height-smallest">See more examples</a>
              </div><!-- palette-actions -->
            </div><!-- palette-card -->
          </div><!-- card-column -->

          <!-- * * * * * * =================================== -->
          <div class="g-col-6">
            <div class="palette-card border border-radius-small padding-1 margin-top-3 display-flex flex-direction-column">
              <h4 class="font-sans-5 margin-bottom-p5 line-height-smaller order-2">Columbia</h4>
              <div class="g-row g-gap-2px order-first">
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="height-1 display-flex align-items-center">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-blue-10 height-1 margin-top-2px"></div>
                  <div class="background-color-blue-30 height-1 margin-top-2px"></div>
                  <div class="background-color-blue-40 height-1 margin-top-2px"></div>
                  <div class="background-color-blue-40v height-1 margin-top-2px"></div>
                  <div class="background-color-blue-70 height-1 margin-top-2px"></div>
                  <div class="background-color-blue-90 height-1 margin-top-2px"></div>
                </div><!-- family-column -->
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="height-1 display-flex align-items-center">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-gold-40 height-1 margin-top-2px"></div>
                  <div class="background-color-gold-60 height-1 margin-top-2px"></div>
                  <div class="background-color-gold-40v height-1 margin-top-2px"></div>
                  <div class="background-color-gold-80 height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                </div><!-- family-column -->
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="height-1 display-flex align-items-center">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-gold-20 height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-gold-40 height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                </div><!-- family-column -->
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="height-1 display-flex align-items-center">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-blue-warm-40 height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-blue-warm-50 height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                </div><!-- family-column -->
                <!-- ========================================= -->
                <div class="g-col-fill">
                  <div class="background-color-white-cool-1 height-1"></div>
                  <div class="background-color-black-cool-5 height-1 margin-top-2px"></div>
                  <div class="background-color-black-cool-30 height-1 margin-top-2px"></div>
                  <div class="background-color-black-cool-50 height-1 margin-top-2px"></div>
                  <div class="height-1 display-flex align-items-center margin-top-2px">
                    <div class="margin-x-auto circle-2px background-color-black-90"></div>
                  </div><!-- blank -->
                  <div class="background-color-black-cool-70 height-1 margin-top-2px"></div>
                  <div class="background-color-black-cool-90 height-1 margin-top-2px"></div>
                </div><!-- family-column -->
              </div> <!-- this-palette -->
              <ul class="order-3 list-reset g-row g-gap font-sans-1 font-weight-400 margin-bottom-0 margin-x-0 min-height-6 align-items-flex-start margin-top-p5">
                <li class="g-col-auto border-0 background-color-white-warm-4 border-radius-small padding-y-p5 padding-x-1 line-height-smallest margin-right-p5">clean</li>
                <li class="g-col-auto border-0 background-color-white-warm-4 border-radius-small padding-y-p5 padding-x-1 line-height-smallest margin-right-p5">fresh</li>
                <li class="g-col-auto border-0 background-color-white-warm-4 border-radius-small padding-y-p5 padding-x-1 line-height-smallest margin-right-p5">earthy</li>
                <li class="g-col-auto border-0 background-color-white-warm-4 border-radius-small padding-y-p5 padding-x-1 line-height-smallest margin-right-p5 margin-top-p5">earnest</li>
              </ul><!-- tags -->
              <div class="order-4 g-row margin-top-2 align-items-center">
                <a href="#0" class="g-col-auto line-height-smallest font-sans-1 font-weight-400 padding-y-1 padding-x-2 background-color-black-90 color-white border-radius-small text-decoration-none">
                  Download palette ⇣
                </a><!-- palette-button -->
                <a href="#0" class="g-col-auto margin-left-auto color-black-90 font-sans-1 text-decoration-underline line-height-smallest">See more examples</a>
              </div><!-- palette-actions -->
            </div><!-- palette-card -->
          </div><!-- card-column -->

        </div><!-- palettes -->

        <h2 class="font-sans-10 margin-y-4 border-top-1px padding-top-2">Downloading and using palettes</h2>
        <p>Selecting <strong>Download palette</strong> will download a small SCSS file named <code>_theme-palette-[palette-name].scss</code>. Its contents set the USWDS variables necessary to use these colors in your project. (Developers, this is the same as manually setting these values in <code>_uswds-project-settings.scss</code>.)</p>
        <pre class="max-width-full background-color-white-warm-4  padding-2 white-space-pre-wrap margin-y-4">
<code class="font-mono-1 padding-0">&lt;!-- * * * * * * =================================== -->
// USWDS Project theme palette
// _theme-palette-onondaga.scss

$neutral:                         black;
$theme-color-neutral-lightest:    $neutral, 2;
$theme-color-neutral-lighter:     $neutral, 10;
$theme-color-neutral-light:       $neutral, 30;
$theme-color-neutral-base:        $neutral, 50;
$theme-color-neutral-dark:        $neutral, 70;
$theme-color-neutral-darker:      $neutral, 70;

$primary:                         blue;
$theme-color-primary-lighter:     $primary, 10;
$theme-color-primary-light:       $primary, 30;
$theme-color-primary-base:        $primary, 50;
$theme-color-primary-vivid:       $primary, 50, vivid;
$theme-color-primary-dark:        $primary, 70;
$theme-color-primary-darker:      false;

$secondary:                       mint;
$theme-color-secondary-light:     $secondary, 50;
$theme-color-secondary-base:      $secondary, 60;
$theme-color-secondary-vivid:     $secondary, 50, vivid;
$theme-color-secondary-dark:      $secondary, 80;

$accent-warm:                     orange;
$theme-color-accent-warm-base:    $accent-warm, 50, vivid;
$theme-color-accent-warm-dark:    $accent-warm, 50, vivid;

$accent-cool:                     cyan;
$theme-color-accent-cool-base:    $accent-cool, 50, vivid;
$theme-color-accent-cool-dark:    $accent-cool, 50, vivid;</code></pre>

        <p>Move this file to your project’s SASS directory and <code>@import</code> it after your existing project settings and before <code>@import 'uswds'</code>.</p>

<pre class="max-width-full background-color-white-warm-4 padding-2 white-space-pre-wrap margin-y-4"><code class="font-mono-1 padding-0">@import 'uswds-project-settings';
@import 'uswds-project-utilities-settings';
@import 'theme-palette-onondaga'; // &lt;-- Add the palette import here.
@import 'uswds';
@import 'uswds-project-custom';
</code></pre>

        <p><strong>Visual designers</strong> we don’t have a solution for providing these palettes in Sketch or Illustator just yet, but we’re working on it!</p>

      </div>
    </div>

  </div><!-- l.container -->
</div><!-- div -->

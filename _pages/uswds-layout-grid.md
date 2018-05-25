---
layout: prototype-clean
title: USWDS layout grid draft
permalink: /uswds-layout-grid/
---

<div class="size-mono-4 weight-300 padding-top-2 padding-bottom-4 tablet:padding-top-4 tablet:padding-bottom-9">

  <div class="grid-container-tablet-lg padding-x-2 margin-top-1">
    <h1 class="size-sans-14 text-300 margin-top-0">USWDS draft layout grid</h1>
    <p class="docs-text"><strong>Note:</strong> <code class="docs-inline-code">.grid-container</code>, <code class="docs-inline-code">.grid-gap</code>, and <code class="docs-inline-code">.grid-col</code> all have mobile-first responsive variants. Only the first example shows them.</p>
    <p class="docs-text"><code class="docs-inline-code">.grid-col</code> and <code class="docs-inline-code">.grid-col-fill</code> items flex to fit</p>

    <div class="grid-row margin-top-1">
      <div class="grid-col-6 tablet-lg:grid-col-fill border-1px border-black-cool-10">
        <div class="display-none tablet-lg:display-block text-center padding-2">.tablet-lg:grid-col</div>
        <div class="tablet-lg:display-none text-center padding-2">.grid-col-6</div>
      </div>
      <div class="grid-col-6 tablet-lg:grid-col-fill border-1px border-left-0 border-black-cool-10">
        <div class="display-none tablet-lg:display-block text-center padding-2">.tablet-lg:grid-col</div>
        <div class="tablet-lg:display-none text-center padding-2">.grid-col-6</div>
      </div>
      <div class="grid-col-4 tablet-lg:grid-col-fill border-1px border-top-0 tablet-lg:border-top-1px tablet-lg:border-left-0 border-black-cool-10">
        <div class="display-none tablet-lg:display-block text-center padding-2">.tablet-lg:grid-col</div>
        <div class="tablet-lg:display-none text-center padding-2">.grid-col-4</div>
      </div>
      <div class="grid-col-4 tablet-lg:grid-col-fill border-1px border-top-0 tablet-lg:border-top-1px border-left-0 border-black-cool-10">
        <div class="display-none tablet-lg:display-block text-center padding-2">.tablet-lg:grid-col</div>
        <div class="tablet-lg:display-none text-center padding-2">.grid-col-4</div>
      </div>
      <div class="grid-col-4 tablet-lg:grid-col-fill border-1px border-top-0 tablet-lg:border-top-1px border-left-0 border-black-cool-10">
        <div class="display-none tablet-lg:display-block text-center padding-2">.tablet-lg:grid-col</div>
        <div class="tablet-lg:display-none text-center padding-2">.grid-col-4</div>
      </div>
    </div><!-- grid-row -->

    <div class="grid-row margin-top-1">
      <div class="grid-col tablet:grid-col-fill border-1px border-black-cool-10">
        <div class="display-none tablet:display-block text-center padding-2">.tablet:grid-col</div>
        <div class="tablet:display-none text-center padding-2">.grid-col</div>
      </div>
      <div class="grid-col tablet:grid-col-fill border-1px border-left-0 tablet:border-top-1px tablet:border-left-0 border-black-cool-10">
        <div class="display-none tablet:display-block text-center padding-2">.tablet:grid-col</div>
        <div class="tablet:display-none text-center padding-2">.grid-col</div>
      </div>
      <div class="grid-col tablet:grid-col-fill border-1px border-left-0 tablet:border-top-1px tablet:border-left-0 border-black-cool-10">
        <div class="display-none tablet:display-block text-center padding-2">.tablet:grid-col</div>
        <div class="tablet:display-none text-center padding-2">.grid-col</div>
      </div>
    </div><!-- grid-row -->

    <p class="docs-text"><code class="docs-inline-code">.grid-col-auto</code> items fit the content and do not flex</p>

    <div class="grid-row margin-top-1">
      <div class="grid-col-auto border-1px border-black-cool-10">
        <div class="text-center padding-2">.grid-col-auto</div>
      </div>
      <div class="grid-col-fill border-1px border-left-0 border-black-cool-10">
        <div class="text-center padding-2">.grid-col</div>
      </div>
      <div class="grid-col-fill border-1px border-left-0 border-black-cool-10">
        <div class="text-center padding-2">.grid-col</div>
      </div>
      <div class="grid-col-auto border-1px border-left-0 border-black-cool-10">
        <div class="text-center padding-2">.grid-col-auto</div>
      </div>
    </div><!-- l.grid-row -->

    <p class="docs-text"><code class="docs-inline-code">.grid-col-[1-12]</code> set a fixed width of [n] grid-columns in a 12-column grid</p>

    <div class="grid-row margin-top-1 size-sans-2">
      <div class="grid-col-1 border-x-2px border-black-cool-90">
        <div class="text-center padding-x-2">1</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">2</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">3</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">4</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">5</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">6</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">7</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">8</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">9</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">10</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">11</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">12</div>
      </div>
    </div><!-- l.grid-row -->

    <div class="grid-row margin-top-1">
      <div class="grid-col-1 border-1px border-black-cool-10">
        <div class="text-center padding-2">.grid-col-1</div>
      </div>
      <div class="grid-col-2 border-1px border-left-0 border-black-cool-10">
        <div class="text-center padding-2">.grid-col-2</div>
      </div>
      <div class="grid-col-3 border-1px border-left-0 border-black-cool-10">
        <div class="text-center padding-2">.grid-col-3</div>
      </div>
      <div class="grid-col-4 border-1px border-left-0 border-black-cool-10">
        <div class="text-center padding-2">.grid-col-4</div>
      </div>
      <div class="grid-col-2 border-1px border-left-0 border-black-cool-10">
        <div class="text-center padding-2">.grid-col-2</div>
      </div>
    </div><!-- l.grid-row -->

    <div class="grid-row margin-top-1">
      <div class="grid-col-8 border-1px border-black-cool-10">
        <div class="text-center padding-2">.grid-col-8</div>
      </div>
      <div class="grid-col-2 border-1px border-left-0 border-black-cool-10">
        <div class="text-center padding-2">.grid-col-2</div>
      </div>
      <div class="grid-col-2 border-1px border-left-0 border-black-cool-10">
        <div class="text-center padding-2">.grid-col-2</div>
      </div>
    </div><!-- l.grid-row -->

    <p class="docs-text"><code class="docs-inline-code">.offset-[1-12]</code> offsets the grid-column by [n] grid-columns</p>

    <div class="grid-row margin-top-1 size-sans-2">
      <div class="grid-col-1 border-x-2px border-black-cool-90">
        <div class="text-center padding-x-2">1</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">2</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">3</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">4</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">5</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">6</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">7</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">8</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">9</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">10</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">11</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">12</div>
      </div>
    </div><!-- l.grid-row -->

    <div class="grid-row margin-top-1">
      <div class="grid-col-8 offset-4 border-1px border-black-cool-10">
        <div class="text-center padding-2">.grid-col-8.offset-4</div>
      </div>
    </div><!-- l.grid-row -->

    <p class="docs-text">Rows wrap when grid-columns add up to more than 12</p>

    <div class="grid-row margin-top-1 size-sans-2">
      <div class="grid-col-1 border-x-2px border-black-cool-90">
        <div class="text-center padding-x-2">1</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">2</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">3</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">4</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">5</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">6</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">7</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">8</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">9</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">10</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">11</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">12</div>
      </div>
    </div><!-- l.grid-row -->

    <div class="grid-row margin-top-1">
      <div class="grid-col-8 border-1px border-black-cool-10">
        <div class="text-center padding-2">.grid-col-8</div>
      </div>
      <div class="grid-col-3 border-1px border-left-0 border-black-cool-10">
        <div class="text-center padding-2">.grid-col-3</div>
      </div>
      <div class="grid-col-5 border-1px border-top-0 border-black-cool-10">
        <div class="text-center padding-2">.grid-col-5</div>
      </div>
    </div><!-- l.grid-row -->

    <p class="docs-text"><code class="docs-inline-code">.grid-gap</code> adds a grid-gap between grid-columns in the grid-row, to a value set as <code class="docs-inline-code">$theme-column-gap</code> in settings</p>

    <div class="grid-row margin-top-1 size-sans-2">
      <div class="grid-col-1 border-x-2px border-black-cool-90">
        <div class="text-center padding-x-2">1</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">2</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">3</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">4</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">5</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">6</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">7</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">8</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">9</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">10</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">11</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">12</div>
      </div>
    </div><!-- l.grid-row -->

    <div class="grid-row grid-gap margin-top-1">
      <div class="grid-col-4">
        <div class="text-center border-1px border-black-cool-10 padding-2">.grid-col-8</div>
      </div>
      <div class="grid-col-4">
        <div class="text-center border-1px border-black-cool-10 padding-2">.grid-col-3</div>
      </div>
      <div class="grid-col-4">
        <div class="text-center border-1px border-black-cool-10 padding-2">.grid-col-5</div>
      </div>
    </div><!-- l.grid-row -->

    <p class="docs-text"><code class="docs-inline-code">.grid-gap-lg</code> adds a grid-gap between grid-columns in the grid-row, to a value set as <code class="docs-inline-code">$theme-column-gap-large</code> in settings</p>

    <div class="grid-row margin-top-1 size-sans-2">
      <div class="grid-col-1 border-x-2px border-black-cool-90">
        <div class="text-center padding-x-2">1</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">2</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">3</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">4</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">5</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">6</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">7</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">8</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">9</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">10</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">11</div>
      </div>
      <div class="grid-col-1 border-x-2px border-left-0 border-black-cool-90">
        <div class="text-center padding-x-2">12</div>
      </div>
    </div><!-- l.grid-row -->

    <div class="grid-row grid-gap-lg margin-top-1">
      <div class="grid-col-4">
        <div class="text-center border-1px border-black-cool-10 padding-2">.grid-col-8</div>
      </div>
      <div class="grid-col-4">
        <div class="text-center border-1px border-black-cool-10 padding-2">.grid-col-3</div>
      </div>
      <div class="grid-col-4">
        <div class="text-center border-1px border-black-cool-10 padding-2">.grid-col-5</div>
      </div>
    </div><!-- l.grid-row -->

  </div><!-- l.grid-container -->
</div><!-- div -->

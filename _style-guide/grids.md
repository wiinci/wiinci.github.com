---
title: "Grids"
type: grids
---

<section class="guide page-section">
    <h2>Eight columns</h2>
    <p><code>col col-1-8 col-lg-4 col-md-2 col-sm-1</code></p>
    <p>8-column layout &rarr; 4-column at 960px <code>(lg)</code> &rarr; 2-column at 640px <code>(md)</code> &rarr; one-column at 480px <code>(sm)</code>.</p>
    <div class="row">
        <div class="col col-1-8 col-lg-4 col-md-2 col-sm-1">
            <div class="col-content"><code>1/8</code></div>
        </div>
        <div class="col col-1-8 col-lg-4 col-md-2 col-sm-1">
            <div class="col-content"><code>1/8</code></div>
        </div>
        <div class="col col-1-8 col-lg-4 col-md-2 col-sm-1">
            <div class="col-content"><code>1/8</code></div>
        </div>
        <div class="col col-1-8 col-lg-4 col-md-2 col-sm-1">
            <div class="col-content"><code>1/8</code></div>
        </div>
        <div class="col col-1-8 col-lg-4 col-md-2 col-sm-1">
            <div class="col-content"><code>1/8</code></div>
        </div>
        <div class="col col-1-8 col-lg-4 col-md-2 col-sm-1">
            <div class="col-content"><code>1/8</code></div>
        </div>
        <div class="col col-1-8 col-lg-4 col-md-2 col-sm-1">
            <div class="col-content"><code>1/8</code></div>
        </div>
        <div class="col col-1-8 col-lg-4 col-md-2 col-sm-1">
            <div class="col-content"><code>1/8</code></div>
        </div>
    </div>
    <h2>Six columns</h2>
    <p><code>col col-1-6 col-lg-3 col-md-2 col-sm-1</code></p>
    <p>6-column layout &rarr; 3-column at 960px <code>(lg)</code> &rarr; 2-column at 640px <code>(md)</code> &rarr; one-column at 480px <code>(sm)</code>.</p>
    <div class="row">
        <div class="col col-1-6 col-lg-3 col-md-2 col-sm-1">
            <div class="col-content"><code>1/6</code></div>
        </div>
        <div class="col col-1-6 col-lg-3 col-md-2 col-sm-1">
            <div class="col-content"><code>1/6</code></div>
        </div>
        <div class="col col-1-6 col-lg-3 col-md-2 col-sm-1">
            <div class="col-content"><code>1/6</code></div>
        </div>
        <div class="col col-1-6 col-lg-3 col-md-2 col-sm-1">
            <div class="col-content"><code>1/6</code></div>
        </div>
        <div class="col col-1-6 col-lg-3 col-md-2 col-sm-1">
            <div class="col-content"><code>1/6</code></div>
        </div>
        <div class="col col-1-6 col-lg-3 col-md-2 col-sm-1">
            <div class="col-content"><code>1/6</code></div>
        </div>
    </div>
    <h2>Four columns</h2>
    <p><code>col col-1-4 col-md-2 col-sm-1</code></p>
    <p>4-column layout &rarr; 2-column at 640px <code>(md)</code> &rarr; one-column at 480px <code>(sm)</code>.</p>
    <div class="row">
        <div class="col col-1-4 col-md-2 col-sm-1">
            <div class="col-content"><code>1/4</code></div>
        </div>
        <div class="col col-1-4 col-md-2 col-sm-1">
            <div class="col-content"><code>1/4</code></div>
        </div>
        <div class="col col-1-4 col-md-2 col-sm-1">
            <div class="col-content"><code>1/4</code></div>
        </div>
        <div class="col col-1-4 col-md-2 col-sm-1">
            <div class="col-content"><code>1/4</code></div>
        </div>
    </div>
    <h2>Three columns</h2>
    <p><code>col col-1-3 col-md-1</code></p>
    <p>3-column layout &rarr; one-column at 640px <code>(md)</code>.</p>
    <div class="row">
        <div class="col col-1-3 col-md-1">
            <div class="col-content"><code>1/3</code></div>
        </div>
        <div class="col col-1-3 col-md-1">
            <div class="col-content"><code>1/3</code></div>
        </div>
        <div class="col col-1-3 col-md-1">
            <div class="col-content"><code>1/3</code></div>
        </div>
    </div>
    <h2>Two columns</h2>
    <p><code>col col-1-2 col-sm-1</code></p>
    <p>2-column layout &rarr; one-column at 480px <code>(sm)</code>.</p>
    <div class="row">
        <div class="col col-1-2 col-sm-1">
            <div class="col-content"><code>1/2</code></div>
        </div>
        <div class="col col-1-2 col-sm-1">
            <div class="col-content"><code>1/2</code></div>
        </div>
    </div>
</section>

<section class="guide page-section">
    <h2>Nested columns</h2>
    <div class="row">
        <div class="col col-1-1">
            <div class="row">
                <div class="col col-1-2 col-md-2 col-sm-1">
                    <div class="row">
                        <div class="col col-1-1">
                            <div class="col-content"><code>1/1 nested</code></div>
                        </div>
                        <div class="col col-1-1">
                            <div class="col-content"><code>1/1 nested</code></div>
                        </div>
                    </div>
                </div>
                <div class="col col-1-2 col-md-2 col-sm-1">
                    <div class="row">
                        <div class="col col-1-3 col-md-1">
                            <div class="col-content"><code>1/3 nested</code></div>
                        </div>
                        <div class="col col-2-3 col-md-1">
                            <div class="col-content"><code>2/3 nested</code></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>
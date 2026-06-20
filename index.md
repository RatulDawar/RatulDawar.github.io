---
layout: default
title: Ratul Dawar's Blog
---

<section class="home-hero">
  <p class="eyebrow">Performance · Rust · Query engines</p>
  <h1>Systems programming,<br>measured.</h1>
  <p class="lede">Deep dives into Rust experiments, Apache DataFusion contributions, and the mechanics behind real speedups — with benchmarks, not vibes.</p>
</section>

<p class="section-label">Latest writing</p>

<div class="post-grid">
  <article class="post-card featured">
    <div>
      <div class="card-meta">
        <time datetime="2026-06-20">June 20, 2026</time>
        <span class="card-tag">DataFusion</span>
      </div>
      <h2><a href="{{ '/posts/datafusion-parquet-page-index-skip/' | relative_url }}">Inside a DataFusion Parquet Scan: Skipping Page Index I/O When Statistics Already Decide</a></h2>
      <p>How the Parquet opener prunes at file, row-group, page, and bloom-filter layers — and why PR #22857 stops loading page index metadata when row-group statistics already prove the filter.</p>
      <a class="read-more" href="{{ '/posts/datafusion-parquet-page-index-skip/' | relative_url }}">Read the post →</a>
    </div>
    <div class="card-visual">
      <img src="{{ '/posts/assets/parquet-scan-pipeline.svg' | relative_url }}" alt="DataFusion Parquet scan pipeline diagram">
    </div>
  </article>

  <article class="post-card">
    <div class="card-meta">
      <time datetime="2026-04-19">April 19, 2026</time>
      <span class="card-tag">DataFusion</span>
    </div>
    <h2><a href="{{ '/posts/datafusion-string-view-performance/' | relative_url }}">Zero-Copy Strings in Apache DataFusion</a></h2>
    <p>How StringViewArray cut the copy tax on string operations and lifted ClickBench performance by 8%.</p>
    <a class="read-more" href="{{ '/posts/datafusion-string-view-performance/' | relative_url }}">Read the post →</a>
  </article>

  <article class="post-card">
    <div class="card-meta">
      <time datetime="2026-03-10">March 10, 2026</time>
      <span class="card-tag">Async</span>
    </div>
    <h2><a href="{{ '/posts/tokio-vs-thread-spawning-which-is-better/' | relative_url }}">Async Runtimes vs Threads in Rust</a></h2>
    <p>Tokio wins on tiny workloads; threads catch up when the work is pure CPU. A measured guide to when each model fits.</p>
    <a class="read-more" href="{{ '/posts/tokio-vs-thread-spawning-which-is-better/' | relative_url }}">Read the post →</a>
  </article>

  <article class="post-card">
    <div class="card-meta">
      <time datetime="2026-03-04">March 4, 2026</time>
      <span class="card-tag">Concurrency</span>
    </div>
    <h2><a href="{{ '/posts/atomics-vs-mutex-contention/' | relative_url }}">Atomics vs Mutex in Rust</a></h2>
    <p>Why a mutex beat atomics under heavy contention — with flamegraphs and a counterintuitive takeaway.</p>
    <a class="read-more" href="{{ '/posts/atomics-vs-mutex-contention/' | relative_url }}">Read the post →</a>
  </article>

  <article class="post-card">
    <div class="card-meta">
      <time datetime="2026-02-28">February 28, 2026</time>
      <span class="card-tag">CPU</span>
    </div>
    <h2><a href="{{ '/posts/cache-padding-false-sharing/' | relative_url }}">Cache Padding &amp; False Sharing</a></h2>
    <p>How 56 bytes of padding turned a 749ms benchmark into 163ms — the hidden cost of cache-line ping-pong.</p>
    <a class="read-more" href="{{ '/posts/cache-padding-false-sharing/' | relative_url }}">Read the post →</a>
  </article>
</div>
